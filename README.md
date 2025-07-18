# 📚 Spring Data JPA Specification Demo

<p align="center">
  <img src="https://img.shields.io/badge/Java-11%2B-blue?style=for-the-badge&logo=java"/>
  <img src="https://img.shields.io/badge/Spring%20Boot-2.5.4-brightgreen?style=for-the-badge&logo=spring-boot"/>
  <img src="https://img.shields.io/badge/H2-Database-blue?style=for-the-badge&logo=h2"/>
  <img src="https://img.shields.io/badge/Maven-Build-red?style=for-the-badge&logo=apache-maven"/>
</p>

<div align="center">
  <b>🇧🇷 Português | <a href="#english-version">🇺🇸 English below</a></b>
</div>

---

## 📑 Sumário | Table of Contents
- [Sobre o Projeto | About](#sobre-o-projeto--about)
- [Tecnologias | Technologies](#tecnologias--technologies)
- [Estrutura | Structure](#estrutura--structure)
- [Configuração | Setup](#configuração--setup)
- [Banco de Dados | Database](#banco-de-dados--database)
- [Testes | Tests](#testes--tests)
- [Autor | Author](#autor--author)

---

## Sobre o Projeto | About

**PT-BR:**
> Projeto de demonstração do uso de Specifications com Spring Data JPA. Permite consultas avançadas e dinâmicas em entidades usando a API Criteria do JPA. Utiliza banco de dados H2 em memória para facilitar testes e demonstrações.

**EN:**
> Demo project for using Specifications with Spring Data JPA. Enables advanced and dynamic queries on entities using JPA Criteria API. Uses in-memory H2 database for easy testing and demonstration.

---

## 🚀 Tecnologias | Technologies
- Java 11+
- Spring Boot 2.5.4
- Spring Data JPA
- H2 Database
- Maven

---

## 🗂️ Estrutura | Structure
```
spring-data-jpa-specification/
├── pom.xml
├── src/
│   ├── main/
│   │   ├── java/com/example/advancedsearch/
│   │   │   ├── AdvancedSearchApplication.java
│   │   │   ├── dto/
│   │   │   ├── enums/
│   │   │   ├── model/
│   │   │   ├── repository/
│   │   │   ├── resource/
│   │   │   ├── service/
│   │   │   └── specification/
│   │   └── resources/
│   │       └── application.properties
│   └── test/
│       └── java/com/example/advancedsearch/
│           └── AdvancedSearchApplicationTests.java
└── README.md
```

---

## ⚙️ Configuração | Setup

**PT-BR:**
1. **Pré-requisitos:** Java 11+, Maven
2. **Banco de dados:**
   - O projeto já está configurado para usar o banco H2 em memória (não é necessário instalar nada).
   - As configurações estão em `src/main/resources/application.properties`.
3. **Build e execução:**
   ```bash
   mvn clean install
   mvn spring-boot:run
   ```
   O serviço estará em `http://localhost:8080`.

**EN:**
1. **Prerequisites:** Java 11+, Maven
2. **Database:**
   - The project is already configured to use the in-memory H2 database (no installation required).
   - Settings are in `src/main/resources/application.properties`.
3. **Build and run:**
   ```bash
   mvn clean install
   mvn spring-boot:run
   ```
   The service will be at `http://localhost:8080`.

---

## 🗄️ Banco de Dados | Database
- **PT-BR:** O projeto utiliza banco H2 em memória para facilitar testes e demonstrações.
- **EN:** The project uses in-memory H2 database for easy testing and demonstration.

---

## 🧪 Testes | Tests
- **PT-BR:** Teste básico de contexto Spring Boot em `src/test/java/com/example/advancedsearch/AdvancedSearchApplicationTests.java`.
- **EN:** Basic Spring Boot context test in `src/test/java/com/example/advancedsearch/AdvancedSearchApplicationTests.java`.

---

## 👤 Autor | Author

<div align="center">
  <b>Feito com 💙 para estudos de Java, Spring Boot e JPA Specifications.<br/>
  Made with 💙 for Java, Spring Boot and JPA Specifications studies.</b>
</div>

---

<div align="center" id="english-version">
  <b>🇺🇸 English version above | <a href="#top">🇧🇷 Versão em português acima</a></b>
</div>