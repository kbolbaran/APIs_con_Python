# 🔄 Automatización de Solicitudes PUT a API desde Excel

Este script automatiza el proceso de realizar solicitudes **PUT a una API REST** usando datos extraídos desde un archivo Excel.

---

## 🚀 ¿Qué hace este script?

1. 📥 Lee un archivo Excel (`DEVOLUCIONES CXP.xlsx`).
2. 🔁 Por cada fila, realiza una solicitud `PUT` a una API externa.
3. 📝 Almacena las respuestas recibidas (códigos de estado, mensajes, errores) en un nuevo archivo Excel.
4. ⏱️ Mide el tiempo total de ejecución del proceso.

---

## 🧰 Requisitos

Instala las librerías necesarias con:

```bash
pip install pandas requests json datetime
