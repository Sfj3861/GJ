# Geometry Jump (GJ)

Prototipo de un juego de plataformas rítmico en HTML5 Canvas, JavaScript y CSS.

## Ejecutar
Abre `index.html` en un navegador moderno. No requiere dependencias ni servidor.

## Controles
- **Editor:** selecciona un objeto en la paleta y haz clic/toque en el escenario para colocarlo.
- **Borrar objeto:** clic derecho (ordenador).
- **Jugar:** botón «Jugar», espacio, flecha arriba o toque.
- **Nave:** mantener pulsado para ascender y soltar para descender.
- **Ball:** cada pulsación invierte la gravedad.
- **UFO:** pulsaciones para saltos individuales.
- **Orbes:** se activan pulsando mientras el jugador está dentro de su área.
- **Pads y portales:** se activan al entrar en contacto.
- **Escape / Editor:** volver al editor.

## Incluido en la primera base
- Renderizado Canvas adaptable a móvil y escritorio.
- Editor con cuadrícula, paleta, borrado, deshacer y desplazamiento horizontal del área de edición.
- Bloques, pinchos, sierras, orbes y pads amarillos/rosas/azules.
- Portales de Cubo, Nave, Ball y UFO.
- Física inicial para Cubo, Nave, Ball y UFO.
- Guardado y carga de niveles en JSON.
- Controles táctiles.
- Orbes y UFO con detección de pulsación nueva para evitar activaciones repetidas al mantener pulsado.

## Pendiente
- Integrar y recortar el spritesheet original del proyecto.
- Ajustar las físicas mediante pruebas y parámetros editables.
- Colisiones de plataformas y geometrías más precisas.
- Portales de gravedad, velocidad, tamaño y dual.
- Editor avanzado: selección, mover, duplicar, zoom, capas, triggers y deshacer/rehacer completo.
- Música, sincronización, efectos, menús y progreso.
- Pruebas en dispositivos reales y optimización.

Los gráficos actuales son provisionales y se dibujan por código. El arte propio se integrará cuando se añada al repositorio.
