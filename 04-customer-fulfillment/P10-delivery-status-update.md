**Final Prompt Text:**
> "Act as a B2B Fulfillment Specialist. Draft a concise delivery status update for [Insert Client Name]. Confirm that Order [Insert Order Number] has been dispatched. Include bullet points for: Courier Name, Tracking Link, and Expected Delivery Date. Tone: Professional, clear, and reassuring."

**Intended Workflow:** Customer Fulfillment - Order Tracking. **Problem Solved:** Reduces the number of "Where is my order?" emails by proactively providing clearly formatted tracking information.

#### 🔄 Iteration Log

| Prompt Version | Change Made | Observed Effect | Lesson Learned |
| :--- | :--- | :--- | :--- |
| **v1.0** | Initial broad instruction ("Tell customer order shipped") | Output was too brief, generic, and lacked basic professionalism. | AI needs a defined audience (B2B vs B2C). |
| **v1.1** | Instructed to add tracking info and excitement | Tone was way too enthusiastic and marketing-heavy for B2B supply chain. | Tone constraints must be explicitly defined. |
| **v1.2** | Added B2B Specialist Role + bulleted tracking constraints | Output proactively provided clear tracking info in a professional tone. | Bullet points are the best format for transactional updates. |

**Automation Potential:** Very High. This is highly repetitive and perfectly suited for AI generation.

**Risks & Limitations:** AI might hallucinate tracking links if not provided exactly. *Mitigation:* Ensure the prompt clearly forces the AI to use only the provided tracking link and not generate a fake one.
