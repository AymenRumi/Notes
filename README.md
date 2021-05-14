# Stars EDA - 2 Month (Jan,Feb) Observation Report

This is a small report from my Stars EDA, it will focus on some interesting findings. The main EDA document is where most of the analysis is.

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

- Many rows are completely duplicate rows, there is mutliple values of the same session ID that are the same, an example is shown below.

![](https://user-images.githubusercontent.com/25378211/118283191-16c7f380-b49d-11eb-8164-463d69230b33.png=100x20) ![](https://user-images.githubusercontent.com/25378211/118283233-21828880-b49d-11eb-95a4-5d6f58010776.png=100x20)


