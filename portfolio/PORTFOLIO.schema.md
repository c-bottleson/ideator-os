# Portfolio schema

One row per idea. Stages never end in “shipped/done.” Shelved = **later**.

## Fields

| Field | Meaning |
|---|---|
| `id` | Short slug (`tack-trunk`, `ideator-os`) |
| `title` | Human name |
| `stage` | `ideating` \| `building` \| `bettering` \| `maintaining` \| `later` |
| `goal` | **Asked, not assumed** — done / profit / learn / ship-to-N — in their words |
| `boot_path` | Folder under `projects/` once Booted (empty while ideating) |
| `last_move` | One line — what happened last |
| `next_move` | One line — Forge / Boot / Ass-kick |
| `asskick` | `off` \| `on` — opt-in relentless drive toward `goal` |
| `updated` | ISO date |

## Stages

| Stage | Primary tool |
|---|---|
| Ideating | Forge |
| Building | Boot’d + Ass-kick toward goal |
| Bettering | Ass-kick softer + Forge for variants |
| Maintaining | Light Ass-kick / check-ins |
| Later | Shelved — not failed; can return |

## File of record

Canonical table: `portfolio/PORTFOLIO.md` (maintained by Ideator).
