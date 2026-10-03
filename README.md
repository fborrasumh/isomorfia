# IsomorfIA

**Enunciados de problemas isomorfos** a partir de un enunciado base: mismos estructura y dificultad, distintos sistemas industriales (u otros contextos).

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23125394.svg)](https://doi.org/10.5281/zenodo.23125394)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> Catálogo [fborrasumh/ia](https://fborrasumh.github.io/ia/) · Universidad Miguel Hernández de Elche

## Idea original

Procedimiento desarrollado por **Ramón Ñeco García** (cuaderno Colab) para la asignatura *Automatización Industrial* (Grado en Ingeniería Eléctrica): generar varios enunciados cuya solución GRAFCET sea estructuralmente equivalente, con estilos de redacción distintos y opción de cambiar nombres de sensores/actuadores.

Esta app Forja generaliza la idea en el navegador (Word o texto pegado, clave de IA del usuario).

## Qué hace

1. Carga un enunciado base (Word `.docx` o texto)
2. Elige número de variantes, estilo (formal / semi-informal / muy informal «Paco») y si se cambian nombres de variables
3. La IA genera enunciados isomorfos
4. Exporta Markdown o copia el resultado
5. **Valida isomorfía**: perfil estructural local + esqueleto GRAFCET y contraste con IA

## Autores

**Ramón Ñeco García** · Universidad Miguel Hernández de Elche · ORCID: [0000-0002-4338-3692](https://orcid.org/0000-0002-4338-3692) — idea original y diseño pedagógico  

**Fernando Borrás Rocher** · Universidad Miguel Hernández de Elche · ORCID: [0000-0002-5519-4573](https://orcid.org/0000-0002-5519-4573) — implementación Forja

## Privacidad

- El enunciado y la clave de API solo salen del navegador hacia el proveedor de IA que elijas.
- El ejemplo demo ilustra el flujo sin llamada a la red.

## Límites

- La validación GRAFCET es orientativa (perfiles + esqueleto textual); no sustituye un simulador ni la revisión docente.
- PDFs no están soportados en v0.1 (usa Word o texto).

## Licencia

MIT · Ver [LICENSE](LICENSE)
