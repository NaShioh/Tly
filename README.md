# 🌐 TalentLync — “Tu talento, nuestro enlace”

**TalentLync** es una plataforma digital inclusiva que conecta **personas en busca de empleo (talentos)** con **empresas y anunciadores**, de forma **rápida, moderna y segura**.  
Su propósito es facilitar la **contratación, formación y promoción profesional**, creando un entorno accesible y colaborativo.

---

## 📖 Índice

1. [Descripción general](#-descripción-general)
2. [Aspectos técnicos principales](#-aspectos-técnicos-principales)
3. [Funciones principales](#-funciones-principales)
4. [Diseño y experiencia](#-diseño-y-experiencia)
5. [Flujos de usuarios](#-flujos-de-usuarios)
   - [Talento](#talento)
   - [Empresa](#empresa)
   - [Anunciante](#anunciante)
6. [Despliegue y entorno](#-despliegue-y-entorno)
7. [Evidencia y repositorio](#-evidencia-y-repositorio)
8. [Control de versiones](#-control-de-versiones)
9. [Licencia](#-licencia)
10. [Créditos y contacto](#-créditos-y-contacto)

---

## 🧠 Descripción general

**TalentLync** es una plataforma web tipo **freemium**, donde los usuarios pueden:
- Postular a empleos y cursos (Talentos)
- Publicar vacantes y contratar (Empresas)
- Promocionar servicios o formaciones (Anunciantes)

Todo en un entorno **100% en español**, con una interfaz accesible, adaptable y potenciada por herramientas modernas del ecosistema web.

> **Slogan:** “Tu talento, nuestro enlace”

---

## ⚙️ Aspectos técnicos principales

| Elemento | Descripción |
|-----------|--------------|
| **Tipo de sistema** | Plataforma Web (no aplicación móvil) |
| **Lenguaje principal** | Español |
| **Frontend** | React + Vite + TypeScript |
| **Estilos** | Tailwind CSS (degradados azul y celeste, tipografía sans-serif) |
| **Base de datos** | Bolt Database (basada en Supabase/PostgreSQL) |
| **Autenticación** | Google Sign-In (inicio de sesión con Google) |
| **Seguridad** | Row Level Security (RLS) activado |
| **Entorno de desarrollo** | Bolt.new, Cursor, Visual Studio Code |
| **Despliegue recomendado** | Frontend: Vercel o Netlify / Backend: Supabase |

---

## 💼 Funciones principales

### 👤 Talentos
- Crear perfil profesional y completar progreso (0–100%)
- Subir CV, agregar habilidades y certificaciones
- Postular a empleos y cursos
- Seguir postulaciones y recibir retroalimentación
- Planes disponibles:
  - **Free**  
  - **Pro:** $3.990 CLP/mes  
  - **Ascenso:** $5.990 CLP/mes  

### 🏢 Empresas
- Registro empresarial con validación
- Crear y gestionar vacantes
- Revisar postulaciones y contactar talentos
- Métricas y reportes descargables
- Planes disponibles:
  - **Free**
  - **Pyme:** $15.990 CLP/mes  
  - **Pro:** $25.990 CLP/mes  
  - **Premium Link:** $45.990 CLP/mes  

### 📢 Anunciadores
- Crear anuncios individuales o suscribirse a planes mensuales  
- Integración de anuncios de manera **orgánica** y **no invasiva** dentro del ecosistema TalentLync  
- Rentabilidad promedio del 15% mediante estrategias de incentivo  

#### Anuncios individuales
| Tipo | Precio | Duración | Ubicación |
|------|---------|-----------|------------|
| **Básico** | $9.900 | 7 días | Feed de vacantes |
| **Premium** | $17.900 | 14 días | “Servicio recomendado” en perfiles |
| **Destacado** | $29.900 | 30 días | Dashboard principal |

#### Planes mensuales
| Plan | Precio | Beneficios principales |
|------|---------|------------------------|
| **Starter Ads** | $59.900 CLP/mes | 3 anuncios destacados, segmentación básica, reporte simple |
| **Pro Ads** | $119.900 CLP/mes | 8 anuncios, segmentación avanzada, logo en “Aliados formativos” |
| **Premium Ads** | $229.900 CLP/mes | Anuncios ilimitados, IA de afinidad, soporte dedicado |

---

## 🎨 Diseño y experiencia

- **Colores principales:** Azul `#2563eb`, celeste y blanco  
- **Tipografía:** Sans-serif moderna  
- **Diseño:** Limpio, responsivo, y adaptado a móvil y escritorio  
- **Animaciones:** Suaves y fluidas  
- **Estructura general:**
  - Home con secciones de **Empleos** (central) y **Formación**
  - Dashboards específicos por tipo de usuario
  - Panel administrativo

---

## 🔁 Flujos de usuarios

### 🧩 Talento

1. **Registro e inicio de sesión**
   - Google o correo electrónico  
2. **Perfil básico y avanzado**
   - Experiencia, habilidades, CV, idiomas, logros  
3. **Exploración**
   - Feed de empleos y cursos con filtros por área, modalidad y ubicación  
4. **Postulación**
   - Sistema de seguimiento y retroalimentación  
5. **Formación**
   - Acceso a microcursos (Coursera, SENCE, Crehana)

---

### 🧩 Empresa

1. **Registro y validación de datos**
   - Razón social, rubro, correo corporativo  
2. **Publicación de vacantes**
   - Cargo, requisitos, tipo de contrato, modalidad  
3. **Gestión**
   - Filtrado de postulaciones y entrevistas  
4. **Analítica**
   - Métricas e informes descargables (PDF o Excel)

---

### 🧩 Anunciante

1. **Registro simple o empresarial**  
2. **Creación de anuncio**
   - Producto, servicio o curso  
3. **Selección de plan**
   - Individual o mensual  
4. **Publicación y métricas**
   - Vistas, clics, conversiones  

---

## 🚀 Despliegue y entorno

**Frontend**
- Deploy recomendado: [Vercel](https://vercel.com) o [Netlify](https://www.netlify.com/)
- Comando de desarrollo:
  ```bash
  npm install
  npm run dev
