
# 📊 Indicadores del Dashboard de Transporte

Este documento describe los indicadores clave utilizados en el tablero de transporte, explicando su propósito, utilidad y cómo contribuyen a la toma de decisiones estratégicas.

---

## 🚚 Rendimiento (Km/Lt)
**Definición:** Mide cuántos kilómetros recorre un vehículo por cada litro de combustible consumido.
**Utilidad:** Permite evaluar la eficiencia de la flota y detectar unidades o rutas con bajo desempeño.
**Decisiones que habilita:** Optimización de rutas, mantenimiento preventivo, renovación de vehículos.

---

## 🛑 Ralenti
**Definición:** Tiempo que un vehículo permanece encendido sin moverse, generando consumo innecesario.
**Utilidad:** Identifica prácticas ineficientes que elevan el gasto operativo.
**Decisiones que habilita:** Capacitación de operadores, ajustes en tiempos de carga/descarga, reducción de emisiones.

---

## 🔍 Desviación Electrónica (Ultragas vs ECM)
**Definición:** Diferencia entre el consumo reportado por el proveedor y el estimado por el sistema electrónico del vehículo.
**Utilidad:** Detecta inconsistencias, errores de medición o posibles fugas/fraudes.
**Decisiones que habilita:** Auditoría de proveedores, revisión de sensores, control de gastos.

---

## 🧭 Hábitos de Manejo
**Definición:** Comportamientos del conductor como velocidad promedio, revoluciones por minuto (RPM) y eficiencia de conducción.
**Utilidad:** Impacta directamente en el consumo de combustible, seguridad y desgaste del vehículo.
**Decisiones que habilita:** Programas de capacitación, incentivos por buen desempeño, mejora continua.

---

## 🧱 Estructura del Modelo de Datos

El modelo de datos está basado en una arquitectura estrella, compuesta por:
- **Tabla de hechos:** viajes y métricas operativas.
- **Dimensiones:** vehículos, rutas, clientes y fechas.

Cada registro representa un viaje realizado, con métricas asociadas como entregas, consumo, distancia y costos.

---

## 🧠 Recomendaciones de Uso del Dashboard

- Utilizar filtros por semana, operador y ruta para análisis detallado.
- Comparar KPIs actuales vs objetivos para identificar brechas.
- Revisar tendencias en hábitos de manejo para implementar mejoras.
- Validar desviaciones electrónicas como parte de auditorías internas.

---

## 🔒 Consideraciones sobre los Datos

Este proyecto fue desarrollado utilizando datos reales proporcionados por una empresa mexicana del sector transporte. Por motivos de confidencialidad:

- Se han eliminado el nombre de la empresa, logotipos y cualquier dato sensible.
- Las fuentes de datos originales no se incluyen en este repositorio.
- Las visualizaciones y métricas presentadas son representativas del análisis realizado, pero no revelan información privada.

Este enfoque permite mostrar las capacidades del dashboard sin comprometer la privacidad ni los acuerdos de confidencialidad.

---

© Hansel Rodríguez, 2025
