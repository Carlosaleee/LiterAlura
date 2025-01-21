# LiterAlura

**Descrição:**
O projeto **LiterAlura** é uma aplicação de busca de livros desenvolvida como parte dos estudos em Spring Boot. Ele oferece uma interface para consulta e gerenciamento de informações sobre livros, integrando banco de dados relacional e recursos modernos de desenvolvimento em Java.

---

## 🛠 Tecnologias Utilizadas

- **Linguagem de Programação:** Java 21
- **Framework Principal:** Spring Boot 3.3.0
- **Banco de Dados:** PostgreSQL
- **ORM:** Hibernate (JPA)
- **Gerenciamento de Dependências:** Maven

---

## 📂 Estrutura do Projeto

O projeto segue uma arquitetura limpa com as seguintes camadas:

1. **Controller:** Gerencia as requisições e respostas HTTP.
2. **Service:** Implementa as regras de negócio.
3. **Repository:** Responsável pela interação com o banco de dados usando JPA.
4. **Model:** Contém as entidades que representam as tabelas do banco de dados.

---

## 🚀 Como Executar o Projeto

### Pré-requisitos
- Java 21 instalado
- Maven configurado
- Banco de Dados PostgreSQL configurado

### Passos
1. Clone o repositório:
   ```bash
   git clone https://github.com/Carlosaleee/LiterAlura.git
   ```
2. Navegue até o diretório do projeto:
   ```bash
   cd LiterAlura
   ```
3. Configure o arquivo `application.properties` com as credenciais do seu banco de dados:
   ```properties
   spring.datasource.url=jdbc:postgresql://localhost/literalura
   spring.datasource.username=<seu-usuario>
   spring.datasource.password=<sua-senha>
   spring.jpa.hibernate.ddl-auto=update
   ```
4. Compile e execute o projeto:
   ```bash
   mvn spring-boot:run
   ```

---

## 🧑‍💻 Desenvolvedor

**Carlos Alexandre da Silva**
- [GitHub](https://github.com/Carlosaleee)
- [LinkedIn](https://www.linkedin.com/in/carlos-alexandre-66b962279/)

---

## 📜 Licença
Este projeto é licenciado sob os termos da licença MIT. Para mais detalhes, consulte o arquivo `LICENSE`.

---

## 🔗 Links
- [Repositório no GitHub](https://github.com/Carlosaleee/LiterAlura)
- [Documentação do Spring Boot](https://spring.io/projects/spring-boot)
- [PostgreSQL Documentation](https://www.postgresql.org/docs/)
