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

### 7.1 Procesos involucrados

Los procesos comerciales que cambian con la incorporación del SIGC son los
mismos que se describieron en la situación actual. La diferencia es que pasan a
operar de manera integrada y digital:

| Proceso | Hoy | Con el SIGC |
|---|---|---|
| Ventas | Se registran en planillas separadas por sucursal. | Se registran en el sistema, en una única base compartida por ambas sucursales. |
| Pedidos | Se cargan a mano a partir de los mensajes de WhatsApp y de correo. | Se cargan al sistema desde un formulario único y quedan vinculados al cliente. |
| Stock | Se controla manualmente, con diferencias frecuentes entre lo real y lo registrado. | El sistema actualiza el stock en tiempo real con cada venta y se apoya en lectores de código de barras. |
| Clientes | Información dispersa en distintos registros. | Base centralizada con datos, historial y contacto de cada cliente. |
| Facturación | Se realiza manualmente, con riesgo de errores de tipeo. | Se emite desde el sistema a partir del pedido cargado. |
| Reportes | Se arman a mano a partir de las planillas. | Se generan automáticamente y se acompañan de un tablero de control para la gerencia. |

### 7.2 Tecnología y recursos requeridos

Para llevar adelante el proyecto se necesitan:

- Un sistema de gestión comercial, contratado bajo modalidad de licencia y
  soporte, que incluya los módulos de ventas, stock e inventario, clientes,
  carga de pedidos, reportes y tablero de control.
- Un servicio de hosting en la nube donde correr el sistema, de modo que pueda
  accederse desde ambas sucursales y desde la administración.
- Lectores de código de barras y equipamiento asociado para las dos sucursales.
- El acompañamiento del proveedor del sistema para la configuración, las
  integraciones, la migración inicial de datos y la capacitación.
- Recursos humanos internos: un referente del proyecto del lado de la empresa y
  el personal de cada área dispuesto a participar de la capacitación.
- Presupuesto para afrontar la inversión inicial y los costos operativos
  anuales; el detalle de los montos se desarrolla en la Sección 8.

### 7.3 Infraestructura

La infraestructura necesaria es la habitual de una PyME comercial que se mueve
hacia herramientas digitales:

- En cada sucursal: estaciones de trabajo (PC o terminal) para registrar ventas
  y cargar pedidos, lectores de código de barras para el control de stock y
  conexión a internet estable.
- En la oficina administrativa y para la dirección: equipos desde los cuales
  administrar el sistema, gestionar la facturación y consultar el tablero de
  control.
- En el backend: hosting del sistema en la nube, provisto por el mismo proveedor
  o por un servicio asociado, de modo que la empresa no necesite mantener un
  servidor propio.

### 7.4 Roles y áreas participantes

El proyecto involucra a distintos roles, tanto durante la implementación como
en la operación posterior:

| Etapa | Rol | Función |
|---|---|---|
| Implementación | Dirección | Patrocina, decide y aprueba el avance. |
| Implementación | Referente interno del proyecto | Coordina con el proveedor, valida los procesos y centraliza las consultas del equipo. |
| Implementación | Proveedor / implementador | Provee el sistema, lo configura, realiza las integraciones, migra los datos y capacita. |
| Implementación | Personal de las sucursales y de administración | Participa del relevamiento y de las capacitaciones. |
| Operación | Personal de ventas y atención | Usa el sistema para registrar ventas y cargar pedidos. |
| Operación | Personal administrativo | Gestiona stock, facturación, clientes y reportes desde el sistema. |
| Operación | Dirección | Consulta el tablero de control y los reportes para tomar decisiones. |
| Operación | Proveedor | Brinda soporte y mantenimiento a través del contrato anual. |

### 7.5 Cambios organizacionales esperados

La incorporación del SIGC supone varios cambios en la forma de trabajo de la
empresa:

- Se pasa de varias planillas separadas a una única fuente de información, lo
  que exige disciplina en el registro y mayor coordinación entre las dos
  sucursales.
- Aparece la necesidad de un referente interno del sistema, que oficie de
  administrador funcional y de nexo con el proveedor.
- Los procesos quedan más estandarizados y dejan trazabilidad, lo que cambia la
  manera de controlar el negocio.
- Es esperable un período de adaptación al inicio, en el que el personal aprende
  a operar la nueva herramienta y la empresa ajusta sus rutinas.

Acompañar estos cambios con capacitación y con un seguimiento cercano por parte
de la dirección es una condición clave para que la mejora se sostenga en el
tiempo.

### 7.6 Condiciones y etapas de implementación

Para que la implementación sea ordenada, se propone seguir una secuencia de
etapas:

1. Relevamiento de los procesos actuales y de los datos cargados en las
   planillas.
2. Parametrización del sistema y configuración de las integraciones necesarias.
3. Instalación del equipamiento y de los lectores de código de barras en las
   sucursales.
4. Migración inicial de los datos al sistema.
5. Capacitación del personal en el uso de los distintos módulos.
6. Puesta en marcha, idealmente con un piloto en una sucursal antes de extender
   el uso a la otra.
7. Estabilización y soporte post-implementación durante los primeros meses.

Como condiciones operativas para esta puesta en marcha conviene elegir un
período de menor movimiento del negocio para reducir el impacto sobre la
atención al cliente, mantener temporalmente las planillas en paralelo hasta
confirmar que el sistema funciona de forma estable y prever instancias de ajuste
luego de la primera etapa de uso.

## 8. Análisis económico y financiero

En esta sección se ordenan los números del proyecto: cuánto cuesta poner en
marcha el SIGC, cuánto cuesta mantenerlo cada año, qué beneficios económicos se
esperan y cómo queda el flujo de fondos a lo largo del horizonte de evaluación.
Todos los montos surgen del caso provisto por la cátedra y están expresados en
pesos. El detalle completo, con las fórmulas y los cálculos, se acompaña en el
archivo `Análisis económico y financiero - SIGC.xlsx` que se incluye en los
anexos (Sección 12).

### 8.1 Supuestos de trabajo

El análisis se apoya en los siguientes supuestos, tomados del enunciado:

| Supuesto | Valor |
|---|---|
| Horizonte de evaluación | 5 años |
| Tasa de descuento anual | 25% |
| Crecimiento anual de los beneficios | 8% |
| Inflación | No se considera |

La tasa del 25% se usa para traer a valor presente los flujos futuros y refleja
el rendimiento mínimo que la empresa le exige al proyecto. Al no considerarse
inflación, los valores se trabajan de forma constante a lo largo de los cinco
años.

### 8.2 Inversión inicial

La inversión inicial es el desembolso que la empresa realiza en el momento cero,
antes de que el sistema empiece a operar. Reúne todo lo necesario para dejar el
SIGC funcionando en las dos sucursales y en la administración:

| Concepto | Monto |
|---|---|
| Implementación del sistema | $4.200.000 |
| Configuración e integraciones | $2.600.000 |
| Equipamiento y lectores de código de barras | $2.200.000 |
| Migración de datos | $1.000.000 |
| Capacitación inicial | $800.000 |
| Contingencia | $1.200.000 |
| Total inversión inicial | $12.000.000 |

El rubro de contingencia se reserva para cubrir imprevistos durante la puesta en
marcha, como ajustes de configuración o demoras en alguna etapa.

### 8.3 Costos operativos anuales

Una vez en funcionamiento, el sistema genera costos que se repiten todos los
años. Son los gastos de mantener el servicio en el aire y al equipo capacitado:

| Concepto | Monto anual |
|---|---|
| Licencias y soporte | $3.600.000 |
| Hosting / infraestructura | $700.000 |
| Mantenimiento y ajustes | $500.000 |
| Capacitación continua | $300.000 |
| Total costos operativos anuales | $5.100.000 |

Estos costos se mantienen constantes en los cinco años del análisis y se
descuentan de los beneficios para obtener el flujo neto de cada período.

### 8.4 Beneficios esperados

Los beneficios son las mejoras económicas que se esperan a partir del uso del
sistema. Para el primer año se estiman en $11.300.000, repartidos así:

| Concepto | Monto año 1 |
|---|---|
| Ahorro de horas administrativas | $4.800.000 |
| Reducción de errores y reprocesos | $1.500.000 |
| Menores pérdidas por stock mal gestionado | $2.000.000 |
| Margen adicional por mejora en ventas | $3.000.000 |
| Total beneficios año 1 | $11.300.000 |

A partir del segundo año los beneficios crecen un 8% anual, acompañando la mayor
adopción del sistema y la mejora progresiva en la gestión. La proyección a cinco
años queda de la siguiente manera:

| Año | 1 | 2 | 3 | 4 | 5 |
|---|---|---|---|---|---|
| Beneficios | $11.300.000 | $12.204.000 | $13.180.320 | $14.234.746 | $15.373.525 |

### 8.5 Flujo de fondos del proyecto

Con la inversión inicial, los costos operativos y los beneficios proyectados se
arma el flujo de fondos. El año 0 recoge la inversión y, de los años 1 a 5, el
flujo neto es la diferencia entre los beneficios del período y los costos
operativos:

| Concepto | Año 0 | Año 1 | Año 2 | Año 3 | Año 4 | Año 5 |
|---|---|---|---|---|---|---|
| Inversión inicial | -$12.000.000 | — | — | — | — | — |
| Beneficios | — | $11.300.000 | $12.204.000 | $13.180.320 | $14.234.746 | $15.373.525 |
| Costos operativos | — | -$5.100.000 | -$5.100.000 | -$5.100.000 | -$5.100.000 | -$5.100.000 |
| Flujo neto | -$12.000.000 | $6.200.000 | $7.104.000 | $8.080.320 | $9.134.746 | $10.273.525 |

El flujo neto es positivo desde el primer año y crece a lo largo del horizonte,
lo que muestra que, una vez superada la inversión inicial, el proyecto genera
fondos de manera sostenida.

### 8.6 Indicadores económico-financieros

A partir del flujo de fondos se calcularon los principales indicadores de
evaluación, usando la tasa de descuento del 25%:

| Indicador | Resultado |
|---|---|
| VAN (Valor Actual Neto) | $8.751.704 |
| TIR (Tasa Interna de Retorno) | 54,2% |
| Payback simple | 1,82 años (aprox. 1 año y 10 meses) |
| Payback descontado | 2,60 años (aprox. 2 años y 7 meses) |

El VAN es positivo, lo que indica que el proyecto genera valor por encima de lo
que la empresa le exige al capital invertido. La TIR del 54,2% se ubica bastante
por encima de la tasa de descuento del 25%, lo que refuerza la conveniencia de
llevar adelante la inversión. El payback muestra que la inversión inicial se
recupera en menos de dos años en términos nominales, y en algo más de dos años y
medio si se considera el valor del dinero en el tiempo.

La lectura de estos resultados y la decisión final sobre el proyecto se
desarrollan en la Sección 9. El modelo completo, con la proyección de
beneficios, el flujo de fondos, los indicadores y un análisis de sensibilidad,
se encuentra en el archivo `Análisis económico y financiero - SIGC.xlsx`
adjunto en los anexos.

## 9. Evaluación del proyecto

En esta sección se analiza la conveniencia de llevar adelante el proyecto a
partir de los datos económicos de la Sección 8. La idea es interpretar los
resultados, ponerlos a prueba frente a distintos escenarios y llegar a una
conclusión fundamentada sobre la viabilidad del SIGC, usando las herramientas de
evaluación trabajadas en la materia.

### 9.1 Criterios de evaluación utilizados

Para evaluar el proyecto se recurrió a los criterios habituales de la evaluación
de proyectos de inversión:

- El Valor Actual Neto (VAN), que mide cuánto valor genera el proyecto por
  encima de la tasa exigida, trayendo todos los flujos a valor presente.
- La Tasa Interna de Retorno (TIR), que indica la rentabilidad propia del
  proyecto y se compara contra la tasa de descuento del 25%.
- El período de recupero (payback), simple y descontado, que muestra en cuánto
  tiempo se recupera la inversión inicial.
- La relación beneficio-costo, que compara el valor presente de los beneficios
  con el de la inversión y los costos.

Todos se aplicaron sobre el flujo de fondos a cinco años, con la tasa de
descuento del 25% indicada en el caso.

### 9.2 Análisis costo-beneficio

Si se llevan a valor presente los beneficios y los costos del proyecto a la tasa
del 25%, se obtiene el siguiente cuadro:

| Componente | Valor presente |
|---|---|
| Beneficios | $34.467.032 |
| Inversión inicial más costos operativos | $25.715.328 |
| Relación beneficio-costo | 1,34 |

La relación beneficio-costo de 1,34 significa que, por cada peso que la empresa
destina al proyecto en valor presente, recupera 1,34 pesos en beneficios. Al ser
mayor que 1, el proyecto se justifica desde lo económico.

### 9.3 Interpretación de los indicadores

Los indicadores calculados en la Sección 8 se interpretan de la siguiente
manera:

| Indicador | Resultado | Lectura |
|---|---|---|
| VAN (25%) | $8.751.704 | Es positivo, por lo que el proyecto agrega valor por encima de la tasa exigida. |
| TIR | 54,2% | Más que duplica la tasa de descuento del 25%, lo que indica un buen margen de rentabilidad. |
| Payback simple | 1,82 años | La inversión se recupera en términos nominales durante el segundo año. |
| Payback descontado | 2,60 años | Considerando el valor del dinero en el tiempo, el recupero se da pasada la mitad del horizonte. |

Los cuatro indicadores apuntan en la misma dirección: el proyecto es conveniente.
El VAN positivo y la TIR muy por encima de la tasa de corte muestran que la
inversión rinde bastante más de lo que la empresa le exige, y el recupero se da
dentro de los primeros años del horizonte de cinco.

### 9.4 Comparación de escenarios y sensibilidad

Como los resultados se apoyan en estimaciones, conviene ver cuán sensibles son a
cambios en los supuestos. Se trabajaron dos análisis, que también están
desarrollados en el archivo `Análisis económico y financiero - SIGC.xlsx`.

El primero observa cómo cambia el VAN si se modifica la tasa de descuento:

| Tasa de descuento | VAN |
|---|---|
| 15% | $14.406.469 |
| 20% | $11.310.070 |
| 25% (caso base) | $8.751.704 |
| 30% | $6.615.956 |
| 35% | $4.816.034 |
| 40% | $3.285.836 |

El VAN se mantiene positivo incluso con una tasa del 40%, lo que muestra que el
proyecto resiste exigencias de rentabilidad bastante mayores a la planteada.

El segundo análisis observa qué pasa si los beneficios estimados resultan
mayores o menores a los previstos, manteniendo la tasa en 25%:

| Escenario | VAN |
|---|---|
| Beneficios -20% | $1.858.298 |
| Beneficios -10% | $5.305.001 |
| Base (100%) | $8.751.704 |
| Beneficios +10% | $12.198.408 |
| Beneficios +20% | $15.645.111 |

Aun en el escenario más desfavorable, con beneficios un 20% por debajo de lo
estimado, el VAN sigue siendo positivo. Esto le da robustez a la conclusión: el
proyecto convendría incluso si las estimaciones de beneficios resultaran algo
optimistas.

### 9.5 Análisis de riesgo

Más allá de los números, conviene tener presentes los riesgos que podrían
afectar el resultado:

- Que los beneficios estimados tarden más en concretarse, sobre todo el ahorro
  de horas administrativas y la mejora en ventas, que dependen de la adopción
  del sistema por parte del personal.
- Que la implementación se demore o cueste más de lo previsto; para esto la
  inversión inicial ya contempla un rubro de contingencia de $1.200.000.
- Que aparezca resistencia al cambio en el uso de la nueva herramienta, lo que
  refuerza la importancia de la capacitación y del acompañamiento de la
  dirección señalados en la Sección 7.
- La dependencia del proveedor del sistema para el soporte y el mantenimiento,
  que está cubierta por el contrato anual incluido en los costos operativos.

El análisis de sensibilidad muestra que, aun considerando estos riesgos, el
proyecto mantiene un margen amplio antes de dejar de ser conveniente.

### 9.6 Conclusión de la evaluación

A partir de los criterios aplicados, la evaluación es favorable. El proyecto
presenta un VAN positivo de $8.751.704, una TIR del 54,2% muy superior a la tasa
de descuento del 25%, un recupero de la inversión dentro de los primeros años y
una relación beneficio-costo de 1,34. Los análisis de sensibilidad confirman que
estos resultados se sostienen frente a tasas más altas y a beneficios menores a
los estimados.

Por todo esto, se considera que la implementación del SIGC es económicamente
viable y conveniente para la empresa, y se recomienda llevarla adelante
acompañando la inversión con la capacitación y el seguimiento necesarios para
que los beneficios proyectados se concreten.

## 10. Conclusiones

A lo largo del trabajo se analizó la propuesta de implementar un Sistema
Integral de Gestión Comercial y un tablero de control en una PyME comercial con
dos sucursales. El punto de partida fue una situación en la que la información
estaba dispersa en planillas separadas, el stock se controlaba de forma manual y
los reportes se armaban a mano, lo que generaba errores, demoras y dificultades
para tomar decisiones. A partir de ese problema se definió el proyecto, se
describió su alcance, se analizó el contexto en el que se inserta y se evaluaron
sus aspectos técnicos, organizacionales y económicos.

Del análisis técnico y organizacional surge que la propuesta es realizable con
los recursos habituales de una PyME que se digitaliza: un sistema contratado
bajo licencia, hosting en la nube, equipamiento para las sucursales y el
acompañamiento del proveedor para la configuración, la migración y la
capacitación. No requiere infraestructura compleja ni desarrollos propios, pero
sí supone cambios en la forma de trabajo y la designación de un referente
interno que coordine con el proveedor.

Desde lo económico, la evaluación resultó favorable. Con una inversión inicial
de $12.000.000, costos operativos de $5.100.000 anuales y beneficios que parten
de $11.300.000 en el primer año, el proyecto muestra un VAN positivo de
$8.751.704, una TIR del 54,2% muy por encima de la tasa de descuento del 25% y
un recupero de la inversión dentro de los primeros años. La relación
beneficio-costo de 1,34 y los análisis de sensibilidad refuerzan esa conclusión,
ya que el VAN se mantiene positivo aun con tasas más altas o con beneficios
menores a los estimados.

Por todo esto se concluye que el proyecto es viable y conveniente. De todos
modos, su éxito depende de algunas condiciones: acompañar la implementación con
una capacitación adecuada, sostener el compromiso de la dirección durante la
puesta en marcha, mantener disciplina en la carga de la información para que el
sistema sea una única fuente confiable y respetar las etapas de implementación
propuestas, idealmente con un piloto en una sucursal antes de extender el uso a
la otra.

Como aporte principal, la propuesta ordena la gestión comercial de la empresa,
centraliza la información de las dos sucursales y le da a la dirección un tablero
de control para decidir con datos. Entre las limitaciones, hay que tener
presente que tanto los beneficios como los costos son estimaciones basadas en el
caso provisto, que los beneficios dependen en buena medida de la adopción del
sistema por parte del personal y que el análisis se realizó sin considerar
inflación, por lo que en una aplicación real esos valores deberían revisarse y
actualizarse. Con esos recaudos, la implementación del SIGC se presenta como una
inversión que mejora la operación del negocio y genera valor para la empresa.

## 11. Bibliografía

Para la elaboración del trabajo se utilizaron principalmente los materiales de
la cátedra Sistemas de Gestión (UTN, Facultad Regional San Rafael, ciclo lectivo
2026), tanto los documentos del proyecto integrador como los apuntes y
presentaciones de las clases. A continuación se detallan las fuentes consultadas.

### Documentos del proyecto integrador

- Cátedra Sistemas de Gestión (2026). Práctica integradora guiada con caso
  provisto por la cátedra. UTN, Facultad Regional San Rafael.
- Cátedra Sistemas de Gestión (2026). Plantilla orientativa de entrega del
  proyecto integrador. UTN, Facultad Regional San Rafael.
- Cátedra Sistemas de Gestión (2026). Criterios generales de evaluación del
  proyecto. UTN, Facultad Regional San Rafael.

### Material teórico de la cátedra

- Cátedra Sistemas de Gestión (2026). Fundamentos de formulación y evaluación de
  proyectos (Clase 1). UTN, Facultad Regional San Rafael.
- Cátedra Sistemas de Gestión (2026). Gestión de proyectos (Clase 2). UTN,
  Facultad Regional San Rafael.
- Cátedra Sistemas de Gestión (2026). Formulación estratégica de proyectos
  (Clase 3). UTN, Facultad Regional San Rafael.
- Cátedra Sistemas de Gestión (2026). Formulación aplicada de proyectos de
  inversión (Clase 4). UTN, Facultad Regional San Rafael.
- Cátedra Sistemas de Gestión (2026). Fundamentos económico-contables para la
  formulación de proyectos de sistemas (Clases 5 y 6). UTN, Facultad Regional
  San Rafael.
- Cátedra Sistemas de Gestión (2026). Evaluación financiera de proyectos: el
  valor del dinero y criterios de rentabilidad (Clase 7). UTN, Facultad Regional
  San Rafael.
- Cátedra Sistemas de Gestión (2026). Formulación estratégica de proyectos de
  sistemas: entorno, mercado y propuesta de valor (Clase 9). UTN, Facultad
  Regional San Rafael.
- Cátedra Sistemas de Gestión (2026). Estrategia comercial y canales de venta en
  proyectos de TI (Clase 11). UTN, Facultad Regional San Rafael.
- Cátedra Sistemas de Gestión (2026). De la formulación estratégica al flujo de
  fondos evaluable (Clase 13). UTN, Facultad Regional San Rafael.
- Cátedra Sistemas de Gestión (2026). El tamiz financiero: la tasa de descuento y
  los modelos CAPM y WACC (Clase 14). UTN, Facultad Regional San Rafael.
- Cátedra Sistemas de Gestión (2026). Evaluación económica de proyectos de TI:
  flujos de fondos y criterios de decisión (Clase 15). UTN, Facultad Regional
  San Rafael.
- Cátedra Sistemas de Gestión (2026). Integración de la evaluación económica: del
  modelo financiero a la decisión estratégica (Clase 16). UTN, Facultad Regional
  San Rafael.
- Cátedra Sistemas de Gestión (2026). Financiamiento de proyectos y análisis de
  riesgo (Clase 17). UTN, Facultad Regional San Rafael.
- Cátedra Sistemas de Gestión (2026). Comunicación, negociación y toma de
  decisiones en la ingeniería de gestión (Clase 18). UTN, Facultad Regional San
  Rafael.

## 12. Anexos

*(Pendiente)*
