# Tecnologia para FrontEnd Avançado - Projeto Universitário - UNIESP 🌐

O projeto a seguir, trata-se de uma aplicação de um site universitário desenvolvido em **React** utilizando o **Vite** como bundler. Permite aos usuários navegar pelas páginas principais e aos administradores gerenciar notícias.

---

## Estrutura do Projeto 🗂️

```plaintext
📂 UNIESP
├── 📂 data
│   └── db.json
├── 📂 public
│   └── [imagens públicas]
├── 📂 src
│   ├── 📂 assets
│   ├── 📂 components
│   │   ├── BannerAd.jsx
│   │   └── Navbar.jsx
│   ├── 📂 pages
│   │   ├── 📂 Admin
│   │   │   ├── AdminNoticias.jsx
│   │   │   ├── CadastroNoticia.jsx
│   │   │   └── EditarNoticias.jsx
│   │   ├── Faculdade.jsx
│   │   ├── DpoLgpd.jsx
│   │   ├── Inicial.jsx
│   │   ├── Noticias.jsx
│   │   └── VizualizaNoticia.jsx
│   └── App.jsx
└── package.json


---

## Serviços desenvolvido 🚧

- **Público Geral**:
  - Acessar a página inicial com informações principais.
  - Navegar para a página de notícias e visualizar notícias detalhadas.
  - Acessar a página com informações sobre LGPD e DPO.

- **Administradores**:
  - Adicionar novas notícias.
  - Editar ou atualizar notícias existentes.
  - Remover notícias desnecessárias.

---

## Bibliotecas Usadas e Funcionalidades 📚

1. **Vite**: 
   - Fornece uma maneira rápida e eficiente de criar projetos React.
   - Oferece um servidor de desenvolvimento rápido com suporte a hot module replacement (HMR).

   **Instalação**:
   ```bash
   npm create vite@latest
   ```

2. **React Router DOM**:
   - Gerencia as rotas no aplicativo React.
   - Permite criar links dinâmicos e URLs amigáveis.
   - Garante navegação sem recarregar a página.

   **Instalação**:
   ```bash
   npm install react-router-dom
   ```

3. **Material UI (MUI)**:
   - Biblioteca de componentes React prontos para uso.
   - Facilita a criação de interfaces modernas e responsivas.
   - Inclui temas e estilizações avançadas.

   **Instalação**:
   ```bash
   npm install @mui/material @emotion/react @emotion/styled
   ```

4. **Axios**:
   - Biblioteca para fazer requisições HTTP.
   - Facilita a comunicação com APIs.
   - Suporta interceptores para gerenciar tokens de autenticação e erros.

   **Instalação**:
   ```bash
   npm install axios
   ```

5. **json-server**:
   - Simula um backend para desenvolvimento rápido.
   - Permite criar endpoints RESTful a partir de um arquivo JSON.

   **Instalação**:
   ```bash
   npm install json-server 
   ```

---

## Requisitos 📌
- Node.js instalado
- Gerenciador de pacotes `npm` ou `yarn`

---

## Como Iniciar o Projeto 👨‍💻

1. Clone o repositório do projeto:
   ```bash
   git clone <URL_DO_REPOSITORIO>
   cd UNIESP
   ```

2. Inicie o frontend:
   ```bash
   npm run dev
   ```

3. Inicie o backend fake com o `json-server`:
   ```bash
   npm run server
   ```

---

## Scripts Disponíveis ⭐

- `npm run dev`: Inicia o servidor de desenvolvimento para o frontend.
- `npm run server`: Inicia o backend fake utilizando `json-server`.

---

## Desenvolvimento 🚀 

Após iniciar o projeto, acesse as páginas usando o navegador:

- Página inicial: [http://localhost:5173](http://localhost:5173)
- Backend fake: [http://localhost:3000](http://localhost:3000)

---
