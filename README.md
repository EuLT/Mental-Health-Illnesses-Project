## Mental Health Illnesses EDA
 
This project is an analysis of mental health illnesses regarding the states in the United States.

I decided to narrow the data with the states in the United States so there could be a comparison between the same country, the other column chosen was treatment, this was to identify how many of the interviewed workers are actually under treatment, I think it is important to identify which state have more mental treatments.

The biggest issue was to change the data frame into states and the two columns of "YES": Received treatment and  "NO": Not Received treatment, this was done by using a slicing in each case and then joining the two variables. Another point I struggle was that after the slicing was done, the data frame was not conformed correctly until reset.index() was added.

Something interesting to see is that on both graphs appear the same states at first: "CA" and "WA", this means that there could be more interviews in those states and it needs further evidence.

Lastly, something import to highlight is that in these interviews there are more people under mental treatment as it is shown at the end of the analysis: 

YES           403
NO            327

This means that this kind of issues should be considered more by the companies to help the employees.
