# Machine-Learning-2025
Cursos de Machine learning de 4 modelos experimentados

# Análisis de Riesgo Crediticio 
![Riesgo Crediticio](https://liberties.imgix.net/images/c2bb6f26-9cb9-4148-bfd4-876fd9981ef1/slapp-01__1_.jpg?ixlib=rails-4.3.1&fm=jpg&auto=format&lossless=true&w=1440&h=902&fit=crop&s=50932f5935ed1d9d81ca8bbae20503a6)

## Descripción del Proyecto

Este proyecto de **Machine Learning** tiene como objetivo analizar el riesgo crediticio de clientes en un banco en Alemania. Se utiliza un conjunto de datos con información financiera y demográfica de los solicitantes de crédito para predecir la probabilidad de incumplimiento de pago.

## Datos Utilizados

El dataset proviene de un banco en Alemania e incluye las siguientes variables:

- **Edad** del solicitante
- **Historial crediticio**
- **Monto del préstamo solicitado**
- **Duración del crédito**
- **Propósito del préstamo**
- **Ingresos**
- **Estado civil** y **sexo**
- **Ocupación**
- **Otros factores financieros**

## Tecnologías Utilizadas

- **Python 3.x**
- **Pandas y NumPy** para manipulación y análisis de datos
- **Scikit-Learn** para modelado predictivo
- **Matplotlib y Seaborn** para visualización de datos
- **Jupyter Notebook** para desarrollo interactivo

## Estructura del Proyecto

```
├── data/                # Conjunto de datos de entrenamiento y prueba
├── notebooks/           # Notebooks Jupyter con el análisis exploratorio y modelado
├── src/                 # Código fuente del modelo de Machine Learning
│   ├── data_processing.py  # Procesamiento y limpieza de datos
│   ├── model.py            # Definición y entrenamiento del modelo
│   ├── evaluation.py       # Evaluación del modelo
├── requirements.txt     # Dependencias del proyecto
├── README.md            # Documentación del proyecto
```

## Instalación y Uso

1. Clonar el repositorio:
   ```sh
   git clone https://github.com/usuario/proyecto-credito.git
   cd proyecto-credito
   ```
2. Crear un entorno virtual y activar:
   ```sh
   python -m venv venv
   source venv/bin/activate  # En Windows: venv\Scripts\activate
   ```
3. Instalar dependencias:
   ```sh
   pip install -r requirements.txt
   ```
4. Ejecutar el análisis y entrenamiento del modelo:
   ```sh
   python src/model.py
   ```

## Resultados

El modelo desarrollado alcanza una **precisión del XX%** en la predicción de clientes con alto riesgo crediticio, permitiendo al banco tomar mejores decisiones en la aprobación de préstamos.

## Contribuciones

Las contribuciones son bienvenidas. Para proponer mejoras, crea un **pull request** o abre un **issue** en el repositorio.

## Licencia

Este proyecto está bajo la licencia **MIT**.


