# ¿Qué Claude abrir? Tabla y árbol de decisión

Datos oficiales de Anthropic a 1-nov-2026. Página completa: https://ctrlia.dev/recetas/que-claude-abrir.html

## Tabla comparativa

| | Claude Code (terminal) | App Claude Desktop (pestaña Code) | Cowork | Chat de claude.ai | Claude Code en la web |
| --- | --- | --- | --- | --- | --- |
| Para qué sirve | Programar con agentes, automatizar con `claude -p` | Lo mismo con diffs visuales, vista previa y sesiones en paralelo | Trabajo de conocimiento sin terminal: documentos, investigación, hojas de cálculo | Conversar, buscar, crear archivos y Artifacts | Tareas de código largas que siguen aunque cierres el portátil |
| Dónde corre el trabajo | Tu máquina | Tu máquina (o entornos SSH, Cloud o WSL) | Servidores de Anthropic, en un entorno aislado | Servidores de Anthropic | Máquina virtual en la nube de Anthropic |
| Qué instalar | `claude` (instalador nativo) | La app de escritorio (trae el motor) | Nada aparte: la misma app, web o móvil | Nada (web) o la app | Nada; conectar GitHub |
| Sistemas | macOS, Linux, WSL, Windows | macOS, Windows x64 y ARM64, Linux en beta (Ubuntu y Debian) | Escritorio, web y móvil | Web, escritorio y móvil | Navegador y app móvil |
| Plan | Pro, Max, Ultra, Team, Enterprise o clave de API | Suscripción de pago | Pro, Max, Ultra, Team, Enterprise | Free y todos | Pro, Max, Ultra, Team; Enterprise con plaza premium |

## Qué incluye cada plan (datos oficiales, 1-nov-2026)

Precios de [claude.com/pricing](https://claude.com/pricing) a 1-nov-2026; compruébalos allí antes de pagar.

| Plan | Precio | Qué incluye para programar |
| --- | --- | --- |
| Free | $0 | Solo el chat de claude.ai; sin Claude Code |
| Pro | $20 al mes ($17 al mes con pago anual) | Claude Code en terminal, IDE, app de escritorio, web y móvil, Remote Control, Dispatch, sesiones en la nube y Cowork |
| Max | $100 al mes | Las mismas funciones que Pro en Claude Code, con 5 veces su margen de uso |
| Ultra | $200 al mes | Las mismas funciones; 10 veces por semana y sin límite de 5 horas en cuentas verificadas |
| Team | Plaza estándar $20 al mes con pago anual o $25 mensual; premium $100 o $125 | Claude Code y Cowork; Remote Control y Channels los activa un administrador; Code Review y panel de analítica; sin Dispatch ni uso del ordenador |
| Enterprise | $20 por plaza al mes con pago anual, mínimo 20 plazas, más el uso a tarifas de API | Sesiones en la nube solo con plaza premium o Chat + Claude Code |
| Clave de API (Console) | Pago por uso | Solo CLI y extensiones de IDE; sin app de escritorio (salvo Claude Desktop on 3P), web, móvil ni Remote Control |

Ultra es el nuevo nombre de Max 20x y Max el de Max 5x; además del margen de uso, cambian los créditos de API incluidos. Detalle de límites en [¿Claude Code es gratis?](https://ctrlia.dev/recetas/claude-code-precio-gratis.html).

## Cuándo usar cada uno

Pregúntate en este orden:

1. **¿Vas a cambiar código?** Si no: chat (preguntas) o Cowork (documentos, investigación, tareas de varios pasos sin terminal).
2. **¿El código está en tu PC y necesitas tus herramientas, servidores locales o MCP?** Entonces Claude Code local: terminal si quieres todas las funciones y automatizar; pestaña Code de la app si prefieres revisar diffs visualmente y abrir varias sesiones; VS Code o JetBrains si no quieres salir del editor.
3. **¿La tarea es larga, está en GitHub y quieres apagar el portátil?** Claude Code en la web o `claude --cloud`.
4. **¿Te vas del escritorio a mitad de una tarea local?** Remote Control desde el móvil ([guía paso a paso](https://ctrlia.dev/recetas/remote-control-movil.html)).

Combinaciones que funcionan:

- Planificar en la terminal con el modo plan y ejecutar en la nube con `claude --cloud`.
- Empezar en la terminal y pasar a la app con `/desktop` para revisar los cambios (requiere suscripción de claude.ai y funciona en macOS y Windows x64).
- Lanzar en la web desde el móvil y rematar en local con `claude --teleport`.

Todo comparte el mismo margen de uso del plan, así que más superficies no significa más límite. Si vienes de otra herramienta, mira la comparativa [Claude Code vs Codex vs Gemini vs Cursor](https://ctrlia.dev/recetas/claude-code-vs-codex-gemini-cursor.html); si estás empezando, la ruta de [Empieza aquí](https://ctrlia.dev/recetas/empieza-aqui.html).
