## Task 5
### Duckworth Lewis Calculator
- This Duckworth Lewis calculator will help you decide which cricket team (but not a chirping cricket) won the match, or you can use it to set a target for the second team if the game is interrupted by the rain.
- The Algorithm:
- * Calculation of the Resource Percentage Lost Due to A Suspension in the Play:
Just when the play stops or gets suspended temporarily, the resource percentage still available to the team is to be noted from the Resource Percentage Table. We name it R(a).
- * After the suspension, when the play resumes, again, we are to make a note of the resource percentage available to the team at that point in time, owing to the reduction of overs. This can be done similarly to the above. We name it R(b).
Substract, R(a) – R(b) to get R(L1). Thus, R(L1) = R(a) – R(b). R(L1) means the Resource Percentage Lost due to interruption or suspension of play.

- * Now, in case the innings do not resume after the suspension, the resource percentage lost is the resource percentage available at the time of suspension. In that case, Since R(b) = 0, R(L1) = R(a).
- * If there happens to be more than one suspension, then all the resource percentages losses are taken in the order R(L1), R(L2), R(L3), and so on.
- * The final Resource Loss Percentage, R(L) = R(L1) + R(L2) + R(L3) ……
- * In the initial stage, the Resource Percentage Available to any team at the start of the innings is 100%.
- * Firstly, we need to evaluate Thus, R1 = [ 100 – R(L) ]%
Now, we are to evaluate R2, which can be estimated simply by looking at the table. If Team 2 gets a full 50 overs, R2 will be 100%. If not, it has to be read from the table based on the number of overs remaining and 0 wickets lost.
- * Now, values of R1 and R2 are to be compared next.
If R1 = R2, NO alterations are made to the target i.e. no revised target for Team 2.
T = S + 1
- * If R1 > R2, Team2’s revised target is made by reducing Team1’s total, S, in the ratio R2/R               1. Any decimal figures should be neglected and the result should be obtained in integer form.
T = (S x R2/R1) + 1
- * If R2 > R1, Team2’s revised target is calculated and it is greater than Team1’s total, owing to the excess of resources.
The excess resources are calculated by R2 – R1 and it is added to the total as a multiple of the average total, agreed by the two teams, i.e. G50.
T = S + (R2 – R1) x G50/100 + 1
- However, the above method holds for Standard Edition. In the case of Professional Edition, there is basically no involvement of G50 or the average score.
Hence,   T = (S x R2/R1) + 1


