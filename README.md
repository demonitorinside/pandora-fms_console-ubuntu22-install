# 📦 Instalación de Pandora FMS Console 7.0NG.777 en Ubuntu 22.04

Esta guía proporciona todos los pasos necesarios para instalar y configurar **Pandora FMS Console v7.0NG.777** en un entorno limpio con **Ubuntu 22.04 LTS**.

---

## 📥 Descarga oficial

🔗 Enlace actualizado al archivo de instalación:  
https://github.com/pandorafms/pandorafms/releases/download/v777-LTS/pandorafms_console-7.0NG.777.tar.gz

También puedes obtenerlo directamente desde la página oficial de [Pandora FMS](https://pandorafms.com) tal como se muestra en el video explicativo.

---

## 🛠️ Requisitos

Asegúrate de tener instalados los siguientes servicios:

- Apache2
- MariaDB
- PHP (con extensiones necesarias)

---

## 🚀 Pasos de instalación

El archivo `instalacion_pandora_fms_ubuntu22.txt` contiene todos los comandos necesarios, paso por paso, incluyendo:

- Instalación de dependencias
- Configuración de base de datos
- Descompresión de la consola
- Permisos correctos
- Configuración de Apache
- Acceso vía navegador y limpieza post-instalación

---

## 🌐 Acceso Web

Una vez finalizado el proceso, puedes acceder a Pandora FMS Console desde tu navegador:

```
http://localhost/pandora_console
```

---

## 🧹 Post-instalación

Recuerda eliminar el archivo `install.php` después de finalizar la instalación vía web:

```bash
sudo rm /var/www/html/pandora_console/install.php
```

---

## 📄 Archivo de instalación

Puedes consultar o ejecutar todos los comandos desde este archivo incluido en el repositorio:

📁 [`instalacion_pandora_fms_ubuntu22.txt`](./instalacion_pandora_fms_ubuntu22.txt)

---

## 📷 Vista previa del video explicativo

*(Próximamente)*

---

## 📃 Licencia

Este proyecto está documentado bajo la Licencia MIT. Puedes usar, modificar y compartir libremente.
