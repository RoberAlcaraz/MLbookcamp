# CRISP DM

(https://es.wikipedia.org/wiki/Cross_Industry_Standard_Process_for_Data_Mining)

- Croos Industry Standard Process for Data Mining is a methodology for organizing ML projects.
- From understanding the problem to deployment

Usual steps:
1. Business understanding:
    - Is there a problem that ML can help/solve?
    - Define a MEASURABLE goal (reduce the amount of spam by 50%)

2. Data understanding (EDA)
    - Analyze the available data
    - Is the data good enough?
    - Do we need more data?
    - We may go back to the previous step and adjust it

3. Data preparation
    - Clean the data
    - Build pipelines
    - Feature Engineering: transform the data so it can be suitable for ML models

4. Modeling
    - Will models should be use?
    - Select the metric to be used
    - Compare them
    - Maybe we should go back to create new features

5. Evaluation
    - Do our metric improve?

6. Deployment
    - Roll the model to all users
    - Proper monitoring
    - Ensuring the quaity and mantainability

7. REPEAT



