# 🧩 TalentLync 2.0  
Plataforma freemium que conecta **talentos** en búsqueda de oportunidades con **empresas** que necesitan contratar rápido y con confianza.  
Incluye módulos de **formación, empleos y publicidad segmentada**, integrando analítica, IA emocional y APIs externas.

---

## 🚀 Descripción General

**TalentLync** es una plataforma digital inclusiva y accesible diseñada para:
- Facilitar la conexión entre talentos y empresas.
- Optimizar procesos de contratación con **match inteligente y visibilidad segmentada**.
- Integrar formación y desarrollo profesional continuo.
- Permitir publicidad dirigida con planes flexibles.

---

## 🧠 Estructura General del Proyecto

### 🔹 Frontend
- **Frameworks:** React.js / Vue.js  
- **Estilos:** TailwindCSS  
- **Visualización:** Chart.js  
- **Diseño:** Responsive + accesibilidad WAI-ARIA  
- **Optimización:** Lazy loading, caching selectivo, y estructura modular.  

### 🔹 Backend
- **Tecnologías:** Node.js + Express / NestJS o Django  
- **Base de Datos:** PostgreSQL / MongoDB  
- **APIs Externas:**  
  - Google Meet API (entrevistas integradas)  
  - APIs de formación (Coursera, Udemy, Crehana, SENCE)  
- **Seguridad:** OWASP ZAP, cifrado JWT, control de roles.  
- **Hosting y Cloud:** AWS (EC2, RDS, S3)  

---

## 🧭 Flujo del Servicio

1. **Registro inicial** (Talento o Empresa)  
2. **Creación de perfil personalizado**  
3. **Acceso a la página de empleos**  
   - Página **central** del sistema (home principal).  
   - Filtros avanzados: ubicación, rubro, modalidad, experiencia, nivel salarial.  
   - Accesible tanto para **talentos** como **empresas premium**.  
4. **Apartado de formación**  
   - Cursos, magíster y microcertificaciones.  
   - Disponible para talentos y empresas premium.  
5. **Plan de suscripción o publicidad**  
   - Modelos freemium, premium y anunciadores.  
6. **Match predictivo y notificaciones automáticas.**

---

## 📂 Estructura de Archivos y Componentes

/src
├── components/
│ ├── JobBoard/
│ │ ├── JobFilters.jsx
│ │ ├── JobCard.jsx
│ │ └── JobList.jsx
│ ├── Training/
│ │ ├── CourseCard.jsx
│ │ └── CourseList.jsx
│ └── Shared/
│ ├── Navbar.jsx
│ └── Footer.jsx
├── pages/
│ ├── Home.jsx
│ ├── Jobs.jsx
│ ├── Training.jsx
│ └── CompanyDashboard.jsx
├── api/
│ ├── jobs.js
│ ├── users.js
│ └── auth.js
└── utils/
├── filters.js
├── apiClient.js
└── analytics.js

yaml
Copiar código

---

## 🧩 Evidencia y Avances

- **Página de empleos**: centralizada en el Home, con sistema de filtros activo y responsive.  
- **Apartado de formación**: ya integrado, visible desde la navegación principal.  
- **Pruebas funcionales**: revisión de endpoints, rendimiento, seguridad y SEO básico.  
- **Feedback real**: pruebas de aceptación con usuarios iniciales (empresas y talentos).  

---

## 💰 Precios Actualizados (Versión 2.0)

### 🧍‍♂️ Planes para Talentos

| Plan | Descripción | Precio Actual | Precio Sugerido Ajustado | Justificación |
|------|--------------|----------------|-----------------------------|----------------|
| **Free** | Perfil básico, postulaciones limitadas. | $0 | $0 | Captación de usuarios. |
| **Pro** | Perfil verificado, más visibilidad y feedback básico. | $3.990 | **$4.990 CLP/mes** | Mejora de margen sin perder accesibilidad. |
| **Ascenso** | Máxima visibilidad, prioridad en búsquedas, alertas personalizadas. | $5.990 | **$6.990 CLP/mes** | Aumenta valor percibido y posicionamiento premium. |

---

### 🏢 Planes para Empresas

| Plan | Descripción | Precio Actual | Precio Sugerido Ajustado | Justificación |
|------|--------------|----------------|-----------------------------|----------------|
| **Free** | Publicación limitada y sin acceso a match inteligente. | $0 | $0 | Estrategia de captación B2B. |
| **Pyme** | Hasta 5 vacantes, métricas básicas. | $15.990 | **$17.990 CLP/mes** | Mejora de rentabilidad manteniendo accesibilidad. |
| **Pro** | Filtros avanzados, match inteligente y reportes de contratación. | $25.990 | **$27.990 CLP/mes** | Ajuste competitivo frente a LinkedIn Recruiter. |
| **Premium Link** | Mayor visibilidad, entrevistas integradas y soporte prioritario. | $45.990 | **$49.990 CLP/mes** | Refuerza percepción de exclusividad. |

---

### 📢 Planes para Anunciadores

| Tipo | Subtipo | Precio Actual | Precio Sugerido | Justificación |
|------|----------|----------------|-----------------|----------------|
| **Individual** | Básico | $9.900 | **$10.990 CLP** | Margen de rentabilidad del 15 %. |
| | Premium | $17.900 | **$19.900 CLP** | Mantiene proporción respecto al básico. |
| | Destacado | $29.900 | **$32.900 CLP** | Incentiva la migración a planes mensuales. |
| **Mensual** | Starter Ads | $59.900 | **$64.900 CLP/mes** | Mejora margen sin perder atractivo. |
| | Pro Ads | $119.900 | **$129.900 CLP/mes** | Cubre gastos técnicos de analítica y soporte. |
| | Premium Ads | $229.900 | **$239.900 CLP/mes** | Mantiene coherencia premium con la propuesta. |

---

## 📈 Proyección a Corto Plazo

| Mes | Ingresos Estimados | Objetivo |
|-----|--------------------|-----------|
| **1** | ≈ $175.000 CLP | Captación inicial y validación de MVP. |
| **2** | ≈ $389.000 CLP | Activación de planes pagos y feedback. |
| **3** | ≈ $828.000 CLP | Consolidación del modelo freemium + premium. |

---

## 🛡️ Control de Calidad y Auditoría

**Checklist de Revisión Técnica:**
- [x] Revisión manual de código y funcionamiento  
- [x] Rendimiento y optimización general  
- [x] UX/UI y comportamiento del usuario  
- [x] Auditoría técnica y SEO  
- [x] Pruebas y depuración de APIs  
- [x] Seguridad básica y control de accesos  
- [x] Experiencia de uso móvil  

---

## 📚 Licencia
Proyecto desarrollado bajo licencia **MIT**.  
Desarrollo original por **TalentLync Labs** — 2025.

---

## 📞 Contacto
**Email:** contacto@talentlync.com  
**Sitio Web:** 
