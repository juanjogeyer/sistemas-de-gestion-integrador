# Proyecto Integrador — Sistema Integral de Gestión Comercial

> **Documento en elaboración.** Se desarrolla sección por sección siguiendo la
> *Plantilla orientativa de entrega del proyecto integrador* de la cátedra
> (12 secciones). Al finalizar se exportará a Word/PDF para la entrega.

---

## 1. Carátula

<div align="center">

**UNIVERSIDAD TECNOLÓGICA NACIONAL**

**Facultad Regional San Rafael**

Carrera: **Ingeniería en Sistemas de Información**

Cátedra: **Sistemas de Gestión**

---

### Implementación de un Sistema Integral de Gestión Comercial y Tablero de Control para una PyME comercial

*Proyecto Integrador*

---

**Integrantes:**

| Apellido y nombre |
|---|
| Lepez, Joaquín |
| Geyer, Juan José |
| Lopez, Juan |
| Sorato, Emiliano |

**Docente:** Juan Gijón

**Año:** 2026

</div>

---

## 2. Índice

1. Carátula
2. Índice
3. Introducción
4. Presentación del problema u oportunidad
5. Descripción general del proyecto
6. Análisis del contexto
7. Análisis técnico y organizacional
8. Análisis económico y financiero
9. Evaluación del proyecto
10. Conclusiones
11. Bibliografía
12. Anexos

> *El índice definitivo, con la numeración de páginas, se ajustará al pasar el
> documento a su formato final.*

---

## 3. Introducción

El presente trabajo constituye el Proyecto Integrador de la cátedra Sistemas de
Gestión, correspondiente al quinto año de la carrera Ingeniería en Sistemas de
Información de la Universidad Tecnológica Nacional, Facultad Regional San Rafael.
Su finalidad es aplicar, sobre un caso concreto, los contenidos vistos durante
la cursada en torno a la formulación y evaluación de proyectos de inversión
vinculados a las tecnologías de la información.

El proyecto se enmarca en la formulación y evaluación de un proyecto de inversión
tecnológica para una pequeña y mediana empresa (PyME) del sector comercial. A
partir del caso provisto por la cátedra, se analiza la incorporación de un
Sistema Integral de Gestión Comercial y Tablero de Control que reemplace la
operatoria manual basada en planillas de cálculo y registros dispersos con la
que la empresa administra actualmente sus ventas, su stock, sus clientes y sus
reportes.

El objetivo del trabajo es recorrer las etapas habituales de un proyecto de
inversión: identificar el problema u oportunidad que le da origen, describir la
propuesta, definir su alcance, analizar sus requerimientos técnicos y
organizacionales y evaluar su conveniencia económica y financiera. Para esto se
construye el flujo de fondos del proyecto, se calculan el Valor Actual Neto
(VAN) y la Tasa Interna de Retorno (TIR), se hace un análisis de sensibilidad y
se evalúa una alternativa de financiamiento, todo lo cual conduce a una
recomendación final.

El trabajo no se limita a presentar números, sino que apunta a mostrar el
razonamiento técnico, organizacional y financiero detrás de la decisión de
invertir, integrando los contenidos vistos durante la cursada.

## 4. Presentación del problema u oportunidad

### 4.1 Contexto en el que surge la situación

La organización sobre la que se desarrolla el proyecto es una pequeña y mediana
empresa (PyME) del sector comercial, dedicada a la comercialización de productos
a través de dos sucursales y de un canal de venta no presencial mediante
WhatsApp y correo electrónico. Su operatoria diaria —la gestión de pedidos, del
stock, de los clientes y de los reportes— se sostiene con planillas de cálculo
y registros manuales, sin un sistema de información que integre esas tareas.

Este esquema resultó suficiente en las etapas iniciales de la empresa, pero a
medida que aumenta el volumen de operaciones las herramientas manuales se
vuelven difíciles de mantener: la información queda dispersa, desactualizada y
sujeta a errores. La dirección advierte esta limitación y evalúa la
incorporación de un sistema integral de gestión comercial como respuesta.

### 4.2 Problema detectado

El problema central es que la gestión comercial de la empresa depende de
procesos manuales y de información no integrada, lo que genera errores,
ineficiencia y falta de visibilidad. Las dificultades concretas relevadas pueden
agruparse en cuatro ejes:

| Eje | Dificultades identificadas |
|---|---|
| Información dispersa y sin trazabilidad | Falta de trazabilidad de ventas y clientes; ausencia de una base centralizada de clientes. |
| Errores operativos | Diferencias frecuentes entre el stock real y el registrado; errores en la carga de pedidos y en la facturación. |
| Ineficiencia operativa | Demoras en la atención de pedidos; fuerte dependencia de tareas manuales repetitivas. |
| Falta de información para decidir | Dificultad para conocer los márgenes por producto; escasa información para la toma de decisiones de la gerencia. |

Estas dificultades no son independientes entre sí: la falta de integración de la
información es la causa de fondo de la que se derivan, en mayor o menor medida,
las demás.

### 4.3 Por qué resulta relevante abordar la situación

Abordar esta situación es relevante porque sus consecuencias impactan
directamente sobre la rentabilidad y la competitividad de la empresa:

- Los descuadres de stock y la dificultad para conocer los márgenes por producto
  generan pérdidas económicas y decisiones de compra y de precios poco
  fundamentadas.
- Las demoras y los errores en pedidos y facturación afectan la calidad del
  servicio, provocan reclamos y pueden derivar en la pérdida de clientes.
- La dependencia de tareas manuales consume tiempo del personal en actividades
  de bajo valor agregado, que podría destinarse a la atención y a la venta.
- La falta de información oportuna limita la capacidad de la dirección para
  tomar decisiones a tiempo.

Además, se trata de un problema creciente: cuanto mayor sea el volumen de
operaciones, mayores serán los errores y las pérdidas asociadas al esquema
manual. El hecho de que la propia dirección ya esté evaluando una solución
muestra que existe conciencia del problema y voluntad de invertir para
resolverlo.

### 4.4 Necesidad u oportunidad que busca atender el proyecto

A partir de lo anterior, el proyecto busca atender la necesidad de centralizar,
integrar y ordenar la gestión comercial de la empresa mediante un sistema
único. Más que la corrección de fallas aisladas, se plantea como una
oportunidad de mejora orientada a:

- contar con información única, confiable y actualizada sobre ventas, stock y
  clientes;
- reducir los errores de carga, facturación y control de inventario;
- automatizar las tareas manuales repetitivas y agilizar la atención de pedidos;
- brindar a la gerencia un tablero de control con indicadores que sustente la
  toma de decisiones;
- sentar una base ordenada para el crecimiento futuro de la empresa.

En resumen, el proyecto que se origina a partir de esta situación no es sólo
tecnológico: apunta a mejorar la eficiencia, el control y la capacidad de
gestión del negocio.

## 5. Descripción general del proyecto

### 5.1 Nombre del proyecto

El proyecto se denomina Implementación de un Sistema Integral de Gestión
Comercial y Tablero de Control. A lo largo del documento, el sistema se
referencia de forma abreviada como SIGC (Sistema Integral de Gestión Comercial).

### 5.2 Descripción general de la propuesta

El proyecto consiste en implementar un sistema integral de gestión comercial que
reemplace las planillas de cálculo y los registros manuales por una única
herramienta informática, utilizada en las dos sucursales de la empresa.

El sistema integra, en un mismo entorno, los siguientes componentes:

- Sistema de gestión comercial, que registra y administra las ventas de ambas
  sucursales, incluidas las que llegan por WhatsApp y correo electrónico.
- Módulo de stock e inventario, que mantiene actualizado el stock en tiempo
  real, apoyado en lectores de código de barras.
- Base centralizada de clientes, que reúne en un único repositorio la
  información hoy dispersa.
- Carga digital de pedidos, que ordena y estandariza el ingreso de pedidos y su
  posterior facturación.
- Reportes comerciales y un tablero de control con indicadores para la gerencia.

La implementación incluye, además, la migración inicial de los datos que hoy
están en las planillas y la capacitación de los usuarios, para asegurar la
puesta en marcha y la adopción del sistema.

### 5.3 Objetivo principal

Dotar a la empresa de un sistema integral de gestión comercial que centralice y
automatice la administración de las ventas, el stock y los clientes, reduciendo
los errores y los tiempos de proceso, y que le dé a la dirección información
oportuna y confiable para la toma de decisiones.

### 5.4 Objetivos específicos

1. Centralizar en un único sistema la información de ventas, stock y clientes
   que hoy está dispersa en planillas y registros manuales.
2. Mantener el stock actualizado en tiempo real, incorporando la lectura de
   código de barras para reducir las diferencias entre el stock real y el
   registrado.
3. Digitalizar la carga de pedidos y la facturación para disminuir los errores y
   las demoras en la atención.
4. Armar una base centralizada de clientes que permita la trazabilidad de las
   ventas.
5. Generar reportes comerciales y un tablero de control con indicadores que
   ayuden a la gerencia a tomar decisiones.
6. Reducir la dependencia de tareas manuales repetitivas, liberando tiempo del
   personal para tareas de mayor valor.
7. Asegurar la adopción del sistema mediante la migración de los datos
   existentes y la capacitación de los usuarios.

### 5.5 Alcance del proyecto

El proyecto abarca la implementación completa del sistema en las dos sucursales
actuales de la empresa.

Queda dentro del alcance:

- Los módulos de ventas, stock e inventario, clientes, carga digital de pedidos,
  reportes comerciales y tablero de control.
- La configuración del sistema y las integraciones necesarias para su puesta en
  marcha.
- El equipamiento y los lectores de código de barras para las dos sucursales.
- La migración inicial de los datos existentes en las planillas de cálculo.
- La capacitación inicial de los usuarios.

Queda fuera del alcance, en esta etapa:

- El desarrollo de una tienda online o canal de venta de comercio electrónico
  propio.
- La integración automática con los canales de mensajería (WhatsApp y correo
  electrónico); los pedidos recibidos por esos medios se cargan en el sistema.
- Módulos de contabilidad, liquidación de sueldos o gestión de recursos humanos.
- La apertura de nuevas sucursales; el sistema queda preparado para escalar, pero
  el proyecto se limita a los dos puntos de venta existentes.

### 5.6 Destinatarios, usuarios y beneficiarios

| Tipo | Quiénes | Vínculo con el sistema |
|---|---|---|
| Usuarios directos | Personal de ventas y atención de las dos sucursales | Registran ventas y cargan pedidos. |
| Usuarios directos | Personal administrativo | Gestiona stock, facturación y reportes. |
| Usuarios directos | Gerencia / dirección | Consulta el tablero de control y los reportes para decidir. |
| Beneficiario principal | La empresa en su conjunto | Mejora la eficiencia, el control y la capacidad de gestión. |
| Beneficiarios indirectos | Los clientes | Reciben una atención más rápida y con menos errores. |

La descripción anterior es coherente con el problema planteado en la Sección 4:
cada componente del SIGC responde a una de las dificultades relevadas en la
operatoria manual de la empresa.

## 6. Análisis del contexto

### 6.1 Contexto organizacional

La empresa es una PyME del sector comercial que opera con dos sucursales y vende
tanto de forma presencial como a través de WhatsApp y correo electrónico. Es una
organización de estructura reducida, en la que pueden distinguirse tres grupos
de trabajo: el personal de ventas y atención de cada sucursal, el personal
administrativo —encargado de la facturación, el control de stock y los
reportes— y la dirección o gerencia, que concentra la toma de decisiones.

La gestión se apoya hoy en planillas de cálculo y registros manuales, una forma
de trabajo a la que el personal está habituado. La incorporación del SIGC
supone, por lo tanto, un cambio en la manera de trabajar, lo que vuelve
importante el acompañamiento y la capacitación. Un elemento favorable del
contexto organizacional es que la propia dirección es la que impulsa el
proyecto: existe un patrocinador interno interesado en que la iniciativa se
concrete.

### 6.2 Entorno del proyecto

El proyecto se desarrolla dentro de la empresa y no depende de manera directa de
factores externos como regulaciones o trámites especiales. De todos modos,
algunos elementos del entorno resultan relevantes:

- Entorno tecnológico: las herramientas necesarias para el proyecto —sistemas de
  gestión comercial, servicios de hosting, lectores de código de barras— son
  tecnologías maduras, disponibles en el mercado y de costo accesible para una
  PyME. Esto hace que la propuesta sea técnicamente realizable sin necesidad de
  desarrollos complejos a medida.
- Entorno de mercado: en el comercio, los clientes valoran la rapidez y la
  precisión en la atención, y la competencia tiende a incorporar herramientas
  digitales de gestión. Ordenar la operatoria interna ayuda a la empresa a
  sostener su competitividad.

### 6.3 Situación actual

Actualmente la empresa gestiona sus operaciones sin un sistema de información
integrado. Cada proceso se maneja por separado, como se resume a continuación:

| Proceso | Cómo se gestiona hoy |
|---|---|
| Ventas | Se registran en planillas de cálculo, de forma separada en cada sucursal. |
| Pedidos | Los pedidos que llegan por WhatsApp y correo electrónico se cargan a mano. |
| Stock | Se controla manualmente, lo que produce diferencias entre el stock real y el registrado. |
| Clientes | La información está dispersa en distintos registros, sin una base única. |
| Facturación | Se realiza manualmente, con riesgo de errores de carga. |
| Reportes | Se arman a mano a partir de las planillas, con demora y poca confiabilidad. |

Esta situación es la que da origen al proyecto y explica por qué la información
de la empresa resulta dispersa, poco confiable y difícil de aprovechar para
tomar decisiones.

### 6.4 Actores involucrados

En el desarrollo del proyecto intervienen distintos actores, con diferente grado
de interés e influencia sobre su resultado:

| Actor | Rol en el proyecto | Interés | Influencia |
|---|---|---|---|
| Dirección / gerencia | Patrocina el proyecto, decide y financia la inversión. | Alto | Alta |
| Personal administrativo | Usuario directo: stock, facturación y reportes. | Alto | Media |
| Personal de ventas y atención | Usuario directo: registro de ventas y carga de pedidos. | Medio | Media |
| Proveedor / implementador del sistema | Provee, configura, migra los datos y capacita. | Medio | Alta |
| Clientes de la empresa | Beneficiarios indirectos de una atención más ágil. | Bajo | Baja |

Los actores más críticos son la dirección y el personal administrativo. La
dirección, porque sin su apoyo y financiamiento el proyecto no se realiza; el
personal administrativo, porque es quien más usa el sistema en el día a día y de
su adopción depende buena parte del éxito. El proveedor del sistema también
tiene una influencia importante, ya que de su trabajo dependen la correcta
implementación y la capacitación.

### 6.5 Condiciones relevantes para el desarrollo de la propuesta

Para que el proyecto pueda llevarse adelante con éxito, hay que tener en cuenta
algunas condiciones:

- El compromiso sostenido de la dirección, tanto en el financiamiento como en el
  acompañamiento del cambio.
- La disponibilidad del presupuesto necesario para afrontar la inversión inicial
  y los costos operativos del sistema.
- La capacitación del personal y el acompañamiento durante la transición, para
  reducir la resistencia al cambio.
- La calidad de los datos actuales de las planillas, ya que de ella depende que
  la migración inicial sea confiable.
- Una infraestructura mínima de equipamiento y conectividad en las dos
  sucursales.
- El mantenimiento de la operación durante la implementación, para no
  interrumpir la atención a los clientes.

En su mayoría, estas condiciones se presentan de manera favorable —en particular
el respaldo de la dirección—, lo que sustenta la viabilidad y la pertinencia de
avanzar con la propuesta.

## 7. Análisis técnico y organizacional

*(Pendiente)*

## 8. Análisis económico y financiero

*(Pendiente)*

## 9. Evaluación del proyecto

*(Pendiente)*

## 10. Conclusiones

*(Pendiente)*

## 11. Bibliografía

*(Pendiente)*

## 12. Anexos

*(Pendiente)*
