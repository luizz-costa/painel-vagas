# 📋 Painel Administrativo de Vagas
![PHP](https://img.shields.io/badge/PHP-8.2-blue)

Este é um sistema de gerenciamento de vagas de emprego desenvolvido em PHP utilizando Orientação a Objetos (POO) e conexão PDO com MySQL.

## 🚀 Tecnologias Utilizadas
* PHP 8.2
* MySQL
* Composer (Gerenciamento de dependências e Autoload)
* Bootstrap (Interface)

## ⚙️ Funcionalidades

✅ Adicionar novas vagas  
✅ Marcar vagas como ativa/inativa  
✅ Excluir vagas  
✅ Editar vagas  

## 🛠️ Como Instalar e Rodar o Projeto

### 1. Clonar o Repositório
```bash
git clone https://github.com/luizz-costa/painel-vagas.git
cd painel-vagas
```
### 2. Instalar Dependências
Você precisará do Composer instalado. No terminal, dentro da pasta do projeto, execute:
```bash
composer install
```
### 3. Configurar o Banco de Dados
1. No seu servidor MySQL (XAMPP/WAMP), crie um banco de dados chamado `vagas`.
2. Importe o arquivo SQL localizado em /Db/luiz_vagas.sql
3. Renomeie o arquivo app/Db/Database.php.example para Database.php
4. Abra o Database.php e preencha as credenciais do seu banco:

    - HOST: Seu host (geralmente localhost)

    - NAME: Nome do banco

    - USER: Seu usuário

    - PASSWORD: Sua senha
### 4. Iniciar o Servidor

1. Mova a pasta do projeto para o diretório de arquivos públicos do seu servidor:
    - XAMPP: `C:/xampp/htdocs/`
    - wamp: `C:/wamp64/www/`
2. Certifique-se de que o módulo Apache e MySQL estejam ativos no painel de controle do seu servidor.
3. Acesse no seu navegador:
```bash
http://localhost/painel-vagas/
```
>Nota: Se o seu Apache estiver configurado em uma porta diferente, como a 8080, utilize:
```bash 
http://localhost:8080/painel-vagas/
```