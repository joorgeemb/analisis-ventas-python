# Análisis de ventas: depuración y hallazgos

🇬🇧 [Read in English](README.md)

Depuración completa y análisis de un dataset de ventas de 4.215 registros
(2024-2025) con problemas típicos de exportación: columnas numéricas
almacenadas como texto, categorías inconsistentes, fechas en tres formatos
y valores imposibles.

## Resultados

- **Corrección de un error del 1.200%** en el indicador de unidades por
  operación (40,3 registradas frente a 3,0 reales). Cualquier informe
  elaborado sin depuración previa habría comunicado esa cifra.
- **Detección de una política de descuentos no justificada por volumen:**
  el canal mayorista opera con un descuento uniforme del 18% y adquiere
  3,03 unidades por operación, frente a 3,01 en los canales minoristas.

## Contenido

| Archivo | Descripción |
|---|---|
| `limpieza_ventas.ipynb` | Notebook con el proceso completo y los hallazgos |
| `ventas_sucio.csv` | Datos de partida |
| `ventas_limpio.csv` | Conjunto depurado |

## Herramientas

Python · pandas · matplotlib

---

*Dataset simulado con problemas de calidad representativos de exportaciones reales.*
