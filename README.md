# 📊 Seguidores - Dashboard de Redes Sociales

Una aplicación web moderna y responsive para mostrar en tiempo real los seguidores de diferentes plataformas sociales utilizando contadores en vivo.

## 🌟 Características

- **Contadores en tiempo real**: Visualización de seguidores actualizados automáticamente
- **Múltiples plataformas**: Soporte para TikTok, Twitch, YouTube, Twitter/X y Kick
- **Diseño responsive**: Adaptable a diferentes tamaños de pantalla
- **Interfaz moderna**: Diseño limpio y atractivo con tipografía personalizada
- **Fácil configuración**: Simple personalización de usuarios y plataformas

## 🚀 Demo

La aplicación muestra contadores en vivo para las siguientes plataformas:
- 🎵 **TikTok**: @jmgranabuab
- 🎮 **Twitch**: @jmgranabuab  
- 📺 **YouTube**: Canal personalizado
- ❌ **Twitter/X**: @jmgranabuab (comentado)
- 🎯 **Kick**: @granaino_buab (comentado)

## 📁 Estructura del Proyecto

```
seguidores/
├── index.html              # Página principal
├── README.md               # Documentación del proyecto
├── LICENSE                 # Licencia MIT
├── css/
│   ├── index.css          # Estilos personalizados
│   ├── bootstrap.min.css  # Framework Bootstrap
│   └── reset.css          # Reset de estilos CSS
├── js/
│   └── index.js           # Scripts JavaScript
└── img/
    ├── tiktok.png         # Logo de TikTok
    ├── twitch.png         # Logo de Twitch
    ├── youtube.png        # Logo de YouTube
    ├── x.png              # Logo de X/Twitter
    └── kick.png           # Logo de Kick
```

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS3**: Estilos y diseño responsive
- **Bootstrap**: Framework CSS para componentes
- **JavaScript**: Funcionalidad interactiva
- **Google Fonts**: Tipografía Yanone Kaffeesatz
- **LiveCounts.io**: API para contadores en tiempo real

## 📦 Instalación y Uso

### Requisitos Previos
- Navegador web moderno
- Servidor web local (opcional, para desarrollo)

### Instalación

1. **Clona el repositorio**:
   ```bash
   git clone https://github.com/GranainoBUAB/seguidores.git
   cd seguidores
   ```

2. **Abre el proyecto**:
   - Opción 1: Abre `index.html` directamente en tu navegador
   - Opción 2: Usa un servidor local (recomendado):
     ```bash
     # Con Python
     python -m http.server 8000
     
     # Con Node.js (http-server)
     npx http-server
     
     # Con PHP
     php -S localhost:8000
     ```

3. **Accede a la aplicación**:
   - Navegador directo: `file:///ruta/al/proyecto/index.html`
   - Servidor local: `http://localhost:8000`

## ⚙️ Personalización

### Cambiar Usuarios de Redes Sociales

Edita el archivo `index.html` y modifica las URLs de los iframes:

```html
<!-- TikTok -->
<iframe src="https://livecounts.io/embed/tiktok-live-follower-counter/TU_USUARIO"></iframe>

<!-- Twitch -->
<iframe src="https://livecounts.io/embed/twitch-live-follower-counter/TU_USUARIO"></iframe>

<!-- YouTube -->
<iframe src="https://livecounts.io/embed/youtube-live-subscriber-counter/TU_CHANNEL_ID"></iframe>
```

### Activar Plataformas Adicionales

Descomenta las secciones de Twitter/X o Kick en `index.html`:

```html
<!-- Descomenta para activar Twitter/X -->
<div class="socialNetwork">
    <div>
        <iframe src="https://livecounts.io/embed/twitter-live-follower-counter/TU_USUARIO"></iframe>
    </div>
</div>
```

### Personalizar Estilos

Modifica `css/index.css` para cambiar:
- Colores del tema
- Tipografías
- Espaciado y layout
- Efectos visuales

## 🎨 Características de Diseño

- **Paleta de colores**: Gris oscuro con acentos dorados
- **Tipografía**: Yanone Kaffeesatz para un look moderno
- **Layout**: Flexbox para alineación perfecta
- **Responsive**: Adaptable a móviles y tablets

## 🤝 Contribuir

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📝 Roadmap

- [ ] Añadir más plataformas sociales
- [ ] Implementar tema oscuro/claro
- [ ] Añadir gráficos de crecimiento
- [ ] Configuración mediante archivo JSON
- [ ] Notificaciones de hitos alcanzados
- [ ] Exportar estadísticas

## 🐛 Problemas Conocidos

- Los iframes pueden tardar en cargar dependiendo de la conexión
- Algunas plataformas pueden tener límites de rate limiting

## 📄 Licencia

Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

## 👤 Autor

**Jose Miguel Quesada** - [@GranainoBUAB](https://github.com/GranainoBUAB)

## 🙏 Agradecimientos

- [LiveCounts.io](https://livecounts.io/) por proporcionar la API de contadores
- [Bootstrap](https://getbootstrap.com/) por el framework CSS
- [Google Fonts](https://fonts.google.com/) por las tipografías

---

⭐ ¡Dale una estrella al proyecto si te ha sido útil!
