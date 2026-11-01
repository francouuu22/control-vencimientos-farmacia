# Sistema de Control de Vencimientos

## Farmacia San Antonio

### 1. Descripción del proyecto

El presente proyecto propone el diseño de un sistema de información para mejorar el control de vencimientos de medicamentos en Farmacia San Antonio, ubicada en Medrano, Mendoza.

Actualmente, el control de vencimientos se realiza principalmente mediante revisiones físicas y etiquetas visuales. No existe un registro digital sistemático que permita consultar las fechas de vencimiento de los productos recibidos.

### 2. Problemática detectada

Se identificaron las siguientes dificultades:

* Falta de registro sistemático de fechas de vencimiento al recibir mercadería.
* Necesidad de revisar físicamente los productos para detectar próximos vencimientos.
* Dificultad para controlar grandes cantidades de stock.
* Riesgo de pérdidas económicas por productos vencidos o próximos a vencer.

### 3. Objetivo general

Proponer un sistema de información que permita registrar, organizar y monitorear las fechas de vencimiento de los medicamentos, generando alertas oportunas para facilitar el control y la toma de decisiones.

### 4. Funcionalidades propuestas

* Registrar productos, lotes, cantidades, fechas de recepción y vencimiento.
* Identificar la ubicación de los productos dentro de la farmacia.
* Almacenar y consultar los registros.
* Evaluar diariamente las fechas de vencimiento.
* Generar alertas sobre productos próximos a vencer.
* Permitir que el farmacéutico responsable revise las alertas y determine las acciones correspondientes.

El sistema funcionará como complemento del software de gestión existente, sin reemplazarlo ni asumir decisiones profesionales.

### 5. Organización del proyecto

El proyecto contempla las siguientes historias de usuario:

* **HU-01: Registro de vencimientos.** Registrar los datos de los productos recibidos para mantener actualizada la información.
* **HU-02: Generación de alertas.** Detectar productos próximos a vencer mediante una evaluación diaria.
* **HU-03: Gestión de alertas.** Permitir al farmacéutico consultar las alertas y decidir las acciones necesarias.

### 6. Herramientas utilizadas

* GitHub: alojamiento y documentación del proyecto.
* Git: control de versiones.
* GitHub Projects: organización y seguimiento de tareas.
* BPMN 2.0: modelado del proceso de control de vencimientos.

### 7. Declaración de uso de inteligencia artificial

Durante el desarrollo de este proyecto se utilizó ChatGPT (OpenAI) como herramienta de asistencia para el análisis, diseño y documentación de la propuesta tecnológica.

**Propósitos de utilización:**

* Analizar la problemática del control de vencimientos en Farmacia San Antonio.
* Organizar y modelar el proceso mediante BPMN 2.0.
* Formular historias de usuario para las funcionalidades propuestas.
* Definir indicadores de control y estándares de desempeño.
* Revisar y mejorar la documentación del proyecto.

**Ejemplos de consultas realizadas (prompts):**

* "Analizá la situación actual del control de vencimientos de Farmacia San Antonio e identificá sus principales problemas."
* "Ayudame a modelar mediante BPMN el proceso de recepción, registro y control de vencimientos."
* "Formulá tres historias de usuario para el sistema propuesto utilizando el formato Como usuario, quiero una funcionalidad, para obtener un beneficio."
* "Proponé indicadores de control y estándares de desempeño para evaluar el funcionamiento del sistema."

**Revisión y participación humana:**

Los resultados proporcionados por la herramienta fueron revisados, contrastados con la información real de la farmacia y adaptados a las consignas de la asignatura.

Se realizaron correcciones sobre la distribución de responsabilidades, el funcionamiento del sistema, el modelado del proceso y las funcionalidades propuestas. También se verificó que el sistema genere alertas, pero que las decisiones profesionales permanezcan bajo responsabilidad del farmacéutico.

La herramienta de inteligencia artificial se utilizó como apoyo y no como sustituto del análisis y las decisiones del estudiante. La responsabilidad final sobre el contenido presentado corresponde al autor del trabajo.


### 8. Alcance del proyecto

Este trabajo constituye una propuesta de mejora tecnológica. No representa un sistema implementado ni una integración efectiva con el software de gestión Plex utilizado actualmente por la farmacia.

## 9. Flujo general del proceso

1. Recepción de mercadería.
2. Verificación de productos y fechas de vencimiento.
3. Registro de los datos en el sistema.
4. Evaluación diaria de las fechas registradas.
5. Generación de alertas cuando corresponda.
6. Revisión de alertas y decisión del farmacéutico responsable.
7. Ejecución de las acciones indicadas.

## 10. Indicadores de control y estándares de desempeño

Para evaluar el funcionamiento del sistema propuesto se establecen los siguientes indicadores:

| Indicador                | Criterio de medición                                                                  | Estándar propuesto                |
| ------------------------ | ------------------------------------------------------------------------------------- | --------------------------------- |
| Registro de vencimientos | Porcentaje de productos recibidos con sus fechas de vencimiento registradas.          | 100 % de los productos recibidos. |
| Evaluación de fechas     | Frecuencia con la que el sistema analiza los registros.                               | Una evaluación diaria.            |
| Generación de alertas    | Porcentaje de productos que cumplen el criterio de alerta y generan una notificación. | 100 % de los casos detectados.    |
| Revisión de alertas      | Tiempo transcurrido entre la generación de una alerta y su revisión profesional.      | Dentro de las 24 horas.           |

Estos indicadores permitirán comparar el desempeño esperado con el funcionamiento real del sistema, detectar posibles desviaciones y establecer medidas correctivas.

Los estándares indicados son valores propuestos para el proyecto y deberán evaluarse una vez que el sistema sea implementado.


