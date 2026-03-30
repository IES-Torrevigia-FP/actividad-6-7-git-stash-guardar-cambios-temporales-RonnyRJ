Es una manera de guardar temporalmente cambios sin hacer commit, para limpiar tu área de trabajo y poder cambiar de rama o hacer otras tareas.

Diferencia con commit:

Commit = guarda cambios en el historial del proyecto de forma permanente.
Stash = guarda cambios temporalmente, sin afectar el historial.

Situaciones reales para usar git stash:

Estás trabajando en una feature y necesitas cambiar rápidamente a otra rama para un hotfix.
Tienes cambios incompletos y quieres probar algo en limpio sin perder lo que llevas hecho.

Riesgos de abusar del stash:

Olvidar qué contiene cada stash → difícil de recuperar.
Acumular muchos stashes sin documentarlos puede causar confusión y conflictos cuando los apliques después.
No es parte del historial → si borras el stash accidentalmente, puedes perder trabajo.
