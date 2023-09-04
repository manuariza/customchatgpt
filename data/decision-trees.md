---
title: "Decision trees"
category: "Operations"
date: "2021-04-07 12:00:00 +09:00"
desc: "Decision trees assist in the choice between two or more courses of action"
thumbnail: "./images/decision-trees/thumbnail.jpg"
alt: "Decision trees assist in the choice between two or more courses of action."
---

Decision trees can help you choose between two or more options. You may create a balanced picture of the risks and rewards by setting out options and outcomes for each choice, assigning values and probabilities along the way. <br>

## When to use it

● When a situation is complex enough that explicitly writing out each possibility will aid in making a decision. <br>
● To allow decision-makers to compare the costs and advantages of each outcome directly.
<br>

## Origins
While decision trees have existed in some form for centuries (the 'Bayes theorem,' which can be used to compute probability inputs for decision trees, was first established in the eighteenth century), their popularity grew in the 1950s with the emergence of computer programming. <br>

## What it is
Complex decisions are represented graphically in decision trees. They enable decision-makers to see the various options accessible in chart form, as well as assign costs, rewards, and probabilities to each outcome. Because most decisions involve both controlled and uncontrollable aspects, pictograms can be used to signify whether a decision must be made or whether uncertainty has been resolved:

● When choosing between two or more mutually exclusive options, decision nodes (represented as squares) reflect the controllable aspects. <br>
● Decision branches are lines that branch out from decision nodes; the set of options should be exhaustive collectively.<br>
● The event nodes, depicted as circles, represent instances in which the decision maker has no control over what happens next.<br>
● Event branches branch out from event nodes and illustrate potential outcomes.<br>
● The final result of a series of decisions and occurrences are terminal nodes, which are illustrated as triangles.<br>


## How to use it
Here's an example of how to utilize a decision tree to make a decision. Campbell Ship Motor (CSM), a manufacturer of tiny, ocean-going ship motors, has produced a more efficient ship motor, according to their research. CSM's ideas are usually purchased by a significant ship-motor manufacturer in South Africa. The redesigned design makes use of new, lower-cost, modular elements and could allow the motor to be produced on an automated line, saving CSM a significant amount of money over the present human assembly line. CSM is debating whether it should invest resources in R&D to commercialize this product, therefore the team creates a 'decision node' as the first branch of the decision tree. <br><br>
The team believes that conducting research and development to generate a working prototype will cost them $30,000 in total. Because of the new materials and design, there's a good chance the prototype won't pass the stress and emissions testing that it'll need to pass. If the prototype passes the testing, the team can devise a method for hand-assembling it. Because it's unclear if the prototype will be useable or not, the team creates a 'event node' at this point.
Because the firm presently builds all of its motors by hand, planning for the new motor to be hand-assembled would be the simplest way to go. Because the new motor employs fewer components, the ship-motor maker may decide to outsource the motor's assembly to a third party. Because it will not have to adjust its assembly procedures if CSM designs the new motor to allow third parties to assemble it, the ship-motor maker may pay more for the design – up to $100,000 in this example.<br><br>
CSM may be able to design the new motor in such a way that it can be manufactured on an automated manufacturing line in North America. If it succeeds, the ship-motor maker would pay top cash for the design – maybe $250,000 – since it will be able to construct the motor close to its clients' locations without incurring significant labor expenses.<br><br>
By assigning a value to each of the 'terminal nodes,' the study team attempts to quantify the result of each decision and event outlined above. The team arrives at its decision tree, depicted opposite, after setting out the decisions and outcomes:

![](./images/decision-trees/decision-trees.png)

Now that the decision tree has been sketched out, the team may use the 'rollback approach' to determine the best plan to pursue. Simply put, the team may decide whether it is worthwhile to start the project based on the information supplied and, if so, the path to take. <br><br>
The 'rollback approach' starts at the terminal nodes and works backwards. The team may determine the expected value at event nodes (the circles) for the assembly line choice using the probabilities assigned to success and failure for each of the possibilities. It accomplishes this by multiplying the chances of success and failure by the supplied values:

● Automated assembly line event node: 50 per cent × $250,000 + 50 per cent × $30,000 = $140,000.<br>
● Outsourced assembly event node: 70 per cent × $100,000 + 30 per cent ×
$50,000 = $85,000.<br>
● Manual assembly line: $75,000. (Note there is no event node for the manual assembly line.)
Given that the automated assembly line event node, at $140,000, has the highest expected value of the three choices, this becomes the rollback value for the next step of the analysis. Therefore, the expected value at the ‘invest in R&D’ event node is 30 per cent × $140,000 = $42,000. As can be seen, the expected value for ‘prototype is unusable’ is 70 per cent × -$30,000 = –$21,000.<br><br>
Finally, the expected value for ‘invest in R&D’ is $42,000 + –$21,000 = $21,000. As this value is higher than the ‘do not invest in R&D’ value of zero, we can state that the value of proceeding with the prototype, at the very start, is $21,000.<br><br>

### Top practical tip
<div style="background:transparent;
            border-radius: 25px; 
            font-size: 20px; 
            padding: 10px; 
            border: 5px solid lightgray; 
            margin: 10px;">Because decision trees can become extremely complex, getting the level of information just right is the true art of using them. You shouldn't have more than three or four variables in your analysis, so make sure you've chosen the most important ones when constructing your research.<br></div>
            
### Top pitfall
<div style="background:transparent;
            border-radius: 25px; 
            font-size: 20px; 
            padding: 10px; 
            border: 5px solid lightgray; 
            margin: 10px;">
While working through the details may consume the majority of your time, it is important to review the options you've presented to verify that they cover all conceivable outcomes for the decision. Returning to the previous scenario, CSM may not have considered the possibility of selling their new design to a Korean consumer.<br></div>

## Notion Templates
Get this high quality templates to help you with implemenation!

● [Decision Making Assessment](https://keymodels.gumroad.com/l/DecisionMakingAssessment)


## Further reading
Quinlan, J.R. (1987) ‘Simplifying decision trees’, International Journal of ManMachine Studies, 27(3): 221.<br><br>
Yuan, Y. and Shaw, M.J. (1995) ‘Induction of fuzzy decision trees’, Fuzzy Sets and Systems, 69(2): 125–139.<br><br>
