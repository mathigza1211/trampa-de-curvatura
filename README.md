# Trampa de curvatura (v1.5)

Simulador de una **trampa geométrica** para una partícula cuántica confinada en una guía en espiral. Idea: en una guía curvada aparece un potencial geométrico efectivo **V = −ħ²κ²/(8m)** (κ = curvatura), que podría atrapar la partícula sin paredes adicionales.

> **Estado:** hipótesis de ingeniería / modelo de juguete. No es un resultado experimental ni un dispositivo.

## Cómo usarlo
Abre `index.html` en el navegador (o por GitHub Pages). Mueve los controles y observa los resultados en vivo. No necesita instalación.

## Qué modela
- Elementos finitos 2D sobre coordenadas lógicas con la métrica polar exacta.
- Corrección de fondo de banda tipo Kronig–Penney.
- Comparación 1D–2D: la discrepancia residual documentada es ≈ 0.4 %.

## Límites (importante)
- Es un modelo teórico idealizado: no hay dispositivo ni medición.
- La extrapolación 2D a anchos muy estrechos es poco fiable (cancelaciones numéricas); se usó refinamiento de malla.
- Falta extender a más vueltas y añadir rugosidad realista de bordes.

## Documentación
Informe asociado: `informe-trampa-curvatura.docx` (si está en esta carpeta).

## Autoría
Mathias Zárate Amenero, Lima, Perú. Desarrollado junto con Claude (Anthropic): el código y los informes se elaboraron con asistencia de IA y los supuestos físicos están declarados arriba.
