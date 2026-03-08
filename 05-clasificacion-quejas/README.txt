Instrucciones para ejecutar el notebook
========================================

1. Abrir el notebook en Google Colab
   - Ir a https://colab.research.google.com
   - File > Upload notebook > seleccionar el archivo .ipynb

2. Configurar la GPU
   - Ir a Runtime > Change runtime type > seleccionar T4 GPU

3. Obtener las credenciales de Kaggle
   - Ir a https://www.kaggle.com
   - Click en tu perfil > Settings > API > Create New Token
   - Se descarga un archivo kaggle.json

4. Ejecutar el notebook
   - Correr las celdas en orden de arriba hacia abajo
   - Cuando pida subir el archivo kaggle.json, seleccionar el que descargaste en el paso 3
   - El dataset se descarga automaticamente desde Kaggle

5. Tiempo estimado
   - La primera corrida (instalacion + descarga del dataset + entrenamiento) tarda entre 20 y 40 minutos dependiendo de la GPU asignada por Colab
   - El entrenamiento del modelo base (3 epochs) tarda aprox 30-40 minutos
   - El experimento con early stopping (hasta 10 epochs) puede tardar un poco mas

Notas
-----
- El notebook esta pensado para correr de principio a fin sin modificar nada
- Si se desconecta Colab hay que volver a correr desde el principio
- Las librerias se instalan en la primera celda del notebook, no hace falta instalar nada antes
- El archivo requirements.txt se incluye como referencia de las dependencias usadas
