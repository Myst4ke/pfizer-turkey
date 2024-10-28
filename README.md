# pfizer-turkey

Project organization
The project is to be realized in group of two or three students. The project: the report + code and data files used are to be sent by mail by November 15, 2024 to vincent.mousseau@centralesupelec.fr.
The work consists of:

• Describe the situation and the decision problem (stakeholders, issues, data, ...)

• Specify the set of choices and the evaluation criteria,

• Compute efficient solutions,

• Discriminate solutions by an additive model

• Analyze the limitations of the proposed model.

Each group will seek to provide some answers to the following questions:
1. Do the obtained solutions have properties that are worth bringing to the attention of the decision maker?
2. Discuss the properties of the current solution in comparison to the solutions you have obtained.
3. Varying workload is currently an objective taken into account in the form of constraints. We can get different sets of effective solutions and tradeoffs with other goals by tightening and relaxing this constraint. Try at least one interval and discuss the result (you can use [0.9, 1.1])
4. How to model the case for partially assigning bricks (i.e. assign a brick to multiple SR?) Implement this and compare the results.
5. If the demand increases uniformly in all bricks (for example + 20%, it may be necessary to hire a new sales representative. There is the question of where to locate his office (center brick)
6. The location of the "center bricks" (SR offices) has a significant impact on the distance traveled by the SRs. An important question is to generalize the model so as to allow a modification of the "center bricks"; this requires considering additional binary variables. (It should be noted that some of the bricks are not good candidates as a "center brick", which makes it possible to reduce the number of variables).

7. How to incorporate in the model the SRs' preferences for their area?


Each group will choose a convenient solver/modeler to implement the solution.
