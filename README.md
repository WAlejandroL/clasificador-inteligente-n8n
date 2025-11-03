# Clasificador Inteligente de Mensajes con n8n

Proyecto desarrollado en n8n que permite clasificar mensajes recibidos desde Telegram usando Inteligencia Artificial (IA) de Hugging Face.

---

## 🚀 Funcionalidad

Este flujo automatiza la clasificación de mensajes de usuarios en Telegram. Cuando un usuario envía un mensaje al bot, el texto es enviado a un modelo de clasificación de Hugging Face, el cual determina la categoría del mensaje y devuelve una respuesta acorde.

Ejemplo de etiquetas:

* 📌 Urgente
* 🛠 Soporte
* 🛍 Compra
* ❓ Información

---

## 🧩 Herramientas Utilizadas

| Herramienta                    | Uso                                     |
| ------------------------------ | --------------------------------------- |
| **n8n**                        | Automatización del flujo                |
| **Hugging Face Inference API** | Clasificación de mensajes con modelo IA |
| **Telegram Bot API**           | Recepción y envío de mensajes           |

---

## 🔧 Instalación y Configuración

1. **Crear un Bot de Telegram** desde @BotFather y obtener el Bot Token
2. **Registrar un modelo de clasificación** en Hugging Face y obtener API Key
3. **Instalar o usar instancia de n8n**
4. Configurar el flujo utilizando:

   * *Trigger*: Telegram Trigger
   * *HTTP Request*: Hugging Face API
   * *Telegram*: Respuesta automática al usuario

---

## 📝 Ejemplo de Salida de la IA

```
{
  "labels": ["urgente", "soporte", "compra", "información"],
  "scores": [0.50, 0.34, 0.13, 0.02]
}
```

---

## 📄 Capturas o Diagrama del Flujo

<img width="939" height="548" alt="image" src="https://github.com/user-attachments/assets/742ff5ca-48e5-4069-bdf4-2d518cc9cc4e" />
![WhatsApp Image 2025-11-03 at 10 18 13_ff0ac54d](https://github.com/user-attachments/assets/6951842f-ab9b-46d4-b83d-a2dae33959f8)

---

## ✅ Estado del Proyecto

Proyecto funcional ✅

Mejoras futuras:

* Conectar clasificación con base de datos
* Añadir más etiquetas entrenadas
* Implementar respuestas personalizadas por categoría

---



---
