**Intended Workflow:** Warehousing - Stock Analysis.
**Problem Solved:** Replaces the manual sorting of Excel sheets to find critical stock issues.

#### 🔄 Iteration Log

| Prompt Version | Change Made | Observed Effect | Lesson Learned |
| :--- | :--- | :--- | :--- |
| **v1.0** | Initial broad instruction ("Write a report about our inventory") | AI hallucinated fake products and numbers because no context was provided. | Never ask for analysis without providing grounding data. |
| **v1.1** | Provided raw data | AI simply repeated the data back in paragraph form without prioritizing insights. | Must instruct the AI on *how* to analyze the data. |
| **v1.2** | Added formatting constraints (top 3, bullets, executive summary) | Output rapidly converted raw data into a highly readable, actionable summary. | Constraining output length and format improves business utility. |

**Automation Potential:** High. Rapidly converts raw CSV data into a readable executive summary.
**Risks & Limitations:** The AI could make a math error if the formatting of the raw data is messy. 
*Mitigation:* Always spot-check the top 3 items against the actual database.
