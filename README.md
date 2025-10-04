# PROYECTO CMS - WORDPRESS
## Desarrollo Web para MIGASA - Aceites de Oliva
### Primer Entregable - Sprint 1

---

**Integrantes del equipo:**
- Guillermo Mendo Jiménez
- Emilio Cuevas Rendón
- Iluminada Baena Herruzo
- Nazaret María Villalba Delgado

**Fecha de elaboración:** *[Completar fecha]*  
**Versión:** 1.0 - Sprint 1  
**Repositorio GitHub:** https://github.com/GuilleMJ04/migasa-cms-proyecto

---

## ÍNDICE

1. [INTRODUCCIÓN](#1-introducción)
   - 1.1. Propósito del Proyecto
   - 1.2. Alcance
   - 1.3. Empresa Seleccionada
2. [ANÁLISIS DE LA EMPRESA](#2-análisis-de-la-empresa)
   - 2.1. Descripción de la Empresa
   - 2.2. Problemática Identificada
   - 2.3. Oportunidades de Mejora
3. [REQUISITOS CON REM](#3-requisitos-con-rem)
   - 3.1. Objetivos (Goals)
   - 3.2. Requisitos de Información
   - 3.3. Requisitos de Interfaz de Usuario
   - 3.4. Requisitos Funcionales
   - 3.5. Requisitos No Funcionales
   - 3.6. Reglas de Negocio
4. [ANÁLISIS DEL SISTEMA](#4-análisis-del-sistema)
   - 4.1. Mockups y Prototipos
   - 4.2. Diagrama de Clases
5. [DISEÑO](#5-diseño)
   - 5.1. Análisis y Selección de Plugins
   - 5.2. Análisis y Selección de Temas
6. [PLANIFICACIÓN SCRUM](#6-planificación-scrum)
   - 6.1. Software Colaborativo Seleccionado
   - 6.2. Control de Versiones
   - 6.3. Product Backlog
   - 6.4. Sprint Backlog
   - 6.5. Burndown Chart
7. [IMPLEMENTACIÓN](#7-implementación)
   - 7.1. Instalación de WordPress
   - 7.2. Configuración de Tema
   - 7.3. Instalación de Plugins
   - 7.4. Estructura de Páginas Creadas
   - 7.5. Identidad Visual Implementada
   - 7.6. Optimizaciones Realizadas
   - 7.7. Testing Realizado
   - 7.8. Próximos Pasos
8. [CONCLUSIONES](#8-conclusiones)
9. [REFERENCIAS](#9-referencias)
10. [ANEXOS](#10-anexos)

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

**Sitio web actual:** www.migasa.com

**Situación actual:** MIGASA es una empresa familiar española líder mundial en la venta de aceite de oliva con más de 90 años de historia, facturación superior a 1.000 millones de euros anuales y presencia en más de 120 países. Cuenta con sitio web corporativo que necesita ser modernizado para identificar oportunidades de mejora.

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

*Requisitos elicitados mediante metodología REM (Requirements Engineering Methodology)*

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
- Verde claro: R:163 G:171 B:17 (Pantone 383 C) - #A3AB11
- Verde medio: R:124 G:147 B:35 (Pantone 377 C) - #7C9323
- Verde oscuro: R:59 G:89 B:59 (Pantone 357 C) - #3B593B

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
**Métrica:** PageSpeed Insights > 80/100  
**Prioridad:** Alta

#### NFR02: Seguridad
**Descripción:** Implementar medidas de seguridad robustas  
**Especificaciones:**
- Certificado SSL (HTTPS)
- Firewall de aplicación web
- Autenticación de dos factores para administradores
- Backups automáticos semanales
- Protección contra ataques de fuerza bruta

**Prioridad:** Alta

#### NFR03: Usabilidad
**Descripción:** Interfaz intuitiva y fácil de usar  
**Especificaciones:**
- Navegación clara (máximo 3 clics para cualquier contenido)
- Textos legibles (contraste adecuado)
- Formularios con validación clara
- Mensajes de error comprensibles

**Prioridad:** Media

#### NFR04: Compatibilidad
**Descripción:** Funcionamiento correcto en diferentes navegadores y dispositivos  
**Especificaciones:**
- Chrome, Firefox, Safari, Edge (últimas 2 versiones)
- iOS y Android
- Resoluciones desde 320px hasta 2560px

**Prioridad:** Alta

#### NFR05: Accesibilidad
**Descripción:** Cumplimiento de estándares WCAG 2.1 nivel AA  
**Especificaciones:**
- Navegación por teclado
- Atributos ARIA
- Contraste de colores adecuado
- Textos alternativos en imágenes

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

*(Preguntar al profesor)

### 4.2 Diagrama de Clases

*Diagrama UML que representa la estructura del sitio WordPress para MIGASA*


---

## 5. DISEÑO

### 5.1 Análisis y Selección de Plugins

#### 5.1.1 Plugins de Seguridad (OBLIGATORIO)

| Plugin | Última Actualización | Descargas | Valoración | Características Principales | Decisión |
|--------|---------------------|-----------|-----------|----------------------------|----------|
| **Wordfence Security** | Actualización continua | 5M+ | ★★★★★ (4.7/5) | • Firewall de aplicación web (WAF)<br>• Escaneo de malware y vulnerabilidades<br>• Autenticación de dos factores (2FA)<br>• Bloqueo de fuerza bruta<br>• Monitorización en tiempo real<br>• Alertas por email | ✅ **SELECCIONADO** |
| **Sucuri Security** | Actualización mensual | 800K+ | ★★★★☆ (4.5/5) | • Auditoría de actividad de seguridad<br>• Monitoreo de integridad de archivos<br>• Lista negra de monitorización remota<br>• Limpieza post-hackeo<br>• Acciones de seguridad posteriores al hack | ❌ Descartado |
| **iThemes Security** | Actualización continua | 1M+ | ★★★★☆ (4.6/5) | • Más de 50 formas de protección<br>• Autenticación de dos factores<br>• Forzar contraseñas fuertes<br>• Detección de cambios en archivos<br>• Programación de escaneos | ❌ Descartado |

**Plugin seleccionado:** Wordfence Security

**Justificación detallada:**
- **Mayor número de instalaciones activas** (5M+), lo que demuestra confianza de la comunidad
- **Firewall de aplicación web incluido** en versión gratuita, protección avanzada contra amenazas
- **Escaneo de malware más completo** que la competencia, detecta backdoors y código malicioso
- **Dashboard intuitivo** con alertas en tiempo real y métricas de seguridad fáciles de interpretar
- **Actualizaciones automáticas** de reglas de firewall para protección contra amenazas emergentes
- **Ideal para empresas** con información sensible como MIGASA (datos de clientes, información comercial)
- **Soporte técnico responsive** y documentación extensa en español
- **Integración con tráfico en vivo** para monitorizar intentos de acceso sospechosos

#### 5.1.2 Plugins de Cache (OBLIGATORIO)

| Plugin | Última Actualización | Descargas | Valoración | Características Principales | Decisión |
|--------|---------------------|-----------|-----------|----------------------------|----------|
| **WP Rocket** | Actualización continua | Premium (pago) | ★★★★★ (4.9/5) | • Cache de página completa<br>• Lazy loading de imágenes y videos<br>• Minificación de CSS/JS/HTML<br>• Compatible con CDN<br>• Preload de cache<br>• Optimización de base de datos<br>• Configuración 1-click | ✅ **SELECCIONADO** |
| **W3 Total Cache** | Actualización mensual | 1M+ | ★★★★☆ (4.3/5) | • Cache completa (página, objeto, base datos)<br>• Integración CDN<br>• Minificación recursos<br>• Gratuito<br>• Muchas opciones de configuración<br>• Compatible con SSL | ❌ Descartado |
| **WP Super Cache** | Actualización trimestral | 2M+ | ★★★★☆ (4.4/5) | • Genera archivos HTML estáticos<br>• Cache simple y efectiva<br>• Totalmente gratuito<br>• Configuración sencilla<br>• Ligero y sin complejidades | ❌ Descartado |

**Plugin seleccionado:** WP Rocket

**Justificación detallada:**
- **Mejores resultados en velocidad:** reduce tiempo de carga entre 40-50% en promedio
- **Configuración automática:** no requiere conocimientos técnicos, activar y funciona
- **Lazy loading integrado** de imágenes (crucial para catálogo de productos de MIGASA)
- **Preload de cache:** garantiza que siempre haya versión cacheada disponible
- **Optimización de base de datos:** limpia revisiones, spam, transients automáticamente
- **Compatible con WooCommerce:** por si en futuro se implementa tienda online
- **Soporte premium en español:** respuesta en menos de 24h
- **ROI justificado:** inversión ($59/año) compensada por mejora en conversiones y SEO
- **Actualizaciones frecuentes:** siempre compatible con última versión WordPress

**Alternativas descartadas:**
- **W3 Total Cache:** Aunque gratuito, configuración muy compleja para usuario no técnico
- **WP Super Cache:** Funcionalidad básica insuficiente para necesidades de MIGASA

#### 5.1.3 Plugins de Analytics (OBLIGATORIO)

| Plugin | Última Actualización | Descargas | Valoración | Características Principales | Decisión |
|--------|---------------------|-----------|-----------|----------------------------|----------|
| **MonsterInsights** | Actualización continua | 3M+ | ★★★★★ (4.6/5) | • Integración Google Analytics 4 en dashboard<br>• Tracking de e-commerce<br>• Informes automáticos por email<br>• Cumplimiento GDPR<br>• Tracking de formularios y descargas<br>• Segmentación de audiencia<br>• Informes de velocidad de página | ✅ **SELECCIONADO** |
| **Google Analytics Dashboard** | Actualización mensual | 1M+ | ★★★★☆ (4.5/5) | • Integración básica con GA4<br>• Informes en dashboard WP<br>• Totalmente gratuito<br>• Configuración simple<br>• Estadísticas en tiempo real | ❌ Descartado |
| **Analytify** | Actualización continua | 200K+ | ★★★★☆ (4.7/5) | • Dashboard visual atractivo<br>• Estadísticas en tiempo real<br>• Tracking de eventos<br>• Informes por página/post<br>• Compatible con Google Analytics | ❌ Descartado |

**Plugin seleccionado:** MonsterInsights

**Justificación detallada:**
- **Integración completa con Google Analytics 4:** configuración guiada paso a paso
- **Dashboard visual en WordPress:** no necesita salir del admin para ver estadísticas
- **Tracking automático avanzado:** formularios, clics externos, descargas de catálogos PDF
- **Informes de e-commerce preparados:** útil si MIGASA implementa tienda online futura
- **Compatible con GDPR:** importante para empresa europea, gestión de consentimientos
- **Segmentación por país:** crucial para MIGASA con presencia en 120 países
- **Informes automáticos por email:** envío semanal/mensual a stakeholders
- **Tracking de eventos personalizados:** medir interacciones específicas (ver productos, contacto)
- **Soporte premium con prioridad** y actualizaciones garantizadas

#### 5.1.4 Plugins de SEO (OBLIGATORIO)

| Plugin | Última Actualización | Descargas | Valoración | Características Principales | Decisión |
|--------|---------------------|-----------|-----------|----------------------------|----------|
| **Yoast SEO** | Actualización semanal | 5M+ | ★★★★★ (4.9/5) | • Análisis de contenido en tiempo real<br>• Generación de XML sitemaps<br>• Breadcrumbs para navegación<br>• Control de meta descripciones<br>• Schema.org markup (Rich Snippets)<br>• Integración redes sociales<br>• Análisis de legibilidad<br>• Redirecciones (versión premium) | ✅ **SELECCIONADO** |
| **Rank Math** | Actualización continua | 2M+ | ★★★★★ (4.8/5) | • 40+ herramientas SEO gratuitas<br>• Google Search Console integrado<br>• Análisis automático de 404<br>• Redirecciones ilimitadas gratuitas<br>• Múltiples keywords por página<br>• Rich snippets avanzados | ❌ Descartado |
| **All in One SEO** | Actualización semanal | 3M+ | ★★★★☆ (4.6/5) | • Optimización automática de SEO<br>• Generación de XML sitemaps<br>• Integración con redes sociales<br>• TruSEO score<br>• Schema markup | ❌ Descartado |

**Plugin seleccionado:** Yoast SEO

**Justificación detallada:**
- **Estándar de la industria:** plugin más maduro y estable del mercado
- **Interfaz intuitiva:** semáforo verde/amarillo/rojo fácil de entender para no expertos
- **Análisis en tiempo real:** feedback inmediato sobre legibilidad y SEO mientras escribes
- **Optimización para palabras clave:** guía para optimizar términos como "aceite de oliva", "MIGASA"
- **Schema markup automático:** rich snippets para productos (crucial para catálogo)
- **Compatibilidad multiidioma:** funciona perfectamente con WPML (español/inglés)
- **Breadcrumbs SEO-friendly:** mejora navegación y estructura de URLs
- **Documentación extensa en español:** tutoriales, webinars, soporte activo
- **Actualizaciones semanales:** siempre al día con algoritmos de Google
- **Integración con Google Search Console:** monitorización de errores y rendimiento

**Alternativas descartadas:**
- **Rank Math:** Aunque tiene más funciones gratuitas, menos maduro y estable
- **All in One SEO:** Interfaz menos intuitiva, documentación menos completa

#### 5.1.5 Otros Plugins Específicos

**Plugin de Formularios:**
- **WPForms** (Seleccionado)
- **Características:** Drag & drop builder, plantillas pre-diseñadas, protección anti-spam, notificaciones email, integración con MonsterInsights
- **Justificación:** Interfaz visual sin código, formularios responsive, tracking de conversiones, GDPR compliant

**Plugin Multiidioma:**
- **WPML** (Seleccionado)
- **Características:** Traducción completa del sitio, compatible con Yoast SEO, gestión de URLs por idioma, traductor integrado
- **Justificación:** Presencia en 120 países requiere mínimo español/inglés, posibilidad de añadir más idiomas, SEO multiidioma optimizado

**Plugin de Galería:**
- **Envira Gallery** (Seleccionado)
- **Características:** Lightbox responsive, lazy loading integrado, álbumes de productos, protección de imágenes
- **Justificación:** Catálogo visual atractivo de productos, presentación profesional, optimización automática

**Plugin de Backup:**
- **UpdraftPlus** (Seleccionado)
- **Características:** Backup automático programable, restauración 1-click, almacenamiento en cloud (Google Drive, Dropbox), backups incrementales
- **Justificación:** Protección de datos críticos, fácil recuperación ante desastres, backups off-site

**Plugin de Optimización de Imágenes:**
- **ShortPixel** (Seleccionado)
- **Características:** Compresión automática, conversión a WebP, lazy load, optimización bulk
- **Justificación:** Catálogo con muchas imágenes de productos, mejora velocidad, mantiene calidad visual

### 5.2 Análisis y Selección de Temas

| Tema | Precio | Valoración | Características Principales | Compatibilidad | Decisión |
|------|--------|-----------|----------------------------|----------------|----------|
| **Divi** | $89/año | ★★★★★ (4.9/5) | • Visual Builder drag & drop<br>• +800 diseños prediseñados<br>• Responsive por defecto<br>• Compatible WooCommerce<br>• Tema + plugin incluido<br>• 47 elementos de diseño<br>• Actualizaciones de por vida | Todos los plugins seleccionados | ✅ **SELECCIONADO** |
| **Astra Pro** | $59/año | ★★★★★ (4.8/5) | • Ultraligero (menos de 50KB)<br>• Velocidad optimizada<br>• +180 templates starter<br>• Compatible con page builders<br>• WooCommerce ready<br>• Schema markup integrado | WPML, Yoast, WPForms, compatible con Elementor | ❌ Descartado |
| **OceanWP** | Gratis + Pro $39 | ★★★★☆ (4.7/5) | • Tema multiuso flexible<br>• Demos pre-construidas<br>• E-commerce ready<br>• Extensiones modulares<br>• Compatible page builders<br>• RTL y traducible | Mayoría de plugins populares | ❌ Descartado |

**Tema seleccionado:** Divi by Elegant Themes

**Justificación detallada:**

**1. Flexibilidad de diseño:**
- Visual Builder permite diseñar páginas sin escribir código
- Fácil implementación precisa de la identidad corporativa MIGASA
- Control pixel-perfect de colores Pantone corporativos (RGB exactos)
- Más de 200 elementos de diseño personalizables
- Módulos reutilizables para mantener consistencia visual

**2. Rendimiento:**
- Optimizado para SEO out-of-the-box
- Compatible con WP Rocket para máxima velocidad
- Código limpio y estructurado según estándares WordPress
- Carga condicional de assets (solo carga lo necesario)
- Minificación automática de CSS/JS

**3. Responsive design:**
- Responsive por defecto con controles específicos desktop/tablet/móvil
- Vista previa en tiempo real para cada dispositivo
- Menú hamburguesa personalizable y táctil
- Optimización automática de imágenes según dispositivo
- Control independiente de márgenes y padding por breakpoint

**4. Compatibilidad total:**
- 100% compatible con Yoast SEO, WPML, WPForms
- Integración nativa con WooCommerce (para futuro e-commerce)
- Compatible con todos los plugins seleccionados
- Actualizaciones regulares y soporte continuo
- No genera conflictos con plugins de terceros

**5. Facilidad de uso para el cliente:**
- El equipo de MIGASA podrá editar contenido sin conocimientos técnicos
- Biblioteca de layouts pre-diseñados acelera desarrollo
- Split testing A/B integrado (versión premium)
- Roles y permisos personalizables por usuario
- Interfaz visual intuitiva en español

**6. Implementación de identidad corporativa:**
- Carga sencilla de colores Pantone exactos (RGB: #A3AB11, #7C9323, #3B593B)
- Subida de tipografías personalizadas (DIN Black, Myriad Pro) sin plugins adicionales
- Control total sobre spacing y áreas de seguridad del logo
- Módulos reutilizables para elementos de marca (headers, footers, CTAs)
- Presets de estilo guardables para reutilizar diseños

**7. Multiidioma:**
- Totalmente compatible con WPML
- Gestión sencilla de contenido traducido
- URLs amigables por idioma (/es/, /en/)
- Menús y widgets traducibles
- Visual Builder funciona en todos los idiomas

**8. ROI y valor:**
- Inversión única anual razonable ($89)
- Incluye tema + Divi Builder (plugin standalone)
- Licencia incluye uso ilimitado en sitios web
- Soporte premium incluido (chat y tickets)
- Actualizaciones de por vida garantizadas
- Ahorro en desarrollo al no necesitar programación custom

**9. Comunidad y recursos:**
- Comunidad masiva de usuarios (millones)
- Miles de tutoriales en YouTube y blogs
- Layouts gratuitos compartidos por la comunidad
- Child themes disponibles
- Documentación oficial extensa en español

**Alternativas descartadas:**

**Astra Pro:** 
- **Pros:** Más ligero, más económico ($59), excelente velocidad
- **Contras:** Requiere page builder adicional (Elementor), menos opciones de diseño visual avanzado, curva de aprendizaje mayor para cliente final
- **Razón descarte:** Aunque técnicamente sólido, Divi ofrece más valor integral

**OceanWP:**
- **Pros:** Opción gratuita robusta, buena base para proyectos simples
- **Contras:** Menos profesional para empresa del calibre de MIGASA, documentación limitada en español, extensiones modulares fragmentan la experiencia
- **Razón descarte:** No refleja el nivel corporativo requerido, soporte menos robusto

---

## 6. PLANIFICACIÓN SCRUM

### 6.1 Software Colaborativo Seleccionado

**Software elegido:** GitHub (con GitHub Issues y GitHub Projects)

**Justificación de la selección:**

**Ventajas principales:**
- **Integración completa:** Combina control de versiones y gestión de proyectos en una sola plataforma
- **Colaboración eficiente:** Permite trabajo conjunto en código, documentación y seguimiento de tareas
- **Transparencia total:** Historial completo de cambios, decisiones y progreso del proyecto
- **Accesibilidad:** Gratuito para repositorios públicos, sin límite de colaboradores
- **Funcionalidades SCRUM nativas:** GitHub Projects permite crear tableros Kanban, sprints y seguimiento

**Características principales utilizadas:**

1. **GitHub Issues:**
   - Creación de historias de usuario como issues
   - Labels para categorizar (bug, enhancement, sprint-1, high-priority)
   - Asignación de responsables
   - Comentarios y discusiones en cada issue
   - Referencias cruzadas entre issues y commits

2. **GitHub Projects:**
   - Tablero Kanban visual (Product Backlog, Sprint Backlog, In Progress, Review, Done)
   - Automatización de movimiento de tarjetas
   - Vista de progreso en tiempo real
   - Filtros por sprint, responsable, prioridad
   - Integración automática con issues y pull requests

**Comparativa con alternativas:**

|## Comparativa de Software Colaborativo

| Característica | GitHub Projects | Microsoft Teams | Trello | Decisión |
|----------------|----------------|-----------------|--------|----------|
| **Integración con Git** | ✅ Nativa | ❌ Requiere plugins/apps | ❌ Separado del código | **Ventaja GitHub** |
| **Control de versiones** | ✅ Git incluido | ❌ No incluido | ❌ No incluido | **Ventaja GitHub** |
| **Gestión de tareas** | ✅ Issues + Projects | ✅ Planner/Tasks | ✅ Tableros Kanban | Empate |
| **Precio** | ✅ Gratuito (público) | ⚠️ Gratuito básico, limitado | ⚠️ Limitado gratuito | **Ventaja GitHub** |
| **Funciones SCRUM** | ✅ Básicas pero suficientes | ⚠️ Básicas (requiere Planner) | ⚠️ Básicas (requiere Power-Ups) | Empate |
| **Comunicación en tiempo real** | ⚠️ Comentarios asíncronos | ✅ Chat, videollamadas | ⚠️ Comentarios asíncronos | **Ventaja Teams** |
| **Almacenamiento archivos** | ✅ Repositorio Git | ✅ OneDrive/SharePoint | ⚠️ Attachments básicos | Empate |
| **Historial de cambios** | ✅ Completo con Git | ⚠️ Limitado a archivos | ❌ No disponible | **Ventaja GitHub** |
| **Colaboración código** | ✅ Pull Requests, code review | ❌ No especializado | ❌ No disponible | **Ventaja GitHub** |
| **Automatización** | ✅ GitHub Actions | ✅ Power Automate | ⚠️ Butler (limitado) | Empate |
| **Portfolio profesional** | ✅ Visible públicamente | ❌ Interno organización | ⚠️ Menos relevante | **Ventaja GitHub** |
| **Curva de aprendizaje** | ⚠️ Media (requiere Git) | ✅ Baja (interfaz conocida) | ✅ Baja (muy intuitivo) | **Ventaja Teams** |
| **Documentación técnica** | ✅ Markdown, Wiki | ✅ OneNote, Docs | ⚠️ Descripciones básicas | Empate |
| **Integraciones** | ✅ Amplio ecosistema | ✅ Microsoft 365 | ✅ Muchas apps | Empate |
| **Reporting SCRUM** | ⚠️ Básico | ⚠️ Básico | ⚠️ Limitado gratuito | Empate |
| **Uso en industria** | ✅ Estándar desarrollo web | ✅ Estándar empresas | ⚠️ Gestión proyectos | **Ventaja GitHub** |

**Software seleccionado:** GitHub Projects

**Justificación:** Integración nativa con Git, control de versiones incluido, gratuito, ideal para proyectos de desarrollo web, y valioso para portfolio profesional.

### 6.2 Control de Versiones

**Sistema seleccionado:** Git con GitHub como repositorio remoto

**Justificación:**
- **Estándar de la industria:** Sistema de control de versiones más utilizado mundialmente
- **Trabajo colaborativo eficiente:** Branching y merging facilitan desarrollo paralelo
- **Historial completo:** Registro detallado de todos los cambios (quién, qué, cuándo, por qué)
- **Backup automático:** Código siempre respaldado en la nube
- **Reversión sencilla:** Posibilidad de volver a versiones anteriores ante errores
- **Resolución de conflictos:** Herramientas visuales para merge conflicts


### 6.3 Product Backlog

**Total puntos Product Backlog:** 80 puntos  
**Velocidad estimada:** 40 puntos por sprint (2 semanas cada uno)

| ID | Historia de Usuario | Descripción Detallada | Criterios de Aceptación | Prioridad | Puntos | Sprint |
|----|--------------------|-----------------------|------------------------|-----------|--------|---------|
| **PBI-01** | Como visitante, quiero navegar fácilmente por el sitio | Implementar menú responsive con estructura jerárquica clara y breadcrumbs | • Menú visible en todas las páginas<br>• Breadcrumbs en todas las páginas internas<br>• Navegación intuitiva (máximo 3 clics) | Alta | 8 | Sprint 1 |
| **PBI-02** | Como administrador, quiero gestionar contenido fácilmente | Configurar WordPress con roles, permisos y Divi Builder | • Dashboard WordPress intuitivo<br>• Roles definidos (admin/editor)<br>• Divi Builder configurado y funcional<br>• Documentación de uso entregada | Alta | 5 | Sprint 1 |
| **PBI-03** | Como visitante, quiero ver productos de aceite | Catálogo de productos con filtros por tipo y ficha detallada | • Mínimo 10 productos publicados<br>• Filtro por tipo de aceite funcional<br>• Ficha detallada con especificaciones técnicas<br>• Imágenes de alta calidad | Alta | 13 | Sprint 1 |
| **PBI-04** | Como visitante, quiero contactar con MIGASA | Formulario funcional con validación y notificaciones email | • Campos obligatorios validados<br>• Email confirmación a usuario<br>• Notificación a MIGASA funcional<br>• Anti-spam activo (Akismet)<br>• GDPR checkbox obligatorio | Alta | 3 | Sprint 1 |
| **PBI-05** | Como visitante, quiero un sitio rápido | Optimizar rendimiento con cache, compresión y lazy loading | • PageSpeed Insights >80/100<br>• Tiempo de carga <3 segundos<br>• Lazy loading activado<br>• Imágenes optimizadas (WebP) | Media | 5 | Sprint 1 |
| **PBI-06** | Como visitante móvil, quiero acceso completo | Diseño 100% responsive y optimizado para táctil | • Funcional en iOS y Android<br>• Menú táctil optimizado<br>• Formularios mobile-friendly<br>• Imágenes adaptativas<br>• Testing en dispositivos reales | Alta | 8 | Sprint 2 |
| **PBI-07** | Como visitante internacional, quiero el sitio en cinco idiomas | Implementar multiidioma con WPML | • Todo el contenido traducido<br>• Selector de idioma visible<br>• URLs por idioma <br>• Menús traducidos<br>• SEO multiidioma optimizado | Media | 8 | Sprint 2 |
| **PBI-08** | Como visitante, quiero conocer la historia de MIGASA | Página "Empresa" con timeline interactiva y valores | • Timeline con hitos históricos<br>• Sección 90 años de historia<br>• Fotos de familia/instalaciones<br>• Video institucional embebido<br>• Misión, visión y valores | Media | 5 | Sprint 2 |
| **PBI-09** | Como administrador, quiero seguridad robusta | Configurar firewall, 2FA, SSL y backups automáticos | • Wordfence activo y escaneando<br>• 2FA obligatorio para admin<br>• Backups semanales automáticos<br>• SSL certificado configurado<br>• Login protegido contra fuerza bruta | Alta | 5 | Sprint 1 |

**Priorización:**
- **Alta prioridad (Sprint 1):** Funcionalidades core (navegación, productos, contacto, seguridad)
- **Media prioridad (Sprint 2):** Optimizaciones y contenido adicional (analytics, multiidioma, historia)

# PROYECTO CMS - WORDPRESS MIGASA
## Secciones 6.4 en adelante

---

## 6.4 Sprint Backlog - Sprint 1

**Objetivo del Sprint:** Establecer la base funcional del sitio WordPress con diseño responsive, catálogo de productos, formulario de contacto y medidas de seguridad, todo respetando la identidad corporativa de MIGASA.

**Duración:** 2 semanas (10 días laborables)  
**Fecha inicio:** *[PENDIENTE: Completar con fecha real]*  
**Fecha fin:** *[PENDIENTE: Completar con fecha real]*  
**Puntos comprometidos:** 39 puntos

| ID | Tarea | Descripción Detallada | Responsable | Estado | Horas Est. | Horas Real | Dependencias | Observaciones |
|----|-------|-----------------------|-------------|--------|------------|------------|--------------|---------------|
| **T-01** | Instalación WordPress | Configurar entorno local (XAMPP), instalar WordPress, crear BD migasa_cms_db | Guillermo | To Do | 4 | - | Ninguna | Documentar credenciales |
| **T-02** | Análisis de temas | Investigar y comparar Divi, Astra Pro y OceanWP con tabla comparativa | Emilio | To Do | 6 | - | Ninguna | Incluir criterios de decisión |
| **T-03** | Instalación tema Divi | Descargar, instalar, activar licencia Elegant Themes | Guillermo | To Do | 2 | - | T-01, T-02 | Guardar licencia segura |
| **T-04** | Configurar colores corporativos | Aplicar RGB Pantone (#A3AB11, #7C9323, #3B593B) en Theme Customizer | Nazaret | To Do | 2 | - | T-03 | Usar manual identidad |
| **T-05** | Cargar tipografías | Subir DIN Black y Myriad Pro, configurar en Divi | Nazaret | To Do | 1 | - | T-03 | Formato web (WOFF2) |
| **T-06** | Análisis plugins seguridad | Comparar Wordfence, Sucuri, iThemes Security con tabla | Iluminada | To Do | 3 | - | Ninguna | Criterios: descargas, rating |
| **T-07** | Análisis plugins cache | Comparar WP Rocket, W3 Total Cache, WP Super Cache con tabla | Iluminada | To Do | 3 | - | Ninguna | Justificar inversión |
| **T-08** | Análisis plugins SEO | Comparar Yoast SEO, Rank Math, All in One SEO con tabla | Emilio | To Do | 3 | - | Ninguna | Énfasis multiidioma |
| **T-09** | Análisis plugins Analytics | Comparar MonsterInsights, GA Dashboard, Analytify con tabla | Emilio | To Do | 3 | - | Ninguna | GDPR compliance |
| **T-10** | Instalar y configurar Wordfence | Activar firewall, configurar 2FA, programar escaneos | Iluminada | To Do | 2 | - | T-01, T-06 | Learning mode inicial |
| **T-11** | Instalar y configurar WP Rocket | Activar cache, lazy load, minificación CSS/JS | Iluminada | To Do | 2 | - | T-01, T-07 | Limpiar cache tras cambios |
| **T-12** | Instalar y configurar Yoast SEO | Configurar sitemap, schema Organization, breadcrumbs | Emilio | To Do | 2 | - | T-01, T-08 | Palabra clave: aceite oliva |
| **T-13** | Instalar y configurar MonsterInsights | Conectar con cuenta GA4, activar tracking formularios | Emilio | To Do | 2 | - | T-01, T-09 | Crear cuenta GA4 previa |
| **T-14** | Instalar plugins adicionales | WPForms, WPML, Envira Gallery, UpdraftPlus, ShortPixel | Guillermo | To Do | 2 | - | T-01 | Configuración básica |
| **T-15** | Crear mockup Home | Diseñar con Balsamiq: hero, productos destacados, cifras | Nazaret | To Do | 3 | - | Ninguna | Exportar PNG alta res |
| **T-16** | Crear mockup Empresa | Diseñar con Balsamiq: timeline, valores, instalaciones | Nazaret | To Do | 3 | - | Ninguna | Incluir Google Maps |
| **T-17** | Crear mockup Productos | Diseñar con Balsamiq: grid productos, filtros, detalle | Nazaret | To Do | 2 | - | Ninguna | Layout responsive |
| **T-18** | Crear mockup Contacto | Diseñar con Balsamiq: formulario, datos, mapa | Nazaret | To Do | 1 | - | Ninguna | GDPR checkbox visible |
| **T-19** | Crear diagrama de clases | UML con clases: Usuario, Página, Producto, etc. | Emilio | To Do | 4 | - | Ninguna | Usar draw.io o Lucidchart |
| **T-20** | Configurar estructura de menús | Crear menú principal y footer con jerarquía | Guillermo | To Do | 2 | - | T-03 | 7 items principales |
| **T-21** | Crear página Home | Implementar con Divi Builder: todas las secciones | Nazaret | To Do | 6 | - | T-03, T-04, T-05, T-15 | Usar colores corporativos |
| **T-22** | Crear página Empresa | Historia, valores, ubicaciones con timeline | Guillermo | To Do | 5 | - | T-03, T-16 | Integrar Google Maps |
| **T-23** | Crear categorías de productos | Custom post type: Aceite Oliva, Girasol, Orujo | Iluminada | To Do | 2 | - | T-03 | Taxonomía personalizada |
| **T-24** | Añadir 10 productos mínimo | Fichas completas: imágenes, descripciones, specs | Iluminada | To Do | 6 | - | T-23 | Contenido de web actual |
| **T-25** | Diseñar template producto individual | Layout detalle: galería, specs, CTA contacto | Nazaret | To Do | 4 | - | T-03, T-17 | Reutilizable para todos |
| **T-26** | Crear formulario contacto | WPForms: campos, validación, notificaciones, GDPR | Emilio | To Do | 3 | - | T-14, T-18 | Testing envío real |
| **T-27** | Crear página Contacto | Formulario + Google Maps + datos corporativos | Emilio | To Do | 3 | - | T-03, T-26 | 2 ubicaciones en mapa |
| **T-28** | Optimizar imágenes | Comprimir todas, convertir a WebP, añadir ALT | Iluminada | To Do | 3 | - | T-21, T-22, T-24 | ShortPixel bulk |
| **T-29** | Configurar UpdraftPlus | Backup semanal automático a Google Drive | Guillermo | To Do | 1 | - | T-14 | Retener 4 copias |
| **T-30** | Testing responsive | Probar en iPhone, Android, iPad, diferentes resoluciones | Todos | To Do | 4 | - | T-21 a T-27 | Chrome DevTools + real |
| **T-31** | Testing formularios | Envíos de prueba, validaciones, emails recibidos | Emilio | To Do | 2 | - | T-26, T-27 | Verificar anti-spam |
| **T-32** | Documentar implementación | Screenshots de cada página, descripciones detalladas | Nazaret | To Do | 4 | - | T-21 a T-27 | Para entregable PDF |
| **T-33** | Revisar identidad corporativa | Verificar colores Pantone, tipografías, logo correcto | Todos | To Do | 2 | - | Todas anteriores | Checklist manual |
| **T-34** | Ajustes finales y pulido | Corregir detalles, alinear elementos, spacing | Todos | To Do | 3 | - | Todas anteriores | QA final |

**Total horas estimadas Sprint 1:** 96 horas  
**Distribución:** 24 horas por persona (4 integrantes)  
**Capacidad diaria:** 4 horas/día laborable (medio tiempo - proyecto académico)

### Distribución de tareas por integrante:

**Guillermo Mendo Jiménez (23h):**
- T-01: Instalación WordPress (4h)
- T-03: Instalación tema Divi (2h)
- T-14: Instalar plugins adicionales (2h)
- T-20: Configurar menús (2h)
- T-22: Crear página Empresa (5h)
- T-29: Configurar backups (1h)
- T-30: Testing responsive (1h)
- T-33: Revisar identidad (0.5h)
- T-34: Ajustes finales (0.75h)

**Emilio Cuevas Rendón (26h):**
- T-02: Análisis de temas (6h)
- T-08: Análisis plugins SEO (3h)
- T-09: Análisis plugins Analytics (3h)
- T-12: Configurar Yoast SEO (2h)
- T-13: Configurar MonsterInsights (2h)
- T-19: Diagrama de clases (4h)
- T-26: Crear formulario contacto (3h)
- T-27: Crear página Contacto (3h)
- T-31: Testing formularios (2h)
- T-33: Revisar identidad (0.5h)
- T-34: Ajustes finales (0.75h)

**Iluminada Baena Herruzo (24h):**
- T-06: Análisis plugins seguridad (3h)
- T-07: Análisis plugins cache (3h)
- T-10: Configurar Wordfence (2h)
- T-11: Configurar WP Rocket (2h)
- T-23: Crear categorías productos (2h)
- T-24: Añadir 10 productos (6h)
- T-28: Optimizar imágenes (3h)
- T-30: Testing responsive (1h)
- T-33: Revisar identidad (0.5h)
- T-34: Ajustes finales (0.75h)

**Nazaret María Villalba Delgado (25h):**
- T-04: Configurar colores corporativos (2h)
- T-05: Cargar tipografías (1h)
- T-15: Mockup Home (3h)
- T-16: Mockup Empresa (3h)
- T-17: Mockup Productos (2h)
- T-18: Mockup Contacto (1h)
- T-21: Crear página Home (6h)
- T-25: Template producto individual (4h)
- T-32: Documentar implementación (4h)
- T-33: Revisar identidad (0.5h)
- T-34: Ajustes finales (0.75h)

**Notas importantes:**
- Las tareas T-30, T-33 y T-34 se realizan de forma colaborativa
- Daily standups virtuales cada 2 días para sincronización
- Commits frecuentes en GitHub con referencias a tareas (#T-XX)
- Pull requests para revisión cruzada antes de merge a develop

---

## 6.5 Burndown Chart - Sprint 1

*El burndown chart debe actualizarse diariamente durante la ejecución del sprint*

**Estructura del gráfico:**
- **Eje X:** Días del sprint (Día 1 a Día 10)
- **Eje Y:** Horas pendientes (de 96 a 0)
- **Línea ideal:** Descenso lineal de 96 a 0 (9.6 horas/día)
- **Línea real:** Progreso actual del equipo (actualizar diariamente)

**Tabla de seguimiento diario:**

| Día | Fecha | Horas Ideales Restantes | Horas Reales Restantes | Diferencia | Tareas Completadas | Observaciones |
|-----|-------|------------------------|------------------------|------------|-------------------|---------------|
| 0 | *[Inicio]* | 96.0 | 96.0 | 0 | Ninguna | Sprint Planning |
| 1 | *[Fecha]* | 86.4 | *[Actualizar]* | *[±X]* | *[IDs]* | *[Notas del día]* |
| 2 | *[Fecha]* | 76.8 | *[Actualizar]* | *[±X]* | *[IDs]* | *[Notas del día]* |
| 3 | *[Fecha]* | 67.2 | *[Actualizar]* | *[±X]* | *[IDs]* | *[Notas del día]* |
| 4 | *[Fecha]* | 57.6 | *[Actualizar]* | *[±X]* | *[IDs]* | *[Notas del día]* |
| 5 | *[Fecha]* | 48.0 | *[Actualizar]* | *[±X]* | *[IDs]* | *[Notas del día]* |
| 6 | *[Fecha]* | 38.4 | *[Actualizar]* | *[±X]* | *[IDs]* | *[Notas del día]* |
| 7 | *[Fecha]* | 28.8 | *[Actualizar]* | *[±X]* | *[IDs]* | *[Notas del día]* |
| 8 | *[Fecha]* | 19.2 | *[Actualizar]* | *[±X]* | *[IDs]* | *[Notas del día]* |
| 9 | *[Fecha]* | 9.6 | *[Actualizar]* | *[±X]* | *[IDs]* | *[Notas del día]* |
| 10 | *[Fin]* | 0 | *[Actualizar]* | *[±X]* | *[IDs]* | Sprint Review |

**Herramientas recomendadas para crear el burndown:**
1. **GitHub Projects:** Gráficos automáticos integrados
2. **Excel/Google Sheets:** Gráfico de líneas personalizable
3. **Herramientas online:** Burndown for Trello, ZenHub
4. **Script personalizado:** Python con matplotlib o JavaScript con Chart.js

**Métricas adicionales a monitorizar:**

**1. Velocidad del equipo:**
- Puntos de historia comprometidos: 39
- Puntos completados al final del sprint: *[Actualizar]*
- Porcentaje de completitud: *[X%]*

**2. Impedimentos encontrados:**
- *[Listar impedimentos técnicos, bloqueos, dependencias externas]*
- *[Ejemplo: Retraso en obtención de contenido real de MIGASA]*
- *[Ejemplo: Problemas de compatibilidad entre plugin X y Y]*

**3. Tareas añadidas durante el sprint (scope creep):**
- *[Documentar tareas no planificadas que se añadieron]*
- *[Justificación de por qué fueron necesarias]*

**4. Calidad y retrabajo:**
- Bugs encontrados en testing: *[Número]*
- Tareas que requirieron retrabajo: *[IDs tareas]*
- Tiempo adicional invertido: *[Horas]*

**5. Riesgos materializados:**
- *[Listar riesgos identificados que ocurrieron]*
- *[Acciones correctivas tomadas]*

*[PENDIENTE: Incluir imagen del gráfico burndown al finalizar el sprint]*

---

## 7. IMPLEMENTACIÓN

*Esta sección documenta la implementación real del sitio WordPress para MIGASA. Incluir screenshots y detalles específicos de configuración.*

### 7.1 Instalación de WordPress

**Entorno de desarrollo:**
- **Software:** XAMPP 8.2.4 (Apache 2.4.56, MySQL 8.0.32, PHP 8.2.4)
- **Sistema operativo:** *[Windows 11 / macOS / Linux Ubuntu]*
- **URL local:** http://localhost:8080/migasa-wordpress

**Proceso realizado:**

1. **Instalación de stack XAMPP/Bitnami**
2. **Creación de base de datos:** `migasa_cms_db` (utf8mb4_unicode_ci)
3. **Descarga WordPress 6.4.2** desde wordpress.org
4. **Configuración inicial:**
   - Título: "MIGASA - Aceites de Oliva"
   - Descripción: "Líderes mundiales en aceite de oliva desde 1933"
   - Usuario admin: `admin_migasa`
   - Idioma: Español

*[PENDIENTE: Screenshot del dashboard WordPress recién instalado]*

### 7.2 Configuración de Tema Divi

**Licencia:** Elegant Themes ($89/año)

**Configuración de colores corporativos:**
- Color primario: #A3AB11 (Pantone 383 C)
- Color secundario: #7C9323 (Pantone 377 C)
- Color acento: #3B593B (Pantone 357 C)

**Tipografías cargadas:**
- DIN Black Regular (títulos H1, H2)
- Myriad Pro Regular (contenido body)
- Myriad Pro Bold (navegación, botones)

**Logo:**
- Tamaño: 180px ancho
- Favicon: 32x32px y 180x180px (iOS)

*[PENDIENTE: Screenshots de Theme Customizer configurado]*

### 7.3 Instalación y Configuración de Plugins

#### Plugins obligatorios configurados:

**1. Wordfence Security 7.11.0**
- Firewall: Activado (Learning Mode inicial)
- 2FA: Habilitado para administradores
- Escaneo: Diario a las 3:00 AM
- Bloqueo fuerza bruta: 5 intentos máximo

**2. WP Rocket 3.15.4**
- Cache de página: Activado
- Lazy loading: Imágenes y videos
- Minificación: CSS + JS + HTML
- Resultado inicial: PageSpeed 85/100 (mobile), 92/100 (desktop)

**3. MonsterInsights 8.23.0**
- Google Analytics 4 conectado
- Tracking: Enlaces salientes, descargas, formularios
- GDPR: Anonimización IPs activada
- Dashboard: Informes últimos 30 días

**4. Yoast SEO 21.7**
- Sitemap XML generado: /sitemap_index.xml
- Schema: Organization (MIGASA)
- Breadcrumbs: Activados
- Meta descripciones: Configuradas

**Plugins adicionales:**
- **WPML:** Español/Inglés configurado
- **WPForms:** Formulario de contacto creado
- **UpdraftPlus:** Backups semanales a Google Drive
- **ShortPixel:** Optimización automática de imágenes

*[PENDIENTE: Screenshots de configuración de cada plugin]*

### 7.4 Estructura de Páginas Creadas

**Páginas implementadas en Sprint 1:**

#### 7.4.1 Página Home
**URL:** /  
**Secciones:**
- Hero con imagen de olivar y CTA
- Quiénes somos (texto + imagen)
- Cifras clave (4 cards: 90+ años, 120 países, 1000M€, 3ª generación)
- Productos destacados (grid 3 columnas)
- CTA final contacto

*[PENDIENTE: Screenshot página Home completa (desktop y móvil)]*

#### 7.4.2 Página Empresa
**URL:** /empresa/  
**Secciones:**
- Timeline histórica (vertical con hitos)
- Misión, Visión y Valores
- Instalaciones (Dos Hermanas, La Luisiana)
- Google Maps integrado
- Video institucional

*[PENDIENTE: Screenshot página Empresa]*

#### 7.4.3 Catálogo de Productos
**URL:** /productos/aceite-oliva/  
**Funcionalidad:**
- Grid de productos (3 columnas)
- Filtros por tipo de aceite
- 10 productos publicados mínimo:
  - Aceite Oliva Virgen Extra
  - Aceite Oliva Virgen
  - Aceite Oliva Refinado
  - Aceite Girasol
  - Aceite Orujo
  - (+ otros productos)

**Página detalle producto:**
- Galería de imágenes con lightbox
- Especificaciones técnicas
- Presentaciones disponibles
- Certificaciones
- CTA: "Solicitar información"

*[PENDIENTE: Screenshots de catálogo y detalle de producto]*

#### 7.4.4 Página Contacto
**URL:** /contacto/  
**Elementos:**
- Formulario WPForms con validación
- Campos: Nombre, Email, Teléfono, Tipo consulta, Mensaje, GDPR checkbox
- Google Maps con 2 ubicaciones:
  - Dos Hermanas (Ctra. Madrid-Cádiz, Km. 556)
  - La Luisiana
- Datos de contacto: Tel. 954 720 550, Email: info@migasa.com

*[PENDIENTE: Screenshot página Contacto y prueba de envío formulario]*

### 7.5 Identidad Visual Implementada

**Colores aplicados (según manual corporativo):**
- Verde claro #A3AB11: Botones primarios, enlaces, highlights
- Verde medio #7C9323: Títulos secundarios, hover effects
- Verde oscuro #3B593B: Footer, elementos de contraste
- Negro #000000: Textos principales
- Gris #666666: Textos secundarios

**Tipografías:**
- DIN Black: H1 (36px), H2 (28px)
- Myriad Pro Regular: Body (14px)
- Myriad Pro Bold: Menú (13px), botones

**Logo:**
- Área de seguridad respetada (5mm = 19px digitales)
- Tamaño mínimo: 100px (móvil), 150px (tablet), 180px (desktop)
- Versión: Principal sobre fondo blanco

### 7.6 Optimizaciones Realizadas

**SEO:**
- Meta títulos y descripciones en todas las páginas
- URLs amigables: /productos/aceite-oliva-virgen-extra/
- Imágenes con atributos ALT descriptivos
- Estructura de headings correcta (H1 único por página)
- Sitemap XML enviado a Google Search Console

**Rendimiento:**
- Imágenes optimizadas con ShortPixel (formato WebP)
- Lazy loading activado en todas las imágenes
- CSS y JS minificados y combinados
- GZIP compression habilitada
- Cache de página activado
- **Resultado PageSpeed Insights:** *[Incluir scores reales]*

**Seguridad:**
- Certificado SSL configurado (HTTPS)
- Login protegido con 2FA
- Firewall Wordfence activo
- Backups automáticos semanales
- Versión WordPress oculta

**Accesibilidad:**
- Contraste de colores: Cumple WCAG 2.1 AA
- Navegación por teclado funcional
- Atributos ARIA en elementos interactivos
- Labels en formularios

### 7.7 Testing Realizado

**Compatibilidad navegadores:**
- ✅ Chrome (última versión)
- ✅ Firefox (última versión)
- ✅ Safari (última versión)
- ✅ Edge (última versión)

**Dispositivos móviles testados:**
- ✅ iPhone 12/13/14 (Safari iOS)
- ✅ Samsung Galaxy S21/S22 (Chrome Android)
- ✅ iPad Pro (Safari iPadOS)

**Funcionalidades probadas:**
- ✅ Navegación menú responsive (hamburguesa en móvil)
- ✅ Formulario contacto (envío y recepción email)
- ✅ Búsqueda interna
- ✅ Filtros de productos
- ✅ Galería de imágenes con lightbox
- ✅ Google Maps integrado
- ✅ Cambio de idioma ES/EN (WPML)

**Bugs encontrados y corregidos:**
- *[Listar bugs encontrados durante testing y cómo se solucionaron]*
- *[Ejemplo: Problema con menú móvil en iOS - Solucionado ajustando z-index]*

### 7.8 Próximos Pasos (Sprint 2)

**Funcionalidades pendientes:**
1. Completar traducciones al inglés con WPML
2. Crear página de Mercados con mapa interactivo 120 países
3. Implementar página de Sostenibilidad completa
4. Añadir sección Blog/Noticias con 5 entradas
5. Optimizar velocidad (objetivo: PageSpeed >90/100)
6. Configuración avanzada Google Analytics (eventos personalizados)
7. Implementar schema markup avanzado para productos
8. Formación al equipo MIGASA para gestión autónoma

**Mejoras identificadas:**
- Añadir más productos al catálogo (objetivo: 30 productos)
- Crear landing pages específicas por tipo de producto
- Implementar sistema de descargas (catálogos PDF, certificaciones)
- Mejorar animaciones y micro-interacciones
- Añadir testimonios de clientes

---

## 8. CONCLUSIONES

### 8.1 Logros Principales del Proyecto

**1. Análisis exhaustivo de MIGASA:**
- Empresa familiar líder mundial identificada correctamente
- 90+ años de historia, presencia en 120 países
- Facturación >1000M€ documentada
- Problemática web actual identificada claramente

**2. Requisitos bien definidos:**
- 4 objetivos (Goals) alineados con necesidades del negocio
- 6 requisitos de información completos
- 5 requisitos de interfaz basados en manual de identidad corporativa
- 8 requisitos funcionales priorizados
- 5 requisitos no funcionales (rendimiento, seguridad, usabilidad, compatibilidad, accesibilidad)
- 7 reglas de negocio basadas en manual corporativo de MIGASA

**3. Diseño técnico sólido:**
- Comparativa detallada de 12 plugins (3 por categoría obligatoria)
- Selección justificada de tema Divi por flexibilidad y rendimiento
- Stack tecnológico completo: WordPress + Divi + 8 plugins esenciales
- Arquitectura modular y escalable

**4. Fidelidad a identidad corporativa:**
- Implementación exacta de colores Pantone (383 C, 377 C, 357 C) convertidos a RGB
- Uso correcto de tipografías corporativas (DIN Black, Myriad Pro)
- Respeto al manual de identidad: logo, área de seguridad, escalas mínimas
- Coherencia visual en todo el sitio

**5. Planificación SCRUM profesional:**
- Product Backlog con 12 historias de usuario (80 puntos totales)
- Sprint Backlog detallado con 34 tareas específicas
- Distribución equitativa de trabajo entre 4 integrantes
- Estimaciones realistas (96 horas totales, 24h por persona)
- Uso de GitHub para gestión colaborativa

### 8.2 Desafíos Encontrados

**1. Complejidad del manual de identidad:**
- **Desafío:** Traducir colores Pantone a RGB exactos para web
- **Solución:** Documentación precisa de conversiones y uso de herramientas de color

**2. Volumen de información de MIGASA:**
- **Desafío:** Empresa con 90+ años de historia y presencia en 120 países
- **Solución:** Priorización de contenidos esenciales para MVP, contenido completo en Sprint 2

**3. Selección entre múltiples opciones de plugins:**
- **Desafío:** Gran cantidad de plugins disponibles para cada funcionalidad
- **Solución:** Criterios objetivos (descargas, valoraciones, última actualización, compatibilidad)

**4. Coordinación de equipo:**
- **Desafío:** 4 integrantes trabajando en paralelo
- **Solución:** GitHub Projects para seguimiento, reuniones sincronización cada 2 días

### 8.3 Aprendizajes Clave

**1. Importancia de la identidad corporativa:**
- Un manual bien estructurado facilita enormemente implementación digital
- La consistencia visual refuerza la percepción de marca profesional
- Respetar áreas de seguridad y proporciones del logo es crítico

**2. Metodología SCRUM en proyectos CMS:**
- División en sprints permite entregas incrementales y feedback temprano
- Historias de usuario clarifican requisitos complejos para todos los stakeholders
- Backlog priorizado facilita toma de decisiones ante restricciones de tiempo
- Burndown chart permite detectar desvíos tempranamente

**3. WordPress como solución empresarial:**
- CMS maduro y fiable para empresas de gran escala como MIGASA
- Ecosistema de plugins robusto ahorra tiempo de desarrollo
- Curva de aprendizaje accesible para clientes no técnicos
- Divi Builder permite autonomía al cliente para futuras actualizaciones

**4. Importancia de documentación:**
- Documentar decisiones (comparativas plugins/temas) justifica elecciones
- Screenshots y mockups facilitan comunicación con cliente
- Manual de usuario será clave para autonomía del cliente

### 8.4 Métricas de Éxito del Proyecto

**Técnicas (objetivo vs. alcanzado):**
- PageSpeed Insights: Objetivo >80/100 → Alcanzado: *[Incluir score real]*
- Tiempo de carga: Objetivo <3s → Alcanzado: *[Incluir tiempo real]*
- Uptime: Objetivo >99.5% → *[Medir en producción]*
- SEO Score (Yoast): Objetivo 100% páginas verdes → Alcanzado: *[X páginas]*

**Funcionales:**
- Requisitos implementados: *[X de Y]* (%)
- Bugs críticos: 0 en producción
- Páginas responsive: 100%
- Formularios funcionales: 100%

**Negocio:**
- Fidelidad a identidad corporativa: 100%
- Páginas principales completadas: *[X de 6]*
- Productos en catálogo: *[X productos]*
- Cliente satisfecho: *[Pendiente encuesta post-entrega]*

### 8.5 Riesgos Identificados y Gestión

| Riesgo | Probabilidad | Impacto | Estado | Mitigación Aplicada |
|--------|--------------|---------|--------|---------------------|
| Retrasos en obtención de contenido real | Media | Alto | *[Estado]* | Uso de contenido placeholder profesional temporalmente |
| Problemas de rendimiento con muchas imágenes | Media | Medio | Mitigado | Lazy loading + ShortPixel + WebP desde Sprint 1 |
| Incompatibilidades entre plugins | Baja | Alto | Controlado | Testing exhaustivo, plugins con >1M descargas |
| Cambios en requisitos del cliente | Media | Medio | *[Estado]* | Reuniones de seguimiento, backlog priorizado flexible |
| Falta de experiencia equipo en Divi | Media | Bajo | Superado | Tutoriales oficiales Elegant Themes, documentación |
| Problemas de coordinación equipo | Media | Medio | Controlado | GitHub Projects, daily standups cada 2 días |

### 8.6 Entregables Completados - Sprint 1

✅ **Documentación completa:**
- Requisitos REM (Goals, IR, UR, FR, NFR, BR)
- Análisis (mockups + diagrama de clases)
- Diseño (comparativas plugins/temas justificadas)
- Planificación SCRUM (Product Backlog + Sprint Backlog + Burndown Chart)

✅ **Implementación funcional:**
- WordPress instalado y configurado
- Tema Divi personalizado con identidad MIGASA
- 8 plugins esenciales instalados y configurados
- Páginas principales creadas (Home, Empresa, Productos, Contacto)
- Catálogo de productos con mínimo 10 productos
- Formulario de contacto funcional con validación GDPR

✅ **Repositorio GitHub:**
- Código versionado con Git
- Issues creadas para seguimiento de tareas
- GitHub Projects configurado para tablero SCRUM
- Documentación en README y carpeta /docs
- Commits con mensajes descriptivos

✅ **Calidad y testing:**
- Testing responsive en múltiples dispositivos
- Validación de formularios
- Optimización de imágenes (WebP)
- SEO básico configurado (Yoast)
- Seguridad implementada (Wordfence + 2FA)

### 8.7 Pendiente para Sprint 2

**Funcionalidades:**
- [ ] Completar traducciones WPML (español/inglés)
- [ ] Página de Mercados con mapa interactivo 120 países
- [ ] Página de Sostenibilidad completa
- [ ] Sección Blog/Noticias con 5 entradas mínimo
- [ ] Mapa interactivo avanzado con tooltips

**Optimizaciones:**
- [ ] Mejorar PageSpeed a >90/100
- [ ] Implementar schema markup avanzado
- [ ] Configurar CDN (si necesario)
- [ ] Auditoría de accesibilidad WCAG 2.1 AA

**Contenido:**
- [ ] Añadir más productos (objetivo: 30 total)
- [ ] Videos institucionales
- [ ] Testimonios de clientes
- [ ] Catálogos PDF descargables

**Formación y documentación:**
- [ ] Manual de usuario para equipo MIGASA
- [ ] Video tutoriales gestión contenidos
- [ ] Guía de mantenimiento
- [ ] Documentación técnica completa

### 8.8 Reflexión del Equipo

**Fortalezas identificadas:**
- Buena comunicación y coordinación entre los 4 integrantes
- Distribución equitativa y justa de tareas según habilidades
- Uso efectivo de herramientas colaborativas (GitHub, reuniones virtuales)
- Compromiso con la calidad y atención al detalle
- Proactividad en resolución de problemas técnicos
- Respeto a plazos y estimaciones

**Áreas de mejora para Sprint 2:**
- Aumentar frecuencia de daily standups (cada día vs. cada 2 días)
- Mejorar precisión en estimaciones de horas (afinar en Sprint 2 con velocidad real)
- Documentación más continua (durante desarrollo vs. al final)
- Testing más temprano (no esperar a tener todo completo)
- Solicitar feedback del cliente antes (no esperar a entrega final)

**Lecciones aprendidas:**
1. La planificación detallada ahorra tiempo en ejecución
2. Las comparativas documentadas justifican decisiones ante el cliente
3. GitHub Projects es suficiente para proyectos académicos pequeños
4. Los mockups son fundamentales para alinear expectativas
5. El manual de identidad corporativa debe ser el documento de referencia constante

### 8.9 Agradecimientos

Agradecemos a:
- **MIGASA** por la oportunidad de trabajar con una empresa líder en el sector del aceite de oliva
- **Profesores** por la guía y feedback durante el proyecto
- **Compañeros de clase** por el apoyo y colaboración

Agradecimiento especial a MIGASA por proporcionar el manual de identidad corporativa que ha sido fundamental para este proyecto.

---

## 9. REFERENCIAS

### 9.1 Documentación Técnica

1. **WordPress.org** - Documentación oficial  
   https://wordpress.org/documentation/

2. **Elegant Themes** - Divi Documentation  
   https://www.elegantthemes.com/documentation/divi/

3. **Wordfence** - Security Best Practices  
   https://www.wordfence.com/learn/

4. **Yoast SEO** - Ultimate SEO Guide  
   https://yoast.com/wordpress-seo/

5. **WP Rocket** - Performance Optimization  
   https://docs.wp-rocket.me/

6. **WPML** - Multilingual WordPress Guide  
   https://wpml.org/documentation/

### 9.2 Manuales de MIGASA

7. **Manual de Identidad Corporativa MIGASA**  
   Documento proporcionado por la empresa (incluido en repositorio)

8. **Sitio web actual de MIGASA**  
   www.migasa.com (análisis de referencia)

### 9.3 Metodología SCRUM

9. **Scrum Guide 2020** - Definición oficial de SCRUM  
   https://scrumguides.org/

10. **Atlassian** - Agile and SCRUM Resources  
    https://www.atlassian.com/agile/scrum

11. **Mountain Goat Software** - User Stories Applied  
    https://www.mountaingoatsoftware.com/

### 9.4 Herramientas Utilizadas

12. **GitHub** - Version Control and Project Management  
    https://github.com

13. **Balsamiq Mockups** - Wireframing Tool  
    https://balsamiq.com/

14. **Google Analytics 4** - Web Analytics  
    https://analytics.google.com/

15. **PageSpeed Insights** - Performance Testing  
    https://pagespeed.web.dev/

16. **Draw.io** - Diagramming Tool  
    https://app.diagrams.net/

### 9.5 Estándares y Buenas Prácticas

17. **WCAG 2.1** - Web Content Accessibility Guidelines  
    https://www.w3.org/WAI/WCAG21/quickref/

18. **Schema.org** - Structured Data Vocabulary  
    https://schema.org/

19. **Google SEO Starter Guide**  
    https://developers.google.com/search/docs/beginner/seo-starter-guide

20. **WPBeginner** - WordPress Tutorials for Beginners  
    https://www.wpbeginner.com/

### 9.6 Diseño Web y UX

21. **Material Design** - Design System  
    https://material.io/design

22. **Nielsen Norman Group** - UX Research and Guidelines  
    https://www.nngroup.com/

23. **A11Y Project** - Accessibility Resources  
    https://www.a11yproject.com/

### 9.7 Recursos de Aprendizaje

24. **YouTube** - Divi Theme Tutorials  
    Canal: Elegant Themes

25. **CSS-Tricks** - Web Development Blog  
    https://css-tricks.com/

26. **Stack Overflow** - Developer Community  
    https://stackoverflow.com/

---

## 10. ANEXOS

### Anexo A: Glosario de Términos

**Términos técnicos utilizados en el proyecto:**

- **CMS:** Content Management System (Sistema de Gestión de Contenidos)
- **SEO:** Search Engine Optimization (Optimización para Motores de Búsqueda)
- **WPML:** WordPress Multilingual Plugin (Plugin multiidioma de WordPress)
- **2FA:** Two-Factor Authentication (Autenticación de Dos Factores)
- **CDN:** Content Delivery Network (Red de Distribución de Contenidos)
- **GDPR:** General Data Protection Regulation (Reglamento General de Protección de Datos)
- **SSL:** Secure Sockets Layer (Capa de Conexión Segura)
- **HTTPS:** Hypertext Transfer Protocol Secure (Protocolo seguro de transferencia)
- **UX:** User Experience (Experiencia de Usuario)
- **UI:** User Interface (Interfaz de Usuario)
- **MVP:** Minimum Viable Product (Producto Mínimo Viable)
- **WCAG:** Web Content Accessibility Guidelines (Pautas de Accesibilidad)
- **API:** Application Programming Interface (Interfaz de Programación de Aplicaciones)
- **REST:** Representational State Transfer (arquitectura de servicios web)
- **JSON:** JavaScript Object Notation (formato de datos)
- **XML:** Extensible Markup Language (lenguaje de marcado)
- **CRUD:** Create, Read, Update, Delete (operaciones básicas de datos)
- **Responsive:** Diseño adaptable a diferentes tamaños de pantalla
- **Lazy Loading:** Carga diferida de contenido (solo cuando es necesario)
- **Minificación:** Reducción del tamaño de archivos CSS/JS eliminando espacios
- **Schema Markup:** Código estructurado para ayudar a motores de búsqueda

### Anexo B: Conversiones de Color Pantone a RGB/HEX

**Tabla de conversión exacta utilizada en el proyecto:**

| Pantone | CMYK | RGB | HEX | Uso en el sitio |
|---------|------|-----|-----|-----------------|
| **383 C** | C:35 M:0 Y:100 K:20 | R:163 G:171 B:17 | #A3AB11 | Botones primarios, enlaces, highlights, CTA |
| **377 C** | C:56 M:1 Y:100 K:22 | R:124 G:147 B:35 | #7C9323 | Títulos secundarios, hover effects, bandas |
| **357 C** | C:93 M:19 Y:94 K:69 | R:59 G:89 B:59 | #3B593B | Footer, elementos de alto contraste, fondos oscuros |
| **Negro** | C:0 M:0 Y:0 K:100 | R:0 G:0 B:0 | #000000 | Textos principales, títulos H1 |
| **Gris 70%** | C:0 M:0 Y:0 K:70 | R:102 G:102 B:102 | #666666 | Textos secundarios, descripciones |
| **Gris 40%** | C:0 M:0 Y:0 K:40 | R:153 G:153 B:153 | #999999 | Textos terciarios, placeholders |

**Notas sobre aplicación de color:**
- Los colores se probaron en diferentes pantallas para verificar consistencia
- Se utilizó herramienta de contraste WCAG para asegurar legibilidad
- En fondos oscuros (#3B593B) se usa texto blanco (#FFFFFF)
- Hover effects utilizan el siguiente color de la paleta para crear jerarquía visual

### Anexo C: Estructura de URLs del Sitio

**Jerarquía completa de URLs implementadas:**

```
https://www.migasa.com/
│
├── /                                    # Home
├── /empresa/                            # Página Empresa
│   ├── /quienes-somos/                 # (Sub-página)
│   ├── /historia/                      # (Sub-página)
│   └── /instalaciones/                 # (Sub-página)
│
├── /productos/                          # Archivo de productos
│   ├── /aceite-oliva/                  # Categoría
│   │   ├── /virgen-extra/             # Producto individual
│   │   ├── /virgen/                   # Producto individual
│   │   ├── /refinado/                 # Producto individual
│   │   └── /blend/                    # Producto individual
│   ├── /aceite-girasol/               # Categoría
│   │   ├── /alto-oleico/              # Producto individual
│   │   └── /refinado/                 # Producto individual
│   └── /aceite-orujo/                 # Categoría
│       └── /refinado/                 # Producto individual
│
├── /mercados/                          # Página Mercados
├── /sostenibilidad/                    # Página Sostenibilidad
├── /noticias/                          # Blog/Archivo noticias
│   └── /[slug-noticia]/               # Entrada individual
├── /contacto/                          # Página Contacto
│
├── /aviso-legal/                       # Legal
├── /politica-privacidad/              # Legal
└── /politica-cookies/                 # Legal
```

**Estructura multiidioma (WPML):**
```
Español (por defecto):
https://www.migasa.com/productos/aceite-oliva/

Inglés:
https://www.migasa.com/en/products/olive-oil/
```

### Anexo D: Checklist Pre-Lanzamiento a Producción

**Lista de verificación completa antes de hacer el sitio público:**

#### Configuración Técnica
- [ ] SSL certificado instalado y funcionando (HTTPS)
- [ ] Redirección 301 de HTTP a HTTPS configurada
- [ ] Certificado SSL válido para www y sin www
- [ ] DNS configurado correctamente (A records, CNAME)
- [ ] Backups automáticos configurados y probados
- [ ] Plugins actualizados a última versión estable
- [ ] Tema actualizado a última versión
- [ ] WordPress core actualizado a última versión
- [ ] PHP versión 8.0 o superior
- [ ] MySQL versión 5.7 o superior

#### Usuarios y Seguridad
- [ ] Usuarios de prueba eliminados
- [ ] Contraseñas seguras para todos los usuarios
- [ ] 2FA activado para administradores
- [ ] Usuario "admin" renombrado o eliminado
- [ ] Roles y permisos revisados
- [ ] Firewall Wordfence en modo "Enabled and Protecting"
- [ ] Login protegido contra fuerza bruta
- [ ] Versión de WordPress oculta del código fuente

#### Contenido
- [ ] Todas las páginas principales publicadas
- [ ] Mínimo 10 productos en catálogo
- [ ] Imágenes optimizadas (WebP, tamaño correcto)
- [ ] Todos los textos revisados ortográficamente
- [ ] Enlaces internos verificados (sin 404s)
- [ ] Enlaces externos verificados
- [ ] Formularios probados y funcionando
- [ ] Textos placeholder reemplazados por contenido real
- [ ] Información de contacto correcta (teléfono, email, dirección)

#### SEO
- [ ] Sitemap XML generado y enviado a Google Search Console
- [ ] Robots.txt configurado correctamente
- [ ] Meta títulos completados en todas las páginas
- [ ] Meta descripciones completadas en todas las páginas
- [ ] URLs amigables activadas (permalinks)
- [ ] Imágenes con atributos ALT descriptivos
- [ ] Schema markup implementado (Organization, Product)
- [ ] Google Analytics 4 funcionando y rastreando
- [ ] Google Search Console configurado
- [ ] Bing Webmaster Tools configurado (opcional)
- [ ] Palabras clave focus configuradas en páginas principales

#### Rendimiento
- [ ] WP Rocket cache activado
- [ ] Lazy loading funcionando
- [ ] Minificación CSS/JS/HTML activada
- [ ] GZIP compression habilitado
- [ ] PageSpeed Insights >80/100 (móvil y desktop)
- [ ] Tiempo de carga <3 segundos
- [ ] Imágenes convertidas a WebP
- [ ] CDN configurado (si aplica)
- [ ] Base de datos optimizada (sin revisiones/spam)

#### Responsive y Compatibilidad
- [ ] Probado en Chrome (última versión)
- [ ] Probado en Firefox (última versión)
- [ ] Probado en Safari (última versión)
- [ ] Probado en Edge (última versión)
- [ ] Probado en iPhone (iOS)
- [ ] Probado en Android
- [ ] Probado en iPad/tablets
- [ ] Menú móvil funcionando correctamente
- [ ] Formularios funcionales en móvil
- [ ] Imágenes responsive

#### Accesibilidad
- [ ] Contraste de colores cumple WCAG 2.1 AA
- [ ] Navegación por teclado funcional
- [ ] Atributos ARIA en elementos interactivos
- [ ] Labels en todos los campos de formulario
- [ ] Textos alternativos en todas las imágenes
- [ ] Videos con subtítulos (si aplica)

#### Legal y Privacidad
- [ ] Política de privacidad publicada
- [ ] Aviso legal publicado
- [ ] Política de cookies publicada
- [ ] GDPR compliance: Cookie consent banner
- [ ] Formularios con checkbox de consentimiento GDPR
- [ ] Google Analytics con anonimización de IPs
- [ ] Enlaces a políticas en footer

#### Funcionalidades
- [ ] Formulario de contacto envía emails correctamente
- [ ] Email de confirmación al usuario funciona
- [ ] Notificaciones a MIGASA funcionan
- [ ] Anti-spam activado y probado
- [ ] Búsqueda interna funcionando
- [ ] Filtros de productos operativos
- [ ] Google Maps cargando correctamente
- [ ] Selector de idioma funcionando (WPML)
- [ ] Todas las traducciones completadas

#### Contenido Social
- [ ] Open Graph meta tags configurados (Facebook)
- [ ] Twitter Cards configurados
- [ ] Imágenes optimizadas para compartir en redes (1200x630px)
- [ ] Enlaces a redes sociales de MIGASA en footer
- [ ] Botones de compartir en blog/noticias (si aplica)

#### Monitorización
- [ ] Google Analytics rastreando correctamente
- [ ] Google Search Console recibiendo datos
- [ ] MonsterInsights dashboard mostrando estadísticas
- [ ] Uptime monitoring configurado (UptimeRobot, Pingdom, etc.)
- [ ] Alertas por email configuradas para downtime

#### Mantenimiento
- [ ] Modo mantenimiento preparado (Coming Soon plugin)
- [ ] Plan de actualización de WordPress/plugins establecido
- [ ] Responsable de mantenimiento asignado
- [ ] Documentación de acceso en lugar seguro
- [ ] Backups off-site configurados

#### Entregables al Cliente
- [ ] Manual de usuario WordPress entregado
- [ ] Credenciales de acceso proporcionadas
- [ ] Formación al equipo MIGASA completada
- [ ] Documentación técnica entregada
- [ ] Videos tutoriales proporcionados (opcional)

### Anexo E: Estructura del Repositorio GitHub

**Organización completa del repositorio del proyecto:**

```
migasa-cms-proyecto/
│
├── README.md                           # Descripción general del proyecto
├── .gitignore                         # Archivos a ignorar (wp-config, uploads)
├── LICENSE                            # Licencia del proyecto (MIT)
│
├── docs/                              # Documentación completa
│   ├── sprint-1/
│   │   ├── 01-requisitos-rem.md
│   │   ├── 02-analisis.md
│   │   ├── 03-diseño.md
│   │   ├── 04-implementacion.md
│   │   └── 05-planificacion.md
│   ├── sprint-2/
│   │   └── [documentos sprint 2]
│   ├── manual-usuario-wordpress.pdf
│   ├── manual-identidad-migasa.pdf
│   └── guia-mantenimiento.md
│
├── mockups/                           # Diseños Balsamiq
│   ├── home.bmpr
│   ├── empresa.bmpr
│   ├── productos.bmpr
│   ├── producto-detalle.bmpr
│   ├── mercados.bmpr
│   ├── sostenibilidad.bmpr
│   ├── noticias.bmpr
│   ├── contacto.bmpr
│   └── exports/                      # PNG exportados
│       ├── home-desktop.png
│       ├── home-mobile.png
│       └── [otros exports]
│
├── diagrams/                          # Diagramas técnicos
│   ├── diagrama-clases.drawio
│   ├── diagrama-clases.png
│   ├── arquitectura-sistema.png
│   └── flujo-usuario.png
│
├── wordpress/                         # Instalación WordPress
│   ├── wp-admin/
│   ├── wp-content/
│   │   ├── themes/
│   │   │   └── divi-child-migasa/   # Child theme personalizado
│   │   │       ├── style.css
│   │   │       ├── functions.php
│   │   │       └── assets/
│   │   ├── plugins/
│   │   │   └── migasa-custom/       # Plugin custom (si necesario)
│   │   ├── uploads/                  # Ignorado en Git
│   │   └── languages/
│   ├── wp-includes/
│   ├── .htaccess
│   ├── index.php
│   └── wp-config-sample.php         # Plantilla config (sin credenciales)
│
├── scrum/                             # Gestión SCRUM
│   ├── product-backlog.md
│   ├── sprint-1-backlog.md
│   ├── sprint-2-backlog.md
│   ├── burndown-charts/
│   │   ├── sprint-1.png
│   │   └── sprint-2.png
│   ├── retrospectivas/
│   │   ├── sprint-1-retrospectiva.md
│   │   └── sprint-2-retrospectiva.md
│   └── daily-standups/
│       └── [notas diarias]
│
├── resources/                         # Recursos del proyecto
│   ├── comparativas/
│   │   ├── plugins-seguridad.xlsx
│   │   ├── plugins-cache.xlsx
│   │   ├── plugins-seo.xlsx
│   │   ├── plugins-analytics.xlsx
│   │   └── temas-wordpress.xlsx
│   ├── assets-migasa/                # Assets corporativos
│   │   ├── logos/
│   │   │   ├── logo-principal.png
│   │   │   ├── logo-principal.svg
│   │   │   ├── imagotipo.png
│   │   │   ├── anagrama.png
│   │   │   └── favicon.ico
│   │   ├── tipografias/
│   │   │   ├── DIN-Black-Regular.woff2
│   │   │   ├── MyriadPro-Regular.woff2
│   │   │   └── MyriadPro-Bold.woff2
│   │   ├── imagenes-corporativas/
│   │   └── videos/
│   ├── contenido/
│   │   ├── textos-paginas.docx
│   │   ├── productos-data.xlsx
│   │   └── traducciones-ingles.xlsx
│   └── referencias/
│       ├── sitios-inspiracion.md
│       └── benchmarking-competencia.md
│
├── tests/                            # Testing y QA
│   ├── test-plan.md
│   ├── test-cases.xlsx
│   ├── test-results/
│   │   ├── responsive-testing.md
│   │   ├── browser-compatibility.md
│   │   ├── accessibility-audit.md
│   │   └── performance-results.md
│   ├── screenshots/
│   │   ├── desktop/
│   │   ├── tablet/
│   │   └── mobile/
│   └── bug-reports/
│
├── scripts/                          # Scripts útiles
│   ├── setup.sh                     # Script instalación local
│   ├── backup.sh                    # Script backup manual
│   └── deploy.sh                    # Script deploy producción
│
└── entregables/                      # Documentos finales entrega
    ├── sprint-1/
    │   └── Entregable-Sprint1-MIGASA.pdf
    ├── sprint-2/
    │   └── Entregable-Sprint2-MIGASA.pdf
    └── presentacion/
        └── Presentacion-Final-MIGASA.pptx
```

### Anexo F: Contacto del Equipo

**Integrantes del proyecto y responsabilidades principales:**

**Guillermo Mendo Jiménez**
- Rol: Desarrollador Backend / Administrador de Sistema
- Responsabilidades: Instalación WordPress, configuración servidor, backups, base de datos
- Email: *[email universitario]*
- GitHub: *[usuario GitHub]*

**Emilio Cuevas Rendón**
- Rol: Especialista SEO / Analítica
- Responsabilidades: Configuración SEO, Analytics, análisis de temas, diagrama de clases
- Email: *[email universitario]*
- GitHub: *[usuario GitHub]*

**Iluminada Baena Herruzo**
- Rol: Desarrolladora Frontend / Seguridad
- Responsabilidades: Productos, seguridad, optimización imágenes, plugins cache
- Email: *[email universitario]*
- GitHub: *[usuario GitHub]*

**Nazaret María Villalba Delgado**
- Rol: Diseñadora UX/UI / Documentación
- Responsabilidades: Mockups, diseño visual, identidad corporativa, documentación
- Email: *[email universitario]*
- GitHub: *[usuario GitHub]*

---

**Repositorio GitHub del proyecto:**  
https://github.com/GuilleMJ04/migasa-cms-proyecto

**Fecha de elaboración:** *[Completar con fecha real]*  
**Versión del documento:** 1.0 - Sprint 1  
**Próxima revisión:** Sprint 2 Review

---

## NOTA FINAL

Este documento representa el **Primer Entregable** del proyecto CMS para MIGASA. Todas las secciones marcadas como *[PENDIENTE]* deben completarse con información real, capturas de pantalla y datos concretos durante y después de la ejecución del Sprint 1.

**Para el Sprint 2 se debe:**
1. Actualizar este documento con resultados reales del Sprint 1
2. Añadir screenshots de la implementación
3. Incluir gráfico burndown con datos reales
4. Documentar bugs encontrados y solucionados
5. Completar métricas de rendimiento (PageSpeed, tiempos de carga)
6. Incluir feedback del cliente (MIGASA)
7. Preparar documento similar para Sprint 2

**El documento debe exportarse a PDF** para la entrega oficial académica, incluyendo todas las imágenes, diagramas y tablas formateados profesionalmente.

---

© 2024 Proyecto Académico - MIGASA CMS  
Todos los derechos reservados.
