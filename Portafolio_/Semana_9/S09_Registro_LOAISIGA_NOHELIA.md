# ICT401 · Semana 9 — Registro de interpretación y reconstrucción 3D

14 al 19 de septiembre de 2026.

- Estudiante: [Nohelia Loaisiga Sandoval]
- Grupo: [60]
- Carpeta o proyecto de Fusion Cloud con acceso docente: [Respuesta]
- Copias personales: `ICT401_S09_P1_Apellido_Nombre`, `ICT401_S09_P2_Apellido_Nombre`, `ICT401_S09_P3_Apellido_Nombre`.

## Instrucciones

Copie esta plantilla a `Portafolio/semana09/` y guárdela como `S09_Registro_Apellido_Nombre.md`. Sustituya `Apellido_Nombre` por un apellido y un nombre sin espacios ni tildes. Complete cada `[Respuesta]`, agregue las imágenes solicitadas en la misma carpeta y haga commit.

Conserve siempre la estrategia inicial. Si modifica una decisión durante el modelado, no borre lo anterior: describa qué cambió, qué evidencia del plano o del modelo motivó la corrección y qué elemento paramétrico modificó.

X = ancho, Y = profundidad, Z = altura. Trabaje en milímetros. Cuando compare vistas, mantenga Front, Top y Right con orientación coherente y cámara ortográfica.

---

## P1 — Del plano a la estrategia de modelado

### P1.1 · Dimensiones generales identificadas antes de abrir Fusion

- X total: [70 mm]
- Y total: [40 mm]
- Z total: [30 mm]

### P1.2 · Características geométricas identificadas

| Característica | Descripción | Vista(s) que la definen | Dimensiones asociadas |
|---|---|---|---|
| 1 | [Base rectangular de la pieza] | [Front (X-Z) y Top (X-Y)] | [70 × 40 × 12 mm] |
| 2 | [Elevación o escalón superior] | [Front (X-Z) y Right (Y-Z)] | [Altura total 30 mm] |
| 3 | [Parte elevada ubicada en un extremo] | [Right (Y-Z) y Top (X-Y)] | [20 mm en Y, 30 mm en Z] |
| 4 | [Cambio de nivel que forma el perfil escalonado] | [Front (X-Z)] | [30 mm de altura total y 12 mm de base] |

### P1.3 · ¿Qué plano de boceto utilizará primero y por qué?

[Utilizaré primero el plano XY (Top), porque permite definir la base de la pieza con sus dimensiones generales de 70 mm en X y 40 mm en Y. Después se puede extruir la base 12 mm en Z y agregar sobre ella la parte elevada.]

### P1.4 · Estrategia inicial de modelado

1. [Crear un boceto en el plano XY (Top) y dibujar un rectángulo de 70 × 40 mm para representar la base.]
2. [Extruir la base 12 mm en Z, obteniendo el espesor de la parte inferior.]
3. [Crear un segundo boceto sobre la cara superior de la base, dibujando el rectángulo de la parte elevada de 30 × 20 mm.]
4. [Extruir la parte elevada 18 mm, ya que la altura total indicada en el plano es de 30 mm y la base tiene 12 mm.]
5. [Comprobar las dimensiones y las vistas Front, Right y Top para verificar que el modelo coincida con el plano.]

### P1.5 · Después de comprobar en Fusion, ¿qué parte de la estrategia funcionó y qué tuvo que corregir?

[La estrategia de crear primero la base y después agregar la parte elevada funcionó correctamente. La principal comprobación fue considerar que la altura de 30 mm es total, por lo que la segunda extrusión debe ser de 18 mm sobre la base de 12 mm. También se verificaron las dimensiones de las vistas para asegurar que coincidieran con el plano.]
### P1.6 · ¿Qué vista o dimensión permitió detectar la corrección?

[La vista FRont al comprobar que la altura total de la pieza es de 30mm y que la pase tiene 12mm de altura. Por eso la parte elevada debía extruirse 18mm adicionales. ]

### Evidencias P1

Modelo parcial o final en orientación pictórica, con nombre del diseño y ViewCube visibles.

![P1: Modelo](S09_P1_Modelo_Apellido_Nombre.png)<img width="1356" height="515" alt="S09_P1_Loaisiga_Nohelia.png" src="https://github.com/user-attachments/assets/07f4b06a-d6af-4245-9ceb-f849588c571d" />


Captura donde se vea el Sketch, dimensión u operación que mejor representa la estrategia seguida.

![P1: Estrategia](S09_P1_Estrategia_Apellido_Nombre.png)<img width="1328" height="556" alt="S09_P1_Loaisiga_Nohelia.png" src="https://github.com/user-attachments/assets/82c485b8-dd1d-4918-b75e-606857e1ba75" />


---

## P2 — Dos estrategias para una misma pieza

### P2.1 · Resuma la estrategia A

[La estrategia A consiste en construir primero el perfil frontal completo en forma de L sobre el plano XZ. Luego se extruye este perfil a toda la profundidad de la pieza y finalmente se crea la perforación vertical pasante]

### P2.2 · Resuma la estrategia B

[La estrategia B consiste en construir primero la base desde un boceto en el plano XY y extruirla. Después se crea la torre izquierda mediante un segundo boceto y una segunda extrusión con operación Join. Finalmente se realiza la perforación vertical pasante.]

### P2.3 · ¿Ambas estrategias pueden producir la misma geometría? Justifique.

[Sí. Ambas estrategias pueden producir la misma geometría final, porque utilizan diferentes secuencias de modelado pero definen las mismas dimensiones y características de la pieza. La diferencia está principalmente en la forma de construirla y en la organización de las operaciones.]

### P2.4 · Compare las estrategias

| Criterio | Estrategia A | Estrategia B | ¿Cuál considera mejor y por qué? |
|---|---|---|---|
| Número de operaciones | [Menor cantidad de operaciones] | [Mayor cantidad de operaciones] | [A porque requiere menos operaciones] |
| Claridad de intención de diseño | [Alta porque el perfil completo se define de una vez] | [Alta porque las características se construyen por separados  ] | [B porque separa la base y la torre] |
| Facilidad de edición | [Alta para cambiar el perfil global; requiere editar solo un Sketch.] | [Media, requiere ajustar el Sketch inicial o la altura de la segunda extrusión.] | [Estrategia A, ya que todos los cambios de perfil se concentran en el primer Sketch.] |
| Dependencia entre operaciones | [Baja; las características principales nacen de la misma operación base.] | [Mayor; la torre depende de la cara superior creada por la base.] | [Estrategia A, al reducir fallos en cascada en la línea del tiempo si se modifica la base.] |
| Correspondencia con el plano |  [Mayor porque la torre depende de la base] | [A porque tiene menos dependencia entre operaciones] |[Estrategia A, al reducir fallos en cascada en la línea del tiempo si se modifica la base.]

### P2.5 · Si cambia una dimensión principal de la pieza, ¿qué estrategia sería más fácil de modificar? Explique qué Sketch u operación tendría que editar.

[La Estrategia A sería la más fácil de modificar. Al haber construido el perfil principal en forma de L en un solo boceto frontal (plano XZ), cualquier cambio en la altura total, altura del escalón, ancho de la base o espesor de la torre se realiza directamente editando el Sketch 1. En la Estrategia B, modificar estas cotas podría requerir editar múltiples bocetos o ajustar cotas de extrusión separadas]

### P2.6 · ¿Cuál estrategia usaría finalmente y por qué?

[Utilizaría la Estrategia A. Es más eficiente al requerir menos operaciones en el timeline de Fusion, mantiene una menor dependencia entre características y facilita futuras modificaciones paramétricas concentrando las dimensiones del perfil principal en un único boceto.]

### Evidencias P2

Captura del historial/timeline y del modelo obtenido con la estrategia seleccionada.

![P2: Estrategia seleccionada](S09_P2_Estrategia_Apellido_Nombre.png) <img width="1365" height="711" alt="S09_P2_Estrategia_Loaisiga_Nohelia.png" src="https://github.com/user-attachments/assets/f53db10e-f81b-4e2e-b737-6d6865532b20" />



---

## P3 — Plano → modelo → plano

### P3.1 · Antes de modelar, describa la pieza en una frase técnica

[Es una pieza prismática formada por una base rectangular, un resalte posterior, una perforación vertical pasante de 12mm y una ranura rectangular vertical pasante de 12x16mm]

### P3.2 · Dimensiones y características clave

| Elemento | Valor o descripción | Vista(s) de donde se obtiene |
|---|---|---|
| X total | [80mm] | [front y top] |
| Y total | [50mm] | [top y right] |
| Z total | [45mm] | [front, y right] |
| Característica 1 | [Resalte de 45x30m] | [front, top y right] |
| Característica 2 | [Aguero vertical 12mm centro (22,35)] | [top] |
| Característica 3 | [Ranura vertical pasante de 12x16mm] | [top] |

### P3.3 · Estrategia inicial

1. [Crear un boceto en el plano XY (Top) para dibujar el perfil base de la pieza de 80 × 50 mm y extruirlo en Z hasta la altura de la base.]
2. [Crear un segundo boceto sobre la cara superior para definir la geometría del resalte posterior (45 × 30 mm) y extruirlo verticalmente hasta alcanzar la altura total de 45 mm.]
3. [Crear un boceto en la cara superior para ubicar el centro del agujero cilíndrico (coordenadas 22, 35 mm desde el origen) y aplicar una operación de extruido de corte o pasante de Ø12 mm.]
4. [Diseñar el boceto de la ranura rectangular de 12 × 16 mm sobre el contorno correspondiente y extruir en corte pasante toda la altura requerida.]
5. [Verificar las cotas finales mediante la herramienta de medición (Inspect > Measure) y comparar las vistas ortográficas (Front, Top y Right) en proyección ortográfica contra el plano técnico.]

### P3.4 · Verificación de vistas

| Vista | ¿Coincide con el plano? | Contorno/característica comprobada | Corrección realizada |
|---|---|---|---|
| Front | [Sí] | [Contorn frontal, altura total y resalte] | [Ninguna] |
| Top | [Sí] | [Ancho, profundidad, posición del agujero y ranura ] | [Ninguna] |
| Right | [Sí] | [Profundidad, altura de la base y resalte ] | [Ninguna] |

### P3.5 · Verificación dimensional

| Dimensión crítica | Valor del plano | Valor medido en Fusion | Elemento medido | ¿Coincide? |
|---|---|---|---|---|
| 1 | [80mm] | [80mm] | [Ancho total] | [si] |
| 2 | [50mm] | [50mm] | [Pronfundidad total ] | [si] |
| 3 | [45mm] | [45mm] | [Altura total] | [si] |
| 4 | [12mm] | [12mm] | [Agujero pasante ] | [si] |

### P3.6 · ¿Qué cambió entre su estrategia inicial y el modelo final?

[La estrategia inicial se mantuvo durante el modelado. AL realizar la comparación de las vistas Front, Top y Right, el modelo coincidió con el plano, por lo que no fue necesario modificar ningún Sketch, dimensión u operación]

### P3.7 · Si tuviera que cambiar una dimensión principal, ¿qué Sketch, dimensión u operación editaría?

[Si tuviera que cambiar una dimensión principal, editaría el Sketch que controla la base de la pieza y modificaria la dimensión correspondiente. Si el cambio fuera de una característica especifica modificaría el Sketch u operación que controla esa característica para que las demás operaciones dependientes se actualicen corretamente.]

### Evidencias P3

Modelo final en orientación pictórica, con nombre y ViewCube visibles.

![P3: Modelo final](S09_P3_Modelo_Apellido_Nombre.png)

Montaje de Front, Top y Right del modelo para compararlos con el plano.

![P3: Vistas](S09_P3_Vistas_Apellido_Nombre.png)

Captura de una comprobación dimensional con `Inspect > Measure`.

![P3: Medicion](S09_P3_Medicion_Apellido_Nombre.png)

---

## Reflexión final

La diferencia principal entre reconstruir una pieza en Semana 8 y reconstruirla desde un plano en Semana 9 es:

[En la Semana 8 se trabajaba a partir de la observación e interpretación directa de un modelo 3D previo, mientras que en la Semana 9 la reconstrucción exige interpretar cotas, vistas ortográficas y tolerancias directamente desde un plano técnico en 2D, traduciendo esa información gráfica en una estrategia de operaciones paramétricas en 3D]

Antes de abrir Fusion, la información mínima que debo extraer de un plano es:

[Las dimensiones máximas globales (X, Y y Z), la ubicación del origen de coordenadas conveniente, el plano principal de boceto (Front, Top o Right) para la primera extrusión y la identificación de las características geométricas secundarias (agujeros, ranuras, escalones) con sus respectivas cotas de ubicación.]

Una estrategia de modelado es mejor que otra cuando:

[Requiere un menor número de operaciones complejas, mantiene una intención de diseño clara, reduce las dependencias innecesarias entre bocetos y permite modificar dimensiones principales de forma sencilla sin que el árbol de operaciones genere errores o fallos en la geometría.]

La comprobación final más importante para asegurar que el modelo corresponde al plano es:

[Configurar la cámara en modo ortográfico, orientar las vistas estándar (Front, Top y Right) para compararlas visualmente de forma directa contra el plano y utilizar la herramienta Inspect Measure para validar que las dimensiones críticas medidas en el modelo 3D coincidan exactamente con las cotas del plano.]

## Checklist

- [ ] Registré la estrategia inicial de P1 antes de comprobar en Fusion.
- [ ] Comparé dos estrategias en P2 y justifiqué mi selección.
- [ ] Reconstruí P3 a partir del plano sin usar un modelo 3D de referencia.
- [ ] Comparé Front, Top y Right contra el plano.
- [ ] Verifiqué al menos cuatro dimensiones críticas en P3.
- [ ] Documenté las correcciones sin borrar mis decisiones iniciales.
- [ ] Las cinco imágenes se visualizan correctamente en GitHub.
- [ ] Los modelos P1–P3 están disponibles en Fusion Cloud con acceso docente.
- [ ] Completé la reflexión final.

Commit sugerido: `S09 ejercicios Fusion Apellido Nombre`.

Corrección posterior: `S09 correccion Fusion Apellido Nombre`.
