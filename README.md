# CorpX: Empowering Startups through a Comprehensive Social Media Application

Repository for the entire project. Uses git submodule to include all other services.

## Description

Corpx is the backend of a Social Media Application meticulously designed to empower startups by facilitating project management, talent acquisition, and financial support alignment with strategic goals and operational necessities.

## 🚀 Features Implemented

Each service with functionalities implemented is equipped with Swagger for easy endpoint testing and exploration.

### [**Payment Service:**](https://github.com/stnslv-bugaev/payment_service.git)
- 💵 [**Order and Payment services**](https://github.com/stnslv-bugaev/payment_service/blob/phoenix-master-stream8/src/main/java/faang/school/paymentservice/service/payment/PaymentService.java)
    - Implemented an order creation and payment acceptance system

### [**Project Service:**](https://github.com/stnslv-bugaev/post_service)
- 📁 [**NewsFeedService**](https://github.com/stnslv-bugaev/post_service/blob/phoenix-master-stream8-stas/src/main/java/faang/school/postservice/service/NewsFeedService.java)
    - Developed a high-load news feed, using Redis for caching and Kafka for notifications when posts are published

### [**Notification Service:**](https://github.com/stnslv-bugaev/notification_service)
- 📦 [**AbstractEventListener**](https://github.com/stnslv-bugaev/notification_service/blob/phoenix-master-stream8/src/main/java/faang/school/notificationservice/listener/AbstractEventListener.java)
    - Implemented a notification system where the preferred notification method is selected for each user and messages are constructed using MessageBuilder
- 📨 [**SmsService**](https://github.com/stnslv-bugaev/notification_service/blob/phoenix-master-stream8/src/main/java/faang/school/notificationservice/service/notification/impl/SmsService.java)
    - Developer a SmsService that sends SMS messages to users

### [**Account Service:**](https://github.com/stnslv-bugaev/account_service)
- 📰 [**RequestService**](https://github.com/stnslv-bugaev/account_service/blob/phoenix-master-stream8/src/main/java/faang/school/accountservice/service/RequestService.java)
    - Request service that ensures each user operation is executed one at a time

## 🛠 Technologies Utilized

- **Programming Language:**
    - Java
- **Frameworks:**
    - Spring Boot
    - Spring MVC
    - Spring Data
    - Spring Cloud
- **Message Broker:**
    - Kafka
    - Redis Streams
- **Database Management:**
    - Hibernate ORM
    - PostgreSQL
    - Liquibase
- **Containerization:**
    - Docker
- **Version Control:**
    - Git
- **Caching and Message Broker:**
    - Redis
- **Cloud Storage:**
    - AWS S3
    - MinIO
