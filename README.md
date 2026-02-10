# Language Learning Activities Dataset Collection

This repository hosts a collection of **annotated language learning activities** and related datasets, designed for:

- language education platforms,
- NLP and computational linguistics research,
- evaluation of gap-filling, classification, and selection tasks,
- dataset curation and benchmarking.

The repository is organized **by activity type**, with each activity type containing one or more **self-contained datasets**.

---

## Repository Structure



Additional documentation, schemas, and guidelines are available under `docs/`.

---

## Activity Types

| Activity type | Description |
|---|---|
| `fill-in-blanks` | Gap-filling exercises with annotated correct answers and distractors |
| `multiple-choice` | multiple choice questions with the source-text of the Question, the Question, the correct answer and two or more distractors.|
| `correct_order` | re-ordering senetences activity |

Each activity type has:
- its own annotation schema,
- activity-specific rules and known issues,
- validation guidelines.

---

## Data Format

- **Primary format:** JSON / JSONL  
- **Splits:** `train`, `dev`, `test` (when applicable)
- **Encoding:** UTF-8
- **One item = one activity**

JSONL is recommended for larger datasets and streaming use.

---

## Documentation

- `docs/schema/` — JSON Schemas for validation
- `docs/guidelines/` — annotation and QA rules
- `docs/examples/` — minimal working examples per activity type

---

## Validation & Quality Assurance

Each dataset may include:
- manual review status,
- known limitations or edge cases.

See activity-specific READMEs for details.

---

## License

Please refer to the `LICENSE` file.

⚠️ Source texts linked or referenced inside datasets may be subject to **external licensing terms**. Users are responsible for ensuring compliance.

---

## Citation

If you use this repository or its datasets in academic work, please cite the repository using `CITATION.cff`.

---

## Contributions

Voula Giouli
Athina Sioupi
Stamatia Michalopoulou
George Tsoulouchas
Zacharoula Kampouri
Anna Kaneolopoulou
Alexandra Gaitatzi


