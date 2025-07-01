# 🎉 Instrucciones para Personalizar tu Sitio de Cumpleaños

## 📝 Configurar el Formulario de Google

Para agregar tu formulario de Google para confirmar asistencia:

1. Ve a [Google Forms](https://forms.google.com)
2. Crea un nuevo formulario con preguntas como:
   - Nombre completo
   - ¿Vas a asistir? (Sí/No)
   - Número de acompañantes
   - Alergias alimentarias
   - Comentarios adicionales

3. Una vez creado, haz clic en "Enviar" y copia el enlace
4. Reemplaza `https://forms.google.com/your-form-link` en el archivo `index.md` con tu enlace real

## 🗺️ Verificar el Mapa de Google

El mapa ya está configurado con tus coordenadas: **31°08'49.7"S 63°24'40.3"W**

Si necesitas ajustar la ubicación:
1. Ve a Google Maps
2. Busca tu ubicación exacta
3. Haz clic en "Compartir" → "Insertar mapa"
4. Copia el código del iframe y reemplázalo en `index.md`

## 🎨 Personalizar el Contenido

### Cambiar la Fecha
Edita la línea en `index.md`:
```markdown
<p>¡Próximamente! Te avisaremos la fecha exacta</p>
```

### Cambiar las Actividades
Modifica la sección "Actividades Planeadas" en `index.md`

### Cambiar los Regalos
Edita la sección "Regalos" según tus preferencias

## 🚀 Publicar Cambios

1. Haz commit de tus cambios:
   ```bash
   git add .
   git commit -m "Actualizar sitio de cumpleaños"
   git push origin master
   ```

2. GitHub Pages se actualizará automáticamente en unos minutos

## 🎯 Características del Sitio

✅ **Completado:**
- Mapa embebido con tus coordenadas
- Sección para formulario de Google
- Diseño responsive
- Estilos personalizados
- Información del evento

🔧 **Para Personalizar:**
- Enlace del formulario de Google
- Fecha y hora específica del evento
- Actividades personalizadas
- Lista de regalos
- Información de contacto

## 🎊 ¡Disfruta tu Sitio de Cumpleaños!

El sitio está listo para usar y se verá genial en tu GitHub Pages. ¡Que tengas una fiesta épica! 🎉 