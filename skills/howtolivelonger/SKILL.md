---
name: howtolivelonger
description: Look up research on longevity, diet, exercise, sleep and everyday habits in the HowToLiveLonger JSON dataset.
---

# HowToLiveLonger

Download and read https://raw.githubusercontent.com/ninhhaidang/HowToLiveLonger/main/data/evidence.json. For Vietnamese answers, also read https://raw.githubusercontent.com/ninhhaidang/HowToLiveLonger/main/locales/vi.json and https://raw.githubusercontent.com/ninhhaidang/HowToLiveLonger/main/locales/readers/vi.json; match records by stable `id`.

Match the user's question to entries in `records`. Read `finding`, `action`, `grade`, `effect`, `ci`, `comparison`, `population`, `limitations` and `sources`. `originalClaim` is historical text, not the current finding. For Vietnamese, prefer the corresponding translated fields and reader summaries; use the original record for source URLs and evidence grade.

Answer in the user's language. Lead with a direct answer and a practical takeaway. Explain necessary technical terms; describe the study population and evidence strength in plain language rather than reciting field names or letter grades. Link the original studies in `sources[].url`. If the dataset does not cover the question, say so.
