# Igrejinha RP - Site de Regras

Projeto React + Vite pronto para publicar no Vercel.

## Como rodar no computador

```bash
npm install
npm run dev
```

## Como publicar no Vercel

### Opção 1: GitHub + Vercel
1. Crie um repositório no GitHub.
2. Envie todos os arquivos deste projeto para o repositório.
3. Entre no Vercel.
4. Clique em **Add New Project**.
5. Importe o repositório.
6. O Vercel detectará automaticamente o projeto Vite.
7. Clique em **Deploy**.

### Opção 2: Upload manual no Vercel
1. Instale as dependências:
```bash
npm install
```
2. Gere a versão final:
```bash
npm run build
```
3. Envie a pasta `dist` para o Vercel.

## Arquivos principais
- `src/App.jsx` → conteúdo do site
- `src/styles.css` → visual do site
- `package.json` → dependências
- `vercel.json` → configuração básica do Vercel

## Personalizações rápidas
- Trocar o link do botão Discord em `src/App.jsx`
- Alterar nome da cidade em `src/App.jsx`
- Ajustar cores em `src/styles.css`
