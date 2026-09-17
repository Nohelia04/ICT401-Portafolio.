# ICT401 · Semana 9 — Laboratorio integrador I-B

**Reconstrucción 3D a partir de un plano o conjunto de vistas — 10 %**

- Estudiante: [Nohelia Loaisiga Sandoval]
- Grupo: [60]
- Fecha: [17_09_2026]
- Nombre del archivo de Fusion: `ICT401_S09_LabIB_Apellido_Nombre`
- Carpeta/proyecto de Fusion Cloud con acceso docente: [Respuesta]
- Commit de entrega: [Respuesta]

## Instrucciones de uso de esta ficha

Complete esta ficha durante el laboratorio. No borre respuestas iniciales aunque luego las corrija. Cuando cambie una decisión, explique qué evidencia del plano o del modelo motivó la modificación.

La ficha debe quedar en `Portafolio/semana09/` con el nombre `S09_Lab_IB_Evidencias_Apellido_Nombre.md`. Las imágenes enlazadas deben estar en la misma carpeta. El archivo nativo permanece en Fusion Cloud con acceso docente.

Esta ficha forma parte de la evidencia evaluable del Laboratorio integrador I-B y está estructurada para facilitar una revisión posterior por la persona docente o mediante ChatGPT. La calificación final corresponde siempre al instrumento oficial del curso.

---

## A. Interpretación inicial del plano

### A1 · Dimensiones generales

- X total: [90mm]
- Y total: [60mm]
- Z total: [42mm]

### A2 · Características geométricas identificadas

| Nº | Característica | Descripción | Vista(s) que la definen | Dimensiones asociadas |
|---|---|---|---|---|
| 1 | [Plataforma] | [Base rectangular principal de la pieza ] | [Arriba,delante y derecha] | [X=0-60, Y=0-25 altura 12mm] |
| 2 | [Torre] | [Volumen elevado ubicado en la parte posterior izquierda ] | [Arriba,delante y derecha] | [X=0-25, Y=25-60, Z=42mm] |
| 3 | [Escalamiento] | [Cambios de altura entre la torre, plataforma y extremo derecho] | [Delantero derecho] | [z=42,z=24, y z=12mm] |
| 4 | [Ranura] | [Ranura rectangular ubicada en el extremo derecho] | [Parte superior y frontal] | [X=68-82, Y=10-22] |
| 5 | [Agujero pasarte] | [Perforación circular vertical] | [Arriba] | [014mm, centro(42,42)] |

### A3 · Describa la pieza en una frase técnica antes de abrir Fusion

[Cuerpo escalonado de tres niveles de altura con una torre y plataforma posterior-izquierda, complementado por una perforación cilíndrica pasante y una ranura rectangular  en la base derecha.]

### A4 · ¿Qué plano de boceto utilizará primero y por qué?

[Utilizaré el plano XZ (Frontal), ya que permite definir en un solo boceto el perfil escalonado principal de la pieza  y extensiones transversales, proyectando la extrusión inicial a lo largo del eje Y]

### A5 · Estrategia inicial de modelado

1. [Crear un boceto en el plano XZ dibando el perfil lateral principal en forma de escalonado triple.]
2. [Extruir el perfil en el eje Y a la profundidad total de 60mm]
3. [Realizar un boceto sobre la cara superior/posterior para recortar la sección sobrante del frente Y= 0 a 25 y dar forma a la torre y plataforma.]
4. [Crear un boceto sobre la cara de la plataforma intermedia en z=28mm para posicionar el círculo]
5. [Aplicar una operación Extrude Cut pasante hacia abajo para generar la perforación cilíndrica.]
6. [Crear un boceto sobre la cara superior de la base derecha proyectar el rectángulo xtruir el corte pasante ]

---

## B. Desarrollo del modelo

### B1 · Boceto base

- Plano seleccionado: [Frontal]
- Geometría principal: [Contorno cerrado escalonado con aristas horizontales y verticales.]
- Restricciones aplicadas: [Coincidencia con el origen, Horizontal]
- Estado del boceto: [Totalmente restringido]

### B2 · Operaciones principales realizadas

| Orden | Operación | Propósito geométrico | Parámetro/dimensión principal | Resultado |
|---|---|---|---|---|
| 1 | [Sketch 1 + Extrude] | [Generar el bloque maestro escalonado] | [Perfil XZ, Extrusión] | [Bloque sólido base] |
| 2 | [Sketch 2 + Extrude Cut] | [Retirar material frontal en la zona escalonada superior] | [Rectaángulo] | [Formación de torre y plataforma] |
| 3 | [Sketch 3 + Extrude Cut	] | [Crear perforación cilíndrica vertical] | [Círculo] | [Agujero pasante en plataforma] |
| 4 | [Sketch 4 + Extrude Cut] | [Crear la ranura rectangular en la base derecha] | [Rectángulo ] | [Ranura pasante en Z=12] |


### B3 · Cambios respecto a la estrategia inicial

| Cambio realizado | Motivo | Vista/dimensión que reveló el problema | Sketch/operación corregida |
|---|---|---|---|
| [Extrusión inicial uniforme vs. vaciado por la cara Top] | [La torre y plataforma solo abarcan desde Y=25 a Y=60, no todo Y=60] | [Se agregó un Extrude Cut secundario desde el plano XY en Y=0 a 25] | [Respu] |
| [Ajuste del orden de cortes] | [Respuesta] | [Respuesta] | [Respuesta] |
| [Ninguno adicional] | [Respue] | [Respuesta] | [Respuesta] |

---

## C. Verificación contra el plano

### C1 · Correspondencia de vistas

| Vista | ¿Coincide? | Evidencia geométrica | Diferencia detectada | Corrección realizada |
|---|---|---|---|---|
| Front | [Respuesta] | [Respuesta] | [Respuesta] | [Respuesta] |
| Top | [Respuesta] | [Respuesta] | [Respuesta] | [Respuesta] |
| Right | [Respuesta] | [Respuesta] | [Respuesta] | [Respuesta] |

### C2 · Comprobación dimensional

| Nº | Dimensión crítica | Valor del plano | Valor medido en Fusion | Elemento seleccionado | ¿Coincide? |
|---|---|---|---|---|---|
| 1 | [Respuesta] | [Respuesta] | [Respuesta] | [Respuesta] | [Respuesta] |
| 2 | [Respuesta] | [Respuesta] | [Respuesta] | [Respuesta] | [Respuesta] |
| 3 | [Respuesta] | [Respuesta] | [Respuesta] | [Respuesta] | [Respuesta] |
| 4 | [Respuesta] | [Respuesta] | [Respuesta] | [Respuesta] | [Respuesta] |
| 5 | [Respuesta] | [Respuesta] | [Respuesta] | [Respuesta] | [Respuesta] |

### C3 · Editabilidad paramétrica

Si una dimensión principal de la pieza cambiara, indique qué Sketch, dimensión u operación tendría que editar y por qué.

[Respuesta]

---

## D. Evidencias

### D1 · Modelo final

Modelo completo en orientación pictórica, con nombre del diseño y ViewCube visibles.

![Lab I-B: Modelo final](S09_LabIB_Modelo_Apellido_Nombre.png) 
 

### D2 · Vistas de verificación

Montaje de Front, Top y Right del modelo, presentado de manera clara para comparar con el plano base.

![Lab I-B: Vistas](S09_LabIB_Vistas_Apellido_Nombre.png)

### D3 · Boceto y restricciones

Captura del boceto más representativo con restricciones y dimensiones visibles.

![Lab I-B: Boceto](S09_LabIB_Boceto_Apellido_Nombre.png)

### D4 · Timeline / historial paramétrico

Captura donde se observen las operaciones principales del historial del modelo.

![Lab I-B: Timeline](S09_LabIB_Timeline_Apellido_Nombre.png)

### D5 · Verificación dimensional

Captura de `Inspect > Measure` con una dimensión crítica y el elemento seleccionado visibles.

![Lab I-B: Medicion](S09_LabIB_Medicion_Apellido_Nombre.png)

---

## E. Checklist de entrega

- [ ] Analicé el plano antes de comenzar el modelado.
- [ ] Registré X, Y y Z totales.
- [ ] Identifiqué las características principales y las vistas que las definen.
- [ ] Registré una estrategia inicial antes de modelar.
- [ ] El modelo final corresponde a Front, Top y Right.
- [ ] Verifiqué al menos cinco dimensiones críticas.
- [ ] Los bocetos principales tienen restricciones y dimensiones coherentes.
- [ ] El historial de operaciones es legible y editable.
- [ ] El nombre del archivo cumple la nomenclatura solicitada.
- [ ] El archivo editable está disponible en Fusion Cloud con acceso docente.
- [ ] Las cinco evidencias se visualizan correctamente en GitHub.
- [ ] Esta ficha está completa.

---

# F. Rúbrica oficial del Laboratorio integrador I-B

> Esta rúbrica reproduce los criterios y valores establecidos en el programa oficial. La persona docente puede anotar el puntaje obtenido y observaciones en las columnas finales.

| Criterio oficial | Valor máximo | Evidencia principal en esta ficha | Puntaje obtenido | Observaciones de evaluación |
|---|---:|---|---:|---|
| Interpretación correcta del plano o conjunto de vistas | 2,0 % | Secciones A1–A5 y C1 | [Evaluador] | [Evaluador] |
| Reconstrucción tridimensional coherente | 2,5 % | Secciones B1–B3, D1 y D2 | [Evaluador] | [Evaluador] |
| Aplicación de restricciones y dimensiones | 1,5 % | B1, D3 y C2 | [Evaluador] | [Evaluador] |
| Precisión geométrica y correspondencia con el plano | 2,0 % | C1, C2, D2 y D5 | [Evaluador] | [Evaluador] |
| Organización, nomenclatura y archivo editable | 1,0 % | Identificación, B2, D4 y checklist | [Evaluador] | [Evaluador] |
| Presentación y cumplimiento del enunciado | 1,0 % | Ficha completa, evidencias y checklist | [Evaluador] | [Evaluador] |
| **Total** | **10,0 %** |  | **[Evaluador]** | **[Evaluador]** |

## G. Resumen para evaluación asistida por ChatGPT

Este bloque debe permitir una revisión rápida sin tener que inferir información faltante.

- ¿El estudiante interpretó correctamente X, Y y Z? [Respuesta]
- ¿Las características listadas corresponden con el plano? [Respuesta]
- ¿La estrategia inicial es coherente? [Respuesta]
- ¿El modelo final coincide con las tres vistas? [Respuesta]
- ¿Las dimensiones críticas coinciden? [Respuesta]
- ¿Los bocetos muestran restricciones y dimensiones adecuadas? [Respuesta]
- ¿El timeline muestra una reconstrucción paramétrica razonable? [Respuesta]
- ¿El archivo y las evidencias cumplen nomenclatura y presentación? [Respuesta]
- Incidencias que el evaluador debería revisar directamente en Fusion: [Respuesta]

## H. Retroalimentación del evaluador

### Fortalezas

[Evaluador]

### Aspectos por corregir

[Evaluador]

### Calificación final

**[Evaluador] / 10,0 %**
