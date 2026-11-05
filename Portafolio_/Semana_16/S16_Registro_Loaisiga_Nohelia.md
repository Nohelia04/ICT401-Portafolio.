# Ficha de registro: Laboratorio Integrador II-B

**Curso:** ICT401 – Dibujo Técnico Asistido por Computadora
**Semana:** 16
**Laboratorio:** Integrador II-B
**Valor del laboratorio:** 10 %
**Estudiante o equipo:** Loaisiga Nohelia, Sequeira Tamara
**Proyecto:** Tapa Dispensadora para Bolsas de Granos
**Fecha:** 05 de noviembre de 2026
**Versión inicial:** `Proyecto_Integrador_Emsamblaje.`
**Versión evaluada:** `Proyecto_Integrador_Emsamblaje222.`

## Propósito y alcance

Esta ficha registra la evidencia del Laboratorio Integrador II-B: integración del modelo, ensamblaje, documentación, exportaciones, tolerancias introductorias y control dimensional básico.

La ficha **no sustituye la entrega de la Fase 4 del Proyecto Integrador**, cuyo valor oficial es 7 % y cuyos requisitos se definen en su propia rúbrica. Algunas evidencias pueden reutilizarse si cumplen ambos propósitos, pero deben conservarse separados el registro del laboratorio y la entrega de la fase.

No se evalúan mediante esta ficha la fabricación física, la metrología avanzada, los procesos completos de manufactura ni la presentación final de la Semana 17.

## Instrucciones

1. Complete la ficha durante las cuatro lecciones.
2. Registre la versión exacta del proyecto utilizada.
3. Conserve una copia de respaldo antes de modificar o exportar.
4. Registre el propósito, formato y comprobación de cada archivo de salida.
5. No invente tolerancias cuando no estén indicadas.
6. Cada medición debe incluir característica, unidad, método y limitación.
7. Use nombres o rutas verificables para las evidencias.

## Lección 1. Auditoría del proyecto y documentación

| Elemento | Registro |
|---|---|
| Archivo o enlace principal |  Proyecto_integrador_ensamblaje222 |
| Versión revisada | Proyecto_integrador_ensamblaje222 |
| Fecha de la versión | 05-11-2026|
| Unidades del proyecto | mm |
| Plano o Drawing utilizado | Proyecto_integrador_ensamblaje222 Dibujo Hojas 1 y 2 |
| Ensamblaje utilizado, si corresponde | Proyecto_integrador_ensamblaje222 |
| Lista básica de componentes, si corresponde | 3 componentes P1, P2 y P3 |
| Ubicación del respaldo inicial | Proyecto_integrador_ensamblaje |
| Problema prioritario encontrado | No se muestra la el collar |

### Revisión de coherencia

| Control | Sí | No | N.A. | Evidencia o corrección |
|---|:---:|:---:|:---:|---|
| El modelo y la documentación corresponden a la misma versión. | [x] | [ ] | [ ] | `Proyecto_integrador_ensamblaje222` y `Proyecto_integrador_ensamblaje222  |
| El plano contiene las vistas, cotas y datos que corresponden. | [x] | [ ] | [ ] | Vista isométrica con globos (Hoja 1) y vistas de alzado/planta acotadas (Hoja 2) |
| El cajetín o identificación está completo según la plantilla. | [x] | [ ] | [ ] | Cajetín diligenciado con fecha `5/11/2026` y título del proyecto |
| La lista coincide con el ensamblaje, cuando corresponde. | [x] | [ ] | [ ] | 3 ítems en la `Lista de piezas` coinciden con `P1`, `P2` y `P3` en el Browser |
| La orientación y la escala son coherentes. | [x] | [ ] | [ ] | Vistas ortogonales alineadas, acotadas en mm y a escala adecuada |

**Captura del estado inicial:** `evidencias/S16_E1_Estado_Inicial.png`  <img width="1360" height="687" alt="S16_E1_Estado_Inicial.png" src="https://github.com/user-attachments/assets/6f12c292-3a55-4c9b-9ed9-223a09782481" />

**Corrección prioritaria antes de exportar:** Renombrar el archivo de dibujo para corregir el error tipográfico.

## Lección 2. Exportaciones y comprobación de archivos

| Formato | Propósito | Configuración relevante | Archivo generado | Comprobado |
|---|---|---|---|:---:|
| STL | Malla para impresión 3D | `Save As Mesh`, unidades en mm | Proyecto_integrador_ensamblaje222.stl [x] |
| STEP | Intercambio de geometría 3D CAD | `File > Export`, componente raíz seleccionado |Proyecto_integrador_ensamblaje222.step| [x] |
| DXF | Perfil 2D para corte/fabricación | Sketch de la vista principal exportado | Proyecto_integrador_ensamblaje222.dxf | [x] |
| PDF | Documentación del plano técnico | `Export > PDF`, todas las hojas | Proyecto_integrador_ensamblaje222Dibujo.pdf | [x] |
| Otro | N.A. | N.A. | N.A. | [ ] |

### Comprobación de cada salida

| Archivo | Geometría | Unidades | Escala/orientación | Versión | Ubicación | Resultado |
|---|:---:|:---:|:---:|:---:|---|---|
| Proyecto_integrador_ensamblaje222Dibujo.pdf  | [x] | [x] | [x] | [x] | `salidas/` | 2 hojas completas y legibles |
| Proyecto_integrador_ensamblaje222.step | [x] | [x] | [x] | [x] | `salidas/` | Geometría 3D sólida e íntegra |
| Proyecto_integrador_ensamblaje222.stl  | [x] | [x] | [x] | [x] | `salidas/` | Malla cerrada apta para impresión 3D |

**Archivo o captura de comprobación:** `evidencias/S16_E2_Exportaciones.png`  <img width="534" height="202" alt="S16_E2_Exportaciones.png" src="https://github.com/user-attachments/assets/4070a5a5-0e36-453f-a166-09d0171026ff" />

**Discrepancia encontrada:** Nombre del archivo de dibujo con errata en la pestaña de Fusion.  
**Corrección aplicada:** Renombrado de archivo y actualización de vistas antes de la exportación final.

## Lección 3. Tolerancias y control dimensional básico

| Característica | Dimensión nominal | Tolerancia | Límite inferior | Límite superior | Valor observado | Unidad |
|---|---:|---:|---:|---:|---:|---|
| Diámetro exterior de la base | 84,00 | ±0,20 | 83,80 | 84,20 | 84,06 | mm |
| Altura total | 22,00 | ±0,15 | 21,85 | 22,15 | 22,00 | mm |
| Ajuste de unión rígida P3 (Tapa) | Nominal | ±0,10 | -0,10 | +0,10 | 0,00 | mm |
| Diámetro del asa superior | 15,00 | ±0,20 | 14,80 | 15,20 | 15,00 | mm |

### Método y resultado

| Característica | Herramienta o método | Resultado | Limitación de la comprobación |
|---|---|---|---|
| Diámetro exterior base | `Inspect > Measure` en Fusion / Cota en plano | Conforme | Medición CAD digital; no evalúa variación por proceso de manufactura |
| Altura total | `Inspect > Measure` cara a cara | Conforme | Medición en modelo ideal sin considerar rugosidad superficial |
| Alineación de la unión | `Browser > Uniones > Rígida 3` | Conforme | Comprobación geométrica virtual; no certifica interferencias físicas de ensamble |
| Ajuste cilíndrico | `Browser > Uniones > Cilíndrica 2` | Conforme | Simulación cinemática CAD; no mide holguras ni fricción real |

**Ejemplo de cálculo:**  
Dimensión nominal = 84,00mm  
Valor medido = 84,06mm
Desviación = 84,06 - 84,00 = +0,06 mm Dentro del rango permitido de +-0,20mm

**Captura o referencia de la medición:** `evidencias/S16_E3_Control_Dimensional.png` <img width="1365" height="691" alt="S16_E3_Control_Dimensional.png" src="https://github.com/user-attachments/assets/1ac5db9b-e098-483a-a89c-b23ea91a250a" />
 
**¿Qué valor o criterio no pudo comprobarse?** La rugosidad superficial y la tolerancia geométrica de concentricidad entre el cuerpo base y la tapa.

## Lección 4. Integración y cierre del laboratorio

### Correcciones finales

| Problema | Acción aplicada | Resultado | Evidencia |
|---|---|---|---|
| ProblemaAcción aplicadaResultadoEvidenciaErrata en el nombre del archivo de dibujo |Renombrar el archivo de dibujo a Proyecto_integrador_ensamblaje222 Dibujo |Nombre corregido y sincronizado en las pestañas | `S16_E4.png` |
|  |  |  |  |
|  |  |  |  |
<img width="371" height="24" alt="S16_E4.png" src="https://github.com/user-attachments/assets/a868905f-2775-4814-a01b-796a0ba8ca80" />

### Checklist del Laboratorio II-B

- [x] La versión del modelo y la documentación coincide.
- [x] El plano final fue revisado.
- [x] La lista básica coincide con el ensamblaje, cuando corresponde.
- [x] Cada archivo exportado tiene un propósito registrado.
- [x] Las salidas fueron revisadas fuera del comando de exportación.
- [x] Se registraron unidades, escala, orientación y versión.
- [x] Se realizó al menos una comprobación dimensional básica.
- [x] Las tolerancias introductorias fueron interpretadas sin inventar valores.
- [x] Se registraron discrepancias y correcciones.
- [x] La versión evaluada fue respaldada.
- [x] La ficha está completa.

### Evidencias finales del laboratorio

| Evidencia | Nombre o ruta | Completa | Observaciones |
|---|---|:---:|---|
| Estado inicial y auditoría | `evidencias/S16_E1_Estado_Inicial.png` | [x] | Modelo 3D activo en Fusion |
| Exportaciones y comprobación | `evidencias/S16_E2_Exportaciones.png` | [x] | Archivos PDF/STEP/STL validados |
| Control dimensional | `evidencias/S16_E3_Control_Dimensional.png` | [x] | Cota de 84,06 mm verificada |
| Plano final o documentación | `evidencias/S16_E4_Plano_Final.pdf` | [x] | Error en el nombre |
| Lista básica, si corresponde | `evidencias/S16_E1_Parts_List.png` | [x] | Lista con P1, P2 y P3 |
| Archivo de respaldo | `salidas/Proyecto_integrador_ensamblaje222.f3d` | [x] | Respaldo nativo de Fusion |
| Ficha completa | `Ficha_Laboratorio_Integrador_IIB.md` | [x] | Ficha diligenciada en su totalidad |

## Separación de la Fase 4

**¿Qué producto o archivo adicional exige la rúbrica de la Fase 4?**  
La memoria descriptiva escrita en PDF con la justificación formal del diseño, análisis de ensamblaje y la presentación ejecutiva.

**¿Qué evidencia de esta ficha puede reutilizarse en la Fase 4?**  
El plano de documentación técnica en PDF, la lista de piezas (`Parts List`) y los archivos neutros exportados (STEP/STL).

**¿Qué requisito de la Fase 4 todavía no está cubierto por esta ficha?**  
La presentación oral de la Semana 17, el análisis funcional detallado y la justificación de la selección de materiales.

## Cierre reflexivo

**¿Qué exportación requirió más comprobación y por qué?**  
La exportación a PDF del plano, ya que exigió verificar la legibilidad de las cotas en la Hoja 2, la alineación de la lista de piezas y la correspondencia de los globos (1, 2, 3) con los componentes de la vista isométrica.

**¿Qué diferencia encontró entre el valor nominal, la tolerancia y el valor observado?**  
Se observó un valor de 84,06 mm frente al nominal de 84,00 mm, representando una variación de +0,06 mm, la cual se encuentra dentro de la tolerancia admisible de $\pm 0,20\text{ mm}$.

**¿Qué corrección mejoró la confiabilidad del producto técnico?**  
La adición y verificación formal de las uniones (`Cilíndrica 2` y `Rígida 3`) en el árbol del ensamblaje, garantizando la correcta alineación sin interferencias mecánicas.

**¿Qué limitación debe comunicar antes de considerar terminada la Fase 4?**  
Que la evaluación dimensional se realizó digitalmente mediante inspección CAD (`Inspect > Measure`), requiriendo validación metrológica sobre un prototipo físico antes de la producción.
