# datasets

Repositorio para organizar datasets de PIA por año, evaluación y práctica.

## Estructura

Actualmente, el repositorio contiene la colección `PIA/` con este esquema:

```text
PIA/
  2024/
    ORD1/
    ORD2/
    PROY/
  2025/
    ORD1/
    ORD2/
    PROY/
  2026/
    ORD1/
    ORD2/
    PROY/
```

Cada carpeta de evaluación incluye archivos como `P1.zip` y `P2.zip`. En `PIA/2025/PROY/`, el recurso `P2.md` apunta a un dataset externo en Hugging Face.

## Convención de nombres

- `2024`, `2025`, `2026`: año del período.
- `ORD1`, `ORD2`: evaluaciones ordinarias.
- `PROY`: material del proyecto.
- `P1`, `P2`: práctica o parte correspondiente.

## Uso

- Agrega nuevos datasets manteniendo la misma jerarquía de carpetas.
- Si un recurso no vive dentro del repositorio, documéntalo con un `.md` o una referencia equivalente.
