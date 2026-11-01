# 🍪 Cookiera - Aplicação Web de Gestão e Receitas

## 📋 Sobre o Projeto
Aplicação web interativa desenvolvida para consulta, gestão de receitas de cookies e carrinho de compras, utilizando integração com a API do Open Food Facts e persistência de dados via Supabase. O projeto foi construído focando em boas práticas de software, testes automatizados integrados com CI/CD no GitHub Actions e conteinerização com Docker[cite: 7, 16].

---

## 👥 Integrantes do Grupo

| Nome Completo | Matrícula | Usuário GitHub | Função Principal | Link da Principal PR |
| :--- | :--- | :--- | :--- | :--- |
| Kauã Henrique Tolentino Nunes | 22612244 | @kauahenrique-create | Frontend, Docker & CI/CD | [PR #1](https://github.com/Rach3lzinha/bootcamp2-projeto-final/pull/1) |
| Rachel Tolentino de Sena | 22612246 | @Rach3lzinha | Frontend & Persistência | [PR #1](https://github.com/Rach3lzinha/bootcamp2-projeto-final/pull/1) |

---

## 🛠️ Tecnologias Utilizadas

- **Frontend:** HTML5, CSS3, JavaScript (ES6)[cite: 7, 16]
- **Backend / Persistência:** Supabase (PostgreSQL Cloud)[cite: 7, 16]
- **API Externa:** [Open Food Facts API](https://wiki.openfoodfacts.org/API)[cite: 7, 16]
- **Testes Unitários:** Jest[cite: 7, 16]
- **CI/CD:** GitHub Actions[cite: 7, 16]
- **Conteinerização:** Docker & Docker Hub (Nginx Alpine)[cite: 7, 16]

---

## ⚙️ Regras do Processo e Governança

- **Proteção da Main:** Commits diretos na branch `main` foram desativados via Branch Protection Rules no GitHub[cite: 7, 16].
- **Workflow de PR:** Todo o código novo foi integrado exclusivamente através de Pull Requests com revisão obrigatória[cite: 7, 16].
- **Validação Automatizada:** Pipeline de CI executa a suíte de testes unitários (`app.test.js`) via GitHub Actions a cada PR submetido antes de permitir o merge[cite: 7, 16].

---

## 🚀 Como Executar o Projeto

### 1. Execução Local
```bash
# 1. Clonar o repositório
git clone [https://github.com/Rach3lzinha/bootcamp2-projeto-final.git](https://github.com/Rach3lzinha/bootcamp2-projeto-final.git)

# 2. Entrar na pasta do projeto
cd bootcamp2-projeto-final

# 3. Instalar dependências
npm install

# 4. Abrir o ficheiro index.html no navegador (ou via Live Server no VS Code)
