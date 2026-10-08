# ICT401 · Semana 11 — Registro de cortes, secciones, detalles y tolerancias

28 de septiembre al 3 de octubre de 2026.

- Estudiante: [Nohelia Loaisiga Sandoval]
- Grupo: [60]
- Carpeta o proyecto de Fusion Cloud con acceso docente: [Respuesta]
- Drawing o modelo de referencia de Semana 10: [Respuesta]
- Modelo utilizado: [Nombre del diseño]

## Instrucciones

Copie esta plantilla a `Portafolio/semana11/` y guárdela como `S11_Registro_Apellido_Nombre.md`. Sustituya `Apellido_Nombre` por un apellido y un nombre sin espacios ni tildes. Complete cada `[Respuesta]`, agregue las imágenes solicitadas en la misma carpeta y publique los cambios mediante un commit.

Conserve las decisiones iniciales y documente las correcciones. No borre una interpretación anterior: explique qué cambió, qué evidencia motivó el cambio y cómo verificó el resultado.

Trabaje sobre un modelo o plano desarrollado en Semana 10. Use milímetros, orientación coherente y una cámara ortográfica. La ficha es un registro de proceso: complete cada sección durante la lección, no al final de memoria.

**Entornos de Fusion:** `Design` es el espacio para abrir y revisar el modelo 3D; `Drawing` es el espacio para crear y editar el plano técnico. P1 se realiza en `Design`; P2 es un croquis de planificación y no crea todavía el plano definitivo; P3, P4 y P5 se realizan principalmente en `Drawing`. Solo se regresa a `Design` para verificar que el plano corresponda con el modelo.

**Continuidad con Semana 10:** reutilice el `Drawing` de Semana 10 con sus vistas `Front`, `Top` y `Right`. Semana 11 no consiste en generar nuevamente las tres vistas desde cero, sino en agregar y verificar el corte o la sección, el rayado, el detalle ampliado y la tolerancia introductoria cuando corresponda. Si el `Drawing` de Semana 10 está incompleto o contiene errores, corríjalo como requisito previo y registre la corrección; no convierta la generación de vistas en la actividad central de esta semana.

## P1 — ¿Cuándo conviene cortar?

**Propósito:** decidir si un corte o una sección comunica mejor una característica interior que una vista ordinaria con líneas ocultas.

**Entorno:** Fusion, espacio `Design`. No se crea ni se modifica todavía el `Drawing`.

### P1.0 · Pasos en Fusion

1. Abra en Fusion el diseño de Semana 10 y permanezca en el espacio `Design`.
2. Seleccione el componente o cuerpo que documentará. No cambie dimensiones ni operaciones.
3. Use el ViewCube para observar `Front`, `Top` y `Right`.
4. Para observar el interior, use `Inspect > Section Analysis` sobre una cara o plano adecuado. Esta sección de análisis sirve para decidir y no es todavía una vista de `Drawing`.
5. Tome `S11_P1_Modelo_Apellido_Nombre.png` con modelo 3D, nombre del diseño y ViewCube visibles.
6. Prepare `S11_P1_Comparacion_Apellido_Nombre.png` como una sola lámina con tres recortes del espacio `Design`: vista ordinaria, vista con líneas ocultas y resultado de `Inspect > Section Analysis`.
7. Agregue las etiquetas `ordinaria`, `ocultas` y `sección` con un editor de imágenes, o escríbalas sobre una impresión y fotografíela. No use `Drawing` en P1.

### P1.1 · Modelo utilizado

- Nombre del diseño en Fusion: [ICT401_S09_P2_Apellido_Nombre]
- Pieza de referencia y semana de origen: [Respuesta]
- Características interiores observadas: [Respuesta]

### P1.2 · Análisis de vistas

| Característica | Vista donde aparece | ¿Se comunica claramente? | Problema detectado |
|---|---|---|---|
| 1 | [Agujero Ø14 mm Top] | [Parcialmente] | [Se identifica su posición, pero una vista convencional no permite comunicar completamente su profundidad y recorrido interior.] |
| 2 | [Plataforma superior	Front / Right] | [Sí] | [El contorno exterior se reconoce, aunque su relación con el agujero puede resultar menos clara sin una sección.] |
| 3 | [Torre superior	Front / Right] | [Sí	] | [Su altura y contorno son visibles mediante las vistas principales.] |
| 4 | [Ranura 14 × 12 mm	Top / Front] | [Parcialmente] | [Puede requerir líneas ocultas para comunicar completamente su geometría.] |

### P1.3 · Comparación de alternativas

| Alternativa | Ventaja | Limitación |
|---|---|---|
| Vista ordinaria | [Permite observar el contorno exterior de la pieza.] | [Algunas características interiores no se comunican completamente.
] |
| Vista con líneas ocultas | [Permite representar elementos interiores sin modificar la vista.] | [Puede acumular líneas y dificultar la interpretación de la geometría] |
| Vista seccionada | [Expone la geometría interior y reduce la necesidad de líneas ocultas.] | [Requiere definir correctamente el plano y la dirección de observación.] |

### P1.4 · Decisión de representación

- Tipo de representación elegido: [Sección completa]
- Vista desde la que se realizará: [Top]
- Posición aproximada del plano de corte: [Plano vertical que atraviesa el centro del agujero Ø14 mm, aproximadamente por Y = 42 mm
]
- Justificación técnica: [La sección permite atravesar el agujero Ø14 mm y mostrar su recorrido interior, además de comunicar con mayor claridad la relación entre el agujero, la plataforma y las superficies interiores. De esta forma se reduce la dependencia de líneas ocultas para interpretar la geometría.]

### Evidencias P1

**Qué debe contener cada imagen:**

- `S11_P1_Modelo_Apellido_Nombre.png`: captura de Fusion en el espacio `Design`, con el modelo 3D utilizado, nombre del diseño, ViewCube y característica interior que se analizará.
- `S11_P1_Comparacion_Apellido_Nombre.png`: comparación entre una vista ordinaria, la alternativa con líneas ocultas y la propuesta de sección. Debe mostrar qué información queda oculta y por qué la sección sería más clara.

Una captura aislada del modelo no demuestra la comparación solicitada.

P1 no requiere crear un `Drawing`; la decisión se registra antes de pasar a la documentación técnica.

![P1: Modelo](S11_P1_Modelo_Loaisiga_Nohelia.png)<img width="1353" height="712" alt="S11_P1_Modelo_Loaisiga_Nohelia.png" src="https://github.com/user-attachments/assets/ef24410b-d80f-4fd1-98c3-2da55e7340c7" />


![P1: Comparación](S11_P1_Comparacion_Loaisiga_Nohelia.png)<img width="1340" height="720" alt="S11_P1_Comparacion_Loaisiga_Nohelia.png" src="https://github.com/user-attachments/assets/e0219fbc-439f-4fd0-bd5d-873aa5842047" />


## P2 — Plano de corte y sección

**Propósito:** planificar el plano de corte, la dirección de observación, la identificación y el rayado antes de aplicarlos en Fusion. P2 es un croquis de planificación; todavía no se edita el `Drawing` definitivo.

**Entorno:** se consulta el modelo en Fusion, espacio `Design`, pero el resultado de P2 es un croquis o esquema de trabajo. La sección definitiva se creará en P3, en `Drawing`.

### P2.0 · Pasos de planificación

1. En Fusion, espacio `Design`, abra el mismo modelo utilizado en P1 y confirme la característica que debe atravesar el corte.
2. Confirme qué característica debe atravesar el corte. No active todavía `Section View`.
3. Sobre una copia de la vista, una impresión o una hoja, dibuje la línea del plano de corte.
4. Coloque las flechas en la dirección de observación y repita la identificación, por ejemplo `A-A`.
5. Dibuje la sección esquemática, rayando únicamente las superficies atravesadas y dejando vacías las cavidades.
6. Guarde `S11_P2_CroquisCorte_Apellido_Nombre.png` como fotografía/escaneo del croquis o como captura de `Design` anotada.
7. Guarde `S11_P2_Seccion_Apellido_Nombre.png` como la sección esquemática rayada. No presente todavía una captura del `Drawing` como evidencia P2.

### P2.1 · Elementos del corte

| Elemento | Decisión aplicada |
|---|---|
| Vista donde se indica el corte | [Top] |
| Posición del plano de corte | [Plano vertical que atraviesa el centro del agujero Ø14 mm, aproximadamente por Y = 42 mm] |
| Dirección de observación | [Perpendicular al plano de corte, hacia la zona que contiene el agujero y la plataforma] |
| Identificación | [A-A] |
| Tipo de corte o sección | [Sección completa] |

### P2.2 · Rayado

- ¿Qué superficies quedan cortadas?: [Las superficies sólidas que son atravesadas directamente por el plano de corte.]
- ¿Qué superficies no deben rayarse?: [Las cavidades y espacios vacíos, incluyendo el interior del agujero Ø14 mm.]
- ¿Cómo diferenció zonas o componentes adyacentes?: [Mediante la separación y dirección uniforme del rayado, manteniendo claramente diferenciadas las superficies cortadas de los espacios vacíos.]
- ¿Qué separación utilizó entre las líneas de rayado?: [Separación uniforme y suficiente para que las líneas puedan distinguirse sin saturar la sección.]
- ¿Cómo evitó que el rayado invadiera textos o cotas?: [El rayado se mantuvo dentro de las superficies cortadas y se respetaron las zonas ocupadas por identificaciones y cotas.]

### P2.3 · Diferencia conceptual

Explique con sus palabras la diferencia entre un corte y una sección.

[Un corte representa la pieza como si una parte hubiera sido retirada mediante un plano de corte, permitiendo observar las características interiores que quedan expuestas. Una sección representa principalmente la forma que resulta de la intersección de la pieza con el plano de corte. En ambos casos, el rayado permite identificar las superficies del material que fueron atravesadas.]

### P2.4 · Correcciones

| Problema detectado | Corrección aplicada | Motivo de la corrección |
|---|---|---|
| [La posición inicial del plano debía atravesar directamente la característica interior principal] | [Se centró el plano de corte respecto al agujero Ø14 mm.] | [Para que la sección comunicara claramente el interior de la pieza.] |
| [Era necesario distinguir la dirección del corte de la dirección de observación] | [Se añadieron flechas y la identificación A-A.] | [Para evitar interpretar incorrectamente la sección resultante.] |

### Evidencias P2

**Qué debe contener cada imagen:**

- `S11_P2_CroquisCorte_Apellido_Nombre.png`: croquis de planificación basado en el modelo consultado en `Design`, con vista de origen, línea del plano de corte, flechas de observación y letras de identificación.
- `S11_P2_Seccion_Apellido_Nombre.png`: sección resultante identificada, superficies rayadas, cavidades sin rayado y zonas adyacentes diferenciadas cuando corresponda.

Un dibujo sin flechas, letras o rayado no demuestra el procedimiento completo.

Estas evidencias no tienen que ser capturas del espacio `Drawing`; el `Drawing` se trabaja en P3.

![P2: Croquis del corte](S11_P2_CroquisCorte_Loaisiga_Nohelia.png)<img width="690" height="369" alt="S11_P2_CroquisCorte_Loaisiga_Nohelia.png" src="https://github.com/user-attachments/assets/d7858b13-a265-4593-ba82-a661bcc9a625" />


![P2: Sección identificada](S11_P2_Seccion_Loaisiga_Nohelia.png)<img width="867" height="622" alt="S11_P2_Seccion_Loaisiga_Nohelia.png" src="https://github.com/user-attachments/assets/537c702c-e0ea-4074-93c6-0e4020eb2c33" />


## P3 — Corte o sección en Fusion

**Propósito:** integrar el corte o la sección al Drawing de Semana 10 y comprobar su correspondencia con el modelo.

**Entorno:** Fusion, espacio `Drawing`. Aquí se crea la `Section View` o vista de sección definitiva. Se cambia a `Design` únicamente para verificar la correspondencia con el modelo 3D.

### P3.0 · Pasos en Fusion

1. Abra el archivo de `Drawing` de Semana 10 y confirme que conserva las vistas `Front`, `Top` y `Right` generadas en Semana 10. La tarea de Semana 11 no es volver a generarlas. Si no existe un `Drawing`, desde el diseño use `File > New Drawing > From Design` como recuperación del requisito de Semana 10.
2. En `Drawing`, seleccione la vista que debe generar la sección.
3. Ejecute la herramienta `Section View` desde la barra de creación del `Drawing`.
4. Dibuje la línea de corte siguiendo el croquis P2 y confirme la dirección de observación.
5. Coloque la vista resultante, conserve la identificación y revise el rayado generado por Fusion.
6. Edite la vista para corregir escala, separación, identificación o visibilidad de líneas. No dibuje rayado manual sobre el plano.
7. Cambie a `Design`, compare la sección con la cavidad real y tome la captura de verificación.
8. Regrese a `Drawing`, aplique correcciones y tome la captura del plano.

### P3.1 · Configuración

- Drawing utilizado: [ICT401_S10_P2_Loaisiga_Nohelia]
- Espacio de trabajo utilizado: `Drawing`
- Herramienta utilizada: `Section View`
- Vista de origen: [Top]
- Tipo de corte: [Sección completa]
- Escala: [ La misma escala utilizada en el Drawing de Semana 10]
- Identificación: [A-A]
- Dirección de observación: [ Perpendicular al plano de corte, hacia el interior de la pieza]

### P3.2 · Verificación con el modelo

| Elemento | ¿Coincide con el modelo? | Evidencia o corrección |
|---|---|---|
| Cavidad o agujero | [Sí] | [El agujero Ø14 mm aparece atravesado por el plano de corte y coincide con el modelo 3D.] |
| Ranura o escalón | [Sí] | [La geometría exterior e interior mantiene correspondencia con el modelo.] |
| Contorno exterior | [Sí] | [El contorno de la pieza coincide con el modelo de Semana 10.] |
| Superficies rayadas | [Sí] | [El rayado se aplica sobre las superficies sólidas atravesadas por el corte y no sobre las cavidades.] |
| Líneas visibles | [Sí] | [Se conservaron las líneas necesarias para interpretar correctamente la geometría.] |

### P3.3 · Líneas ocultas

- ¿Qué líneas ocultas dejaron de ser necesarias?: [Las correspondientes a la geometría interior que ahora queda expuesta mediante la sección.]
- ¿Qué líneas visibles debieron conservarse?: [Las necesarias para definir el contorno exterior, escalones y demás características visibles de la pieza.]
- ¿Detectó alguna contradicción entre vistas?: [No se detectaron contradicciones importantes entre la sección y las vistas principales.]
- ¿Cómo verificó la dirección de observación?: [Se comparó la dirección indicada por las flechas del plano de corte con la geometría observada en Design mediante la sección de análisis.]

### P3.4 · Errores y correcciones

| Error detectado | Evidencia que lo reveló | Corrección aplicada |
|---|---|---|
| [Era necesario comprobar que la sección atravesara realmente el agujero.] | [Comparación entre Drawing y modelo 3D en Design.] | [Se verificó la ubicación del plano de corte respecto al centro del agujero Ø14 mm.] |
| [Algunas líneas interiores podían resultar redundantes después de crear la sección.] | [Revisión de legibilidad del Drawing] | [Se eliminaron o ajustaron las líneas ocultas que dejaron de aportar información necesaria.] |

### Evidencias P3

**Qué debe contener cada imagen:**

- `S11_P3_PlanoSeccion_Apellido_Nombre.png`: captura de Fusion en el espacio `Drawing`, con las vistas de Semana 10, corte o sección incorporado, identificación, rayado y cotas legibles.
- `S11_P3_ModeloVerificacion_Apellido_Nombre.png`: captura del mismo modelo en el espacio `Design`, orientado para comprobar la cavidad, agujero, ranura o escalón representado.

La segunda imagen debe permitir comparar modelo y plano, no solo mostrar una pantalla genérica de Fusion.

![P3: Plano con sección](S11_P3_PlanoSeccion_Apellido_Nombre.png)<img width="1237" height="642" alt="image" src="https://github.com/user-attachments/assets/1f75bc10-b192-4e06-b728-6fbb6e9d04fb" />


![P3: Verificación con modelo](S11_P3_ModeloVerificacion_Apellido_Nombre.png)

## P4 — Detalle ampliado y tolerancia introductoria

**Propósito:** ampliar una zona que no se lee con claridad e interpretar una tolerancia dimensional sencilla, únicamente cuando exista una justificación.

**Entorno:** Fusion, espacio `Drawing`. El detalle y la tolerancia se agregan al plano; no se modifica la geometría del modelo en `Design`.

### P4.0 · Pasos en Fusion

1. Abra el `Drawing` de P3 y permanezca en ese espacio de trabajo.
2. Seleccione la vista que contiene la característica difícil de leer.
3. Ejecute `Detail View`, encierre la zona y coloque la vista ampliada.
4. Asigne la letra de referencia y establezca la escala del detalle.
5. Agregue o edite la dimensión en el `Drawing`.
6. Configure una tolerancia únicamente si existe una razón funcional o una indicación explícita del ejercicio.
7. Si aplica una tolerancia, abra las propiedades de la dimensión, active la presentación disponible y registre valor nominal, límite superior e inferior.
8. Si no aplica una tolerancia, conserve la dimensión nominal y escriba la justificación.
9. Tome las tres capturas desde `Drawing`: zona de origen, detalle ampliado y dimensión/tolerancia.

### P4.1 · Detalle ampliado

- Zona seleccionada: [Agujero Ø14 mm y zona de la plataforma que lo rodea.]
- Motivo de la ampliación: [Facilitar la lectura del agujero y su relación con las superficies cercanas.]
- Letra asignada: [B]
- Escala del detalle: [2:1]
- Vista de origen: [Top]
- Herramienta utilizada en `Drawing`: `Detail View`
- Espacio de trabajo utilizado: `Drawing`

### P4.2 · Tolerancia introductoria

- Dimensión nominal: [Ø14 mm]
- Tolerancia aplicada: [No se agregó una tolerancia específica al modelo.]
- Límite superior: [No aplica.]
- Límite inferior: [No aplica.]
- Motivo funcional o indicación del enunciado: [El ejercicio no proporciona una función de fabricación ni una tolerancia específica para el agujero. Por esta razón se conserva la dimensión nominal y no se inventan requisitos de fabricación.]

**Criterio de cálculo:** en la fórmula `D_min = D_N - T_inf`, `T_inf` se registra como magnitud positiva de la desviación inferior. Si la desviación se escribe con signo, por ejemplo `-0,10 mm`, el límite se calcula como `D_N + (-0,10 mm)`.

### P4.3 · Interpretación

Interprete el ejemplo didáctico `20 ± 0,1 mm`.

- Valor nominal: [20,0 mm]
- Valor máximo permitido: [20,1 mm]
- Valor mínimo permitido: [19,9 mm]

### P4.4 · Decisión técnica

¿La tolerancia era necesaria para este plano? Justifique sin inventar requisitos de fabricación.

[La tolerancia no era necesaria para este plano porque el ejercicio no proporciona una función específica que requiera establecer límites dimensionales para la pieza. Agregar una tolerancia sin una justificación técnica introduciría un requisito de fabricación que no está definido en el enunciado. Por ello, se conserva la dimensión nominal.
]

### Evidencias P4

**Qué debe contener cada imagen:**

- `S11_P4_ZonaDetalle_Apellido_Nombre.png`: captura del `Drawing` con la zona de origen encerrada o señalada con una letra.
- `S11_P4_Detalle_Apellido_Nombre.png`: detalle creado en el `Drawing`, con letra de referencia y escala.
- `S11_P4_Tolerancia_Apellido_Nombre.png`: dimensión nominal y tolerancia aplicada en el `Drawing`, o anotación que explique por qué se mantuvo solo la dimensión nominal.

No basta con escribir una tolerancia sin justificarla.

![P4: Zona de detalle](S11_P4_ZonaDetalle_Apellido_Nombre.png)

![P4: Detalle ampliado](S11_P4_Detalle_Apellido_Nombre.png)

![P4: Tolerancia](S11_P4_Tolerancia_Apellido_Nombre.png)

## P5 — Plano final y verificación

**Propósito:** revisar el plano completo mediante la rúbrica y preparar la Prueba Corta 2.

**Entorno:** la revisión y las correcciones se realizan principalmente en Fusion, espacio `Drawing`. Se cambia a `Design` para comparar el plano final con el modelo 3D y luego se vuelve a `Drawing` para corregir o guardar.

### P5.0 · Pasos en Fusion

1. En `Drawing`, abra la versión que conserva las vistas `Front`, `Top` y `Right`, además del corte o la sección de P3 y el detalle de P4.
2. Compruebe vistas, identificación, dirección de observación, rayado, líneas ocultas, cotas, detalle y tolerancia.
3. Cambie a `Design` y compare cada característica interior con el modelo 3D.
4. Regrese a `Drawing`, corrija el plano y guarde la versión final en Fusion Cloud.
5. Tome `S11_P5_PlanoFinal_Apellido_Nombre.png` mostrando el `Drawing` completo, el nombre del diseño y la información legible.
6. Prepare `S11_P5_Verificacion_Apellido_Nombre.png` como una sola imagen con un recorte del plano final y otro del modelo verificado, etiquetados `Drawing` y `Design`.
7. Complete el checklist y registre qué cambió, qué evidencia motivó el cambio y cómo verificó el resultado.

### P5.1 · Lista de comprobación

- [ ] El corte atraviesa la característica relevante.
- [ ] La dirección de observación es correcta.
- [ ] Las letras y flechas son coherentes.
- [ ] El rayado representa únicamente superficies cortadas.
- [ ] Las áreas adyacentes se diferencian.
- [ ] Se eliminaron líneas ocultas innecesarias.
- [ ] Las cotas siguen siendo legibles.
- [ ] El detalle tiene letra y escala.
- [ ] La tolerancia está justificada o se documentó por qué no se agregó.
- [ ] El plano coincide con el modelo 3D.
- [ ] No hay superposiciones ni información redundante.

### P5.2 · Revisión por pares

| Criterio revisado | Observación recibida | Corrección realizada |
|---|---|---|
| Corte o sección | [Se debe comprobar que el corte atraviese la característica interior principal.] | [Se verificó el plano de corte respecto al agujero Ø14 mm.] |
| Rayado | [El rayado debe representar únicamente las superficies atravesadas.] | [Se revisó el rayado y se mantuvieron libres las cavidades.] |
| Detalle | [La zona ampliada debe tener identificación y escala.] | [Se identificó el detalle como B y se indicó la escala 2:1.] |
| Tolerancia | [No se debe agregar una tolerancia sin justificación.] | [Se mantuvo la dimensión nominal de Ø14 mm.] |
| Legibilidad | [Las vistas, cotas y anotaciones deben poder interpretarse sin superposiciones.] | [Se revisó la distribución del Drawing y se ajustaron los elementos necesarios.] |

### P5.3 · Preparación para la Prueba Corta 2

- Una situación en la que conviene una sección: [Respuesta]
- Diferencia entre corte y sección: [Respuesta]
- Función del rayado: [Respuesta]
- Función de las flechas del plano de corte: [Respuesta]
- Significado de una tolerancia bilateral: [Respuesta]

### Evidencias P5

**Qué debe contener cada imagen:**

- `S11_P5_PlanoFinal_Apellido_Nombre.png`: captura final de Fusion en el espacio `Drawing`, con vistas, corte o sección, rayado, cotas, detalle y tolerancia cuando corresponda, sin superposiciones importantes.
- `S11_P5_Verificacion_Apellido_Nombre.png`: comparación final entre el plano en `Drawing` y el modelo 3D en `Design`, con una orientación que permita comprobar la geometría representada.

Estas imágenes deben respaldar el checklist y las correcciones registradas en la ficha.

![P5: Plano final](S11_P5_PlanoFinal_Apellido_Nombre.png)

![P5: Verificación final](S11_P5_Verificacion_Apellido_Nombre.png)

## Reflexión final

### 1. ¿Por qué fue necesario utilizar un corte o una sección?

[Respuesta]

### 2. ¿Qué diferencia existe entre corte y sección?

[Respuesta]

### 3. ¿Qué característica fue más difícil de representar?

[Respuesta]

### 4. ¿Qué corrección mejoró más la legibilidad del plano?

[Respuesta]

### 5. ¿Qué aprendí sobre tolerancias introductorias?

[Respuesta]

## Referencia de Fusion

Para los comandos del software consulte la documentación oficial vigente de Autodesk Fusion sobre los espacios `Design` y `Drawing`, `Inspect > Section Analysis`, `Section View`, `Detail View` y edición de dimensiones: <https://help.autodesk.com/view/fusion360/ENU/>.

## Cierre de la ficha

- [ ] Completé las respuestas de P1 a P5.
- [ ] Incorporé las evidencias con la nomenclatura solicitada.
- [ ] Las imágenes se visualizan correctamente desde GitHub.
- [ ] El modelo y el Drawing están disponibles en Fusion Cloud con acceso docente.
- [ ] Documenté las correcciones sin borrar decisiones iniciales.
- [ ] Publiqué los últimos cambios en GitHub.

Commit sugerido: `S11 ejercicios cortes secciones Apellido Nombre`.

Corrección posterior: `S11 correccion plano seccion Apellido Nombre`.
