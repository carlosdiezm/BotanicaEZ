![imgBotanicaEz](https://github.com/user-attachments/assets/bd4323be-4b5f-43aa-b10b-cb4d00821c55)
# 🌿 BotanicaEZ

**Herramienta de estudio de botánica para estudiantes universitarios**

[![Web](https://img.shields.io/badge/Web-botanica--ez.vercel.app-4CAF50?style=flat-square&logo=vercel)](https://botanica-ez.vercel.app)
[![HTML](https://img.shields.io/badge/Tech-HTML%20%2F%20CSS%20%2F%20JS-orange?style=flat-square&logo=html5)](https://github.com/carlosdiezm/BotanicaEZ)

---

## ¿Qué es BotanicaEZ?

BotanicaEZ es una aplicación web diseñada para ayudar a estudiantes de carreras universitarias a preparar la asignatura de botánica. La idea es simple: aprender a identificar plantas y hongos a partir de fotografías, de la misma forma que se estudia el examen del carnet de conducir — una imagen, cuatro opciones, y a ver si aciertas.

El proyecto nació a petición de un estudiante que necesitaba una manera práctica y visual de memorizar más de 130 especies entre árboles, arbustos, helechos, briófitos y estructuras reproductoras vegetales.

---

## 🚀 WEB

👉 [Botanica-Ez](https://botanica-ez.vercel.app)

---

## ✨ Modos de estudio

### 🧪 Modo Test
Responde 50 preguntas de tipo test: se muestra una fotografía de una planta o hongo y debes elegir el nombre correcto entre 4 opciones. Al finalizar, obtienes tu puntuación y se registran los errores para el modo repaso.

### 📚 Modo Estudio
Tarjetas interactivas con fotografías de cada especie. Haz tap en cada tarjeta para darle la vuelta y revelar el nombre científico. Ideal para un primer contacto con el catálogo o para repasar de forma relajada.

### 🔁 Modo Repaso de Errores
Recoge automáticamente las preguntas falladas en el Modo Test y las presenta en formato tarjetas. Así puedes centrarte en las especies que más te cuestan sin perder tiempo con las que ya dominas.

---

## 🌱 Catálogo de especies

La base de datos incluye más de 130 entradas con fotografías reales, cubriendo:

- **Coníferas** — *Pinus*, *Abies*, *Cedrus*, *Larix*, *Picea*, *Sequoia*...
- **Frondosas** — *Quercus*, *Fagus*, *Betula*, *Castanea*, *Populus*, *Salix*...
- **Arbustos mediterráneos** — *Cistus*, *Lavandula*, *Rosmarinus*, *Thymus*, *Erica*...
- **Leguminosas** — *Genista*, *Cytisus*, *Retama*, *Robinia*, *Spartium*...
- **Helechos** — *Pteridium*, *Polypodium*, *Blechnum*, *Adiantum*, *Asplenium*...
- **Briófitos y estructuras reproductoras** — Protonema, anteridios, arquegonios, esporangios...

---

## 🗂️ Estructura del repositorio

```
BotanicaEZ/
├── index.html       # Aplicación completa (HTML + CSS + JS en un único archivo)
├── plants.json      # Base de datos de especies con nombres científicos y rutas de imágenes
├── imgs/            # Fotografías de todas las especies
└── vercel.json      # Configuración de despliegue en Vercel
```

---

## 🛠️ Tecnologías

- HTML, CSS y JavaScript vanilla — sin frameworks, sin dependencias
- JSON como base de datos de especies
- Desplegado en [Vercel](https://vercel.com)

---

## 📦 Uso local

Clona el repositorio y abre `index.html` directamente en el navegador:

```bash
git clone https://github.com/carlosdiezm/BotanicaEZ.git
cd BotanicaEZ
open index.html   # o simplemente arrástralo al navegador
```

No requiere servidor ni instalación de dependencias.

---

## 🤝 Contribuciones

Si estudias botánica y echas en falta alguna especie, ¡las contribuciones son bienvenidas! Puedes abrir un issue o un pull request con nuevas fotografías y su entrada correspondiente en `plants.json`.

---

## 📄 Licencia

Este proyecto no tiene licencia definida aún. Si quieres reutilizarlo, contacta con el autor.
