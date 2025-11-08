# Centralized Configs (Spring Cloud Config)

Именование: <spring.application.name>[-<profile>].yml  
Клиентское приложение будет называться `client-app`, поэтому здесь лежат:
- `client-app.yml` (дефолт)
- `client-app-dev.yml` (профиль dev)
- `client-app-prod.yml` (профиль prod)

(Опционально) `application.yml` — глобальные дефолты для всех приложений.
