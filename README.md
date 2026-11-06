# TeKnical May Cry (TmC) 🎮

[![C++](https://img.shields.io/badge/Language-C%2B%2B-blue.svg)](https://isocpp.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Norms: APA v7](https://img.shields.io/badge/Docs-APA%20v7-green.svg)](#)

Repositorio oficial del **Proyecto Integrador Anual (P.I.A.)** para la asignatura **Laboratorio de Programación (LPR)** en la **Escuela de Educación Secundaria Técnica N.º 1 "Eduardo Ader"**.

---

## 📌 Descripción General

**TeKnical May Cry (TmC)** es un videojuego de temática de recreación escolar y combate técnico en 2D/3D desarrollado como proyecto integrador. El proyecto implementa una arquitectura modular enfocada en el rendimiento a bajo y medio nivel, integrando estructuras de datos complejas, gestión directa de memoria mediante punteros, interacción con bases de datos y persistencia.

---

## 👥 Equipo de Desarrollo y Roles

| Estudiante | Rol Principal | GitHub User |
| :--- | :--- | :--- |
| **Ferrari, Ulises** | Líder de Proyecto, Investigación y Formato APA v7 | [@Ferraribip](https://github.com/Ferraribip) |
| **Del Pino, Lucas** | Programación Backend y Pruebas C++ | — |
| **Mattia, Federico** | Gestión de Repositorio Dual-Remote (GitHub / GitLab) | — |
| **Orué, Máximo** | Control de Calidad y Traza de Memoria | — |

### 👨‍🏫 Cuerpo Docente / Revisores
* **Prof. Mansilla Muñoz, York Elías** ([@webappdeved](https://github.com/webappdeved))
* **Prof. Ganduglia, Yamil De Jesus** ([@yamilganduglia-gh](https://github.com/yamilganduglia-gh))

---

## 📁 Estructura del Repositorio

```text
tmc/
├── .vscode/               # Configuraciones del IDE (excluido en .gitignore)
├── capturas/              # Evidencias visuales para informes técnicos
├── docs/                  # Documentación académica e informes APA v7
├── include/               # Archivos de cabecera (.h / .hpp)
├── src/                   # Código fuente principal (.cpp / .cs)
│   └── main.cpp
├── .gitignore             # Filtros de exclusión de binarios y temporales
├── CHANGELOG.md           # Historial de versiones del proyecto
├── CODE_OF_CONDUCT.md     # Código de conducta para colaboradores
├── CONTRIBUTING.md        # Guía de contribución y flujo de Git
├── LICENSE                # Licencia de uso del código
├── README.md              # Documentación principal
└── SECURITY.md            # Políticas de reporte de vulnerabilidades
```

---

## 🛠️ Requisitos e Instalación

### Prerrequisitos
* Compilador GCC/G++ (`g++` v11.0 o superior) o entorno MSVC.
* Git cliente instalado para control de versiones.

### Compilación Básica
```bash
# Clonar el repositorio
git clone https://github.com/Ferraribip/tmc.git

# Acceder al directorio
cd tmc

# Compilar el módulo principal
g++ -std=c++17 src/main.cpp -Iinclude -o bin/tmc_app

# Ejecutar
./bin/tmc_app
```

---

## 📜 Licencia

Este proyecto se distribuye bajo la licencia **MIT**. Consulta el archivo `LICENSE` para más detalles.

*EEST N.º 1 "Eduardo Ader" — Vicente López, Buenos Aires, Argentina.*