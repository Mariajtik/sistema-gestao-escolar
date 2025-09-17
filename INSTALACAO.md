# 🚀 Guia de Instalação

## Pré-requisitos
- Docker e Docker Compose instalados
- Git instalado

## Passo a Passo

### 1. Clonar o Repositório

```bash
git clone https://github.com/Mariajtik/sistema-gestao-escolar.git
cd sistema-gestao-escolar

2. Configurar o ambiente 

# Copiar arquivo de exemplo
cp .env.example .env

# Editar o arquivo .env com suas configurações
# IMPORTANTE: Mude as senhas e chaves! 

3. Executar o sistema 

# Iniciar todos os serviços
docker-compose up -d

# Ver logs (opcional)
docker-compose logs -f

4. Acessar a Aplicação 

• Frontend: http://localhost:3000
•API: http://localhost:5000/swagger
• Login: admin@escola.com/admin123 

Parar o Sistema 

``` bash

docker-compose

```

Problemas Comuns 
Erro de porta ocupada
``` bash

#Parar serviços na porta 3000 ou 5000
sudo lsof -ti:3000 | xargs kill -9
sudo lsof -ti:5000 | xargs kill -9

```
Banco não conecta

1. Aguarde 30 segundos para o SQL Server inicializar 
2. Verifique os logs: docker-compose logs sqlserver
