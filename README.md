# 💊 MedAlerta

> Sistema de gerenciamento e acompanhamento de medicamentos desenvolvido em Java e Spring Boot, com persistência de dados em MySQL e ambiente containerizado com Docker.

---

## 📌 Sobre o projeto

O **MedAlerta** é um sistema desenvolvido para auxiliar no gerenciamento de medicamentos, permitindo o cadastro de usuários, medicamentos e o vínculo entre eles.

O projeto foi desenvolvido com foco na aplicação prática de conceitos de desenvolvimento backend, persistência de dados, arquitetura em camadas e utilização de containers Docker.

---

## 🎓 Contexto acadêmico

O MedAlerta foi desenvolvido durante o **Bootcamp de Engenharia de Software da UNINTER**, realizado em 2026.

O projeto fez parte das atividades práticas do bootcamp, nas quais foram apresentados conceitos e tecnologias utilizados no desenvolvimento de aplicações backend.

A equipe desenvolveu e evoluiu o sistema a partir da estrutura e dos conhecimentos apresentados durante o bootcamp.

---

## 👥 Equipe

Projeto desenvolvido em equipe durante o Bootcamp de Engenharia de Software da UNINTER.

| Integrante | GitHub |
|---|---|
| Cesar Augusto | [@Cesarleitor](https://github.com/Cesarleitor) |
| Mariana Alexandre | [@MarianaUY](https://github.com/MarianaUY) |
| Cruz | [@clearlce-dev](https://github.com/clearIce-dev) |
| Filipe Mariano Rocha | [@Filipe-glitch](https://github.com/Filipe-glitch) |
| Higor Rodrigues dos Santos | [@Higor-dev-rs](https://github.com/Higor-dev-rs) |

---

## 👨‍🏫 Professores

O projeto foi desenvolvido com orientação dos professores responsáveis pelo Bootcamp de Engenharia de Software da UNINTER:

- [Prof. Me. Rodrigo da Silva do Nascimento](https://github.com/nascimentoRodrigo)
- [Prof. Me. Guilherme Patriota](https://github.com/guipatriota)
- [Prof. PhD. Neusa Grando](https://github.com/neusagrando)
- [Prof. Me. Jadson Almeida](https://github.com/jadinhu)

---

## ✨ Funcionalidades

- Cadastro, consulta, atualização e remoção de usuários;
- Cadastro, consulta, atualização e remoção de medicamentos;
- Associação entre usuários e medicamentos;
- Consulta dos medicamentos vinculados a um usuário;
- Controle de horário de uso dos medicamentos;
- Registro de alertas;
- Registro e confirmação do consumo de medicamentos;
- Consultas e listagens relacionadas aos usuários, medicamentos e seus vínculos.

---

## 🛠️ Tecnologias

- **Java**
- **Spring Boot**
- **Spring Data JPA**
- **Hibernate**
- **MySQL**
- **Docker**
- **Maven**
- **Git**
- **GitHub**

---

## 📁 Estrutura do projeto

```text
Projeto-Turma-2---MediAlerta/
├── .devcontainer/
├── .github/
├── docker/
├── docs/   
├── src/
├── docker-compose.yml
├── Dockerfile
├── pom.xml
└── README.md

```
## 🚀 Como executar o projeto

```bash
docker compose up -d
docker compose attach app
```

## 🛑 Parando o projeto

```bash
docker compose down
```