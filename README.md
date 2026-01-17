# 🎓 Plantilla Maestra LaTeX - Normas APA 7ma Edición (UNMSM)

![LaTeX](https://img.shields.io/badge/LaTeX-Project-green) ![APA 7](https://img.shields.io/badge/Style-APA%207-blue) ![UNMSM](https://img.shields.io/badge/Facultad-Economía-red) ![License](https://img.shields.io/badge/License-MIT-yellow)

> **"Deja de pelear con Word y empieza a escribir ciencia."**

Esta plantilla ha sido desarrollada para estandarizar y profesionalizar la producción académica en la **Facultad de Ciencias Económicas de la Universidad Nacional Mayor de San Marcos (UNMSM)**. Su objetivo es automatizar el 100% del formato exigido (márgenes, citas, bibliografía, índices) para que el estudiante o investigador se enfoque exclusivamente en el contenido.

---

## 🚀 Características Principales

* **Normativa APA 7 Automática:** Configuración preestablecida de márgenes (2.54 cm), fuentes (Times New Roman), interlineado y sangrías.
* **Gestión Bibliográfica:** Integración con `BibTeX` y `apacite` para generar citas y referencias perfectas sin esfuerzo manual.
* **Entorno Econométrico:** Paquetes pre-cargados (`amsmath`, `amsfonts`) para la escritura de modelos matemáticos complejos, sistemas de ecuaciones y matrices.
* **Tablas y Figuras Profesionales:** Configuración de `booktabs` y `caption` para cumplir con el estilo de "sándwich" de APA (Título arriba, Nota abajo, sin líneas verticales).
* **Estructura Modular:** Archivos separados para la Carátula y la Bibliografía, manteniendo el código limpio y ordenado.

## 📂 Estructura del Proyecto

El repositorio contiene los siguientes archivos esenciales:

* `plantilla.tex`: **El cerebro del proyecto.** Archivo principal que orquesta todo el documento.
* `Caratula.tex`: Plantilla de portada adaptada a los estándares de la UNMSM.
* `bibliografia.bib`: Base de datos para tus referencias bibliográficas.
* `unmsm insignia.png`: Logotipo oficial de la universidad (requerido para la portada).

## 🛠️ Requisitos Previos

Para usar esta plantilla necesitas tener instalado:

1.  **Una distribución de LaTeX:**
    * Windows: [MiKTeX](https://miktex.org/) o [TeX Live](https://www.tug.org/texlive/).
    * Mac: [MacTeX](https://www.tug.org/mactex/).
    * Linux: TeX Live (`sudo apt-get install texlive-full`).
2.  **Un editor de texto:**
    * Recomendado: [TeXstudio](https://www.texstudio.org/) (por su facilidad de uso).
    * Alternativa: VS Code con la extensión "LaTeX Workshop".

## ⚡ Guía de Inicio Rápido

1.  **Clona este repositorio:**
    ```bash
        https://github.com/uvargascur-ship-it/PlantillaAPA7LAtex.git
    ```
2.  **Abre el proyecto:** Ejecuta el archivo `plantilla.tex` en tu editor.
3.  **Compila:** Presiona `F5` (en TeXstudio) o el botón de "Build".
    * *Nota:* Si es la primera vez, asegúrate de compilar dos veces para generar correctamente los índices y la bibliografía.
4.  **Personaliza:**
    * Edita `Caratula.tex` con tus datos.
    * Empieza a escribir tu tesis en el cuerpo de `plantilla.tex` puedes cambiar el nombre si gustas según tu criterio.

## 🤝 Contribuciones

Este es un proyecto de código abierto pensado para la comunidad estudiantil. Si encuentras un error o quieres mejorar la plantilla:

1.  Haz un Fork del proyecto.
2.  Crea una rama con tu mejora (`git checkout -b feature/MejoraIncreible`).
3.  Haz Commit (`git commit -m 'Añadí X funcionalidad'`).
4.  Haz Push (`git push origin feature/MejoraIncreible`).
5.  Abre un Pull Request.

## 📄 Créditos y Autor

Desarrollado por **Ulises Vargas**.
* Adaptado para la E.P. de Economía Internacional - UNMSM.
* Lima, Perú (2026).

---
*Hecho con ❤️ y mucho cariño en la comodidad de mi hogar "Huaycán".*
