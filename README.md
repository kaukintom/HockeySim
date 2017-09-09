
### Fantasy Hockey Simulator
Created to simulate the point production of hockey players for an NHL season and accommodate a fantasy hockey scoring system. This project would be used to aid in fantasy hockey player selection.

### Getting Started
Upon opening the Excel file, there is a button that provides a tutorial on how to use the simulator.

1) The user will specify the amount of fantasy points recieved for all the relevent and available categories, then click the button that reads "Calculate Fantasy Points". Any category not containing a value, will not be included in the generated table.

2) To conduct simulation, then click the button that reads "Simulate Next Season's Point values". The user can specify how many simulations to conduct. The generated table from the previous step will include 4 new columns of data, all related to the simulated results.

At any moment in time, as long as a table of hockey players is present on the worksheet (which there always should be), any relevent category to the table can be sorted by clicking button that reads "Sort By Category".

This workbook uses userforms for the tutorial, sorting, and simulation components. This helps guide the user and add convenience to the process.

### About The Simulation
Note: Data collection and generated probability distributions were conducted in another workbook.

Simulated results are based on how a player performed in the prior season. If it was a player's first season in the NHL, then it is based on how they are categorized (when first season occured and how they performed in their first season). The similated results are currently only goals and assists.

Simulations are conducted using a normal distribution, with a mean and variance based on the season they are entering and how they are categorized.

Some category of players currently contain too few entries to develop an accurate probability distribution for, so some hockey players may not have their next season point totals simulated.

### Acknowledgments
McMaster Commerce course 3QA3: Introduced simulation and how simulation can be achieved
