# Fase 4 — Documentación técnica y Archivos finales del dispensador

## 1. Información general

| Campo | Información |
|---|---|
| Proyecto | Diseño y ensamblaje de un dispensador |
| Fase | 4 |
| Estudiante | Tamara Sequeira Rosales-Nohelia Loaisiga Sandoval |
| Curso | ICT401 – Dibujo Técnico Asistido por Computadora |
| Software | Autodesk Fusion 360 |
| Entrega | Semana 16 |

---
### Archivos de Autodesk Fusion

Los archivos nativos correspondientes al proyecto se encuentran en las carpetas de Autodesk Fusion 360 llamadas Tamara Sequeira y Nohelia Loaisiga.

### Archivos de Autodesk Fusion

Los archivos nativos correspondientes al proyecto se encuentran en las carpetas de Autodesk Fusion 360 llamadas **Dinoska Carrillo** y **Leslie Rivel**.

| **Archivo** | **Descripción** |
|---|---|
| `Proyecto_integrador_ensamblaje` | Ensamble general completo de la tapa dispensadora de granos. |
| `P1_Tapa_proyecto_Integrador1` | Componente principal del cuerpo/base de la tapa dispensadora. |
| `P2_Proyecto_Integrador1` | Mecanismo interno / dosificador rotativo de granos. |
| `P3_tapa_proyecto_Integrador1` | Comprobadora / Cubierta superior de la boquilla dispensadora. |


## 2. Introducción al proyecto

En esta fase se desarrollara la documentación técnica final del dispensador diseñado en Autodesk Fusion 360. Se trabaja con el ensamblaje de sus componentes, las relaciones mecánicas, la revisión del movimiento y la elaboración de los planos técnicos.

El proyecto integra tres componentes principales que conforman el diseño del dispensador: P1, P2 y P3. Cada pieza cumple una función dentro de la estructura y el funcionamiento del conjunto.

## 3. Objetivos de la fase

- Revisar la integración de los componentes del dispensador.
- Aplicar y comprobar las relaciones de posición y movimiento.
- Verificar la alineación y el contacto entre las piezas.
- Identificar posibles interferencias físicas en el ensamblaje.
- Elaborar la documentación técnica correspondiente.
- Preparar los archivos y las evidencias finales del proyecto.

## 4. Herramientas y recursos utilizados

- **Autodesk Fusion 360:** modelado tridimensional, ensamblaje y elaboración de planos técnicos.
- **Herramientas de ensamblaje:** configuración y revisión de las relaciones mecánicas.
- **Drawing:** creación de vistas y acotaciones técnicas.
- **Animation:** representación del movimiento del conjunto, cuando corresponda.
- **GitHub:** organización y documentación del proyecto mediante Markdown.

## 5. Componentes del dispensador

El diseño está integrado por tres componentes principales:

| Componente | Nombre | Descripción |
|---|---|---|
| P1 | Collar | Componente identificado como P1 dentro del diseño. |
| P2 | Tapa | Componente identificado como P2 dentro del diseño. |
| P3 | Tapón | Componente identificado como P3 dentro del diseño. |

### 5.1. Modelo tridimensional final

A continuación, se presenta el modelo tridimensional del dispensador, en el que se observa la integración de sus componentes y su configuración general.


**Figura 1.** Modelo tridimensional del dispensador desarrollado en Autodesk Fusion 360.
![Modelo tridimensional final del dispensador](imagenes/dispensador_final.png)
<img width="691" height="521" alt="image" src="https://github.com/user-attachments/assets/218e76e5-dfa8-4d26-b49d-b5430d6f6d3f" />


---

## 6. Ensamblaje y relaciones mecánicas

En esta etapa se trabajó con la integración de los componentes del dispensador en Autodesk Fusion 360, con el propósito de establecer las relaciones necesarias para mantener las piezas correctamente posicionadas y permitir el movimiento correspondiente del conjunto.

### 6.1. Integración de los componentes

El ensamblaje está compuesto por los tres componentes principales del dispensador: P1, P2 y P3. Estos se integraron en un mismo diseño para representar la configuración general del dispositivo.

**Figura 2.** Ensamblaje de los componentes del dispensador.

<img width="918" height="362" alt="image" src="https://github.com/user-attachments/assets/900333c7-9097-4947-81b2-aeb431a6cf05" />

 

### 6.2. Relaciones de unión

Para establecer la posición y el comportamiento de los componentes se utilizaron las siguientes relaciones mecánicas:

| Relación | Función |
|---|---|
| Cilíndrica | Permite el movimiento de giro y desplazamiento a lo largo del eje, según su configuración. |
| Rígida | Mantiene los componentes unidos sin permitir movimiento relativo entre ellos. |

**Figura 3.** Relaciones mecánicas configuradas en Autodesk Fusion 360.

[Relación de unión cilíndrica]<img width="853" height="510" alt="image" src="https://github.com/user-attachments/assets/6775277b-dcb5-4cdb-b89a-f6bd11db7fa2" />


[Relación de unión rígida]<img width="755" height="503" alt="image" src="https://github.com/user-attachments/assets/094dc03e-a5bb-4132-b582-af4e3b50f3a4" />



### 6.3. Verificación del movimiento del ensamblaje

Se comprobó el comportamiento de las relaciones mecánicas configuradas en el ensamblaje mediante la herramienta de animación de uniones de Autodesk Fusion 360.

La unión cilíndrica permitió observar el movimiento de giro y desplazamiento del componente conectado, mientras que la unión rígida mantuvo fija la posición relativa de los componentes vinculados.

Las capturas anteriores muestran el comportamiento de ambas relaciones durante su comprobación.

## 6.3. Acotación y tolerancias dimensionales

Para el plano técnico se incorporaron las dimensiones necesarias para representar las características geométricas de la tapa dispensadora.

Se aplicó una tolerancia dimensional al diámetro de encaje y giro del mecanismo interno mediante la opción **Deviation**, estableciendo una desviación superior de **+0.15 mm** y una inferior de **-0.05 mm** respecto a la dimensión nominal.

Esta configuración permite representar los límites de variación requeridos para evitar fugas de granos pequeños y asegurar que la pieza gire suavemente sin atascarse.

### Tabla de tolerancias dimensionales

| **Criterio** | **Valor** |
|---|---|
| Tipo de tolerancia | Deviation |
| Desviación superior | +0.15 mm |
| Desviación inferior | -0.05 mm |

<img width="1358" height="629" alt="image" src="https://github.com/user-attachments/assets/0c8f0a9d-4310-4b9c-b0af-5eb3890f634b" />

## 7. Elaboración del plano técnico (Drawing)

Se elaboró el Drawing de la tapa dispensadora de granos en Fusion, incorporando las vistas principal, de sección (corte) y acotaciones correspondientes al modelo tridimensional.

El plano permite observar el perfil de agarre lateral, el sistema de dosificación y las dimensiones requeridas para interpretar la geometría completa.

Se realizó una revisión de las cotas y de la representación de las piezas para mantener la exactitud entre el modelo 3D y el dibujo técnico.

**Evidencia del plano técnico completo:**

<img width="1343" height="689" alt="image" src="https://github.com/user-attachments/assets/bf479a82-1e03-4b6b-a05e-29466e317354" />

<img width="1360" height="687" alt="image" src="https://github.com/user-attachments/assets/f06fcbfa-ad94-4daa-9cf3-872683606cb6" />


## 8. Archivos de intercambio y documentación final

En esta sección se incorporan los enlaces a los archivos derivados del proyecto, para facilitar su consulta y descarga.

| **Archivo** | **Formato** | **Enlace** |
|---|---|---|
| Plano Técnico | PDF |[Descargar PDF](Proyecto_integrador_ensamblaje222Dibujo.pdf) |
| Plano Técnico editable | DXF | [Descargar DXF](Proyecto_integrador_ensamblaje222.dxf)|
| Modelo tridimensional | STEP | [Descargar STE](Proyecto_integrador_ensamblaje222.step)|
| Modelo para impresión 3D | STL |  [Descargar STL](Proyecto_integrador_ensamblaje222.stl) |

## 9. Dificultades y decisiones técnicas

### Dificultad principal

Establecer las relaciones de junta y restricciones de movimiento en Autodesk Fusion para que el mecanismo dosificador rotara de forma fluida sin interferir geométricamente con el cuerpo de la tapa.

### Decisión técnica más importante

Adoptar un sistema de tolerancias de ajuste deslizante en las zonas de contacto entre la pieza móvil y la base de la tapa, además de incorporar estrías laterales exteriorizadas para mejorar el agarre ergonómico durante la manipulación manual.

### Resultado final

Se completó exitosamente la documentación técnica de la tapa dispensadora de granos mediante el modelo tridimensional final, las animaciones de apertura y cierre, la configuración de tolerancias dimensionales y la emisión de los planos técnicos Drawing.

---

## 10. Archivos de Fusion

| **Archivo** | **Enlace** |
|---|---|
| Drawing |  https://a360.co/4it5QZq|
| Animación | https://a360.co/4zenpCg |
