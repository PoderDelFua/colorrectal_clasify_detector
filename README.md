# 🧠 Colorectal Classify Detector

Repositorio oficial del Trabajo de Fin de Grado (TFG): **Detección y Clasificación de Pólipos Colorrectales** mediante una arquitectura en dos etapas combinando YOLOv8 y VGG19.

---

## 📌 Descripción del Proyecto

Este proyecto implementa un sistema de clasificación de lesiones colónicas en dos etapas:

1. **Detección de pólipos** mediante un modelo YOLOv8 binario (pólipo vs no pólipo).
2. **Clasificación de pólipos detectados** en *adenoma* o *serrado* usando VGG19.

El pipeline completo permite:
- Localizar con alta precisión las lesiones en imágenes endoscópicas.
- Diferenciar entre subtipos clínicamente relevantes.

---

## 🗂️ Estructura del repositorio

```bash
├── PipelineTFG.ipynb               # Integración y pruebas del sistema completo
├── TFG_entrenamiento_completo.ipynb # Entrenamiento del clasificador VGG19
├── VGGTrain.ipynb                  # Entrenamiento + validación VGG con logging
├── dataAugVGG.ipynb                # Aumentación de datos para clasificación
├── data_aug_TFG.ipynb              # Aumentación general del dataset
└── resultados_vgg19/               # Resultados, gráficos y métricas generadas
