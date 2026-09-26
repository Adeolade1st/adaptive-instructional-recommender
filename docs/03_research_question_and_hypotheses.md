# Research Question and Hypotheses ## 

1. Research Aim:
This research aims to investigate whether learner and task characteristics can be used to recommend instructional strategies through an adaptive instructional recommender.

  
3. Primary Research Question:
RQ1:To what extent can an adaptive instructional recommender select appropriate instructional strategies based on learner and task characteristics?


4. Secondary Research Questions:
RQ2: Which learner and task features contribute most to instructional strategy recommendations?

RQ3: How does the adaptive recommender compare with predefined baseline recommendation approaches? 

RQ4: How consistently does the recommender perform across different learner and task contexts? 

RQ5: Can recommendations be presented in a form that supports human interpretation and review? 


4.1 Variables
Independent Variables: Potential independent variables include:
- learner characteristics
- prior knowledge
- task characteristics
- task difficulty
- observed performance
- engagement-related features
- instructional context
- other features defined in the feature schema


4.2 Dependent Variables
Potential dependent variables include:
-recommendation accuracy
- precision
- recall
- F1 score
- ranking metrics
- agreement with an appropriately defined reference recommendation
- recommendation coverage
- [other predefined metrics]

The final evaluation metrics are defined in `09_evaluation_framework.md`


5. Hypotheses
H1: Adaptive Recommendation:
An adaptive instructional recommender using learner and task characteristics will produce recommendations that meet the predefined evaluation criteria.

H2: Feature Information: Including learner and task characteristics will produce a measurable difference in recommendation performance compared with a baseline that does not use these characteristics. 

H3: Context Sensitivity > Recommendation performance will vary across predefined learner or task contexts. 

H4: Feature Contribution > Different learner and task feature groups will contribute differently to instructional strategy recommendations. 


6. Null Hypotheses
H01: There is no statistically or practically meaningful difference between the adaptive recommender and the selected baseline according to the predefined evaluation criteria.

H02: Including learner and task characteristics does not produce a statistically or practically meaningful difference in recommendation performance compared with the baseline. 

H03: Recommendation performance does not differ meaningfully across the predefined learner or task contexts. 


7. Hypothesis Testing
The hypotheses will be evaluated using the experimental protocol defined in `05_research_protocol.md`. Evaluation metrics and statistical procedures are defined in `09_evaluation_framework.md`. No hypothesis should be considered supported solely because a model produces a high score. Results should be interpreted using the predefined evaluation procedure, uncertainty estimates, effect sizes where appropriate, and study limitations.

8. Scope of Inference
The hypotheses concern performance within the defined research setting, dataset, population, and experimental conditions. They should not be interpreted as evidence that the system will generalize to all educational contexts, learners, institutions, or instructional settings without further validation.
