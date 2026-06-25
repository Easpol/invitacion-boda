# AGENTS.md

## Proyecto

Sitio web estático de invitación de boda (Nuria y Raúl, 21 nov 2026). Un solo `index.html` con CSS/JS inline. Sin sistema de build, sin framework.

## Estructura

- `index.html` — sitio completo (HTML + CSS + JS)
- `pareja-flores.png` — imagen de fondo referenciada por CSS

## Convenciones

- Idioma: Español
- Variables CSS definidas en `:root` (`--color-primary`, `--color-secondary`, etc.)
- Fuentes: Great Vibes (títulos), Cormorant Garamond (cuerpo), Lato (botones)
- Responsive con `clamp()` y `@media (max-width: 768px)`

## Cuidado

- `confirmarAsistencia()` y `confirmarAusencia()` son funciones placeholder (muestran alertas). Falta integrar formulario real.
- La sección de código QR es un div placeholder, no es un QR real.
