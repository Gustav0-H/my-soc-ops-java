🌐 [Português (BR)](README.pt_BR.md) | [Español](README.es.md)

[![CI](https://github.com/Gustav0-H/my-soc-ops-java/actions/workflows/ci.yml/badge.svg)](https://github.com/Gustav0-H/my-soc-ops-java/actions/workflows/ci.yml)

# Soc Ops

> Turn casual events into playful networking with a Social Bingo experience.

## What is Soc Ops?

**Soc Ops** is a Java Spring Boot app that turns ice-breaking into a game:
- Create a bingo card of people-friendly questions
- Match people across the room with fun prompts
- Win by getting 5 boxes in a row

It is built as a learning playground for Java web development, Spring Boot, Thymeleaf, and modern CI workflows.

## Why this project matters

- Great for in-person mixers, meetups, and onboarding events
- Shows how to build a small web app with real interactions
- Includes a workshop-style guide for hands-on learning

## Quick Start

```bash
cd socops
./mvnw spring-boot:run
```

Open the app at:

```text
http://localhost:8080
```

## One-click commands

```bash
cd socops
./mvnw -DskipTests clean package
./mvnw test
```

## Explore the workshop

Start here for the guided lab:

- 📘 [Workshop Guide](workshop/GUIDE.md)
- 00 Overview & Checklist
- 01 Setup & Context Engineering
- 02 Design-First Frontend
- 03 Custom Quiz Master
- 04 Multi-Agent Development

## Project structure

- `socops/src/main/java/com/socops/SocOpsApplication.java` — app entry point
- `socops/src/main/java/com/socops/web/BingoRestController.java` — REST controller
- `socops/src/main/java/com/socops/service/BoardAssembler.java` — bingo board assembly
- `socops/src/main/resources/templates/` — UI templates

## Development checklist

- [x] Java 21 JDK
- [x] Build with Maven
- [x] Run tests
- [x] CI workflow enabled

## Want to contribute?

Feel free to explore the code, update the workshop guide, or improve the app experience. This repo is a great starting point for learning full-stack Java development.
