# Stars EDA - 2 Month (Jan,Feb) Observation Report

This is a small report from my Stars EDA, it will focus on some interesting findings that need answers. The main EDA document is where most of the analysis is.

## Missing Data Patterns

![image](https://user-images.githubusercontent.com/25378211/118280377-285bcc00-b49a-11eb-9923-d8604f171d6f.png)

Missing Data

1. Instructor ID ~ very little (can be taken care of with imputation)
2. Training Session Type ID
3. Training Check Type ID
4. Customer ID
5. Device Key
6. Aircraft Type Designator
7. AUC ID


## Session ID

#### Observation:

- Many rows are completely duplicate rows, there is mutliple values of the same session IDs where the rows are completely the same, an example on two identical rows is shown below.

![](https://user-images.githubusercontent.com/25378211/118283899-da48c780-b49d-11eb-969d-4bf50c9819f1.png)


## Formula & Training Event Grade

#### Observation:

- Depending on the Formula, the inputs for the Training Event Grade differ greatly. All possible inputs depending on the formula are shown below

![image](https://user-images.githubusercontent.com/25378211/118284700-b2a62f00-b49e-11eb-826e-c8858665cbf8.png)

