# Asistente integral de salud

Prototipo de un asistente de inteligencia artificial orientado a facilitar el acceso a información sanitaria y servicios farmacéuticos en Colombia.

- **Estado del proyecto:** Maquetación inicial
- **Tecnologías:** HTML5 y CSS3
- **Metodología de diseño:** Mobile First
- **Contexto:** Proyecto formativo — Riwi

## 1. Descripción del proyecto

El Asistente integral de salud es una propuesta tecnológica que busca contribuir al mejoramiento de la experiencia de los usuarios dentro del sistema sanitario colombiano mediante una interfaz accesible, intuitiva y centrada en las personas.

El proyecto plantea un asistente de inteligencia artificial capaz de proporcionar orientación preliminar sobre síntomas, facilitar la preparación de consultas médicas y ayudar a los usuarios a localizar medicamentos en establecimientos farmacéuticos.

La propuesta no busca reemplazar a los profesionales de salud, sino servir como una herramienta complementaria que facilite el acceso a información confiable y contribuya a optimizar los procesos de atención.

Actualmente, el proyecto se encuentra en su etapa de maquetación, desarrollada exclusivamente con HTML y CSS.

## 2. Problemática

El proyecto surge a partir de dos situaciones que pueden afectar la experiencia de los usuarios del sistema de salud colombiano.

### Orientación y atención sanitaria

- Dificultad para acceder a información confiable sobre síntomas.
- Incertidumbre sobre los pasos que se deben seguir ante determinadas molestias.
- Falta de información organizada al momento de acudir a una consulta médica.
- Necesidad de contribuir a la optimización de los procesos de atención en EPS, IPS, hospitales y servicios de urgencias.

### Acceso a medicamentos

- Desplazamientos innecesarios a establecimientos farmacéuticos.
- Filas y tiempos de espera para consultar la disponibilidad de medicamentos.
- Dificultad para conocer qué establecimientos cuentan con los medicamentos requeridos.
- Falta de información oportuna sobre existencias, ubicaciones y convenios con las EPS.

## 3. Objetivos

### Objetivo general

Diseñar un prototipo de asistente de inteligencia artificial que facilite la orientación sanitaria y la búsqueda de medicamentos, priorizando la accesibilidad, la transparencia, la seguridad y el control humano.

### Objetivos específicos

- Diseñar una interfaz sencilla y accesible para usuarios con diferentes niveles de conocimiento tecnológico.
- Representar un flujo de consulta de síntomas que permita organizar información relevante para una futura valoración médica.
- Diseñar una interfaz de búsqueda de medicamentos y establecimientos farmacéuticos.
- Representar los diferentes estados de interacción de una aplicación basada en inteligencia artificial.
- Promover la consulta de fuentes confiables y el reconocimiento de las limitaciones de la IA.
- Garantizar que la atención humana sea una alternativa visible dentro de la interfaz.
- Aplicar la metodología Mobile First durante el proceso de maquetación.

## 4. Propuesta de solución

El asistente plantea una interfaz híbrida que combina la interacción conversacional con opciones guiadas mediante formularios y botones.

Esta combinación busca facilitar su utilización tanto para personas familiarizadas con herramientas digitales como para usuarios que necesitan una experiencia más guiada.

La aplicación se divide en dos módulos principales.

### 4.1. Módulo de orientación en salud

Este módulo está diseñado para representar una experiencia de orientación preliminar sobre síntomas.

La interfaz contempla:

- Descripción libre de síntomas.
- Selección de síntomas mediante opciones predefinidas.
- Registro de la duración de las molestias.
- Escala de intensidad del dolor del 0 al 10.
- Campo de información adicional.
- Respuestas informativas de ejemplo.
- Fuentes de referencia.
- Mensajes de error e incertidumbre.
- Opciones de atención profesional.

En una futura implementación, este módulo podría ayudar a organizar la información proporcionada por el usuario y facilitar su comunicación con los profesionales de salud.

El asistente no pretende realizar diagnósticos, prescribir tratamientos ni sustituir la clasificación oficial del triage hospitalario.

### 4.2. Módulo de asistencia farmacéutica

Este módulo representa una interfaz para consultar la disponibilidad de medicamentos en establecimientos farmacéuticos.

Los criterios de búsqueda contemplados son:

- Nombre del medicamento.
- Concentración y presentación.
- Entidad Promotora de Salud (EPS).
- Ciudad o municipio.

La interfaz presenta tarjetas de resultados que incluyen información de referencia sobre:

- Establecimiento farmacéutico.
- Sede y ubicación.
- Horario de atención.
- Medicamento consultado.
- Convenio con la EPS.
- Disponibilidad.
- Fuente y actualización del inventario.
- Opción de contacto.

Se representan tres posibles estados de disponibilidad:

| Estado | Descripción |
|---|---|
| Disponible | El inventario reporta existencias del medicamento. |
| Agotado | El inventario reporta ausencia de existencias. |
| Sin confirmar | No existe información suficiente para determinar la disponibilidad. |

Los datos presentados en la maqueta son ficticios y no corresponden a inventarios reales.

## 5. Estados de la interfaz

La maquetación representa los estados necesarios para diseñar una experiencia transparente y comprensible en una aplicación basada en inteligencia artificial.

| Estado | Descripción |
|---|---|
| Vacío | Estado inicial antes de realizar una consulta. |
| Cargando | Representación visual del procesamiento de una consulta. |
| Respuesta | Presentación de información acompañada de fuentes de referencia. |
| Error | Comunicación clara de un fallo y representación de alternativas para continuar. |
| Incertidumbre | Reconocimiento de que no existe información suficiente para proporcionar una respuesta confiable. |
| Sin resultados | Representación de una búsqueda farmacéutica sin establecimientos coincidentes. |

Estos estados se encuentran maquetados de manera estática. Su comportamiento dinámico será responsabilidad de futuras etapas de desarrollo.

## 6. Flujo de interacción

El flujo de interacción comienza en una pantalla principal desde la cual el usuario puede acceder al módulo de orientación en salud, al módulo de asistencia farmacéutica o a las opciones de atención humana.

El recorrido general contempla:

1. Acceso a la pantalla principal.
2. Selección del tipo de consulta.
3. Introducción de información mediante conversación o formularios.
4. Estado de carga.
5. Presentación de una respuesta, reconocimiento de incertidumbre o mensaje de error.
6. Consulta de fuentes de información.
7. Posibilidad de continuar, reformular, reintentar o solicitar atención humana.
8. Finalización o inicio de una nueva consulta.

La atención humana se plantea como una alternativa transversal, disponible durante todo el recorrido.

Ante una posible emergencia médica, el usuario debe buscar atención inmediata sin esperar una respuesta del asistente.

El diagrama de flujo representa el comportamiento previsto de la aplicación y no una funcionalidad actualmente implementada.

### Diagrama del flujo de interacción

![Flujo de interacción — Asistente integral de salud. Diagrama con la pantalla principal en la parte superior, el módulo de orientación en salud a la izquierda, el módulo de asistencia farmacéutica a la derecha, el panel de atención humana como sección transversal y una ruta prioritaria de emergencia médica.](docs/flujo-interaccion-asistente-integral-de-salud.png)

*Prototipo de orientación sanitaria y asistencia farmacéutica con supervisión humana.*

Archivos del diagrama:

- [Imagen vectorial (SVG)](docs/flujo-interaccion-asistente-integral-de-salud.svg): ábrela en un navegador.
- [Código fuente en Mermaid](docs/flujo-interaccion-asistente-integral-de-salud.mermaid): permite editar y regenerar el diagrama.

#### Cómo interpretar el diagrama

| Elemento | Significado |
|---|---|
| Óvalos | Inicio y finalización del recorrido. |
| Rectángulos | Pantallas, acciones o procesos. |
| Rombos | Decisiones, con sus salidas etiquetadas. |
| Hexágonos ① | Conectores de retorno: «Volver al inicio» y «Nueva consulta». |
| Flechas continuas | Recorrido principal. |
| Flechas punteadas verdes | Acceso a la atención humana, disponible en cualquier estado. |
| Flechas rojas gruesas | Ruta prioritaria de emergencia médica. |

Los estados de la interfaz se identifican con símbolos, además del color:

| Símbolo | Estado |
|---|---|
| ⏳ | Estado de carga |
| ✔ | Estado de respuesta |
| ❓ | Estado de incertidumbre |
| ∅ | Estado sin resultados |
| ✖ | Estado de error técnico |
| ⚠ | Emergencia médica |
| ● ○ ◐ | Disponible, agotado y sin confirmar |

Para regenerar los archivos a partir del código fuente se puede utilizar [Mermaid CLI](https://github.com/mermaid-js/mermaid-cli):

```bash
mmdc -i docs/flujo-interaccion-asistente-integral-de-salud.mermaid -o docs/flujo-interaccion-asistente-integral-de-salud.svg
```

## 7. Principios de diseño

### Accesibilidad

La interfaz prioriza una navegación comprensible, textos legibles, controles de tamaño adecuado y una distribución adaptable a diferentes dispositivos.

### Mobile First

El diseño parte de las necesidades de los usuarios de dispositivos móviles y se adapta progresivamente a pantallas de mayor tamaño mediante media queries.

### Transparencia

El asistente debe comunicar sus limitaciones, identificar las fuentes de información y reconocer situaciones en las que no dispone de información suficiente.

### Control humano

La inteligencia artificial se plantea como una herramienta complementaria. Los profesionales de salud conservan la responsabilidad de realizar valoraciones clínicas y tomar decisiones médicas.

### Seguridad y privacidad

El diseño contempla la protección de la información personal y médica como un principio fundamental para futuras etapas de desarrollo.

La maqueta no requiere ni debe utilizar información clínica real.

### Autonomía del usuario

El usuario debe poder consultar las fuentes, reformular sus preguntas, solicitar atención humana o finalizar la interacción.

## 8. Identidad visual

La identidad visual busca transmitir tranquilidad, cercanía, confianza y profesionalismo mediante una combinación de tonos verdes y fondos cálidos.

| Color | Código hexadecimal | Uso |
|---|---|---|
| Verde principal | `#287D70` | Botones y elementos principales |
| Verde oscuro | `#206359` | Elementos interactivos |
| Verde menta | `#DDEFE7` | Fondos complementarios |
| Blanco cálido | `#F8F7F2` | Fondo general |
| Blanco | `#FFFFFF` | Tarjetas y formularios |
| Verde suave | `#E5F0EA` | Barra lateral |
| Verde oscuro de texto | `#23443E` | Texto principal |
| Verde grisáceo | `#536B65` | Texto secundario |
| Verde claro | `#C8DED5` | Bordes |
| Rojo | `#B42318` | Emergencias y errores |
| Rojo suave | `#FFF0ED` | Fondos de alertas |
| Amarillo oscuro | `#765000` | Advertencias e incertidumbre |
| Amarillo suave | `#FFF8E6` | Fondos de advertencias |

**Tipografía:** Nunito Sans, integrada mediante Google Fonts.

La interfaz utiliza una barra lateral de navegación, tarjetas de servicios, formularios y componentes visuales reutilizables.

## 9. Tecnologías utilizadas

| Tecnología | Propósito |
|---|---|
| HTML5 | Estructura semántica de las páginas. |
| CSS3 | Presentación visual y estilos reutilizables. |
| Flexbox | Distribución y alineación de componentes. |
| CSS Grid | Organización de formularios y tarjetas. |
| Media Queries | Adaptación a diferentes tamaños de pantalla. |
| Google Fonts | Integración de la tipografía Nunito Sans. |
| Markdown | Documentación del proyecto. |
| Mermaid | Código fuente editable del diagrama de flujo de interacción. |

No se utilizan frameworks, librerías de JavaScript ni servicios de backend en esta etapa.

## 10. Estructura del proyecto

- `index.html`: pantalla principal y acceso a los servicios.
- `sintomas.html`: maquetación del módulo de orientación en salud.
- `medicamentos.html`: maquetación del módulo de asistencia farmacéutica.
- `css/styles.css`: hoja de estilos general y responsive.
- `docs/`: diagrama del flujo de interacción en formatos `.mermaid`, `.svg` y `.png`.
- `README.md`: documentación del proyecto.

Las tres páginas comparten una misma hoja de estilos para mantener la coherencia visual y facilitar el mantenimiento del código.

## 11. Cómo visualizar el proyecto

1. Descargar o clonar el repositorio.
2. Abrir la carpeta del proyecto en un editor de código.
3. Abrir el archivo `index.html` directamente en el navegador o mediante la extensión Live Server de Visual Studio Code.
4. Utilizar la navegación para explorar los diferentes módulos.

No es necesario instalar dependencias ni configurar un servidor de aplicaciones.

La carga de la tipografía externa requiere acceso a Google Fonts. En caso de no estar disponible, el navegador utilizará una fuente alternativa.

## 12. Alcance actual

El proyecto se encuentra en una primera etapa de diseño y maquetación.

### Elementos desarrollados

- Pantalla principal.
- Navegación entre páginas.
- Interfaz del módulo de orientación en salud.
- Interfaz del módulo farmacéutico.
- Formularios de consulta.
- Tarjetas de resultados.
- Representación visual de los estados de interacción.
- Avisos de emergencia y límites de la inteligencia artificial.
- Representación de opciones de atención humana.
- Diseño responsive bajo la metodología Mobile First.
- Definición del flujo de interacción.

### Elementos no implementados

- Procesamiento dinámico de consultas.
- Validación y gestión de formularios.
- Integración con modelos de inteligencia artificial.
- Consulta automatizada de fuentes médicas.
- Conexión con inventarios farmacéuticos.
- Integración con EPS, IPS y hospitales.
- Bases de datos.
- Autenticación de usuarios.
- Almacenamiento de información clínica.
- Servicios reales de contacto y agendamiento.

Los formularios, respuestas, estados y resultados representan componentes visuales de una futura aplicación.

## 13. Proyección a futuro

En posteriores etapas de desarrollo se contempla evaluar la incorporación de:

- Interacciones dinámicas mediante JavaScript.
- Integración con modelos de inteligencia artificial.
- Consulta de fuentes sanitarias verificables.
- Generación de resúmenes de síntomas reportados por el usuario para facilitar su comunicación con profesionales de salud.
- Integración autorizada con servicios de EPS e IPS.
- Consulta actualizada de inventarios farmacéuticos.
- Canales de atención humana.
- Mecanismos de protección de datos y seguridad.

Cualquier implementación real en el sector sanitario requerirá validación clínica, evaluación de riesgos, autorización de las entidades correspondientes y cumplimiento de la normativa aplicable.

## 14. Pruebas de usabilidad

La evaluación del prototipo contempla pruebas con otros usuarios para identificar dificultades de navegación, comprensión y accesibilidad.

Se propone evaluar:

- Facilidad para acceder a los módulos.
- Comprensión de los formularios.
- Identificación de los estados de interacción.
- Visibilidad de las fuentes.
- Comprensión de los avisos de límites.
- Diferenciación entre los estados de disponibilidad farmacéutica.
- Facilidad para encontrar las opciones de atención humana.
- Adaptación de la interfaz a dispositivos móviles.

Los hallazgos de estas pruebas permitirán identificar oportunidades de mejora en la maquetación.

## 15. Aviso importante

Este proyecto tiene fines exclusivamente educativos.

Actualmente no existe una inteligencia artificial conectada ni se realizan consultas médicas, diagnósticos, clasificaciones de triage, búsquedas reales de medicamentos o tratamientos personalizados.

La información de ejemplo no debe utilizarse para tomar decisiones clínicas.

Una valoración realizada por un profesional de salud es la forma adecuada de evaluar síntomas y determinar la atención necesaria.

Ante una emergencia médica, se debe buscar atención inmediata.

---

Proyecto desarrollado en el contexto del proceso formativo de Riwi.