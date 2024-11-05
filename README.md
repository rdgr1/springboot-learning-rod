# Projeto de Aprendizado de Spring Boot

Este repositório contém um projeto de aprendizado prático para explorar os conceitos e melhores práticas do **Spring Boot**. Ele serve como um guia para desenvolvedores que desejam se aprofundar no desenvolvimento de aplicações Java com a estrutura Spring Boot.

## Funcionalidades

- **Estrutura modular**: Implementação de uma arquitetura limpa, dividida em camadas de controladores, modelos, DTOs e repositórios.
- **Classe de inicialização**: `SpringbootApplication.java` serve como ponto de entrada da aplicação.
- **Exemplos práticos**: Implementações de APIs RESTful e integração com banco de dados.
- **Uso de boas práticas**: Código organizado seguindo padrões de design do Spring Framework.

## Estrutura do Projeto

```bash
springboot-learning-rod/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── rdg/
│   │   │           └── springboot/
│   │   │               ├── SpringbootApplication.java
│   │   │               ├── controllers/
│   │   │               ├── dtos/
│   │   │               ├── models/
│   │   │               └── repositories/
│   │   └── resources/
│   └── test/
├── pom.xml
└── README.md
```

## Tecnologias Utilizadas

- **Java 17+**
- **Spring Boot 3**
- **Maven** para gerenciamento de dependências

## Como Executar

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/rdgr1/springboot-learning-rod.git
   cd springboot-learning-rod
   ```

2. **Compile e execute a aplicação**:
   ```bash
   mvn clean install
   mvn spring-boot:run
   ```

3. **Acesse a aplicação**:
   A API estará disponível em `http://localhost:8080`.

## Estrutura de Código

- **`controllers`**: Contém classes para gerenciar endpoints e lógica de controle.
- **`dtos`**: Define objetos de transferência de dados para comunicação entre camadas.
- **`models`**: Inclui as classes de entidade para mapeamento de dados.
- **`repositories`**: Interfaces para manipulação e persistência de dados com Spring Data JPA.

## Licença

Esse `README.md` reflete a estrutura real do seu projeto e inclui instruções para novos desenvolvedores.
Este projeto é licenciado sob a licença MIT. Consulte o arquivo `LICENSE` para mais detalhes.

---
