# Cannabis Grow Diagnosis Dataset

An open, structured dataset of common cannabis cultivation problems — deficiencies, pests, diseases, environmental stress, and growth issues. Maintained by [PlantClue](https://plantclue.com), a German-language cannabis growing knowledge platform.

## What's in here

79 diagnoses across 12 categories (nutrient deficiencies/excesses, pests, fungal/bacterial diseases, pH/EC issues, watering problems, root problems, light stress, temperature/humidity/VPD, growth/training issues, flowering/harvest issues), each with:

- German + English name
- Category
- Short description
- Affected plant parts
- Typical growth phase
- First visible symptoms
- Typical causes
- Links to full in-depth articles (where available)

## Files

| File | Format |
|---|---|
| `cannabis-diagnosen-dataset.json` | Full dataset, JSON |
| `cannabis-diagnosen-dataset.csv` | Full dataset, CSV |
| `kategorien.json` | Category reference (id, German name, English name) |

## What's NOT in here

This is a deliberately reduced excerpt. Immediate remedies, long-term solutions, differential-diagnosis logic (how to tell similar-looking problems apart), and severity staging are not part of this public dataset — those live in the full diagnosis system on [plantclue.com/diagnose](https://plantclue.com/diagnose/), including a free interactive diagnosis wizard.

## License

Licensed under [CC BY 4.0](LICENSE) — free to use, share, and adapt, including commercially, as long as you give appropriate credit and link back to this repository or to [plantclue.com](https://plantclue.com).

## Source / more information

- Interactive diagnosis wizard: https://plantclue.com/diagnose/
- Full knowledge base: https://plantclue.com/wissen/

Data is maintained periodically; not guaranteed to reflect the latest state of the live database at all times.
