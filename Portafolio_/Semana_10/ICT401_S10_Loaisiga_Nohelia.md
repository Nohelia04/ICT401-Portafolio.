# ICT401 · Semana 10 — Registro de vistas técnicas y acotación normalizada

21 al 26 de septiembre de 2026.

- Estudiante: [Nohelia Loaisiga Sandoval]
- Grupo: [60]
- Carpeta o proyecto de Fusion Cloud con acceso docente: []
- Modelos utilizados: `ICT401_S09_P1_Apellido_Nombre`, `ICT401_S09_P2_Apellido_Nombre`, `ICT401_S09_P3_Apellido_Nombre` u otros equivalentes.

## Instrucciones

Copie esta plantilla a `Portafolio/semana10/` y guárdela como `S10_Registro_Apellido_Nombre.md`. Sustituya `Apellido_Nombre` por un apellido y un nombre sin espacios ni tildes. Complete cada `[Respuesta]`, agregue las imágenes solicitadas en la misma carpeta y haga commit.

Documente cada decisión de selección de vistas y acotación. Si modifique una decisión durante el proceso, no borre lo anterior: describa qué cambio, qué evidencia del modelo o del Drawing motivó la corrección y qué ajuste realizó.

X = ancho, Y = profundidad, Z = altura. Trabaje en milímetros. Cuando compare vistas, mantenga Front, Top y Right con orientación coherente y cámara ortográfica.

---

## P1 — Del modelo 3D a las vistas técnicas

### P1.1 · Modelo utilizado

- Nombre del diseño en Fusion: [Nombre real del diseño]
- Pieza de referencia (semana de origen): Pieza en L reconstruida en la Semana 9.

### P1.2 · Características principales del modelo

| Característica | Descripción | Vista(s) que la comunican |
|---|---|---|
| 1 | Base rectangular de 60 mm de ancho, 40 mm de profundidad y 10 mm de altura. | Front, Top y Right |
| 2 | Pared vertical que eleva la pieza hasta una altura total de 35 mm. | Front y Right |
| 3 | Forma general en L formada por la base y la pared vertical. | Front |
| 4 | La pared ocupa una profundidad de 10 mm y su posición se aprecia respecto a la base. | Top y Right |

### P1.3 · Vistas seleccionadas y justificación

| Vista | ¿Es necesaria? | ¿Por qué? | ¿Qué información aporta? |
|---|---|---|---|
| Front | Sí | Es necesaria porque muestra directamente la forma en L de la pieza y la diferencia de alturas. | Comunica el ancho total de 60 mm, la altura total de 35 mm y la altura de la base de 10 mm. |
| Top | Sí | Es necesaria para observar la profundidad y la posición de la pared respecto a la base. | Comunica la profundidad total de 40 mm y la separación/posición de la pared de 10 mm. |
| Right | Sí | Permite confirmar la altura y la posición de la pared desde otra dirección. | Comunica la profundidad y la altura de la pieza, además de la posición de la pared. |
| Otra: Ninguna | No | No se requiere una vista adicional porque Front, Top y Right permiten comunicar la geometría de la pieza. | Evita agregar información redundante. |

### P1.4 · ¿Algual vista resultó redundante? ¿Cuál y por qué?

No se consideró redundante ninguna de las tres vistas principales. Front, Top y Right aportan información diferente y permiten comprobar la correspondencia geométrica de la pieza en las tres dimensiones.

### P1.5 · Método utilizado para generar las vistas en Fusion

Se utilizó el entorno Drawing o la función de vistas del modelo en Fusion para generar las vistas ortogonales. Se tomó Front como referencia y se proyectaron Top y Right, verificando que mantuvieran la correspondencia geométrica con el modelo 3D.

### Evidencias P1

Captura de las vistas ortogonales generadas desde el modelo.

![P1: Vistas](S10_P1_Vistas_Apellido_Nombre.png)<img width="618" height="495" alt="](S10_P1_Vistas_Loaisiga_Nohelia.png" src="https://github.com/user-attachments/assets/1e11fcfd-3e7a-44f4-a443-89d40bce020f" />


Modelo 3D en orientación isométrica con nombre y ViewCube visibles.

![P1: Modelo](S10_P1_Modelo_Apellido_Nombre.png)<img width="1365" height="672" alt="S10_P1_Modelo_Loaisiga_Nohelia.png" src="https://github.com/user-attachments/assets/1a987dfa-bd5d-4fbb-9e2a-095fed442cf1" />


---

## P2 — Creación del plano desde el modelo

### P2.1 · Configuración del Drawing

- Formato seleccionado: A4
- Orientación: Horizontal
- Escala: 1:1
- Justificación de cada elección: Se seleccionó A4 horizontal porque permite organizar las vistas Front, Top y Right con suficiente espacio para las cotas. La escala 1:1 permite conservar las dimensiones reales de la pieza y facilita la lectura de las vistas.

### P2.2 · Disposición de vistas

| Vista | Posición en el Drawing | Distancia a la vista adyacente | ¿Alineada correctamente? |
|---|---|---|---|
| Front (base) | Parte central del Drawing | Suficiente para colocar las cotas | Sí |
| Top | Debajo de Front | Separación suficiente para las cotas | Sí |
| Right | Al lado de Front | Separación suficiente para evitar superposición | Sí |

### P2.3 · ¿Qué problemas de alineación o disposición detectó? ¿Cómo los resolvió?

Se verificó que las vistas mantuvieran la correspondencia entre sus ejes y características geométricas. Cuando fue necesario, se ajustó la posición de las vistas para mantenerlas alineadas y dejar espacio suficiente para colocar las cotas sin superposiciones.

### P2.4 · ¿La escala permite legibilidad de todas las vistas? Justifique.

Sí. La escala seleccionada permite observar claramente las tres vistas y colocar las dimensiones sin que se superpongan con el contorno de las piezas. La guía indica que la escala debe permitir la legibilidad y que las vistas deben disponer de espacio suficiente para futuras cotas.

### Evidencias P2

Captura del Drawing con las tres vistas insertadas y alineadas.

![P2: Plano](S10_P2_Plano_Apellido_Nombre.png)<img width="657" height="467" alt="S10_P2_Plano_Loaisiga_Nohelia.png" src="https://github.com/user-attachments/assets/d5ccc6e8-0fd1-4bfe-b021-b8690744c6b8" />




---

## P3 — Acotación normalizada básica

### P3.1 · Dimensiones generales aplicadas

| Dimensión | Valor | Vista donde se colocó | Justificación |
|---|---|---|---|
| Ancho total (X) | 72 mm | Front | Define el tamaño total de la pieza en dirección X. |
| Profundidad total (Y) | 36 mm | Top | Define la profundidad total de la pieza. |
| Altura total (Z) | 36 mm | Front | Define la altura máxima de la pieza. |

### P3.2 · Dimensiones parciales y funcionales

| Característica | Dimensión | Valor | Vista | ¿Repetida en otra vista? |
|---|---|---|---|---|
| Escalón superior | Ancho | 28 mm | Front | No |
| Base | Altura | 12 mm | Front | No |
| Perforación | Diámetro | Ø12 mm | Top | No |
| Perforación | Posición del centro | (14, 18) mm | Top | No |

### P3.3 · ¿Eliminó alguna cota por redundante? ¿Cuál?

Sí. Se evitó repetir una misma dimensión en diferentes vistas. Cada cota se colocó en la vista donde la característica puede interpretarse con mayor claridad.

### P3.4 · ¿Alguna dimensión quedó dentro del contorno de la vista? ¿Qué hizo al respecto?

Cuando una dimensión podía quedar dentro del contorno, se reorganizó su posición para colocarla fuera de la vista y mantener una separación suficiente. Esto facilita la lectura y evita confundir las cotas con las líneas del modelo.

### P3.5 · ¿Qué criterio de organización utilizó para disponer las cotas?

Se organizaron las cotas de mayor a menor, desde las más alejadas hacia las más cercanas al contorno de la pieza. Se evitaron cotas repetidas, ambiguas o innecesarias y se procuró colocar cada dimensión en la vista que comunica mejor la característica correspondiente.

### Evidencias P3

Captura del Drawing con las cotas aplicadas.

![P3: Cotización](S10_P3_Cotizacion_Apellido_Nombre.png)<img width="645" height="451" alt="S10_P3_Cotizacion_Loaisiga_Nohelia.png" src="https://github.com/user-attachments/assets/20a73623-88da-45c1-9081-c815800dd863" />


Detalle de una zona del plano donde se aprecie la organización de las cotas.

![P3: Detalle](S10_P3_Detalle_Apellido_Nombre.png)<img width="379" height="212" alt="S10_P3_Detalle_Loaisiga_Nohelia.png" src="https://github.com/user-attachments/assets/3ba6e132-deed-4c2b-93a1-19b65f6654be" />


---

## P4 — Práctica guiada de plano técnico

### P4.1 · Pieza documentada

- Nombre del diseño: [Nombre real del diseño en Fusion]
- Pieza de referencia: Pieza con base, resalte, perforación y ranura reconstruida en la Semana 9.

### P4.2 · Vistas generadas

| Vista | Información que comunica | Cotas asignadas |
|---|---|---|
| Front | Muestra el perfil escalonado, el resalte y las alturas principales. | Ancho total 80 mm, altura total 32 mm, ancho del resalte 45 mm y altura de la base 12 mm. |
| Top | Muestra la disposición de la base, el resalte, la perforación y la ranura. | Profundidad total 50 mm, diámetro de perforación Ø12 mm, posiciones del centro, dimensiones y posición de la ranura. |
| Right | Confirma la profundidad y las alturas de los diferentes elementos. | Profundidad, alturas y posiciones necesarias para completar la definición de la pieza. |

### P4.3 · Resumen de cotas aplicadas

| Tipo de dimensión | Cantidad | Ejemplo |
|---|---|---|
| Generales | 3 | Ancho total = 80 mm, profundidad total = 50 mm, altura total = 32 mm |
| Parciales | Varias | Ancho del resalte = 45 mm, altura de base = 12 mm, dimensiones de la ranura |
| Funcionales | Varias | Diámetro de perforación = Ø12 mm y posición de su centro |

### P4.4 · ¿El plano contiene información suficiente para fabricar la pieza? ¿Falta algo?

Sí, el objetivo del ejercicio es que el Drawing sea autónomo y contenga las dimensiones necesarias para fabricar la pieza. Debe comunicar las dimensiones generales, el resalte, la perforación y la ranura, incluyendo sus posiciones y tamaños. No se requieren en esta semana cortes, secciones, detalles ni tolerancias, ya que esos contenidos se desarrollarán posteriormente.

### P4.5 · Errores encontrados y correcciones realizadas

| Error detectado | Corrección aplicada | Vista afectada |
|---|---|---|
| Posible falta de espacio para colocar las cotas | Se reorganizó la posición de las vistas dejando separación suficiente para las dimensiones. | Front, Top y Right |
| Riesgo de repetir dimensiones entre vistas | Se dejó cada dimensión en la vista donde la característica resulta más expresiva. | Front, Top y Right |

### Evidencias P4

Drawing completo con vistas y cotas.

![P4: Plano completo](S10_P4_PlanoCompleto_Apellido_Nombre.png)<img width="1359" height="678" alt="S10_P4_PlanoCompleto_Loaisiga_Nohelia.png" src="https://github.com/user-attachments/assets/466e0b39-c542-4b37-89a8-4f4115937bf5" />



Comparación del Drawing con el modelo 3D.

![P4: Verificación](S10_P4_Verificacion_Apellido_Nombre.png)<img width="652" height="461" alt="S10_P4_Verificacion_Loaisiga_Nohelia.png" src="https://github.com/user-attachments/assets/c7e10ee1-b551-462c-8b24-ac3183e3ba1f" />


---

## Reflexión final

La diferencia principal entre documentar una pieza en Semana 9 (reconstrucción desde plano) y documentarla en Semana 10 (generación de vistas desde modelo) es:

En la Semana 9 se reconstruye el modelo tridimensional utilizando como referencia un plano y sus vistas, mientras que en la Semana 10 se parte del modelo 3D ya construido para generar las vistas técnicas y elaborar un Drawing que comunique sus características mediante una acotación normalizada.

Los criterios que utilicé para seleccionar las vistas necesarias fueron:

Seleccioné las vistas que permiten comunicar la geometría de la pieza sin información redundante. Consideré principalmente qué vista muestra mejor las formas, dimensiones y posiciones de las características. Front se utiliza para comunicar el perfil principal, Top para la profundidad, posiciones y características ubicadas en el plano X-Y, y Right para confirmar alturas y profundidades.

Los principios de acotación normalizada que más influyeron en la claridad de mi plano fueron:

Utilicé las dimensiones necesarias para definir la pieza, evitando repetir una misma medida. Las cotas se organizaron de mayor a menor, de afuera hacia adentro, y se colocaron fuera del contorno siempre que fue posible. También se buscó que cada dimensión apareciera en la vista donde la característica pudiera interpretarse con mayor claridad.

Si tuviera que agregar una vista adicional a una de mis piezas, sería:

No sería necesario agregar una vista adicional, porque Front, Top y Right permiten comunicar la geometría principal de las piezas trabajadas. Una vista adicional solamente sería necesaria si apareciera alguna característica que no pudiera interpretarse correctamente con las tres vistas existentes.

## Checklist

- [x] Seleccioné las vistas necesarias y justifiqué cada una.
- [x] Generé las vistas ortogonales correctamente alineadas.
- [x] Configuré formato, orientación y escala de manera coherente.
- [x] Apliqué dimensiones generales, parciales y funcionales.
- [x] Evité cotas repetidas, ambiguas o innecesarias.
- [x] Organice las cotas fuera del contorno de las vistas.
- [x] El plano contiene información suficiente para fabricar la pieza.
- [x] Documenté errores y correcciones sin borrar decisiones iniciales.
- [ ] Las evidencias se visualizan correctamente en GitHub.
- [ ] Los Drawing están disponibles en Fusion Cloud con acceso docente.
- [ ] Completé la reflexión final.

## Cierre del Portafolio Técnico 2

La revisión del portafolio abarca las **semanas 6 a 10**. El plazo para completar y publicar los pendientes de **Semana 10** es el **viernes 25 de septiembre de 2026, a las 11:59 p. m., hora de Costa Rica**. Este plazo no habilita correcciones de las semanas 6 a 9.

Antes del cierre verifique:

- [ ] Las fichas de las semanas 6--10 están completas en `Portafolio/semanaXX/`.
- [ ] Las imágenes y enlaces se visualizan correctamente desde GitHub.
- [ ] Las correcciones están documentadas sin borrar respuestas iniciales.
- [ ] Los modelos están disponibles en Fusion Cloud con acceso docente.
- [ ] Los últimos cambios están publicados en GitHub.

Commit sugerido: `S10 ejercicios Fusion Apellido Nombre`.

Corrección posterior: `S10 correccion Fusion Apellido Nombre`.
