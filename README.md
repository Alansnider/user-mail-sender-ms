\# 📧 User Mail Sender MS



Sistema baseado em arquitetura de microsserviços para gerenciamento de usuários e envio de e-mails.



\---



\## 🚀 Tecnologias

\- Java

\- Spring Boot

\- Spring Data JPA

\- RabbitMQ

\- Flyway

\- PostgreSQL



\---



\## 📦 Estrutura



\### 👤 User Service

\- Cadastro de usuários

\- Persistência no banco

\- Envio de eventos



\### 📧 Email Service

\- Recebe eventos

\- Envia e-mails

\- Registra status



\---



\## 🔄 Comunicação

Mensageria com RabbitMQ (assíncrona)



\---



\## ▶️ Como rodar



```bash

git clone https://github.com/Alansnider/user-mail-sender-ms.git

cd user-mail-sender-ms

mvn spring-boot:run

