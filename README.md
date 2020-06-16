# Data-Science-Projects
## Titanic Sinking Ship Data Science Issue:-
The script written walks us through a typical workflow for solving which segment of passengers were most likely/unlikely to be saved. The objective of this script is to follow a step-by-step workflow, explaining each step and rationale for every decision we take during solution development.

### Workflow stages
The solution workflow goes through seven stages described in the Data Science Solutions book.

1. Question or problem definition.
2. Acquire training and testing data.
3. Wrangle, prepare, cleanse the data.
4. Analyze, identify patterns, and explore the data.
5. Model, predict and solve the problem.
6. Visualize, report, and present the problem solving steps and final solution.
7. Supply or submit the results.
The workflow indicates general sequence of how each stage may follow the other. However there are use cases with exceptions.

We may combine mulitple workflow stages. We may analyze by visualizing data.
Perform a stage earlier than indicated. We may analyze data before and after wrangling.
Perform a stage multiple times in our workflow. Visualize stage may be used multiple times.
Drop a stage altogether. We may not need supply stage to productize or service enable our dataset for a competition.
#### Question and problem definition
The sinking of the Titanic is one of the most infamous shipwrecks in history.

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew.
Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.

In this Project, we ask you to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).

Knowing from a training set of samples listing passengers who survived or did not survive the Titanic disaster, can our model determine based on a given test dataset not containing the survival information, if these passengers in the test dataset survived or not.

We may also want to develop some early understanding about the domain of our problem. 
