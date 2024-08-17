<hr>

# <center>COURSE PROJECT</center>

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Ingeniería de Software - 2024-2</strong><br>
    <strong>Aplicaciones Web - WX56</strong><br>
    <strong>Profesor: Alberto Wilmer Sanchez Seña</strong><br>
    <br>INFORME DE TRABAJO FINAL - TB1
</p>

<p align="center">
    <strong>Startup: Apple Web</strong><br>
    <strong>Producto:DEBTGO</strong>
</p>

<div style="text-align:center;">
    <h3>Team Members:</h3>
    <table align="center">
        <tr>
            <th style="text-align:center;">Member</th>
            <th style="text-align:center;">Code</th>
        </tr>
        <tr>
            <td>Medina Chocce, Karito Dianeth</td>
            <td>U20221C769</td>
        </tr>
        <tr>
            <td>Sanchez Rios, Camila Cristina</td>
            <td>U202210973</td>
        </tr>
        <tr>
            <td>Durand Vera, Gianfranco Angel</td>
            <td>U20201f640</td>
        </tr>
        <tr>
            <td>Chávarri Zarzosa, Daniel Jhared </td>
            <td>U202211108</td>
        </tr>
         <tr>
            <td>Duran Santander, Emilia Mercedes </td>
            <td>U201914541</td>
         </tr>
    </table>
</div>

<p align="center">
    <strong>Agosto, 2024</strong>
</p>
<br>

<h1 align="center">Registro de versiones del Informe</h1>
</br>
<table>
        <thead>
            <tr>
                <th>Versión</th>
                <th>Fecha</th>
                <th>Autor</th>
                <th>Descripción de modificaciones</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <th>TB1</th>
                <td>2/08/2024</td>
                <td>
                    <ul>
          <li>Karito Medina</li>
          <li>Camila Sanchez</li>
          <li>Gianfranco Durand</li>
          <li>Daniel Chávarri</li>
          <li>Emilia Duran</li>
                    <ul>
           </td>
      <td>            
             <ul>
          <li>Capítulo I: Introducción</li>
          <li>Capítulo II: Requirements Elicitation & Analysis</li>
          <li>Capítulo III: Requirements Specification</li>
          <li>Capítulo IV: Product Design</li>
          <li>Avance del Capítulo V: Product Implementation, Validation & Deployment hasta el punto 5.2.1.8</li>
          <li>Avance de Conclusiones, Bibliografía y Anexos</li>
        </ul>
      </td>
  </tr>
</tbody>
</table>

<br><br>

# Project Report Collaboration Insights
Link del repositorio del reporte del TB1: https://github.com/upc-pre-202402-si730-wx53-apple-web 

Para el presente informe, se llevaron a cabo reuniones y se distribuyeron los puntos a elaborar para la entrega actual, correspondientes a los Capítulos I hasta el Capítulo V: Sprint 1. Quedando de la siguiente manera:
- Imágen de las Contribuciones del equipo:

<p></p>
<br><br>


## [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
## [Project Report Collaboration Insights](#project-report-collaboration-insights)

## [Contenido](#contenido-1)
## [Tabla de contenidos](#tabla-de-contenidos-1)
## [Student Outcome](#student-outcome-1)

## [Capítulo I: Introducción](#capítulo-i-introducción-1)
- [1.1. Startup Profile](#11-startup-profile)
   - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
   - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](#12-solution-profile)
   - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
   - [1.2.2 Lean UX Process](#122-lean-ux-process)
     - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
     - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
     - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
     - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)

## [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis-1)
- [2.1. Competidores](#21-competidores)
   - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
   - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
- [2.2. Entrevistas](#22-entrevistas)
   - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
   - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
   - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
- [2.3. Needfinding](#23-needfinding)
   - [2.3.1. User Personas](#231-user-personas)
   - [2.3.2. User Task Matrix](#232-user-task-matrix)
   - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
   - [2.3.4. Empathy Mapping](#234-empathy-mapping)
   - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
- [2.4. Ubiquitous Language](#24-ubiquitous-language)

## [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification-1)
- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

## [Capítulo IV: Product Design](#capítulo-iv-product-design-1)
- [4.1. Style Guidelines](#41-style-guidelines)
   - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
   - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
- [4.2. Information Architecture](#42-information-architecture)
   - [4.2.1. Organization Systems](#421-organization-systems)
   - [4.2.2. Labeling Systems](#422-labeling-systems)
   - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
   - [4.2.4. Searching Systems](#424-searching-systems)
   - [4.2.5. Navigation Systems](#425-navigation-systems)
- [4.3. Landing Page UI Design](#43-landing-page-ui-design)
   - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
   - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
- [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
   - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
   - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
   - [4.4.2. Web Applications Mock-ups](#443-web-applications-mock-ups)
   - [4.4.3. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
- [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
- [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
   - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
   - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
   - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
- [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
   - [4.7.1. Class Diagrams](#471-class-diagrams)
   - [4.7.2. Class Dictionary](#472-class-dictionary)
- [4.8. Database Design](#48-database-design)
   - [4.8.1. Database Diagram](#481-database-diagram)

## [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment-1)
- [5.1. Software Configuration Management](#51-software-configuration-management)
   - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
   - [5.1.2. Source Code Management](#512-source-code-management)
   - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
   - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
- [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
   - [5.2.1. Sprint 1](#521-sprint-1)
     - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
     - [5.2.1.2. Sprint Backlog 1](#5212-sprint-backlog-1)
     - [5.2.1.3. Development Evidence for Sprint Review](#5213-development-evidence-for-sprint-review)
     - [5.2.1.4. Testing Suite Evidence for Sprint Review](#5214-testing-suite-evidence-for-sprint-review)
     - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
     - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
     - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
     - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
   - [5.2.2. Sprint 2](#522-sprint-2)
     - [5.2.2.1. Sprint Planning 1](#5221-sprint-planning-2)
     - [5.2.2.2. Sprint Backlog 1](#5222-sprint-backlog-2)
     - [5.2.2.3. Development Evidence for Sprint Review](#5223-development-evidence-for-sprint-review)
     - [5.2.2.4. Testing Suite Evidence for Sprint Review](#5224-testing-suite-evidence-for-sprint-review)
     - [5.2.2.5. Execution Evidence for Sprint Review](#5225-execution-evidence-for-sprint-review)
     - [5.2.2.6. Services Documentation Evidence for Sprint Review](#5226-services-documentation-evidence-for-sprint-review)
     - [5.2.2.7. Software Deployment Evidence for Sprint Review](#5227-software-deployment-evidence-for-sprint-review)
     - [5.2.2.8. Team Collaboration Insights during Sprint](#5228-team-collaboration-insights-during-sprint)
  - [5.2.3. Sprint 3](#523-sprint-3)
     - [5.2.3.1. Sprint Planning 1](#5231-sprint-planning-3)
     - [5.2.3.2. Sprint Backlog 1](#5232-sprint-backlog-3)
     - [5.2.3.3. Development Evidence for Sprint Review](#5233-development-evidence-for-sprint-review)
     - [5.2.3.4. Testing Suite Evidence for Sprint Review](#5234-testing-suite-evidence-for-sprint-review)
     - [5.2.3.5. Execution Evidence for Sprint Review](#5235-execution-evidence-for-sprint-review)
     - [5.2.3.6. Services Documentation Evidence for Sprint Review](#5236-services-documentation-evidence-for-sprint-review)
     - [5.2.3.7. Software Deployment Evidence for Sprint Review](#5237-software-deployment-evidence-for-sprint-review)
     - [5.2.3.8. Team Collaboration Insights during Sprint](#5238-team-collaboration-insights-during-sprint)
  - [5.2.4. Sprint 4](#524-sprint-4)
     - [5.2.4.1. Sprint Planning 4](#5241-sprint-planning-4)
     - [5.2.4.2. Sprint Backlog 1](#5242-sprint-backlog-4)
     - [5.2.4.3. Development Evidence for Sprint Review](#5243-development-evidence-for-sprint-review)
     - [5.2.4.4. Testing Suite Evidence for Sprint Review](#5244-testing-suite-evidence-for-sprint-review)
     - [5.2.4.5. Execution Evidence for Sprint Review](#5245-execution-evidence-for-sprint-review)
     - [5.2.4.6. Services Documentation Evidence for Sprint Review](#5246-services-documentation-evidence-for-sprint-review)
     - [5.2.4.7. Software Deployment Evidence for Sprint Review](#5247-software-deployment-evidence-for-sprint-review)
     - [5.2.4.8. Team Collaboration Insights during Sprint](#5248-team-collaboration-insights-during-sprint)
     - [5.3. Validation Interviews](#53-validation-interviews)
    - [5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)
    - [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
    - [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
    - [5.4. Video About-The-Product](#54-video-about-the-product)
  - [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

# Student Outcome
ABET – EAC - Student Outcome 5

Criterio: La capacidad de funcionar efectivamente en un equipo cuyos miembros
juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo,
establecen objetivos, planifican tareas y cumplen objetivos

<table>
  <tr>
    <td><b>Criterio específico</b></td>
    <td><b>Acciones realizadas</b></td>
    <td><b>Conclusiones</b></td>
  </tr>
    </thead>
  <tbody>
    <tr>
      <td><b>Trabaja en equipo para
proporcionar liderazgo en
forma conjunta</b></td>
      <td>
        <p><b>Medina Chocce, Karito Dianeth</b></p>
        <p><b>TB1:</b></p>
        <p>.</p>
        <p><b>TP1:</b></p>
        <p>.</p>
        <p><b>TB2:</b></p>
        <p>.</p>
        <p><b>TF:</b></p>
        <p>.</p>
        <p><b>Sanchez Rios, Camila Cristina</b></p>
       <p><b>TB1:</b></p>
        <p>.</p>
        <p><b>TP1:</b></p>
        <p>.</p>
        <p><b>TB2:</b></p>
        <p>.</p>
        <p><b>TF:</b></p>
        <p>.</p>
        <p><b>Durand Vera, Gianfranco Angel</b></p>
        <p><b>TB1:</b></p>
        <p>.</p>
        <p><b>TP1:</b></p>
        <p>.</p>
        <p><b>TB2:</b></p>
        <p>.</p>
        <p><b>TF:</b></p>
        <p>.</p>
        <p><b>Chávarri Zarzosa, Daniel Jhared</b></p>
       <p><b>TB1:</b></p>
        <p>.</p>
        <p><b>TP1:</b></p>
        <p>.</p>
        <p><b>TB2:</b></p>
        <p>.</p>
        <p><b>TF:</b></p>
        <p>.</p>
        <p><b>Duran Santander, Emilia Mercedes</b></p>
       <p><b>TB1:</b></p>
        <p>.</p>
        <p><b>TP1:</b></p>
        <p>.</p>
        <p><b>TB2:</b></p>
        <p>.</p>
        <p><b>TF:</b></p>
        <p>.</p>
      </td>
      <td>
        <p><strong>TB1:</strong></p>
        <p>En conclusión, .</p>
        <p><strong>TP1:</strong></p>
        <p>En resumen, .</p>
        <p><strong>TB2:</strong></p>
        <p>En conclusión, </p>
        <p><strong>TF:</strong></p>
        <p>En conclusión, .</p>
      </td>
    </tr>
    <tr>
      <td>Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos.</td>
      <td>
        <p><b>Medina Chocce, Karito Dianeth</b></p>
        <p><b>TB1:</b></p>
        <p>.</p>
        <p><b>TP1:</b></p>
        <p>.</p>
        <p><b>TB2:</b></p>
        <p>.</p>
        <p><b>TF:</b></p>
        <p>.</p>
        <p><b>Sanchez Rios, Camila Cristina</b></p>
       <p><b>TB1:</b></p>
        <p>.</p>
        <p><b>TP1:</b></p>
        <p>.</p>
        <p><b>TB2:</b></p>
        <p>.</p>
        <p><b>TF:</b></p>
        <p>.</p>
        <p><b>Durand Vera, Gianfranco Angel</b></p>
        <p><b>TB1:</b></p>
        <p>.</p>
        <p><b>TP1:</b></p>
        <p>.</p>
        <p><b>TB2:</b></p>
        <p>.</p>
        <p><b>TF:</b></p>
        <p>.</p>
        <p><b>Chávarri Zarzosa, Daniel Jhared</b></p>
       <p><b>TB1:</b></p>
        <p>.</p>
        <p><b>TP1:</b></p>
        <p>.</p>
        <p><b>TB2:</b></p>
        <p>.</p>
        <p><b>TF:</b></p>
        <p>.</p>
        <p><b>Duran Santander, Emilia Mercedes</b></p>
       <p><b>TB1:</b></p>
        <p>.</p>
        <p><b>TP1:</b></p>
        <p>.</p>
        <p><b>TB2:</b></p>
        <p>.</p>
        <p><b>TF:</b></p>
        <p>.</p>
      </td>
       <td>
        <p><strong>TB1:</strong></p>
        <p>En conclusión, .</p>
        <p><strong>TP1:</strong></p>
        <p>En resumen, .</p>
        <p><strong>TB2:</strong></p>
        <p>En conclusión, </p>
        <p><strong>TF:</strong></p>
        <p>En conclusión, .</p>
      </td>
    </tr>
  </tbody>
</table>

<br><br>


# Capitulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

DebtGo es una aplicación móvil innovadora que transforma la forma en que las personas gestionan sus deudas y mejoran su educación financiera. La plataforma proporciona herramientas intuitivas para que los usuarios, tanto jóvenes como adultos, puedan manejar sus finanzas de manera efectiva, evitando deudas innecesarias y promoviendo el bienestar financiero. DebtGo permite a los usuarios establecer metas financieras, seguir sus ingresos y gastos, y recibir informes detallados sobre su flujo de efectivo. Con un enfoque en la personalización, la aplicación crea presupuestos adaptados a las necesidades individuales y ofrece recordatorios para pagos puntuales, además de brindar recursos educativos para mejorar la alfabetización financiera.

**Misión:**

Empoderar a las personas a tomar el control de sus finanzas mediante herramientas intuitivas y educación financiera, ayudándoles a evitar deudas innecesarias y promover un bienestar financiero sostenible.

**Visión:**

Ser la plataforma líder en gestión financiera personal, ofreciendo a los usuarios soluciones innovadoras que les permitan alcanzar la estabilidad y libertad financiera, contribuyendo así a una sociedad más consciente y educada financieramente.

### 1.1.2. Perfiles de integrantes del equipo

<table>
  <tr>
    <th>
      <img src="" alt="Foto de perfil de Karito" width="800px">
    </th>
    <td valign="top">
      <p><b>Medina Chocce, Dianeth Karito</b></p>
      <p>
        ....
      </p>
    </td>
  </tr>
  <tr>
    <th>
      <img src="" alt="Foto de perfil de Camila" width="800px">
    </th>
    <td valign="top">
      <p><b>Sánchez Ríos, Camila Cristina</b></p>
      <p>
        ...
      </p>
    </td>
  </tr>
  <tr>
    <th>
      <img src="" alt="Foto de perfil de Gianfranco" width="800px">
    </th>
    <td valign="top">
      <p><b>Durand Vera, Gianfranco Ángel</b></p>
      <p>
        ...
      </p>
    </td>
  </tr>
  <tr>
    <th>
      <img src="" alt="Foto de perfil de Daniel" width="800px">
    </th>
    <td valign="top">
      <p><b>Chávarri Zarzosa, Daniel Jhared</b></p>
      <p>
       ...
      </p>
    </td>
  </tr>
  <tr>
    <th>
      <img src="" alt="Foto de perfil de Emilia" width="700px">
    </th>
    <td valign="top">
      <p><b>Durán Santander, Emilia Mercedes.</b></p>
      <p>
        ...
      </p>
    </td>
  </tr>
</table>
<br>

## 1.2. Solution Profile

### 1.2.1 Antecedentes y problemática

- **Qué:** Una aplicación que proporcionará a los usuarios herramientas y recursos para comprender, monitorear y gestionar sus deudas de manera intuitiva y educativa.
- **Quién:** Está dirigida a personas mayores de edad que deseen gestionar sus deudas de manera más efectiva y mejorar su educación financiera.
- **Dónde:** La aplicación estaría disponible a través de las tiendas virtuales de los sistemas operativos (iOS, Android).
- **Cuándo:** La plataforma estaría disponible las 24 horas, así pudiendo permitir el fácil y libre acceso a la aplicación.
- **Por qué:** Esta aplicación está pensada para personas que tienen dificultades con la gestión de deudas y carecen de educación financiera, lo que conduce a estrés y decisiones financieras deficientes.
- **Cómo:** El usuario ingresará los pagos pendientes en el apartado de deudas e ingresará detalladamente cómo se debe pagar la deuda pendiente (en cuotas con o sin intereses, financiado por meses, entre otros) y la aplicación generará planes de pago y
estrategias personalizadas para que el usuario se le haga más sencillo pagar la deuda pendiente. Además, la aplicación emplea una interfaz amigable con secciones claras para una vista general de las deudas, seguimiento de pagos, contenido educativo y utilizará recursos como notificaciones y recordatorios para ayudar al usuario a estar al día con sus pagos y objetivos financieros.
- **Cuánto:** La aplicación utilizará una estrategia de monetización en la cual se podría incluir un modelo freemium, donde la aplicación básica sea gratuita y las características avanzadas estén disponibles mediante una tarifa de suscripción.


### 1.2.2 Lean UX Process.
#### 1.2.2.1. Lean UX Problem Statements.
Nuestra aplicación se encargará de ofrecer a los usuarios una alternativa que tiene la finalidad de ayudar a las personas a manejar de manera más efectiva sus deudas y, al mismo tiempo, fortalecer su educación financiera. La app creará una oportunidad para que los usuarios puedan mejorar su situación financiera, pero hemos identificado algunos desafíos clave que debemos abordar para asegurar el éxito de la plataforma.

Uno de los problemas principales es la desconfianza que algunos usuarios pueden sentir al utilizar nuestra aplicación, especialmente porque somos una empresa nueva en el mercado. Los usuarios podrían temer que la app no cumpla con sus expectativas o que no sea segura. ¿Cómo podemos eliminar esta desconfianza en los usuarios al introducir nuestra aplicación? Creemos que si implementamos características de seguridad robustas, proporcionamos testimonios de usuarios y ofrecemos una prueba gratuita, podemos reducir esta desconfianza y aumentar la adopción de la app.

Además, hemos notado que muchas personas no reconocen la importancia de la educación financiera, lo que puede disminuir la motivación para utilizar una aplicación centrada en mejorar sus habilidades de manejo de deudas y finanzas. ¿Qué tan primordial es una app de aprendizaje financiero para nuestros usuarios? Creemos que si logramos mostrar claramente los beneficios tangibles de mejorar la educación financiera, como el ahorro de dinero y la reducción de estrés, más personas estarán motivadas para usar nuestra app.

Por último, es posible que los usuarios no perciban la utilidad inmediata de la aplicación para mejorar su situación financiera, lo que podría llevar a una baja adopción y uso continuo. ¿Cómo podemos motivar a las personas a reconocer que nuestra app es realmente útil? Creemos que si destacamos historias de éxito y casos de estudio dentro de la app, demostrando cómo otros usuarios han mejorado su situación financiera con DebtGo, podremos persuadir a nuevos usuarios sobre la utilidad real de la aplicación y aumentar su uso activo.

#### 1.2.2.2. Lean UX Assumptions.
**Business Outcomes:**

**User Outcomes:**

#### 1.2.2.3. Lean UX Hypothesis Statements.

#### 1.2.2.4. Lean UX Canvas.

## 1.3. Segmentos objetivo. 
