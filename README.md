# Wet Lab

Protocol lineage and sample provenance for all datasets entering computational analysis.

## Structure

| Folder | Contents |
|--------|---------|
| `protocols/` | Versioned experimental protocols (immutable once linked) |
| `samples/` | Sample metadata, conditions, QC |
| `datasets/` | Dataset-level provenance — links protocols + samples → EXP-IDs |
| `SOPs/` | Standard operating procedures (step-by-step, for wet lab team) |

## Protocol version convention

`{protocol-name}_v{MAJOR}.{MINOR}_{YYYY-MM}`

Never edit a version file once it has been linked from a Dataset. Create a new version.

## Dataset ID convention

`DATASET-{PROJECT_SLUG}-{YYYYMMDD}-{NNN}` or use PI-assigned IDs if provided.
# Wetware
