# ¿Qué Claude abrir? Claude Code, Desktop, Cowork, claude.ai y la web

🇬🇧 [Read in English](README.en.md)

English version: [README.en.md](README.en.md) (archivos en `en/`).

Una tabla para decidir en 30 segundos qué producto de Claude abrir: Claude Code en la terminal, la app Claude Desktop
(pestaña Code), Cowork, el chat de claude.ai y Claude Code en la web. Para cada uno: para qué sirve, dónde corre el
trabajo, qué instalar, en qué sistemas funciona y qué plan lo incluye. Más el árbol de decisión y lo que incluye cada plan.

Página completa: [ctrlia.dev (ES)](https://ctrlia.dev/recetas/que-claude-abrir.html) ·
[ctrlia.dev (EN)](https://ctrlia.dev/en/recetas/que-claude-abrir.html)

## Qué incluye

- `tabla.md`: tabla comparativa, planes (precios oficiales a 1-nov-2026) y árbol de decisión, en español.
- `en/tabla.md`: lo mismo en inglés.

## Cómo usarlo

Léelo en GitHub o cópialo a la documentación de tu equipo. Para saber con qué cuenta y plan usas Claude Code:

```bash
claude auth status   # authMethod (claude.ai o API) y subscriptionType
```

Es una comparativa **documental** (fuentes oficiales de Anthropic, 1-nov-2026), no una prueba de rendimiento. Los precios
cambian: compruébalos en https://claude.com/pricing antes de pagar.

## Probado

Con Claude Code **2.1.316** en Linux: `claude auth status` y las opciones `--desktop` y `--cloud` de `claude --help`.
No se probaron Cowork, la app de escritorio en Windows o macOS ni una sesión en la nube de punta a punta.

## Licencia

MIT. Copyright (c) 2026 Ctrl+IA (Carlos P.). Ver [LICENSE](LICENSE).
