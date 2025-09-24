
<div align="center">

# 🎓 Sistema de Gestão Escolar

**Um sistema de gestão escolar completo e moderno construído com React + TypeScript e .NET 8.**

*Autenticação JWT • Operações CRUD Completas • Relatórios em PDF • Integração com API Externa*

</div>

---

### 🌟 Funcionalidades

| 🎨 Frontend (React + TypeScript) | 🚀 Backend (.NET 8 WebAPI) |
| :--- | :--- |
| 🔐 **Autenticação JWT** com login/logout seguro | 🛡️ **Autenticação JWT** - Tokens seguros com atualização |
| 📊 **Dashboard Interativo** com estatísticas em tempo real | 🗄️ **Entity Framework Core** - ORM para SQL Server |
| 👥 **Gestão de Alunos** - Operações CRUD completas | 👤 **Identity Framework** - Sistema de gestão de utilizadores |
| 👨‍🏫 **Gestão de Professores** - Perfis completos dos professores | 🏗️ **Padrão Repositório** - Arquitetura limpa |
| 📚 **Gestão de Cursos** - Controlo do programa académico | 🔄 **AutoMapper** - Mapeamento DTO/Entidade |
| 📝 **Gestão de Matrículas** - Acompanhamento de inscrições | 📋 **Geração de PDF** - Integração com iText7 |
| 📄 **Relatórios em PDF** - Geração automatizada de relatórios | 🌐 **HTTP Client** - Consumo de API externa |
| 🌍 **API Externa** - Integração com CEP do Brasil (ViaCEP) | 📚 **Swagger/OpenAPI** - Documentação auto-gerada |
| 📱 **Design Responsivo** - UI moderna com Tailwind CSS | 📝 **Logging Estruturado** - Sistema de logs completo |
| ⚡ **Estado Global** - Context API para autenticação | 🔒 **Configuração CORS** - Integração com o frontend |
| ✅ **Validação de Formulários** - Validação completa de entradas | ✅ **Validação de Dados** - Validação baseada em anotações |
| | 🌱 **Database Seeding** - Configuração de dados iniciais |

---

### 🚀 Início Rápido

**Login:** `admin@escola.com` / `admin123`

```bash
# Clone o repositório
git clone https://github.com/Mariajtik/sistema-gestao-escolar.git

# Navegue até o diretório
cd sistema-gestao-escolar

# Inicie os serviços com Docker
docker-compose up -d
```

---

### 🛠️ Instalação

#### Pré-requisitos
*   Node.js 18+
*   .NET 8 SDK
*   Docker & Docker Compose
*   SQL Server (LocalDB ou instância completa)

#### 🐳 Instalação com Docker (Recomendado)
```bash
# Clone o repositório
git clone https://github.com/Mariajtik/sistema-gestao-escolar.git
cd sistema-gestao-escolar

# Copie a configuração do ambiente
cp .env.example .env

# Inicie todos os serviços
docker-compose up -d

# Visualize os logs (opcional)
docker-compose logs -f
```

#### 🔧 Instalação Manual
<details>
<summary><strong>Clique para expandir os passos da instalação manual</strong></summary>
<br>

**Configuração do Backend**
```bash
cd backend/SchoolManagementAPI
dotnet restore
dotnet ef migrations add InitialCreate
dotnet ef database update
dotnet run
```
*Backend disponível em: `https://localhost:7001`*

**Configuração do Frontend**
```bash
cd frontend
npm install
npm start
```
*Frontend disponível em: `http://localhost:3000`*
</details>

---

### 🤝 Contribuições

<mark> Acolhemos contribuições! Veja como pode ajudar: </mark>

1.  Faça um **Fork** do repositório.
2.  Crie a sua *feature branch* (`git checkout -b feature/AmazingFeature`).
3.  Faça o **commit** das suas alterações (`git commit -m 'Add some AmazingFeature'`).
4.  Faça o **push** para a *branch* (`git push origin feature/AmazingFeature`).
5.  Abra um **Pull Request**.

Por favor, leia o nosso **Guia de Contribuição** para mais detalhes.

---

### 📄 Licença
Este projeto está licenciado sob a Licença MIT - veja o ficheiro `LICENSE` para mais detalhes.

---

### 👩‍💻 Autora
<div align="center">

**Maria Katchakile Carlos Baptista**

*Desenvolvedora Full-Stack apaixonada por criar soluções educacionais eficientes.*

</div>

---

### 💬 Suporte
<div align="center">

Precisa de ajuda? Estamos aqui para si!

📧 **Email:** mariakcbaptista06@gmail.com
<br>
🐛 **Relatórios de Bugs:** [Criar uma Issue](https://github.com/Mariajtik/sistema-gestao-escolar/issues)
<br>
💡 **Sugestões de Funcionalidades:** [Iniciar uma Discussão](https://github.com/Mariajtik/sistema-gestao-escolar/discussions)

</div>

---

### ⭐ Mostre o Seu Apoio
<div align="center">

Se este projeto o ajudou, por favor, considere dar-lhe uma ⭐ estrela no GitHub!

<br>

🌟 **Dê uma estrela a este repositório** • **Faça um Fork para contribuir** • **Partilhe com outros**

<br>

*Construído com ❤️ usando React, .NET e tecnologias web modernas.*

<br>

© 2025 Maria Baptista. Todos os direitos reservados.

</div>

