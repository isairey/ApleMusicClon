<div align="center">

<img src="https://user-images.githubusercontent.com/21055469/43682115-2b5a1682-981e-11e8-973d-fe316aa3a49b.png" width="100%">

# 🎵 Music App (iOS Style)

Aplicación web de streaming musical inspirada en la interfaz de **iOS Music App**, desarrollada con JavaScript.

👉 *Explorando hasta dónde puede llegar JavaScript en el desarrollo de aplicaciones modernas.*

🌐 **Demo en vivo:** http://tannerv.com/music

</div>

---

## 🚀 Descripción

Este proyecto es una recreación funcional de una app de música tipo iOS, enfocada en:

* Experiencia de usuario fluida
* Interfaz moderna
* Arquitectura simple pero escalable

Ideal como referencia para proyectos de frontend + backend con APIs personalizadas.

---

## 🖼️ Vista previa

<img src="https://user-images.githubusercontent.com/21055469/44004287-0a541a80-9e15-11e8-93e8-ff3606dd4db1.png" width="100%">

<img src="https://user-images.githubusercontent.com/21055469/44004289-0df0907e-9e15-11e8-9bcf-ec5e62bcd70a.png" width="100%">

---

## ⚙️ Backend API

El backend está diseñado para ser ligero y eficiente. Puede implementarse fácilmente con **Laravel + MySQL**.

### 🗄️ Estructura de base de datos

```sql
CREATE TABLE tracks (
  id INT AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(255) NOT NULL,
  artist VARCHAR(255) NOT NULL,
  album VARCHAR(255) NOT NULL,
  track INT NOT NULL,
  url VARCHAR(255) NOT NULL,
  artwork VARCHAR(255) NOT NULL,
  created_at TIMESTAMP NULL,
  updated_at TIMESTAMP NULL
);
```

### 🔌 Endpoints

* `/albums` → Lista de álbumes con su artista
* `/album/{album}` → Canciones de un álbum
* `/artists` → Lista de artistas
* `/artist/{artist}` → Álbumes por artista

---

## 💻 Desarrollo local

### 📦 Instalación

```bash
git clone <repo-url>
cd <project>
npm install
```

### ▶️ Ejecutar en desarrollo

```bash
npm start
```

Abrir en el navegador:
👉 http://localhost:3000

---

### 🏗️ Build de producción

```bash
npm run build
```

* Optimiza el rendimiento
* Minifica archivos
* Genera versión lista para deploy

---

## 🧠 Tecnologías utilizadas

* JavaScript
* React
* Node.js
* Laravel (Backend API)
* MySQL

---

## 📌 Características

* 🎧 Reproductor de música estilo iOS
* 📂 Organización por álbum y artista
* ⚡ Interfaz rápida y responsiva
* 🔗 Integración con API personalizada
* 🎨 UI moderna inspirada en Apple

---

## 👤 Autor

**Isai Reyes**

---

## 📄 Licencia

Este proyecto es de código abierto y puede ser usado con fines educativos y de desarrollo.

---

## 💡 Notas

* Puedes conectar tu propio backend fácilmente
* Ideal para aprender arquitectura frontend + API
* Proyecto escalable para apps reales

---


