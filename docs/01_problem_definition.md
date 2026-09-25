# Problem Definition ## 

1. Background Educational
AI and adaptive learning systems can support teachers and learners by using information about learning contexts and learner activity to inform instructional decisions. UNESCO emphasizes that the use of AI in education should remain human-centred and should account for ethical, safe, equitable, and meaningful use [1]. Learners can differ in prior knowledge, task performance, learning needs, engagement, and accessibility requirements. These differences motivate investigation into instructional approaches that can adapt to learner and task characteristics. This project investigates an adaptive instructional recommender that recommends instructional strategies based on defined learner, task, and contextual information. The project treats the recommender as a decision-support system rather than an autonomous replacement for educators. This is consistent with human-centred approaches to AI in education and with guidance emphasizing human agency and teacher responsibility [1,2].
   

2. Real-World Problem
In educational settings, instructional decisions may depend on fixed teaching plans, available resources, contextual constraints, and professional judgement. The research problem addressed by this project is: > How can learner and task information be used to recommend an appropriate instructional strategy in a systematic, transparent, and evidence-informed way? The system is intended to support instructional decision-making rather than replace educators or other qualified human decision-makers.

  
3. Target Users
The intended users of the system are:
- Educators/teachers
- Instructional designers
- Researchers
- Other intended users: The system is designed to provide recommendations that can be reviewed and interpreted by a human.

  
4. Learner Context
The project considers learner characteristics that may be relevant to instructional strategy selection.
Potential characteristics include:
- prior knowledge
- task performance
- engagement;
- observed learning needs
- task difficulty
- instructional context
- accessibility requirements; and - other features defined in the feature schema. Only features justified by the research protocol and data protocol should be used. 

  
5. Problem Scope
Included this research focuses on: 
- recommending instructional strategies; - representing learner and task characteristics; - comparing alternative recommendation approaches; - evaluating recommendation quality using predefined metrics; and - maintaining human oversight of recommendations. ### Excluded The system does not aim to: - make autonomous high-stakes educational decisions; - diagnose disabilities or medical conditions; - replace educators; - determine a learner's ability or potential from limited data; or - infer sensitive characteristics without an appropriate research and legal basis.

6. Problem Definition The research problem can be summarized as follows: > Given information about a learner, learning task, and instructional context, can an adaptive system recommend an instructional strategy that is appropriate according to predefined research criteria? 

7. Problem Identification The problem should be justified using: - peer-reviewed literature; - relevant educational research; - stakeholder requirements; - observation or analysis of current practice; and/or - other documented evidence. The actual evidence supporting the problem definition will be documented in `02_literature_review.md` and `04_research_gap.md`. ## 8. Design Principles


8.1 Human Oversight Recommendations should support rather than replace human judgement. UNESCO's guidance on AI in education emphasizes a human-centred approach, while its AI competency framework for teachers explicitly emphasizes human agency and human-centred use of AI [1,2].
-
-
8.2 Transparency The system should provide an understandable basis for recommendations where technically and practically possible. ### 8.3 Fairness and Accessibility The system should be evaluated for potentially systematic differences in recommendation performance where appropriate. Accessibility should be considered as part of inclusive educational design. Article 24 of the UN Convention on the Rights of Persons with Disabilities recognizes inclusive education and reasonable accommodation as important elements of education for persons with disabilities [3]. ### 8.4 Privacy Learner data should be minimized, protected, and processed only for defined purposes. The GDPR establishes principles including purpose limitation and data minimisation [4]. ### 8.5 Risk Management AI risks should be considered throughout design, development, evaluation, and use. The NIST AI Risk Management Framework provides a voluntary framework for managing AI risks and promoting trustworthy and responsible AI development [5]. ### 8.6 Reproducibility Data processing, experiments, model configurations, and evaluation procedures should be documented. ### 8.7 Evidence-Based Development
