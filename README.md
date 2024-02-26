# Monitor de Procesos
 Este script de Python monitorea un proceso específico y lo inicia o detiene según sea necesario. Utiliza las bibliotecas subprocess, time y psutil de Python para lograr esto.

# Uso
 Antes de ejecutar el script, asegúrate de tener Python y las bibliotecas psutil y subprocess instaladas. Puedes instalar las bibliotecas usando pip:
 
![carbon](https://github.com/LouiseV98/Estatus/assets/143037181/26ec3935-4eef-469a-adb3-4dc3bb56ff78)

Para ejecutar el script, simplemente ejecuta el archivo monitor_procesos.py desde la línea de comandos de Python:

![carbon (1)](https://github.com/LouiseV98/Estatus/assets/143037181/25a1ad87-b388-4514-b05e-c3ab4002de5c)

El script buscará el proceso especificado en nombre_Proceso y, si no está en ejecución, lo iniciará utilizando iniciar_Proceso(ruta_Proceso). Si el proceso ya está en ejecución, lo detendrá utilizando parar_Proceso(nombre_Proceso). El script se ejecutará indefinidamente, verificando el estado del proceso cada 5 segundos.
