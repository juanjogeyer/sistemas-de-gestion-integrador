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

**Implementación de un Sistema Integral de Gestión Comercial y Tablero de
Control.** A lo largo del documento, el sistema se referenciará de forma
abreviada como **SIGC** (Sistema Integral de Gestión Comercial).

### 5.2 Descripción general de la propuesta

El proyecto consiste en **implementar un sistema integral de gestión comercial**
que reemplace las planillas de cálculo y los registros manuales por una única
herramienta informática, utilizada en las dos sucursales de la empresa.

El sistema integra, en un mismo entorno, los siguientes componentes:

- **Sistema de gestión comercial**, que registra y administra las ventas de
  ambas sucursales, incluidas las originadas por los canales de WhatsApp y
  correo electrónico.
- **Módulo de stock e inventario**, que mantiene actualizado el stock en tiempo
  real, apoyado en lectores de código de barras.
- **Base centralizada de clientes**, que reúne en un único repositorio la
  información hoy dispersa.
- **Carga digital de pedidos**, que ordena y estandariza el ingreso de pedidos y
  su posterior facturación.
- **Reportes comerciales** y un **tablero de control** con indicadores para la
  gerencia.

La implementación incluye, además, la **migración inicial de los datos**
existentes en las planillas y la **capacitación de los usuarios**, de modo de
asegurar la puesta en marcha y la adopción del sistema.

### 5.3 Objetivo principal

Dotar a la empresa de un sistema integral de gestión comercial que **centralice
y automatice la administración de las ventas, el stock y los clientes**,
reduciendo los errores y los tiempos de proceso, y que provea a la dirección
**información oportuna y confiable** para la toma de decisiones.

### 5.4 Objetivos específicos

1. Centralizar en un único sistema la información de ventas, stock y clientes
   hoy dispersa en planillas y registros manuales.
2. Mantener el stock actualizado en tiempo real, incorporando la lectura de
   código de barras para reducir las diferencias entre el stock real y el
   registrado.
3. Digitalizar la carga de pedidos y la facturación para disminuir los errores y
   las demoras en la atención.
4. Constituir una base centralizada de clientes que permita la trazabilidad de
   las ventas.
5. Proveer reportes comerciales y un tablero de control con indicadores que
   sustente la toma de decisiones de la gerencia.
6. Reducir la dependencia de tareas manuales repetitivas, liberando tiempo del
   personal para tareas de mayor valor.
7. Asegurar la adopción del sistema mediante la migración de los datos
   existentes y la capacitación de los usuarios.

### 5.5 Alcance del proyecto

El proyecto abarca la implementación completa del sistema en las dos sucursales
actuales de la empresa.

**Incluye:**

- Los módulos de ventas, stock e inventario, clientes, carga digital de pedidos,
  reportes comerciales y tablero de control.
- La configuración del sistema y las integraciones necesarias para su puesta en
  marcha.
- El equipamiento y los lectores de código de barras para las dos sucursales.
- La migración inicial de los datos existentes en las planillas de cálculo.
- La capacitación inicial de los usuarios.

**No incluye (en esta etapa):**

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

*(Pendiente)*

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
