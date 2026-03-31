**Intended Workflow:** Procurement - Contract Review.
**Problem Solved:** Manually reading 20-page contracts to find hidden costs takes hours and is prone to human error.

#### 🔄 Iteration Log

**Attempt 1:** "Summarize this supplier contract." 
*(Error: The AI provided a general summary but missed the hidden late fees and penalties.)*

**Attempt 2:** "Find all the fees in this supplier contract." 
*(Error: The AI found the fees, but the output was a messy paragraph that was hard to read quickly.)*

**Attempt 3 (Final Prompt):** "Act as a Procurement Analyst. Review the provided supplier contract text. Extract all fee structures, hidden penalties, and payment terms. Output the results in a clean Markdown table with the columns: Fee Type, Amount/Percentage, and Trigger Condition."

**Automation Potential:** High. Instantly turns dense legal text into a readable pricing table.
**Risks & Limitations:** The AI might misinterpret complex legal jargon. 
*Mitigation:* A human must verify the extracted table against the original contract before signing.
