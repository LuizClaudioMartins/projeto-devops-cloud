# 🚀 CloudOps Portal — Pipeline CI/CD com Deploy em Nuvem

Projeto prático desenvolvido para a disciplina **Cloud Computing e DevOps** (II Unidade) da Faculdade Esuda, sob orientação do **Prof. João Freire Abramowicz**.

---

## 👥 Equipe do Projeto
* **Luiz Claudio Martins**
* **Pethrus Souza**
* **Gabriel Normandio**

---

## 📌 Descrição da Aplicação
O **CloudOps Portal** é uma aplicação web funcional projetada para centralizar o status operacional de serviços e monitorar a integridade da infraestrutura por meio de rotinas de *Health Check*.

### Principais Recursos:
- **Painel Interativo:** Validação de integridade do serviço com simulação de resposta HTTP 200 via JavaScript.
- **Identificação e Rastreabilidade:** Informações de autoria e status da publicação em nuvem.
- **Design Responsivo:** Interface limpa e estilizada em padrão moderno.

---

## 🛠️ Tecnologias e Ferramentas
- **Linguagens:** HTML5, CSS3 e JavaScript.
- **Controle de Versão:** Git e GitHub.
- **Integração e Entrega Contínuas (CI/CD):** GitHub Actions.
- **Provedor de Nuvem:** Plataforma de Nuvem Pública com suporte a deploy contínuo.

---

## ⚙️ Arquitetura do Pipeline CI/CD
1. **Push:** Desenvolvedor envia uma alteração na branch `main`.
2. **Build &amp; Test:** O pipeline do GitHub Actions valida a integridade do código.
3. **Continuous Deployment (CD):** A versão aprovada é entregue e publicada automaticamente na nuvem pública.
4. **Disponibilização Pública:** A aplicação fica acessível via URL pública global.
