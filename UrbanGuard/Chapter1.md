## Capítulo I: Introduction

### 1.1 Startup Profile

#### 1.1.1 Descripción de la Startup

**UrbanGuard** es una startup peruana de tecnología orientada a la seguridad en el transporte público urbano. Surgimos ante la alarmante situación de inseguridad que enfrentan diariamente millones de usuarios del transporte público en Lima y otras ciudades del Perú, donde la falta de control sobre la identidad de los conductores, la ausencia de mecanismos de alerta en emergencias y el desconocimiento de la cantidad de pasajeros a bordo incrementan exponencialmente el riesgo ante accidentes, asaltos y situaciones de peligro.

Nuestra propuesta tecnológica es **SafeBus**, un sistema que articula tres pilares de seguridad en tiempo real:

- Verificación de conductores mediante código QR al inicio de cada servicio
- Botón de pánico integrado para el conductor, que transmite alertas inmediatas a la central de operaciones
- Conteo automatizado de pasajeros a bordo del vehículo, identificando la cantidad de vidas expuestas ante una emergencia

**MISIÓN:** Fortalecer la seguridad de los usuarios del transporte público mediante soluciones digitales innovadoras que permitan verificar la identidad de conductores, gestionar emergencias en tiempo real y cuantificar el riesgo humano a bordo de cada vehículo.

**VISIÓN:** Convertirnos en la plataforma líder de seguridad y trazabilidad en el transporte público de Latinoamérica, reconocida por reducir incidentes viales, empoderar a las autoridades con información oportuna y devolver la confianza ciudadana en el sistema de movilidad urbana.

#### 1.1.2. Perfiles de integrantes del equipo

|                     Foto de perfil                      | Nombre Completo                      | Carrera                | Habilidades                                                                                                         |
| :-----------------------------------------------------: | :----------------------------------- | :--------------------- | :------------------------------------------------------------------------------------------------------------------ |
| ![LeonardoFoto](Resources/img/leonardo.png)  | Leonardo Sebastian Delgado Arriola   | Ingenieria de Software | C++, HTML, CSS, JS, Vue, MySQL, MongoDB, Git                                                                        |
|     ![BorisFoto](Resources/img/boris.png)      | Boris Alvarado Millan    | Ingenieria de Software | Java, Html, Css, JavaScript, Angular, Vue, Node.js, TypeScript, TailwindCss, Spring, C++, Python                    |
| ![CarlosFoto](Resources/img/carlos.png) | Blancas Chávez, Carlos Franco      | Ingenieria de Software | C++, HTML, CSS, MySQL, Python (basics), C# (basics)                                                                 |
| ![IvonneFoto](Resources/img/ivonne.png) | Ivonne Beatriz Ibañez Torres                       | Ingenieria de Software | C++ y Python, y conocimientos en diseño y patrones de software, PostgreSQL y MongoDB, Java ,Spring Boot y  Node.js. |
|  ![FernandoFoto](Resources/img/fernando.png)   | Fernando Carlos Espíritu Silvestre | Ingenieria de Software | C++, Java, JavaScript, HTML, CSS, SQL Server, MongoDB, Git                      
---

### 1.2. Solution Profile

#### 1.2.1 Antecedentes y problemática

Para entender mejor las necesidades de nuestros usuarios, aplicamos la técnica **5W's & 2H's**, herramienta que responde a siete preguntas clave para caracterizar un problema de forma integral.

**What (Qué) — ¿Cuál es el problema?**

La inseguridad en el transporte público urbano del Perú. Los pasajeros no tienen forma de verificar si el conductor del vehículo en el que abordan es la persona autorizada para operar esa unidad. A esto se suma la inexistencia de mecanismos de alerta en tiempo real para el conductor ante situaciones de riesgo y la falta de registro de cuántas personas se encuentran a bordo.

**When (Cuándo) — ¿Cuándo sucede el problema?**

El problema se manifiesta en cada servicio de transporte público: al momento de abordar la unidad, durante el trayecto y en la gestión de incidentes por parte de las autoridades. Los accidentes de tránsito y asaltos ocurren en cualquier momento del día, con mayor incidencia en horarios nocturnos.

*¿Cuándo utilizará el cliente el producto?* Desde que el conductor ingrese al bus, previo a encender el motor.

**Where (Dónde) — ¿Dónde está el cliente cuando usa el producto?**

En su jornada laboral, conduciendo en medio del viaje. El problema surge en el norte del Perú (Trujillo, Chiclayo, Piura) hace casi dos décadas, extendiéndose a zonas céntricas de Lima.

**Who (Quién) — ¿A quiénes les sucede el problema?**

A los pasajeros del transporte público (especialmente mujeres, adultos mayores y escolares), a los conductores expuestos a asaltos y extorsiones, a las empresas operadoras de transporte que no tienen visibilidad de sus unidades en tiempo real, y a las autoridades de seguridad y emergencias.

**Why (Por qué) — ¿Cuál es la causa del problema?**

Por la ausencia de tecnología de identificación y trazabilidad en las unidades de transporte público. Las empresas operadoras carecen de plataformas digitales que les permitan verificar en tiempo real quién conduce cada unidad. Tampoco existen canales de emergencia directos entre el conductor y la central de operaciones, ni sensores para el conteo de pasajeros.

**How (Cómo) — ¿Cómo afecta este problema?**

La combinación de informalidad en el sector, débil regulación tecnológica y la ausencia de estándares digitales de seguridad genera un entorno donde cualquier persona puede operar una unidad sin trazabilidad. El impacto se refleja en violencia, aumento de pasajes, inseguridad ciudadana, aumento del transporte informal e impacto psicológico.

**How Much (Cuánto) — ¿Qué datos respaldan la problemática?**

Según el MTC (2023), en el Perú se registran más de 90,000 accidentes de tránsito anuales, de los cuales aproximadamente el 30% involucra unidades de transporte público. La Defensoría del Pueblo reporta que el 68% de mujeres ha sufrido algún tipo de acoso o situación de inseguridad en el transporte público. Aproximadamente el 40% de empresas de transporte en Lima y Callao pagan cupos, según gremios.

---

#### 1.2.2 Lean UX Process

##### 1.2.2.1 Lean UX Problem Statements

**Problem Statement 1:** Los conductores de transporte público enfrentan situaciones de riesgo como robos, agresiones y extorsiones durante sus recorridos diarios. Actualmente, muchas unidades no cuentan con mecanismos digitales que permitan reportar incidentes de manera inmediata ni solicitar apoyo en tiempo real, lo que incrementa la sensación de inseguridad y dificulta una respuesta rápida ante emergencias.

**Problem Statement 2:** Las empresas de transporte presentan una limitada capacidad de supervisión sobre sus unidades mientras están en operación, lo que dificulta conocer en tiempo real lo que sucede durante los recorridos. Esta falta de visibilidad reduce su capacidad para coordinar acciones oportunas, tomar decisiones informadas y responder de manera eficiente ante incidentes o emergencias.

**Problem Statement 3:** Los usuarios del transporte público perciben el servicio como inseguro debido a la ausencia de mecanismos visibles que garanticen su protección durante el viaje. Esta percepción negativa no solo disminuye la confianza en el servicio, sino que también afecta la experiencia del usuario y su disposición a utilizar el transporte público de manera frecuente.

##### 1.2.2.2 Lean UX Assumption

**Business Assumptions:**

- Creemos que las empresas de transporte público necesitan herramientas digitales que les permitan supervisar sus unidades en tiempo real y responder rápidamente ante incidentes de seguridad.
- Suponemos que las empresas estarían dispuestas a adoptar una plataforma tecnológica si esta contribuye a mejorar el control operativo y reducir situaciones de riesgo dentro de las unidades.
- Consideramos que la implementación de SafeBus puede optimizar la comunicación entre conductores y supervisores durante situaciones de emergencia.
- Creemos que centralizar la información de recorridos, alertas e incidencias facilitará la toma de decisiones y mejorará la capacidad de monitoreo de las operaciones de transporte.

**Business Outcomes:**

- Reducir el tiempo de respuesta ante incidentes reportados por los conductores.
- Mejorar la capacidad de supervisión operativa de las empresas.
- Incrementar la percepción de confiabilidad del servicio.
- Reducir los tiempos de respuesta ante emergencias.

**User Benefits:**

- Los conductores podrán reportar incidentes de manera rápida y sencilla mediante alertas desde la aplicación móvil.
- Los supervisores tendrán acceso inmediato a información relacionada con rutas, incidencias y estado de las unidades.
- Los usuarios podrán percibir un entorno de transporte más seguro gracias al monitoreo y seguimiento de las unidades.
- La plataforma permitirá mejorar la coordinación y atención ante situaciones de riesgo o emergencia.

##### 1.2.2.3 Lean UX Hypothesis Statements

**Hypothesis Statement 1:** Creemos que al implementar una funcionalidad de reporte rápido desde la aplicación móvil, los conductores podrán registrar incidentes de forma inmediata. Sabremos que esto es cierto cuando al menos el 70% de los incidentes sean reportados en menos de 10 segundos.

**Hypothesis Statement 2:** Creemos que al proporcionar un panel de control con información en tiempo real, las empresas podrán coordinar acciones de respuesta de manera más eficiente ante incidentes. Sabremos que esto es cierto cuando el tiempo de coordinación y respuesta se reduzca en al menos un 30%.

**Hypothesis Statement 3:** Creemos que al ofrecer a los usuarios visibilidad sobre el estado y recorrido de las unidades, se incrementará su confianza en el servicio de transporte. Sabremos que esto es cierto cuando al menos el 60% de los usuarios reporten mayor confianza en encuestas posteriores al uso.

##### 1.2.2.4 Lean UX Canvas

<img src= "Resources/img/LeanUxCanvas.png">

---

### 1.3 Segmento Objetivo

| Segmento objetivo | Características demográficas | Información estadística de sustento |
|-------------------|------------------------------|--------------------------------------|
| Conductores (operarios) de transporte público | Cantidad de vehículos: Uno o 2 a su disposición. Edad: Adultos de 24 años en adelante. Cargo: Conductores con vehículo asignado a una empresa-ruta. Ubicación: Lima Metropolitana y el Callao. Interés: Garantizar su bienestar y el de los pasajeros a bordo. | Según Panamericana.pe (2025), los conductores deben pagar una cuota diaria y semanal para poder operar. Si alguien se niega, corre el riesgo de ser atacado a balazos. |
| Empresas o consorcios de transporte público | Cantidad de vehículos: Más de 2 a nombre del consorcio. Edad: Adultos de 28 años a más. Cargo: Representantes legales de consorcios con operarios de cústers. Ubicación: Lima Metropolitana y Callao. Interés: Garantizar la seguridad de pasajeros y operarios. | De acuerdo con larepublica.pe (2024), más de 14,000 denuncias por extorsión han sido registradas en todo el país, destacándose Lima y La Libertad como las regiones más afectadas. |
