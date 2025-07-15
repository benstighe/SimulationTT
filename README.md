# SimulationTT

# Simulación de Planta de Hidrógeno Verde con PyPSA

## Descripción

Este proyecto implementa una simulación energética horaria para una planta de hidrógeno verde ubicada en la Región de Magallanes, Chile. Utiliza generación solar fotovoltaica, electrolizadores, almacenamiento de hidrógeno y considera demanda constante. Está desarrollado sobre la librería `PyPSA` y estructurado de forma modular en Python para facilitar su extensión.

## Objetivos

- Simular la operación energética en horizontes multianuales (hasta 5 años).
- Estimar generación de hidrógeno a partir de energías renovables.
- Evaluar el despacho óptimo horario usando `LOPF`.
- Calcular métricas clave como producción total, almacenamiento y utilización de electrolizador.
- Permitir la estimación de CAPEX y diseño de componentes según requerimientos de producción.

## Estructura del proyecto

