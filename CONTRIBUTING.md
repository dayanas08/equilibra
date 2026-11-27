# Convenciones de colaboración / Contribution guidelines

## Ramas (branches)
- `main`: versión aprobada para publicación.
- `develop`: integración de entregas revisadas.
- `feature/EQ-XXX`: trabajo asociado a un Issue, desde develop.

No realizar cambios directos en main ni fusionar cambios sin aprobación de la responsable. Las protecciones automáticas de ramas no se han configurado en este Issue.

## Commits
Usar Conventional Commits: `tipo(alcance): descripción`.
Ejemplos: `docs(readme): describe project scope`, `feat(expenses): add weighted split`, `fix(expenses): preserve cents`.
Tipos: feat (funcionalidad), fix (corrección), docs (documentación), chore (mantenimiento), test (pruebas), refactor (reestructuración). Referenciar el Issue en el PR.

## Flujo
1. Seleccionar Issue autorizado y moverlo a In progress.
2. Crear rama independiente desde develop.
3. Implementar y revisar criterios de aceptación.
4. Abrir Pull Request hacia develop con referencia al Issue y evidencia de pruebas.
5. Pasar a In review y Testing según corresponda.
6. La responsable aprueba la entrega antes de fusionarla. Cerrar Issue y mover a Done solo después de validar e integrar.

No guardar credenciales, datos personales reales ni archivos de entorno locales. Usar datos ficticios en pruebas.
