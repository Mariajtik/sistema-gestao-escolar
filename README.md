<h2> 🎓 School Management System </h2>


<div align="center"> 

A complete, modern school management system built with React + TypeScript and .NET 8

JWT Authentication • Full CRUD Operations • PDF Reports • External API Integration



⚡ Quick Start git clone https://github.com/Mariajtik/sistema-gestao-escolar.git cd sistema-gestao-escolar docker-compose up -d 

Login: admin@escola.com / admin123

</div> 🌟 Features <table> <tr> <td width="50%"> 
  🎨 Frontend (React + TypeScript)
  <br></br>
  🔐 JWT Authentication with secure login/logout 
  <br></br>
  📊 Interactive Dashboard with real-time statistics 
  <br></br>
  👥 Student Management - Complete CRUD operations 
    <br></br>
  👨‍🏫 Teacher Management - Full professor profiles 
  📚 Course Management - Academic program control 
  📝 Enrollment Management - Registration tracking 
  📄 PDF Reports - Automated report generation 
  🌍 External API - Brazilian ZIP code integration (ViaCEP) 
  📱 Responsive Design - Modern UI with Tailwind CSS 
  ⚡ Global State - Context API for authentication 
  ✅ Form Validation - Comprehensive input validation </td> <td width="50%"> 
    🚀 Backend (.NET 8 WebAPI) 
    🛡️ JWT Authentication - Secure tokens with refresh 
    🗄️ Entity Framework Core - SQL Server ORM 
    👤 Identity Framework - User management system 
    🏗️ Repository Pattern - Clean architecture 
    🔄 AutoMapper - DTO/Entity mapping 
    📋 PDF Generation - iText7 integration 
    🌐 HTTP Client - External API consumption 
    📚 Swagger/OpenAPI - Auto-generated documentation 
    📝 Structured Logging - Comprehensive log system 
    🔒 CORS Configuration - Frontend integration 
    ✅ Data Validation - Annotation-based validation 
    🌱 Database Seeding - Initial data setup </td> </tr> </table>


</div> 🚀 Quick Start Prerequisites Node.js 18+ .NET 8 SDK Docker & Docker Compose SQL Server (LocalDB or full instance) 
🐳 Docker Installation (Recommended) # Clone the repository git clone https://github.com/Mariajtik/sistema-gestao-escolar.git cd sistema-gestao-escolar # Copy environment configuration cp .env.example .env # Start all services docker-compose up -d # View logs (optional) docker-compose logs -f 
🔧 Manual Installation <details> <summary><strong>Click to expand manual installation steps</strong></summary> Backend Setup cd backend/SchoolManagementAPI dotnet restore dotnet ef migrations add InitialCreate dotnet ef database update dotnet run 

Backend available at: https://localhost:7001

Frontend Setup cd frontend npm install npm start 

Frontend available at: http://localhost:3000



<mark> We welcome contributions! Here's how you can help: </mark>

Fork the repository Create your feature branch (git checkout -b feature/AmazingFeature) Commit your changes (git commit -m 'Add some AmazingFeature') Push to the branch (git push origin feature/AmazingFeature) Open a Pull Request 

Please read our Contributing Guide for more details.

📄 License 

This project is licensed under the MIT License - see the LICENSE file for details.

👩‍💻 Author

<div align="center"> Maria Katchakile Carlos Baptista 

Full-Stack Developer passionate about creating efficient educational solutions

</div> 💬 Support <div align="center"> 

Need help? We're here for you!

📧 Email: mariakcbaptista06@gmail.com 🐛 Bug Reports: Create an Issue 💡 Feature Requests: Start a Discussion

</div> Show Your Support 

If this project helped you, please consider giving it a ⭐ star on GitHub!

<div align="center"> 🌟 Star this repository • Fork for contributions • Share with others 

Built with ❤️ using React, .NET, and modern web technologies



© 2025 Maria Baptista. All rights reserved.
