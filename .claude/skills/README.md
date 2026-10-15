# Skills de Claude para este proyecto

Copiadas tal cual de repos de terceros (licencia MIT, ver LICENSE en cada carpeta).
Claude Code las carga solo cuando trabaja dentro de este repo.

| Skill | Origen | Para qué sirve aquí |
|---|---|---|
| ponytail | dietrichgebert/ponytail @ 2961b52 | Hacer el cambio más pequeño que resuelva todo, sin código de más. |
| ponytail-review | dietrichgebert/ponytail @ 2961b52 | Revisar un cambio: lógica, seguridad, rendimiento, líneas que sobran. |
| ponytail-audit | dietrichgebert/ponytail @ 2961b52 | Auditar el tema completo y listar lo roto o riesgoso, por prioridad. |
| code-review-and-quality | addyosmani/agent-skills @ aeac41d | Revisión antes de publicar un cambio. |
| debugging-and-error-recovery | addyosmani/agent-skills @ aeac41d | Encontrar la causa real cuando algo se rompe. |
| frontend-ui-engineering | addyosmani/agent-skills @ aeac41d | Secciones accesibles y responsive. |
| performance-optimization | addyosmani/agent-skills @ aeac41d | Velocidad de la tienda (Core Web Vitals). |

Las listas de chequeo que usan están en ../references/.
No se instalaron los hooks de ponytail ni de agent-skills (cambian el arranque de cada sesión) ni graphify (no lee archivos .liquid).
