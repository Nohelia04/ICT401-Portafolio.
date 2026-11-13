
# ICT401 · Semana 11 — Registro de cortes, secciones, detalles y tolerancias

28 de septiembre al 3 de octubre de 2026.

* Estudiante: [Nohelia Loaisiga Sandoval]
* Grupo: [60]
* Carpeta o proyecto de Fusion Cloud con acceso docente: [Nohelia Loaisiga]
* Drawing o modelo de referencia de Semana 10: `ICT401_S09_P2_Apellido_Nombre`
* Modelo utilizado: `ICT401_S09_P2_Apellido_Nombre`

## Instrucciones

Se trabajó sobre el modelo y el Drawing desarrollado durante Semana 10, manteniendo las vistas principales `Front`, `Top` y `Right`. El objetivo de esta semana fue comunicar mejor la geometría interior mediante un corte o sección, incorporar un detalle ampliado y revisar la aplicación de tolerancias introductorias.

El modelo se mantuvo sin modificaciones en su geometría durante la elaboración del plano. Las verificaciones se realizaron comparando el `Drawing` con el modelo 3D en el espacio `Design`.

## P1 — ¿Cuándo conviene cortar?

**Propósito:** decidir si un corte o una sección comunica mejor una característica interior que una vista ordinaria con líneas ocultas.

**Entorno:** Fusion, espacio `Design`.

### P1.0 · Pasos en Fusion

Se abrió el modelo correspondiente a Semana 10 en el espacio `Design` y se revisaron las vistas `Front`, `Top` y `Right`. Se utilizó `Inspect > Section Analysis` para observar las características interiores y determinar qué información podía quedar oculta mediante una representación convencional.

No se modificaron las dimensiones ni las operaciones del modelo.

### P1.1 · Modelo utilizado

* Nombre del diseño en Fusion: `ICT401_S09_P2_Apellido_Nombre`
* Pieza de referencia y semana de origen: Pieza desarrollada en Semana 10.
* Características interiores observadas: agujero pasante de Ø14 mm, escalones formados por la plataforma y la torre, y la ranura de 14 × 12 mm ubicada en la base.

### P1.2 · Análisis de vistas

| Característica      | Vista donde aparece | ¿Se comunica claramente? | Problema detectado                                                                                                             |
| ------------------- | ------------------- | ------------------------ | ------------------------------------------------------------------------------------------------------------------------------ |
| Agujero Ø14 mm      | Top                 | Parcialmente             | Se identifica su posición, pero una vista convencional no permite comunicar completamente su profundidad y recorrido interior. |
| Plataforma superior | Front / Right       | Sí                       | El contorno exterior se reconoce, aunque su relación con el agujero puede resultar menos clara sin una sección.                |
| Torre superior      | Front / Right       | Sí                       | Su altura y contorno son visibles mediante las vistas principales.                                                             |
| Ranura 14 × 12 mm   | Top / Front         | Parcialmente             | Puede requerir líneas ocultas para comunicar completamente su geometría.                                                       |

### P1.3 · Comparación de alternativas

| Alternativa              | Ventaja                                                                            | Limitación                                                             |
| ------------------------ | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------- |
| Vista ordinaria          | Permite observar el contorno exterior de la pieza.                                 | Algunas características interiores no se comunican completamente.      |
| Vista con líneas ocultas | Permite representar elementos interiores sin modificar la vista.                   | Puede acumular líneas y dificultar la interpretación de la geometría.  |
| Vista seccionada         | Expone la geometría interior y reduce la necesidad de líneas ocultas.              | Requiere definir correctamente el plano y la dirección de observación. |

### P1.4 · Decisión de representación

* Tipo de representación elegido: **Sección completa**
* Vista desde la que se realizará: **Top**
* Posición aproximada del plano de corte: **Plano vertical que atraviesa el centro del agujero Ø14 mm, aproximadamente por Y = 42 mm**
* Justificación técnica: **La sección permite atravesar el agujero Ø14 mm y mostrar su recorrido interior, además de comunicar con mayor claridad la relación entre el agujero, la plataforma y las superficies interiores. De esta forma se reduce la dependencia de líneas ocultas para interpretar la geometría.**

### Evidencias P1

![P1: Modelo](S11_P1_Modelo_Loaisiga_Nohelia.png) <img width="841" height="365" alt="S11_P1_Modelo_Loaisiga_Nohelia" src="https://github.com/user-attachments/assets/5849460d-93a6-4e48-9807-fa64029d8504" />)

![P1: Comparación](S11_P1_Comparacion_Loaisiga_Nohelia.png) <img width="1175" height="536" alt="S11_P1_Comparacion_Loaisiga_Nohelia.png" src="https://github.com/user-attachments/assets/276e2625-8eae-499d-93d2-529a1d1ea657" />)

---

## P2 — Plano de corte y sección

**Propósito:** planificar el plano de corte, la dirección de observación, la identificación y el rayado antes de aplicarlos en Fusion.

**Entorno:** Fusion, espacio `Design`. El resultado de P2 corresponde a un croquis de planificación.

### P2.0 · Pasos de planificación

Se utilizó el mismo modelo de Semana 10 para determinar la ubicación del plano de corte. Se seleccionó una línea de corte que atraviesa el centro del agujero Ø14 mm.

La dirección de observación se indicó mediante flechas perpendiculares al plano de corte y se utilizó la identificación `A-A`. La sección esquemática representa rayadas únicamente las superficies atravesadas por el plano, dejando sin rayado las cavidades vacías.

### P2.1 · Elementos del corte

| Elemento                       | Decisión aplicada                                                                        |
| ------------------------------ | ---------------------------------------------------------------------------------------- |
| Vista donde se indica el corte | Top                                                                                      |
| Posición del plano de corte    | Plano vertical que atraviesa el centro del agujero Ø14 mm, aproximadamente por Y = 42 mm |
| Dirección de observación       | Perpendicular al plano de corte, hacia la zona que contiene el agujero y la plataforma   |
| Identificación                 | A-A                                                                                      |
| Tipo de corte o sección        | Sección completa                                                                         |

### P2.2 · Rayado

* ¿Qué superficies quedan cortadas?: **Las superficies sólidas que son atravesadas directamente por el plano de corte.**
* ¿Qué superficies no deben rayarse?: **Las cavidades y espacios vacíos, incluyendo el interior del agujero Ø14 mm.**
* ¿Cómo diferenció zonas o componentes adyacentes?: **Mediante la separación y dirección uniforme del rayado, manteniendo claramente diferenciadas las superficies cortadas de los espacios vacíos.**
* ¿Qué separación utilizó entre las líneas de rayado?: **Separación uniforme y suficiente para que las líneas puedan distinguirse sin saturar la sección.**
* ¿Cómo evitó que el rayado invadiera textos o cotas?: **El rayado se mantuvo dentro de las superficies cortadas y se respetaron las zonas ocupadas por identificaciones y cotas.**

### P2.3 · Diferencia conceptual

Un **corte** representa la pieza como si una parte hubiera sido retirada mediante un plano de corte, permitiendo observar las características interiores que quedan expuestas. Una **sección** representa principalmente la forma que resulta de la intersección de la pieza con el plano de corte. En ambos casos, el rayado permite identificar las superficies del material que fueron atravesadas.

### P2.4 · Correcciones

| Problema detectado                                                                               | Corrección aplicada                                     | Motivo de la corrección                                            |
| ------------------------------------------------------------------------------------------------ | ------------------------------------------------------- | ------------------------------------------------------------------ |
| La posición inicial del plano debía atravesar directamente la característica interior principal. | Se centró el plano de corte respecto al agujero Ø14 mm. | Para que la sección comunicara claramente el interior de la pieza. |
| Era necesario distinguir la dirección del corte de la dirección de observación.                  | Se añadieron flechas y la identificación A-A.           | Para evitar interpretar incorrectamente la sección resultante.     |

### Evidencias P2

![P2: Croquis del corte](S11_P2_CroquisCorte_Loaisiga_Nohelia.png) <img width="915" height="546" alt="S11_P2_CroquisCorte_Loaisiga_Nohelia.png" src="https://github.com/user-attachments/assets/6ea42543-6fa3-4ff5-9980-162ae23baca7" />


)

![P2: Sección identificada](S11_P2_Seccion_Loaisiga_Nohelia.png) <img width="959" height="637" alt="S11_P2_Seccion_Loaisiga_Nohelia.png" src="https://github.com/user-attachments/assets/a8e871eb-efed-43f7-b3b1-a24c042ac6c8" />)

---

## P3 — Corte o sección en Fusion

**Propósito:** integrar el corte o la sección al Drawing de Semana 10 y comprobar su correspondencia con el modelo.

**Entorno:** Fusion, espacio `Drawing`.

### P3.0 · Pasos en Fusion

Se abrió el Drawing de Semana 10 y se conservaron las vistas `Front`, `Top` y `Right`. A partir del croquis realizado en P2 se seleccionó la vista correspondiente y se utilizó la herramienta `Section View`.

La línea de corte se ubicó siguiendo la planificación realizada en P2 y se confirmó la dirección de observación. Posteriormente se revisaron la identificación, el rayado, la escala y las líneas visibles y ocultas.

Finalmente, se cambió al espacio `Design` para comparar la sección con la geometría real del modelo y comprobar que el agujero y las demás características coincidieran con el modelo 3D.

### P3.1 · Configuración

* Drawing utilizado: ICT401`Nohelia Loaisiga`
* Espacio de trabajo utilizado: `Drawing`
* Herramienta utilizada: `Section View`
* Vista de origen: `Top`
* Tipo de corte: `Sección completa`
* Escala: **La misma escala utilizada en el Drawing de Semana 10**
* Identificación: `A-A`
* Dirección de observación: **Perpendicular al plano de corte, hacia el interior de la pieza**

### P3.2 · Verificación con el modelo

| Elemento            | ¿Coincide con el modelo? | Evidencia o corrección                                                                               |
| ------------------- | ------------------------ | ---------------------------------------------------------------------------------------------------- |
| Cavidad o agujero   | Sí                       | El agujero Ø14 mm aparece atravesado por el plano de corte y coincide con el modelo 3D.              |
| Ranura o escalón    | Sí                       | La geometría exterior e interior mantiene correspondencia con el modelo.                             |
| Contorno exterior   | Sí                       | El contorno de la pieza coincide con el modelo de Semana 10.                                         |
| Superficies rayadas | Sí                       | El rayado se aplica sobre las superficies sólidas atravesadas por el corte y no sobre las cavidades. |
| Líneas visibles     | Sí                       | Se conservaron las líneas necesarias para interpretar correctamente la geometría.                    |

### P3.3 · Líneas ocultas

* ¿Qué líneas ocultas dejaron de ser necesarias?: **Las correspondientes a la geometría interior que ahora queda expuesta mediante la sección.**
* ¿Qué líneas visibles debieron conservarse?: **Las necesarias para definir el contorno exterior, escalones y demás características visibles de la pieza.**
* ¿Detectó alguna contradicción entre vistas?: **No se detectaron contradicciones importantes entre la sección y las vistas principales.**
* ¿Cómo verificó la dirección de observación?: **Se comparó la dirección indicada por las flechas del plano de corte con la geometría observada en `Design` mediante la sección de análisis.**

### P3.4 · Errores y correcciones

| Error detectado                                                                    | Evidencia que lo reveló                              | Corrección aplicada                                                                        |
| ---------------------------------------------------------------------------------- | ---------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| Era necesario comprobar que la sección atravesara realmente el agujero.            | Comparación entre `Drawing` y modelo 3D en `Design`. | Se verificó la ubicación del plano de corte respecto al centro del agujero Ø14 mm.         |
| Algunas líneas interiores podían resultar redundantes después de crear la sección. | Revisión de legibilidad del Drawing.                 | Se eliminaron o ajustaron las líneas ocultas que dejaron de aportar información necesaria. |

### Evidencias P3

![P3: Plano con sección](S11_P3_PlanoSeccion_Loaisiga_Nohelia.png)<img width="1080" height="763" alt="S11_P3_PlanoSeccion_Loaisiga_Nohelia.png" src="https://github.com/user-attachments/assets/96adfe32-55c8-4587-9ffa-0eaa706f710c" />)

![P3: Verificación con modelo](S11_P3_ModeloVerificacion_Loaisiga_Nohelia.png) <img width="1895" height="936" alt="S11_P3_ModeloVerificacion_Loaisiga_Nohelia.png" src="https://github.com/user-attachments/assets/0b04ca99-a741-4d72-aebd-3f473d867d32" />)

---

## P4 — Detalle ampliado y tolerancia introductoria

**Propósito:** ampliar una zona que no se lee con claridad e interpretar una tolerancia dimensional sencilla únicamente cuando existe una justificación.

**Entorno:** Fusion, espacio `Drawing`.

### P4.0 · Pasos en Fusion

Se trabajó sobre el Drawing resultante de P3. Se seleccionó como zona de interés el área correspondiente al agujero Ø14 mm, debido a que es una característica relevante para la interpretación de la pieza.

Se utilizó `Detail View` para ampliar la zona y facilitar la lectura de la característica. Se asignó la letra `B` al detalle y se estableció una escala mayor que la vista de origen.

No se modificó la geometría del modelo en `Design`.

### P4.1 · Detalle ampliado

* Zona seleccionada: **Agujero Ø14 mm y zona de la plataforma que lo rodea.**
* Motivo de la ampliación: **Facilitar la lectura del agujero y su relación con las superficies cercanas.**
* Letra asignada: `B`
* Escala del detalle: **2:1**
* Vista de origen: **Top**
* Herramienta utilizada en `Drawing`: `Detail View`
* Espacio de trabajo utilizado: `Drawing`

### P4.2 · Tolerancia introductoria

* Dimensión nominal: **Ø14 mm**
* Tolerancia aplicada: **No se agregó una tolerancia específica al modelo.**
* Límite superior: **No aplica.**
* Límite inferior: **No aplica.**
* Motivo funcional o indicación del enunciado: **El ejercicio no proporciona una función de fabricación ni una tolerancia específica para el agujero. Por esta razón se conserva la dimensión nominal y no se inventan requisitos de fabricación.**

### P4.3 · Interpretación

Interpretación del ejemplo didáctico `20 ± 0,1 mm`:

* Valor nominal: **20,0 mm**
* Valor máximo permitido: **20,1 mm**
* Valor mínimo permitido: **19,9 mm**

### P4.4 · Decisión técnica

La tolerancia no era necesaria para este plano porque el ejercicio no proporciona una función específica que requiera establecer límites dimensionales para la pieza. Agregar una tolerancia sin una justificación técnica introduciría un requisito de fabricación que no está definido en el enunciado. Por ello, se conserva la dimensión nominal.

### Evidencias P4

![P4: Zona de detalle](S11_P4_ZonaDetalle_Loaisiga_Nohelia.png) <img width="507" height="262" alt="S11_P4_ZonaDetalle_Loaisiga_Nohelia.png" src="https://github.com/user-attachments/assets/0f2f3f85-6341-40cf-a847-eff0056bf875"/>)

![P4: Detalle ampliado](S11_P4_Detalle_Loaisiga_Nohelia.png) <img width="208" height="222" alt="S11_P4_Detalle_Loaisiga_Nohelia.png" src="https://github.com/user-attachments/assets/26339f63-3a88-4f0e-af6c-cc9f372f44f2" />)

![P4: Tolerancia](S11_P4_Tolerancia_Loaisiga_Nohelia.png)<img width="940" height="667" alt="S11_P4_Tolerancia_Loaisiga_Nohelia.png" src="https://github.com/user-attachments/assets/e4013a33-ef2f-4e72-9cc3-ce35598b1689" />
)

---

## P5 — Plano final y verificación

**Propósito:** revisar el plano completo mediante la lista de comprobación y verificar su correspondencia con el modelo 3D.

**Entorno:** Fusion, espacios `Drawing` y `Design`.

### P5.0 · Pasos en Fusion

Se revisó el Drawing final conservando las vistas `Front`, `Top` y `Right`, junto con la sección A-A y el detalle B.

Se verificaron la dirección de observación, las letras y flechas, el rayado, las líneas ocultas, las cotas y la escala del detalle. Posteriormente se cambió a `Design` para comparar la representación técnica con el modelo 3D.

Las correcciones realizadas se enfocaron en mejorar la legibilidad del plano y mantener la correspondencia entre el Drawing y el modelo.

### P5.1 · Lista de comprobación

* [x] El corte atraviesa la característica relevante.
* [x] La dirección de observación es correcta.
* [x] Las letras y flechas son coherentes.
* [x] El rayado representa únicamente superficies cortadas.
* [x] Las áreas adyacentes se diferencian.
* [x] Se eliminaron líneas ocultas innecesarias.
* [x] Las cotas siguen siendo legibles.
* [x] El detalle tiene letra y escala.
* [x] La tolerancia está justificada o se documentó por qué no se agregó.
* [x] El plano coincide con el modelo 3D.
* [x] No hay superposiciones ni información redundante.

### P5.2 · Revisión por pares

| Criterio revisado | Observación recibida                                                           | Corrección realizada                                                           |
| ----------------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ |
| Corte o sección   | Se debe comprobar que el corte atraviese la característica interior principal. | Se verificó el plano de corte respecto al agujero Ø14 mm.                      |
| Rayado            | El rayado debe representar únicamente las superficies atravesadas.             | Se revisó el rayado y se mantuvieron libres las cavidades.                     |
| Detalle           | La zona ampliada debe tener identificación y escala.                           | Se identificó el detalle como B y se indicó la escala 2:1.                     |
| Tolerancia        | No se debe agregar una tolerancia sin justificación.                           | Se mantuvo la dimensión nominal de Ø14 mm.                                     |
| Legibilidad       | Las vistas, cotas y anotaciones deben poder interpretarse sin superposiciones. | Se revisó la distribución del Drawing y se ajustaron los elementos necesarios. |

### P5.3 · Preparación para la Prueba Corta 2

* Una situación en la que conviene una sección: **Cuando una característica interior no puede comunicarse claramente mediante una vista ordinaria y líneas ocultas,**
