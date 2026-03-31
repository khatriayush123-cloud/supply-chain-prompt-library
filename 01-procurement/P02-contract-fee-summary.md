**Final Prompt Text:**
> "Act as a Procurement Analyst. Review the provided supplier contract text. Extract all fee structures, hidden penalties, and payment terms. Output the results in a clean Markdown table with the columns: Fee Type, Amount/Percentage, and Trigger Condition."

**Intended Workflow:** Procurement - Contract Review. **Problem Solved:** Manually reading 20-page contracts to find hidden costs takes hours and is prone to human error.

#### 🔄 Iteration Log

| Prompt Version | Change Made | Observed Effect | Lesson Learned |
| :--- | :--- | :--- | :--- |
| **v1.0** | Initial broad instruction ("Summarize this supplier contract") | Output provided a general summary but completely missed the hidden late fees and penalties. | Broad instructions fail for targeted data extraction. |
| **v1.1** | Added specific target ("Find all the fees...") | Output found the fees, but presented them in a dense, hard-to-read paragraph. | Need explicit formatting constraints for readability. |
| **v1.2** | Added RACE framework + Markdown table constraint | Output perfectly extracted fees into a clean table with trigger conditions. | Structured prompts yield structured business data. |

**Automation Potential:** High. Instantly turns dense legal text into a readable pricing table.

**Risks & Limitations:** The AI might misinterpret complex legal jargon. *Mitigation:* A human must verify the extracted table against the original contract before signing.
