# 🌮 SpringTaco

SpringTaco — учебный backend/web-проект на **Java 21 и Spring Boot**, созданный для практического изучения экосистемы Spring и разработки серверных приложений.

Проект использует Spring MVC, Thymeleaf, валидацию данных и стандартные инструменты Spring Boot для разработки и тестирования приложения.

## 🛠️ Tech Stack

* **Java 21**
* **Spring Boot 3.5.3**
* **Spring MVC / Spring Web**
* **Thymeleaf**
* **Spring Validation**
* **Lombok**
* **Maven**
* **Spring Boot Test**

## 📌 Project Goals

Основная цель проекта — практическое изучение и применение возможностей Spring Framework:

* разработка web-приложений на Spring Boot;
* создание MVC-контроллеров;
* обработка HTTP-запросов;
* работа с Thymeleaf;
* валидация пользовательских данных;
* использование dependency injection;
* написание тестов;
* управление зависимостями через Maven.

## 🏗️ Application Architecture

Проект построен с использованием подхода **Spring MVC**:

```text
Client
  │
  ▼
Controller
  │
  ▼
Application / Domain Logic
  │
  ▼
View / Response
  │
  ▼
Thymeleaf
```

Spring MVC отвечает за обработку HTTP-запросов, контроллеры — за взаимодействие с приложением, а Thymeleaf используется для формирования HTML-страниц.

## 🎨 Thymeleaf

Для серверного формирования HTML используется **Thymeleaf**.

Это позволяет связывать Java-модели приложения с HTML-шаблонами непосредственно на стороне сервера.

## ✅ Validation

Для проверки входных данных используется:

```text
spring-boot-starter-validation
```

Это позволяет валидировать данные, поступающие от пользователя, до их дальнейшей обработки приложением.

## 🧪 Testing

Для тестирования используется Spring Boot Test:

```bash
./mvnw test
```

Для Windows:

```powershell
.\mvnw.cmd test
```

## 🚀 Getting Started

### Requirements

Для запуска проекта требуется:

* JDK 21;
* Git.

Maven устанавливать отдельно не требуется — проект содержит Maven Wrapper.

### Clone

```bash
git clone https://github.com/hacker2023beginer/SpringTaco.git
cd SpringTaco
```

### Run

Linux / macOS:

```bash
./mvnw spring-boot:run
```

Windows:

```powershell
.\mvnw.cmd spring-boot:run
```

После запуска приложение будет доступно на локальном сервере Spring Boot.

## 🔨 Build

Сборка проекта:

```bash
./mvnw clean package
```

Windows:

```powershell
.\mvnw.cmd clean package
```

## 📁 Project Structure

Проект использует стандартную структуру Maven:

```text
SpringTaco/
├── .mvn/
│   └── wrapper/
├── src/
│   ├── main/
│   │   ├── java/
│   │   └── resources/
│   └── test/
├── .gitignore
├── .gitattributes
├── mvnw
├── mvnw.cmd
├── pom.xml
└── README.md
```

## 📚 Technologies Practiced

В рамках проекта изучаются и применяются:

* Spring Boot;
* Spring MVC;
* Thymeleaf;
* dependency injection;
* controllers;
* server-side rendering;
* data validation;
* Maven;
* unit/integration testing;
* Lombok.

## 📈 Project Status

Проект находится в стадии разработки и используется как практический проект для изучения Java Backend и Spring Framework.

## 👨‍💻 Author

**Vladislav**

GitHub:
https://github.com/hacker2023beginer

---

⭐ If you find this project useful, feel free to star the repository.
