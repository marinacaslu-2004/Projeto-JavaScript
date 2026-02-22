# Ecommerce (DT STORE)

Projeto frontend estático de uma loja (Ecommerce) construído com HTML, JavaScript e Tailwind CSS. Inclui um catálogo de produtos, carrinho modal, cálculo de total e validação básica de endereço.

## Tecnologias

- HTML5
- JavaScript (vanilla)
- Tailwind CSS (devDependency no projeto)
- Font Awesome (CDN)

## Funcionalidades

- Exibição de catálogo de produtos
- Adição de itens ao carrinho
- Modal para visualizar o carrinho e finalizar pedido
- Cálculo do total do carrinho
- Validação simples de endereço no checkout
- Layout responsivo com Tailwind

## Scripts disponíveis

O `package.json` inclui o script abaixo para compilar o CSS do Tailwind em modo de desenvolvimento:

- `npm run dev`

Ele executa:

```
npx tailwindcss -i ./styles/style.css -o ./styles/output.css --watch
```

## Como executar localmente

Pré-requisitos: ter o Node.js e o npm instalados.

1. Na raiz do projeto, instale dependências (opcional, apenas para garantir o Tailwind local):

```
npm install
```

2. Para compilar o CSS do Tailwind em modo watch:

```
npm run dev
```

3. Abra `index.html` no seu navegador (ou sirva os arquivos estáticos via um servidor HTTP local, por exemplo `npx serve` ou `Live Server` no VS Code).

## Dicas de build para produção

Para gerar CSS minificado para produção, rode:

```
npx tailwindcss -i ./styles/style.css -o ./styles/output.css --minify
```

## Estrutura do projeto

- `index.html` — página principal da loja
- `script.js` — lógica do carrinho e interações
- `package.json` — scripts e dependências de desenvolvimento
- `tailwind.config.js` — configuração do Tailwind
- `styles/style.css` — arquivo fonte com diretivas do Tailwind
- `styles/output.css` — CSS compilado (gerado pelo script)
- `assets/` — imagens e logos usados no projeto

## Observações

- O projeto é um protótipo front-end estático; não há backend ou persistência além do tempo de sessão.
- As imagens e preços no catálogo são exemplos e podem ser substituídos em `assets/` e no HTML.

## Contribuições

Este repositório NÃO está aceitando contribuições externas no momento. Pull requests, forks ou submissions não serão revisados.

Se você precisa colaborar ou tem uma sugestão importante, entre em contato diretamente com a proprietária do projeto através do perfil do GitHub.

## Licença

Este projeto está licenciado sob a licença ISC. Veja o arquivo `LICENSE` na raiz do repositório para os termos completos.

Direitos e propósito:

- Copyright (c) 2026 Marina Lucas.
- O propósito deste projeto é exclusivamente didático/educacional — serve como exemplo e exercício de frontend.
- A licença ISC permite uso, cópia, modificação e distribuição desde que o aviso de copyright e a permissão sejam mantidos. Apesar disso, este repositório NÃO aceita contribuições externas (veja `CONTRIBUTING.md`).

