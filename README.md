# Web Development – CineBox

## 🧠 1. Descrição

O **CineBox** é uma aplicação web desenvolvida com **React + Vite** que exibe um catálogo de filmes consumindo uma API mockada em JSON.
O usuário pode visualizar **título, capa, ano, gênero, descrição, duração e avaliações**, tudo em uma interface leve e responsiva.

O projeto foi criado com foco em:

* Consumo e manipulação de dados de APIs
* Organização de rotas e componentes
* Estudo de Typescript + Tailwind
* Boas práticas de estruturação de projetos em React

---

## 🚀 2. Como executar o projeto

1. Clone o repositório:

   ```bash
   git clone https://github.com/1IMperaDOR0/cinebox.github.io
   ```

2. Entre na pasta principal do projeto:

   ```bash
   cd cinebox.github.io/react
   ```

3. Instale as dependências:

   ```bash
   npm install
   ```

4. Execute em ambiente local:

   ```bash
   npm run dev
   ```

---

## 🧬 3. Tecnologias utilizadas

### **Frontend**

* React
* Typescript
* Vite
* TailwindCSS
* React Router DOM

### **Outras ferramentas**

* Git & GitHub
* Deploy via GitHub Pages
* Manipulação de JSON estático como API mockada

---

## 🧭 4. Estrutura geral

### **📁 src/**

| Pasta / Arquivo | Função                                         |
| --------------- | ---------------------------------------------- |
| **assets/**     | Armazena imagens utilizadas nos componentes    |
| **components/** | Menus, footer e outros elementos reutilizáveis |
| **pages/**      | Todas as páginas principais da aplicação       |
| **services/**   | Arquivo JSON simulando API de filmes           |
| `App.tsx`       | Configuração base e rotas                      |
| `main.tsx`      | Renderização raiz da aplicação                 |

---

## 🎞️ 5. Páginas principais

### 🏠 **Home**

* Destaque para filmes populares
* Acesso rápido ao catálogo

### 🎥 **Lista**

* Mostra todos os filmes da API
* Cards com imagem, nome e ano

### 🔍 **Pesquisar**

* Busca por nome (filter direto sobre a API local)

### 🆕 **Lançamentos**

* Agrupa filmes recentes

### 👤 **Perfil**

* Dados fictícios do usuário

### ✉️ **Contato**

* Página simples com formulário estilizado

---

## 📦 6. API Mockada (JSON)

O arquivo `movies_api.json` simula uma API real contendo:

* **id**
* **nome**
* **imagem**
* **ano**
* **gênero**
* **descrição**
* **nota**
* **avaliações** com nome e comentário

Exemplo da estrutura:

```json
{
  "id": 0,
  "nome": "Interestelar",
  "imagem": "/images/interestelar.jpg",
  "ano": 2014,
  "genero": "Ficção-científica",
  "duracao": "2h49min",
  "descricao": "Interestelar é um filme de ficção científica...",
  "nota": "10/10",
  "avaliacoes": {
    "pessoa_1": {
      "nome": "Ana Costa",
      "comentario": "Simplesmente fascinante..."
    }
  }
}
```

---

## 🧱 7. Estrutura do Projeto

```bash
react/
├── public/
│   └── images/                # Imagens dos filmes
├── src/
│   ├── assets/                # Logos e ícones
│   ├── components/            # Menu, footer, menus mobile
│   ├── pages/                 # Home, Lista, Perfil, Contato etc.
│   ├── services/
│   │   └── movies_api.json    # API mockada
│   ├── App.tsx
│   ├── main.tsx
│   └── index.css
├── package.json
├── tsconfig.json
└── vite.config.ts
```

---

## 👥 Integrantes A-Z

* **Henrique de Oliveira Gomes – RM566424**
* **Lucas Henrique Viana Estevam Sena – RM566246**

---

## 🔗 Links

- Solution URL: [https://github.com/1IMperaDOR0/cinebox.github.io](https://github.com/1IMperaDOR0/cinebox.github.io)
- Live Site URL: [https://1imperador0.github.io/cinebox.github.io/](https://1imperador0.github.io/cinebox.github.io/)

---

## 📜 Licença

Projeto acadêmico. Uso livre para fins educacionais.

---