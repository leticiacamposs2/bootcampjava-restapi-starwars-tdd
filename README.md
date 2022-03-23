# API Rest TDD com Star Wars ✨🚀

![api-rest](https://user-images.githubusercontent.com/34458509/159596858-e41d95a1-9949-4411-924f-f8889b064c0f.png)

---

## Tecnologias

- Java 8
- SpringBoot
- Junit 5
- JBDC Template

---

## Arquitetura do projeto (tecnologias):

- Uso da **JPA** que é a tecnologia de acesso ao banco de dados. Com ele você pode usar os Design Patterns (padrão de design) que não fazem parte do JPA especificamente.

- **Repository** é um Design Pattern onde os dados são obtidos do banco de dados e ocorre também a regra de negócio. Este retorna objetos de domínio que seriam as Entidades (classes anotadas com @Entity).

- **DAO** é outro Design Pattern onde somente há a comunicação com o banco de dados sem regra de negócio.

- **Service** seria outro Desing Pattern onde há somente a regra de negócio e não tem acesso direto ao banco de dados.

- **Controller** Ele é utilizado para lidar com a ligação da View com as outras partes do sistema que são a regra de negócio e banco de dados.
