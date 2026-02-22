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

## Como contribuir

1. Faça um fork/clone do repositório.
2. Abra uma branch para sua feature/bugfix.
3. Faça commits pequenos e claros.
4. Envie um pull request descrevendo as alterações.

## Licença

O `package.json` indica `ISC`. Ajuste conforme necessário.

---

Se quiser, eu posso:

- adaptar o README com instruções de deploy específicas,
- adicionar exemplos de commits ou template de PR,
- ou commitar o README para o repositório. Informe o que prefere.
