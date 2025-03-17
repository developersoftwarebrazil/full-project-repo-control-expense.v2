# 💰 Controle de Gastos - Full Project

Este projeto é um sistema para controle de entradas e saídas financeiras, permitindo que os usuários adicionem despesas, receitas e acompanhem seus pagamentos, incluindo parcelamentos.  

## 🚀 Tecnologias Utilizadas  

### **📌 Backend**  
- **NestJS** (API em Node.js)  
- **Prisma ORM** (Gerenciamento do banco de dados)  
- **PostgreSQL** (Banco de dados)  
- **DDD + SOLID** (Arquitetura e boas práticas)  
- **Swagger** (Documentação da API)  

### **📌 Frontend**  
- **Next.js** (Framework React para frontend)  
- **SCSS** (Estilização)  
- **React Query** (Gerenciamento de estados assíncronos)  

### **📌 Deploy**  
- **Backend:** Vercel  
- **Frontend:** Netlify  

## 📂 Estrutura do Projeto  
```bash
full-project/
│── backend/          # API desenvolvida em NestJS
│── frontend/         # Aplicação frontend em Next.js
│── README.md         # Documentação do projeto
│── .gitignore        # Arquivos ignorados no Git
```

## 🚀 Como Rodar o Projeto 

### **1️⃣ Clonar o repositório**
```bash
git clone https://github.com/seu-usuario/full-project-expense-2025.git
cd full-project-expense-2025
```
### **1️⃣ Configurar o backend**
```bash
cd backend
cp .env.example .env
npm install
npx prisma migrate dev
npm run start:dev
```
Acesse: http://localhost:3000

### **1️⃣ Configurar o frontend**
```bash
cd ../frontend
cp .env.example .env
npm install
npm run dev
```
Acesse: http://localhost:3001

## **✅ Funcionalidades Principais**
- **✔ Cadastro e listagem de despesas e receitas.**
- **✔ Parcelamento automático de despesas.**
- **✔ Controle de entradas e saídas.**
- **✔ Autenticação JWT (em breve).**
- ✔ Deploy no Netlify e Vercel (em breve).
