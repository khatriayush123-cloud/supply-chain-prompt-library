**Intended Workflow:** Warehousing - Stock Analysis.
**Problem Solved:** Replaces the manual sorting of Excel sheets to find critical stock issues.

#### 🔄 Iteration Log

**Attempt 1:** "Write a report about our inventory." 
*(Error: The AI completely hallucinated fake products and numbers because no data was provided.)*

**Attempt 2:** "Look at this raw inventory data and write a report." 
*(Error: The AI just repeated the data back in paragraph form without analyzing it.)*

**Attempt 3 (Final Prompt):** "Act as a Warehouse Manager. Analyze the following raw inventory data: [Insert Data]. Identify the top 3 items running low on stock and the top 3 overstocked items. Provide a short, bulleted executive summary and a two-sentence recommendation for reordering."

**Automation Potential:** High. Rapidly converts raw CSV data into a readable executive summary.
**Risks & Limitations:** The AI could make a math error if the formatting of the raw data is messy. 
*Mitigation:* Always spot-check the top 3 items against the actual database.
