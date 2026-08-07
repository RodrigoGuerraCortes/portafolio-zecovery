# 💼 Zecovery — Payments & Document Systems Case Study

> Professional portfolio case study. Original source code and proprietary implementation details are not included.

## 🇬🇧 English

### Context

At **Zecovery** I worked as a **Full Stack Developer / Software Engineer** on systems used by municipalities and other organizations in Chile.

The work involved digital payments, document workflows, secure file delivery and modernization of existing applications.

### Selected problems I worked on

#### Municipal payment workflows

I worked on **SEM2**, a platform used for municipal procedures such as licenses, permits and vehicle-related payments.

The system had to support high daily transaction volumes while keeping the application modular and maintainable.

My work included:

- backend development with **Laravel**;
- frontend work with **Vue**;
- **PostgreSQL** persistence;
- REST communication between services;
- reusable modules shared across different municipal procedures;
- automated testing and deployment practices.

According to my professional project record, the platform processed **thousands of payments per day**.

#### Secure temporary file delivery

I designed a mechanism for controlled access to files stored in **AWS**, exposing an API that generated temporary download URLs with expiration.

```text
[ Client request ]
       │
       ▼
[ Laravel API ]
       │
       ▼
[ Authorization / validation ]
       │
       ▼
[ AWS S3 signed URL ]
       │
       ▼
[ Time-limited download ]
```

This pattern allowed files to remain private while applications could grant temporary access when required.

#### Electronic invoicing and legacy systems

Other work included:

- modular electronic invoicing workflows;
- unit and functional testing around financial data;
- maintaining document-management applications;
- modernizing legacy PHP code while preserving business continuity.

### Technology stack

| Area | Technologies |
| --- | --- |
| Backend | PHP, Laravel |
| Frontend | Vue, Nuxt, JavaScript, jQuery |
| Database | PostgreSQL |
| Cloud / storage | AWS S3, signed URLs |
| Infrastructure | Docker, Linux |
| Delivery | GitLab CI/CD |
| Engineering | REST APIs, automated tests, TDD practices |

### What this experience demonstrates

- Experience with **payment and transaction-oriented systems**.
- Ability to integrate **cloud services and secure file-access workflows**.
- Experience evolving both modern and legacy applications.
- Strong understanding of backend business rules and data integrity.
- Ability to work across backend, frontend, infrastructure and testing when the project requires it.

---

## 🇪🇸 Español

### Contexto

En **Zecovery** trabajé como **Desarrollador Full Stack / Ingeniero de Software** en sistemas utilizados por municipalidades y otras organizaciones en Chile.

Mi trabajo involucró pagos digitales, flujos documentales, entrega segura de archivos y modernización de aplicaciones existentes.

### Problemas representativos

#### Flujos de pagos municipales

Trabajé en **SEM2**, una plataforma utilizada para trámites municipales como patentes, permisos y pagos relacionados con vehículos.

El sistema debía soportar un volumen importante de transacciones manteniendo una arquitectura modular y mantenible.

Mi participación incluyó:

- desarrollo backend con **Laravel**;
- frontend con **Vue**;
- persistencia con **PostgreSQL**;
- comunicación REST entre servicios;
- módulos reutilizables para distintos trámites;
- pruebas automatizadas y prácticas de despliegue.

De acuerdo con mi registro profesional del proyecto, la plataforma procesaba **miles de pagos al día**.

#### Entrega segura de archivos temporales

Diseñé un mecanismo para entregar acceso controlado a archivos almacenados en **AWS**, mediante una API que generaba URLs temporales con expiración.

```text
[ Solicitud cliente ]
       │
       ▼
[ API Laravel ]
       │
       ▼
[ Autorización / validación ]
       │
       ▼
[ URL firmada AWS S3 ]
       │
       ▼
[ Descarga temporal ]
```

Esto permitía mantener los archivos privados y entregar acceso únicamente durante el periodo autorizado.

#### Facturación electrónica y sistemas legacy

Otros trabajos incluyeron:

- flujos modulares de facturación electrónica;
- pruebas unitarias y funcionales sobre procesos financieros;
- mantenimiento de sistemas de gestión documental;
- modernización de código PHP legacy sin interrumpir la continuidad operacional.

### Stack tecnológico

| Área | Tecnologías |
| --- | --- |
| Backend | PHP, Laravel |
| Frontend | Vue, Nuxt, JavaScript, jQuery |
| Base de datos | PostgreSQL |
| Cloud / almacenamiento | AWS S3, URLs firmadas |
| Infraestructura | Docker, Linux |
| Entrega | GitLab CI/CD |
| Ingeniería | REST APIs, pruebas automatizadas, prácticas TDD |

### Qué demuestra esta experiencia

- Experiencia con **sistemas transaccionales y de pagos**.
- Integración de **servicios cloud y acceso seguro a archivos**.
- Capacidad para evolucionar aplicaciones modernas y legacy.
- Comprensión de reglas de negocio backend e integridad de datos.
- Capacidad full stack cuando el problema requiere intervenir en distintas capas.

---

## Contact

**Rodrigo Guerra Cortés**  
Backend & Integration Engineer — Chile 🇨🇱  
[GitHub Profile](https://github.com/RodrigoGuerraCortes) · [LinkedIn](https://www.linkedin.com/in/rodrigo-guerra-cortes) · [Email](mailto:rguerracortes@gmail.com)

> This repository contains a high-level description of professional work only. No proprietary source code, credentials or confidential client information is included.
