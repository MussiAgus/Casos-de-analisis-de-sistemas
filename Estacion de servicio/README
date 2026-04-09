# Caso de Estudio: Sistema de Expendio de Combustible Automatizado

Este proyecto detalla el análisis y diseño de un sistema para estaciones de servicio que permite la automatización total del expendio de combustible, integrando pagos electrónicos y programas de beneficios.

## El Problema
El sistema debe gestionar terminales autoservicio donde los conductores operan bocas de expendio. Los desafíos principales incluyen la comunicación en tiempo real con sistemas bancarios para validar tarjetas y la gestión de stock de combustible por tipo (Infinia, Super, etc.).

##  Aspectos Destacados del Análisis
**Lógica de Fidelización:** Implementación de un sistema de puntos (10 puntos cada $100) y beneficios por recurrencia (15% de descuento en la 6ta carga mensual).
**Diagrama de Actividad:** Modelado detallado del flujo de carga, incluyendo bifurcaciones para tarjetas inválidas, falta de stock o aplicación de beneficios.
**Automatización de Reportes:** El diseño contempla la emisión diaria de informes de ventas segmentados por boca de expendio y tipo de combustible.

## Componentes Clave
**Modelo de Dominio:** Relación entre `Conductor`, `Tarjeta de Afinidad`, `Boca de Expendio` y `Combustible`.
**Interfaz Tentativa:** Diseño de la pantalla de la terminal que muestra el precio final con descuentos ya aplicados.
**Casos de Uso:** Incluye el CU "Emitir informe diario" disparado por un `Timer` y la consulta de puntos extendida desde el catálogo de beneficios.
