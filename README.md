# Pesquisa Culturama — Formulário

> Formulário simples para coleta de respostas da pesquisa do projeto Culturama.

## Descrição

Este repositório contém um formulário web estático para coletar respostas de usuários sobre cultura e eventos. Este projeto foi desenvolvido junto com um curso da Alura. É uma página leve, sem backend, pensada para uso local ou deploy estático (por exemplo, GitHub Pages).

## Status

Em produção leve — pronto para uso e fácil de personalizar.

## Tecnologias

- HTML5
- CSS3

## Pré-requisitos

Nenhum servidor é necessário. Para visualização local, abra o arquivo [index.html](index.html) no navegador ou use uma extensão como Live Server.

## Como usar

1. Abra [index.html](index.html) no seu navegador.
2. Preencha o formulário e envie para ver a página de sucesso ([sucesso.html](sucesso.html)).

Dica: para testes mais realistas com rotas e assets, rode um servidor estático (ex.: `npx serve` ou Live Server no VS Code).

## Estrutura do projeto

- [index.html](index.html) — página principal com o formulário
- [sucesso.html](sucesso.html) — página exibida após envio
- css/
  - [style.css](css/style.css) — estilos do projeto
- img/ — imagens usadas no formulário e na interface

## Personalização

- Para alterar estilos visuais, edite `css/style.css`.
- Para ajustar campos do formulário, edite `index.html` (labels, placeholders e atributos `required`).
- Para mudar a página exibida após envio, edite `sucesso.html`.

## Acessibilidade e boas práticas

- Certifique-se de que cada `<input>` tenha um `<label>` associado.
- Use atributos `required` e tipos de input apropriados (`email`, `tel`, etc.).
- Verifique contraste de cores em `css/style.css` para legibilidade.

## Deploy

1. Commit e push para um repositório GitHub.
2. Ative GitHub Pages nas configurações do repositório (branch `main`/`root`).

Ou hospede em qualquer serviço de arquivos estáticos (Netlify, Vercel, Surge).

