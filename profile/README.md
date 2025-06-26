<h1 align="center">🎮 Онлайн магазин.</h1>

<p align="center">
  Проекты по разработке веб-приложений, десктопных утилит и инфраструктурных решений.<br>
  Особое внимание уделяется архитектуре безопасности, микросервисам и интеграции современных стеков.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Spring_Boot-3.x-green?logo=springboot&logoColor=white">
  <img src="https://img.shields.io/badge/OAuth2-Security-blue?logo=springsecurity">
  <img src="https://img.shields.io/badge/RabbitMQ-Messaging-orange?logo=rabbitmq">
  <img src="https://img.shields.io/badge/Keycloak-SSO-red?logo=keycloak">
  <img src="https://img.shields.io/badge/Prometheus-Monitoring-orange?logo=prometheus">
</p>

---

## 📦 Основные проекты

### 🛒 Онлайн-магазины игр

| Проект | Описание | Технологии |
|--------|----------|------------|
| [Online-Storage-Classic](https://github.com/Online-video-game-store/Online-Storage-Classic) | Онлайн-магазин по классической схеме с собственным OAuth2-сервером и синхронным HTTP-взаимодействием между сервисами. | Spring Boot, Spring Security, OAuth2, Feign, RabbitMQ, Prometheus |
| [Online-Game-Storage](https://github.com/Online-video-game-store/Online-Game-Storage) | Аналогичный магазин, но с Keycloak как сервером авторизации, асинхронным взаимодействием через RabbitMQ и Gateway в роли OAuth2-клиента. | Spring Security, RabbitMQ, Keycloak |

---

## 🔧 Используемые технологии

- ✅ **Spring Boot 3.x**, **Spring ramework 6.x**
- 🔐 **Spring Security**, **OAuth2 Authorization Server**, **Keycloak**
- 📡 **RabbitMQ**, **WebSocket**, **Feign**
- 🛢️ **MySQL**, **JPA**
- 📊 **Actuator**, **Prometheus**, **Grafana**
- 📱 **Android SDK**, **Swing**
- 🐳 **Docker**, **Docker Compose**
  
---

## 🧠 О подходе

Проекты создаются с уклоном в:

- 🧩 **Архитектуру микросервисов**
- 🔐 **Безопасность и авторизацию (OAuth2, JWT)**
- 📬 **Межсервисное взаимодействие (HTTP, AMQP)**
- 📈 **Мониторинг и масштабируемость**

Фокус — не просто рабочий код, а практическое применение продвинутых паттернов Spring-экосистемы.

---

## 🚀 Планы на будущее

- [ ] Переход на реактивный стек (WebFlux + RSocket)
- [ ] Внедрение BFF-паттерна и SSR-UI
- [ ] Контейнеризация с Docker Compose и Helm-чартами
- [ ] CI/CD через GitHub Actions

---

## 📫 Связь и поддержка

Если у вас есть вопросы, идеи или предложения — добро пожаловать в [Issues](https://github.com/Online-video-game-store/Online-Game-Storage/issues) соответствующего проекта или через Pull Request.

⭐ Если проект был полезен — не забудьте поставить звезду!

---
