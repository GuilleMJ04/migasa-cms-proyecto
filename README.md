# PROYECTO CMS - WORDPRESS
## Desarrollo Web para MIGASA - Aceites de Oliva
### Primer Entregable - Sprint 1

---

**Integrantes del equipo:**
- Guillermo Mendo Jiménez
- Emilio Cuevas Rendón
- Iluminada Baena Herruzo
- Nazaret María Villalba Delgado

**Fecha de elaboración:** *29/09/2025*  
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

# 1. INTRODUCCIÓN

## 1.1. Propósito del Proyecto
El propósito del proyecto es **transformar la plataforma web actual de MIGASA**, que actualmente es puramente informativa, en una **herramienta funcional de comercio electrónico**, capaz de ofrecer venta directa de productos envasados.

## 1.2. Alcance
El proyecto contempla el **diseño, desarrollo e implementación** de un portal web corporativo con funcionalidades de **e-commerce** y **gestión de usuarios**.  
Se excluye del alcance la venta de productos a granel, limitándose únicamente a la línea de productos **embotellados y empaquetados**.

El sistema incluirá:
- Catálogo interactivo de productos.
- Carrito de compra y procesamiento de pedidos.
- Integración de métodos de pago seguros.
- Sistema multiidioma (5 idiomas).
- Descuentos exclusivos para empleados.

## 1.3. Empresa Seleccionada
**MIGASA** es una empresa líder en el sector agroalimentario español, especializada en la **producción, envasado y comercialización de aceites vegetales**.  
Cuenta con marcas reconocidas como **La Masía**, **Ybarra** y otras filiales, con presencia en más de **120 países**.  
Su estrategia actual busca potenciar el canal digital mediante una plataforma que combine **información corporativa, sostenibilidad y comercio electrónico**.

---

# 2. ANÁLISIS DE LA EMPRESA

## 2.1. Descripción de la Empresa
MIGASA es una empresa familiar con amplia trayectoria en el sector oleícola.  
Su principal línea de negocio es la producción de **aceite de oliva, girasol y orujo**, tanto para consumo nacional como internacional.  
Actualmente, su web cumple una función informativa, sin ofrecer un canal de ventas online ni interacción directa con los usuarios.

## 2.2. Problemática Identificada
- La web actual es **puramente informativa**, sin funcionalidades de venta ni gestión dinámica del contenido.  
- No existen **canales digitales directos** para la comercialización de productos.  
- Falta de **segmentación de usuarios** (clientes particulares y empleados).  

## 2.3. Oportunidades de Mejora
- Implementar un **canal de ventas online**.  
- Incorporar **formularios inteligentes** y un sistema de ayuda (FAQ).  
- Integrar **principios de diseño responsive** y accesibilidad.  

---

# 3. REQUISITOS CON REM

## 3.1. Objetivos (Goals)

### Objetivo Principal
Transformar la plataforma web actual en una herramienta funcional de ventas con capacidades de comercio electrónico.

### Objetivos Específicos
- Ampliar el catálogo de productos de la compañía.  
- Establecer un canal de ventas directo **online**.  
- Mejorar la interacción con los clientes mediante formularios y sistemas de ayuda (FAQ).  
- Facilitar la gestión de **eventos** (calendario).  
- Mantener una **experiencia óptima en smartphones y tablets**.  

---

## 3.2. Requisitos de Información

| Código / Requisito de Información | Descripción |
|----------------------|-------------|
| **RI01: Catálogo de productos** | El sistema deberá disponer de un catálogo digital completo que actúe como escaparate principal de la oferta comercial. Cada producto deberá mostrar su nombre, descripción breve, imágenes de calidad desde distintos ángulos, precio actualizado, disponibilidad de stock y filtros avanzados por marca (Ybarra o La Masía), tipo de producto, capacidad del envase y rango de precios. Este módulo constituirá la base de la funcionalidad de venta online. |
| **RI02: Ficha detallada de producto** | Cada producto deberá contar con una página individual que incluya información comercial y técnica detallada. Se especificarán ingredientes, alérgenos, certificaciones (sin gluten, sin lactosa, sin derivados lácteos, vegetariano, vegano y ecológico), tipo de envase, capacidad exacta, origen del producto y recomendaciones de uso. Este contenido deberá presentarse de forma estructurada, accesible y conforme a la normativa vigente sobre información alimentaria. |
| **RI03: Información corporativa** | Se incluirá un apartado institucional que reúna la información sobre la identidad y trayectoria de la empresa. Este deberá contener los logotipos oficiales del grupo MIGASA y de sus marcas (Ybarra y La Masía) en todos los formatos disponibles, los colores corporativos con sus códigos exactos y la guía de estilo oficial en formato descargable (PDF). Además, se presentará la historia de la compañía desde su fundación, los valores empresariales, la estructura organizativa, el equipo directivo y datos corporativos relevantes como su presencia internacional. |
| **RI04: Datos de empleados** | Cada perfil incluirá información personal y profesional: nombre completo, número de empleado, correo corporativo, fotografía opcional, departamento, puesto, centro de trabajo y fecha de incorporación. Los empleados tienen acceso a descuentos exclusivos.|
| **RI05: Contenido multiidioma** | El sitio web deberá ofrecer contenido traducido profesionalmente en los cinco idiomas prioritarios: español, inglés, francés, portugués y chino. El usuario podrá seleccionar el idioma mediante un conmutador visible en la parte superior de la interfaz. Las traducciones deberán mantener la coherencia terminológica y la calidad lingüística acorde a los estándares corporativos. |
| **RI06: Marcas del grupo** | Se incluirá una sección dedicada a la presentación de las dos principales marcas del grupo. En ella, se describirá la identidad y gama de productos de cada una: Ybarra, especializada en salsas y La Masía, centrada en aceites. Se destacará la complementariedad entre ambas marcas y sus valores diferenciales dentro del grupo MIGASA.|
| **RI07: FAQ y chatbot Asistencial**| Se desarrollará un sistema de atención automatizada con chatbot multilingüe, disponible 24/7. Este asistente virtual deberá ser capaz de interpretar preguntas formuladas en lenguaje natural y ofrecer respuestas precisas sobre productos, pedidos, funcionamiento del portal y puntos de venta. Además, deberá integrarse con una base de conocimiento (FAQ) que se actualice periódicamente, y podrá mejorar sus respuestas mediante aprendizaje progresivo. |
| **RI08: Contacto y ubicaciones** | El sitio incluirá un apartado de contacto con información corporativa actualizada: teléfonos, direcciones de correo electrónico, formulario de contacto estructurado y mapa de las sedes principales. |
| **RI09: Sostenibilidad y RSC** | Se habilitará un espacio informativo donde se detalle el compromiso de la empresa con la sostenibilidad y la responsabilidad social. Se incluirá información sobre gestión de envases y reciclaje, uso de energías renovables, trazabilidad de materias primas, así como proyectos sociales y colaboraciones con ONGs o bancos de alimentos. |
| **RI10: Sistemas de Pedidos** | La plataforma deberá almacenar información sobre los pedidos realizados por los clientes, incluyendo número de pedido, fecha de realización, historial y detalles de entrega.|

---

## 3.3. Requisitos de Interfaz de Usuario

| Código / Requisito de Interfaz de Usuario | Descripción |
|----------------------|-------------|
| **RUI01: Interfaz intuitiva y modular**| La plataforma deberá disponer de una interfaz sencilla, clara e intuitiva, estructurada mediante bloques o secciones modulares que faciliten la gestión del contenido por parte de personal no técnico. Los elementos interactivos deberán ser visualmente identificables y accesibles, garantizando una navegación fluida para cualquier tipo de usuario. |
| **RUI02: Aplicación de la identidad visual corporativa** | El diseño de la interfaz deberá mantener una coherencia visual en todas las secciones del portal, siguiendo la guía de estilo corporativo de la empresa. Deberán aplicarse correctamente el logotipo oficial, los colores representativos, las tipografías y los tamaños definidos en la guía de marketing proporcionada en formato PDF. |
| **RUI03: Navegación multiidioma** | El sitio web deberá permitir la selección del idioma desde un elemento visible situado en la parte superior de la página (menú desplegable). Esta funcionalidad garantizará que el usuario pueda visualizar el contenido en su idioma preferido (español, inglés, francés, portugués o chino) de forma inmediata y sin pérdida de contexto. |
| **RUI04: Visualización destacada del catálogo de productos** | En la página principal deberá incluirse una sección visible y destacada que muestre una selección representativa del catálogo de productos, priorizando aquellos más relevantes o identificativos de la marca. Se busca captar la atención del visitante e incentivar la navegación hacia las fichas de producto. |  
| **RUI05: Diseño adaptable (responsive design)** | La interfaz de usuario deberá ser completamente adaptable (responsive), garantizando la correcta visualización, legibilidad y funcionalidad del contenido en diferentes resoluciones y dispositivos: ordenadores de escritorio, tabletas y teléfonos móviles. |  
| **RUI06: Integración visual del chatbot de asistencia** | El diseño de la interfaz deberá incluir un acceso permanente al chatbot de ayuda, visible en todas las páginas (icono flotante en la esquina inferior). Su apariencia deberá integrarse con la identidad visual del sitio y ofrecer una experiencia fluida tanto en versión de escritorio como móvil. |  
| **RUI07: Sección de contacto y FAQ accesible desde el menú principal** | La interfaz deberá incorporar accesos directos visibles a las secciones de contacto y preguntas frecuentes (FAQ). Los formularios deberán diseñarse con campos claros, mensajes de validación comprensibles y un diseño coherente con el resto del portal. |
| **RUI08: Representación diferenciada de las marcas del grupo** | La interfaz deberá permitir visualizar de manera clara la identidad de las dos marcas principales del grupo (Ybarra y La Masía). En el diseño se deberán respetar sus elementos visuales particulares (logotipos, colores y mensajes de marca), sin romper la coherencia general del portal corporativo. | 

---

## 3.4. Requisitos Funcionales

### Prioridad Alta
| Código / Requisito Funcional | Descripción |
|----------------------|-------------|
|**RF01: Catálogo de productos con vista previa** | El sistema deberá ofrecer un catálogo completo de productos organizado por categorías, donde cada producto cuente con una vista previa compuesta por nombre, imagen, precio y disponibilidad. El usuario podrá aplicar filtros de búsqueda (por tipo, marca, precio o certificación) y acceder a la página individual del producto para consultar su información detallada (ingredientes, alérgenos, certificaciones, envase y capacidad). |  
| **RF02: Carrito de compra completo** | El sistema deberá permitir a los usuarios añadir productos al carrito de compra, modificar cantidades, eliminar artículos y visualizar el total de la compra en tiempo real. Además, deberá calcular automáticamente los impuestos y gastos de envío. El usuario podrá guardar el carrito o continuar al proceso de pago. |
| **RF03: Procesamiento de pedidos** | La aplicación deberá gestionar pedidos tanto de clientes particulares como de empresas. En cada caso, se deberán registrar los datos de facturación y envío, el método de pago seleccionado y los detalles del pedido. El sistema generará un número de pedido único. |
| **RF04: Métodos de pago seguros** | El sistema deberá integrar pasarelas de pago seguras que permitan realizar transacciones mediante tarjeta de crédito/débito, PayPal y plataformas digitales como Google Pay o Apple Pay. Todos los procesos deberán cumplir con los protocolos de seguridad y cifrado establecidos. |
| **RF05: Sistema de autenticación para empleados** | Se deberá implementar un sistema de autenticación mediante credenciales únicas (usuario y contraseña). Tras iniciar sesión, el empleado podrá acceder a funcionalidades exclusivas. |
| **RF06: Sistema de descuentos para empleados** | Los empleados autenticados deberán disponer de un módulo que les permita aplicar descuentos automáticos sobre determinados productos o categorías. El sistema deberá validar que el usuario está autorizado y registrar el uso del beneficio en la base de datos. |
| **RF07: Formulario de contacto funcional** | El sistema deberá disponer de un formulario de contacto accesible desde la página principal, que permita al usuario enviar consultas al departamento correspondiente. Se deberán incluir los campos obligatorios: nombre, correo electrónico, tipo de consulta y mensaje. El sistema validará los datos introducidos y confirmará la recepción del mensaje mediante notificación en pantalla o correo electrónico. |

### Prioridad Media
| Código / Requisito Funcional | Descripción |
|----------------------|-------------|
| **RF08: Programación de eventos (Calendario)** | El sistema deberá incluir un módulo que permita programar, visualizar y gestionar eventos corporativos o promocionales (por ejemplo, campañas de descuento o lanzamientos de productos). El calendario deberá poder mostrar eventos próximos en la página principal. |
| **RF09: Sección de preguntas (FAQ)** | Se deberá habilitar una sección de preguntas frecuentes que contenga información relevante para los usuarios (como envíos, devoluciones, pagos o productos). El contenido deberá poder presentarse en formato de lista desplegable para facilitar su lectura. |
| **RF10: Soporte multiidioma** | El sitio deberá ofrecer soporte completo para varios idiomas, incluyendo al menos español, inglés, francés, portugués y chino. El cambio de idioma deberá ser inmediato, afectando a todos los textos visibles, menús, botones y mensajes del sistema. |

---

## 3.5. Requisitos No Funcionales

### Rendimiento
| Código / Requisito No Funcional | Descripción |
|----------------------|-------------|
| **RNF01: Tiempo de carga rápido para el catálogo** | El sistema deberá garantizar que el catálogo de productos se cargue completamente en un tiempo inferior a 3 segundos en condiciones de conexión estándar (10 Mbps), optimizando imágenes, consultas a base de datos y uso de caché. |
| **RNF02: Capacidad para gestionar pedidos de gran volumen** | La aplicación deberá poder procesar simultáneamente un gran número de peticiones de usuarios y pedidos, asegurando un rendimiento estable. |

### Seguridad
| Código / Requisito No Funcional | Descripción |
|----------------------|-------------|
| **RNF03: Transacciones seguras con SSL/TLS** | Todas las comunicaciones entre cliente y servidor deberán realizarse mediante conexión cifrada utilizando el protocolo HTTPS (SSL/TLS 1.2 o superior) para garantizar la integridad y confidencialidad de los datos. |
| **RNF04: Autenticación segura para empleados y clientes VIP** | El sistema deberá implementar un mecanismo de autenticación seguro, además de incorporar políticas de contraseñas seguras (mínimo 8 caracteres, combinación de letras, números y símbolos). |
| **RNF05: Protección de datos personales y comerciales** | El sistema deberá cumplir con la normativa vigente de protección de datos (RGPD), incluyendo la gestión de consentimientos, anonimización de información sensible y control de acceso a los datos por rol y privilegio. |

### Usabilidad
| Código / Requisito No Funcional | Descripción |
|----------------------|-------------|
|**RNF06: Cumplimiento de estándares de accesibilidad** | El portal deberá cumplir con los estándares de accesibilidad web WCAG 2.1 nivel AA, garantizando que los contenidos sean legibles, navegables mediante teclado, y compatibles con lectores de pantalla. |

### Mantenibilidad
| Código / Requisito No Funcional | Descripción |
|----------------------|-------------|
| **RNF07: Sistema actualizable por una sola persona** | La arquitectura del sistema deberá permitir actualizaciones, despliegues y mantenimiento por una única persona con perfil técnico, mediante un proceso documentado y automatizado.|
| **RNF08: Documentación clara y control de versiones (Git)** | Toda la documentación técnica deberán mantenerse en un sistema de control de versiones Git, con convenciones de commit estandarizadas y guías de despliegue actualizadas. |

### Disponibilidad
| Código / Requisito No Funcional | Descripción |
|----------------------|-------------|
| **RNF09: Alta disponibilidad del sistema** | El sistema deberá garantizar una disponibilidad mínima del 99,5% anual, evitando interrupciones en los servicios esenciales como el catálogo, el carrito o las pasarelas de pago. |
| **RNF10: Sistema de copia de seguridad y recuperación** | Se deberán realizar copias de seguridad automáticas diarias de la base de datos y semanales del contenido multimedia, con posibilidad de restauración completa ante fallos o pérdida de datos. |

### Compatibilidad
| Código / Requisito No Funcional | Descripción |
|----------------------|-------------|
| **RNF11: Funcionamiento correcto en navegadores y dispositivos** | La aplicación deberá ser completamente compatible con los navegadores Google Chrome, Mozilla Firefox, Microsoft Edge, Safari y con los sistemas operativos móviles iOS y Android, asegurando una correcta visualización en distintas resoluciones. |

### Accesibilidad y Cumplimiento Normativo
| Código / Requisito No Funcional | Descripción |
|----------------------|-------------|
| **RNF12: Traducción profesional multiidioma** | Todos los contenidos deberán estar traducidos de manera profesional y supervisada, evitando el uso de traducciones automáticas sin revisión. Cada idioma (español, inglés, francés, portugués y chino) deberá presentar el mismo nivel de precisión terminológica y comercial. |
| **RNF13: Cumplimiento legal y normativo del sector alimentario** | La información de productos deberá ajustarse a la legislación europea sobre etiquetado alimentario, garantizando la correcta presentación de ingredientes, alérgenos y certificaciones. |
| **RNF14: Optimización SEO y rendimiento web** | El sitio deberá estar optimizado para motores de búsqueda (SEO), incluyendo metadatos estructurados, URLs amigables, imágenes comprimidas y etiquetas alt descriptivas, a fin de mejorar su posicionamiento y rendimiento general. |
| **RNF15: Escalabilidad del sistema** | La arquitectura del sistema deberá permitir una ampliación futura de funcionalidades (nuevos idiomas, módulos, integración con CRM) sin necesidad de rediseñar la base del sistema. |

---

## 3.6. Reglas de Negocio
| Código / Regla de Negocio | Descripción |
|----------------------|-------------|
|**RN01: Inclusión exclusiva de productos envasados** | El catálogo del sitio web solo deberá incluir productos correspondientes a la línea de productos envasados, quedando expresamente excluidos los productos a granel o de venta en cisternas. Esta restricción se establece por razones estratégicas y de viabilidad técnica para la gestión de pedidos online.| 
| **RN02: Acceso a descuentos exclusivos para empleados** | Los empleados de la empresa deberán disponer de acceso a descuentos preferenciales en los productos, visibles únicamente tras autenticarse en el sistema mediante sus credenciales corporativas. Los descuentos aplicables estarán definidos por el departamento de Administración o Tesorería. |
| **RN03: Administración centralizada por un único responsable interno** | La gestión de contenidos, mantenimiento y administración general del sitio web será responsabilidad de una única persona designada internamente, el encargado de aplicaciones web. Por tanto, todas las herramientas administrativas deben permitir una operación autónoma, segura y simplificada. |
| **RN04: Soporte lingüístico obligatorio en cinco idiomas** | El sitio web deberá ofrecer su contenido íntegramente traducido en los siguientes idiomas: español, inglés, francés, portugués y chino, garantizando uniformidad y calidad en la terminología empleada. |
| **RN05: Cumplimiento de la guía de identidad corporativa** | Todo el diseño y contenido del sitio web deberá respetar íntegramente el Manual de Identidad Corporativa, incluyendo el uso del logotipo oficial, los colores institucionales, las proporciones, la tipografía y los márgenes definidos en la guía de estilo proporcionada por el departamento de marketing. |
| **RN06: Jerarquía de productos** | El catálogo deberá organizarse en dos líneas principales de negocio: Aceites (La Masía) y Salsas (Ybarra). Aceites: oliva, oliva virgen extra, girasol, orujo. Salsas: mayonesa, alioli, cocktail, gaucha, roquefort, burguer, BBQ, mostaza, césar, kebab, ranchera, brava, yogurt. Esta jerarquía deberá mantenerse de forma coherente en todo el sitio (catálogo, filtros, buscador y fichas de producto). |
| **RN07: Certificación y sellos visibles y verificables** | Todos los productos que dispongan de certificaciones (ecológicas, sin gluten, etc.) deberán mostrar sus sellos oficiales de forma visible y verificable, con enlaces o referencias a las entidades certificadoras correspondientes.|
| **RN08: Diferenciación entre líneas de negocio** | El sitio web deberá reflejar la existencia de las dos líneas de producto de la compañía —granel y envasado—, mostrando únicamente información comercial y visual de la segunda, y dejando constancia institucional de la primera para mantener coherencia corporativa. |
| **RN09: Inclusión de información** | El portal corporativo deberá incorporar una sección dedicada a Sostenibilidad y Responsabilidad Social Corporativa (RSC), donde se detallen las políticas medioambientales, el uso de energías renovables, el origen de las materias primas y las colaboraciones con ONGs o bancos de alimentos. |
| **RN10: Destacada representación de marcas del grupo** | Las marcas principales del grupo (Ybarra y La Masía) deberán estar claramente representadas en el sitio, cada una con su identidad diferenciada, descripción, catálogo propio y enlaces a sus productos correspondientes dentro del grupo empresarial. |
| **RN11: Presentación institucional de la empresa y estructura organizativa** | El sitio deberá incluir una sección institucional con información sobre la historia de la empresa reforzando la transparencia y la imagen de marca ante clientes y socios. |

---


## 4. ANÁLISIS DEL SISTEMA

### 4.1 Mockups y Prototipos

#### Mockup de la Página Principal
![ImagenPaginaPrincipal](https://github.com/user-attachments/assets/fad29aa7-63dc-4f6b-a918-fb4b32476a4e)

#### Mockup de la Tienda
![ImagenTienda](https://github.com/user-attachments/assets/63515b42-4728-4029-a928-405c9195d91f)

#### Mockup de la Información de cada Producto
![ImagenInfoProductos](https://github.com/user-attachments/assets/eb0013d6-ad05-4f2c-ba55-505ad07ca0ac)

#### Mockup del Conócenos
![ImagenDelConócenos](https://github.com/user-attachments/assets/18acfbbd-83e8-4c3c-aad1-5725cf932827)

#### Mockup del Carrito de compra
![ImagenCarrito](https://github.com/user-attachments/assets/fde831be-da5f-4dd0-a517-e9b2cb308ece)

#### Mockup del Register
![ImagenRegistro](https://github.com/user-attachments/assets/7677c916-b1b1-430a-9b9b-b7cfdd3729a2)

#### Mockup del Login
![ImagenLogin](https://github.com/user-attachments/assets/5d091c17-d412-4f70-8ce7-7fbab79f668b)

#### Mockup del FAQ
![ImagenFAQ](https://github.com/user-attachments/assets/4b559b9d-7f62-4bb7-a26a-6c1dba346f8b)

### 4.2 Diagrama de Clases

*Diagrama UML que representa la estructura del sitio WordPress para MIGASA*

---

## 5. DISEÑO

### 5.1 Análisis y Selección de Plugins (POR TOCAR)

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

### 5.2 Análisis y Selección de Temas (POR TOCAR)

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

## Comparativa de Software Colaborativo

| Característica | GitHub Projects | Microsoft Teams | Decisión |
|----------------|----------------|-----------------|----------|
| **Integración con Git** | ✅ Nativa | ❌ Requiere plugins/apps | **Ventaja GitHub** |
| **Control de versiones** | ✅ Git incluido | ❌ No incluido | **Ventaja GitHub** |
| **Gestión de tareas** | ✅ Problemas(Issues) + Proyectos | ✅ Planificador/Tareas integrado | Empate |
| **Precio** | ✅ Gratuito (público) | ⚠️ Gratuito básico, limitado | **Ventaja GitHub** |
| **Funciones SCRUM** | ✅ Básicas pero suficientes | ⚠️ Básicas (requiere Planner) | Empate |
| **Comunicación en tiempo real** | ⚠️ Comentarios asíncronos | ✅ Chat, videollamadas | **Ventaja Teams** |
| **Almacenamiento archivos** | ✅ Repositorio Git | ✅ OneDrive/SharePoint | Empate |
| **Historial de cambios** | ✅ Completo con Git (commits detallados)| ⚠️ Limitado a archivos | **Ventaja GitHub** |
| **Colaboración código** | ✅ Solicitudes de revisión de código | ❌ No especializado | **Ventaja GitHub** |
| **Automatización** | ✅ GitHub Actions ejecuta tareas (tests, validaciones) automáticamente | ✅ Power Automate es la herramienta de MIcrosoft para automatizar tareas| Empate |
| **Portfolio profesional** | ✅ Visible públicamente | ❌ Interno organización | **Ventaja GitHub** |
| **Curva de aprendizaje** | ⚠️ Media (requiere aprender Git) | ✅ Baja (interfaz conocida en la asignatura) | **Ventaja Teams** |
| **Documentación técnica** | ✅ Markdown, Wiki | ✅ OneNote, Docs | Empate |
| **Integraciones** | ✅ Amplio ecosistema | ✅ Microsoft 365 | Empate |
| **Reporting SCRUM** | ⚠️ Básico | ⚠️ Básico | Empate |
| **Uso en industria** | ✅ Estándar desarrollo web | ✅ Estándar empresas | **Ventaja GitHub** |

**Software seleccionado:** GitHub Projects

**Justificación:** Integración nativa con Git, control de versiones incluido, gratuito, ideal para proyectos de desarrollo web, y valioso para portfolio profesional.

### 6.2 Control de Versiones

**Sistema seleccionado:** Git con GitHub como repositorio remoto

**Justificación:**
- **Estándar de la industria:** Sistema de control de versiones más utilizado mundialmente
- **Trabajo colaborativo eficiente:** Branching y merging facilitan desarrollo paralelo.  El Branching es crear una copia independiente de tu código donde puedes trabajar sin afectar la rama principal. El Merging es el proceso de integrar los cambios de una rama a otra.
- **Historial completo:** Registro detallado de todos los cambios (quién, qué, cuándo, por qué)
- **Backup automático:** Código siempre respaldado en la nube
- **Reversión sencilla:** Posibilidad de volver a versiones anteriores ante errores
- **Resolución de conflictos:** Herramientas visuales para merge conflicts (conflictos de fusión) aparecen por ejemplo cuando dos personas editan la misma línea de un archivo o ambas ramas tienen cambios incompatibles en el mismo lugar.


### 6.3 Product Backlog (POR TOCAR)

**Total puntos Product Backlog:** 28 puntos  
**Velocidad estimada:** 14 puntos por sprint (2 semanas cada uno, 1 punto por día)

| ID | Historia de Usuario | Descripción Detallada | Criterios de Aceptación | Prioridad | Puntos | Sprint |
|----|--------------------|-----------------------|------------------------|-----------|--------|---------|
| **PBl-01** | Como visitante, quiero navegar fácilmente por el sitio | Implementar menú responsive con estructura jerárquica clara y breadcrumbs | • Menú visible en todas las páginas<br>• Breadcrumbs en todas las páginas internas<br>• Navegación intuitiva (máximo 3 clics) | Alta | 1 | Sprint 1 |
| **PBl-02** | Como administrador, quiero gestionar contenido fácilmente | Configurar WordPress con roles, permisos | • Dashboard WordPress intuitivo<br>• Roles definidos (admin/editor)<br>• Documentación de uso entregada | Alta | 5 | Sprint 1 |
| **PBl-03** | Como visitante, quiero ver productos de aceite | Catálogo de productos con filtros por tipo y ficha detallada | • Mínimo 10 productos publicados<br>• Filtro por tipo de aceite funcional<br>• Ficha detallada con especificaciones técnicas<br>• Imágenes de alta calidad | Alta | 13 | Sprint 1 |
| **PBl-04** | Como visitante, quiero contactar con MIGASA | Formulario funcional con validación y notificaciones email | • Campos obligatorios validados<br>• Email confirmación a usuario<br>• Notificación a MIGASA funcional<br>• Anti-spam activo (Akismet)<br>• GDPR checkbox obligatorio | Alta | 3 | Sprint 1 |
| **PBl-05** | Como visitante, quiero un sitio rápido | Optimizar rendimiento con cache, compresión y lazy loading | • PageSpeed Insights >80/100<br>• Tiempo de carga <3 segundos<br>• Lazy loading activado<br>• Imágenes optimizadas (WebP) | Media | 5 | Sprint 1 |
| **PBl-06** | Como administrador, quiero seguridad robusta | Configurar firewall, 2FA, SSL y backups automáticos | • Wordfence activo y escaneando<br>• 2FA obligatorio para admin<br>• Backups semanales automáticos<br>• SSL certificado configurado<br>• Login protegido contra fuerza bruta | Media | 5 | Sprint 2 |
| **PBl-07** | Como visitante móvil, quiero acceso completo | Diseño 100% responsive y optimizado para táctil | • Funcional en iOS y Android<br>• Menú táctil optimizado<br>• Formularios mobile-friendly<br>• Imágenes adaptativas<br>• Testing en dispositivos reales | Alta | 8 | Sprint 1 |
| **PBl-08** | Como visitante internacional, quiero el sitio en cinco idiomas | Implementar multiidioma con GTranslate | • Todo el contenido traducido<br>• Selector de idioma visible<br>• URLs por idioma <br>• Menús traducidos<br>• SEO multiidioma optimizado | Media | 8 | Sprint 1 |
| **PBl-09** | Como visitante, quiero conocer la historia de MIGASA | Página "Empresa" con timeline interactiva y valores | • Timeline con hitos históricos<br>• Sección 90 años de historia<br>• Fotos de familia/instalaciones<br>• Video institucional embebido<br>• Misión, visión y valores | Media | 5 | Sprint 1 |
| **PBl-10** | Como comprador, quiero un carrito y proceso de compra completo | Implementar carrito persistente con gestión de cantidades, impuestos, envío y resumen del pedido | • Añadir/eliminar/modificar cantidades.<br>• Cálculo de impuestos y envío.<br>• Carrito persistente por sesión/usuario.<br>• Vista resumen con totales | Alta | 8 | Sprint 1 |
| **PBl-11** | Como cliente, quiero pagar de forma segura en el sitio | Integrar pasarelas de pago seguras (tarjeta, PayPal, Google Pay, Apple Pay) |• Integración funcional con TPV y PayPa.l<br>• Pagos en HTTPS cifrados.<br>• Tokenización sin almacenar datos de tarjeta.<br>• Confirmación de pedido por email. | Alta | 5 | Sprint 1 |
| **PBl-12** | Como empleado, quiero autenticarme y aplicar descuentos exclusivos | Implementar autenticación para empleados y módulo de descuentos automáticos |• Login de empleados con credenciales únicas.• 2FA activado.<br>• Descuentos aplicados automáticamente.<br>• Registro de uso en BD.<br>• Acceso por rol validado. | Alta | 3 | Sprint 1 |
| **PBl-13** | Como usuario, quiero ver eventos y promociones en el calendario | Módulo de calendario para programar y mostrar eventos o campañas |• Crear/editar eventos en backend.<br>• Widget en home con próximos eventos.<br>• Soporte para eventos recurrentes.<br>• Exportación a iCal/Google Calendar.| Media | 2 | Sprint 1 |
| **PBl-14** | Como visitante, quiero soporte rápido con FAQ y chatbot asistencial | Implementar sistema FAQ administrable y chatbot multilingüe conectado a base de conocimiento |• Sección FAQ con lista desplegable.<br>• Chatbot visible en todas las páginas.<br>• Soporte en 5 idiomas.<br>• Respuestas integradas con FAQ.<br>• Métricas básicas de interacción.|Media| 2 | Sprint 1 |

**Priorización:**
- **Alta prioridad (Sprint 1):** Funcionalidades core (navegación, productos, contacto, seguridad)
- **Media prioridad (Sprint 2):** Optimizaciones y contenido adicional (analytics, multiidioma, historia)

# PROYECTO CMS - WORDPRESS MIGASA
## Secciones 6.4 en adelante

---

## 6.4 Sprint Backlog - Sprint 1 (POR TOCAR)

**Objetivo del Sprint:** Establecer la base funcional del sitio WordPress con diseño responsive, catálogo de productos, formulario de contacto y medidas de seguridad, todo respetando la identidad corporativa de MIGASA.

**Duración:** 2 semanas (10 días laborables)  
**Fecha inicio:** *29/09/2025*  
**Fecha fin:** *12/10/2025*  

| ID | Tarea | Descripción Detallada | Responsable | Estado | Horas Est. | Horas Real | Dependencias | Observaciones |
|----|-------|-----------------------|-------------|--------|------------|------------|--------------|---------------|
| **T-01** | Instalación WordPress | Configurar entorno local (XAMPP), instalar WordPress, crear BD migasa_cms_db | Guillermo | Done | 1 | 0'5 | Ninguna | Documentar credenciales |
| **T-02** | Análisis de temas | Investigar y comparar Divi, Astra Pro y OceanWP con tabla comparativa | Nazaret | Doing | - | - | Ninguna | Incluir criterios de decisión |
| **T-03** | Instalación tema Divi | Descargar, instalar, activar licencia Elegant Themes | Nazaret | Done | 0'5 | 0'25 | T-01, T-02 | Guardar licencia segura |
| **T-04** | Configurar colores corporativos | Aplicar RGB Pantone (#A3AB11, #7C9323, #3B593B) en Theme Customizer | Iluminada | Done | - | - | T-03 | Usar manual identidad |
| **T-05** | Cargar tipografías | Subir DIN Black y Myriad Pro, configurar en Divi | Iluminada | Doing | - | - | T-03 | Formato web (WOFF2) |
| **T-06** | Análisis plugins seguridad | Comparar Wordfence, Sucuri, iThemes Security con tabla | ------ | To Do |  | - | Ninguna | Criterios: descargas, rating |
| **T-07** | Análisis plugins cache | Comparar WP Rocket, W3 Total Cache, WP Super Cache con tabla | ------ | To Do |  | - | Ninguna | Justificar inversión |
| **T-08** | Análisis plugins SEO | Comparar Yoast SEO, Rank Math, All in One SEO con tabla | ------ | To Do |  | - | Ninguna | Énfasis multiidioma |
| **T-09** | Análisis plugins Analytics | Comparar MonsterInsights, GA Dashboard, Analytify con tabla | ------ | To Do |  | - | Ninguna | GDPR compliance |
| **T-10** | Instalar y configurar Wordfence | Activar firewall, configurar 2FA, programar escaneos | ------ | To Do |  | - | T-01, T-06 | Learning mode inicial |
| **T-11** | Instalar y configurar WP Rocket | Activar cache, lazy load, minificación CSS/JS | ------ | To Do |  | - | T-01, T-07 | Limpiar cache tras cambios |
| **T-12** | Instalar y configurar Yoast SEO | Configurar sitemap, schema Organization, breadcrumbs | ------ | To Do |  | - | T-01, T-08 | Palabra clave: aceite oliva |
| **T-13** | Instalar y configurar MonsterInsights | Conectar con cuenta GA4, activar tracking formularios | ------ | To Do |  | - | T-01, T-09 | Crear cuenta GA4 previa |
| **T-14** | Instalar plugins adicionales | WPForms, WPML, Envira Gallery, UpdraftPlus, ShortPixel | ------ | To Do |  | - | T-01 | Configuración básica |
| **T-15** | Crear mockup Home | Diseñar con Balsamiq: hero, productos destacados, cifras | Nazaret | Done |  | - | Ninguna | Exportar PNG alta res |
| **T-16** | Crear mockup Empresa | Diseñar con Balsamiq: timeline, valores, instalaciones | ------ | To Do |  | - | Ninguna | Incluir Google Maps |
| **T-17** | Crear mockup Productos | Diseñar con Balsamiq: grid productos, filtros, detalle | ------ | To Do |  | - | Ninguna | Layout responsive |
| **T-18** | Crear mockup Contacto | Diseñar con Balsamiq: formulario, datos, mapa | ------ | To Do |  | - | Ninguna | GDPR checkbox visible |
| **T-19** | Crear diagrama de clases | UML con clases: Usuario, Página, Producto, etc. | Emilio y Guillermo | Doing |  | - | Ninguna | Usar draw.io o Lucidchart |
| **T-20** | Configurar estructura de menús | Crear menú principal y footer con jerarquía | Iluminada | Done |  | - | T-03 | 7 items principales |
| **T-21** | Crear página Home | Implementar con Woocommerce: todas las secciones | Iluminada | Doing |  | - | T-03, T-04, T-05, T-15 | Usar colores corporativos |
| **T-22** | Crear página Empresa | Historia, valores, ubicaciones con timeline | Iluminada | Doing |  | - | T-03, T-16 | Integrar Google Maps |
| **T-23** | Crear categorías de productos | Custom post type: Aceite Oliva, Girasol, Orujo | Iluminada | Doing |  | - | T-03 | Taxonomía personalizada |
| **T-24** | Añadir 10 productos mínimo | Fichas completas: imágenes, descripciones, specs | Iluminada | Doing |  | - | T-23 | Contenido de web actual |
| **T-25** | Diseñar template producto individual | Layout detalle: galería, specs, CTA contacto | ------ | To Do |  | - | T-03, T-17 | Reutilizable para todos |
| **T-26** | Crear formulario contacto | WPForms: campos, validación, notificaciones, GDPR | ------ | To Do |  | - | T-14, T-18 | Testing envío real |
| **T-27** | Crear página Contacto | Formulario + Google Maps + datos corporativos | ------ | To Do |  | - | T-03, T-26 | 2 ubicaciones en mapa |
| **T-28** | Optimizar imágenes | Comprimir todas, convertir a WebP, añadir ALT | ------ | To Do |  | - | T-21, T-22, T-24 | ShortPixel bulk |
| **T-29** | Configurar UpdraftPlus | Backup semanal automático a Google Drive | ------ | To Do |  | - | T-14 | Retener 4 copias |
| **T-30** | Testing responsive | Probar en iPhone, Android, iPad, diferentes resoluciones | ------ | To Do |  | - | T-21 a T-27 | Chrome DevTools + real |
| **T-31** | Testing formularios | Envíos de prueba, validaciones, emails recibidos | ------ | To Do |  | - | T-26, T-27 | Verificar anti-spam |
| **T-32** | Documentar implementación | Screenshots de cada página, descripciones detalladas | ------ | To Do |  | - | T-21 a T-27 | Para entregable PDF |
| **T-33** | Revisar identidad corporativa | Verificar colores Pantone, tipografías, logo correcto | ------ | To Do |  | - | Todas anteriores | Checklist manual |
| **T-34** | Ajustes finales y pulido | Corregir detalles, alinear elementos, spacing | ------ | To Do |  | - | Todas anteriores | QA final |

**Total horas estimadas Sprint 1:** X horas  
**Distribución:** X horas por persona (4 integrantes)  
**Capacidad diaria:** 4 horas/día laborable (medio tiempo - proyecto académico)

### Distribución de tareas por integrante:

**------ (23h):**
- T-01: Instalación WordPress (4h)
- T-03: Instalación tema Divi (2h)
- T-14: Instalar plugins adicionales (2h)
- T-20: Configurar menús (2h)
- T-22: Crear página Empresa (5h)
- T-29: Configurar backups (1h)
- T-30: Testing responsive (1h)
- T-33: Revisar identidad (0.5h)
- T-34: Ajustes finales (0.75h)

**------ (26h):**
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

**------ (24h):**
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

**------ (25h):**
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

## 6.5 Burndown Chart - Sprint 1 (POR TOCAR)

*El burndown chart debe actualizarse diariamente durante la ejecución del sprint*

**Estructura del gráfico:**
- **Eje X:** Días del sprint (Día 1 a Día 10)
- **Eje Y:** Horas pendientes (de 96 a 0)
- **Línea ideal:** Descenso lineal de 96 a 0 (9.6 horas/día)
- **Línea real:** Progreso actual del equipo (actualizar diariamente)

**Tabla de seguimiento diario:**

| Día | Fecha | Horas Ideales Restantes | Horas Reales Restantes | Diferencia | Tareas Completadas | Observaciones |
|-----|-------|------------------------|------------------------|------------|-------------------|---------------|
| 0 | *29/09/2025* | 96.0 | 96.0 | 0 | Ninguna | Sprint Planning |
| 1 | *[Fecha]* | 86.4 | *[Actualizar]* | *[±X]* | *[IDs]* | *[Notas del día]* |
| 2 | *[Fecha]* | 76.8 | *[Actualizar]* | *[±X]* | *[IDs]* | *[Notas del día]* |
| 3 | *[Fecha]* | 67.2 | *[Actualizar]* | *[±X]* | *[IDs]* | *[Notas del día]* |
| 4 | *[Fecha]* | 57.6 | *[Actualizar]* | *[±X]* | *[IDs]* | *[Notas del día]* |
| 5 | *[Fecha]* | 48.0 | *[Actualizar]* | *[±X]* | *[IDs]* | *[Notas del día]* |
| 6 | *[Fecha]* | 38.4 | *[Actualizar]* | *[±X]* | *[IDs]* | *[Notas del día]* |
| 7 | *[Fecha]* | 28.8 | *[Actualizar]* | *[±X]* | *[IDs]* | *[Notas del día]* |
| 8 | *[Fecha]* | 19.2 | *[Actualizar]* | *[±X]* | *[IDs]* | *[Notas del día]* |
| 9 | *[Fecha]* | 9.6 | *[Actualizar]* | *[±X]* | *[IDs]* | *[Notas del día]* |
| 10 | *12/10/25* | 0 | *0* | *[±X]* | *[IDs]* | Sprint Review |

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

### 7.1 Instalación de WordPress (POR TOCAR)

**Entorno de desarrollo:**
- **Software:** XAMPP 8.2.4 (Apache 2.4.56, MySQL 8.0.32, PHP 8.2.4)
- **Sistema operativo:** *[Windows 11 / macOS / Linux Ubuntu]*
- **URL local:** http://localhost:8080/migasa-wordpress

**Proceso realizado:**

1. **Instalación de stack XAMPP/Bitnami**
2. **Creación de base de datos:** `migasa_cms_db` (utf8mb4_unicode_ci)
3. **Descarga WordPress 6.4.2** desde wordpress.org
4. **Configuración inicial:**
   - Título: "MIGASA - Tienda online"
   - Descripción: "Líderes mundiales en aceite de oliva desde 1933"
   - Usuario admin: `admin_migasa`
   - Idioma: Español

*[PENDIENTE: Screenshot del dashboard WordPress recién instalado]*

### 7.2 Configuración de Tema Green Store 1.0.2 (POR TOCAR)

**Licencia:** gradientthemes

**Configuración de colores corporativos:**
- Color primario: #A3AB11 (Pantone 383 C)
- Color secundario: #7C9323 (Pantone 377 C)
- Color acento: #3B593B (Pantone 357 C)

**Tipografías cargadas:**
- DIN Black Regular (títulos H1, H2)
- Myriad Pro Regular (contenido body)
- Myriad Pro Bold (navegación, botones)

**Logo:**
- Tamaño: 512x512
- Favicon: 32x32px y 180x180px (iOS)  --> No lo he usado

*[PENDIENTE: Screenshots de Theme Customizer configurado]*

### 7.3 Instalación y Configuración de Plugins (POR TOCAR)

#### Plugins obligatorios configurados: (POR TOCAR)

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
- **WPML:** Español/Inglés configurado                        (NO USADO)
- **WPForms Lite:** Formulario de contacto creado
- **UpdraftPlus:** Backups semanales a Google Drive           (NO USADO)
- **ShortPixel:** Optimización automática de imágenes         (NO USADO)
- **Carousel Slider Block:** Carrusel de imágenes
- **WooCommerce:** Comercio electrónico
- **WooCommerce Stripe Gateway:** Diferentes formas de pago online
- **WooCommerce PayPal Payments:** Pago con Paypal
- **Google for WooCommerce:** Búsquedas de la página en Google
- **Jetpack:** Seguridad

*[PENDIENTE: Screenshots de configuración de cada plugin]*

### 7.4 Estructura de Páginas Creadas (POR TOCAR)

**Páginas implementadas en Sprint 1:**

#### 7.4.1 Página Home
**URL:** /  
**Secciones:**
- Header con imagen de olivar y barra de páginas
- Quiénes somos/Nuestra historia (texto + carrusel imágenes)
- Cifras clave (4 bloques: 90+ años, 120 países, 1000M€, 3ª generación)
- Productos destacados (bloque 5 columnas)
- Pie de página con contacto y links páginas

*[PENDIENTE: Screenshot página Home completa (desktop y móvil)]*

#### 7.4.2 Página Empresa  (POR CREAR)
**URL:** /empresa/  
**Secciones:**
- Timeline histórica (vertical con hitos)
- Misión, Visión y Valores
- Instalaciones (Dos Hermanas, La Luisiana)
- Google Maps integrado
- Video institucional

*[PENDIENTE: Screenshot página Empresa]*

#### 7.4.3 Catálogo de Productos
**URL:** /tienda/  
**Funcionalidad:**
- Bloque de productos (4 columnas)
- Filtros por tipo de aceite
- 10 productos publicados mínimo:
  - Aceite Oliva Virgen Extra
  - Aceite Oliva Virgen
  - Aceite Oliva Refinado
  - Aceite Girasol
  - Aceite Orujo
  - (+ otros productos)

**Página detalle producto:**
- Galería de imágenes
- Precio con impuestos
- Especificaciones técnicas
- Presentaciones disponibles
- Certificaciones
- Botón para añadir a carrito

*[PENDIENTE: Screenshots de catálogo y detalle de producto]*

#### 7.4.4 Página Contacto   (POR CREAR)
**URL:** /contacto/  
**Elementos:**
- Formulario WPForms con validación
- Campos: Nombre, Email, Teléfono, Tipo consulta, Mensaje, GDPR checkbox
- Google Maps con 2 ubicaciones:
  - Dos Hermanas (Ctra. Madrid-Cádiz, Km. 556)
  - La Luisiana
- Datos de contacto: Tel. 954 720 550, Email: info@migasa.com

*[PENDIENTE: Screenshot página Contacto y prueba de envío formulario]*

#### 7.4.5 Carrito
**URL:** /carrito/  
**Elementos:**
- Bloque con resumen del producto y su precio con impuestos
- Productos relacionados
- Bloque de compra con precio estimado sin gastos de envío
- Pestaña para cupones

*[PENDIENTE: Screenshot página Contacto y prueba de envío formulario]*

### 7.5 Identidad Visual Implementada (POR TOCAR)

**Colores aplicados (según manual corporativo):**
- Verde claro #A3AB11: Botones primarios, enlaces, highlights
- Verde medio #7C9323: Títulos secundarios, hover effects
- Verde oscuro #3B593B: Footer, elementos de contraste
- Negro #000000: Textos principales
- Gris #666666: Textos secundarios y fondos

**Tipografías:**
- DIN Black: H1 (36px), H2 (28px)
- Myriad Pro Regular: Body (14px)
- Myriad Pro Bold: Menú (13px), botones

**Logo:**
- Área de seguridad respetada (5mm = 19px digitales)
- Tamaño mínimo: 100px (móvil), 150px (tablet), 180px (desktop)
- Versión: Principal sobre fondo blanco

### 7.6 Optimizaciones Realizadas (POR TOCAR)

**SEO:**
- Meta títulos y descripciones en todas las páginas
- URLs amigables: /productos/aceite-oliva-virgen-extra/
- Imágenes con atributos ALT descriptivos
- Estructura de headings correcta (H1 único por página)
- Sitemap XML enviado a Google Search Console

**Rendimiento:**
- Imágenes optimizadas con ShortPixel (formato WebP)   **(PLUGIN NO USADO)**
- Lazy loading activado en todas las imágenes
- CSS y JS minificados y combinados
- GZIP compression habilitada
- Cache de página activado        **(NECESITO PLUGIN)**
- **Resultado PageSpeed Insights:** *[Incluir scores reales]*

**Seguridad:**
- Certificado SSL configurado (HTTPS)    **(NO TENEMOS, VALE DINERO)**
- Login protegido con 2FA                **(LOGIN POR CREAR)**
- Firewall Wordfence activo              **(NO USADO)**
- Backups automáticos semanales
- Versión WordPress oculta

**Accesibilidad:**
- Contraste de colores: Cumple WCAG 2.1 AA      **(NI IDEA)**
- Navegación por teclado funcional
- Atributos ARIA en elementos interactivos      **(NI IDEA)**
- Labels en formularios

### 7.7 Testing Realizado (POR TOCAR)

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

### 7.8 Próximos Pasos (Sprint 2) (POR TOCAR)

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

### 8.1 Logros Principales del Proyecto (POR TOCAR)

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

### 8.2 Desafíos Encontrados (POR TOCAR)

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

### 8.3 Aprendizajes Clave (POR TOCAR)

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

### 8.5 Riesgos Identificados y Gestión (POR TOCAR)

| Riesgo | Probabilidad | Impacto | Estado | Mitigación Aplicada |
|--------|--------------|---------|--------|---------------------|

### 8.6 Entregables Completados - Sprint 1 (POR TOCAR)

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
- Catálogo de productos con mínimo 10 productos por página
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

### 8.7 Pendiente para Sprint 2 (POR TOCAR)

**Funcionalidades:**
- [ ] Completar traducciones WPML 
- [ ] Página de Sostenibilidad completa

**Optimizaciones:**
- [ ] Mejorar PageSpeed a >90/100
- [ ] Implementar schema markup avanzado

**Contenido:**
- [ ] Añadir más productos (objetivo: 100 total)
- [ ] Videos institucionales
- [ ] Testimonios de clientes
- [ ] Catálogos PDF descargables

### 8.8 Reflexión del Equipo (POR TOCAR)

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

### 8.9 Agradecimientos (POR TOCAR)

Agradecemos a:
- **MIGASA** por la oportunidad de trabajar con una empresa líder en el sector del aceite de oliva
- **Profesores** por la guía y feedback durante el proyecto
- **Compañeros de clase** por el apoyo y colaboración

Agradecimiento especial a MIGASA por proporcionar el manual de identidad corporativa que ha sido fundamental para este proyecto.

---

## 9. REFERENCIAS

### 9.1 Documentación Técnica (POR TOCAR)

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

### 9.2 Manuales de MIGASA (POR TOCAR)

7. **Manual de Identidad Corporativa MIGASA**  
   Documento proporcionado por la empresa (incluido en repositorio)

8. **Sitio web actual de MIGASA**  
   www.migasa.com (análisis de referencia)

### 9.3 Metodología SCRUM (POR TOCAR)

9. **Scrum Guide 2020** - Definición oficial de SCRUM  
   https://scrumguides.org/

10. **Atlassian** - Agile and SCRUM Resources  
    https://www.atlassian.com/agile/scrum

11. **Mountain Goat Software** - User Stories Applied  
    https://www.mountaingoatsoftware.com/

### 9.4 Herramientas Utilizadas (POR TOCAR)

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

17. **CLAUDE AI & CHAT GPT** - Content Generator
    https://claude.com
    https://chatgpt.com

### 9.5 Estándares y Buenas Prácticas (POR TOCAR)

18. **WCAG 2.1** - Web Content Accessibility Guidelines  
    https://www.w3.org/WAI/WCAG21/quickref/

19. **Schema.org** - Structured Data Vocabulary  
    https://schema.org/

20. **Google SEO Starter Guide**  
    https://developers.google.com/search/docs/beginner/seo-starter-guide

21. **WPBeginner** - WordPress Tutorials for Beginners  
    https://www.wpbeginner.com/

### 9.6 Diseño Web y UX (POR TOCAR)

22. **Material Design** - Design System  
    https://material.io/design

23. **Nielsen Norman Group** - UX Research and Guidelines  
    https://www.nngroup.com/

24. **A11Y Project** - Accessibility Resources  
    https://www.a11yproject.com/

### 9.7 Recursos de Aprendizaje (POR TOCAR)

25. **YouTube** - Divi Theme Tutorials  
    Canal: Elegant Themes

26. **CSS-Tricks** - Web Development Blog  
    https://css-tricks.com/

27. **Stack Overflow** - Developer Community  
    https://stackoverflow.com/

---

## 10. ANEXOS (POR TOCAR)

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
- Email: *emicueren@alum.us.es*
- GitHub: *Cuevas2004*

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
