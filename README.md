## 💻 Sistema de Gerenciamento de Ordens de Serviço - Oficina Mecânica

Este projeto foi desenvolvido como parte de um **desafio de modelagem de dados** proposto pela **Digital Innovation One (DIO)**. O objetivo é representar de forma conceitual um sistema de controle e gerenciamento de ordens de serviço em uma oficina mecânica.

### 📎 Narrativa

- Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica
- Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões  periódicas
- Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.
- A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra
- O valor de cada peça também irá compor a OSO cliente autoriza a execução dos serviços
- A mesma equipe avalia e executa os serviços
- Os mecânicos possuem código, nome, endereço e especialidade
- Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.

### 🔍 Objetivo

Modelar as entidades, atributos e relacionamentos necessários para gerenciar:

- Cadastro de clientes, veículos, mecânicos e equipes
- Emissão e controle de ordens de serviço (OS)
- Registro de serviços realizados e peças utilizadas
- Cálculo do valor total da OS com base em mão de obra e peças

### 📌 Escopo

A modelagem abrange os principais processos da oficina, desde a entrada do veículo até a conclusão dos serviços, passando por autorizações, execução por equipe, e controle de prazos e valores.

> Projeto desenvolvido como parte da formação em Banco de Dados pela [Digital Innovation One (DIO)](https://www.dio.me/).
