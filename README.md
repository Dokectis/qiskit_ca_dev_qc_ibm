# Qiskit Quantum Computing Development Labs | IBM Quantum

## EN

This repository is a personal development space for exploring quantum computing with **Qiskit** and the **IBM Quantum** ecosystem. It is organized as a practical notebook collection focused on simulator validation, circuit design, foundational concepts, and hands-on experimentation.

The current workspace is centered on `01_fundamentals/`, which contains the active baseline notebooks for environment checks, Bell-state construction, and sandbox-style circuit testing.

### Objective

Build a clean and reusable learning path for:

- verifying the local Qiskit environment
- testing Aer simulator execution paths
- understanding core quantum circuit concepts
- documenting practical experiments in notebook form

### Tech Stack

- **SDK:** Qiskit Python 2.3.x
- **Simulator:** Qiskit Aer / `AerSimulator`
- **Environment:** Jupyter Notebooks, Python 3.x
- **Target Ecosystem:** IBM Quantum

### Project Structure

#### `01_fundamentals/`

- [00_env_test.ipynb](01_fundamentals/00_env_test.ipynb)  
  Environment verification notebook. Checks the installed Qiskit version, lists Aer backends, and runs a minimal simulator sanity test.

- [00_qiskit_sandbox_v1.ipynb](01_fundamentals/00_qiskit_sandbox_v1.ipynb)  
  Early sandbox notebook for basic circuit experiments, including a single-qubit interference-style example and first simulator runs.

- [00_qiskit_sandbox_v2.ipynb](01_fundamentals/00_qiskit_sandbox_v2.ipynb)  
  Development sandbox for rapid circuit prototyping, `Statevector` validation, backend checks, debugging, and `AerSimulator` testing.

- [01_bell_state.ipynb](01_fundamentals/01_bell_state.ipynb)  
  Foundational notebook for creating and simulating the Bell state `|Phi+>`, including measurement and histogram-based interpretation.

- [19102025_ca_Qiskit_practice_QC.ipynb](01_fundamentals/19102025_ca_Qiskit_practice_QC.ipynb)  
  Practice notebook with introductory circuit construction, register creation, Bell-state examples, and basic visualization exercises.

### Notes

- Notebook naming still reflects iterative development history.
- Some notebooks are learning labs, while others are experimental sandboxes.
- The README is aligned to the files currently present in the repository.

---

## ES

Este repositorio es un espacio personal de desarrollo para explorar computacion cuantica con **Qiskit** y el ecosistema de **IBM Quantum**. Esta organizado como una coleccion practica de notebooks enfocada en validacion del simulador, diseno de circuitos, conceptos fundamentales y experimentacion aplicada.

El workspace actual esta centrado en `01_fundamentals/`, que contiene los notebooks base activos para pruebas de entorno, construccion de estados de Bell y pruebas tipo sandbox de circuitos cuanticos.

### Objetivo

Construir una ruta de aprendizaje limpia y reutilizable para:

- verificar el entorno local de Qiskit
- probar rutas de ejecucion del simulador Aer
- entender conceptos centrales de circuitos cuanticos
- documentar experimentos practicos en formato notebook

### Stack Tecnologico

- **SDK:** Qiskit Python 2.3.x
- **Simulador:** Qiskit Aer / `AerSimulator`
- **Entorno:** Jupyter Notebooks, Python 3.x
- **Ecosistema objetivo:** IBM Quantum

### Estructura del Proyecto

#### `01_fundamentals/`

- [00_env_test.ipynb](01_fundamentals/00_env_test.ipynb)  
  Notebook de verificacion del entorno. Revisa la version instalada de Qiskit, lista los backends de Aer y ejecuta una prueba minima del simulador.

- [00_qiskit_sandbox_v1.ipynb](01_fundamentals/00_qiskit_sandbox_v1.ipynb)  
  Sandbox inicial para experimentos basicos de circuitos, incluyendo un ejemplo tipo interferencia de un solo qubit y primeras ejecuciones con simulador.

- [00_qiskit_sandbox_v2.ipynb](01_fundamentals/00_qiskit_sandbox_v2.ipynb)  
  Sandbox de desarrollo para prototipado rapido de circuitos, validacion con `Statevector`, comprobaciones de backends, depuracion y pruebas con `AerSimulator`.

- [01_bell_state.ipynb](01_fundamentals/01_bell_state.ipynb)  
  Notebook fundamental para crear y simular el estado de Bell `|Phi+>`, incluyendo mediciones e interpretacion basada en histogramas.

- [19102025_ca_Qiskit_practice_QC.ipynb](01_fundamentals/19102025_ca_Qiskit_practice_QC.ipynb)  
  Notebook de practica con construccion introductoria de circuitos, creacion de registros, ejemplos de estado de Bell y ejercicios basicos de visualizacion.

### Notas

- Los nombres de algunos notebooks aun reflejan el historial iterativo de desarrollo.
- Algunos notebooks son laboratorios de aprendizaje y otros son sandboxes experimentales.
- Este README esta alineado con los archivos que existen actualmente en el repositorio.

### Author

**Carlos Araque L.**  
Senior Data Engineer | Databricks Certified | Quantum Computing Learner and Builder
