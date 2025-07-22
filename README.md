# 📊 Análisis de Predicción de Accidentes Cerebrovasculares

## 📝 Descripción del Proyecto

Este proyecto presenta un análisis exploratorio completo del **Healthcare Dataset - Stroke Data**, enfocado en identificar patrones y factores de riesgo asociados con los accidentes cerebrovasculares. El análisis incluye limpieza de datos, exploración estadística, visualizaciones interactivas y conclusiones relevantes para la prevención clínica.

## 🎯 Objetivos

1. **Análisis Exploratorio**: Comprender la estructura y características del dataset
2. **Identificación de Patrones**: Descubrir factores de riesgo significativos
3. **Visualización de Datos**: Crear gráficos informativos y comprensibles
4. **Insights Clínicos**: Generar conclusiones útiles para la prevención de strokes

## 📁 Estructura del Proyecto

```
tarea_1/
├── README.md                           # Este archivo
├── analisis_funcion_continua.ipynb     # Notebook principal con el análisis
├── healthcare-dataset-stroke-data.csv  # Dataset original
└── .venv/                              # Entorno virtual de Python
```

## 📊 Dataset Utilizado

- **Nombre**: Healthcare Dataset - Stroke Data
- **Fuente**: Kaggle
- **Tamaño**: ~5,000 registros de pacientes
- **Variables**: 12 características incluyendo:
  - Información demográfica (edad, género, estado civil)
  - Datos médicos (hipertensión, enfermedades cardíacas, BMI, glucosa)
  - Estilo de vida (tipo de trabajo, residencia, hábito de fumar)
  - Variable objetivo: stroke (0=No, 1=Sí)

## 🔧 Tecnologías y Librerías Utilizadas

- **Python 3.13.5**
- **Pandas**: Manipulación y análisis de datos
- **NumPy**: Operaciones numéricas
- **Matplotlib & Seaborn**: Visualizaciones estáticas
- **Plotly**: Visualizaciones interactivas
- **SymPy**: Análisis de funciones matemáticas
- **Scikit-learn**: Preprocesamiento de datos

## 🚀 Cómo Ejecutar el Proyecto

### Prerrequisitos
- Python 3.7 o superior
- Jupyter Notebook o VS Code con extensión de Python

### Instalación
1. Clona este repositorio:
```bash
git clone https://github.com/ManuelPiano/tarea_1.git
cd tarea_1
```

2. Crea un entorno virtual:
```bash
python -m venv .venv
```

3. Activa el entorno virtual:
```bash
# Windows
.venv\Scripts\activate

# macOS/Linux
source .venv/bin/activate
```

4. Instala las dependencias:
```bash
pip install pandas numpy matplotlib seaborn plotly sympy scikit-learn jupyter
```

5. Abre el notebook:
```bash
jupyter notebook analisis_funcion_continua.ipynb
```

## 📈 Principales Hallazgos

### 🔍 Factores de Riesgo Identificados:

1. **Edad**: Principal predictor - el riesgo aumenta significativamente con la edad
2. **Nivel de Glucosa**: Pacientes con stroke presentan niveles más elevados
3. **Hipertensión**: Comorbilidad fuertemente asociada
4. **Enfermedades Cardíacas**: Factor de riesgo importante
5. **BMI**: Relación positiva con el riesgo de stroke

### 📊 Estadísticas Clave:
- **Prevalencia de Stroke**: ~5% en la población estudiada
- **Edad Promedio con Stroke**: Significativamente mayor
- **Desbalance de Clases**: La mayoría de casos son negativos

### 🎨 Visualizaciones Incluidas:
- Distribución de la variable objetivo
- Histogramas y boxplots de variables numéricas
- Análisis de variables categóricas vs stroke
- Matriz de correlación
- Gráfico interactivo edad vs BMI vs stroke

## 📋 Metodología del Análisis

El proyecto sigue una metodología estructurada de 5 pasos:

1. **Elección del Dataset**: Selección del Healthcare Dataset - Stroke Data
2. **Limpieza y Transformación**: 
   - Verificación de valores faltantes
   - Eliminación de duplicados
   - Conversión de tipos de datos
   - Imputación de valores faltantes

3. **Análisis Exploratorio (EDA)**:
   - Estadísticas descriptivas
   - Análisis de distribuciones
   - Identificación de patrones

4. **Visualización de Resultados**:
   - Gráficos de distribución
   - Análisis comparativo por grupos
   - Visualizaciones interactivas

5. **Documentación y Conclusiones**:
   - Resumen de hallazgos
   - Implicaciones clínicas
   - Próximos pasos sugeridos

## 🔮 Próximos Pasos

1. **Desarrollo de Modelo Predictivo**: Implementar algoritmos de machine learning
2. **Validación Cruzada**: Evaluar la robustez del modelo
3. **Feature Engineering**: Crear nuevas variables derivadas
4. **Análisis de Interpretabilidad**: Explicar las predicciones del modelo
5. **Despliegue**: Crear una aplicación web para predicciones

## 👨‍💻 Autor

**Manuel Piano**
- GitHub: [@ManuelPiano](https://github.com/ManuelPiano)
- Proyecto: Análisis de Datos para Predicción de Stroke

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📞 Contacto

Si tienes preguntas sobre este proyecto, no dudes en abrir un issue en el repositorio.

---
⭐ **Si este proyecto te resultó útil, por favor dale una estrella en GitHub!**
