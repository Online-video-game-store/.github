## 📦 Онлайн-магазины.
Два pet-проекта, выполняющих одну и ту же задачу, но с разными реализациями.
Особое внимание уделяется архитектуре безопасности, микросервисам и интеграции современных стеков.

В качестве товара используются старые видеоигры, просто потому, что банальные телефоны, гаджеты и шмотки порядком поднадоели, 
да и скриншотов с видеоигр наделать проще.

| Проект | Описание | Технологии |
|--------|----------|------------|
| [Online-Storage-Classic](https://github.com/Online-video-game-store/Online-Storage-Classic.git) | Онлайн-магазин по классической схеме с собственным OAuth2-сервером и синхронным HTTP-взаимодействием между сервисами. | Spring Boot, Spring Security, OAuth2, Eureka, Feign, RabbitMQ, Prometheus |
| [Online-Game-Storage](https://github.com/Online-video-game-store/Online-Game-Storage.git) | Аналогичный магазин, но с Keycloak как сервером авторизации, асинхронным взаимодействием через RabbitMQ и Gateway в роли OAuth2-клиента. | Spring Security, Eureka, RabbitMQ, Keycloak |

---

## 🔧 Используемые технологии

- ✅ **Spring Boot 3.x**, **Spring ramework 6.x**
- 🔐 **Spring Security**, **OAuth2 Authorization Server**, **Keycloak**
- 📡 **RabbitMQ**, **WebSocket**, **Feign**
- 🛢️ **MySQL**, **JPA**
- 📊 **Actuator**, **Prometheus**, **Grafana**
- 🌐 **Thymeleaf**, **JavaScript** (UI реализован базово, без фреймворков — в основном для демонстрации логики)
- 🐳 **Docker**, **Docker Compose**
  
---

## 🧠 О подходе

Проект создавался с уклоном в:

- 🧩 **Архитектуру микросервисов**
- 🔐 **Безопасность и авторизацию (OAuth2, JWT)**
- 📬 **Межсервисное взаимодействие (HTTP, AMQP)**
- 📈 **Мониторинг и масштабируемость**

Фокус — не просто рабочий код, а практическое применение продвинутых паттернов Spring-экосистемы.

