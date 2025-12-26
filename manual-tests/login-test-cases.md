## CT-01 - Validar login com dados válidos

**Pré-condição:**  
Usuário na página de login

**Passos:**  
1. Preencher os campos de email e senha com dados válidos  
2. Clicar no botão Login  

**Resultado esperado:**  
O sistema deve permitir o acesso do usuário ao sistema

---

## CT-02 - Validar login com campos vazios

**Pré-condição:**  
Usuário na página de login

**Passos:**  
1. Deixar os campos de email e senha vazios  
2. Clicar no botão Login  

**Resultado esperado:**  
O sistema não deve permitir o acesso do usuário e deve exibir uma mensagem de erro informando que os campos são obrigatórios

---

## CT-03 - Validar login com caractere inválido

**Pré-condição:**  
Usuário na página de login

**Passos:**  
1. Preencher o campo email com caracteres inválidos  
2. Clicar no botão Login  

**Resultado esperado:**  
O sistema não deve permitir o acesso do usuário e deve exibir uma mensagem de erro informando dados inválidos

