# Requirement-driven organization structure model: Bridging Organizational Structure and Software Development

## Interview Transcript

**Host (Chief Algorithm Officer, Tech Company):**  
Hello everyone. Today's workshop focuses on a classic case of AI implementation failure. The project involved a multinational pharmaceutical company (Client) as the Client-Side, with our team and a third-party requirements analysis partner as Contractor. The goal was to build a data-driven user behavior analysis platform, with a budget of 1.9 million and a 6-month timeline. Ultimately, costs exceeded 10x the budget, deadlines were severely missed, and the delivered solution was never adopted by the Client.

**Researcher A:**  
What were the critical failure points?  
**Host:**  
Issues emerged from the outset. First, the Client’s responsible department had abnormal authority—it operated independently from IT and Marketing, managing only two online communities. Worse, the Client’s lead changed abruptly after kickoff, with the new lead lacking involvement in initial planning. Structural flaws also plagued the Contractor: the outsourced requirements team took 70% of the budget (700k) for a <1,000-word document, while our algorithm and engineering teams worked in silos, liaising separately with different Client departments.

**Researcher B:**  
What challenges arose during requirements analysis?  
**Host:**  
Chaotic requirements were core to the failure. Three Client departments (Community Ops, Data Science, IT) had conflicting demands: Community Ops prioritized user profiling, Data Science emphasized system configurability, and IT focused solely on maintainability. Crucially, **data schema standardization was never discussed**—without unified data standards, "data integration" became impossible. Requirements analysis took 9 months (vs. 3 planned). To compound issues, the engineering team crawled Client data without authorization, deepening mistrust.

**Researcher C:**  
Did technical implementation proceed smoothly?  
**Host:**  
Module development succeeded, but integration exposed architectural flaws. With no lead architect, interfaces were incompatible. For example, 90% of algorithmic features couldn’t be accessed via the frontend—because frontend requirements came from IT, while backend needs came from Community Ops. After integration failed, Client complaints surged.Contractor deployed 10x more resources for fixes, inflating costs to 13 million.

**Professor:**  
From an academic lens, what structural contradictions merit study?  
**Host:**  
Three core conflicts:  

1.  **Misaligned Authority:** Key Client decision-makers were absent, while non-decision-makers (e.g., a community manager) dominated requirements and blocked technical dialogue.  
2.  **Communication Silos:** Contractor’s parallel algorithm/engineering teams and the Client’s multi-department structure created a **fragmented communication network**, severing information flow.  
3.  **Goal Misalignment:** The Client’s business objective—"standardizing user medication behavior"—was reduced to pure technical tasks, lacking a business-technology alignment mechanism.  
    *Quantifying these could build risk-prediction models—a potential collaboration focus.*

**Researcher D:**  
Were any rescue measures attempted?  
**Host:**  
Later,Contractor assigned a senior PM to centralize Client requests, temporarily easing tensions. But adding manpower to structural flaws was like **pouring fuel on the fire**. Ironically, we later realized the Client only needed a standard recommendation system—initial requirement distortions overcomplicated a simple solution.

**Professor:**  
Thank you! I suggest future work on **"conflict quantification models in multi-agent collaborations."** We can merge enterprise data with academic theory.  
**Host:**  
Agreed. Today’s discussion will be documented for reference, and a dedicated research group will be formed.