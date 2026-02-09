# 🧊 Modelos 3D y Diseño CAD

Este directorio contiene los diseños mecánicos y piezas tridimensionales desarrolladas para dar soporte físico a los proyectos de electrónica y lógica programable (FPGA).

---

## 🖼️ Galería de Diseños

| Modelo | Vista Previa | Descripción |
| :--- | :---: | :--- |
| **Carcasa Nexys 3** | ![Preview](images/case_nexys.png) | Case protector con ventilación y acceso a los switches de la Spartan-6. |
| **Soporte Cámara** | ![Preview](images/camera_mount.png) | Base diseñada para el sensor de visión utilizado en el proyecto de Lane Detection. |
| **Base para Cyclone V** | ![Preview](images/cyclone_base.png) | Soporte de elevación para evitar cortocircuitos en superficies metálicas. |

---

## 🛠️ Especificaciones de Diseño

### Herramientas Utilizadas
* **CAD:** [Indica aquí: Fusion 360 / SolidWorks / Tinkercad] para el modelado paramétrico.
* **Formatos Disponibles:** * `.STL`: Listos para el software de laminado (Slicer).
    * `.STEP`: Formato universal para edición y mejora en cualquier software CAD.

### 🖨️ Parámetros de Impresión Sugeridos
Para asegurar la estabilidad térmica y resistencia de las piezas cerca de las placas FPGA, se recomienda:
* **Material:** PLA (estándar) o PETG (si la placa genera mucho calor).
* **Altura de capa:** 0.2 mm.
* **Relleno (Infill):** 20% - 30% (Patrón de rejilla o giroide).
* **Soportes:** [Sí/No, según la geometría de la pieza].

---

## 🔗 Integración con el Hardware
Muchos de estos modelos están diseñados para encajar milimétricamente con los proyectos de este repositorio:
* El **Soporte de Cámara** es esencial para el flujo de datos del proyecto [Lane Detection](../Lane_detection_C_V/).
* Los adaptadores de riel están pensados para la organización de la [Nexys 3](../Nexys_3/).

> [!TIP]
> Antes de imprimir, verifica la escala en tu Slicer. Los diseños están en **milímetros (mm)**.
