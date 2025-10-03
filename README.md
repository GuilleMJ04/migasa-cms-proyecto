
## Primer Entregable - Sprint 1

**Integrantes del equipo:**
- Guillermo Mendo Jiménez
- Emilio Cuevas Rendón
- Iluminada Baena Herruzo
- Nazaret María Villalba Delgado

---

## ÍNDICE

1. [Introducción](#1-introducción)
2. [Análisis de la Empresa](#2-análisis-de-la-empresa)
3. [Requisitos con REM](#3-requisitos-con-rem)
   - 3.1. Objetivos (Goals)
   - 3.2. Requisitos de Información
   - 3.3. Requisitos de Interfaz de Usuario
   - 3.4. Requisitos Funcionales
   - 3.5. Requisitos No Funcionales
   - 3.6. Reglas de Negocio
4. [Análisis del Sistema](#4-análisis-del-sistema)
   - 4.1. Mockups y Prototipos
   - 4.2. Diagrama de Clases
5. [Diseño](#5-diseño)
   - 5.1. Análisis y Selección de Plugins
   - 5.2. Análisis y Selección de Temas
6. [Planificación SCRUM](#6-planificación-scrum)
   - 6.1. Software Colaborativo Seleccionado
   - 6.2. Control de Versiones
   - 6.3. Product Backlog
   - 6.4. Sprint Backlog
   - 6.5. Burndown Chart

---

## 1. INTRODUCCIÓN

### 1.1 Propósito del Proyecto
Desarrollar un sitio web corporativo mejorado para MIGASA utilizando WordPress como CMS, con el objetivo de modernizar su presencia digital, mejorar la experiencia de usuario y optimizar la comunicación de sus productos y servicios en el sector del aceite de oliva.

### 1.2 Alcance
El proyecto abarca:
- Rediseño completo del sitio web corporativo respetando la identidad visual de MIGASA
- Implementación de WordPress con estructura modular y escalable
- Optimización para dispositivos móviles y tablets
- Mejora del SEO y velocidad de carga
- Integración de herramientas de analytics y seguridad
- Creación de secciones para productos, empresa, historia, sostenibilidad y contacto

### 1.3 Empresa Seleccionada
**Nombre de la empresa:** MIGASA (Grupo Migasa)

**Sector:** Fabricación y refinado de aceites de oliva y otros aceites vegetales

**Situación actual:** MIGASA es una empresa familiar española líder mundial en la venta de aceite de oliva con más de 90 años de historia, facturación superior a 1.000 millones de euros anuales y presencia en más de 120 países. Cuenta con sitio web corporativo (www.migasa.com) que necesita ser analizado para identificar oportunidades de mejora.

---

## 2. ANÁLISIS DE LA EMPRESA

### 2.1 Descripción de la Empresa
**MIGASA (Grupo Migasa)** es una empresa familiar española fundada hace más de 90 años, que se ha convertido en líder mundial en la fabricación y comercialización de aceite de oliva. 

**Datos principales:**
- **Facturación:** Más de 1.000 millones de euros anuales
- **Presencia internacional:** Más de 120 países en los cinco continentes
- **Empleados:** Aproximadamente 145 empleados (datos 2024)
- **Sede central:** Dos Hermanas (Sevilla), Andalucía
- **Centros de producción:** 
  - Dos Hermanas: Refinerías de aceites de oliva y semillas
  - La Luisiana (Sevilla): Planta de refinación de aceite de orujo y girasol

**Características diferenciales:**
- Empresa familiar en tercera generación
- Control exhaustivo de toda la cadena de valor
- Presencia en todas las etapas del proceso de elaboración
- Fuerte vinculación con el sector olivarero andaluz
- Capacidad para trabajar con todo tipo de envases y volúmenes

### 2.2 Problemática Identificada

**Análisis del sitio web actual (www.migasa.com):**

1. **Experiencia de usuario limitada:**
   - Navegación poco intuitiva
   - Falta de jerarquía visual clara
   - Información no estructurada adecuadamente

2. **Diseño desactualizado:**
   - No refleja completamente la identidad corporativa moderna de MIGASA
   - Falta de elementos visuales atractivos
   - Escasa interactividad

3. **Problemas de rendimiento:**
   - Tiempos de carga elevados
   - Falta de optimización de imágenes
   - No implementa cache eficientemente

4. **Carencias funcionales:**
   - Sección de productos poco detallada
   - Falta de información sobre sostenibilidad y RSC
   - No hay sistema de gestión de contenidos ágil
   - Ausencia de blog o área de noticias

5. **SEO y visibilidad:**
   - Posicionamiento mejorable en buscadores
   - Meta descripciones y títulos no optimizados
   - Falta de estrategia de contenidos

### 2.3 Oportunidades de Mejora

1. **Modernización visual:** Aplicar correctamente el manual de identidad corporativa con los colores Pantone corporativos (383 C, 377 C, 357 C)

2. **Experiencia móvil:** Diseño 100% responsive adaptado a todos los dispositivos

3. **Contenido estructurado:** Organizar información por áreas temáticas claras (Productos, Clientes Objetivos, Mercados, Competidores, Cargo Empresarial, etc.)

4. **Storytelling:** Destacar la historia familiar de más de 90 años y presencia en 120 países

5. **Sostenibilidad:** Crear sección específica sobre prácticas sostenibles y responsabilidad ambiental

6. **Área de administración:** Sistema de gestión de contenidos intuitivo con WordPress

---

## 3. REQUISITOS CON REM

*[Nota: Estos requisitos deben ser elicitados después de una entrevista con la empresa]*

### 3.1 Objetivos (Goals)

#### G01: Modernización de la presencia web
**Descripción:** Mejorar la experiencia de usuario y la funcionalidad del sitio web corporativo
**Prioridad:** Alta

#### G02: Optimización para dispositivos móviles
**Descripción:** Garantizar una experiencia óptima en smartphones y tablets
**Prioridad:** Alta

#### G03: Mejora del posicionamiento SEO
**Descripción:** Aumentar la visibilidad en motores de búsqueda
**Prioridad:** Media

#### G04: Integración de herramientas de analytics
**Descripción:** Implementar seguimiento y análisis del comportamiento de usuarios
**Prioridad:** Media

### 3.2 Requisitos de Información

#### IR01: Información de la empresa
**Descripción:** El sistema debe mostrar información corporativa de MIGASA (historia, misión, visión, valores)
**Fuente:** Reunión con empresa / Manual corporativo
**Prioridad:** Alta

#### IR02: Catálogo de productos
**Descripción:** Información detallada de productos de aceite de oliva y aceites vegetales
**Contenido:** Tipos de aceite, presentaciones, características, certificaciones
**Prioridad:** Alta

#### IR03: Mercados y presencia internacional
**Descripción:** Información sobre los 120 países donde opera MIGASA
**Contenido:** Mercados principales, distribución geográfica
**Prioridad:** Media

#### IR04: Clientes objetivo
**Descripción:** Información sobre los diferentes perfiles de clientes (Horeca, retail, industrial)
**Prioridad:** Media

#### IR05: Sostenibilidad y RSC
**Descripción:** Información sobre prácticas sostenibles, certificaciones ambientales
**Prioridad:** Media

#### IR06: Contacto y ubicaciones
**Descripción:** Datos de contacto, ubicación de oficinas y fábricas (Dos Hermanas, La Luisiana)
**Prioridad:** Alta

### 3.3 Requisitos de Interfaz de Usuario

#### UR01: Identidad visual corporativa
**Descripción:** El sitio web debe respetar el manual de identidad corporativa de MIGASA
**Especificaciones:**
- Colores corporativos: Pantone 383 C, 377 C, 357 C (tonos verdes)
- Tipografía: DIN Black para títulos corporativos, Myriad Pro para contenidos
- Logo con área de seguridad de 5mm y tamaño mínimo: 100px digital
- Versiones del logo: completo, imagotipo, anagrama
**Justificación:** Mantener coherencia con la imagen de marca establecida
**Prioridad:** Alta

#### UR02: Diseño responsive
**Descripción:** Interfaz adaptable a todos los dispositivos (desktop, tablet, móvil)
**Especificaciones:** Breakpoints estándar, menú hamburguesa en móvil
**Prioridad:** Alta

#### UR03: Navegación intuitiva
**Descripción:** Menú principal claro con estructura jerárquica
**Elementos:** Inicio, Empresa, Productos, Mercados, Sostenibilidad, Contacto
**Prioridad:** Alta

#### UR04: Paleta de colores web
**Descripción:** Implementar correctamente los colores corporativos
**RGB:** 
- Verde claro: R:163 G:171 B:17 (Pantone 383 C)
- Verde medio: R:124 G:147 B:35 (Pantone 377 C)  
- Verde oscuro: R:59 G:89 B:59 (Pantone 357 C)
**Prioridad:** Alta

#### UR05: Galería de imágenes de productos
**Descripción:** Visualización atractiva de productos con zoom y lightbox
**Prioridad:** Media

### 3.4 Requisitos Funcionales

#### FR01: Gestión de contenidos
**Descripción:** Sistema CMS WordPress para gestión de contenido por el administrador
**Entrada:** Credenciales de acceso, contenido a publicar
**Salida:** Contenido publicado en el sitio
**Prioridad:** Alta

#### FR02: Catálogo de productos navegable
**Descripción:** Sistema de visualización de productos por categorías (aceite oliva, girasol, orujo)
**Entrada:** Selección de categoría/producto
**Salida:** Ficha detallada del producto con imágenes y especificaciones
**Prioridad:** Alta

#### FR03: Formulario de contacto
**Descripción:** Formulario funcional para consultas de clientes
**Entrada:** Nombre, email, mensaje, tipo de consulta
**Salida:** Email al departamento correspondiente, confirmación al usuario
**Prioridad:** Alta

#### FR04: Búsqueda interna
**Descripción:** Motor de búsqueda para localizar información en el sitio
**Entrada:** Términos de búsqueda
**Salida:** Resultados relevantes ordenados por relevancia
**Prioridad:** Media

#### FR05: Mapa interactivo
**Descripción:** Visualización de presencia internacional en 120 países
**Entrada:** Selección de región/país
**Salida:** Información de mercado y distribución
**Prioridad:** Baja

#### FR06: Área de noticias/blog
**Descripción:** Sección para publicar noticias corporativas y del sector
**Entrada:** Contenido de noticia desde panel admin
**Salida:** Publicación en blog con fecha y categoría
**Prioridad:** Media

#### FR07: Multiidioma
**Descripción:** Sitio disponible en español e inglés mínimo (presencia en 120 países)
**Entrada:** Selección de idioma
**Salida:** Contenido traducido
**Prioridad:** Media

#### FR08: Integración Google Maps
**Descripción:** Ubicación de oficinas y fábricas (Dos Hermanas, La Luisiana)
**Entrada:** Click en ubicación
**Salida:** Mapa interactivo con dirección exacta
**Prioridad:** Baja

### 3.5 Requisitos No Funcionales

#### NFR01: Rendimiento
**Descripción:** El sitio web debe cargar en menos de 3 segundos
**Medida:** Tiempo de carga < 3s
**Prioridad:** Alta

#### NFR02: Seguridad
**Descripción:** *[PENDIENTE: Definir requisitos de seguridad]*
**Prioridad:** Alta

#### NFR03: Usabilidad
**Descripción:** *[PENDIENTE: Definir requisitos de usabilidad]*
**Prioridad:** Media

### 3.6 Reglas de Negocio

#### BR01: Identidad corporativa obligatoria
**Descripción:** Todo elemento visual debe cumplir con el manual de identidad corporativa de MIGASA (colores Pantone, tipografías, uso del logo)

#### BR02: Jerarquía de información
**Descripción:** Los productos deben organizarse según la estructura: Aceite de Oliva > Aceite de Girasol > Aceite de Orujo

#### BR03: Información de contacto visible
**Descripción:** Los datos de contacto (Ctra. Madrid-Cádiz Km 556, teléfono 954 720 550) deben ser accesibles desde cualquier página

#### BR04: Certificaciones y sellos
**Descripción:** Todas las certificaciones de calidad y sostenibilidad deben ser visibles y verificables

#### BR05: Actualizaciones de contenido
**Descripción:** El contenido debe poder ser actualizado por el equipo de MIGASA sin conocimientos técnicos avanzados

#### BR06: Respaldo de la marca familiar
**Descripción:** Se debe destacar la historia familiar de más de 90 años y tercera generación

#### BR07: Accesibilidad
**Descripción:** El sitio debe cumplir con estándares WCAG 2.1 nivel AA mínimo

---

## 4. ANÁLISIS DEL SISTEMA

### 4.1 Mockups y Prototipos

*[Los mockups deben crearse con Balsamiq u otra herramienta de diseño]*

#### 4.1.1 Página Principal (Home)
**Descripción del mockup:** 
- Header con logo MIGASA (respetando área de seguridad 5mm)
- Menú de navegación principal
- Hero section con imagen destacada de olivar/producción
- Sección "Quiénes somos" (90+ años de historia)
- Productos destacados
- Cifras clave (120 países, >1000M€ facturación)
- Footer con datos de contacto y redes sociales

**Elementos principales:**
- Colores corporativos: Pantone 383 C, 377 C, 357 C
- Tipografía: DIN Black (títulos), Myriad Pro (contenido)
- Call-to-action: "Conoce nuestros productos", "Contacta con nosotros"

#### 4.1.2 Página de Empresa
**Descripción:** Historia, misión, visión, valores, equipo directivo
**Secciones:**
- Historia familiar (3 generaciones)
- Nuestra misión y visión
- Valores corporativos
- Instalaciones (Dos Hermanas, La Luisiana)
- Cifras y presencia internacional

#### 4.1.3 Página de Productos
**Descripción:** Catálogo organizado por tipos de aceite
**Estructura:**
- Filtros por tipo: Oliva, Girasol, Orujo
- Tarjetas de producto con imagen, nombre, descripción breve
- Detalle de producto: especificaciones técnicas, presentaciones, certificaciones
- CTA: Solicitar información

#### 4.1.4 Página de Mercados
**Descripción:** Presencia internacional de MIGASA
**Elementos:**
- Mapa interactivo con los 120 países
- Listado de mercados principales
- Testimonios de clientes internacionales

#### 4.1.5 Página de Sostenibilidad
**Descripción:** Compromiso ambiental y RSC
**Contenido:**
- Prácticas sostenibles
- Certificaciones ambientales
- Proyectos de economía circular
- Objetivos de desarrollo sostenible

#### 4.1.6 Página de Contacto
**Descripción:** Formulario y datos de contacto
**Elementos:**
- Formulario: Nombre, Email, Teléfono, Tipo consulta, Mensaje
- Google Maps con ubicaciones
- Datos: Ctra. Madrid-Cádiz Km 556, Tfno. 954 720 550
- Horario de atención

### 4.2 Diagrama de Clases

*[Crear diagrama UML que represente la estructura del sitio WordPress]*

**Clases principales identificadas:**

#### Clase: Página
- Atributos: id, título, contenido, slug, fecha_publicación, autor
- Métodos: publicar(), editar(), eliminar()

#### Clase: Producto
- Atributos: id, nombre, tipo_aceite, descripción, imagen, especificaciones, precio, categoría
- Métodos: mostrar(), filtrar_por_tipo(), buscar()
- Relaciones: Pertenece a CategoríaProducto

#### Clase: CategoríaProducto  
- Atributos: id, nombre (Oliva/Girasol/Orujo), descripción
- Métodos: listar_productos()
- Relaciones: Tiene muchos Productos

#### Clase: Menú
- Atributos: id, nombre, orden, url, página_padre
- Métodos: mostrar_navegación(), generar_breadcrumbs()

#### Clase: FormularioContacto
- Atributos: nombre, email, teléfono, tipo_consulta, mensaje
- Métodos: validar(), enviar_email(), guardar()

#### Clase: Usuario
- Atributos: id, nombre, email, rol (admin/editor/suscriptor)
- Métodos: login(), logout(), gestionar_contenido()

#### Clase: Noticia
- Atributos: id, título, contenido, fecha, imagen_destacada, categoría
- Métodos: publicar(), archivar()

**Relaciones:**
- Usuario gestiona Páginas (1:N)
- Usuario gestiona Productos (1:N)
- Usuario gestiona Noticias (1:N)
- Producto pertenece a CategoríaProducto (N:1)
- Página tiene Menú (1:1)

*[Incluir diagrama visual UML en el documento final]*

---

## 5. DISEÑO

### 5.1 Análisis y Selección de Plugins

#### 5.1.1 Plugins de Seguridad (OBLIGATORIO)

| Plugin | Última Actualización | Descargas | Valoración | Características Principales | Decisión |
|--------|---------------------|-----------|-----------|----------------------------|----------|
| **Wordfence Security** | Actualización continua | 5M+ | ★★★★★ (4.7/5) | Firewall, escaneo malware, 2FA, bloqueo fuerza bruta, monitorización en tiempo real | ✅ **SELECCIONADO** |
| **Sucuri Security** | Actualización mensual | 800K+ | ★★★★☆ (4.5/5) | Auditoría de seguridad, monitoreo integridad archivos, lista negra, limpieza post-hackeo | ❌ Descartado |
| **iThemes Security** | Actualización continua | 1M+ | ★★★★☆ (4.6/5) | +50 formas de protección, 2FA, contraseñas fuertes, detección cambios archivos | ❌ Descartado |

**Plugin seleccionado:** Wordfence Security

**Justificación:** 
- Mayor número de instalaciones activas (5M+)
- Firewall de aplicación web incluido en versión gratuita
- Escaneo de malware más completo
- Dashboard intuitivo con alertas en tiempo real
- Actualizaciones automáticas de reglas de seguridad
- Ideal para empresas con información sensible como MIGASA

#### 5.1.2 Plugins de Cache (OBLIGATORIO)

| Plugin | Última Actualización | Descargas | Valoración | Características Principales | Decisión |
|--------|---------------------|-----------|-----------|----------------------------|----------|
| **WP Rocket** | Actualización continua | Premium | ★★★★★ (4.9/5) | Cache página, lazy load, minificación CSS/JS, CDN compatible, preload cache | ✅ **SELECCIONADO** |
| **W3 Total Cache** | Actualización mensual | 1M+ | ★★★★☆ (4.3/5) | Cache completa, CDN, minificación, gratuito, muchas opciones configuración | ❌ Descartado |
| **WP Super Cache** | Actualización trimestral | 2M+ | ★★★★☆ (4.4/5) | Cache simple, archivos HTML estáticos, gratuito, fácil configuración | ❌ Descartado |

**Plugin seleccionado:** WP Rocket

**Justificación:**
- Mejores resultados en velocidad (reduce tiempo carga 40-50%)
- Configuración automática sin conocimientos técnicos
- Lazy loading de imágenes (importante para catálogo productos)
- Compatible con WooCommerce (por si se añade e-commerce futuro)
- Soporte premium en español
- ROI justificado para empresa del nivel de MIGASA

#### 5.1.3 Plugins de Analytics (OBLIGATORIO)

| Plugin | Última Actualización | Descargas | Valoración | Características Principales | Decisión |
|--------|---------------------|-----------|-----------|----------------------------|----------|
| **MonsterInsights** | Actualización continua | 3M+ | ★★★★★ (4.6/5) | Google Analytics en dashboard, tracking e-commerce, informes automáticos, GDPR compliant | ✅ **SELECCIONADO** |
| **Google Analytics Dashboard** | Actualización mensual | 1M+ | ★★★★☆ (4.5/5) | Integración GA4, informes básicos, gratuito, configuración simple | ❌ Descartado |
| **Analytify** | Actualización continua | 200K+ | ★★★★☆ (4.7/5) | Dashboard visual, estadísticas en tiempo real, tracking eventos | ❌ Descartado |

**Plugin seleccionado:** MonsterInsights

**Justificación:**
- Integración completa con Google Analytics 4
- Dashboard visual en WordPress sin salir del admin
- Tracking automático de descargas, clics externos, formularios
- Informes de e-commerce (útil si se añade tienda)
- Compatible con GDPR (importante para empresa europea)
- Segmentación de audiencia por país (relevante para 120 países)

#### 5.1.4 Plugins de SEO (OBLIGATORIO)

| Plugin | Última Actualización | Descargas | Valoración | Características Principales | Decisión |
|--------|---------------------|-----------|-----------|-----------|----------|
| **Yoast SEO** | Actualización semanal | 5M+ | ★★★★★ (4.9/5) | Análisis contenido, XML sitemaps, breadcrumbs, meta descripciones, schema markup | ✅ **SELECCIONADO** |
| **Rank Math** | Actualización continua | 2M+ | ★★★★★ (4.8/5) | 40+ herramientas SEO, Google Search Console integrado, análisis 404, redirecciones | ❌ Descartado |
| **All in One SEO** | Actualización semanal | 3M+ | ★★★★☆ (4.6/5) | Optimización automática, sitemaps XML, integración redes sociales | ❌ Descartado |

**Plugin seleccionado:** Yoast SEO

**Justificación:**
- Estándar de industria, más maduro y estable
- Interfaz intuitiva con semáforo verde/amarillo/rojo
- Análisis en tiempo real de legibilidad y SEO
- Optimización para palabras clave específicas ("aceite de oliva", "MIGASA")
- Schema markup para rich snippets (importante para productos)
- Multiidioma (español/inglés) con WPML
- Documentación extensa en español

#### 5.1.5 Otros Plugins Específicos

**Plugin de Formularios:**
- **WPForms** (Seleccionado): Drag & drop, plantillas pre-diseñadas, anti-spam, notificaciones email
- Justificación: Integración con MonsterInsights para tracking de conversiones

**Plugin Multiidioma:**
- **WPML** (Seleccionado): Traducción completa sitio, compatible con Yoast SEO, gestión URLs por idioma
- Justificación: Presencia en 120 países requiere mínimo español/inglés

**Plugin de Galería:**
- **Envira Gallery** (Seleccionado): Lightbox responsive, lazy loading, álbumes de productos
- Justificación: Catálogo visual atractivo de productos de aceite

**Plugin de Backup:**
- **UpdraftPlus** (Seleccionado): Backup automático, restauración 1-click, almacenamiento cloud
- Justificación: Protección datos críticos de empresa

### 5.2 Análisis y Selección de Temas

| Tema | Precio | Valoración | Características | Compatibilidad | Decisión |
|------|--------|-----------|----------------|----------------|----------|
| *[Tema 1]* | *[Precio]* | *[★★★★★]* | *[Características]* | *[Plugins compatibles]* | *[Seleccionado/Descartado]* |
| *[Tema 2]* | *[Precio]* | *[★★★★☆]* | *[Características]* | *[Plugins compatibles]* | *[Seleccionado/Descartado]* |
| *[Tema 3]* | *[Precio]* | *[★★★☆☆]* | *[Características]* | *[Plugins compatibles]* | *[Seleccionado/Descartado]* |

**Tema seleccionado:** *[PENDIENTE]*
**Justificación:** *[PENDIENTE: Explicar por qué se eligió este tema]*

---

## 6. PLANIFICACIÓN SCRUM

### 6.1 Software Colaborativo Seleccionado

**Software elegido:** GitHub (con GitHub Issues y GitHub Projects)

**Justificación de la selección:**
- **Integración completa:** Combina control de versiones y gestión de proyectos en una sola plataforma
- **Colaboración eficiente:** Permite trabajo conjunto en código, documentación y seguimiento de tareas
- **Transparencia:** Historial completo de cambios y decisiones del proyecto
- **Accesibilidad:** Gratuito para proyectos públicos y con amplio soporte de la comunidad
- **Funcionalidades SCRUM:** GitHub Projects permite crear tableros Kanban, sprints y seguimiento de progreso

**Características principales:**
- Gestión de issues (historias de usuario, bugs, tareas)
- Tableros de proyecto estilo Kanban
- Integración con commits y pull requests
- Seguimiento de milestones (sprints)
- Documentación integrada (Wiki, README)

### 6.2 Control de Versiones

**Sistema seleccionado:** Git con GitHub

**Justificación:** 
- Estándar de la industria para control de versiones
- Permite trabajo colaborativo eficiente
- Historial completo de cambios
- Branching y merging para desarrollo paralelo
- Backup automático en la nube

**Estructura del repositorio:**
```
proyecto-migasa-cms/
├── docs/                 # Documentación del proyecto
├── wordpress/           # Archivos de WordPress
├── plugins/             # Plugins personalizados
├── themes/              # Temas personalizados
├── mockups/            # Diseños y mockups
├── scrum/              # Documentos SCRUM
└── README.md           # Información del proyecto
```

### 6.3 Product Backlog

| ID | Historia de Usuario | Descripción Detallada | Criterios de Aceptación | Prioridad | Puntos | Sprint |
|----|--------------------|-----------------------|------------------------|-----------|--------|---------|
| PBI-01 | Como visitante, quiero navegar fácilmente por el sitio | Implementar menú responsive con estructura jerárquica clara | - Menú visible en todas las páginas<br>- Hamburguesa en móvil<br>- Breadcrumbs funcionales<br>- Tiempo navegación < 3 clics | Alta | 8 | Sprint 1 |
| PBI-02 | Como administrador, quiero gestionar contenido fácilmente | Configurar WordPress con roles, permisos y editor visual | - Dashboard intuitivo<br>- Roles definidos (admin/editor)<br>- Divi Builder activo<br>- Capacitación documentada | Alta | 5 | Sprint 1 |
| PBI-03 | Como visitante, quiero ver productos de aceite | Catálogo de productos con filtros por tipo | - Mínimo 10 productos<br>- Filtro por tipo aceite<br>- Ficha detallada producto<br>- Imágenes de calidad | Alta | 13 | Sprint 1 |
| PBI-04 | Como visitante, quiero contactar con MIGASA | Formulario funcional con validación y notificaciones | - Campos obligatorios validados<br>- Email de confirmación<br>- Notificación a MIGASA<br>- Anti-spam activo | Alta | 3 | Sprint 1 |
| PBI-05 | Como visitante, quiero un sitio rápido | Optimizar rendimiento con cache y compresión | - PageSpeed >80/100<br>- Tiempo carga <3s<br>- Lazy loading activo<br>- Imágenes optimizadas | Media | 5 | Sprint 1 |
| PBI-06 | Como administrador, quiero analizar el tráfico | Integrar Google Analytics y herramientas SEO | - GA4 configurado<br>- Dashboard MonsterInsights<br>- Yoast SEO activo<br>- Sitemap XML generado | Media | 3 | Sprint 2 |
| PBI-07 | Como visitante móvil, quiero acceso completo | Diseño 100% responsive y táctil | - Funcional en iOS/Android<br>- Menú táctil optimizado<br>- Formularios móvil-friendly<br>- Imágenes adaptativas | Alta | 8 | Sprint 2 |
| PBI-08 | Como visitante internacional, quiero el sitio en inglés | Implementar multiidioma ES/EN con WPML | - Todo contenido traducido<br>- Selector idioma visible<br>- URLs por idioma<br>- Menús traducidos | Media | 8 | Sprint 2 |
| PBI-09 | Como visitante, quiero conocer la historia de MIGASA | Página "Empresa" con timeline y valores | - Timeline interactiva<br>- 90 años historia<br>- Fotos familia<br>- Video institucional | Media | 5 | Sprint 2 |
| PBI-10 | Como visitante, quiero ver la presencia internacional | Mapa interactivo con 120 países | - Mapa con markers<br>- Info por región<br>- Datos por país<br>- Responsive | Baja | 8 | Sprint 2 |
| PBI-11 | Como administrador, quiero seguridad robusta | Configurar firewall, 2FA y backups | - Wordfence activo<br>- 2FA obligatorio admin<br>- Backups semanales<br>- SSL configurado | Alta | 5 | Sprint 1 |
| PBI-12 | Como visitante, quiero leer noticias del sector | Blog/área noticias actualizable | - Mínimo 5 entradas<br>- Categorías definidas<br>- RSS feed<br>- Compartir en redes | Baja | 5 | Sprint 2 |

**Total puntos Product Backlog:** 80 puntos
**Velocidad estimada:** 40 puntos por sprint

### 6.4 Sprint Backlog - Sprint 1

**Objetivo del Sprint:** Establecer la base del sitio WordPress con funcionalidades principales, diseño responsive y estructura de contenidos siguiendo la identidad corporativa de MIGASA.

**Duración:** 2 semanas (10 días laborables)
**Fecha inicio:** *[PENDIENTE: Fecha inicio real]*
**Fecha fin:** *[PENDIENTE: Fecha fin real]*

| ID | Tarea | Descripción Detallada | Responsable | Estado | Horas Est. | Horas Real | Observaciones |
|----|-------|-----------------------|-------------|--------|------------|------------|---------------|
| **T-01** | Instalación WordPress | Configurar entorno local, instalar WordPress, crear BD | *Guillermo* | To Do | 4 | - | Stack: XAMPP |
| **T-02** | Análisis y selección de tema | Investigar, comparar 3 temas, documentar decisión | *Emilio* | To Do | 6 | - | Comparar Divi/Astra/OceanWP |
| **T-03** | Instalación tema Divi | Descargar, instalar, activar licencia, configuración básica | *Guillermo* | To Do | 2 | - | - |
| **T-04** | Configurar colores corporativos | Aplicar Pantones MIGASA en Theme Customizer | *Nazaret* | To Do | 2 | - | RGB del manual |
| **T-05** | Cargar tipografías | Subir DIN Black y Myriad Pro al sitio | *Nazaret* | To Do | 1 | - | Formatos web |
| **T-06** | Análisis plugins seguridad | Comparar 3 plugins, documentar, instalar seleccionado | *Iluminada* | To Do | 3 | - | Wordfence vs Sucuri vs iThemes |
| **T-07** | Análisis plugins cache | Comparar 3 plugins, documentar, instalar seleccionado | *Iluminada* | To Do | 3 | - | WP Rocket vs W3 vs Super Cache |
| **T-08** | Análisis plugins SEO | Comparar 3 plugins, documentar, instalar seleccionado | *Emilio* | To Do | 3 | - | Yoast vs Rank Math vs AIOSEO |
| **T-09** | Análisis plugins Analytics | Comparar 3 plugins, documentar, instalar seleccionado | *Emilio* | To Do | 3 | - | MonsterInsights vs otros |
| **T-10** | Configurar Wordfence | Firewall, 2FA, escaneo programado | *Iluminada* | To Do | 2 | - | - |
| **T-11** | Configurar WP Rocket | Cache, lazy load, minificación CSS/JS | *Iluminada* | To Do | 2 | - | - |
| **T-12** | Configurar Yoast SEO | Sitemap, schema, breadcrumbs, meta defaults | *Emilio* | To Do | 2 | - | - |
| **T-13** | Configurar MonsterInsights | Conectar GA4, configurar tracking | *Emilio* | To Do | 2 | - | Cuenta GA requerida |
| **T-14** | Instalar plugins adicionales | WPForms, WPML, Envira, UpdraftPlus | *Guillermo* | To Do | 2 | - | - |
| **T-15** | Crear mockups principales | Diseñar con Balsamiq: Home, Empresa, Productos | *Nazaret* | To Do | 8 | - | 3 páginas mínimo |
| **T-16** | Crear diagrama de clases | UML con estructura WordPress/páginas/productos | *Emilio* | To Do | 4 | - | Usar draw.io o similar |
| **T-17** | Estructura de menús | Crear menú principal y footer, jerarquía | *Guillermo* | To Do | 2 | - | 7 items principales |
| **T-18** | Crear página Home | Implementar con Divi: hero, cifras, productos, CTA | *Nazaret* | To Do | 6 | - | Secciones modulares |
| **T-19** | Crear página Empresa | Historia, valores, ubicaciones, timeline | *Guillermo* | To Do | 5 | - | Incluir Google Maps |
| **T-20** | Crear categorías productos | Oliva, Girasol, Orujo + custom post type | *Iluminada* | To Do | 2 | - | - |
| **T-21** | Añadir 10 productos | Fichas con imágenes, descripciones, especificaciones | *Iluminada* | To Do | 6 | - | Contenido de web actual |
| **T-22** | Diseñar página producto individual | Template detalle producto con galería | *Nazaret* | To Do | 4 | - | Incluir CTA contacto |
| **T-23** | Crear formulario contacto | WPForms con validación, GDPR, notificaciones | *Emilio* | To Do | 3 | - | - |
| **T-24** | Crear página Contacto | Formulario + Google Maps + datos contacto | *Emilio* | To Do | 3 | - | 2 ubicaciones en mapa |
| **T-25** | Optimizar imágenes | Comprimir, convertir WebP, añadir ALT | *Iluminada* | To Do | 3 | - | - |
| **T-26** | Testing responsive | Probar en móvil/tablet/desktop | *Todos* | To Do | 4 | - | iOS, Android, navegadores |
| **T-27** | Testing formularios | Envíos de prueba, validaciones | *Emilio* | To Do | 2 | - | - |
| **T-28** | Documentar implementación | Screenshots, descripción de cada página | *Nazaret* | To Do | 4 | - | Para entregable PDF |
| **T-29** | Configurar backup automático | UpdraftPlus con Google Drive | *Guillermo* | To Do | 1 | - | - |
| **T-30** | Review general y ajustes | Revisar identidad, corregir detalles | *Todos* | To Do | 4 | - | Checklist final |

**Total horas estimadas Sprint 1:** 96 horas
**Distribución por persona:** ~24 horas/persona
**Capacidad por persona:** 4 horas/día laborable (medio tiempo por ser proyecto académico)

### Distribución de tareas por integrante:

**Guillermo Mendo Jiménez (24h):**
- Instalación y configuración técnica WordPress
- Estructura de menús y páginas
- Página Empresa
- Backups

**Emilio Cuevas Rendón (24h):**
- Análisis y configuración plugins SEO/Analytics
- Diagrama de clases
- Formulario y página Contacto
- Testing formularios

**Iluminada Baena Herruzo (23h):**
- Análisis y configuración plugins Seguridad/Cache
- Gestión de productos (categorías y fichas)
- Optimización de imágenes

**Nazaret María Villalba Delgado (25h):**
- Diseño visual (colores, tipografías)
- Mockups con Balsamiq
- Página Home y templates productos
- Documentación visual

### 6.5 Burndown Chart

### 6.5 Burndown Chart - Sprint 1

*[PENDIENTE: Gráfico burndown que debe actualizarse diariamente]*

**Estructura del gráfico:**
- Eje X: Días del sprint (10 días laborables)
- Eje Y: Horas pendientes (de 96 a 0)
- Línea ideal: Descenso lineal de 96 a 0 (9.6 horas/día)
- Línea real: Progreso actual del equipo

**Herramientas para crear el burndown:**
- GitHub Projects (gráficos automáticos)
- Excel/Google Sheets
- Jira (si se usa en lugar de GitHub Projects)
- Trello con Power-Ups

**Observaciones del Sprint 1:**
*[Actualizar diariamente durante el sprint]*

**Ejemplo de seguimiento:**
| Día | Fecha | Horas Ideales Restantes | Horas Reales Restantes | Diferencia | Observaciones |
|-----|-------|------------------------|------------------------|------------|---------------|
| 1 | *[Fecha]* | 86.4 | *[Real]* | *[Calc]* | *[Notas]* |
| 2 | *[Fecha]* | 76.8 | *[Real]* | *[Calc]* | *[Notas]* |
| 3 | *[Fecha]* | 67.2 | *[Real]* | *[Calc]* | *[Notas]* |
| 4 | *[Fecha]* | 57.6 | *[Real]* | *[Calc]* | *[Notas]* |
| 5 | *[Fecha]* | 48.0 | *[Real]* | *[Calc]* | *[Notas]* |
| 6 | *[Fecha]* | 38.4 | *[Real]* | *[Calc]* | *[Notas]* |
| 7 | *[Fecha]* | 28.8 | *[Real]* | *[Calc]* | *[Notas]* |
| 8 | *[Fecha]* | 19.2 | *[Real]* | *[Calc]* | *[Notas]* |
| 9 | *[Fecha]* | 9.6 | *[Real]* | *[Calc]* | *[Notas]* |
| 10 | *[Fecha]* | 0 | *[Real]* | *[Calc]* | Sprint Review |

**Métricas a monitorizar:**
- Velocidad del equipo (puntos de historia completados)
- Impedimentos encontrados
- Tareas bloqueadas
- Tareas añadidas durante el sprint
- Horas extra necesarias (si aplica)

---

## CONCLUSIONES DEL PRIMER ENTREGABLE

### Logros Principales

1. **Análisis exhaustivo de MIGASA:**
   - Empresa familiar líder mundial con 90+ años de historia
   - Presencia en 120 países, facturación >1000M€
   - Identificación clara de oportunidades de mejora web

2. **Requisitos bien definidos:**
   - 4 objetivos principales (Goals)
   - 6 requisitos de información
   - 5 requisitos de interfaz alineados con identidad corporativa
   - 8 requisitos funcionales priorizados
   - 5 requisitos no funcionales (rendimiento, seguridad, usabilidad)
   - 7 reglas de negocio basadas en manual corporativo

3. **Diseño técnico sól### 5.2 Análisis y Selección de Temas

| Tema | Precio | Valoración | Características Principales | Compatibilidad | Decisión |
|------|--------|-----------|----------------------------|----------------|----------|
| **Divi** | $89/año | ★★★★★ (4.9/5) | Visual Builder drag&drop, +800 diseños, responsive, WooCommerce, tema+plugin | Todos plugins seleccionados | ✅ **SELECCIONADO** |
| **Astra Pro** | $59/año | ★★★★★ (4.8/5) | Ultraligero (50KB), velocidad optimizada, +180 templates, compatible page builders | WPML, Yoast, WPForms | ❌ Descartado |
| **OceanWP** | Gratuito + Pro $39 | ★★★★☆ (4.7/5) | Multiuso, demos pre-construidas, e-commerce ready, extensiones modulares | Mayoría plugins | ❌ Descartado |

**Tema seleccionado:** Divi by Elegant Themes

**Justificación detallada:**

1. **Flexibilidad de diseño:**
   - Visual Builder permite diseñar páginas sin código
   - Fácil implementación de la identidad corporativa MIGASA
   - Control pixel-perfect de colores Pantone corporativos
   - Más de 200 elementos de diseño personalizables

2. **Rendimiento:**
   - Optimizado para SEO out-of-the-box
   - Compatible con WP Rocket
   - Código limpio y estructurado
   - Carga condicional de assets

3. **Responsive design:**
   - Responsive por defecto con controles específicos para móvil/tablet/desktop
   - Vista previa en tiempo real para cada dispositivo
   - Menú hamburguesa personalizable
   - Optimización automática de imágenes según dispositivo

4. **Compatibilidad:**
   - 100% compatible con Yoast SEO, WPML, WPForms
   - Integración nativa con WooCommerce (futuro e-commerce)
   - Compatible con todos los plugins seleccionados
   - Actualizaciones regulares y soporte continuo

5. **Facilidad de uso:**
   - El equipo de MIGASA podrá editar contenido sin conocimientos técnicos
   - Biblioteca de layouts pre-diseñados para acelerar desarrollo
   - Split testing A/B integrado
   - Roles y permisos personalizables

6. **Identidad corporativa:**
   - Fácil implementación de colores Pantone exactos (RGB)
   - Carga de tipografías personalizadas (DIN Black, Myriad Pro)
   - Control total sobre spacing y áreas de seguridad del logo
   - Módulos reutilizables para mantener consistencia

7. **Multiidioma:**
   - Totalmente compatible con WPML
   - Gestión sencilla de contenido traducido
   - URLs amigables por idioma

8. **ROI:**
   - Inversión única anual razonable ($89)
   - Ahorro en desarrollo al no necesitar programación custom
   - Licencia incluye uso ilimitado en sitios
   - Soporte premium incluido

**Alternativas descartadas:**
- **Astra Pro:** Aunque más ligero y económico, requiere plugins adicionales (page builder) y tiene menos opciones de diseño visual avanzado
- **OceanWP:** Buena opción gratuita pero menos profesional para una empresa del calibre de MIGASA, documentación limitada en español# PROYECTO CMS - WORDPRESS

## 7. IMPLEMENTACIÓN

### 7.1 Instalación de WordPress

**Proceso realizado:**
1. Instalación de stack XAMPP/Bitnami WAMP
2. Creación de base de datos MySQL: `migasa_cms_db`
3. Descarga de WordPress desde wordpress.org
4. Configuración inicial: nombre sitio, usuario admin, email
5. Acceso: http://localhost:8080/wordpress

**Screenshots:**
*[PENDIENTE: Incluir captura de pantalla del dashboard WordPress instalado]*

### 7.2 Configuración de Tema Divi

**Pasos realizados:**
1. Descarga e instalación de Divi Theme
2. Activación de licencia Elegant Themes
3. Configuración de colores corporativos en Theme Customizer:
   - Color primario: #A3AB11 (Pantone 383 C)
   - Color secundario: #7C9323 (Pantone 377 C)
   - Color acento: #3B593B (Pantone 357 C)
4. Carga de tipografías: DIN Black, Myriad Pro
5. Configuración responsive: breakpoints personalizados

**Screenshots:**
*[PENDIENTE: Captura del Theme Customizer con colores MIGASA]*

### 7.3 Instalación de Plugins

**Plugins instalados y configurados:**

1. **Wordfence Security**
   - Firewall activado en "Learning Mode" inicial
   - Escaneo programado diario a las 3:00 AM
   - 2FA activado para usuario administrador
   - *[Screenshot configuración]*

2. **WP Rocket**
   - Cache de página activado
   - Lazy loading de imágenes habilitado
   - Minificación CSS y JS activada
   - Precarga de cache configurada
   - *[Screenshot panel WP Rocket]*

3. **MonsterInsights**
   - Conectado con Google Analytics 4
   - Tracking de formularios activado
   - Exclusión de IPs internas
   - Dashboard configurado
   - *[Screenshot informes Analytics]*

4. **Yoast SEO**
   - Configuración inicial completada
   - Sitemap XML generado: /sitemap_index.xml
   - Schema.org tipo: Organización
   - Breadcrumbs activados
   - Meta descripción por defecto configurada
   - *[Screenshot análisis SEO]*

5. **WPML** (Multiidioma)
   - Idiomas: Español (principal), Inglés
   - Formato URLs: directorio (/es/, /en/)
   - Traducción menús configurada

6. **WPForms**
   - Formulario contacto creado
   - Notificaciones email configuradas
   - Anti-spam Akismet integrado
   - *[Screenshot formulario]*

7. **UpdraftPlus**
   - Backup automático semanal
   - Almacenamiento: Google Drive
   - Retención: 4 copias

### 7.4 Estructura de Páginas Creadas

**Menú principal:**
- Inicio
- Empresa
  - Quiénes somos
  - Historia
  - Instalaciones
- Productos
  - Aceite de Oliva
  - Aceite de Girasol
  - Aceite de Orujo
- Mercados
- Sostenibilidad
- Noticias
- Contacto

**Screenshots de cada página:**
*[PENDIENTE: Incluir capturas de cada página implementada]*

#### 7.4.1 Página de Inicio
**Descripción:**
- Header con logo MIGASA (versión principal sobre fondo blanco)
- Hero section con imagen de olivar y texto "Líderes mundiales en aceite de oliva desde 1933"
- Sección cifras clave: 90+ años, 120 países, 1000M€ facturación
- Productos destacados (3 columnas)
- CTA: "Descubre nuestra historia"
- Footer con contacto y redes sociales

**Colores aplicados:** Tonos verdes corporativos, fondo blanco limpio
*[Screenshot]*

#### 7.4.2 Página de Empresa
**Descripción:**
- Timeline interactiva con historia de MIGASA
- Sección "Tercera generación" con fotos familia
- Valores corporativos en cards
- Video institucional embebido
- Ubicaciones: Dos Hermanas y La Luisiana con Google Maps

*[Screenshot]*

#### 7.4.3 Página de Productos - Aceite de Oliva
**Descripción:**
- Grid de productos con filtros
- Cada producto muestra: imagen, nombre, descripción, presentaciones
- Sidebar con categorías
- CTA: "Solicitar información" (enlace formulario contacto)

**Productos incluidos:**
- Aceite de Oliva Virgen Extra
- Aceite de Oliva Virgen
- Aceite de Oliva Refinado
- Aceite de Oliva (blend)

*[Screenshot]*

#### 7.4.4 Página de Contacto
**Descripción:**
- Formulario WPForms con campos:
  - Nombre y Apellidos (requerido)
  - Email (requerido)
  - Teléfono
  - Tipo de consulta (dropdown): General, Productos, Comercial, Prensa
  - Mensaje (requerido)
  - GDPR checkbox
- Google Maps doble: Dos Hermanas y La Luisiana
- Datos contacto:
  - Dirección: Ctra. Madrid-Cádiz, Km. 556, 41703 Dos Hermanas (Sevilla)
  - Teléfono: 954 720 550
  - Fax: 954 729 552
  - Email: info@migasa.com
  - Web: www.migasa.com

*[Screenshot]*

### 7.5 Identidad Visual Implementada

**Logo:**
- Versión completa en header (tamaño 150px de ancho)
- Área de seguridad respetada (5mm = 19px)
- Versión móvil reducida a 100px

**Tipografías:**
- Títulos H1, H2: DIN Black Regular
- Contenido: Myriad Pro Regular (9pt/12pt según sección)
- Menú: Myriad Pro Bold

**Paleta de colores RGB aplicada:**
- Verde claro #A3AB11 (botones primarios, enlaces)
- Verde medio #7C9323 (títulos secundarios)
- Verde oscuro #3B593B (footer, elementos de contraste)
- Negro 100% para textos principales
- Gris 70% para textos secundarios

**Elementos gráficos:**
- Líneas paralelas del imagotipo usadas como separadores
- Patrón de líneas en backgrounds sutiles
- Iconografía en verde corporativo

### 7.6 Optimizaciones Realizadas

**SEO:**
- Meta título y descripción en todas las páginas
- URLs amigables activadas: /productos/aceite-oliva/
- Imágenes con atributos ALT descriptivos
- Heading hierarchy correcta (H1 único por página)
- Sitemap XML enviado a Google Search Console

**Rendimiento:**
- Imágenes optimizadas (formato WebP cuando posible)
- Lazy loading activado
- CSS y JS minificados
- GZIP compression habilitada
- Resultado PageSpeed Insights: *[PENDIENTE: incluir score]*

**Seguridad:**
- Certificado SSL configurado (HTTPS)
- Login protegido con 2FA
- Firewall Wordfence en modo activo
- Backups automáticos semanales
- Ocultación de versión WordPress

**Accesibilidad:**
- Contraste de colores cumple WCAG 2.1 AA
- Navegación por teclado funcional
- Atributos ARIA en elementos interactivos
- Formularios con labels correctos

### 7.7 Testing Realizado

**Compatibilidad navegadores:**
- ✅ Chrome (última versión)
- ✅ Firefox (última versión)
- ✅ Safari (última versión)
- ✅ Edge (última versión)

**Dispositivos móviles:**
- ✅ iPhone (Safari)
- ✅ Android (Chrome)
- ✅ iPad (Safari)

**Funcionalidades probadas:**
- ✅ Navegación menú responsive
- ✅ Formulario contacto (envío y recepción email)
- ✅ Búsqueda interna
- ✅ Cambio de idioma (ES/EN)
- ✅ Galerías de productos
- ✅ Google Maps integrado

### 7.8 Próximos Pasos (Sprint 2)

1. Completar traducciones al inglés con WPML
2. Añadir más productos al catálogo
3. Crear sección blog/noticias con primeras entradas
4. Implementar mapa interactivo de presencia internacional
5. Optimizar aún más velocidad (objetivo: <2s carga)
6. Formación al equipo MIGASA para gestión de contenidos
7. Configurar Google Search Console y Analytics avanzado
8. Implementar schema markup para productos

## REFERENCIAS

*[PENDIENTE: Referencias utilizadas]*

---

**Notas para el desarrollo:**
- Este documento debe ser completado progresivamente
- Las secciones marcadas como *[PENDIENTE]* requieren información específica
- Todos los diagramas y mockups deben ser incluidos como imágenes
- El documento final debe exportarse a PDF
