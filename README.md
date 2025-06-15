# Flask Docker GCP Deploy 🚀

Este repositorio contiene una aplicación web mínima en **Flask** empaquetada en **Docker** y desplegada en una instancia de **Google Cloud Compute Engine** utilizando **Artifact Registry** y **Cloud Build**.

---

## 📦 Tecnologías utilizadas

- Python 3.9
- Flask 3.x
- Gunicorn (WSGI server)
- Docker
- Google Cloud Platform (GCP)
  - Cloud Shell
  - Cloud Build
  - Artifact Registry
  - Compute Engine

---

## 📁 Estructura del proyecto
devops-repo/
├── Dockerfile
├── main.py
├── requirements.txt
├── templates/
│ ├── layout.html
│ └── index.html


---

## 🔧 Cómo funciona

La aplicación utiliza Flask para mostrar un mensaje simple:  
`Hello DevOps Fans.`

La app se ejecuta sobre Gunicorn y escucha en el puerto 80 dentro de un contenedor Docker, que es desplegado en una máquina virtual de GCP.

---

## 🚀 Despliegue paso a paso (resumen del laboratorio)

1. **Configuración del repositorio y código base en Cloud Shell.**
2. **Creación de imagen Docker con Cloud Build.**
3. **Almacenamiento de la imagen en Artifact Registry.**
4. **Despliegue de la imagen en una instancia de Compute Engine.**
5. **Acceso público mediante IP externa (HTTP).**

---

## 🌐 Acceso a la aplicación

Puedes acceder a la app desplegada desde la siguiente IP pública (si sigue activa):

**http://[TU_IP_PÚBLICA]**

_Reemplazar `[TU_IP_PÚBLICA]` con la dirección real si lo estás usando como demo público._

---

## ✅ Estado del laboratorio

Este repositorio forma parte de un laboratorio de Google Cloud completado con éxito en Qwiklabs.

---

## 📬 Autor

**Santiago Barrera**  
Industrial Technologist & Python Developer  
GitHub: [@Santiagobc53](https://github.com/Santiagobc53)

---

## 📌 Notas

- Este proyecto es una excelente base para entender cómo se conecta Docker con la infraestructura en la nube.
- Puede extenderse para microservicios, CI/CD, y más funcionalidades backend.

---



