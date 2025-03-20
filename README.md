# 📚 Onix Capacitação Profissional

Este projeto é uma plataforma de ensino online que permite que professores cadastrem cursos, adicionem materiais e vídeos, e interajam com alunos. Além disso, os alunos podem acessar cursos pagos e gratuitos, realizar testes e obter certificados ao concluir os cursos.

## 🚀 Funcionalidades

- 📌 Cadastro e autenticação de usuários (Alunos, Professores, Administradores)
- 🎥 Upload e gestão de aulas em vídeo
- 📚 Materiais de apoio (PDFs, slides, links externos)
- 💳 Pagamento de cursos via Stripe ou Mercado Pago
- 📝 Testes e quizzes para alunos
- 🎓 Certificação automática após conclusão do curso
- 📊 Dashboard para professores gerenciarem seus cursos
- 📷 Integração com Instagram na página inicial

## 🛠️ Tecnologias Utilizadas

### 🔹 Frontend

- **Next.js** (React Framework)
- **Tailwind CSS** (Estilização)
- **Shadcn/ui** (Componentes UI)
- **Axios** (Requisições HTTP)

### 🔹 Backend

- **NestJS** (Framework para Node.js)
- **PostgreSQL** + **MongoDB** (Banco de Dados Híbrido)
- **Prisma ORM** (Para PostgreSQL)
- **Mongoose** (Para MongoDB)
- **JWT** (Autenticação)
- **Stripe ou Mercado Pago** (Pagamentos)

### 🔹 Armazenamento de Vídeos

- **AWS S3** ou **Firebase Storage**

## 📂 Estrutura do Projeto

```
/plataforma-ensino
│── frontend/                # Aplicação Next.js
│   ├── components/          # Componentes reutilizáveis
│   ├── pages/               # Páginas do site
│   ├── styles/              # Estilos globais
│   ├── services/            # Integrações com API
│── backend/                 # API com NestJS
│   ├── src/                 # Código-fonte
│   │   ├── modules/         # Módulos do sistema
│   │   ├── database/        # Configuração do PostgreSQL e MongoDB
│   │   ├── auth/            # Autenticação
│   │   ├── courses/         # Gestão de cursos
│   │   ├── users/           # Gestão de usuários
│   ├── package.json         # Dependências do backend
│── README.md                # Documentação do projeto
```

## ⚡ Como Rodar o Projeto

### 🔹 Clonar o repositório

```bash
git clone https://github.com/seu-usuario/plataforma-ensino.git
cd plataforma-ensino
```

### 🔹 Configurar o Backend

```bash
cd backend
cp .env.example .env # Configure suas variáveis de ambiente
npm install
npm run start:dev
```

### 🔹 Configurar o Frontend

```bash
cd frontend
npm install
npm run dev
```

## 🚀 Contribuindo

1. Faça um Fork do repositório
2. Crie uma branch para sua feature (`git checkout -b minha-feature`)
3. Commit suas alterações (`git commit -m 'Adicionando nova feature'`)
4. Faça um push (`git push origin minha-feature`)
5. Abra um Pull Request

## 📜 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usá-lo e contribuir!

---

Dúvidas ou sugestões? Entre em contato! ✉️

