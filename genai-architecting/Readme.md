## Functional Requirements

The company wants to invest in creating their own infrastructure because of data recidency and privacy requirements.
The cost of managed services for GenAI might be greater than the budget for this requirement i.e. 10-15K USD.
An AI PC will be purchased, with the available budget of 10-15K.
There are 300 active students located in the city of Nagasaki.

## Non-Functional Requirements

The portal must support minimum 300 concurrent users. 
Uptime of the portal should be atleast 99.99%.

## Assumptions
Assuming that the chosen Open Source LLMs are powerful enough to run on the AI PC/hardware purchaged.
The AI PC/hardware would act as a server hosted locally in the office and connect to internet. It should have enough bandwidth to serve 300 students.

## Constraints

The budget might not be enough to buy a good hardware that can support LLMs with large parameters > 40 B.

## Data Stategy
To avoid using copyrighted materials, purchase of training materials would be required. 
These materials will be stored in our database and will be available for students to query.