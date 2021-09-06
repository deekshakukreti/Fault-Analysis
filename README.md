# Fault-Analysis


# Business Scenario
When deciding upon resourcing plans it is important to consider likely fault volumes. Since the orders that fuel the provision work are typically taken 2 weeks in advance, a forward looking forecast of fault volumes would enable a more accurate prediction of the number of provision volumes to take on each week.
You have been provided with the fault volume and rainfall data for a single geographic area for 3 years. Please use this data to create a model to predict the expected daily fault intake based on weather events. Detailed explanation of the fields provided is given below.
At the interview you will be given 10 minutes to present your findings. The presentation should give an overview of your findings and be targeted at a senior stakeholder level. Please provide a copy of your findings for review before the interview.

Things you may want to consider in the model;

1 Both short term and long term impact of rainfall

2 Impact of weather events on different fault types

3 Other things that might impact fault volume


Data provided:

Fault Data: This contains information of individual faults for a single region over a 4 year period.

Fault ID: Fault identifier



Report Date: The date that the fault was reported

Initial MFL: Location of the fault;

CA: Customer appointed (home)

CE: D-side overhead network

EX: Exchange

FU: Frames (exchange)

LN: E-side Underground network

OK: Line has tested OK

OTHER: Other faults



Rainfall: This contains daily rainfall information for the same 4 year period

Observation Date: Date

Rainfall mm: Rainfall (in mm)

Calendar Lookup: This contains a lookup to give calendar information such as day of week and bank holidays

Actual Date: Date

Day of Week: Day of Week

Day Num Cal Week: Numeric value of day within the week

Day Num Cal Month: Numeric value of day within the month

Day Num Cal Year: Numeric value of day within the year

Bank holiday: Flags the bank holiday (Y: bank holiday)
