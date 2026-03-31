**Final Prompt Text:**
> "Act as a Customs Broker. Create a bulleted checklist of the exact export documentation required for shipping [Insert Product] from [Insert Origin Country] to [Insert Destination Country]. Include a strict 1-sentence explanation for why each document is legally required."

**Intended Workflow:** Logistics - Export Compliance. **Problem Solved:** Prevents shipments from getting stuck at the border by ensuring junior staff know exactly what paperwork to attach.

#### 🔄 Iteration Log

| Prompt Version | Change Made | Observed Effect | Lesson Learned |
| :--- | :--- | :--- | :--- |
| **v1.0** | Initial broad instruction ("What documents do I need for international shipping?") | Output provided an overwhelming list of every possible document globally. | Context must be narrowed down to specific shipping lanes. |
| **v1.1** | Added specific origin/destination | Output was accurate but formatted poorly and lacked legal context for junior staff. | Checklists need explanations to be useful for training. |
| **v1.2** | Added Customs Broker Role + 1-sentence explanation constraint | Output generated a perfect, actionable checklist with legal justifications. | Role-playing improves the authority and accuracy of the output. |

**Automation Potential:** Medium. Excellent for generating checklists, but laws change.

**Risks & Limitations:** AI training data might be outdated regarding current tariff laws or embargos. *Mitigation:* Use this as a foundational checklist, but verify against current government customs portals.
