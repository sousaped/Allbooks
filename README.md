# 📘 Estudos — Git e GitHub | Alura

Repositório criado durante o curso de **Git e GitHub** da Alura. Aqui estão registradas as práticas e conceitos aprendidos ao longo do curso.

---

## ✅ O que aprendi

### 🔧 Fundamentos do Git e GitHub

- Diferença entre **Git** (ferramenta de versionamento) e **GitHub** (plataforma de repositórios)
- Criação de repositório local com `git init` e `git branch -M main`
- Conexão entre repositório local e remoto com `git remote add origin URL`
- Registro de alterações com `git commit -m "mensagem"`
- Envio e recebimento de alterações com `git push origin main` e `git pull origin main`

### 🌿 Branches e Fluxo Colaborativo

- Gerenciamento do fluxo de trabalho com `git status`, `git add`, `git commit`, `git push` e `git pull`
- Criação de nova branch e alternância para ela com `git checkout -b nova-branch`
- Fusão de alterações com `git merge`
- Resolução de conflitos quando um mesmo arquivo é editado por pessoas diferentes
- Uso de **Issues** para documentar e rastrear tarefas do projeto
- Uso de **Pull Requests** para revisão de código antes de integrar à outra branch

### 🔀 Estratégias de Ramificação

- **Gitflow** — utiliza múltiplas branches com propósitos específicos (`develop`, `feature`, `release`, `hotfix`), ideal para projetos com ciclos de lançamento definidos
- **Trunk Based Development** — mantém a branch principal (`main`) sempre estável com integrações frequentes e pequenas, favorecendo a entrega contínua

### ⚙️ Integração Contínua (CI)

- Conceito de **Integração Contínua**: automatização de atualizações de código com execução frequente de testes para detectar problemas de integração
- Configuração de um **workflow com GitHub Actions**
- Teste e visualização do funcionamento do workflow de CI
- **Proteção de branches**: garantia de que todo código integrado à `main` passe por revisão via PR e seja testado pelo workflow de CI

### 🔒 Segurança com Dependabot

- Ativação de alertas de vulnerabilidade nas dependências do projeto
- Automação da resolução de vulnerabilidades com abertura de Pull Requests automáticos
- Configuração de atualização automática de versões

---

## 🛠️ Comandos vistos no curso

| Comando | Descrição |
|---|---|
| `git init` | Inicia um repositório local |
| `git branch -M main` | Renomeia a branch principal para `main` |
| `git remote add origin URL` | Conecta o repositório local ao remoto |
| `git status` | Exibe o estado atual dos arquivos |
| `git add` | Adiciona arquivos para o próximo commit |
| `git commit -m "msg"` | Registra as alterações com uma mensagem |
| `git push origin main` | Envia as alterações para o repositório remoto |
| `git pull origin main` | Traz as alterações do repositório remoto |
| `git checkout -b nova-branch` | Cria e alterna para uma nova branch |
| `git merge` | Funde alterações de uma branch em outra |

---

Curso realizado na [Alura](https://www.alura.com.br).
