# 👁️ LinkEye 
### Rompiendo el silencio a través de la mirada.

**LinkEye** es una WebApp de comunicación aumentativa y alternativa (AAC) diseñada para personas con discapacidades motoras severas y pérdida del habla (como tetraplejia o pacientes con traqueostomía). Inspirada en *Look to Speak*, esta herramienta utiliza visión artificial para permitir la comunicación autónoma mediante el rastreo ocular, sin necesidad de hardware costoso.

---

## ✨ Características Principales

* **Rastreo Ocular por Cámara:** Utiliza la cámara frontal del dispositivo para detectar la dirección de la mirada en tiempo real (vía MediaPipe).
* **Escritura Jerárquica:** Sistema de selección de letras optimizado para reducir la fatiga ocular.
* **Texto Predictivo en Español:** Motor de sugerencias que agiliza la construcción de frases.
* **Síntesis de Voz (TTS):** Convierte el texto generado en audio con un solo gesto.
* **Privacidad Total:** El procesamiento de imágenes se realiza localmente en el navegador; ningún dato de video sale del dispositivo.
* **Instalable (PWA):** Funciona como una aplicación nativa en Android/iOS a través del navegador.

---

## 🛠️ Stack Tecnológico

* **Frontend:** HTML5, CSS3 (Flexbox/Grid), JavaScript (ES6+).
* **Visión Artificial:** [MediaPipe Face Landmarker](https://developers.google.com/mediapipe/solutions/vision/face_landmarker) para el tracking de pupilas.
* **Voz:** Web Speech API para la síntesis de voz en español.

---

## 🚀 Cómo funciona LinkEye

1.  **Calibración:** El sistema identifica la posición de reposo de los ojos del usuario.
2.  **Selección:** El usuario mira hacia la **izquierda** o **derecha** para filtrar grupos de letras.
3.  **Predicción:** Al detectar las primeras letras, el sistema ofrece palabras frecuentes (ej. "H-A" -> "HAMBRE").
4.  **Acción:** Gestos específicos (como mirar arriba o parpadear) activan funciones como borrar palabra o "hablar frase".

---

## 📋 Próximos Pasos (Roadmap)

- [ ] Implementar calibración automática de sensibilidad.
- [ ] Agregar soporte para frases personalizadas (cajones de emergencia).
- [ ] Optimizar el motor predictivo con aprendizaje automático local.
- [ ] Añadir modo de alto contraste personalizable.
 

---

## ⚖️ Licencia

Este proyecto está bajo la Licencia MIT. Siéntete libre de usarlo, modificarlo y distribuirlo para ayudar a quienes lo necesiten.
