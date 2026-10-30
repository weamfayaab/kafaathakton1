# AI Usage Log

## Purpose
AI was used as an assistant for code organization, dashboard/UI design, quality-review guidance, and executive communication.

## Examples of AI-assisted tasks
1. **Notebook organization**
   - Prompt intent: reorganize the existing Python analysis into a reproducible submission structure.
   - Verification: code was checked against the actual Excel schema and restricted to existing columns.

2. **Data-quality review**
   - Prompt intent: identify appropriate checks for missing values, duplicates, outliers, and categorical placeholders.
   - Verification: all reported counts are calculated in Python from the submitted dataset.

3. **Dashboard design**
   - Prompt intent: create an executive dashboard using actual dataset fields only.
   - Verification: KPIs and charts were mapped to source columns; fabricated targets/dates were prohibited.

4. **Executive wording**
   - Prompt intent: translate calculated findings into concise management-facing language.
   - Verification: wording was constrained to descriptive findings; causal claims were not accepted without evidence.

## Responsible-use controls
- AI was not treated as the source of truth for numerical results.
- Numbers were calculated from the dataset using Python.
- No AI-generated values were inserted into the source dataset.
- Ambiguous duplicates and outliers are not automatically deleted.
- Human review is retained for questionable records.
