# Cliente Backend API

![Status do Projeto](https://img.shields.io/badge/status-em_desenvolvimento-yellow)
![License](https://img.shields.io/badge/license-MIT-green)

Esta é a API de gerenciamento de clientes, responsável por fornecer endpoints para operações de CRUD (Create, Read, Update, Delete) para integração com interface de usuarios no frontend.

## 🚀 Tecnologias Utilizadas

* **Linguagem:** Java
* **Framework:** Spring Boot
* **Banco de Dados:** H2
* **Ferramentas:** Git, VS Code.

## 🛠️ Funcionalidades

- [x] Cadastro de clientes, obtem o endereço pelo ViaCEP - valida CEP, CPF inválido e CPF já cadastrado.
- [x] Consulta cliente por CPF.
- [x] Atualização de dados cadastrais - valida CEP.
- [x] Remoção de clientes do sistema.
 * Carrega arquivo csv de clientes para simulação armazenado junto com o fonte: path - src/main/resources.
 * Permite usar um simulador (stub) de ViaCEP

## 📦 Como executar o projeto

Para rodar este projeto localmente, siga os passos abaixo:

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/almeida2/cliente-back2.git

 2. **Abra o terminal na pasta raiz do projeto:** <p>
Pasta raiz - C:\temp\projeto-java\cliente-backv2 <p>
IDE: no menu principal da IDE run java <p> 
Maven: para compilar e gerar o build exeute no terminal - mvn clean install <p>
JAR: no cmd execute - java -jar cliente-backv2-0.0.1-SNAPSHOT.jar. 

