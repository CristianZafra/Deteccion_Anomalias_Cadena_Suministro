# Deteccion de Anomalías en la Cadena de Suministro

Este repositorio contiene un cuaderno interactivo para detectar anomalías en operaciones lógicas utilizando algoritmos de aprendizaje automático no supervisado. El objetivo es **identificar posibles fraudes o fallas operativas** dentro de la cadena de suministro a viajes del análisis de variables clave.

---

## Objetivo

- Detectar transacciones lógicas atípicas o sospechosas.
- Aplicar métodos de detección de anomalías como:
  - **bosque de aislamiento**
  - **Factor atípico local (LOF)**
- Prevenir posibles fraudes, errores o ineficiencias operativas en entregas.

---

## Datos utilizados

El archivo `datos_cadena_suministro_anomalias.csv` contiene:

- `ID_Transaccion`: identificador de la transacción logística.
- `Tiempo_Entrega`: tiempo que tomó completar la entrega (horas).
- `Costo_Transporte`: costo reportado del transporte (COP).
- `Cantidad_Entregada`: cantidad de unidades entregadas.
- `Distancia_km`: distancia cubierta en kilómetros.

> Incluye 15 anomalías inyectadas artificiales.

---

## ¿como usar este cuaderno?

1. **Abrir el cuaderno en Google Colab**:
 👉 [Abrir en Colab](https://colab.research.google.com/github/tuusuario/Anomalias_Suministro/blob/main/Deteccion_Anomalias_Cadena_Suministro.ipynb)

2. **Subir el archivo CSV con los datos simulados.**

3. **Ejecutar paso a paso para:**
   - Estandarizar los datos
   - Aplicar modelos de detección
   - Visualizar gráficamente las anomalías
   - Obtener el listado de transacciones sospechosas

---

## Resultados esperados

- Mapa de relaciones entre variables operativas.
- Anomalías detectadas según diferentes modelos.
- Representación visual de comportamientos atípicos.
- Identificación directa de posibles transacciones fraudulentas.

---

## Créditos

Desarrollado por **Cristian Alejandro Zafra Rodríguez**  
Docente e investigador en Ingeniería Industrial  
Universidad Antonio Nariño  
🔬 Enfoque en trazabilidad de operaciones, ciencia de datos y gesción de riesgos operativas.

---

## Licencia 📜

Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo [LICENCIA](LICENCIA) para más detalles.

