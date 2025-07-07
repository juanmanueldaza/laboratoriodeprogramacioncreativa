# Laboratorio de Programación Creativa

Un espacio donde el código se convierte en herramienta para **imaginar, experimentar y construir**. Laboratorio de exploración creativa y técnica a través de la programación.

> **📁 Parte del Ecosistema daza.ar**: Este repositorio es parte del [daza.ar-env](https://github.com/juanmanueldaza/daza.ar-env) entorno de desarrollo. Para la configuración de desarrollo local, flujo de trabajo unificado y documentación inter-sitios, consulta el [repositorio principal](https://github.com/juanmanueldaza/daza.ar-env).

## 🌐 Sitio en Vivo

Visita el laboratorio en: **[laboratoriodeprogramacioncreativa.daza.ar](https://laboratoriodeprogramacioncreativa.daza.ar)**

## ✨ Características

- 🎨 **Enfoque Creativo** - Programación como herramienta de expresión artística
- 🛠️ **Múltiples Tecnologías** - Arduino, Processing, p5.js, JavaScript, Python
- 🤝 **Colaborativo** - Espacio para proyectos individuales y colaborativos
- 📚 **Educativo** - Aprendizaje horizontal y metodológico
- 🌐 **Comunidad** - Red viva de personas que comparten conocimientos
- 📱 **Responsive** - Perfecto en todos los dispositivos
- 📝 **Contenido Dinámico** - Contenido desde archivos markdown remotos
- 🧭 **Navegación Integrada** - Usa el componente navbar de daza.ar

## 🎯 Objetivos del Laboratorio

- Fomentar la exploración creativa y técnica a través de la programación
- Acompañar los proyectos personales de cada participante
- Impulsar la colaboración entre personas con intereses comunes
- Documentar los procesos en plataformas abiertas (como GitHub Pages)

## 🛠️ Herramientas y Lenguajes

- **Hardware**: Arduino, Raspberry Pi, Linux
- **Web**: HTML, CSS, JavaScript, Node.js
- **Creatividad**: Processing, p5.js
- **Backend**: Python, PHP
- **Documentación**: Markdown, GitHub Pages

## 🧩 Dinámica del Laboratorio

### 🌀 Exploración Individual
Cada persona trabaja sobre sus inquietudes, ideas o proyectos. El laboratorio brinda orientación técnica y metodológica.

### 🔗 Conexiones entre Pares
Se generan momentos de diálogo y sesiones libres donde pueden surgir proyectos colaborativos espontáneos.

### 📐 Formato de los Encuentros
- **Semanales** (2 horas): Sábados de 11:00 a 13:00
- **Alternancia**: Entre talleres, sesiones libres y presentaciones
- **Documentación**: Colectiva en repositorio abierto

## 👥 Participantes

| 🛍️ | **Emprendedores** | Quieren crear soluciones digitales, tiendas o sitios web |
| 🎨 | **Artistas** | Buscan nuevas formas de expresión con visuales o sonido |
| 📚 | **Educadores** | Quieren enseñar programación desde lo creativo y exploratorio |
| ⚙️ | **Hackers Caseros** | Gente curiosa que quiere experimentar con hardware y código |
| 🧠 | **Creativos Híbridos** | Mezclan tecnología, arte, pedagogía o activismo |

## 🏗️ Arquitectura

Este sitio usa una **arquitectura de módulos remotos**:

- **Contenido**: Importado desde archivos markdown de [data.daza.ar](https://data.daza.ar/md/)
- **Navegación**: Usa el componente [navbar.daza.ar](https://navbar.daza.ar)
- **Procesamiento Markdown**: Usa el módulo [mdsite.daza.ar](https://mdsite.daza.ar/mdsite.js)
- **Generación PDF**: Funcionalidad de exportación integrada

## 🚀 Stack Tecnológico

- **HTML5** - Estructura de marcado semántico
- **CSS3** - Estilado moderno con flexbox/grid
- **JavaScript Vanilla** - Módulos ES6
- **Módulos Remotos** - Componentes compartidos del ecosistema daza.ar
- **GitHub Pages** - Hosting estático con dominio personalizado

## 📁 Estructura de Archivos

```
laboratoriodeprogramacioncreativa/
├── CNAME          # Configuración de dominio personalizado
├── index.html     # Archivo HTML principal
└── README.md      # Este archivo
```

## 🛠️ Desarrollo

### Desarrollo Local

Usa el [daza.ar-env](https://github.com/juanmanueldaza/daza.ar-env) entorno de desarrollo:

```bash
# Clona el entorno de desarrollo
git clone https://github.com/juanmanueldaza/daza.ar-env.git
cd daza.ar-env

# Configura todos los sitios (incluyendo este)
./setup.sh

# Inicia los servidores de desarrollo
./dev.sh

# El sitio del laboratorio estará disponible en:
# http://laboratoriodeprogramacioncreativa.local:3008
```

### Gestión de Contenido

El contenido se gestiona centralmente en el [repositorio data](https://github.com/juanmanueldaza/data):

1. Edita `laboratorio-de-programacion-creativa.md` en el repositorio data
2. Los cambios se reflejan automáticamente en el sitio en vivo
3. No se requiere despliegue para actualizaciones de contenido

### Despliegue

Despliegue automatizado vía GitHub Pages:

```bash
# Despliegue manual (si es necesario)
npm run deploy
```

## 🎨 Personalización

### Estilos

Usa propiedades CSS personalizadas para tematización consistente:

```css
:root {
  --window-bg: #fff;
  --window-border: #e1e4e8;
  --text-primary: #23232e;
  --link: #0366d6;
  --link-hover: #0056b3;
}
```

### Secciones de Contenido

El laboratorio muestra:

- **Manifiesto** - Visión y principios del laboratorio
- **Objetivos** - Metas y propósitos
- **Herramientas** - Tecnologías y lenguajes utilizados
- **Dinámica** - Formato y metodología de trabajo
- **Facilitador** - Información sobre Juan Manuel Daza
- **Participantes** - Perfiles de quienes pueden participar

## 🔧 Configuración

La configuración automática incluye:

- **Navbar**: Enlaces de contacto profesional
- **Exportación PDF**: Optimizado para impresión
- **Carga de Contenido**: Procesamiento markdown remoto
- **Accesibilidad**: Cumplimiento completo WCAG
- **SEO**: Meta tags y datos estructurados

## 🏗️ Integración con el Ecosistema

Este laboratorio es parte del **ecosistema daza.ar**:

- **🛠️ Entorno de Desarrollo**: [daza.ar-env](https://github.com/juanmanueldaza/daza.ar-env) - Configuración unificada de desarrollo
- **📋 Contribuciones**: Sigue el flujo de trabajo de branches en [daza.ar-env/CONTRIBUTING.md](https://github.com/juanmanueldaza/daza.ar-env/blob/main/CONTRIBUTING.md)
- **🎯 Issues & Features**: Usa la plantilla [feature_improvement.md](https://github.com/juanmanueldaza/daza.ar-env/blob/main/.github/ISSUE_TEMPLATE/feature_improvement.md)
- **🏗️ Arquitectura**: Ver [documentación de despliegue](https://github.com/juanmanueldaza/daza.ar-env/blob/main/docs/DEPLOYMENT.md)

### Sitios Relacionados

- **📄 Sitio CV**: [cv.daza.ar](https://cv.daza.ar) - Currículum completo detallado
- **📋 One Pager**: [onepager.daza.ar](https://onepager.daza.ar) - Resumen profesional
- **🏠 Página de Inicio**: [start.daza.ar](https://start.daza.ar) - Dashboard personal
- **🧭 Navbar**: [navbar.daza.ar](https://navbar.daza.ar) - Componente de navegación
- **📝 Mdsite**: [mdsite.daza.ar](https://mdsite.daza.ar) - Utilidades de procesamiento Markdown
- **📊 Data**: [data.daza.ar](https://data.daza.ar) - Repositorio de contenido
- **🖼️ Wallpapers**: [wallpapers.daza.ar](https://wallpapers.daza.ar) - Colección de fondos de pantalla

## 👨‍🏫 Facilitador

**Juan Manuel Daza** - Desarrollador Full Stack que fusiona tecnología, creatividad y cultura.

Con más de 5 años de experiencia y formación en literatura, periodismo musical y gestión cultural, aporta una perspectiva multidisciplinaria única. Su enfoque creativo fusiona tecnología con disciplinas artísticas para crear experiencias digitales significativas.

## 📱 Compatibilidad de Navegadores

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Navegadores móviles con diseño responsive

## 🤝 Contribuir

¡Las contribuciones son bienvenidas! Por favor usa el entorno de desarrollo unificado:

1. Usa [daza.ar-env](https://github.com/juanmanueldaza/daza.ar-env) para la configuración de desarrollo
2. Sigue las [pautas de contribución](https://github.com/juanmanueldaza/daza.ar-env/blob/main/CONTRIBUTING.md)
3. Usa la [plantilla de features](https://github.com/juanmanueldaza/daza.ar-env/blob/main/.github/ISSUE_TEMPLATE/feature_improvement.md) para nuevas características

### Contribuciones de Contenido

- **Contenido del Laboratorio**: Edita `laboratorio-de-programacion-creativa.md` en el [repositorio data](https://github.com/juanmanueldaza/data)
- **Características del Sitio**: Contribuye a este repositorio o módulos compartidos
- **Diseño**: Sugiere mejoras UX/UI

## 👤 Autor

**Juan Manuel Daza**

- Website: [daza.ar](https://daza.ar)
- GitHub: [@juanmanueldaza](https://github.com/juanmanueldaza)
- LinkedIn: [juanmanueldaza](https://www.linkedin.com/in/juanmanueldaza)
- Email: juanmanueldaza@gmail.com

## 📄 Licencia

Licencia MIT - consulta el archivo [LICENSE](LICENSE) para más detalles.

---

<div align="center">
  <p>Hecho con ❤️ como parte del <a href="https://github.com/juanmanueldaza/daza.ar-env">ecosistema daza.ar</a></p>
  <p>
    <a href="https://laboratoriodeprogramacioncreativa.daza.ar">Sitio en Vivo</a> •
    <a href="https://github.com/juanmanueldaza/daza.ar-env">Entorno de Desarrollo</a> •
    <a href="https://github.com/juanmanueldaza/daza.ar-env/issues">Reportar Issue</a>
  </p>
</div>