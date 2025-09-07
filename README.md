# hurricane-modeling
Simulación de flujos de vórtice y sumidero aplicados al Huracán Isaac.

# 🌪️ Modelado Matemático de Huracanes con Python y Jupyter

Este repositorio contiene un **estudio simplificado del campo de velocidades de un huracán**, implementado en **Python mediante Jupyter Notebook**.  
El modelo se construye bajo supuestos de **flujo ideal, incompresible, estacionario y bidimensional**, lo que permite una representación analítica del huracán como la superposición de dos flujos elementales:

- **Flujo de vórtice:** describe la rotación del aire en torno al ojo del huracán.
- **Flujo de sumidero:** describe el movimiento radial del aire hacia el centro.

---

## 📖 Contenido del repositorio

- `Modelo_Huracanes.ipynb` → Notebook principal con deducciones teóricas, implementación en Python y visualización.
- `Modelo_Huracanes.pdf` → Documento en formato PDF con la formalización matemática, resultados y figuras.
- (Opcional) Carpeta `img/` → figuras y gráficas generadas.

---

## ⚙️ Requisitos

El notebook utiliza únicamente librerías básicas de Python:

```bash
pip install numpy matplotlib

