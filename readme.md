# Taller: Desplegando un tablero en la nube

Miguel Angel Cardona Chamorro

---

## 1. Configuración del repositorio local con Git
Breve descripción de la configuración inicial de Git y creación del repositorio local.

**Capturas requeridas:**
- Ejecución de `git init`
![alt text](image.png)
- Configuración de usuario y correo en Git
![alt text](image-1.png)
- Modificación en la función `load_data()` en `app.py`
![alt text](image-2.png)
- Tablero corriendo en local en el navegador
![alt text](image-3.png)
![alt text](image-4.png)

---

## 2. Subida del código a GitHub
[Repositorio de GitHub](https://github.com/micardona96/taller1_dash)

**Capturas requeridas:**
- Vista del repositorio en GitHub con todos los archivos (`app.py`, `datos_energia.csv`, carpeta `assets`)
![alt text](image-5.png)
- Historial de commits
![alt text](image-6.png)

---

## 3. Configuración de la máquina virtual
**Capturas requeridas:**
![alt text](image-7.png)
- Conexión a la máquina virtual por SSH
![alt text](image-8.png)
- Ejecución de `sudo yum update -y`
![alt text](image-9.png)
- Instalación de Python, pip, pandas, dash, gunicorn, git
![alt text](image-12.png)
- Carpeta clonada desde el repositorio remoto en la máquina virtual (`ls` mostrando los archivos)
![alt text](image-11.png)

---

## 4. Lanzamiento del tablero en la nube
**Capturas requeridas:**
- Modificación en `app.py` para `host="0.0.0.0"`
![alt text](image-13.png)
- Cambio guardado y enviado a GitHub desde la VM
![alt text](image-14.png)
- Configuración del Security Group en AWS (puerto 8050)
![alt text](image-15.png)

**Enlace al tablero en la nube:** 
http://13.221.45.232:8050/
