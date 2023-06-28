---
title: Etapa 2. Ejecución Gobierno. Incremento 1
keywords:
- SOA
- madurez
- gobierno
- FNA
lang: en-US
date-meta: '2023-06-28'
author-meta:
- Harry Wong, ing.
- Wilson Morales, ing.
- Flavio Hernandez, ing.
- Viviana M. Martinez, ing.
header-includes: |
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta property="og:type" content="article" />
  <meta name="dc.title" content="Etapa 2. Ejecución Gobierno. Incremento 1" />
  <meta name="citation_title" content="Etapa 2. Ejecución Gobierno. Incremento 1" />
  <meta property="og:title" content="Etapa 2. Ejecución Gobierno. Incremento 1" />
  <meta property="twitter:title" content="Etapa 2. Ejecución Gobierno. Incremento 1" />
  <meta name="dc.date" content="2023-06-28" />
  <meta name="citation_publication_date" content="2023-06-28" />
  <meta property="article:published_time" content="2023-06-28" />
  <meta name="dc.modified" content="2023-06-28T12:34:42+00:00" />
  <meta property="article:modified_time" content="2023-06-28T12:34:42+00:00" />
  <meta name="dc.language" content="en-US" />
  <meta name="citation_language" content="en-US" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="Harry Wong, ing." />
  <meta name="citation_author_institution" content="Arquitecto SOA, Stefanini" />
  <meta name="citation_author" content="Wilson Morales, ing." />
  <meta name="citation_author_institution" content="Software, Aplicaciones" />
  <meta name="citation_author" content="Flavio Hernandez, ing." />
  <meta name="citation_author_institution" content="SOA, Arquitectura" />
  <meta name="citation_author" content="Viviana M. Martinez, ing." />
  <meta name="citation_author_institution" content="Analista, Proyectos" />
  <link rel="canonical" href="https://hwong23.github.io/fna-dd-f2-e2/" />
  <meta property="og:url" content="https://hwong23.github.io/fna-dd-f2-e2/" />
  <meta property="twitter:url" content="https://hwong23.github.io/fna-dd-f2-e2/" />
  <meta name="citation_fulltext_html_url" content="https://hwong23.github.io/fna-dd-f2-e2/" />
  <meta name="citation_pdf_url" content="https://hwong23.github.io/fna-dd-f2-e2/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://hwong23.github.io/fna-dd-f2-e2/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://hwong23.github.io/fna-dd-f2-e2/v/d251ecf2faeb0513a245fb16b0858e0ee48bee01/" />
  <meta name="manubot_html_url_versioned" content="https://hwong23.github.io/fna-dd-f2-e2/v/d251ecf2faeb0513a245fb16b0858e0ee48bee01/" />
  <meta name="manubot_pdf_url_versioned" content="https://hwong23.github.io/fna-dd-f2-e2/v/d251ecf2faeb0513a245fb16b0858e0ee48bee01/manuscript.pdf" />
  <meta property="og:type" content="article" />
  <meta property="twitter:card" content="summary_large_image" />
  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />
  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />
  <meta name="theme-color" content="#ad1457" />
  <!-- end Manubot generated metadata -->
bibliography:
- content/manual-references.bib
- content/manual-references.json
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
manubot-clear-requests-cache: false
...




<small><em>Los productos contractuales (PR0n) de esta etapa([Web](https://hwong23.github.io/fna-dd-f2-e2/v/d251ecf2faeb0513a245fb16b0858e0ee48bee01/))
están basados en el resultado de la consultoría "Arquitectura E-Service",
[Sharepoint STEF@d251ecf](https://stefaninilatam.sharepoint.com/:f:/r/sites/PROYECTOARQUITECTURAE-SERVICEFNA/Documentos%20compartidos/General/Repositorio%20SOA/Procesos%20Fase%20II/181-2020.%20E-SERV.%20Fase%202-ETAPA%200.%20docx?csf=1&web=1&e=BiNcBP)
del June 28, 2023.
</em></small>

|    **Versión** del producto 1.d251ecf de 28 Jun 2023



<br>

## Autores



+ **Harry Wong, ing.**
  <br>
    · ![Usuario](images/github.svg){.inline_icon width=16 height=16}
    [e_hwong](https://github.com/e_hwong)
    <br>
  <small>
     Arquitecto SOA, Stefanini
  </small>

+ **Wilson Morales, ing.**
  <br>
    · ![Usuario](images/github.svg){.inline_icon width=16 height=16}
    [wmorales](https://github.com/wmorales)
    <br>
  <small>
     Software, Aplicaciones
  </small>

+ **Flavio Hernandez, ing.**
  <br>
    · ![Usuario](images/github.svg){.inline_icon width=16 height=16}
    [fhernandez](https://github.com/fhernandez)
    <br>
  <small>
     SOA, Arquitectura
  </small>

+ **Viviana M. Martinez, ing.**
  <br>
    · ![Usuario](images/github.svg){.inline_icon width=16 height=16}
    [vmmartinez](https://github.com/vmmartinez)
    <br>
  <small>
     Analista, Proyectos
  </small>


::: {#correspondence}
✉ — Enviar mensajes a Harry Wong, ing. \<e_hwong@stefanini.com\>.


:::

<br>



## Objetivo del Documento
Entrega de los productos de la Etapa 2, PR04 y PR05, del proyecto Gobierno SOA: Políticas, flujos de trabajo y personas que ejercitan y conforman (cumplen) con el gobierno SOA del FNA a desplegar a cargo de la oficina de arquitectura.


##  Control de Cambios {.page_break_before}
| Tema           | PRY01 Gobierno SOA FNA     |
|----------------|----------------------------|
| Palabras clave | SOA, E-Service, FNA, Análisis de brecha, GAP, Comparativa              |
| Autor          |                            |
| Fuente         |                            |
| Versión        | 1.d251ecf del 28 Jun 2023 |
| Vínculos       | [N003a Vista Segmento SOA FNA](N03a%a20Vsta%20aSegenta%20SOA%20FNA.md) |

<br>

<br>

***
<div style="page-break-before: always;"></div>


---
geometry:
  - top=1in
  - bottom=1in
fignos-cleveref: True
fignos-plus-name: Fig.
fignos-caption-name: Imagen
tablenos-caption-name: Tabla
...

>    E-Service. Fase II
>
>    PRY01 Gobierno SOA. Contenido de los Productos Contractuales
>
>    Contrato 1812020
>
>    FNA, Stefanini
>
>    28 Jun 2023
>
>    **Versión** 1.d251ecf

<br>

# Producto 4: PR04. Definición de roles y responsabilidades y selección e instalación del comité
Desarrollo de procedimientos, funciones, entregables, selección de roles y herramientas a desplegar para la puesta en marcha de un Comité de Arquitectura del FNA adscrito a la Vicepresidencia de Tecnología FNA y en cumplimiento con el Gobierno SOA, versión 0.5, objeto de este proyecto.

**Nota**: los análisis de este producto están dirigidos a cumplir los objetivos del proyecto PRY01, Gobierno SOA: desarrollo, gestión, gobierno de arquitectura y adopción.

<br>

## Justificación
El Comité de Arquitectura es la entidad de supervisión ubicada entre la oficina de arquitectura (PR02, objeto de este proyecto) y los líderes de grupo de productos del FNA y áreas interesadas. Es una figura necesaria dado los resultados de los diagnósticos SOA, en particular el de riesgos técnicos, realizados en la Fase I de la consultoría E-Service que señalan como causantes a la complejidad y (baja) agilidad que enfrenta el FNA. El Comité de Arquitectura funge como complemento, apoyo y arbitraje (directriz) de los decisiones conciernentes a los trabajo de arquitectura del FNA dirigidos a la solución de estos problemas.

## Contenidos
1. Modelo operativo del Comité de Gobierno de Arquitectura del FNA: actores, información y procedimientos
1. Consideraciones para la puesta en marcha del Comité
1. Aplicaciones de soporte a la Oficina de Arquitecura (Pr02) y a la Vicepresidencia de Tecnología del FNA
1. Matriz de responsabilidades y procedimiento del Comité de Arquitectura
1. Métodos de evaluación de arquitecturas para el FNA

<br>

## Criterios de Aceptación
* Entendimiento funcional y operativa del comité de arquitectura del FNA
* Matriz de roles y procedimientos del del comité de  arquitetura del FNA

<br>

## Modelo de Implementación del PRY01
![Plan de Implementación del Proyecto Hoja de Ruta E-Service FNA, 2023. Abril 2023 a Agosto 2023](images/pry1gobierno.jpg){#fig: width=lin}

_Fuente: Elaboración propia._

<br>


---
geometry:
  - top=1in
  - bottom=1in
fignos-cleveref: True
fignos-plus-name: Fig.
fignos-caption-name: Imagen
tablenos-caption-name: Tabla
...

***

>    E-Service. Fase II
>
>    PRY01. Gobierno SOA del FNA. Contenido de los Productos Contractuales
>
>    Contrato 1812020
>
>    FNA, Stefanini
>
>    28 Jun 2023
>
>    **Versión** 1.d251ecf

<br>

# Producto 5: PR05. Procesos de mejoramiento de diseño y vigilancia de riesgos técnicos
Uno de los principales valores que un Gobierno entrega es la identificación y la gestión de las acciones para controlar los riesgos. Y en el caso de este ejercicio de gobierno trataremos los riesgos de tecnología y de arquitectura SOA del FNA consignados en el estudio E-Service, Fase I (2022). 

El producto 5 es el detalle de los procedimientos y técnicas de tratamiento y modelamiento diseñadas para la operación de los riesgos técnicos del FNA consignados en el estudio E-Service, Fase I (2022).

**Nota**: los análisis de este producto están dirigidos a cumplir los objetivos del proyecto PRY01, Gobierno SOA: desarrollo, gestión, gobierno de arquitectura y adopción.

<br>

## Justificación
El tratamiento de los riesgos tecnológicos identifidos en el diagnóstco SOA de Fase I, E-Service (2022) (ver [03.Fase 1 PR3 Resultado Diagnóstico Situación Actual](N03a%a20Vsta%20aSegenta%20SOA%20FNA.md)) exigen acciones tal que mitiguen y adviertan al FNA sobre los impactos que estos comportan. El desarrollo de la vigilancia de los riesgos técnicos entra a reforzar al gobierno SOA del Fondo Nacional del Ahorro en curso en este proyecto y resulta en la personalización y aplicación de métodos que den tratamiento a estos. Además, operar los riesgos técnicos es de carácter obligatorio, dado que es un objetivo del Gobierno SOA del FNA: objtivo Vigilancia del riesgo tecnológico (G-OBJ1).

## Contenidos
1. Definición y tratamiento del riesgo técnico del FNA
1. Modelamiento del riesgo técnico del FNA
1. Métodos para el tratamiento de los riesgos técnicos E-Service Fase I

<br>

## Criterios de Aceptación
El producto 5 es el detalle de los procedimientos de tratamiento y técnicas de modelamiento diseñadas para el tratamiento de los riesgos técnicos del FNA consignados en el estudio E-Service, Fase I (2022).

* Procedimientos y técnicas de modelamiento para el tratamiento de los riesgos técnicos del FNA (E-Service, 2022)
* Matriz de riesgos técnicos e impactos del FNA

<br>

## Modelo de Implementación del PRY01
![Plan de Implementación del Proyecto Hoja de Ruta E-Service FNA, 2023. Abril 2023 a Agosto 2023](images/pry1gobierno.jpg){#fig: width=lin}

_Fuente: Elaboración propia._

<br>



# Referencias {.page_break_before}
<!-- Explicitly insert bibliography here -->
<div id="refs">E-Service. Situación SOA Actual del FNA. Etapa I. (2022).</div>
<div id="refs">E-Service. Arquitectura de Referencia del FNA. Etapa II. (2023).</div>
<div id="refs">E-Service. Hoja de Ruta e Iniciativas. Etapa III. (2023).</div>
<div id="refs">TOGAF 9.1. Risk Management (2023). En https://pubs.opengroup.org/architecture/togaf9-doc/arch/chap27.html</div>


