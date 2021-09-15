# Productivity-Prediction-of-Employees

<h2>TABLE OF CONTENTS</h2>

-  [ Problem Statement](#desc)
-  [ Dataset Description](#usage)
-  [ Data insight using Seaborn](#usage)
-  [ Feature Engineering ](#usage)
-  [ Model Comparison ](#usage)

<a name="desc"></a>
<h2>Problem Statement</h2>
The Garment Industry is one of the key examples of the industrial globalization of this modern era. It is a highly labour-intensive industry with lots of manual processes. Satisfying the huge global demand for garment products is mostly dependent on the production and delivery performance of the employees in the garment manufacturing companies. So, it is highly desirable among the decision makers in the garments industry to track, analyse and predict the productivity performance of the working teams in their factories. This dataset can be used for regression purpose by predicting the productivity range (0-1).

<a name="usage"></a>
<h2>Dataset</h2>

**Input Features**

- date : Date in MM-DD-YYYY<br>
- day : Day of the Week<br>
- quarter : A portion of the month. A month was divided into four quarters<br>
- department : Associated department with the instance<br>
- team_no : Associated team number with the instance<br>
- no_of_workers : Number of workers in each team<br>
- no_of_style_change : Number of changes in the style of a particular product<br>
- targeted_productivity : Targeted productivity set by the Authority for each team for each day.<br>
- smv : Standard Minute Value, it is the allocated time for a task<br>
- wip : Work in progress. Includes the number of unfinished items for products<br>
- over_time : Represents the amount of overtime by each team in minutes<br>
- incentive : Represents the amount of financial incentive (in BDT) that enables or motivates a particular course of action.<br>
- idle_time : The amount of time when the production was interrupted due to several reasons<br>
- idle_men : The number of workers who were idle due to production interruption<br>

**Output**

- actual_productivity : The actual % of productivity that was delivered by the workers. It ranges from 0-1.
