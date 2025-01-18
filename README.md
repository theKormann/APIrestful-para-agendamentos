# APIrestful-para-agendamentos
API - Agendamentos Clínica Veterinária
⚠️ Status: Em desenvolvimento

Esta API foi desenvolvida para gerenciar o backend de uma clínica veterinária, oferecendo funcionalidades avançadas de agendamento e pagamento de consultas. Ela é integrada a um banco de dados MySQL e a um sistema de pagamento com Stripe.

**Funcionalidades**

*Armazenamento de Dados no MySQL*
Todos os dados de consultas, usuários e horários são salvos no banco de dados MySQL, garantindo persistência e confiabilidade.

*Filtragem por Tipo de Consulta*
Permite filtrar as consultas entre generalista (animais domésticos) ou silvestre (animais exóticos).

*Criação de IDs Únicos para Usuários*
Cada usuário recebe uma identificação única, facilitando o gerenciamento de informações e garantindo segurança.

*Cálculo e Pagamento de Consultas*
Calcula automaticamente o valor da consulta e gera o pagamento diretamente pelo Stripe.
O link de pagamento é disponibilizado para o cliente.

*Disponibilidade de Horários*
Trabalha em conjunto com JavaScript para verificar e exibir os horários disponíveis, permitindo um agendamento eficiente.


**Tecnologias Utilizadas**
Java Spring Boot: Backend principal da API.
MySQL: Banco de dados relacional para armazenamento de informações.
Stripe API: Integração para processamento de pagamentos.
JavaScript: Gerenciamento e exibição da disponibilidade de horários no front-end.
Configuração do Ambiente
Pré-requisitos:
Java 17+
MySQL
Maven
Conta no Stripe com chaves de API

