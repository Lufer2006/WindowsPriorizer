# WindowsPriorizer

Descripción del Script
El script es un optimizador de Windows que realiza cambios en el sistema operativo según el modo seleccionado por el usuario. Aquí te explico qué hace cada modo:

• Rendimiento Extremo:

Desactiva servicios innecesarios como wuauserv (Windows Update) y SysMain (Superfetch) para liberar recursos del sistema.
Limpia archivos temporales para liberar espacio en disco.
Permite al usuario priorizar un programa/juego específico en tiempo real, lo que le da la máxima prioridad de CPU.

• Rendimiento:

Desactiva algunos servicios menos críticos para mejorar el rendimiento.
Limpia archivos temporales.
Permite al usuario priorizar un programa/juego específico con prioridad alta.

• Estabilidad:
Ofrece dos opciones: estabilidad para programas en primer plano o en segundo plano.
Ajusta el plan de energía a equilibrado o mínimo según la opción seleccionada para mejorar la estabilidad del sistema.

•Ahorro de Batería:

Activa el plan de energía de ahorro máximo para reducir el consumo de energía, lo cual es útil en laptops.

# Recomendaciones de Python
Versión Recomendada: Es recomendable usar Python 3.6 o superior para ejecutar este script.

# Instalación de Python
Descargar Python:
Ve al sitio oficial de Python: python.org.
Haz clic en "Downloads" y selecciona la versión adecuada para tu sistema operativo (Windows, macOS, Linux).
Instalar Python en Windows:

Ejecuta el instalador descargado.
Asegúrate de marcar la opción "Add Python to PATH" para que puedas ejecutar Python desde la línea de comandos.
Haz clic en "Install Now" y sigue las instrucciones del instalador.
Verificar la Instalación:

Abre una terminal o símbolo del sistema.
Escribe python --version y presiona Enter. Deberías ver la versión de Python instalada.

Instalar Módulos Adicionales (si es necesario):

Puedes instalar módulos adicionales usando pip, el gestor de paquetes de Python.
Por ejemplo, para instalar un módulo, usa el comando: pip install nombre_del_modulo.
Ejecución del Script
Guardar el Script: Copia el código del script y guárdalo en un archivo con extensión .py, por ejemplo, optimizador_windows.py.

• Ejecutar el Script:

Abre una terminal o símbolo del sistema.
Navega hasta el directorio donde guardaste el archivo.
Ejecuta el script con el comando: python optimizador_windows.py.

# Nota: Este script debe ejecutarse con permisos de administrador para que los cambios en el sistema tengan efecto. Asegúrate de entender cada comando antes de ejecutarlo, ya que modificar configuraciones del sistema puede causar problemas si no se hace correctamente.
