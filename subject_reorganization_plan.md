# Subject Reorganization Plan

Scanned 59 top-level LaTeX project directories and classified each into a proposed subject folder based on the main `.tex` entrypoint, title blocks, section headings, and topic keywords.

## Proposed Subject Directories

- `subjects/bases-de-datos`
- `subjects/redes`
- `subjects/computacion-distribuida`
- `subjects/inteligencia-artificial`
- `subjects/arquitectura-y-sistemas-operativos`
- `subjects/intro-programacion-y-logica`
- `subjects/criptografia-y-seguridad`
- `subjects/algoritmos-y-matematicas`
- `subjects/investigacion-y-tesis`
- `subjects/otras-materias-ciencias`
- `subjects/templates-y-referencias`
- `subjects/por-clasificar`

## Key Findings

- Exact duplicate: `Tarea02_Distribuida (Copy)` matches `Tarea02_Distribuida/main.tex`.
- Likely duplicate or variant: `Arqui` and `reies` share the same architecture assignment title.
- Folder-name mismatch: `Bitacora 1` contains `Tarea 6` de Fundamentos de Bases de Datos.
- Folder-name mismatch: `Examen 2 (Copy)` is actually `Bitacora 1` de Geoquimica organica.
- Empty or placeholder projects: `ore2` is empty, `tesisPost` is a stub, and `preguntaas` is too generic to classify with high confidence.
- Several folders are clearly templates or references rather than homework projects, so they were grouped under `templates-y-referencias`.

## Output Files

- `subject_reorg_manifest.csv`: one row per top-level directory with the proposed target path, subject, confidence, and notes.

## Suggested Next Step

1. Review the rows marked `low` confidence or `template`.
2. Move the `high` confidence coursework directories into the proposed `subjects/*` folders.
3. Decide whether to merge or remove duplicates after the move.
