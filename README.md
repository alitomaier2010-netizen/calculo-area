# Cálculo de Área — Enfoque modular y diseño Top-Down

**Actividad 3 — Enfoque modular y diseño Top-Down** · Laboratorio de Programación · 5.º 3.ª A-B · E.E.S.T. N.º 1 «Eduardo Ader»

Programa en C++ que calcula el **área de un círculo** (`A = π · r²`) dividiendo el problema en módulos:
prototipo de función, filtro de consistencia (el radio debe ser > 0), función `calcularAreaCirculo`
con la constante `const double PI`, y un bonus que dibuja una diana ASCII según el tamaño del radio.

- Estudiante: **Alexis Maier**

## Datos institucionales

- **Institución:** E.E.S.T. N.º 1 «Eduardo Ader» — Vicente López
- **Curso:** 5.º 3.ª A-B
- **Materia:** Laboratorio de Programación (LPR)
- **Profesor:** Prof. York
- **Actividad:** 3 — Enfoque modular y diseño Top-Down

## Presentación de la Actividad

Cálculo del área de un círculo mediante diseño descendente: función con prototipo, filtro de radio válido y salida con diana ASCII.

## Integrantes y roles

| Integrante | Rol / tarea asignada | Aporte individual |
|---|---|---|
| Alexis Maier | Diseño Top-Down, modularización, pruebas de escritorio e informe | [calculo-area](https://github.com/alitomaier2010-netizen/calculo-area) |

## Requisitos e instalación

1. **Git** instalado para clonar el repositorio.
2. **Editor de código** (VS Code con extensiones de C/C++, o Visual Studio Community).
3. **Compilador g++** (MinGW-w64 / MSYS2) agregado al `PATH` del sistema.
4. Clonar y situarse en el directorio:

```bash
git clone https://github.com/alitomaier2010-netizen/calculo-area.git
cd calculo-area
```

## Estructura

```
calculoarea/
├── .gitignore
├── LICENSE
├── README.md
├── capturas/
│   ├── compilacion_area.png
│   └── diagrama_flujo.png
├── docs/
│   └── InformeProyectoCALCULOAREA.pdf
└── src/
    └── main.cpp
```

## Compilar y ejecutar (PowerShell)

```
g++ src/main.cpp -o src/area.exe
.\src\area.exe
```
