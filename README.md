

# Cómo descargar e instalar XAMPP en los diferentes sistemas operativos 

## INSTALACIÓN DE XAMPP EN UBUNTU. (APACHE, MYSQL,PHP)

XAMPP, aunque es muy popular en sistemas Windows, también puede instalarse en sistemas Linux como Ubuntu. Aquí tienes una guía básica para instalar XAMPP en Ubuntu:

1. **Descargar XAMPP:**
   - Visita el sitio web oficial de XAMPP: [https://www.apachefriends.org/index.html](https://www.apachefriends.org/index.html)
   - Descarga la versión de XAMPP para Linux.

2. **Cambiar Permisos del Archivo Descargado:**
   - Abre una terminal y navega al directorio donde descargaste el archivo XAMPP.
   - Asegúrate de que el archivo sea ejecutable con el siguiente comando:
     ```bash
     chmod +x nombre_del_archivo_descargado.run 
     ```
   - [https://www.apachefriends.org/es/faq_linux.html](https://www.apachefriends.org/es/faq_linux.html) 

3. **Instalar XAMPP:**
   - Ejecuta el instalador con el siguiente comando:
     ```bash
     sudo ./nombre_del_archivo_descargado.run
     ```
   - Sigue las instrucciones en pantalla para completar la instalación. Puedes instalar XAMPP en el directorio que prefieras (por ejemplo, `/opt`).

4. **Iniciar XAMPP:**
   - Después de la instalación, puedes iniciar XAMPP ejecutando el siguiente comando:
     ```bash
     sudo /opt/lampp/lampp start
     ```
   - Esto iniciará Apache y MySQL. Puedes verificar si están en funcionamiento visitando `http://localhost` en tu navegador.

5. **Detener XAMPP:**
   - Puedes detener XAMPP con el siguiente comando:
     ```bash
     sudo /opt/lampp/lampp stop
     ```

6. **Acceder a phpMyAdmin:**
   - phpMyAdmin debería estar disponible en `http://localhost/phpmyadmin`.

Recuerda que XAMPP está destinado principalmente a entornos de desarrollo local. Si planeas usarlo en un entorno de producción, asegúrate de configurar adecuadamente la seguridad y seguir las mejores prácticas de seguridad.

Ten en cuenta que la información puede cambiar con el tiempo, y siempre es recomendable consultar la documentación oficial de XAMPP o el sitio web del proyecto para obtener información más actualizada sobre la instalación y configuración en Linux.

### _EN MI CASO INSTALÉ XAMPP VERSION= 8.0.28_

XAMPP 8.0.28 / PHP 8.0.28

En XAMPP para Linux, no existe un panel de control gráfico predeterminado como en las versiones de XAMPP para Windows. En lugar de eso, puedes controlar los servicios de XAMPP utilizando comandos en la terminal. Aquí te dejo algunos comandos básicos:

1. **Iniciar XAMPP:**
   ```bash
   sudo /opt/lampp/lampp start
   ```

2. **Detener XAMPP:**
   ```bash
   sudo /opt/lampp/lampp stop
   ```

3. **Reiniciar XAMPP:**
   ```bash
   sudo /opt/lampp/lampp restart
   ```

4. **Verificar el Estado de XAMPP:**
   ```bash
   sudo /opt/lampp/lampp status
   ```

En estos comandos, `/opt/lampp/` es la ruta predeterminada de instalación de XAMPP en Linux. Si has instalado XAMPP en un directorio diferente, debes ajustar la ruta en consecuencia.

Si prefieres una interfaz gráfica para controlar servicios, puedes utilizar herramientas como `gnome-system-monitor` para ver los procesos en ejecución o instalar aplicaciones específicas para el manejo de servicios en tu entorno gráfico.

Ten en cuenta que esta información se basa en la configuración predeterminada de XAMPP y puede variar si has personalizado la instalación o estás utilizando una distribución diferente de XAMPP.
