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

El presente trabajo constituye el Proyecto Integrador de la cátedra **Sistemas de
Gestión**, correspondiente al quinto año de la carrera Ingeniería en Sistemas de
Información de la Universidad Tecnológica Nacional, Facultad Regional San Rafael.
Su finalidad es integrar y aplicar, sobre un caso concreto, los contenidos
desarrollados a lo largo de la cursada en torno a la formulación y evaluación de
proyectos de inversión vinculados a las tecnologías de la información.

El proyecto se enmarca en la **formulación y evaluación de un proyecto de
inversión tecnológica** para una pequeña y mediana empresa (PyME) del sector
comercial. A partir de un caso provisto por la cátedra, se analiza la
incorporación de un **Sistema Integral de Gestión Comercial y Tablero de
Control** que reemplace la operatoria manual basada en planillas de cálculo y
registros dispersos con la que la empresa administra actualmente sus ventas, su
stock, sus clientes y sus reportes.

El propósito del trabajo es **recorrer el ciclo completo de un proyecto de
inversión**: identificar con claridad el problema u oportunidad que le da origen,
formular una propuesta de valor coherente, definir su alcance, analizar sus
requerimientos técnicos y organizacionales y, finalmente, evaluar su conveniencia
económica y financiera. Para ello se construye un flujo de fondos proyectado, se
calculan los principales criterios de rentabilidad —Valor Actual Neto (VAN) y
Tasa Interna de Retorno (TIR)—, se analiza el comportamiento del proyecto frente
a la incertidumbre y se considera una alternativa de financiamiento, todo lo cual
conduce a una recomendación final fundamentada.

De este modo, el documento busca mostrar no solo un resultado numérico, sino el
razonamiento que articula los aspectos estratégicos, técnicos, organizacionales y
financieros de una decisión de inversión, tal como se aborda a lo largo de la
materia.

## 4. Presentación del problema u oportunidad

### 4.1 Contexto en el que surge la situación

La organización sobre la que se desarrolla el proyecto es una pequeña y mediana
empresa (PyME) del sector comercial, dedicada a la comercialización de productos
a través de **dos sucursales** y de un canal de venta no presencial mediante
**WhatsApp y correo electrónico**. Su operatoria diaria —la gestión de pedidos,
del stock, de los clientes y de los reportes— se sostiene actualmente con
**planillas de cálculo y registros manuales**, sin un sistema de información que
integre esas tareas.

Este esquema resultó suficiente en las etapas iniciales de la empresa, pero a
medida que aumentan el volumen de operaciones y la cantidad de puntos de venta,
las herramientas manuales se vuelven difíciles de mantener: la información queda
dispersa, desactualizada y sujeta a errores. La dirección de la empresa advierte
esta limitación y evalúa la incorporación de un sistema integral de gestión
comercial como respuesta.

### 4.2 Problema detectado

El problema central es que **la gestión comercial de la empresa depende de
procesos manuales y de información no integrada**, lo que genera errores,
ineficiencia y falta de visibilidad. Las dificultades concretas relevadas pueden
agruparse en cuatro ejes:

| Eje | Dificultades identificadas |
|---|---|
| **Información dispersa y sin trazabilidad** | Falta de trazabilidad de ventas y clientes; ausencia de una base centralizada de clientes. |
| **Errores operativos** | Diferencias frecuentes entre el stock real y el registrado; errores en la carga de pedidos y en la facturación. |
| **Ineficiencia operativa** | Demoras en la atención de pedidos; fuerte dependencia de tareas manuales repetitivas. |
| **Falta de información para decidir** | Dificultad para conocer los márgenes por producto; escasa información para la toma de decisiones de la gerencia. |

Estas dificultades no son independientes entre sí: la falta de integración de la
información es la causa de fondo de la que se derivan, en mayor o menor medida,
las demás.

### 4.3 Por qué resulta relevante abordar la situación

Abordar esta situación es relevante porque sus consecuencias **impactan
directamente sobre la rentabilidad y la competitividad** de la empresa:

- Los descuadres de stock y la dificultad para conocer los márgenes por producto
  generan pérdidas económicas y decisiones de compra y de precios poco
  fundamentadas.
- Las demoras y los errores en pedidos y facturación afectan la calidad del
  servicio, provocan reclamos y pueden derivar en la pérdida de clientes.
- La dependencia de tareas manuales consume tiempo del personal en actividades
  de bajo valor agregado, que podría destinarse a la atención y a la venta.
- La falta de información oportuna limita la capacidad de la dirección para
  tomar decisiones, justamente cuando la empresa atraviesa una etapa de
  crecimiento.

Además, se trata de un problema **creciente**: cuanto mayor sea el volumen de
operaciones, mayores serán los errores y las pérdidas asociadas al esquema
manual. El hecho de que la propia dirección ya esté evaluando una solución
muestra que existe conciencia del problema y voluntad de invertir para
resolverlo.

### 4.4 Necesidad u oportunidad que busca atender el proyecto

A partir de lo anterior, el proyecto busca atender la necesidad de
**centralizar, integrar y ordenar la gestión comercial de la empresa** mediante
un sistema único. Más que la corrección de fallas aisladas, se plantea como una
**oportunidad de mejora** orientada a:

- contar con información única, confiable y actualizada sobre ventas, stock y
  clientes;
- reducir los errores de carga, facturación y control de inventario;
- automatizar las tareas manuales repetitivas y agilizar la atención de pedidos;
- brindar a la gerencia un tablero de control con indicadores que sustente la
  toma de decisiones;
- sentar una base ordenada para el crecimiento futuro de la empresa.

En síntesis, la situación da origen a un proyecto cuyo sentido no es únicamente
tecnológico, sino de **mejora de la eficiencia, del control y de la capacidad de
gestión** del negocio.

## 5. Descripción general del proyecto

*(Pendiente)*

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
