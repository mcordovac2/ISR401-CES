# GA-SUM-02 — EXP-1

## Exposición del primer corte

**Asignatura:** Ingeniería de Requisitos (ISR-401)  
**Universidad:** Universidad Técnica Estatal de Quevedo  
**Grupo:** CES  
**Herramienta seleccionada:** ReqView  
**Caso de aplicación:** Sistema de Tutorías y Seguimiento Académico

## Integrantes

- Córdova Carreño Mayra Lucila.
- Espinoza Pivaque Angelo Maximiliano.
- Saltos Tello Joseph Orlando.

## Objetivo

Analizar ReqView como herramienta de apoyo a la gestión de requisitos,
explicando sus funcionalidades, ventajas, limitaciones y posibilidades
de aplicación al Proyecto de Fin de Curso.

La exposición incluye una comparación con Jira y una demostración
propia para documentar, clasificar y relacionar requisitos.

## Contenido de la exposición

1. Introducción y fundamentación conceptual.
2. Características y funcionalidades de ReqView.
3. Ventajas, limitaciones y riesgos.
4. Comparación con Jira.
5. Recomendación de uso para el PFC.
6. Aplicación práctica y demostración.
7. Conclusiones.
8. Referencias bibliográficas.

## Distribución del trabajo — Grupo CES

Las responsabilidades se distribuyen entre los tres integrantes
para preparar la investigación, las diapositivas, la demostración
y la exposición oral.

| Integrante | Responsabilidades asignadas | Diapositivas previstas | Tiempo estimado |
|---|---|---|---|
| Córdova Carreño Mayra Lucila | Introducción, fundamentación conceptual, definición y funcionalidades de ReqView. Participación en la demostración. | 1–5 | 4 minutos |
| Espinoza Pivaque Angelo Maximiliano | Ventajas, limitaciones, riesgos, comparación con Jira y recomendación para el PFC. Participación en la demostración. | 6–9 | 4 minutos |
| Saltos Tello Joseph Orlando | Aplicación práctica, configuración de ReqView, evidencias y conclusiones. Participación en la demostración. | 10–14 | 4 minutos |

La distribución corresponde a la planificación del equipo.
La ubicación final de las referencias se ajustará durante
la integración de la presentación.

La versión final debe contener entre 10 y 16 diapositivas,
incluidas las páginas de referencias, y respetar los
12 minutos de exposición previstos.

### Responsabilidades compartidas

- Investigar y contrastar información sobre Ingeniería de Requisitos
  y las herramientas analizadas.
- Verificar las referencias y aplicar el formato IEEE.
- Revisar la precisión técnica y la coherencia de la presentación.
- Comprobar la compilación del documento LaTeX/Beamer.
- Obtener evidencias originales de la demostración.
- Ensayar la exposición y preparar respuestas a preguntas.
- Registrar las contribuciones mediante commits identificables.

### Seguimiento de contribuciones

Cada integrante registra sus aportes utilizando su propia cuenta
de GitHub.

Los aportes efectivamente realizados se verificarán mediante
los archivos, las evidencias, el historial de commits y la
participación en la exposición.

Todos los integrantes deben comprender la presentación completa,
incluidos los requisitos y las decisiones de la demostración.

## Demostración práctica de ReqView

### Caso de aplicación

La demostración se relaciona con el proceso de solicitud
de tutorías del PFC.

Se propone representar una necesidad del estudiante,
el requisito que responde a esa necesidad y un caso de
prueba relacionado.

El ejemplo utiliza datos ficticios y no acredita que
el sistema del PFC ya haya sido implementado.

### Objetivo de la demostración

Mostrar cómo se documentan los elementos del ejemplo,
se clasifican mediante atributos y se relacionan mediante
enlaces de trazabilidad en ReqView.

### Ejemplo propuesto

| ID | Elemento | Descripción |
|---|---|---|
| N-01 | Necesidad | El estudiante necesita solicitar apoyo académico al docente. |
| RF-01 | Requisito funcional | El sistema deberá permitir al estudiante registrar una solicitud de tutoría indicando la asignatura y el tema que necesita revisar. |
| CP-01 | Caso de prueba | Registrar una solicitud con asignatura y tema; comprobar que queda guardada y asociada al estudiante. |

### Relaciones propuestas

- RF-01 se relaciona con N-01 para identificar la necesidad
  que lo origina.
- CP-01 se relaciona con RF-01 para identificar el requisito
  que busca verificar.

Los tipos de enlace y su dirección se configurarán de manera
consistente en el proyecto de ReqView.

### Ejemplo de cambio

Se propone añadir una descripción de la dificultad a la
solicitud de tutoría.

Este cambio requiere revisar RF-01 y actualizar CP-01
para comprobar el nuevo dato.

Registrar el caso de prueba en ReqView no equivale a ejecutarlo
sobre el sistema desarrollado.

### Distribución de responsabilidades prácticas

| Integrante | Preparación | Participación en la demostración |
|---|---|---|
| Córdova Carreño Mayra Lucila | Revisión de los requisitos candidatos, identificadores y descripciones. | Explicación del registro de requisitos. |
| Espinoza Pivaque Angelo Maximiliano | Clasificación, atributos y relaciones de trazabilidad. | Explicación de atributos, enlaces y revisión ante cambios. |
| Saltos Tello Joseph Orlando | Configuración del proyecto e incorporación de los elementos acordados. | Presentación de la estructura y funcionamiento del proyecto. |

### Procedimiento previsto

1. Presentar el proyecto y su estructura en ReqView.
2. Mostrar la necesidad, el requisito y el caso de prueba.
3. Explicar los atributos utilizados.
4. Mostrar las relaciones de trazabilidad.
5. Introducir el cambio propuesto y revisar los elementos relacionados.
6. Explicar los resultados y las limitaciones de la demostración.

### Evidencias

Cuando se complete la configuración, se incorporarán:

- Capturas originales del proyecto.
- Elementos documentados y clasificados.
- Atributos y relaciones de trazabilidad.
- Archivos del proyecto o exportaciones que permitan revisar el ejemplo.

El ejemplo se mantiene como propuesta hasta que haya sido
configurado y comprobado en ReqView.

No se publicarán datos personales de estudiantes o docentes reales.

## Archivos de la actividad

| Archivo o directorio | Descripción |
|---|---|
| `README.md` | Organización del equipo, estado del trabajo e instrucciones de compilación. |
| `main.tex` | Presentación Beamer con las diapositivas 1–9 y el bloque de referencias. |
| `referencias.bib` | Fuentes académicas y documentación oficial seleccionadas. |
| `main.pdf` | Presentación compilada; debe actualizarse después de modificar el código o la bibliografía. |
| `figuras/` | Directorio previsto para capturas originales de la demostración. |

Las capturas y los artefactos prácticos se incorporarán cuando
el equipo los haya elaborado y verificado.

## Referencias bibliográficas

El archivo `referencias.bib` reúne las fuentes seleccionadas.
La bibliografía final debe mostrar únicamente las referencias
citadas y efectivamente utilizadas.

### Libros y documentos de referencia

- Klaus Pohl — Requirements Engineering: Fundamentals,
  Principles, and Techniques (2025).
- IREB — CPRE Foundation Level Syllabus, versión 3.3.0 (2026).
- IEEE Computer Society — SWEBOK Guide, versión 4.0 (2024).

### Artículos científicos

- M. Ozkaya, G. Kardas y M. A. Kose,
  “An Analysis of the Features of Requirements Engineering Tools,”
  Systems, 2023.
  DOI: https://doi.org/10.3390/systems11120576

- M. Ruiz, J. Y. Hu y F. Dalpiaz,
  “Why don’t we trace? A study on the barriers to software
  traceability in practice,” Requirements Engineering, 2023.
  DOI: https://doi.org/10.1007/s00766-023-00408-9

### Documentación oficial de ReqView

- Set up Requirements Projects.
- Review Requirements Documents.
- Export Requirements to ReqIF.
- Custom Requirement Attributes.
- Requirements Traceability Links.

### Documentación oficial de Atlassian

- Using Jira for Requirements Management.

La comparación utiliza documentación de Jira Data Center;
sus afirmaciones no se generalizan automáticamente a todas
las ediciones de Jira.

### Integración de citas

Las diapositivas 6–9 incorporan citas numeradas mediante
`\cite{...}`.

La integración de las citas numeradas de las diapositivas
1–5 se completará durante su revisión final.

Los artículos científicos fundamentan los criterios de
análisis y los riesgos generales. La documentación oficial
respalda las funciones específicas de cada herramienta.

Antes de entregar, el equipo comprobará:

- Existencia y exactitud de las referencias.
- Correspondencia entre afirmaciones y fuentes.
- Al menos cuatro fuentes académicas o normas, con dos
  de los últimos cinco años, citadas donde se utilizan.
- Ausencia de citas sin resolver.
- Legibilidad de la bibliografía final.

## Compilación

La presentación utiliza LaTeX/Beamer en formato panorámico 16:9.

### Archivo principal y herramientas

- **Archivo principal desde la raíz:** `EXP-1/main.tex`.
- **Compilador:** pdfLaTeX.
- **Procesador bibliográfico:** BibTeX.
- **Estilo bibliográfico:** `IEEEtran`.
- **Archivo bibliográfico:** `EXP-1/referencias.bib`.

### Dependencias

Distribución MiKTeX o TeX Live con:

- Clase `beamer`.
- Paquetes `inputenc`, `fontenc`, `babel` con soporte para español,
  `tgheros`, `tikz`, `array`, `tabularx` y `colortbl`.
- Estilo bibliográfico `IEEEtran.bst`.

### Orden de comandos

Desde la raíz del repositorio, ejecutar uno por uno:

```sh
cd EXP-1
pdflatex -interaction=nonstopmode -halt-on-error main.tex
bibtex main
pdflatex -interaction=nonstopmode -halt-on-error main.tex
pdflatex -interaction=nonstopmode -halt-on-error main.tex
```

Si la terminal ya está dentro de `EXP-1`, omitir `cd EXP-1`.

El resultado es `EXP-1/main.pdf`.

### Abrir el PDF en Windows

Desde la carpeta `EXP-1`:

```powershell
Invoke-Item ".\main.pdf"
```

### Verificación

- Todos los comandos deben finalizar sin errores.
- Las citas deben aparecer numeradas, sin `[?]`.
- La bibliografía debe corresponder a las citas utilizadas.
- Los textos, tarjetas y tablas no deben superponerse
  ni exceder los márgenes.
- El PDF debe corresponder a los últimos cambios.

Si la compilación falla, puede permanecer un PDF anterior.

### Compilación en Overleaf

1. Cargar los archivos del proyecto.
2. Seleccionar `main.tex` como documento principal.
3. Utilizar pdfLaTeX como compilador.
4. Recompilar y revisar las citas y referencias.

Overleaf gestiona las ejecuciones de BibTeX al recompilar.

### Diseño

Se conserva la plantilla del equipo:

- Formato panorámico 16:9.
- Tipografía TeX Gyre Heros.
- Paleta naranja, marrón y crema.
- Encabezados y pies uniformes.
- Tarjetas originales y tarjetas de análisis con altura
  ajustada al contenido.
- Tablas con colores de la misma paleta.

### Archivos auxiliares

Los archivos `.aux`, `.log`, `.out`, `.nav`, `.snm`,
`.toc`, `.bbl` y `.blg` se generan durante la compilación.

No necesitan subirse si pueden regenerarse siguiendo
estas instrucciones.

## Uso de herramientas de inteligencia artificial

Se utilizó ChatGPT como apoyo para organizar el contenido,
buscar fuentes, preparar propuestas de redacción y elaborar
y corregir el código LaTeX/Beamer.

El equipo debe contrastar las afirmaciones con las fuentes,
comprobar la compilación y comprender los contenidos que expondrá.

Las referencias se revisaron mediante las páginas de las
editoriales y la documentación oficial de las herramientas.
La apariencia de las diapositivas se revisa en el PDF generado.

La declaración final de la presentación debe identificar
la herramienta, su versión cuando sea conocida, los usos
realizados y el procedimiento de verificación.

El ejemplo propuesto no se presenta como una demostración
ejecutada hasta contar con el proyecto y las evidencias originales.

La responsabilidad académica corresponde a los integrantes
del grupo CES.

## Estado del avance

Se han desarrollado las diapositivas 1–9:

- Diapositivas 1–5: introducción, fundamentación conceptual
  y funcionalidades de ReqView.
- Diapositivas 6–9: ventajas, limitaciones y riesgos,
  comparación con Jira y aplicación propuesta al PFC.

Se añadieron dos artículos científicos de 2023 y documentación
oficial para respaldar el análisis.

Se incorporó el bloque de bibliografía IEEE y las citas
de las diapositivas 6–9.

Falta completar:

- La parte práctica de Joseph.
- Los artefactos y las capturas originales de ReqView.
- Las conclusiones de la demostración.
- Las citas numeradas de las diapositivas 1–5.
- La declaración final de uso de IA.
- La revisión conjunta y la compilación final.

El equipo ajustará la distribución final para respetar
el límite de diapositivas y el tiempo de exposición.

## Entrega

En el repositorio se conservarán los archivos fuente,
la bibliografía, las evidencias públicas y el PDF compilado.

En el SGA se entregará únicamente el PDF de una página
con los datos informativos, la fecha límite y la URL completa
del repositorio en una sola línea.

El cierre se rige por el horario de exposición establecido
para el paralelo y las instrucciones del docente.