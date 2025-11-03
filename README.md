# Modelo lógico de banco de dados voltado a um sistema de controle e gerenciamento de execuções de ordem de serviços de uma oficina mecânica.

Segundoo desafio do projeto da plataforma [DIO](https://www.dio.me/) curso "SQL Database Specialist".

## 🚗 Oficina Mecânica 

- **Entidades:** Clientes, Veículo, Mecânico, Ordem de Serviço, Valor da Ordem de Serviço, Peça. 

## 📖 Narrativa

**1. Clientes**

- Clientes levam veículos à oficina mêcanica para serem consertados ou para passarem por revisões periódicas.

**2. Veículo**

- Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega. 

**3. Mecânico**

- Os mecânicos possuem código, nome, endereço e especialidade.

**4. Ordem de Serviço**

- Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos

**5. Valor da Ordem de Serviço**

- A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra.

**6. Peças**

- O valor de cada peça também irá compor a OS

## ✍️ Descrição do desafio 
 
Elaborar um esquema de modelo lógico de banco de dados funcional através dos requisitos sollicitados para execução do sistema de gerenciamento de uma oficina mecânica

## 💡Solução

<img align="center" src="https://github.com/rodrigo-sza-almeida/" width=""/> 

## 🧑‍💻 Tecnologia utilizada 

![MySQL Workbench](https://img.shields.io/badge/MySQL%20Workbench-ffffff?style=for-the-badge&logo=mysql&logoColor=black)
