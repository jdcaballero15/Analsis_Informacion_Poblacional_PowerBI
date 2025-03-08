# 📸 Capturas del Dashboard en Power BI

Esta carpeta contiene imágenes del dashboard en acción, mostrando cómo funcionan los filtros y visualizaciones interactivas.

## 🖼️ Capturas Incluidas
- `dashboard_general.png` → Vista general del dashboard.
- `filtro_continente.png` → Ejemplo de segmentación por continente y cantidad de poblacion.
- `comparacion_esperanza_vida.png` → Matriz mostrando la  esperanza de vida.
- - `modelado_de_datos.png` → Modelo de datos utilizado.

## 🔍 📊 **Modelo de Datos en Power BI**
El modelado de datos es una parte fundamental en Power BI, ya que define cómo se relacionan las tablas dentro del análisis. La siguiente imagen muestra la estructura utilizada en este proyecto:

![Modelo de Datos](modelado_datos.png)

### 📌 **Estructura del Modelo**
- **`Countries`** 🌎 → Contiene la información de los países y continentes.
- **`Population`** 👥 → Almacena la cantidad de población por país.
- **`Mortalidad Infantil`** ⚠️ → Registra la tasa de mortalidad infantil por país.
- **`Esperanza de Vida`** ⏳ → Contiene la esperanza de vida promedio en cada país.

### 🔗 **Relaciones entre las Tablas**
- **`Countries`** se conecta con todas las demás tablas mediante el campo **"País"**.
- **Relaciones uno a muchos (1:N)** para asegurar que cada país tenga múltiples registros en distintas tablas de métricas.

## 🔎 ¿Cómo interactuar con el dashboard?
1. **Usar filtros** para seleccionar continentes y países específicos.
2. **Explorar la jerarquía de datos** para comparar diferentes métricas.
3. **Visualizar mapas interactivos** para ver la distribución poblacional global.
4. **Analizar gráficos de dispersión** para identificar tendencias en los datos.

🚀 **Este dashboard permite un análisis profundo y visualmente atractivo de la población mundial.**
