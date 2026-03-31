**Intended Workflow:** Logistics - Carrier Selection.
**Problem Solved:** Eliminates the need to manually build comparison tables for every single freight shipment.

#### 🔄 Iteration Log

**Attempt 1:** "Compare FedEx and UPS." 
*(Error: The AI gave a generic history of the companies, not a rate comparison.)*

**Attempt 2:** "Compare these two quotes from FedEx and UPS." 
*(Error: The AI wrote a long, confusing paragraph comparing the prices.)*

**Attempt 3 (Final Prompt):** "Act as a Logistics Analyst. Compare the following freight quotes: [Insert Quote Data]. Output a comparison table highlighting three columns: Total Cost, Transit Time, and Reliability Score. Below the table, write a one-sentence recommendation based on the lowest cost per day of transit."

**Automation Potential:** Very High. Perfect for structuring unstructured pricing data.
**Risks & Limitations:** AI might misunderstand currency symbols or fuel surcharges. 
*Mitigation:* Spot-check the "Total Cost" column against the original quotes.
