# Sistema de Diagnóstico Visual de Riesgo en Pasillos, Escaleras y Zonas de Circulación Universitaria

**Grupo 6** - Inteligencia Artificial  
**Universidad de Guayaquil**

---

## Integrantes
- Reyes Cirro Rubén Guillermo
- Pedro Antonio Castillo Cucián
- Chasi Hernández Marina del Pilar
- John [Apellido]

---

## Descripción del Proyecto

Sistema de diagnóstico visual que clasifica imágenes de pasillos, escaleras y zonas de circulación en 4 niveles de riesgo, y detecta evidencias visuales específicas (objetos, cables, obstrucciones) utilizando YOLO.

### Clases de Clasificación
- 🟢 zona_segura
- 🟡 riesgo_bajo
- 🟠 riesgo_alto
- 🔴 riesgo_critico

### Clases YOLO (Detección de Evidencias)
| Clase | Descripción |
|-------|-------------|
| cable_expuesto | Cable o manguera visible en zona de circulación |
| silla_bloqueando | Silla o mobiliario obstruyendo el paso |
| caja_en_pasillo | Caja u objeto similar en el suelo |
| salida_bloqueada | Salida de emergencia obstruida |
| escalera_obstruida | Escalón con objetos u obstrucción |
| piso_mojado | Superficie húmeda o con líquido visible |
| objeto_en_piso | Objeto pequeño suelto en el suelo |

---

## Dataset
- **174 imágenes originales anotadas**
- **418 imágenes con augmentación (3x)**
- **7 clases YOLO**
- **Formato YOLOv8**

---

## Estructura del Proyecto
