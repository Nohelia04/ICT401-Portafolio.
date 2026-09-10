# ICT401 · Semana 8 — Registro formativo de práctica en Fusion

7 al 12 de septiembre de 2026. V Congreso Universitario. Consolidación de contenidos. Sin evaluaciones.

- Estudiante: [Nohelia Loaisiga Sandoval]
- Grupo: [60]
- Carpeta o proyecto de Fusion Cloud con acceso docente (sin enlaces privados): [Respuesta]
- Modelos proporcionados: `S08_P1_Modelo_Observacion.f3d` y, después de P2, `S08_P2_Modelo_Comprobacion.f3d`.
- Copias personales: `ICT401_S08_P1_Apellido_Nombre` y `ICT401_S08_P2_Apellido_Nombre`.
- Diseños propios: `ICT401_S08_P4_Apellido_Nombre` y `ICT401_S08_P5_Apellido_Nombre`.

## Instrucciones

Copie esta plantilla a `Portafolio/semana08/` y guárdela como `S08_Registro_Apellido_Nombre.md`. Sustituya `Apellido_Nombre` en todos los nombres y enlaces por un apellido y un nombre sin espacios ni tildes. Complete cada [Respuesta], agregue las ocho imágenes en esa misma carpeta y haga commit. No necesita construir otra plantilla.

Escriba las predicciones y decisiones iniciales antes de comprobar. **Nunca borre una respuesta inicial incorrecta:** conserve lo escrito y agregue la corrección y su causa en el apartado posterior. Use la guía para los recursos gráficos y los tiempos de cada P1–P5 (50 minutos cada uno).

X = ancho, Y = profundidad, Z = altura; milímetros. Primer diedro: Right a la izquierda de Front y Top debajo de Front. Cámara ortográfica. Los montajes documentan correspondencia, no son planos a escala: compruebe dimensiones con Measure, no con píxeles. Combine capturas con una herramienta de imágenes o diapositivas y guarde un único PNG por nombre; no deforme imágenes ni oculte el ViewCube. Los recortes temporales no se entregan.

## P1 — Del modelo 3D a las vistas

### P1.1 · Antes de seleccionar Front, Top o Right: ¿qué características, caras y aristas espera ver en cada vista y qué dimensiones aparecerán horizontal y verticalmente?

[Este ver el perfil lateral escalonado de la pieza que corresponda a una forma en L invertida de tres escalones y que se aprecien las caras verticales de cada escalón y sus alturas correspondientes. Y con las dimensiones en el eje horizontal aparecerá la profundidad y en el eje vertical la altura. ]

### P1.2 · ¿Cuál vista considera inicialmente más informativa y por qué?

[La vista Front porque es la que permite apreciar directamente lo que es la geometría de los escalones mostrando tanto lo que es la altura como la longitud horizontal característica de cada nivel de la pieza en una sola proyección  ]

### P1.3 · Después de observar Front, Top y Right: ¿qué predicciones confirmó y qué corrigió? Explique por qué sin borrar su respuesta inicial.

[Se pudo confirmar la presencia de tres niveles escalonados simétricos en el perfil frontal. Al inicio se asumió que los descansos de los escalones tenían profundidad uniforme simple sin variaciones laterales lo que confirmo que al contrastar con Top y Right, no hubo errores mayores solo una mayor precisión en la proporción visual de los anchos respecto a la profundidad.]

### P1.4 · ¿Qué pares de vistas comparten ancho, altura y profundidad? Anote el valor comprobado en milímetros y la arista seleccionada.

[El ancho es compartido entre Front y Top la altura entre Front y Right los valores exactos se obtienen directamente mediante la herramienta Measure sobre las aristas correspondientes del modelo tridimencional.]

### P1.5 · Elija una característica tridimensional: ¿cómo aparece en dos vistas diferentes? Identifique las caras o aristas relacionadas.

[El cambio de nivel superior aparece en lo que es la vista Front como una arista horizontal superior que delimita el escalón más alto y en la vista Top como una línea divisoria paralela del escalón del segundo.  ]

| Vista | Predicción inicial: características y dimensiones | Observación posterior | Corrección y causa |
|---|---|---|---|
| Front | [Perfil con tres escalones, ancho horizontal y altura vertical total.] | [Se observa claramente el perfil escalonado de tres niveles con aristas netas.] | [Ninguna corrección necesaria; la predicción coincidió con el modelo.] |
| Top | [ Rectángulos adyacentes que muestran la profundidad y el ancho de cada huella.] | [Se visualizan tres franjas rectangulares correspondientes a las superficies horizontales.] | [Se ajustó la apreciación del espesor visual de cada franja tras medir en Fusion. ] |
| Right | [Contorno lateral derecho reflejando los escalones en sentido de profundidad. ] | [Se aprecian los saltos de altura y el fondo rectangular de la pieza. ] | [Ninguna corrección requerida.] |

| Dimensión compartida | Par de vistas | Valor (mm) y arista seleccionada |
|---|---|---|
| Ancho | [Front y Top] | [60mm] |
| Altura | [Front y Right] | [36mm] |
| Profundidad | [Top y Right] | [30mm] |

### Evidencias

Modelo completo en orientación pictórica, ViewCube y nombre de su copia visibles.

![P1: Modelo](S08_P1_Modelo_Apellido_Nombre.png)<img width="1360" height="696" alt="S08_P1_Modelo_Loaisiga_Nohelia.png" src="https://github.com/user-attachments/assets/0c376771-90a5-4a2b-8b6c-41c52b54f5bb" />


Un montaje de tres capturas de Fusion: Right a la izquierda, Front a la derecha y Top debajo de Front; etiquetas y cuerpo completo visibles.

![P1: Vistas](S08_P1_Vistas_Apellido_Nombre.png)<img width="1001" height="504" alt="S08_P1_Vistas_Loaisiga_Nohelia.png" src="https://github.com/user-attachments/assets/26b68b69-c11d-4efb-b5f4-1f3354b21eb9" />





## P2 — De las vistas al modelo mental

### P2.1 · ¿Qué forma general imagina y cuáles son sus cambios de altura?

[Me imagino una pieza prismática escalonada en forma de L o de sección en escuadra que presenta dos niveles principales de altura: una sección más alta en un extremo y una sección longitudinal más baja y alargada en el otro.]

### P2.2 · ¿La profundidad se mantiene o cambia entre zonas? Relacione las tres vistas.

[La profundidad cambia entre zonas según cada escalón la vista Top muestra un cuerpo principal ancho que se reduce en una esquina formando un rebaje o sección de menor profundidad, lo cual se alinea directamente con los límites verticales observados en las vistas Front y Right.]

### P2.3 · ¿Qué correspondencias encuentra entre vistas?

[Se observa alineación ortogonal directa la altura de la vista Front corresponde exactamente con la altura máxima de la vista Right, y los anchos o límites laterales de la vista Top coinciden con las proyecciones verticales de las vistas adyacentes según el sistema de primer diedro.
]

### P2.4 · ¿Qué información aporta Top y qué información aporta Right?

[La vista Top aporta la distribución bidimensional de la planta, delimitando el ancho total y las áreas de rebaje en los ejes X e Y; la vista Right aporta la perspectiva lateral del perfil escalonado y la distribución de las alturas en profundidad.]

### P2.5 · Describa verbalmente la pieza imaginada antes de mirar las alternativas.

[La vista Top aporta la distribución bidimensional de la planta, delimitando el ancho total y las áreas de rebaje en los ejes X e Y; la vista Right aporta la perspectiva lateral del perfil escalonado y la distribución de las alturas en profundidad.]

### P2.6 · ¿Selecciona A, B, C o D? Justifique antes de comprobar y descarte cada una de las otras tres mediante una vista.

[Se selecciona la alternativa que representa fielmente el volumen escalonado en escuadra con el rebaje frontal y lateral exacto. Las demás alternativas se descartan por presentar inversiones en la orientación del escalón, alturas incorrectas o geometrías de rebaje distintas al contrastarlas con la vista Front y Top.
]

### P2.7 · Después de comprobar: ¿fue correcta su selección, qué interpretó incorrectamente si falló y qué vista fue decisiva? Conserve la selección inicial y explique la corrección.

[La selección inicial fue correcta al coincidir plenamente con el modelo tridimensional de comprobación. La vista Front fue decisiva para validar la proporción exacta del perfil elevado en L sin necesidad de correcciones adicionales.]

| Alternativa | Justificación inicial: seleccionar o descartar | Vista que apoya mi decisión |
|---|---|---|
| A | [Seleccionada por coincidir con la geometría en L y el rebaje de planta. ] | [Front y Top] |
| B | [Descartada por mostrar una inversión en la orientación del perfil elevado. ] | [Right] |
| C | [Descartada por presentar proporciones de altura incongruentes con el alzado. ] | [Front] |
| D | [Descartada por contener un volumen rebajado central ajeno al esquema. ] | [Top] |

### Evidencias

Modelo correcto proporcionado por el docente durante la comprobación, en orientación pictórica, con nombre y ViewCube visibles.

![P2: Seleccion](S08_P2_Seleccion_Apellido_Nombre.png)<img width="870" height="397" alt="S08_P2_Seleccion_Loisiga_Nohelia.png" src="https://github.com/user-attachments/assets/5366843e-1a6d-44de-bb45-5d5742e723a3" />




## P3 — Detectives de vistas

### P3.1 · Caso A: ¿qué vista parece incorrecta, qué línea produce la inconsistencia, con cuál otra vista entra en contradicción y cómo debería corregirse?

[Mi hipótesis inicial es que la vista Top es la incorrecta, específicamente por la línea horizontal interna que aparece atravesando toda la pieza. Esta línea entra en contradicción con la vista Front, porque el cambio de nivel no debería extenderse por todo el ancho de la pieza. La línea correcta debería terminar donde se encuentra el cambio de posición indicado por las otras vistas, manteniendo la correspondencia entre las aristas.]

### P3.2 · Caso B: ¿qué dimensión debería conservarse, dónde aparece la contradicción, qué información permite comprobarla y cómo debería corregirse?

[La dimensión que debería conservarse es la profundidad Y, porque Top y Right comparten ese eje. En este caso aparece una contradicción porque Top indica una profundidad total de 48 mm, mientras que Right indica 40 mm. Para comprobarlo en Fusion utilizaría Measure, seleccionando la arista completa que representa la profundidad del sólido. Ambas vistas deberían mostrar el mismo valor, por lo que una de las dimensiones debe corregirse para que coincida con la medida real del modelo.]

### P3.3 · Caso C: ¿cuál vista no pertenece al conjunto, qué característica lo demuestra, con cuáles vistas entra en contradicción y qué debería mostrar una vista correcta?

[La vista que no pertenece al conjunto es Front, porque muestra la parte elevada en el lado derecho, mientras que Top y Right indican que esa característica debe ubicarse en el lado izquierdo. La posición de la arista vertical y del cambio de altura demuestra la contradicción. Una vista Front correcta debería mostrar la parte más alta hacia el lado izquierdo, manteniendo la correspondencia con Top y Right.]

### P3.4 · Para cada caso: ¿qué acción realizó en Fusion, qué observó y cómo corrigió su hipótesis inicial?

[En el caso A comparé las vistas Front y Top y observé que la línea horizontal de Top no correspondía con el cambio de nivel mostrado en Front, por lo que confirmé que esa línea era incorrecta. En el caso B utilicé la herramienta Measure para comprobar la profundidad del modelo y relacionarla entre Top y Right, confirmando que ambas vistas deben conservar el mismo valor. En el caso C alterné entre Front, Top y Right y observé que la posición de la zona elevada no coincidía entre las vistas, por lo que confirmé que Front era la vista que no pertenecía al conjunto.]

### P3.5 · ¿Qué caso documentó en la captura y qué detalle demuestra el error?

[Documenté el caso B, porque permite demostrar el error de manera más precisa mediante la herramienta Measure. La captura muestra la arista completa seleccionada y su longitud, permitiendo comprobar directamente la diferencia entre la profundidad indicada en Top y la que corresponde al modelo.]

| Caso | Hipótesis inicial | Acción en Fusion y observación | Corrección y causa |
|---|---|---|---|
| A | [La vista Top parece incorrecta por la línea horizontal que atraviesa toda la pieza.] | [Comparé Top con Front y observé que la línea no corresponde con el cambio de nivel.] | [Se debe corregir la línea para que termine donde corresponde al cambio de nivel del sólido.] |
| B | [La profundidad indicada en una de las vistas parece incorrecta.] | [Utilicé Measure sobre la arista completa de profundidad y comparé Top con Right.] | [Ambas vistas deben conservar la misma profundidad Y; una de las medidas de 48 mm o 40 mm es incompatible.] |
| C | [La vista Front parece incorrecta porque la parte elevada está en el lado contrario.] | [Comparé Front con Top y Right y revisé la posición de las aristas.] | [Front debe mostrar la zona elevada en el lado izquierdo para coincidir con las otras dos vistas.] |

### Evidencias

Una vista de Fusion que compruebe uno de los errores; nombre y ViewCube visibles. Para el caso B, incluya Measure con la arista completa y su longitud.

![P3: Error](S08_P3_Error_Apellido_Nombre.png)<img width="1048" height="473" alt="](S08_P3_Error_Loaisiga_Nohelia.png" src="https://github.com/user-attachments/assets/e7451359-a68f-47dd-8881-3097293187ef" />



## P4 — Reconstrucción 3D guiada

### P4.1 · Antes de abrir Fusion: indique ancho total, altura máxima, profundidad total y número de niveles o cambios principales.

[La pieza tiene un ancho total de 64 mm, una profundidad total de 40 mm y una altura máxima de 40 mm. Presenta tres niveles principales de altura: 10 mm, 28 mm y 40 mm. También hay cambios importantes de posición en X = 24 mm y en Y = 20 mm, que permiten ubicar correctamente los diferentes niveles.]

### P4.2 · ¿Qué vista usará como referencia, qué plano inicial elegirá y cómo será su boceto base? Justifique relacionando las vistas.

[Usaré principalmente la vista Top como referencia para construir la base, porque permite relacionar directamente el ancho y la profundidad. Elegiré el plano XY y realizaré un boceto rectangular de 64 × 40 mm. Después relacionaré este boceto con Front y Right para determinar las diferentes alturas de la pieza.]

### P4.3 · ¿Cuál será su primera operación 3D y qué características posteriores prevé? Justifique.

[La primera operación será una extrusión de 10 mm del rectángulo base de 64 × 40 mm, ya que 10 mm corresponde al nivel más bajo de la pieza. Después agregaré material mediante nuevas extrusiones para alcanzar los niveles de 28 mm y 40 mm. Para ubicarlos correctamente tendré que considerar el cambio en X = 24 mm y el cambio de profundidad en Y = 20 mm.]

### P4.4 · Después de construir: ¿coincide Front, coincide Top y coincide Right? Para cada vista cite un contorno, una arista y una dimensión comprobada.

[Después de construir la pieza, las tres vistas coinciden con las referencias. En Front se observa el contorno escalonado y se comprueba el ancho total de 64 mm y la altura máxima de 40 mm. En Top se observa el contorno rectangular y el cambio de profundidad, comprobando 64 × 40 mm. En Right se observa el perfil de las alturas y se comprueba la profundidad total de 40 mm y la altura máxima de 40 mm.]

### P4.5 · ¿Qué fue necesario corregir y qué Sketch, operación o dimensión controlaba la corrección? Si no hubo cambios, justifique con una comprobación.

[No fue necesario realizar una corrección importante después de la construcción, porque las tres vistas coincidieron con las referencias. La comprobación mediante las vistas Front, Top y Right permitió verificar las dimensiones principales y la posición de los cambios de nivel. También comprobé que el modelo mantuviera un solo cuerpo y que las alturas correspondieran a 10, 28 y 40 mm.]

| Vista | ¿Coincide? | Contorno y arista | Dimensión comprobada (mm) | Corrección y causa |
|---|---|---|---|---|
| Front | [Sí] | [Contorno escalonado y arista vertical del cambio de nivel] | [Ancho 64 mm y altura 40 mm] | [No fue necesaria una corrección.] |
| Top | [Sí] | [Contorno rectangular y arista transversal del cambio de profundidad] | [64 × 40 mm] | [No fue necesaria una corrección.] |
| Right | [Sí] | [Perfil lateral y aristas de los cambios de altura] | [Profundidad 40 mm y altura 40 mm] | [No fue necesaria una corrección.] |

### Evidencias

Modelo terminado completo en orientación pictórica, nombre del diseño y ViewCube visibles.

![P4: Modelo](S08_P4_Modelo_Apellido_Nombre.png)<img width="1351" height="613" alt="S08_P4_Modelo_Loaisiga_Nohelia.png" src="https://github.com/user-attachments/assets/229b9de4-66e6-458c-885a-573d94475981" />


Montaje con tres pares: vista de referencia de esta guía junto a su correspondiente vista de Fusion. Disponga Right a la izquierda, Front a la derecha y Top debajo de Front.

![P4: Comparacion](S08_P4_Comparacion_Apellido_Nombre.png)<img width="715" height="514" alt="S08_P4_Comparacion_Loaisiga_Nohelia.png" src="https://github.com/user-attachments/assets/6747229a-3e1c-4821-a64d-3923ff30fa21" />



## P5 — Reto de reconstrucción autónoma

### P5.1 · Antes de modelar: indique ancho total, altura máxima y profundidad total.

[Respuesta]

### P5.2 · ¿Qué vista elegirá para comenzar, qué plano inicial y qué primera operación prevé? Justifique.

[Respuesta]

### P5.3 · ¿Qué características posteriores prevé, cuál es la más difícil de interpretar y qué vistas necesita relacionar para comprenderla?

[Respuesta]

### P5.4 · Después de construir: ¿coinciden Front, Top y Right? Para cada vista cite un contorno, una arista y una dimensión comprobada.

[Respuesta]

### P5.5 · ¿Funcionó la estrategia inicial, qué tuvo que modificar, qué vista permitió detectarlo y qué haría diferente si reconstruyera nuevamente la pieza?

[Respuesta]

| Vista | ¿Coincide? | Contorno y arista | Dimensión comprobada (mm) | Corrección y causa |
|---|---|---|---|---|
| Front | [Respuesta] | [Respuesta] | [Respuesta] | [Respuesta] |
| Top | [Respuesta] | [Respuesta] | [Respuesta] | [Respuesta] |
| Right | [Respuesta] | [Respuesta] | [Respuesta] | [Respuesta] |

### Evidencias

Modelo terminado completo en orientación pictórica, nombre del diseño y ViewCube visibles.

![P5: Modelo](S08_P5_Modelo_Apellido_Nombre.png)

Montaje con tres pares: vista de referencia de esta guía junto a su correspondiente vista de Fusion. Disponga Right a la izquierda, Front a la derecha y Top debajo de Front.

![P5: Comparacion](S08_P5_Comparacion_Apellido_Nombre.png)

## Reflexión final

Una vista por sí sola puede ser insuficiente porque:

[Respuesta]

Para relacionar correctamente varias vistas debo comprobar:

[Respuesta]

Antes de comenzar una reconstrucción 3D conviene:

[Respuesta]

La diferencia principal entre lo que hice en Semana 7 y Semana 8 es:

[Respuesta]

Lo que todavía necesito practicar antes de reconstruir una pieza a partir de un plano es:

[Respuesta]

## Checklist

- [ ] Completé P1 antes y después de observar las vistas.
- [ ] Justifiqué mi selección en P2.
- [ ] Identifiqué y comprobé inconsistencias en P3.
- [ ] Planifiqué P4 antes de comenzar a modelar.
- [ ] Comprobé P4 contra las tres vistas originales.
- [ ] Realicé P5 con mayor autonomía.
- [ ] Comprobé P5 contra las vistas originales.
- [ ] Respondí las preguntas de reflexión.
- [ ] Las ocho imágenes se visualizan correctamente en GitHub.
- [ ] Mis modelos P4 y P5 están disponibles para revisión docente en Fusion Cloud.
- [ ] Conservé mis predicciones iniciales aunque fueran incorrectas.
- [ ] Expliqué las correcciones realizadas.
- [ ] El commit utiliza el mensaje solicitado.

Commit: `S08 ejercicios Fusion Apellido Nombre`.

Corrección posterior: `S08 correccion Fusion Apellido Nombre`.

Abra el registro en GitHub y compruebe los ocho enlaces. Los archivos nativos permanecen en Fusion Cloud con acceso docente. Este registro conserva práctica formativa y no constituye una entrega evaluada de portafolio.
