# Invitación a Asado - Página Web Interactiva

Este repositorio contiene una página web interactiva para invitar a amigos a un asado. La página incluye un diseño atractivo, un formulario de confirmación de asistencia integrado con Google Forms, y un elemento interactivo que reproduce un fragmento de audio de YouTube al hacer clic.

![Vista previa de la invitación](tiopig.github.io/Azaito)

## 🔥 Características

- **Diseño responsivo**: Se adapta a diferentes tamaños de pantalla
- **Integración con Google Forms**: Para gestionar las confirmaciones de asistencia
- **Elemento interactivo**: Reproduce un fragmento de audio de YouTube al hacer clic en "(Inserte sabaleta)"
- **Estética atractiva**: Diseño temático de asado con colores cálidos
- **Puntos de encuentro**: Información clara sobre ubicación y puntos de reunión

## 🛠️ Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript
- Bootstrap 5
- Google Fonts
- Font Awesome
- YouTube API

## 📋 Cómo usar

1. Clona este repositorio:
```bash
git clone https://github.com/tu-usuario/invitacion-asado.git
```

2. Personaliza la invitación:
   - Modifica la fecha, hora y lugar del asado
   - Cambia los puntos de encuentro
   - Actualiza el ID del formulario de Google Forms
   - Personaliza el ID del video de YouTube y los tiempos de inicio/fin

3. Despliega la página:
   - Puedes usar GitHub Pages para un despliegue rápido y gratuito
   - O cualquier otro servicio de hosting web

## 🎵 Personalización del audio

El elemento interactivo "(Inserte sabaleta)" reproduce un fragmento de un video de YouTube. Para personalizarlo:

1. Encuentra el ID del video de YouTube que deseas usar (la parte después de `v=` en la URL)
2. Determina los segundos exactos de inicio y fin del fragmento que quieres reproducir
3. Modifica estas líneas en el código:

```javascript
const startTime = 30; // Cambia esto al segundo exacto donde quieres que comience
const endTime = 35;   // Cambia esto al segundo exacto donde quieres que termine
```

```javascript
videoId: 'Ks-_Mh1QhMc', // Cambia este ID por el de tu video
```

## 📝 Integración con Google Forms

La página utiliza un iframe para integrar un formulario de Google Forms. Para usar tu propio formulario:

1. Crea un formulario en Google Forms
2. Obtén el enlace de inserción (Embed)
3. Reemplaza la URL en el iframe:

```html
<iframe src="https://docs.google.com/forms/d/e/TU_ID_DE_FORMULARIO/viewform?embedded=true" width="640" height="585" frameborder="0" marginheight="0" marginwidth="0">Cargando…</iframe>
```

## 📱 Compatibilidad

La página es compatible con:
- Chrome (última versión)
- Firefox (última versión)
- Safari (última versión)
- Edge (última versión)
- Dispositivos móviles Android e iOS

## ⚠️ Notas importantes

- **Reproducción de audio**: Debido a las políticas de los navegadores, el audio solo se reproducirá después de una interacción del usuario (clic).
- **Permisos de YouTube**: Algunos videos pueden tener restricciones que impiden su reproducción en sitios externos.
- **Formulario de Google**: Asegúrate de que tu formulario de Google Forms tenga los permisos adecuados para ser accesible públicamente.

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE.md](LICENSE.md) para más detalles.

## 🙏 Agradecimientos

- [Bootstrap](https://getbootstrap.com/) por el framework CSS
- [Font Awesome](https://fontawesome.com/) por los iconos
- [Google Fonts](https://fonts.google.com/) por las fuentes
- [Unsplash](https://unsplash.com/) por la imagen de fondo

---

Hecho con ❤️ para reunir amigos alrededor de un buen asado.
