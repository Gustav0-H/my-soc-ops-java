Checklist obrigatório de desenvolvimento
- Lint: `cd socops && ./mvnw checkstyle:check` (ou a ferramenta de lint do projeto)
- Build: `cd socops && ./mvnw -DskipTests clean package`
- Test: `cd socops && ./mvnw test`

Quickstart (resumido)
- Requisitos: Java JDK 21
- Build: `cd socops && ./mvnw -DskipTests clean package`
- Rodar em dev: `cd socops && ./mvnw spring-boot:run` ou use a task VS Code `mvn: run`
- Acesso: http://localhost:8080

Locais importantes
- Entrada: `socops/src/main/java/com/socops/SocOpsApplication.java`
- API: `socops/src/main/java/com/socops/web/BingoRestController.java`
- Serviço do tabuleiro: `socops/src/main/java/com/socops/service/BoardAssembler.java`
- Templates: `socops/src/main/resources/templates/`

Recursos
- Tour rápido: `docs/WORKSPACE_TOUR.md`

Problemas comuns
- Porta ocupada: ajuste `server.port` em `socops/src/main/resources/application.properties`.
- JDK incorreto: verifique `java -version` e `./mvnw -v`.

Deseja que eu adicione um badge de CI no `README.md` ou configure um `devcontainer`?
