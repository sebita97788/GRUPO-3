
# GRUPO-3

<p align="center">
  <img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/2c3d0613-f51e-47d7-bd82-439b78384731" />
</p>



<div align="center">

# UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS

### FACULTAD DE INGENIERIA
### CARRERA DE INGENIERÍA DE SOFTWARE

<br>

# INFORME DE PROYECTO

## Nombre del proyecto
### ****

<br>

**Curso:**  
Desarrollo de Aplicaciones Open Source

**Sección:**  
7750

<br>

### Integrantes

| Integrante | Código |
|---|---|
| NICOLAS TANTALEAN GRANDA | U202410728 |
| WILMER SEBASTIAN GUTIERREZ LIZARBE| U202412044 |
| [Nombre completo 3] | [Código] |
| [Nombre completo 4] | [Código] |

<br>

**Docente:**  
Efrain Ricardo Bautista Ubillus

<br>

**Ciclo:**  
[2026-2]

<br>

**Lima, Perú**  
**2026**

</div>


---

# ÍNDICE

## Capítulo I: Introducción

### 1.1. Startup Profile
#### 1.1.1. Descripción de la Startup
HeavyMach tiene como objetivo transformar digitalmente la gestión, contratación y supervisión del alquiler de maquinaria pesada en las industrias de la construcción, minería e infraestructura, abarcando actividades desde la reserva de equipos y programación de mantenimientos hasta la emisión automatizada de comprobantes de pago. A través de su plataforma principal, HeavyMach permite a las empresas proveedoras y contratistas organizar de forma centralizada sus solicitudes de alquiler, asignar maquinaria y operadores de manera eficiente, y monitorear el estado operativo y financiero de sus flotas en tiempo real.

La solución busca resolver la falta de trazabilidad, la informalidad en la disponibilidad de equipos y los retrasos en los procesos administrativos en entornos donde las operaciones de obra deben adaptarse a cronogramas exigentes. Para ello, HeavyMach integra funcionalidades de catálogo dinámico con disponibilidad en tiempo real, programación de mantenimientos preventivos y correctivos, alertas automáticas de estado de máquina y emisión instantánea de facturación electrónica integrada a los estándares tributarios de SUNAT.

Una de las principales fortalezas del sistema es su capacidad para adaptarse a la realidad operativa del sector industrial: contempla la sincronización de datos entre personal de campo y administradores, la gestión transparente de valorizaciones por horas trabajadas, y dashboards especializados que reflejan el rendimiento de la flota y el cumplimiento de contratos en tiempo real. Esta solución aporta un valor diferencial tanto para los gestores de flota que planifican como para los contratistas que requieren equipos garantizados en obra.

**Misión:** Optimizar la comercialización, gestión operativa y trazabilidad tributaria del alquiler de maquinaria pesada mediante una plataforma inteligente, eficiente y adaptable a las necesidades del sector construcción e infraestructura.

**Visión:** HeavyMach aspira a convertirse en la plataforma tecnológica preferida por empresas de alquiler de maquinaria y contratistas en Latinoamérica, facilitando operaciones más eficientes, transparentes y formalizadas a través de la innovación digital aplicada al sector industrial.
#### 1.1.2. Perfiles de integrantes del equipo
* **Wilmer Sebastián Gutiérrez Lizarbe**
  * **Código:** U202412044
  * **Carrera:** Ingeniería de Software (5.º ciclo)
  * **Perfil:** Estudiante de Ingeniería de Software con conocimientos en desarrollo web (HTML5, CSS3, JavaScript/TypeScript, Angular), arquitectura backend (Java, Spring Boot) y gestión de bases de datos relacionales y no relacionales. Aporta al equipo capacidad analítica para el diseño de arquitecturas distribuidas, integración de APIs RESTful y lógica de negocio orientada a procesos industriales.
### 1.2. Solution Profile

#### 1.2.1. Antecedentes y problemática

##### 1.2.1.1. What

**¿Cuál es el problema?**

El problema se define como la ausencia de un recurso tecnológico centralizado capaz de organizar, planificar y supervisar el proceso de gestión, alquiler y mantenimiento de maquinaria pesada, así como la emisión de comprobantes de pago. Actualmente, la falta de un sistema digital unificado provoca **descoordinación**, **errores en la disponibilidad de equipos**, **pérdidas de tiempo por paradas no programadas**, **retrasos en la facturación electrónica** y **aumento de costos operativos** tanto para los proveedores de maquinaria como para las empresas contratistas. Esto genera impactos negativos en la eficiencia, la productividad de las obras y la liquidez de las PYMEs del sector.

##### 1.2.1.2. Who

**¿Quiénes están involucrados en el problema?**

Este problema involucra principalmente a **proveedores y gestores de flota de maquinaria pesada**, encargados de administrar el inventario, programar mantenimientos y asignar equipos; a **contratistas y jefes de obra**, responsables de la ejecución de proyectos de construcción o minería que requieren alquileres garantizados; a **técnicos de mantenimiento**, quienes registran las revisiones operativas de los equipos; y al **personal administrativo y contable**, que exige información exacta para la liquidación de horas máquina y la emisión de facturas electrónicas conformes a SUNAT. La falta de integración entre estos actores genera cuellos de botella que afectan directamente la continuidad de los proyectos.

##### 1.2.1.3. Where

**¿Dónde surge el problema?**

El problema surge en **obras de construcción, proyectos mineros, frentes de infraestructura y canteras** en todo el país, donde la ejecución de tareas requiere maquinaria en óptimas condiciones operativas. También se presenta en las **oficinas de control y centros administrativos de los proveedores**, donde la falta de visibilidad en tiempo real sobre la ubicación, estado técnico y disponibilidad de la flota limita la capacidad de respuesta ante imprevistos o solicitudes urgentes.

##### 1.2.1.4. When

**¿Cuándo se presenta el problema?**

El problema inicia desde la **búsqueda y reserva inicial de maquinaria**, cuando los contratistas no cuentan con información actualizada sobre la disponibilidad de equipos. Se intensifica durante la **ejecución en obra**, cuando ocurren averías imprevistas debido al descontrol en el historial de mantenimientos preventivos, y persiste hasta la etapa de **cierre del servicio y facturación**, donde se generan discrepancias en la liquidación de horas trabajadas y demoras en la emisión de comprobantes de pago.

##### 1.2.1.5. Why

**¿Por qué surge el problema?**

El problema se origina principalmente por la alta informalidad del sector y la continua dependencia de procesos manuales, tales como el registro de mantenimientos en papel, la coordinación de alquileres mediante mensajería informal y el cálculo manual de tarifas de alquiler. La ausencia de una solución SaaS integrada dificulta la comunicación fluida entre el personal operativo de obra y el área administrativa.

##### 1.2.1.6. How

**¿Cómo se utilizará el producto?**

La plataforma operará bajo un modelo distribuido accesible desde entornos web y móviles. Los clientes o contratistas navegarán por un catálogo interactivo con filtros por categoría, ubicación y precio para realizar reservas de maquinaria. Los proveedores gestionarán sus flotas, recibirán alertas automáticas para programar mantenimientos preventivos y monitorearán el estado de los contratos. Al finalizar el periodo de alquiler, la plataforma calculará automáticamente el monto correspondiente y generará la facturación electrónica integrada en cumplimiento con las normativas locales.

##### 1.2.1.7. How Much

**¿Cuál es la magnitud del problema?**

En el sector de la construcción e infraestructura, las averías no detectadas a tiempo por falta de mantenimiento representan pérdidas operativas de hasta un 25% en el tiempo de ejecución de una obra. Asimismo, las demoras administrativas y la falta de digitalización en el cobro y facturación electrónica afectan directamente la liquidez de más del 40% de las pequeñas y medianas empresas proveedoras de equipos.
#### 1.2.2. Lean UX Process
##### 1.2.2.1. Lean UX Problem Statements
##### 1.2.2.2. Lean UX Assumptions
##### 1.2.2.3. Lean UX Hypothesis Statements
##### 1.2.2.4. Lean UX Canvas

### 1.3. Segmentos objetivo

---

## Capítulo II: Requirements Elicitation & Analysis

### 2.1. Competidores
#### 2.1.1. Análisis competitivo
#### 2.1.2. Estrategias y tácticas frente a competidores

### 2.2. Entrevistas
#### 2.2.1. Diseño de entrevistas
#### 2.2.2. Registro de entrevistas
#### 2.2.3. Análisis de entrevistas

### 2.3. Needfinding
#### 2.3.1. User Personas
#### 2.3.2. User Task Matrix
#### 2.3.3. User Journey Mapping
#### 2.3.4. Empathy Mapping
#### 2.3.5. Big Picture Event Storming

### 2.4. Ubiquitous Language

---

## Capítulo III: Requirements Specification

### 3.1. User Stories

### 3.2. Impact Mapping

### 3.3. Product Backlog

---

## Capítulo IV: Product Implementation, Validation & Deployment

### 5.1. Software Configuration Management
#### 5.1.1. Software Development Environment Configuration
#### 5.1.2. Source Code Management
#### 5.1.3. Source Code Style Guide & Conventions
#### 5.1.4. Software Deployment Configuration

### 5.2. Landing Page, Services & Applications Implementation

#### 5.2.X. Sprint n
##### 5.2.X.1. Sprint Planning
##### 5.2.X.2. Aspect Leaders and Collaborators
##### 5.2.X.3. Sprint Backlog
##### 5.2.X.4. Development Evidence for Sprint Review
##### 5.2.X.5. Execution Evidence for Sprint Review
##### 5.2.X.6. Services Documentation Evidence for Sprint Review
##### 5.2.X.7. Software Deployment Evidence for Sprint Review
##### 5.2.X.8. Team Collaboration Insights during Sprint

### 5.3. Validation Interviews
#### 5.3.1. Diseño de entrevistas
#### 5.3.2. Registro de entrevistas
#### 5.3.3. Evaluaciones heurísticas

### 5.4. Video About-the-Product

---



---

# Informe de Proyecto

> Repositorio colaborativo del informe del proyecto.
