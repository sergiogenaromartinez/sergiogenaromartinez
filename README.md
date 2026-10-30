# Portfolio Profesional | Full Stack & Enterprise Software Developer

¡Hola! Soy un **Desarrollador Full Stack y Mobile con enfoque Enterprise**. Me especializo en el diseño, arquitectura e integración de sistemas críticos, plataformas de alta concurrencia industriales, automatización de procesos mediante CRMs de clase mundial y soluciones móviles integradas a sistemas de facturación gubernamentales.

Mi experiencia abarca desde la optimización de bases de datos relacionales masivas hasta la implementación de interfaces de usuario modernas y ágiles para sectores industriales, gubernamentales y de telecomunicaciones.

---

## 🛠️ Stack Tecnológico General

| Capa / Especialidad | Tecnologías y Herramientas |
| :--- | :--- |
| **Frontend & Web** | ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white) |
| **Mobile Development** | ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white) ![Ionic](https://img.shields.io/badge/Ionic-3880FF?style=flat-square&logo=ionic&logoColor=white) ![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white) |
| **Backend & APIs** | ![.NET Core](https://img.shields.io/badge/.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=java&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white) |
| **Bases de Datos & BI** | ![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-00758F?style=flat-square&logo=mysql&logicColor=white) `SSRS (Reporting Services)` |
| **Enterprise & Cloud** | ![Salesforce](https://img.shields.io/badge/Salesforce-00A1E0?style=flat-square&logo=salesforce&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white) |

---

## 💼 Proyectos Destacados (Fichas Técnicas)

> 🔒 **Nota de Confidencialidad:** Por motivos de acuerdos de confidencialidad (NDA), propiedad intelectual y seguridad de la información corporativa, los nombres de ciertas entidades han sido generalizados, los datos en producción omitidos y las interfaces de los sistemas se describen bajo criterios de arquitectura técnica mas no visual explícita.

### 1. Sistema Integrado de Control de Producción (MES/ERP) — Sector Textil
* **Rol:** Lead Full Stack & Mobile Developer.
* **Stack:** `Angular 16+`, `Ionic`, `Node.js / .NET Core`, `SQL Server`.

```
[ Web Admin (Angular) ] <---> [ Central REST API (.NET/Node) ] <---> [ SQL Server (Múltiples Nodos) ]
                                        ^
                                        |
                            [ Planta Móvil (Ionic) ]
```

* **Descripción:** Plataforma robusta para la gestión punta a punta de plantas de maquila textil de alta capacidad. Centraliza el flujo de Órdenes de Compra (PO), planificación de recursos, corte, costura, empaque, control de calidad, eficiencia de maquinaria y rendimiento del personal en planta.
* **Reto Técnico & Acción:** Se diseñó una arquitectura desacoplada donde el portal web de Angular maneja la alta carga administrativa y reportería gerencial, mientras que clientes móviles en Ionic (desplegados en tabletas industriales en planta de costura) capturan métricas en tiempo real. Implementé lógica avanzada en base de datos para el cálculo en vivo de eficiencia operativa de operarios y balanceo de líneas mediante balanceadores de carga en la API para tolerar la alta concurrencia de eventos en piso.
* **Impacto:** Sincronización milimétrica del estado de producción por lote, reduciendo la brecha de reportes manuales e incrementando la visibilidad de cuellos de botella de días a segundos.

---

### 2. App Móvil de Fuerza de Ventas con Facturación Electrónica (FEL) — Distribución Telecomunicaciones
* **Rol:** Mobile & Backend Engineer.
* **Stack:** `Ionic`, `C# .NET`, `SQL Server`, `Integración API Infile (FEL Guatemala)`.
* **Descripción:** Aplicación móvil nativa-híbrida para la gestión de rutas, preventa, cobros y liquidaciones en tiempo real para un distribuidor masivo de la red de Claro.
* **Reto Técnico & Acción:** El desafío crítico radicaba en garantizar la emisión legal y almacenamiento inmediato de facturas electrónicas en zonas rurales con conectividad intermitente. Desarrollé una arquitectura de sincronización offline con SQLite local en el dispositivo. Diseñé la lógica de integración mediante web services SOAP/REST con el certificador autorizado **Infile**, automatizando el firmado digital, validación del NIT y generación instantánea del archivo XML legal/PDF de la factura electrónica.
* **Impacto:** Automatización del 100% del ciclo de venta en ruta. Eliminación de reprocesos por ingreso manual de pedidos en oficina central y emisión inmediata de documentos tributarios en el punto de entrega.

---

### 3. Módulo Gubernamental de Gestión de Apostillas Electrónicas — Sector Público (MINEX)
* **Rol:** Consultor Senior y Desarrollador CRM.
* **Stack:** `Salesforce Service Cloud`, `Apex`, `Lightning Web Components (LWC)`, `Rest APIs`.
* **Descripción:** Módulo de automatización y gobernanza de documentos legales extranjeros para el Ministerio de Relaciones Exteriores, enfocado en el procesamiento de apostillas.
* **Reto Técnico & Acción:** Migración de flujos manuales burocráticos y aislados hacia un entorno CRM centralizado, seguro y auditable. Programé disparadores (Triggers) y clases controladoras asíncronas en Apex para validaciones de flujos de aprobación multinivel. Diseñé interfaces dinámicas con Lightning Web Components (LWC) para los validadores ministeriales y expuse Endpoints REST seguros para consumir servicios de validación de firmas digitales gubernamentales externas.
* **Impacto:** Reducción drástica del tiempo de respuesta ciudadano en trámites internacionales, garantizando auditoría del 100% sobre el ciclo de vida del documento apostillado.

---

### 4. Módulo Avanzado de Logística de Distribución — Cloud & CRM Enterprise
* **Rol:** Salesforce & Cloud Architecture Consultant.
* **Stack:** `Salesforce Lightning Experience`, `Apex Triggers`, `AWS S3 / Lambda`, `REST Web Services`.
* **Descripción:** Diseño e implementación de un módulo de logística end-to-end integrado nativamente en el CRM, enfocado en el control de flotas, asignación de transportistas, optimización de carga y trazabilidad de despachos.
* **Reto Técnico & Acción:** El principal reto técnico consistía en procesar grandes volúmenes de coordenadas geográficas y manifiestos de carga pesada sin superar los límites de gobierno de Salesforce (Governor Limits). Diseñé una arquitectura híbrida descargando el procesamiento pesado asíncrono hacia **AWS Lambda** y almacenando la documentación adjunta en **AWS S3**. Conecté ambos sistemas mediante web services seguros e implementé lógica de Apex asíncrono (Queueable/Future) para actualizar el CRM en tiempo real.
* **Impacto:** Visibilidad total de la cadena de suministro en el ecosistema comercial, reduciendo los tiempos de asignación de despachos y previniendo retrasos mediante un sistema automatizado de alertas de tránsito.

---

### 5. Sistema Centralizado de Cobranza y Planificador Interactivo
* **Rol:** Backend & Database Developer.
* **Stack:** `.NET Core Web API`, `SQL Server`, `Entity Framework Core`, `JavaScript (Tablero Kanban)`.
* **Descripción:** Aplicación financiera para la gestión de carteras de cobro pesadas, promesas de pago e historial crediticio, integrado con un planificador de asignación de asesores mediante un tablero dinámico interactivo.
* **Reto Técnico & Acción:** Manejo de bloqueos transaccionales (Deadlocks) en SQL Server debido al procesamiento masivo simultáneo de pagos y asignación de cuentas. Optimicé procedimientos almacenados complejos, implementé índices no agrupados estratégicos y apliqué aislamiento de transacciones de tipo `SNAPSHOT`. En el backend .NET, estructuré la API bajo los principios de Clean Architecture (Arquitectura Limpia) para independizar las reglas financieras del motor de base de datos.
* **Impacto:** Estabilización de la plataforma financiera con tiempos de respuesta menores a 200ms en la actualización de estados de cuenta masivos y carga del tablero dinámico en tiempo real.

---

### 6. Sistema Centralizado de Integraciones Core — Sector Farmacéutico
* **Rol:** Backend & Integration Engineer.
* **Stack:** `.NET 7/8`, `Java (Spring Boot)`, `PostgreSQL`, `REST/SOAP APIs`.
* **Descripción:** Middleware empresarial especializado en la unificación de canales y sistemas informáticos heterogéneos para una corporación farmacéutica líder en Guatemala. El sistema conecta los inventarios en puntos de venta, el inventario de laboratorios centrales y los proveedores logísticos.
* **Reto Técnico & Acción:** Garantizar la consistencia transaccional estricta en el despacho de medicamentos regulados e inventarios críticos distribuidos. Implementé un patrón de microservicios utilizando .NET y Java, comunicados de manera altamente segura a través de APIs REST con encriptación avanzada. Diseñé una estrategia de resiliencia en el backend mediante reintentos dinámicos y políticas de tolerancia a fallos sobre la base de datos PostgreSQL, blindando el sistema contra pérdidas de conectividad con proveedores externos.
* **Impacto:** Sincronización exacta de inventarios farmacéuticos a nivel nacional, mitigando por completo las órdenes duplicadas de medicamentos críticos y garantizando la trazabilidad auditable exigida por normativas sanitarias.

---

### 7. Inteligencia de Datos y Reportería de Manufactura — Industria del Plástico
* **Rol:** Analista de Datos & DB Developer.
* **Stack:** `Microsoft SQL Server`, `SQL Server Reporting Services (SSRS)`, `T-SQL Avanzado`.
* **Descripción:** Infraestructura corporativa de BI orientada al cruce de información entre los departamentos de Production, Finanzas, Logística y Ventas para una planta de extrusión e inyección de plásticos en Guatemala.
* **Reto Técnico & Acción:** Consolidación de datos heterogéneos provenientes de sistemas legados de pesaje de resina y mermas en planta. Diseñé consultas e ingenierías de datos complejas utilizando funciones analíticas de T-SQL, Pivottables dinámicos y optimización de vistas indexadas. Desarrollé una matriz visual de reportes interactivos parametrizados en SSRS automatizados para envío programado por correo a juntas directivas.
* **Impacto:** Democratización de datos en la compañía. Reducción de pérdidas por merma oculta de material mediante alertas analíticas visuales sobre los márgenes de producción diarios por lote.

---

## 📬 Contacto y Redes

* **LinkedIn:** [linkedin.com/in/tu-usuario](https://linkedin.com/in/tu-usuario)
* **GitHub:** [github.com/tu-usuario](https://github.com/tu-usuario)
* **Correo Electrónico:** [tu.correo@email.com](mailto:tu.correo@email.com)

---
*Desarrollado con enfoque en calidad, escalabilidad y arquitecturas robustas.*
