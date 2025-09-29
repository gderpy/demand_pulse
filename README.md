# DemandPulse

DemandPulse — аналитика спроса и динамическое ценообразование.

Микросервисный проект на Python (FastAPI + SQLAlchemy + PostgreSQL + Docker), демонстрирующий:
- архитектуру микросервисов;
- работу с аналитикой спроса;
- рекомендации по ценам и закупкам;
- CI/CD пайплайны;
- безопасность по OWASP Top 10;
- тестирование (pytest, coverage);
- деплой (docker-compose / k8s).

Фичи:
- Sales Collector (CRUD по продажам).
- Analytics Engine (ABC/XYZ анализ).
- Recommendation Service (динамическое ценообразование).
- Auth Service (JWT + RBAC).
- API Gateway.
