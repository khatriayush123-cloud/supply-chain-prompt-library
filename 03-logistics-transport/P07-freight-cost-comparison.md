**Intended Workflow:** Logistics - Carrier Selection.
**Problem Solved:** Eliminates the need to manually build comparison tables for every single freight shipment.

#### 🔄 Iteration Log

| Prompt Version | Change Made | Observed Effect | Lesson Learned |
| :--- | :--- | :--- | :--- |
| **v1.0** | Initial broad instruction ("Compare FedEx and UPS") | Output gave a generic history of the companies, not a rate comparison. | AI will default to general knowledge if not fed specific data. |
| **v1.1** | Provided quote data | Output wrote a long, confusing paragraph comparing the prices. | Unstructured financial data is useless for quick decision-making. |
| **v1.2** | Added specific column requirements + recommendation constraint | Output perfectly structured the unstructured pricing data into a decision matrix. | Table constraints are essential for comparative analysis. |

**Automation Potential:** Very High. Perfect for structuring unstructured pricing data.
**Risks & Limitations:** AI might misunderstand currency symbols or fuel surcharges. 
*Mitigation:* Spot-check the "Total Cost" column against the original quotes.
