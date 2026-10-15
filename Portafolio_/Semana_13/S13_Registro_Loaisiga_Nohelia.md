# ICT401 · Semana 13 — Registro de ensamblaje básico

12 al 17 de octubre de 2026.

- Estudiante: [Nohelia Loaisiga Sandovaol]
- Grupo: [60]
- Proyecto de Fusion Cloud con acceso docente: [ ICT401_NoheliaLoaisiga]
- Nombre del diseño de ensamblaje: [Ensamblaje_Basico_Nohelia]
- Piezas base utilizadas: [Base, Soporte vertical, Pasador]
- Fecha de trabajo de laboratorio: [Respuesta]

## Instrucciones

Utilice esta plantilla en `Portafolio/semana13/` y guárdela como `S13_Registro_Apellido_Nombre.md`. Sustituya `Apellido_Nombre` por un apellido y un nombre sin espacios ni tildes. Complete cada `[Respuesta]` durante las cuatro lecciones prácticas y agregue las imágenes solicitadas junto con la ficha.

La sesión virtual del miércoles se dedica a la revisión oral del Proyecto Integrador. Este registro corresponde únicamente a las cuatro lecciones prácticas de laboratorio. La actividad es formativa y no sustituye las evaluaciones oficiales posteriores.

Trabaje con las piezas base proporcionadas por la persona docente. Si todavía no se han distribuido, use las imágenes PNG y las dimensiones de esta ficha para construirlas. No modifique los archivos originales ni oculte un componente para evitar una interferencia. Si su versión de Fusion utiliza otro nombre de comando, escriba el nombre real utilizado y describa su función.

Ayuda oficial de Fusion: [Fusion Help](https://help.autodesk.com/view/fusion360/ENU/), sección `Assemblies`.

## Conjunto de trabajo

Dimensiones nominales de referencia: base maciza `100 x 70 x 10 mm`; soporte de `60 mm` de ancho, `70 mm` de alto y `40 mm` de fondo, con alojamiento pasante `diametro 16 mm`; pasador `diametro 16 x 80 mm`.

![Ensamblaje básico de referencia](ICT401_S13_Ensamblaje_Basico.png)

### Posicionamiento exacto

El soporte se centra sobre la base, no se coloca en una esquina:

- Margen lateral: `20 mm` a cada lado, porque `(100 - 60) / 2 = 20 mm`.
- Margen frontal y posterior: `15 mm` a cada lado, porque `(70 - 40) / 2 = 15 mm`.
- Cara inferior del soporte coincidente con la cara superior de la base.
- Relación base-soporte: `Rígida (Rigid)`.
- Centro del alojamiento: `40 mm` desde la cara inferior del soporte y `30 mm` desde cada lado del soporte.
- Pasador: coaxial con el alojamiento, centrado en el espesor de la pared y con relación `Revolute (Revoluta)`.
- Si la pared mide `10 mm`, el pasador de `80 mm` sobresale aproximadamente `35 mm` a cada lado.

No registre una distancia desde una esquina para ubicar el pasador. Su posición queda definida por el centro del alojamiento.

| Componente | Nombre en Fusion | Función dentro del conjunto | Observación inicial |
|---|---|---|---|
| Base | [Base] | [Referencia fija del conjunto y soporte de las demás piezas] | [Placa maciza rectangular de 100 x 70x 10 mm] |
| Soporte vertical | [Soporte vertical] | [Pieza en escuadra que se relaciona con la base y aloja el pasador] | [Dimensiones 60 x 70 x 40 mm con alojamiento pasante 16 mm] |
| Eje o pasador | [Pasador] | [Pieza cilíndrica que atraviesa el alojamiento del soporte permitiendo movimiento de giro] | [Dimensiones 16 x 80 mm] |

## Comandos bilingues de Fusion

| Accion | Ruta o comando | Resultado esperado |
|---|---|---|
| Crear diseño | `Archivo > Nuevo diseño (File > New Design)` | Diseño vacío y proyecto confirmado en el Panel de datos. |
| Insertar pieza | `Insertar en el diseño actual (Insert into Current Design)` | Componente visible en el Navegador. |
| Fijar base | Clic derecho en Navegador > `Fijar (Ground)` | La base no se desplaza ni gira. |
| Relacionar soporte | `Ensamblar > Unión (Assemble > Joint)` > `Rígida (Rigid)` | El soporte queda unido a la base. |
| Relacionar pasador | `Ensamblar > Unión (Assemble > Joint)` > `Revoluta (Revolute)` | El pasador gira alrededor de su eje. |
| Probar relación | Clic derecho en la unión > `Animar unión (Drive Joint)` | Se comprueba el movimiento permitido. |
| Revisar interferencias | `Inspeccionar > Interferencia (Inspect > Interference)` > `Calcular (Compute)` | Se identifican cuerpos que ocupan el mismo volumen. |
| Editar relación | Clic derecho en la relación > `Editar (Edit)` | Se corrige origen, orientación, tipo o desplazamiento. |

Registre en cada lección qué componente seleccionó, qué comando utilizó y qué resultado observó. No se considera suficiente escribir solo el nombre de la herramienta.

## L1 — Reconocimiento de piezas y componente base

### Diagnóstico

- ¿Qué pieza funcionará como base y por qué?: [La placa rectangular de 100 x 70 x 10 mm, porque posee la mayor superficie de apoyo y sirve como cimiento fijo para montar los demás componentes]
- ¿Qué superficies de la base y del soporte podrían entrar en contacto?: [ La cara superior de la base y la cara inferior horizontal (ala) del soporte vertical]
- ¿Qué eje o alojamiento utilizará el pasador?: [El agujero pasante cilíndrico con diámetro de 16 mm ubicado en la sección vertical del soporte]
- ¿Qué movimiento estaba libre antes de aplicar relaciones?: [ El soporte presentaba seis grados de libertad tres de traslación y tres de rotación en el espacio tridimensional]
- ¿Qué orientación inicial seleccionó y por qué?: [e orientó con la base apoyada sobre el plano XY y el soporte alineado hacia arriba con el fin de replicar la posición del conjunto de referencia]

### Estado inicial

| Comprobación | Resultado |
|---|---|
| Base insertada como componente | [Sí,incorporada correctamente en el árbol del navegador] |
| Base fija o establecida como referencia | [Sí,mediante el comando Fijar] |
| Soporte insertado | [Sí] |
| Eje o pasador disponible | [Sí] |
| Nombres identificables en el navegador | [Sí] |

### Evidencia L1

`S13_PiezasBase_Apellido_Nombre.png`: captura del ensamblaje con la base y el soporte visibles, el navegador de componentes abierto y los nombres identificables.

![L1: piezas base](S13_PiezasBase_Loaisiga_Nohelia.png)<img width="1304" height="670" alt="image" src="https://github.com/user-attachments/assets/9daa93a7-283a-4448-894e-6d48fe014553" />


## L2 — Relaciones entre componentes

### Decisiones

| Relación | Componentes o geometrías vinculadas | Movimiento que elimina | Movimiento que conserva | Resultado |
|---|---|---|---|---|
| 1 | [Cara inferior del soporte y cara superior de la base] | [Las tres traslaciones y las tres rotaciones relativas entre base y soporte] | [Ninguno] | [El soporte queda fijo y centrado sobre la base] |
| 2 | [Superficie cilíndrica del pasador y alojamiento del soporte] | [Las traslaciones en X, Y, Z y las rotaciones sobre los ejes perpendiculares] | [La rotación axial a lo largo del propio pasador] | [El pasador atraviesa el alojamiento de manera coaxial y gira libremente] |

- Comando o herramienta utilizada: [Ensamblar > Unión]
- ¿Por qué esa relación representa la intención del conjunto?: [Porque refleja el comportamiento físico real: el soporte está rígidamente montado sobre la placa y el pasador actúa como un eje mecánico articulado de rotación]
- ¿La orientación del soporte quedó correcta?: [Sí,comprobada mediante los márgenes simétricos de 20 mm y 15 mm]
- ¿Qué movimiento debe conservar el eje?: [ Rotación pura a lo largo de su eje longitudinal]
- ¿Qué movimiento inesperado observó y cómo lo corrigió?: [Al aplicar la unión inicial, el soporte quedó invertido; se solucionó utilizando la opción Invertir (Flip) en el cuadro de diálogo de la unión]

### Evidencia L2

`S13_Relaciones_Apellido_Nombre.png`: captura del navegador de componentes y de la relación aplicada, con el conjunto orientado para leer la posición del soporte y del eje.

![L2: relaciones](S13_Relaciones_Loaisiga_Nohelia.png)<img width="593" height="416" alt="S13_Relaciones_Loaisiga_Nohelia.png" src="https://github.com/user-attachments/assets/42082d33-2c84-4885-b396-91c99a985250" />

## L3 — Revisión de interferencias

- Herramienta utilizada: [Inspeccionar > Interferencia]
- Componentes comparados: [Base, Soporte vertical y Pasador]
- ¿Se encontró una interferencia?: [No]
- Ubicación de la condición: [Interfaz cilíndrica entre el pasador y el agujero del soporte]
- ¿Se trata de interferencia, contacto previsto o separación intencional?: [Contacto previsto]
- Causa probable: [Coincidencia geométrica del diámetro nominal entre el pasador y el alojamiento del soporte]
- ¿Qué efecto tendría sobre el funcionamiento del conjunto?: [Ninguno negativo, ya que el espacio corresponde al acoplamiento mecánico holgado necesario para permitir la rotación del pasador]

| Componente A | Componente B | Zona revisada | Resultado | Evidencia |
|---|---|---|---|---|
| [Soporte vertical] | [Pasador] | [Alojamiento cilíndrico interior] | [Sin interferencias no deseadas] | [S13_Interferencia_Loaisiga_Nohelia.png] |

### Evidencia L3

`S13_Interferencia_Apellido_Nombre.png`: captura del análisis o de la zona problemática, con los componentes involucrados identificables.

![L3: interferencia](S13_Interferencia_Loaisiga_Nohelia.png)<img width="1363" height="469" alt="S13_Interferencia_Loaisiga_Nohelia.png" src="https://github.com/user-attachments/assets/a7fb6a08-9466-499a-b738-084cdc899059" />


## L4 — Corrección, verificación y cierre

### Registro de corrección

- Problema seleccionado: [Ajuste de la alineación coaxial del pasador para evitar desplazamientos longitudinales involuntarios excesivos durante la animación]
- Corrección prevista antes de modificar: [ Modificar el valor de desplazamiento (offset) en las propiedades de la unión revoluta para centrar simétricamente el pasador en el soporte]
- Componente o relación modificada: [Relación de unión revoluta del pasador]
- Cambio aplicado: [Edición de la unión Revolute para ajustar la posición del pasador dejando aproximadamente 35 mm salientes a cada lado]
- Resultado del segundo análisis: [El pasador mantiene el movimiento de rotación esperado sin generar errores ni colisiones volumétricas imprevistas]
- ¿La base continúa estable?: [Sí]
- ¿El soporte conserva su orientación?: [Sí]
- ¿El eje conserva el movimiento esperado?: [Sí]
- Versión o nombre final en Fusion Cloud: [Respuesta]

| Comprobación final | Resultado | Evidencia o explicación |
|---|---|---|
| Componentes visibles y nombrados | [Conforme] | [Árbol del navegador ordenado y etiquetado claramente] |
| Relaciones comprensibles | [Conforme] | [Uniones rígida y de revoluta documentadas] |
| Movimiento esperado | [Conforme] | [Comprobado mediante la herramienta de animación de uniones] |
| Interferencia revisada | [Conforme] | [Análisis completado sin colisiones volumétricas críticas] |
| Corrección documentada | [Conforme] | [Parámetros de desplazamiento ajustados y registrados] |

### Evidencia L4

`S13_Correccion_Apellido_Nombre.png`: captura comparativa o lámina con el estado problemático y el estado corregido, ambos etiquetados.

![L4: corrección](S13_Correccion_Loaisiga_Nohela.png)<img width="700" height="637" alt="S13_Correccion_Loaisiga_Nohela.png" src="https://github.com/user-attachments/assets/5a507081-c4c9-49ff-b7fd-09be43639c9f" />


## Checklist de cierre

- [x] Las tres piezas base corresponden al conjunto indicado.
- [x] La base está fija o definida como referencia.
- [x] Los componentes tienen nombres identificables.
- [x] Cada relación aplicada tiene una intención explicable.
- [x] El movimiento permitido corresponde a la función del conjunto.
- [x] Se ejecutó una revisión de interferencias.
- [x] La interferencia o ausencia de interferencia quedó interpretada.
- [x] La corrección quedó registrada antes y después.
- [x] El ensamblaje fue guardado en Fusion Cloud.
- [x] La ficha y las imágenes utilizan la nomenclatura solicitada.
- [x] No se adelantaron vistas explosionadas ni listas de componentes.

## Reflexión final

1. ¿Qué diferencia encontró entre insertar piezas y construir un ensamblaje con relaciones?: [Insertar piezas solo coloca los componentes de forma aislada en el espacio de trabajo sin restricciones espaciales, mientras que construir un ensamblaje con relaciones (Joints) define matemáticamente cómo interactúan, limitando sus grados de libertad según su función mecánica real]
2. ¿Qué relación fue más difícil de definir y por qué?: [La relación revoluta del pasador, ya que requirió seleccionar con precisión las aristas circulares correctas para asegurar la coaxialidad exacta sin bloquear el giro libre]
3. ¿Cómo distinguió una interferencia de un contacto previsto?: [La interferencia representa una penetración física errónea entre volúmenes sólidos que ocupan el mismo espacio simultáneamente, en tanto que el contacto previsto corresponde a superficies de apoyo o ajustes mecánicos funcionales]
4. ¿Qué comprobará en Semana 14 antes de generar una vista explosionada o una lista de componentes?: [ Verificaré que todas las uniones estén libres de advertencias, que los componentes posean nombres estructurados y definitivos, y que el árbol del navegador mantenga una jerarquía limpia]

## Revisión docente

- Observación sobre componentes y nombres: [Respuesta]
- Observación sobre relaciones: [Respuesta]
- Observación sobre interferencias: [Respuesta]
- Corrección sugerida: [Respuesta]
- Estado del registro: [Pendiente/Completo]
