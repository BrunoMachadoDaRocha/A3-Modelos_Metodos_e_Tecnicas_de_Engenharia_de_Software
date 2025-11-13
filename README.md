https://www.figma.com/design/T71c4DqCtNheVCZMThpBBD/A3---Modelos--M%C3%A9todos-de-engenharia-de-Software?node-id=0-1&t=JCztWQy0hOX3Vkqv-1

Ótimo! 😄 Vamos passo a passo — usar o GitHub é basicamente aprender a:
1️⃣ Criar um repositório para guardar seu código,
2️⃣ Usar o Git (localmente) para versionar arquivos,
3️⃣ Enviar (push) suas mudanças para o GitHub.

Aqui vai um guia simples 👇

🧩 1. Criar uma conta e instalar o Git

Acesse https://github.com
 e crie uma conta.

Baixe e instale o Git:
🔗 https://git-scm.com/downloads

💻 2. Configurar o Git no seu computador

Abra o terminal (ou Git Bash no Windows) e digite:

git config --global user.name "Seu Nome"
git config --global user.email "seuemail@exemplo.com"


Essas informações aparecem nos commits.

📁 3. Criar um repositório local

No terminal, vá até a pasta do seu projeto e inicialize o Git:

cd caminho/para/sua/pasta
git init


Depois, adicione e confirme os arquivos:

git add .
git commit -m "Primeiro commit"

☁️ 4. Criar um repositório no GitHub

No GitHub, clique em “New repository”.

Escolha um nome e clique em “Create repository”.

Você verá instruções parecidas com estas:

git remote add origin https://github.com/seuusuario/seurepositorio.git
git branch -M main
git push -u origin main


Copie e cole no terminal — isso envia seu projeto para o GitHub.

🔄 5. Atualizar o repositório

Quando fizer mudanças no código:

git add .
git commit -m "Descreva o que mudou"
git push


Para baixar atualizações (caso trabalhe em equipe):

git pull

🧠 6. Conceitos principais

Commit = um "salvamento" de versão do seu código.

Branch = uma “linha paralela” para desenvolver novas features.

Merge = juntar uma branch com outra.

Push/Pull = enviar ou receber alterações do GitHub.

Se quiser, posso te mostrar um exemplo prático: criar um repositório, editar um arquivo e fazer o primeiro commit passo a passo (com os comandos exatos).
Quer que eu monte esse exemplo?

# 🛒 Zona Mista ⚽

Bem-vindo ao **Zona Mista**, um sistema completo de vendas online desenvolvido para oferecer uma experiência moderna e intuitiva de compra de camisetas personalizadas.

Este projeto foi construído com foco em **boas práticas**, **organização**, **segurança** e **performance**, integrando um backend robusto com um frontend dinâmico e responsivo.

---

## 🚀 Tecnologias Utilizadas

### **Frontend**
- HTML5
- CSS3
- JavaScript



### **Backend**
- Node.js / Express  


---

## 📦 Funcionalidades

### 🧍‍♂️ **Área do Cliente**
- Cadastro e login de usuários  
- Listagem de camisetas com filtros por categoria, tamanho e preço  
- Busca de produtos  
- Visualização detalhada de camisetas  
- Carrinho de compras dinâmico  
- Finalização de pedidos com pagamento online (Stripe)  
- Histórico de compras  

### 🛠️ **Área Administrativa**
- Login de administrador  
- Cadastro, edição e exclusão de produtos  
- Upload de imagens para camisetas  
- Gerenciamento de pedidos e usuários  
- Dashboard com estatísticas de vendas  

