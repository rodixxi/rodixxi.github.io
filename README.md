# 🎉 Previa Hacker - Sitio Web de Rodixxi

¡Bienvenidos a la previa más hacker de Córdoba! Este sitio está inspirado en terminales, la estética de Lipgloss y el tema Jekyll Hacker.

## 🚀 ¿Qué es esto?
Una invitación interactiva y divertida para la previa de mi cumpleaños, con secciones tipo "terminal" y navegación por pestañas con emojis.

## 🖥️ Demo
Puedes verlo en: [https://rodixxi.github.io](https://rodixxi.github.io)

## 🧑‍💻 Estructura de la Página
- 🎉 Invitación
- 📋 Detalles del evento
- 🗺️ Mapa
- ✅ Confirmar asistencia
- 🎁 Regalos
- 💬 Mensaje final
- ☀️ Clima en Villa Santa Rosa, Córdoba (en vivo)

## 🛠️ Tecnologías Utilizadas
- **Jekyll** (con tema `jekyll-theme-hacker`)
- **HTML/CSS** personalizado para el look terminal
- **GitHub Pages** para hosting
- **wttr.in** para el clima en vivo

## 🏃‍♂️ Cómo correr el sitio localmente

### 1. Instala Ruby (recomendado Ruby 3+)
- **En macOS:**
  - Instala Homebrew si no lo tienes:
    ```sh
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    ```
  - Instala rbenv y ruby-build:
    ```sh
    brew install rbenv ruby-build
    rbenv install 3.2.2
    rbenv global 3.2.2
    echo 'eval "$(rbenv init - zsh)"' >> ~/.zshrc
    source ~/.zshrc
    ruby --version  # Debería mostrar 3.2.2
    ```
- **En Linux:**
  - Instala rbenv siguiendo [estas instrucciones](https://github.com/rbenv/rbenv#installation)

### 2. Instala Bundler
```sh
gem install bundler
```

### 3. Instala las dependencias del proyecto
```sh
bundle install
```

### 4. Corre el servidor local de Jekyll
```sh
bundle exec jekyll serve
```

### 5. Abre tu navegador en
[http://localhost:4000](http://localhost:4000)

---

#### ⚠️ Problemas comunes
- Si ves errores de permisos, asegúrate de estar usando Ruby instalado con rbenv, no el del sistema.
- Si Bundler te da error de versión, ejecuta:
  ```sh
  gem install bundler
  ```
- Si tienes problemas con gems nativos (como ffi, webrick), asegúrate de tener las Xcode Command Line Tools instaladas:
  ```sh
  xcode-select --install
  ```
- Si cambias de versión de Ruby, ejecuta:
  ```sh
  gem install bundler
  bundle install
  ```

---

## ✨ Créditos y Agradecimientos
- Inspirado en [Lipgloss](https://github.com/charmbracelet/lipgloss) y el tema [jekyll-theme-hacker](https://pages-themes.github.io/hacker/)
- Clima en vivo gracias a [wttr.in](https://wttr.in/-31.1506846,-63.4220181?1)
- **Asistente IA:** ¡Gracias a [Cursor agent](https://www.cursor.so/) por ayudar a diseñar y automatizar este sitio!

---

*"Si leés esto, ya sos parte de la previa más hacker del año."*
