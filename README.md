# 🧪 Central de Testes Manuais

Este repositório organiza todos os cenários de teste funcionais do sistema.

## 👥 Funcionalidade: Tela de Login

### CT001: Login com sucesso
* **Pré-condição:** Usuário já deve estar cadastrado no sistema.
* **Passo a Passo:**
  1. Acessar a página de login.
  2. Preencher o e-mail correto e a senha correta.
  3. Clicar no botão "Entrar".
* **Resultado Esperado:** O sistema deve autenticar o usuário e abrir a tela do Dashboard principal.

---

### CT002: Login com senha incorreta
* **Pré-condição:** Usuário já deve estar cadastrado no sistema.
* **Passo a Passo:**
  1. Acessar a página de login.
  2. Preencher o e-mail correto.
  3. Preencher uma senha errada.
  4. Clicar no botão "Entrar".
* **Resultado Esperado:** O sistema deve exibir o alerta "E-mail ou senha inválidos" e manter o usuário na mesma página.
