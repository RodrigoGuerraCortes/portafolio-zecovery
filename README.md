# 💼 Zecovery — Payment & Document Management Systems / Sistemas de Pago y Gestión Documental

> 🇬🇧 English version below — Versión en español más abajo ⬇️

---

## 🇬🇧 English Version

### 🧩 Context

At **Zecovery**, I worked as a **Software Engineer** leading multiple projects focused on process optimization, digital payments, and document management for municipalities and public institutions in Chile.

The company’s main challenge was handling high transaction volumes securely and automating workflows across different systems.

### 🎯 Objective

Develop robust and scalable systems that support daily financial and document operations for municipal and enterprise clients, while maintaining strict reliability and data integrity.

### ⚙️ Tech Stack

| Project                              | Backend    | Frontend       | Database   | Infrastructure / Tools  |
| ------------------------------------ | ---------- | -------------- | ---------- | ----------------------- |
| **SEM2 (Municipal Payment System)**  | Laravel 9  | Vue 2          | PostgreSQL | Docker, GitLab CI       |
| **Temporary File URL System (AWS)**  | Laravel 9  | Vue 2          | PostgreSQL | AWS S3, Pre-signed URLs |
| **Zefactura (Electronic Invoicing)** | Laravel 10 | Vue 3 + NuxtJS | PostgreSQL | Docker, GitLab CI       |
| **Ceropapel (Document Management)**  | PHP 5/7/8  | jQuery + JS    | PostgreSQL | Apache, Linux           |

---

### 🚀 Key Achievements


* **SEM2** was architected as a **microservice ecosystem**, where each municipal procedure (license, permit, patent, etc.) was developed as an independent service.
* Central shared modules — such as **Users**, **Accounts**, and **Procedures** — acted as core packages, reused across all services.
* Designed lightweight **RESTful communication** between microservices and internal event-driven jobs for data synchronization.

* Applied **TDD (Test-Driven Development)** across Laravel projects to ensure payment accuracy, data consistency, and maintainability.
* Implemented a **secure AWS API for temporary file access**, generating signed URLs with expiration for user downloads.
* Built **Zefactura**, a modular invoicing system capable of generating and validating electronic invoices for multiple institutions.
* Designed **unit and functional tests** to validate invoice data integrity and backend workflows.
* Provided long-term **support for Ceropapel**, improving document workflows and upgrading legacy PHP code to modern versions.

---

### 🧱 Architecture Overview

```text
[ Vue Frontend ] ↔ [ Laravel API ] ↔ [ PostgreSQL ]
                            │
                            ├──→ [ AWS S3 (Temporary Signed URLs) ]
                            ├──→ [ Electronic Invoice API (Zefactura) ]
                            └──→ [ Payment Gateway Integration (SEM2) ]
```

---

### 🧪 Engineering Practices

* Full **TDD workflow** (unit + feature + integration tests).
* Continuous Integration with **GitLab CI/CD pipelines**.
* Code review culture and reusable backend modules.
* Agile methodology for fast iteration and delivery.
* Use of **Docker containers** for consistent environments.

---

### 🧾 Impact

* Improved payment processing reliability for many **municipalities**.
* Reduced deployment errors through Dockerized environments.
* Achieved **90%+ test coverage** on core financial and invoicing modules.
* Enhanced backend resilience with automated exception handling and monitoring.

---

## 🇪🇸 Versión en Español

### 🧩 Contexto

En **Zecovery**, trabajé como **Ingeniero de Desarrollo** liderando diversos proyectos orientados a la optimización de procesos, pagos digitales y gestión documental para municipalidades e instituciones públicas en Chile.

El principal desafío era manejar altos volúmenes de transacciones con seguridad y automatizar flujos críticos en entornos mixtos de tecnologías modernas y heredadas.

### 🎯 Objetivo

Desarrollar sistemas robustos y escalables que soporten las operaciones financieras y documentales diarias de clientes municipales y empresariales, asegurando confiabilidad e integridad de datos.

### ⚙️ Stack Tecnológico

| Proyecto                                | Backend    | Frontend       | Base de Datos | Infraestructura / Herramientas |
| --------------------------------------- | ---------- | -------------- | ------------- | ------------------------------ |
| **SEM2 (Sistema de Pagos Municipales)** | Laravel 9  | Vue 2          | PostgreSQL    | Docker, GitLab CI              |
| **Sistema de URLs Temporales (AWS)**    | Laravel 9  | Vue 2          | PostgreSQL    | AWS S3, URLs Firmadas          |
| **Zefactura (Facturación Electrónica)** | Laravel 10 | Vue 3 + NuxtJS | PostgreSQL    | Docker, GitLab CI              |
| **Ceropapel (Gestión Documental)**      | PHP 5/7/8  | jQuery + JS    | PostgreSQL    | Apache, Linux                  |

---

### 🚀 Logros Destacados

* **SEM2** fue diseñado bajo una **arquitectura de microservicios**, donde cada trámite (licencia, permiso, patente, etc.) se implementó como un servicio independiente.
* Se crearon **paquetes centrales compartidos** — como **Usuarios**, **Cuentas** y **Trámites** — utilizados transversalmente por todos los microservicios.
* Comunicación interna mediante **APIs RESTful ligeras** y sincronización de datos con procesos asíncronos tipo evento.
* Aplicación de **TDD (Desarrollo Guiado por Pruebas)** en Laravel para garantizar exactitud en pagos y confiabilidad de datos.
* Implementación de un sistema **AWS S3 con URLs temporales**, generadas mediante APIs seguras y control de expiración.
* Creación del sistema **Zefactura**, modular y adaptable para la generación y validación de facturas electrónicas.
* Implementación de **pruebas unitarias y funcionales** para garantizar integridad y precisión en los datos.
* Soporte y evolución del sistema **Ceropapel**, modernizando su arquitectura PHP y mejorando la gestión documental.

---

### 🧱 Arquitectura General

```text
[ Frontend Vue ] ↔ [ API Laravel ] ↔ [ PostgreSQL ]
                         │
                         ├──→ [ AWS S3 (URLs Temporales Firmadas) ]
                         ├──→ [ API Facturación Electrónica (Zefactura) ]
                         └──→ [ Integración Pasarelas de Pago (SEM2) ]
```

---

### 🧪 Buenas Prácticas

* Flujo completo de **TDD** (pruebas unitarias, funcionales e integraciones).
* Integración Continua con **GitLab CI/CD**.
* Modularización del backend y revisiones de código.
* Metodología **ágil** para desarrollo iterativo.
* Uso de **contenedores Docker** para garantizar entornos reproducibles.

---

### 🧽 Impacto

* Mayor confiabilidad en el procesamiento de pagos de muchas **municipalidades**.
* Reducción de errores de despliegue mediante entornos dockerizados.
* **Cobertura de pruebas superior al 90 %** en módulos financieros y de facturación.
* Aumento de resiliencia del backend con manejo automático de excepciones y monitoreo.

---

## 👨‍💻 Author

**Rodrigo Guerra Cortés**
Full Stack Developer — Chile 🇨🇱
📧 [rguerracortes@gmail.com](mailto:rguerracortes@gmail.com)
🌐 [LinkedIn](https://linkedin.com/in/rodrigoguerracortes)

---

## 🧪 License

This documentation is part of Rodrigo Guerra’s professional portfolio.
All source code for the original Zecovery systems is private and owned by the company.
