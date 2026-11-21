# GA-SUM-02 — EXP-1

## Exposición del primer corte

**Asignatura:** Ingeniería de Requisitos (ISR-401)  
**Universidad:** Universidad Técnica Estatal de Quevedo (UTEQ)  
**Carrera:** Ingeniería de Software  
**Grupo:** CES  
**Herramienta seleccionada:** ReqView  
**Caso de aplicación:** Sistema de Tutorías y Seguimiento Académico

---

## 1. Integrantes

- Córdova Carreño Mayra Lucila.
- Espinoza Pivaque Angelo Maximiliano.
- Saltos Tello Joseph Orlando.

## 2. Objetivo

Analizar ReqView como herramienta automatizada de apoyo a la Ingeniería de Requisitos, describiendo sus características, funcionalidades, ventajas, limitaciones y posibilidades de aplicación al Sistema de Tutorías y Seguimiento Académico.

La actividad integra fundamentación conceptual, comparación con Jira, análisis crítico y una demostración práctica mediante artefactos documentados en ReqView.

## 3. Contenido de la exposición

La presentación aborda los siguientes temas:

1. Introducción y fundamentos de la gestión de requisitos.
2. Diferencias entre elicitación y gestión de requisitos.
3. Definición y funcionalidades de ReqView.
4. Ventajas, limitaciones y riesgos de la herramienta.
5. Comparación entre ReqView y Jira.
6. Análisis crítico y recomendación para el PFC.
7. Aplicación al Sistema de Tutorías y Seguimiento Académico.
8. Registro y clasificación de artefactos.
9. Gestión de cambios y trazabilidad.
10. Resultados, conclusiones y referencias bibliográficas.

La presentación está organizada en 15 diapositivas, incluida la sección de referencias bibliográficas.

## 4. Distribución del trabajo — Grupo CES

La elaboración de la actividad se distribuyó entre los tres integrantes para promover la participación en la investigación, preparación de materiales y exposición oral.

| Integrante | Responsabilidades | Diapositivas | Tiempo estimado |
|---|---|---|---|
| Córdova Carreño Mayra Lucila | Introducción, fundamentos conceptuales, definición y funcionalidades de ReqView. | 1–5 | 4 minutos |
| Espinoza Pivaque Angelo Maximiliano | Ventajas, limitaciones, riesgos, comparación con Jira y análisis crítico. | 6–9 | 4 minutos |
| Saltos Tello Joseph Orlando | Aplicación práctica, documentación de artefactos, trazabilidad, evidencias y conclusiones. | 10–14 | 4 minutos |

La diapositiva 15 corresponde a las referencias bibliográficas.

### 4.1. Responsabilidades compartidas

- Investigación y revisión de información técnica.
- Verificación de fuentes bibliográficas.
- Revisión de la presentación en LaTeX/Beamer.
- Compilación y comprobación del documento PDF.
- Preparación y revisión de la demostración práctica.
- Ensayo de la exposición oral.
- Preparación de respuestas a posibles preguntas.
- Registro de contribuciones mediante commits de GitHub.

### 4.2. Seguimiento de contribuciones

Cada integrante registra sus aportes mediante su cuenta personal de GitHub.

La participación puede verificarse a través de los archivos incorporados, las evidencias y el historial de commits.

El trabajo colaborativo implica que todos los integrantes deben comprender el contenido general de la presentación y las funcionalidades utilizadas en la demostración.

## 5. Demostración práctica de ReqView

### 5.1. Caso de aplicación

**Proyecto:** Sistema de Tutorías y Seguimiento Académico.

El caso se centra en la necesidad de un estudiante de solicitar apoyo académico cuando presenta dificultades en una asignatura o tema específico.

Para representar este escenario se documentaron en ReqView una necesidad del usuario, un requisito funcional y un caso de prueba.

La demostración corresponde a la gestión de requisitos y no a la implementación de un sistema informático funcional.

### 5.2. Objetivo de la demostración

Mostrar cómo ReqView permite:

- Documentar necesidades y requisitos.
- Organizar artefactos mediante documentos estructurados.
- Asignar atributos y estados.
- Consultar el historial de modificaciones.
- Establecer relaciones de trazabilidad.
- Apoyar el seguimiento de los requisitos.

### 5.3. Artefactos documentados

| Identificador | Clasificación | Descripción |
|---|---|---|
| N-01 | Necesidad del usuario | El estudiante necesita un medio para solicitar apoyo académico a un docente cuando presenta dificultades en una asignatura o tema específico. |
| RF-01 | Requisito funcional | El sistema deberá permitir al estudiante registrar una solicitud de tutoría indicando la asignatura, el tema que necesita revisar y una descripción de la dificultad que presenta. |
| CP-01 | Caso de prueba | Verificar que el estudiante pueda registrar una solicitud de tutoría indicando la asignatura, el tema y una descripción de la dificultad, y que el sistema guarde la solicitud asociada al estudiante. |

### 5.4. Clasificación y estados

En el documento de ReqView se registraron los siguientes estados:

| Artefacto | Estado |
|---|---|
| N-01 | Aprobado |
| RF-01 | En revisión |
| CP-01 | Pendiente |

Estos estados forman parte del ejemplo académico configurado en la herramienta. No representan una validación formal por parte de un cliente real.

### 5.5. Relaciones de trazabilidad

La demostración establece relaciones entre los tres artefactos:

**N-01 → RF-01 → CP-01**

La necesidad N-01 se relaciona con el requisito funcional RF-01, mientras que este se vincula con el caso de prueba CP-01.

Estas relaciones permiten identificar el origen de un requisito y el elemento destinado a verificar su cumplimiento.

### 5.6. Historial de cambios

ReqView permite consultar las modificaciones realizadas sobre los artefactos documentados.

En la demostración se presentan registros del historial de cambios de RF-01 y CP-01, incluyendo modificaciones de contenido y atributos.

Estas evidencias muestran las funciones de seguimiento y revisión disponibles en la herramienta.

**Alcance:** el caso de prueba CP-01 fue documentado en ReqView, pero no se ejecutó sobre un sistema de tutorías implementado.

### 5.7. Participación durante la demostración

| Integrante | Participación |
|---|---|
| Córdova Carreño Mayra Lucila | Presentación del caso y explicación de las necesidades y los requisitos documentados. |
| Espinoza Pivaque Angelo Maximiliano | Explicación de los atributos, estados y relaciones de trazabilidad. |
| Saltos Tello Joseph Orlando | Presentación de la estructura del proyecto en ReqView, historial de cambios y evidencias. |

Los tres integrantes participan en la explicación de la aplicación práctica.

## 6. Evidencias de ReqView

Las evidencias originales se encuentran en el directorio `evidencias/`.

| Evidencia | Contenido |
|---|---|
| EVID-06 | Estados asignados a los artefactos documentados. |
| EVID-08 | Estructura y contenido del documento de requisitos. |
| EVID-09 | Historial de modificaciones del requisito RF-01. |
| EVID-10 | Historial de modificaciones del caso de prueba CP-01. |
| EVID-11 | Relación de trazabilidad entre los artefactos. |

Las capturas corresponden al uso de ReqView para el caso académico y permiten contrastar la explicación presentada con los elementos registrados en la herramienta.

No se utilizan datos personales reales de estudiantes o docentes.

## 7. Estructura del repositorio

La actividad se encuentra en el directorio `EXP-1/` del repositorio del grupo CES.

```text
EXP-1/
├── README.md
├── main.tex
├── main.pdf
├── referencias.bib
└── evidencias/
    ├── EVID-06_Estados_Requisitos_ReqView.png
    ├── EVID-08_Estructura_y_Contenido_Documento_REQ_ReqView.png
    ├── EVID-09_Historial_Cambio_RF01_ReqView.png
    ├── EVID-10_Historial_Cambio_CP01_ReqView.png
    └── EVID-11_Trazabilidad_RF01_ReqView.png
```

### 7.1. Descripción de archivos

| Archivo o directorio | Descripción |
|---|---|
| `README.md` | Documentación de la actividad, responsabilidades, evidencias e instrucciones de compilación. |
| `main.tex` | Código fuente de la presentación elaborada en LaTeX/Beamer. |
| `main.pdf` | Versión compilada de la presentación. |
| `referencias.bib` | Base de datos bibliográfica en formato BibTeX. |
| `evidencias/` | Capturas originales de la demostración práctica en ReqView. |

## 8. Referencias bibliográficas

Las referencias se administran mediante el archivo `referencias.bib`.

Se utilizan fuentes relacionadas con Ingeniería de Requisitos, gestión de requisitos, trazabilidad y documentación oficial de las herramientas analizadas.

Entre las fuentes consultadas se encuentran:

- International Requirements Engineering Board (IREB).
- IEEE Computer Society — SWEBOK Guide.
- Publicaciones académicas sobre Ingeniería de Requisitos y trazabilidad.
- Documentación oficial de ReqView.
- Documentación oficial de Atlassian Jira.

Las referencias utilizadas en la presentación se citan mediante `\cite{...}` y se presentan utilizando el estilo bibliográfico IEEEtran.

Los datos bibliográficos fueron revisados por el equipo para comprobar su correspondencia con las fuentes consultadas.

## 9. Compilación reproducible

### 9.1. Herramientas necesarias

La presentación se elaboró en LaTeX utilizando la clase Beamer.

Para reproducir el documento se requiere:

- Una distribución LaTeX, como TeX Live o MiKTeX, o un proyecto de Overleaf.
- Compilador pdfLaTeX.
- Procesador bibliográfico BibTeX.
- Estilo bibliográfico IEEEtran.

### 9.2. Dependencias

El proyecto requiere la clase `beamer` y los paquetes utilizados en `main.tex`, entre ellos:

- `inputenc`
- `fontenc`
- `babel` con soporte para español
- `tgheros`
- `tikz`
- `cite`
- `url`

También deben estar disponibles los demás paquetes declarados en el preámbulo del documento, así como el archivo `IEEEtran.bst`.

### 9.3. Compilación local

Desde la raíz del repositorio, acceder a la carpeta correspondiente:

```bash
cd EXP-1
```

Ejecutar los comandos en el siguiente orden:

```bash
pdflatex -interaction=nonstopmode -halt-on-error main.tex
bibtex main
pdflatex -interaction=nonstopmode -halt-on-error main.tex
pdflatex -interaction=nonstopmode -halt-on-error main.tex
```

La primera ejecución de pdfLaTeX genera los archivos auxiliares.

BibTeX procesa las referencias bibliográficas almacenadas en `referencias.bib`.

Las dos ejecuciones posteriores de pdfLaTeX permiten resolver las citas, actualizar la bibliografía y generar la versión final del documento.

El resultado es el archivo `main.pdf`.

### 9.4. Compilación en Overleaf

1. Abrir el proyecto en Overleaf.
2. Incorporar `main.tex` y `referencias.bib`.
3. Incorporar la carpeta `evidencias/` con las imágenes originales.
4. Seleccionar `main.tex` como documento principal.
5. Configurar pdfLaTeX como compilador.
6. Ejecutar la recompilación.
7. Revisar las diapositivas, imágenes y referencias bibliográficas.
8. Descargar el archivo PDF generado.

Overleaf puede procesar automáticamente las referencias mediante BibTeX.

### 9.5. Verificación de la compilación

Para comprobar el resultado se debe verificar que:

- La compilación finalice sin errores.
- Todas las diapositivas se visualicen correctamente.
- Las imágenes se incorporen sin errores de ruta.
- Las citas bibliográficas estén resueltas.
- La bibliografía aparezca en estilo IEEE.
- Los textos y elementos gráficos permanezcan dentro de los márgenes.
- El archivo `main.pdf` corresponda al código fuente actualizado.

### 9.6. Archivos auxiliares

Durante la compilación pueden generarse archivos como:

- `.aux`
- `.log`
- `.out`
- `.nav`
- `.snm`
- `.toc`
- `.bbl`
- `.blg`

Estos archivos son auxiliares y pueden regenerarse mediante el procedimiento de compilación indicado.

No es necesario incluirlos en el repositorio.

## 10. Criterios de diseño de la presentación

La presentación utiliza:

- Formato panorámico 16:9.
- Tipografía TeX Gyre Heros.
- Paleta de colores inspirada en ReqView.
- Encabezados y pies de página uniformes.
- Tarjetas y elementos gráficos para sintetizar conceptos.
- Capturas originales de la herramienta.
- Referencias bibliográficas numeradas.

El diseño busca favorecer la legibilidad, la claridad conceptual y la explicación oral durante la exposición.

## 11. Uso de inteligencia artificial

**Herramienta:** ChatGPT (GPT-6).

**Finalidad del uso:** apoyo en la organización del contenido, redacción, elaboración y corrección del código LaTeX/Beamer, estructuración del README y revisión de referencias bibliográficas.

**Verificación:** los integrantes revisaron la información con fuentes académicas y documentación oficial, comprobaron los datos bibliográficos y revisaron el resultado de la compilación en Overleaf.

Las evidencias de ReqView corresponden al trabajo realizado con la herramienta y no fueron generadas artificialmente.

La responsabilidad académica sobre el contenido, las decisiones y la exposición corresponde a los integrantes del grupo CES.

## 12. Entrega de la actividad

El repositorio contiene los archivos correspondientes a la presentación, bibliografía y evidencias de la demostración práctica.

**Repositorio de la actividad:**

https://github.com/mcordovaac2/ISR401-CES/tree/main/EXP-1

La entrega al Sistema de Gestión Académica (SGA) se realiza mediante una constancia de repositorio en formato PDF de una página, que incluye:

- Identificación de los integrantes.
- Código y nombre de la actividad.
- Fecha límite de entrega.
- Enlace al repositorio de GitHub.

La presentación y demostración se realizan conforme a las indicaciones del docente.
