Bem-vindo ao workspace "my-soc-ops-java"!

Este é um tour rápido para começar a desenvolver localmente.

1) Requisitos
- Java JDK 21
- VS Code com extensão Java (opcional)

2) Comandos úteis
- Build (maven):
  - `cd socops && ./mvnw -DskipTests clean package`
- Rodar em desenvolvimento (task VS Code):
  - Use a task `mvn: run` ou execute `cd socops && ./mvnw spring-boot:run`

3) Endpoints principais
- App web: http://localhost:8080

4) Onde estão os pontos-chave do código
- Entrada da aplicação: `src/main/java/com/socops/SocOpsApplication.java`
- API REST: `src/main/java/com/socops/web/BingoRestController.java`
- Montagem do tabuleiro: `src/main/java/com/socops/service/BoardAssembler.java`

5) Testes
- Rodar testes: `cd socops && ./mvnw test`

6) Próximos passos sugeridos
- Abrir [docs/step.html](docs/step.html) para ver materiais do workshop.
- Experimentar editar templates em `src/main/resources/templates/game.html`.

Se quiser, posso adicionar um badge de execução no README.md ou criar scripts de ajuda. Diga o que prefere.
