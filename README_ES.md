# Análisis: Miembros Anuales vs Usuarios Casuales – Cyclistic

## Contexto de Negocio

Cyclistic es una empresa de bicicletas compartidas que busca convertir usuarios casuales en miembros anuales. Comprender las diferencias de comportamiento entre ambos segmentos es clave para diseñar estrategias de marketing efectivas.

---

## Objetivo

Identificar patrones de comportamiento entre miembros anuales y usuarios casuales para apoyar decisiones estratégicas basadas en datos.

---

## Fuente de Datos

- Dataset público de Cyclistic
- Datos procesados usando SQL (Google BigQuery)
- Visualización desarrollada en Power BI

---

## Proceso

1. Limpieza y transformación de datos en BigQuery.
2. Agregaciones por:
   - Tipo de usuario (miembro vs casual)
   - Día de la semana
   - Hora del día
   - Mes
3. Creación de tablas analíticas estructuradas.
4. Diseño del dashboard en Power BI siguiendo principios de jerarquía visual y claridad.

---

## Insights Clave

### Patrones de Comportamiento

- Los miembros anuales generan significativamente más viajes totales que los usuarios casuales.
- Los miembros muestran consistencia durante los días laborales, especialmente a mitad de semana.
- Los usuarios casuales incrementan su actividad hacia el fin de semana.
- Los patrones horarios sugieren comportamiento de desplazamiento laboral en miembros.

### Dinámica Estacional

- La demanda alcanza su punto máximo durante los meses de verano.
- La actividad de usuarios casuales aumenta de forma más marcada en meses cálidos.
- Los miembros mantienen mayor estabilidad a lo largo del año.
- La demanda disminuye en meses fríos para ambos segmentos.

---

## Recomendaciones Estratégicas

- Enfocar campañas de marketing en convertir usuarios casuales de temporada alta en miembros anuales.
- Promover beneficios asociados al uso entre semana para reforzar la propuesta de valor del miembro.
- Lanzar incentivos de suscripción antes del pico de verano.
- Implementar promociones dirigidas en fines de semana para atraer y convertir usuarios casuales.

---

## Vista del Dashboard

Las visualizaciones completas están disponibles en el archivo Power BI incluido en este repositorio.

---

## Herramientas Utilizadas

- SQL (Google BigQuery)
- Power BI
- GitHub
