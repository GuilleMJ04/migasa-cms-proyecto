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

*Los mockups deben crearse con Balsamiq u otra herramienta de diseño y adjuntarse como imágenes en el documento final*

#### 4.1.1 Página Principal (Home)

**Descripción del mockup:** 
- Header con logo MIGASA (respetando área de seguridad 5mm)
- Menú de navegación principal horizontal
- Hero section con imagen destacada de olivar/producción
- Texto principal: "Líderes mundiales en aceite de oliva desde 1933"
- Sección "Quiénes somos" (90+ años de historia, empresa familiar)
- Grid de productos destacados (3 columnas)
- Cifras clave en cards: 
  - 90+ años de historia
  - 120 países
  - 1000M€ facturación
  - 3ª generación familiar
- Call-to-action principal: "Descubre nuestra historia"
- Sección de sostenibilidad
- Footer con datos de contacto, redes sociales y enlaces legales

**Elementos principales:**
- Colores corporativos: Pantone 383 C, 377 C, 357 C
- Tipografía: DIN Black (títulos H1, H2), Myriad Pro (contenido, navegación)
- Espaciado generoso y diseño limpio
- Imágenes de alta calidad de productos y olivares

*[PENDIENTE: Incluir imagen del mockup de la página principal]*

#### 4.1.2 Página de Empresa

**Descripción:** Página institucional que cuenta la historia y valores de MIGASA

**Secciones principales:**
- Hero con imagen corporativa y título "Nuestra Historia"
- Timeline interactiva: desde fundación (años 30) hasta actualidad
- Sección "Tercera Generación" con foto familiar
- Misión, Visión y Valores en cards con iconos
- "Nuestras Instalaciones":
  - Dos Hermanas (refinería aceites oliva y semillas)
  - La Luisiana (refinería aceite orujo y girasol)
- Mapa con ubicaciones
- Video institucional embebido
- Cifras clave y presencia internacional
- CTA: "Conoce nuestros productos"

**Elementos de diseño:**
- Timeline vertical con puntos de hito
- Tarjetas (cards) para valores
- Galería de imágenes de instalaciones
- Integración Google Maps

*[PENDIENTE: Incluir imagen del mockup de la página Empresa]*

#### 4.1.3 Página de Productos - Aceite de Oliva

**Descripción:** Catálogo de productos organizado y filtrable

**Estructura:**
- Breadcrumbs: Inicio > Productos > Aceite de Oliva
- Título principal: "Aceite de Oliva"
- Texto introductorio sobre el aceite de oliva de MIGASA
- Sidebar izquierdo con:
  - Filtros por tipo (Virgen Extra, Virgen, Refinado, Blend)
  - Filtros por presentación (envase)
  - Certificaciones
- Grid de productos (3 columnas) con:
  - Imagen del producto
  - Nombre
  - Breve descripción
  - Botón "Ver detalles"

**Página detalle de producto:**
- Galería de imágenes (lightbox)
- Nombre y descripción completa
- Especificaciones técnicas (tabla)
- Presentaciones disponibles
- Certificaciones y sellos
- Información nutricional
- CTA: "Solicitar información" (enlace a formulario)
- Productos relacionados

**Elementos de diseño:**
- Grid responsive (3 col desktop, 2 tablet, 1 móvil)
- Hover effects en tarjetas de producto
- Colores verdes corporativos en botones

*[PENDIENTE: Incluir imagen del mockup de página de productos]*

#### 4.1.4 Página de Mercados

**Descripción:** Visualización de la presencia internacional de MIGASA

**Elementos:**
- Hero: "Presencia en más de 120 países"
- Mapa interactivo mundial con markers
- Filtro por continente
- Click en marker muestra:
  - Nombre del país
  - Años de presencia
  - Tipo de productos vendidos
  - Datos de contacto local (si aplica)
- Sección "Nuestros principales mercados":
  - Europa
  - América
  - Asia
  - África
  - Oceanía
- Testimonios de clientes internacionales (carrusel)
- Estadísticas de exportación

*[PENDIENTE: Incluir imagen del mockup de página Mercados]*

#### 4.1.5 Página de Sostenibilidad

**Descripción:** Compromiso ambiental y responsabilidad social corporativa

**Contenido:**
- Hero: "Compromiso con el medio ambiente"
- Introducción sobre filosofía sostenible de MIGASA
- Secciones principales:
  - **Prácticas sostenibles:**
    - Gestión responsable del agua
    - Eficiencia energética
    - Economía circular
  - **Certificaciones ambientales:**
    - ISO 14001
    - Otras certificaciones (mostrar sellos)
  - **Proyectos actuales:**
    - Reducción huella carbono
    - Energías renovables
    - Residuo cero
  - **Objetivos de Desarrollo Sostenible (ODS):**
    - ODS relacionados con su actividad
- Timeline de logros ambientales
- Informes de sostenibilidad descargables (PDF)

**Elementos de diseño:**
- Iconografía relacionada con sostenibilidad
- Colores verdes corporativos reforzando el mensaje
- Infografías de datos

*[PENDIENTE: Incluir imagen del mockup de página Sostenibilidad]*

#### 4.1.6 Página de Contacto

**Descripción:** Formulario de contacto y datos corporativos

**Elementos principales:**
- Título: "Contacta con nosotros"
- Formulario WPForms (lado izquierdo):
  - Nombre y Apellidos* (campo requerido)
  - Email* (campo requerido con validación)
  - Teléfono
  - Tipo de consulta* (dropdown): 
    - Consulta general
    - Información de productos
    - Consulta comercial
    - Prensa y comunicación
  - Mensaje* (textarea, requerido)
  - Checkbox GDPR* (consentimiento tratamiento datos)
  - Botón "Enviar" (color verde corporativo)

- Datos de contacto (lado derecho):
  - **Oficinas y Fábrica:**
    - Dirección: Ctra. Madrid-Cádiz, Km. 556
    - Código Postal: 41703 Dos Hermanas (Sevilla), España
    - Teléfono: +34 954 720 550
    - Fax: +34 954 729 552
    - Email: info@migasa.com
    - Web: www.migasa.com
  - Horario de atención
  - Enlaces a redes sociales

- Google Maps integrado (parte inferior):
  - 2 markers: Dos Hermanas y La Luisiana
  - Opción cambiar entre ubicaciones

**Elementos de diseño:**
- Layout 2 columnas (desktop)
- Formulario con validación visual
- Iconos para datos de contacto

*[PENDIENTE: Incluir imagen del mockup de página Contacto]*

### 4.2 Diagrama de Clases

*Diagrama UML que representa la estructura del sitio WordPress para MIGASA*

**Clases principales identificadas:**

#### Clase: Usuario
**Atributos:**
- id: Integer
- nombre: String
- email: String
- rol: Enum (administrador, editor, autor, suscriptor)
- fecha_registro: DateTime

**Métodos:**
- login()
- logout()
- cambiarContraseña()
- gestionarContenido()
- asignarRol()

#### Clase: Página
**Atributos:**
- id: Integer
- título: String
- contenido: Text
- slug: String
- fecha_publicación: DateTime
- autor_id: Integer
- estado: Enum (publicado, borrador, revisión)
- plantilla: String

**Métodos:**
- publicar()
- editar()
- eliminar()
- cambiarEstado()
- obtenerURL()

#### Clase: Menú
**Atributos:**
- id: Integer
- nombre: String
- ubicación: String (principal, footer, móvil)
- orden: Integer
- url: String
- página_padre_id: Integer

**Métodos:**
- mostrarNavegación()
- generarBreadcrumbs()
- ordenarItems()
- actualizarJerarquía()

#### Clase: CategoríaProducto
**Atributos:**
- id: Integer
- nombre: String (Aceite Oliva, Aceite Girasol, Aceite Orujo)
- descripción: Text
- slug: String
- orden: Integer

**Métodos:**
- listarProductos()
- contarProductos()
- obtenerURL()

#### Clase: Producto
**Atributos:**
- id: Integer
- nombre: String
- tipo_aceite: String
- descripción: Text
- descripción_corta: String
- imagen_principal: String
- galería_imágenes: Array
- especificaciones_técnicas: JSON
- presentaciones: Array
- certificaciones: Array
- precio: Decimal (opcional)
- categoría_id: Integer
- fecha_creación: DateTime
- estado: Enum (publicado, borrador)

**Métodos:**
- mostrarDetalle()
- filtrarPorTipo()
- buscar()
- obtenerGalería()
- listarPresentaciones()

**Relaciones:**
- Pertenece a CategoríaProducto (N:1)

#### Clase: FormularioContacto
**Atributos:**
- id: Integer
- nombre: String
- email: String
- teléfono: String
- tipo_consulta: Enum (general, productos, comercial, prensa)
- mensaje: Text
- consentimiento_gdpr: Boolean
- fecha_envío: DateTime
- ip_usuario: String
- estado: Enum (nuevo, leído, respondido)

**Métodos:**
- validarCampos()
- enviarEmail()
- guardarEnBD()
- generarNotificación()
- verificarAntispam()

#### Clase: Noticia
**Atributos:**
- id: Integer
- título: String
- contenido: Text
- extracto: Text
- imagen_destacada: String
- fecha_publicación: DateTime
- autor_id: Integer
- categoría: String
- tags: Array
- estado: Enum (publicado, borrador)

**Métodos:**
- publicar()
- archivar()
- programarPublicación()
- obtenerRelacionadas()

#### Clase: MediaBiblioteca
**Atributos:**
- id: Integer
- nombre_archivo: String
- url: String
- tipo_mime: String
- tamaño: Integer
- dimensiones: String
- texto_alternativo: String
- fecha_subida: DateTime

**Métodos:**
- subir()
- optimizar()
- eliminar()
- generarMiniaturas()

### Relaciones entre clases:

```
Usuario (1) ─── gestiona ─── (N) Página
Usuario (1) ─── gestiona ─── (N) Producto
Usuario (1) ─── gestiona ─── (N) Noticia
Página (1) ─── tiene ─── (1) Menú
Producto (N) ─── pertenece a ─── (1) CategoríaProducto
Producto (N) ─── utiliza ─── (N) MediaBiblioteca
Noticia (N) ─── utiliza ─── (N) MediaBiblioteca
FormularioContacto (N) ─── envía a ─── (1) Usuario
```

*[PENDIENTE: Incluir diagrama UML visual creado con herramienta como draw.io, Lucidchart o similar]*

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

3. **Milestones:**
   - Sprint 1 y Sprint 2 como milestones
   - Agrupación de issues por sprint
   - Porcentaje de completitud visible
   - Fechas de inicio y fin

4. **GitHub Wiki:**
   - Documentación del proyecto
   - Guías de instalación y configuración
   - Estándares de código
   - Manual de usuario

**Comparativa con alternativas:**

| Herramienta | Ventajas | Desventajas | Decisión |
|-------------|----------|-------------|----------|
| **GitHub Projects** | Integrado con Git, gratuito, todo en uno | Funciones SCRUM básicas | ✅ Seleccionado |
| **Trello** | Interfaz visual intuitiva, fácil de usar | Separado del código, limitado gratuito | ❌ Descartado |
| **Jira** | SCRUM robusto, reporting avanzado | Costoso, complejo para proyecto pequeño | ❌ Descartado |
| **Asana** | Gestión tareas potente, vistas múltiples | No integrado con Git, pago para equipos | ❌ Descartado |

### 6.2 Control de Versiones

**Sistema seleccionado:** Git con GitHub como repositorio remoto

**Justificación:**
- **Estándar de la industria:** Sistema de control de versiones más utilizado mundialmente
- **Trabajo colaborativo eficiente:** Branching y merging facilitan desarrollo paralelo
- **Historial completo:** Registro detallado de todos los cambios (quién, qué, cuándo, por qué)
- **Backup automático:** Código siempre respaldado en la nube
- **Reversión sencilla:** Posibilidad de volver a versiones anteriores ante errores
- **Resolución de conflictos:** Herramientas visuales para merge conflicts

**Estructura del repositorio:**

```
migasa-cms-proyecto/
├── README.md                           # Descripción general del proyecto
├── .gitignore                         # Archivos a ignorar (wp-config.php, uploads)
├── docs/                              # Documentación del proyecto
│   ├── sprint-1/
│   │   ├── 01-requisitos-rem.md
│   │   ├── 02-analisis.md
│   │   ├── 03-diseño.md
│   │   ├── 04-implementacion.md
│   │   └── 05-planificacion.md
│   ├── sprint-2/
│   ├── manual-usuario.md
│   └── manual-identidad-migasa.pdf
├── mockups/                           # Diseños y prototipos
│   ├── home.bmpr
│   ├── empresa.bmpr
│   ├── productos.bmpr
│   ├── mercados.bmpr
│   ├── sostenibilidad.bmpr
│   └── contacto.bmpr
├── diagrams/                          # Diagramas UML y técnicos
│   ├── diagrama-clases.png
│   └── arquitectura-sistema.png
├── wordpress/                         # Instalación WordPress
│   ├── wp-content/
│   │   ├── themes/
│   │   │   └── divi-child-migasa/    # Child theme personalizado
│   │   ├── plugins/
│   │   │   └── migasa-custom/        # Plugin custom si necesario
│   │   └── uploads/                   # (ignorado en .gitignore)
│   ├── wp-config-sample.php          # Plantilla configuración
│   └── .htaccess
├── scrum/                             # Documentos SCRUM
│   ├── product-backlog.md
│   ├── sprint-1-backlog.md
│   ├── sprint-2-backlog.md
│   └── burndown-charts/
│       ├── sprint-1.png
│       └── sprint-2.png
├── resources/                         # Recursos adicionales
│   ├── comparativas-plugins.xlsx
│   ├── comparativas-temas.xlsx
│   ├── assets-migasa/                # Logos, imágenes corporativas
│   └── documentacion-empresa/
└── tests/                            # Tests y validaciones
    ├── test-plan.md
    └── test-results/
```

**Flujo de trabajo Git (Git Flow simplificado):**

**Ramas principales:**
- `main`: Código en producción, siempre estable
- `develop`: Rama de desarrollo, integración continua

**Ramas de funcionalidad:**
- `feature/nombre-funcionalidad`: Para cada nueva característica
- `bugfix/nombre-bug`: Para corrección de errores
- `hotfix/nombre-critico`: Para fixes urgentes en producción

**Convención de commits:**
```
tipo(ámbito): descripción breve

- feat: Nueva funcionalidad
- fix: Corrección de bug
- docs: Cambios en documentación
- style: Cambios de formato (sin afectar código)
- refactor: Refactorización de código
- test: Añadir o modificar tests
- chore: Tareas de mantenimiento

Ejemplos:
feat(productos): añadir filtro por tipo de aceite
fix(formulario): corregir validación email
docs(readme): actualizar instrucciones instalación
style(home): ajustar colores corporativos Pantone
```

### 6.3 Product Backlog

**Total puntos Product Backlog:** 80 puntos  
**Velocidad estimada:** 40 puntos por sprint (2 semanas cada uno)

| ID | Historia de Usuario | Descripción Detallada | Criterios de Aceptación | Prioridad | Puntos | Sprint |
|----|--------------------|-----------------------|------------------------|-----------|--------|---------|
| **PBI-01** | Como visitante, quiero navegar fácilmente por el sitio | Implementar menú responsive con estructura jerárquica clara y breadcrumbs | • Menú visible en todas las páginas<br>• Hamburguesa en móvil funcional<br>• Breadcrumbs en todas las páginas internas<br>• Navegación intuitiva (máximo 3 clics) | Alta | 8 | Sprint 1 |
| **PBI-02** | Como administrador, quiero gestionar contenido fácilmente | Configurar WordPress con roles, permisos y Divi Builder | • Dashboard WordPress intuitivo<br>• Roles definidos (admin/editor)<br>• Divi Builder configurado y funcional<br>• Documentación de uso entregada | Alta | 5 | Sprint 1 |
| **PBI-03** | Como visitante, quiero ver productos de aceite | Catálogo de productos con filtros por tipo y ficha detallada | • Mínimo 10 productos publicados<br>• Filtro por tipo de aceite funcional<br>• Ficha detallada con specs técnicas<br>• Imágenes de alta calidad | Alta | 13 | Sprint 1 |
| **PBI-04** | Como visitante, quiero contactar con MIGASA | Formulario funcional con validación y notificaciones email | • Campos obligatorios validados<br>• Email confirmación a usuario<br>• Notificación a MIGASA funcional<br>• Anti-spam activo (Akismet)<br>• GDPR checkbox obligatorio | Alta | 3 | Sprint 1 |
| **PBI-05** | Como visitante, quiero un sitio rápido | Optimizar rendimiento con cache, compresión y lazy loading | • PageSpeed Insights >80/100<br>• Tiempo de carga <3 segundos<br>• Lazy loading activado<br>• Imágenes optimizadas (WebP) | Media | 5 | Sprint 1 |
| **PBI-06** | Como administrador, quiero analizar el tráfico | Integrar Google Analytics 4 y configurar Yoast SEO | • GA4 conectado y rastreando<br>• Dashboard MonsterInsights funcional<br>• Yoast SEO configurado (sitemap, meta)<br>• Search Console vinculado | Media | 3 | Sprint 2 |
| **PBI-07** | Como visitante móvil, quiero acceso completo | Diseño 100% responsive y optimizado para táctil | • Funcional en iOS y Android<br>• Menú táctil optimizado<br>• Formularios mobile-friendly<br>• Imágenes adaptativas<br>• Testing en dispositivos reales | Alta | 8 | Sprint 2 |
| **PBI-08** | Como visitante internacional, quiero el sitio en inglés | Implementar multiidioma español/inglés con WPML | • Todo el contenido traducido<br>• Selector de idioma visible<br>• URLs por idioma (/es/, /en/)<br>• Menús traducidos<br>• SEO multiidioma optimizado | Media | 8 | Sprint 2 |
| **PBI-09** | Como visitante, quiero conocer la historia de MIGASA | Página "Empresa" con timeline interactiva y valores | • Timeline con hitos históricos<br>• Sección 90 años de historia<br>• Fotos de familia/instalaciones<br>• Video institucional embebido<br>• Misión, visión y valores | Media | 5 | Sprint 2 |
| **PBI-10** | Como visitante, quiero ver la presencia internacional | Mapa interactivo con los 120 países donde opera MIGASA | • Mapa mundial con markers<br>• Info tooltip por país/región<br>• Datos de presencia por continente<br>• Responsive en móvil | Baja | 8 | Sprint 2 |
| **PBI-11** | Como administrador, quiero seguridad robusta | Configurar firewall, 2FA, SSL y backups automáticos | • Wordfence activo y escaneando<br>• 2FA obligatorio para admin<br>• Backups semanales automáticos<br>• SSL certificado configurado<br>• Login protegido contra fuerza bruta | Alta | 5 | Sprint 1 |
| **PBI-12** | Como visitante, quiero leer noticias del sector | Blog/área de noticias actualizable con categorías | • Mínimo 5 entradas publicadas<br>• Categorías definidas<br>• RSS feed generado<br>• Botones compartir en redes<br>• Comentarios (opcional) | Baja | 5 | Sprint 2 |

**Priorización:**
- **Alta prioridad (Sprint 1):** Funcionalidades core (navegación, productos, contacto, seguridad)
- **Media prioridad (Sprint 2):** Optimizaciones y contenido adicional (analytics, multiidioma, historia)
- **Baja prioridad:** Nice-to-have (mapa interactivo, blog)

### 6.4 Sprint Backlog - Sprint 1

**Objetivo del Sprint:** Establecer la base funcional del sitio WordPress con diseño responsive, catálogo de productos, formulario de contacto y medidas de seguridad, todo respetando la identidad corporativa de MIGASA.

**Duración:** 2 semanas (10 días laborables)  
**Fecha inicio:** *[PENDIENTE: Completar con fecha real]*  
**Fecha fin:** *[PENDIENTE: Completar con fecha real]*  
**Puntos comprometidos:** 39 puntos

| ID | Tarea | Descripción Detallada | Responsable | Estado | Horas Est. | Horas Real | Dependencias | Observaciones |
|----|-------|-----------------------|-------------|--------|------------|------------|--------------|---------------|
| **T-01** | Instalación WordPress | Configurar entorno local (XAMPP), instalar WordPress, crear base de datos migasa_cms_db | Guillermo | To Do | 4 | - | Ninguna | Documentar credenciales |
| **T-02** | Análisis de temas | Investigar y comparar Divi, Astra Pro y OceanWP con tabla comparativa | Emilio | To Do | 6 | - | Ninguna | Incluir criterios de decisión |
| **T-03** | Instalación tema Divi | Descargar, instalar, activar licencia Elegant Themes | Guillermo | To Do | 2 | - | T-01, T-02 | Guardar licencia segura |
| **T-04** | Configurar colores corporativos | Aplicar RGB Pantone (#A3AB11, #7C9323, #3B593B) en Theme Customizer | Nazaret | To Do | 2 | - | T-03 | Usar manual identidad |
| **T-05** | Cargar tipografías | Subir DIN Black y Myriad Pro, configurar en Divi | Nazaret | To Do | 1 | - | T-03 | Formato web (WOFF2) |
| **T-06** | Análisis plugins seguridad | Comparar Wordfence, Sucuri, iThemes Security con tabla | Iluminada | To Do | 3 | - | Ninguna | Criterios: descargas, rating, features |
| **T-07** | Análisis
