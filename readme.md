# 📓 MiTrackList.net

> **Tu catálogo personal universal.** Unifica tus animes, videojuegos, películas, series, cómics, libros y novelas ligeras en una sola plataforma rápida, limpia y sin depender de múltiples aplicaciones corporativas.

![MiTrackList Preview](https://via.placeholder.com/800x400/111/333?text=MiTrackList.net+-+Universal+Tracker)

---

## 💡 ¿Por qué nació MiTrackList?

Como muchos entusiastas del entretenimiento, me encontré con un problema frustrante: **ninguna plataforma existente lo unía todo.** Si quería llevar mi historial, tenía que usar MyAnimeList para anime, Letterboxd para películas, Backloggd para videojuegos y otras apps para libros o cómics. Tener mi consumo fragmentado en 5 aplicaciones diferentes era insostenible.

Así que pensé: *¿Por qué no lo hago yo?* 
A pesar de estar aprendiendo a programar y dar mis primeros pasos en el desarrollo web, decidí utilizar la inteligencia artificial como copiloto técnico para materializar esta idea desde cero. El resultado es una aplicación construida con un propósito claro: simplicidad absoluta, velocidad de carga instantánea y control total de tus datos.

---

## ✨ Características Principales

*   **Multicategoría Universal:** Soporta 8 categorías de entretenimiento distintas adaptadas bajo un mismo techo (Anime, Manga, Videojuegos, Películas, Series, Libros, Novelas Ligeras y Cómics).
*   **Campos Dinámicos Inteligentes:** El formulario se adapta automáticamente a lo que estás catalogando (te pide *horas jugadas* y *desarrolladora* si es un videojuego, o *guionista y dibujante* si es un cómic).
*   **100% Privado y Sin Servidores Centralizados:** Tus datos residen originalmente en el almacenamiento de tu navegador (`localStorage`). No almacenamos correos, contraseñas ni perfiles en bases de datos comerciales.
*   **Sincronización Cloud con JSONBin.io (BaaS):** ¿Quieres cambiar de dispositivo? Puedes conectar tu propia Master Key gratuita de JSONBin para sincronizar tus listas entre tu PC y tu móvil de forma privada.
*   **Cero Anuncios y Cero Cookies Invasivas:** Sin rastreadores publicitarios ni banners molestos. Una experiencia clásica de la web de los 2000s con tecnologías modernas.

---

## 🚀 Tecnologías Utilizadas

Este proyecto fue desarrollado priorizando una arquitectura del lado del cliente (*Client-Side*) ligera y sin pasos de compilación complejos (`build-step`), permitiendo un despliegue instantáneo:

*   **React 18** (Renderizado dinámico de componentes mediante UMD).
*   **Tailwind CSS** (Estilizado responsivo rápido basado en utilidades).
*   **Lucide Icons** (Iconografía minimalista y limpia).
*   **JSONBin.io REST API** (Backend-as-a-Service minimalista para persistencia en la nube).

---

## 🛠️️ Cómo Probarlo o Usarlo Localmente

Al ser una aplicación basada puramente en el cliente (*Client-Side*), no necesitas instalar Node.js, gestores de paquetes ni configurar bases de datos locales pesadas.

1. Clona este repositorio o descarga el archivo `index.html`.
2. Haz doble clic en el archivo `index.html` para abrirlo directamente en cualquier navegador web moderno (Chrome, Firefox, Safari, Edge).
3. ¡Empieza a añadir tus obras favoritas!
4. *(Opcional)* Haz clic en el botón de **Login / Cloud** en la barra superior para seguir el tutorial integrado y conectar tu propio casillero en la nube mediante JSONBin.

---

## 📄 Licencia y Aviso Legal

Este es un proyecto de código abierto desarrollado con fines educativos y de uso personal.

> *Aviso de Uso Justo (Fair Use):* Todas las portadas, nombres de obras, marcas y logotipos de los títulos registrados pertenecen a sus respectivos propietarios de derechos de autor (Nintendo, Shueisha, Warner Bros, Marvel, DC, etc.) y se utilizan únicamente con fines ilustrativos y de catalogación personal sin fines de lucro.

---

### 👨‍💻 Autor

Creado con pasión y código por **TTatcTT**. 
*¿Sugerencias o comentarios? ¡Siéntete libre de abrir un issue o explorar el repositorio!*