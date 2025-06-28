# 🧠 The Work: Las Cuatro Preguntas

> Aplicación web interactiva para practicar "The Work" de Byron Katie - Un método revolucionario de auto-indagación.

## 🌐 Demo en vivo
**[➡️ Probar la aplicación](https://magaiden.github.io/the-work-cuatro-preguntas/)**

## ✨ Características

### 🎨 **Interfaz moderna**
- **Modo oscuro elegante** por defecto
- **Diseño responsive** optimizado para móviles y desktop
- **Animaciones suaves** y transiciones fluidas
- **Tipografía moderna** con fuente Inter

### 🔄 **Funcionalidades avanzadas**
- **Guardado automático** de sesiones (persiste 24 horas)
- **Navegación bidireccional** entre pasos
- **Indicador de progreso** visual con pasos completados
- **Exportar resumen** completo al portapapeles
- **Recuperación de sesión** al recargar la página

### 📱 **Experiencia de usuario**
- **Validación inteligente** de campos
- **Feedback visual** inmediato
- **Estados de carga** y confirmaciones
- **Accesible** y fácil de usar

## 🧠 ¿Qué es "The Work"?

"The Work" es un método de auto-indagación desarrollado por Byron Katie que consiste en cuatro preguntas simples pero poderosas para cuestionar pensamientos estresantes:

### Las Cuatro Preguntas:
1. **¿Es verdad?**
2. **¿Puedes saber que es verdad con absoluta certeza?**
3. **¿Cómo reaccionas, qué sucede, cuando crees ese pensamiento?**
4. **¿Quién serías sin el pensamiento?**

### Plus: La Inversión
Invierte el pensamiento original y encuentra ejemplos genuinos de cómo la inversión puede ser tan o más verdadera.

## 🚀 Tecnologías utilizadas

- **HTML5** semántico
- **CSS3** con variables personalizadas y animaciones
- **JavaScript vanilla** (ES6+)
- **Tailwind CSS** para estilos utilitarios
- **Google Fonts** (Inter)
- **LocalStorage API** para persistencia
- **Clipboard API** para exportar

## 📋 Funcionalidades técnicas

### Persistencia de datos
```javascript
// Auto-guardado cada 2 segundos
const AUTO_SAVE_DELAY = 2000;
// Sesiones válidas por 24 horas
const sessionValidTime = 24 * 60 * 60 * 1000;
```

### Estados de progreso
- **6 pasos totales**: Pensamiento inicial + 4 preguntas + Inversión
- **Indicadores visuales** de pasos completados, activos y pendientes
- **Barra de progreso** animada

### Compatibilidad
- ✅ Chrome, Firefox, Safari, Edge
- ✅ iOS Safari, Chrome Mobile
- ✅ Fallback para navegadores sin Clipboard API

## 🎯 Propósito

Esta aplicación está diseñada como una herramienta de meditación y auto-reflexión. **No es un sustituto de la terapia profesional**, sino un complemento para el crecimiento personal y la paz mental.

## 📖 Cómo usar

1. **Escribe** un pensamiento estresante
2. **Responde** las cuatro preguntas con honestidad
3. **Escribe** la inversión del pensamiento
4. **Reflexiona** sobre el resumen completo
5. **Exporta** o guarda tu trabajo

## 🙏 Créditos

Inspirado en "The Work" de **Byron Katie**. 
Más información en: [thework.com](https://thework.com)

---

💻 **Desarrollado con ❤️ por [@MaGaiDeN](https://github.com/MaGaiDeN)**

🌟 **¿Te gusta el proyecto? ¡Dale una estrella!**