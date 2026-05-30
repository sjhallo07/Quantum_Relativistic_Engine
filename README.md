# Quantum Relativistic Engine (AQCS)

## 🌌 Visión General
El **Quantum Relativistic Engine (AQCS)** es una arquitectura avanzada de orquestación de sistemas dinámicos que integra búsqueda semántica (RAG - Retrieval-Augmented Generation) con motores de simulación de caos (Sistemas de Lorenz) y filtrado estocástico (Filtro de Kalman Extendido).

Este repositorio contiene el "cerebro" procedimental capaz de ajustar dinámicamente parámetros de simulación física a través de consultas en lenguaje natural.

---

## 🏗️ Arquitectura del Sistema
El núcleo del AQCS opera mediante un lazo de control cerrado que garantiza la estabilidad del sistema ante la divergencia caótica.

[Image of a closed-loop feedback control system for dynamical systems]

1. **Motor Semántico (Einstein):** Recupera leyes físicas y parámetros desde un corpus documental.
2. **Motor Caótico (Schrödinger):** Proyecta la superposición de trayectorias.
 **Simulación Lorenz/EKF** | ✅ Operativo | Motor de integración numérica (Schrödinger/DeepTest). |
3. **Orquestador (Bridge):** Realiza el colapso de estados y estabiliza mediante el Filtro de Kalman.

---

## 📊 Estado Actual del Proyecto
| Módulo | Estado | Descripción |
| :--- | :--- | :--- |
| **Búsqueda Semántica** | ✅ Operativo | Implementación RAG estable. |
| **Simulación Lorenz/EKF** | ✅ Operativo | Motor de integración numérica validado. |
| **Puente de Orquestación** | ✅ Operativo | Integración total completada (Run All). |
| **Persistencia** | 💾 Activa | Checkpointing habilitado en almacenamiento persistente. |

---

## 🛠️ Estructura de Notebooks
* `Einstein_Semantic_Search_RAG (2.0).ipynb`: Motor de recuperación de parámetros.
* `Schrödinger_superposición.ipynb`: Análisis de trayectorias cuánticas/caóticas.
*`deeptest.ipynb`: Pruebas profundas de estimación del EKF y análisis de caos.
* `bridge_integrated.ipynb`: Orquestador principal del lazo de control.

---

## 🚀 Cómo Empezar
1. Clonar el repositorio.
2. Configurar el entorno virtual: `source venv-aqcs/bin/activate`.
3. Iniciar servidor: `jupyter-lab --ip=0.0.0.0 --port=8081 --no-browser`.
4. Acceder vía túnel SSH en `localhost:8080`.

---
*Documentación generada para el control de estabilidad de sistemas dinámicos no lineales.*
# Quantum_Relativistic_Engine