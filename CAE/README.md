
# Stars EDA 2 Month - Observation Report

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

![image](https://user-images.githubusercontent.com/25378211/118284807-d23d5780-b49e-11eb-9632-6e336476bccd.png)

![image](https://user-images.githubusercontent.com/25378211/118284864-e6815480-b49e-11eb-86af-51f9a2428dfc.png)

![image](https://user-images.githubusercontent.com/25378211/118284897-f0a35300-b49e-11eb-8866-a22d0905dde1.png)

![image](https://user-images.githubusercontent.com/25378211/118284924-f862f780-b49e-11eb-9fc1-201365ad54f7.png)




