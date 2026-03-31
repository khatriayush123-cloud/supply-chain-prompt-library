**Final Prompt Text:**
> "Act as a Senior Procurement Specialist. Write a concise, professional email to a supplier regarding a delayed shipment. Context: Supplier Name: [Insert Supplier Name], Order Number: [Insert Order #], Item: [Insert Item Description]. The shipment is currently [Insert Number] days overdue. This delay is beginning to impact our production schedule. Action: Request an immediate updated Estimated Time of Arrival (ETA) and a brief explanation for the delay. Constraints: Keep the tone firm but collaborative. Do not exceed 100 words. Do not make up any information outside of the provided context."

**Intended Workflow:** Procurement - Supplier Delay Follow-up. **Problem Solved:** Eliminates the manual drafting of repetitive delay inquiries, ensuring a consistent, professional tone while saving approximately 10 minutes per incident.

#### 🔄 Iteration Log

| Prompt Version | Change Made | Observed Effect | Lesson Learned |
| :--- | :--- | :--- | :--- |
| **v1.0** | Initial broad instruction | Output was 400 words (too long), and the AI hallucinated fake tracking numbers. | Needed strict constraints on length and data fabrication. |
| **v1.1** | Added specific order details | Output was accurate but tone was too casual and missed business impact. | Needed a defined Role (RACE framework) and professional tone constraint. |
| **v1.2** | Added RACE framework + strict formatting limits | Consistent, professional output under 100 words ready for immediate use. | Explicit role and constraints = reliable outputs. |

**Automation Potential:** High. This prompt can be turned into a standard template where staff only need to fill in the bracketed variables before generating the email.

**Risks & Limitations:** The AI might hallucinate data to fill the gaps if the user forgets to fill in the bracketed information. *Mitigation:* A human must always proofread the output before hitting send to ensure the tone matches the specific relationship history with that supplier.
