
hw1_q2.xml

Options IN ORDER:

City
- San Diego
- Seattle

State
- California
- Seattle

Forecast
- current
- Short term
- long term


===================================================

hw1_q3.xml

Main Options
- One -> IN ORDER
- Two -> ALL AT ONCE 

Options IN ORDER:

City Options
- San Diego
- Seattle

State Options
- California
- Seattle

Forecast Options
- current
- Short term
- long term

Options ALL AT ONCE:

City, State, Forecast Options
- [ San Diego, Seattle] , [California, Washington], [current, Short term, long term ]


One major problem I encountered with the assignment was constructing the grammar 
for question three to make the system to be able to parse all options all at once. 
However, after much browsing on the documentation page, I have managed to resolve 
the problem. The options are parsed individually under different rule id and then
concatenated together. 

One insight would be that lots of variations of option combination is possible via
the same technique. Thus, 






