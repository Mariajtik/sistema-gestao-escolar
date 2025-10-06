

<div align="center">


# 🎓 School Management System


**A complete and modern school management system built with React + TypeScript and .NET 8.**


*JWT Authentication • Complete CRUD Operations • PDF Reports • External API Integration*


</div>


---


### 🌟 Features





---


### 🚀 Quick Start


**Login:** `admin@escola.com` / `admin123`


```bash

# Clone the repository

git clone https://github.com/Mariajtik/sistema-gestao-escolar.git


# Navigate to the directory

cd school-management-system


# Start services with Docker

docker-compose up -d

```


---


### 🛠️ Installation


#### Prerequisites

* Node.js 18+

* .NET 8 SDK

* Docker & Docker compose

* SQL Server (LocalDB or full instance)


#### 🐳 Installation with Docker (Recommended)

```bash

# Clone the repository

git clone https://github.com/Mariajtik/sistema-gestao-escolar.git

cd school-management-system


# Copy the environment configuration

cp .env.example .env


# Start all services

docker-compose up -d


# View logs (optional)

docker-compose logs -f

```


#### 🔧 Manual Installation

<details>

<summary><strong>Click to expand the manual installation steps</strong></summary>

<br>


**Backend Configuration**

```bash

cd backend/SchoolManagementAPI

dotnet restore

dotnet ef migrations add InitialCreate

dotnet ef database update

dotnet run

```

*Backend available at: `https://localhost:7001`*


**Frontend Configuration**

```bash

cd frontend

npm install

npm start

```

*Frontend available at: `http://localhost:3000`*

</details>


---


### 🤝 Contributions


<mark> We welcome contributions! See How you can help:


1. Fork the repository.

2. Create your feature branch (`git checkout -b feature/AmazingFeature`).

3. Commit your changes (`git commit -m ‘Add some AmazingFeature’`).

4. Push to the branch (`git push origin feature/AmazingFeature`).

5. Open a Pull Request.


Please read our Contribution Guide for more details.


---


### 📄 License

This project is licensed under the MIT License - see the `LICENSE` file for more details.


---


### 👩‍💻 Author

<div align="center">


**Maria Katchakile Carlos Baptista**


*Full-Stack Developer passionate about creating efficient educational solutions.*


</div>


---


### 💬 Support

<div align="center">


Need help? We're here for you!


📧 **Email:** mariakcbaptista06@gmail.com

<br>

🐛 **Bug Reports:** [Create an Issue](https://github.com/Mariajtik/sistema-gestao-escolar/issues)

<br>

💡 **Feature Suggestions:** [Start a Discussion](https://github.com/Mariajtik/sistema-gestao-escolar/discussions)


</div>


---


### ⭐ Show Your Support

<div align="center">


If this project has helped you, please consider giving it a ⭐ star on GitHub!


<br>


🌟 **Star this repository** • **Fork to contribute** • **Share with others**


<br>


*Built with ❤️ using React, .NET, and modern web technologies.*


<br>


© 2025 Maria Baptista. All rights reserved.


</div>


