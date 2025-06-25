# Projeto: Formulário Web com HTML e CSS

---

## Descrição do Projeto

Este projeto consiste na criação de um **formulário web** utilizando os conceitos básicos de **HTML** e **CSS**. O formulário deverá conter campos essenciais para coleta de informações do usuário.

---

## Requisitos do Formulário

O formulário deve conter obrigatoriamente os seguintes campos:

- **Nome**  
  Campo para inserção do nome completo do usuário.

- **E-mail**  
  Campo para inserir o endereço de e-mail válido.

- **Telefone**  
  Campo para inserir o número de telefone.

- **Opção de Contato**  
  Campo para o usuário escolher a forma preferida de contato (exemplo: telefone, e-mail).

- **Botão Enviar**  
  Botão para envio dos dados preenchidos no formulário.

---

## Tecnologias Utilizadas

- **HTML** para estruturar o formulário e seus campos.
- **CSS** para estilizar o formulário, garantindo uma boa experiência visual e usabilidade.

---

## Estrutura Básica do Formulário

- Utilizar elementos semânticos do HTML5, como `<form>`, `<label>`, `<input>`, `<select>`, e `<button>`.
- Garantir que todos os campos essenciais sejam devidamente identificados e marcados como obrigatórios, se aplicável.
- Estilização externa ou interna para deixar o formulário visualmente agradável e responsivo.

---

## Exemplo Simples de Uso

```html
<form>
  <label for="nome">Nome:</label>
  <input type="text" id="nome" name="nome" required>

  <label for="email">E-mail:</label>
  <input type="email" id="email" name="email" required>

  <label for="telefone">Telefone:</label>
  <input type="tel" id="telefone" name="telefone" required>

  <label for="contato">Opção de Contato:</label>
  <select id="contato" name="contato" required>
    <option value="email">E-mail</option>
    <option value="telefone">Telefone</option>
  </select>

  <button type="submit">Enviar</button>
</form>
