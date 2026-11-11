# SGI · Sistema de gestión interna de Harpa

Back-office con el que **[Harpa SpA](https://harpa.cl)** administra su negocio y sus productos SaaS: clientes, suscripciones, finanzas, facturación y soporte. Es el sistema central al que se conectan los demás productos de Harpa, como el [POS](https://github.com/HaxPG/harpa-pos), para sincronizar planes y límites de cada cliente.

> **El código fuente es privado** y pertenece a [Harpa SpA](https://github.com/Harpa-SpA). Este repositorio solo presenta el proyecto. Si quieres conocer más detalles técnicos o ver una demo, escríbeme por [LinkedIn](https://www.linkedin.com/in/nain-burgos-ortiz-b96b35260) o en [harpa.cl/contacto](https://harpa.cl/contacto).

## Qué hace

- **Clientes y ventas:** CRM, empresas y contactos, cotizaciones, demos y registro público de clientes.
- **SaaS:** gestión de sistemas, planes y suscripciones, usuarios de cada producto y sincronización de planes con los SaaS.
- **Finanzas:** finanzas, contabilidad, inversiones y facturación electrónica con el SII.
- **Soporte y comunicación:** tickets de soporte, portal de clientes, campañas y mailing, notificaciones en tiempo real.
- **Equipo:** recursos humanos, usuarios internos y documentos.
- **Operación y seguridad:** monitoreo de servidores y de seguridad, auditoría, respaldos, mantención de la base de datos y control del uso de IA.

## Tecnologías

- **Frontend:** Angular 20, Angular Material, Socket.IO
- **Backend:** NestJS, TypeScript, TypeORM, MySQL 8, Redis y BullMQ (colas), WebSockets, API documentada con Swagger
- **Seguridad:** JWT con Passport, passkeys (WebAuthn), rate limiting, auditoría
- **Operación:** Sentry, S3, Docker, Docker Compose

## Mi rol

Cofundador y desarrollador full-stack en Harpa SpA, empresa que desarrolla y opera el sistema.
