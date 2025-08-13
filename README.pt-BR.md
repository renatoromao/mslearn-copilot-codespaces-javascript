# Template de Portfolio JavaScript — Accenture (Codespaces)

Bem-vindos! Este repositório é um template de portfolio web em JavaScript/React, preparado para uso em GitHub Codespaces e em execução local. A identidade visual está adaptada ao tema Accenture (tons de roxo e preto).

## Requisitos
- Node.js 18+ e npm
- GitHub Codespaces (opcional, mas recomendado)

## Como começar (Codespaces)
1. Abra este repositório no GitHub e clique em "Code" > "Create codespace on main".
2. Aguarde a criação do ambiente. O VS Code Web abrirá automaticamente.
3. No terminal integrado, instale dependências (se necessário) e inicie:

```bash
npm install
npm start
```

4. A aplicação abrirá em uma porta pública do Codespaces. Se o preview não abrir sozinho, verifique a aba "Ports" e clique no link da porta exposta.

## Como rodar localmente
1. Clone o repositório:
```bash
git clone <url-do-repositorio>
cd mslearn-copilot-codespaces-javascript
```
2. Instale as dependências e inicie o servidor de desenvolvimento:
```bash
npm install
npm start
```
3. Acesse http://localhost:1234

## Como gerar build de produção
```bash
npm run build
```
Os artefatos ficarão na pasta `dist/`.

## Publicar no GitHub Pages (opcional)
Atualize o script `build-gh` no `package.json`, substituindo `{github-username}` e `{repo-name}`; depois rode:
```bash
npm run predeploy
npm run deploy
```

## Estrutura do projeto
- `src/` — código-fonte
  - `index.html`, `index.js`, `App.jsx`
  - `Components/` — componentes React (ex.: `Home.jsx`)
  - `styles.css` — estilos globais (tema Accenture)
  - `images/` — imagens e ícones

## Personalização (Identidade Accenture)
- A Home utiliza classes `acc_home`, `acc_home_title`, `acc_home_subtitle` e `acc_arrow` definidas em `src/styles.css`.
- Cores principais: `#a259ff` (roxo), `#2e085a` (roxo escuro).
- Tipografia: Montserrat (UI) e Cormorant Garamond (títulos).

## Dicas
- Edite `src/Components/Home.jsx` para alterar nome, título e imagem de fundo.
- Substitua imagens em `src/images/` conforme desejar.
- Ajuste estilos em `src/styles.css` para refinar o tema.

## Qualidade de código
- Lint/format (opcional):
```bash
npx eslint src --ext .js,.jsx
npx prettier --check .
```

## Suporte
Se encontrar problemas:
- Verifique se a versão do Node está atualizada
- Limpe a pasta `.parcel-cache` e rode novamente:
```bash
rm -rf .parcel-cache dist
npm start
```

---
Feito com ❤️ para os alunos da Accenture.
