# Fase 3: Integración y validación en Autodesk Fusion 360 Tapa Dispensadora

---

## 1. Información general

| Campo | Información |
|---|---|
| Proyecto | Tapa dispensadora  |
| Fase | 3 (Integración y validación) |
| Software | Autodesk Fusion |
| Estudiante | Nohelia Loaisiga - Tamara Sequeira |
| Curso | Dibujo Técnico Asistido por Computadora |
| Fecha de entrega | Semana 14 |

## 2. Descripción del proyecto

En esta fase se realiza la integración de los componentes modelados previamente (P1, P2 y P3) en un solo archivo de ensamblaje general dentro de Autodesk Fusion. El proceso comprende la aplicación de relaciones de posición y movimiento justificadas (como uniones cilíndricas y rígidas), la verificación de alineación, contacto e interferencias, y la validación geométrica del conjunto funcional de la tapa dispensadora.

## 3. Objetivos

- Integrar los componentes de la tapa dispensadora en un archivo de ensamblaje coherente.
- Aplicar relaciones de posición y movimiento justificadas uniones cilíndricas y rígidas.
- Revisar la alineación, el contacto y la ausencia de interferencias físicas entre las piezas.
- Validar el modelo geométricamente respecto a los requisitos funcionales del dispositivo.

## 4. Herramientas utilizadas

- **Autodesk Fusion:** entorno de ensamblaje e inserción de componentes.
- **GitHub:** almacenamiento y documentación del proyecto en formato Markdown.
- **Capturas de pantalla:** evidencias del proceso de integración y restricciones.

## 5. Integración de componentes del ensamblaje

| Componente | Rol en el Ensamblaje | Tipo de Unión / Relación |
|---|---|---|
| **P1 Base Roscada** | Pieza base de fijación a la bolsa | Elemento fijo / de referencia en el conjunto |
| **P2 Tapa Roscada** | Cuerpo intermedio de manipulación | Unión Cilíndrica (permite giro de ajuste) |
| **P3 Tapón con asa** | Tapa superior de cierre y vertido | Unión Rígida (acoplada sobre la estructura) |

## 6. Procedimiento de integración y validación

### 6.1. Inserción y jerarquía de componentes

Se importan los archivos independientes (P1, P2 y P3) dentro del archivo de ensamblaje general para estructurar el modelo conjunto en Autodesk Fusion.

**Evidencia 1. Ensamblaje general de la tapa dispensadora**

[Ensamblaje general] <img width="1352" height="640" alt="Emnsamblaje_Loaisiga_Nohelia" src="https://github.com/user-attachments/assets/c393ca3c-eb03-4401-baa2-2b288ba5906d" />

<img width="1363" height="645" alt="image" src="https://github.com/user-attachments/assets/2717f079-52d4-4bcb-ac8d-0a8f2ef4207e" />


### 6.2. Aplicación de uniones y restricciones

Se establecen las relaciones mecánicas de posición necesarias para definir el comportamiento del mecanismo, configurando los límites de rotación y movimiento:

**Evidencia 2. Configuración de uniones y límites de movimiento**

[Límites de movimiento y uniones]<img width="1362" height="654" alt="Uniones_Loaisiga_Nohelia" src="https://github.com/user-attachments/assets/ae2eee16-c309-4c72-8d54-55e44a9d4695" />


### 6.3. Revisión de interferencias y validación geométrica

Se verifica mediante la herramienta de análisis de interferencias del software que los componentes encajen de forma correcta, confirmando la ausencia de colisiones geométricas no deseadas entre las roscas y la estructura.

**Evidencia 3. Análisis de interferencias y validación de contactos**

[Análisis de interferencias]<img width="1360" height="650" alt="Interferencias_Loaisiga_Nohelia" src="https://github.com/user-attachments/assets/75d1062d-9647-47a0-af47-07ac2be72db5" />


---

## 7. Dificultades encontradas y soluciones

Durante el proceso de integración del conjunto se abordaron los siguientes aspectos técnicos:

| Dificultad | Acción |
|---|---|
| Alineación de ejes en el ensamblaje | Utilizar referencias de los centroides y orígenes de cada componente para asegurar una concentricidad exacta entre P1, P2 y P3. |
| Definición de tipos de uniones | Configurar correctamente las uniones cilíndricas y rígidas en el árbol de operaciones de Fusion para reflejar el comportamiento funcional esperado. |
| Documentación de validación | Registrar mediante capturas de pantalla el estado final del ensamblaje, los límites de movimiento y el análisis de interferencias. |

**Link:** https://a360.co/4zenpCg
