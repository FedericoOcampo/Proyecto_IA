# Proyecto_IA
FEDERICO OCAMPO QUICENO - BIOINGENIERÍA - 1000763227

JULIANA PRECIADO CARRANZA - BIOINGENIERÍA - 1002331092

Video de youtube entrega final: https://www.youtube.com/watch?v=DtSMraWIa7U

Video de youtube segunda entrega: https://www.youtube.com/watch?v=-tL2Pkpa7eE

# Guía para Ejecutar el Proyecto en Google Colab con Kaggle

## Paso 1: Obtener credenciales de Kaggle

1. Ingresa a **kaggle.com** e inicia sesión.
2. Haz clic en tu perfil (esquina superior derecha) y selecciona **Settings**.
3. Desplázate hasta la sección **API**.
4. Haz clic en **Create New API Token**.
5. Se descargará un archivo **`kaggle.json`**. Guárdalo en un lugar seguro.

---

## Paso 2: Acceder a Google Colab

1. Abre **Google Colab**.
2. Crea un nuevo notebook o carga tu archivo `.ipynb`.
3. Configura el entorno de ejecución:
   - Ve a **Runtime → Change runtime type**
   - Selecciona **GPU (T4)** para acelerar el entrenamiento.

---

## Paso 3: Preparar el entorno

Ejecuta esta celda primero para instalar dependencias:

`!pip install kaggle lightgbm scikit-learn --quiet`.

Revisa los outputs durante la ejecución para detectar problemas a tiempo.

---
## Paso 4: Configurar Kaggle

1. Ejecuta la celda que solicita subir el archivo `kaggle.json`.  
2. Cuando aparezca el botón **Choose Files**, selecciona tu archivo `kaggle.json`.  
3. Verifica que aparezca el mensaje:
   `kaggle.json configurado correctamente.`

## Paso 5: Ejecutar el flujo completo

- Ejecuta todas las celdas **en orden secuencial**.  
- No omitas ninguna celda; el orden es crucial.  
- Monitorea los outputs para detectar errores a tiempo.


