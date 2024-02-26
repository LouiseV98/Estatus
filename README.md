# Monitor de Procesos
 Este script de Python monitorea un proceso específico y lo inicia o detiene según sea necesario. Utiliza las bibliotecas subprocess, time y psutil de Python para lograr esto.

# Uso
 Antes de ejecutar el script, asegúrate de tener Python y las bibliotecas psutil y subprocess instaladas. Puedes instalar las bibliotecas usando pip:
 
pip install psutil subprocess

Para ejecutar el script, simplemente ejecuta el archivo monitor_procesos.py desde la línea de comandos de Python:

python monitor_procesos.py

El script buscará el proceso especificado en nombre_Proceso y, si no está en ejecución, lo iniciará utilizando iniciar_Proceso(ruta_Proceso). Si el proceso ya está en ejecución, lo detendrá utilizando parar_Proceso(nombre_Proceso). El script se ejecutará indefinidamente, verificando el estado del proceso cada 5 segundos.
