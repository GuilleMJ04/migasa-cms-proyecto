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
| **iThemes Security** | Actualización continua | 1M+ | ★★★★☆ (4.6/5) | • Más de 50 formas de protección<br>• Autenticación de dos factores<br>• Forzar contraseñas fuertes<br>• Detección de cambios en archivos<br>• Programación de escaneos | ❌
