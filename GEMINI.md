# Proyecto: NeoMonitor Web & NMrespi

Este proyecto es la landing page oficial de **NeoMonitor**, que actualmente está evolucionando para integrar un segundo producto: **NMrespi** (simulador de respirador artificial).

## Visión del Proyecto
- **NeoMonitor**: Simulador de signos vitales de alta fidelidad, gratuito y basado en web. Ya operativo.
- **NMrespi**: Simulador de ventilación mecánica (en desarrollo).
- **Objetivo**: Proveer herramientas de simulación clínica accesibles para medicina crítica (Neonatología, UCI, Emergencias).

## Stack Tecnológico
- **Frontend**: HTML5, Vanilla JavaScript, CSS3.
- **Styling**: Tailwind CSS (vía CDN).
- **Iconografía**: Font Awesome 6.
- **Tipografía**: Inter (UI) y JetBrains Mono (Datos/Sistemas).
- **Deployment**: Firebase Hosting.

## Estructura de la Landing Page (`index.html`)
El sitio utiliza un diseño de **"Portal Dual"** que presenta ambos productos sin usar términos grandilocuentes como "Suite".

### Componentes Clave:
1. **Hero Dual**: Sección superior con dos cards informativas para NeoMonitor y NMrespi.
2. **Motor de Traducción**: Sistema en Vanilla JS que soporta Español (ES), Inglés (EN) y Portugués (PT) mediante el atributo `data-t`.
3. **Secciones de NeoMonitor**: "Cómo funciona" (Setup), "Funcionalidades" y "Audiencia".
4. **Sección NMrespi**: Bloque técnico con animaciones SVG de curvas de presión y detalle de modos ventilatorios (VCP, VCV, PSV).

## Guías de Desarrollo
- **Consistencia Visual**: NeoMonitor usa tonos verdes (`green-400/500`), NMrespi usa tonos cian (`cyan-400/500`).
- **Mobile-First**: El diseño debe ser 100% responsive usando clases de Tailwind.
- **Traducciones**: Cualquier texto nuevo debe agregarse al objeto `translations` en el script del final del archivo para mantener la paridad idiomática.
- **Animaciones**: Preferir animaciones SVG livianas (como las curvas de ECG y ventilador) sobre archivos de video pesados.

## Roadmap Inmediato
- [ ] Refinar las descripciones técnicas de NMrespi.
- [ ] Implementar la animación dinámica de la curva de presión/volumen en NMrespi.
- [ ] Configurar Firebase Hosting para pruebas en dispositivos reales.
- [ ] Sincronizar el diseño con los activos de redes sociales (@neomonitor.pro).
