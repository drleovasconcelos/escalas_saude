# Sistema de Escalas de Saúde

## 📋 Descrição
O **Sistema de Escalas de Saúde** é uma plataforma digital projetada para profissionais de saúde que necessitam de acesso rápido e preciso a diversas escalas hospitalares amplamente utilizadas, como:
- Escala de Coma de Glasgow
- Escala de Ramsay
- Escala de Richmond (RASS)
- Índice de Barthel
- Escala de Mobilidade (EMU)
- Entre outras

Com essa ferramenta, as escalas são apresentadas de forma clara e interativa, permitindo a aplicação prática no ambiente clínico.

## 🚀 Funcionalidades
- Cadastro e gerenciamento de pacientes.
- Acesso a escalas específicas por área de atuação (UTI, neurologia, fisioterapia, etc.).
- Armazenamento seguro de dados usando **Spring Security**.
- Relatórios automáticos baseados nos resultados das escalas.
- Integração com APIs externas para cálculos avançados, como o APACHE II.
- Interface amigável e responsiva com **Thymeleaf** ou frameworks modernos como React.

## 🛠️ Tecnologias Utilizadas
- **Back-end**: Spring Boot, Spring Data JPA, Spring Security
- **Banco de Dados**: MySQL
- **Front-end**: Thymeleaf ou React.js
- **Segurança**: Autenticação JWT
- **Documentação de API**: Swagger
- **Ferramentas de Desenvolvimento**: Maven, IntelliJ IDEA

## 🏗️ Estrutura do Projeto
```bash
src/
├── main/
│   ├── java/com/escalasdesaude/
│   │   ├── controller/
│   │   ├── model/
│   │   ├── repository/
│   │   └── service/
│   └── resources/
│       ├── static/
│       ├── templates/
│       └── application.properties
├── test/
⚙️ Configuração Inicial

```
# Pré-requisitos:
JDK 17+
Maven 3.8+
MySQL Server

# Passos:
Clone o repositório:
git clone https://github.com/seu-usuario/sistema-escalas-saude.git

# Configure o arquivo application.properties com as credenciais do banco de dados:
properties
spring.datasource.url=jdbc:mysql://localhost:3306/sistema_escalas
spring.datasource.username=seu_usuario
spring.datasource.password=sua_senha

# Execute o projeto:
mvn spring-boot:run
📚 Escalas Implementadas
Escala de Coma de Glasgow
Escala de Sedação de Ramsay
Escala de Agitação e Sedação de Richmond (RASS)
Escala de Rankin
Índice de Barthel Modificado
Escala de Mobilidade em UTI (EMU)
Escore APACHE II
E muito mais...

🛡️ Segurança
Autenticação com JWT.
Senhas armazenadas com hash Bcrypt.
Proteção contra CSRF.

📄 Licença
Este projeto está licenciado sob a MIT License.

✉️ Contato
Para dúvidas ou sugestões, entre em contato:

Nome: Dr. Leonardo Freire
E-mail: lfreire1985@gmail.com
LinkedIn: https://www.linkedin.com/in/leonardofv
