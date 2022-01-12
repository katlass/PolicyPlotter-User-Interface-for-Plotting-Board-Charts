# PolicyPlotter-User-Interface-for-Plotting-Board-Charts
Policy Plotter – R Shiny Application: 

Solved a core problem facing the Federal Reserve Board by independently developing a plotting application to vastly increase the efficiency of creating charts/exhibits for The Federal Open Market Committee (FOMC). This committee determines monetary policy for the United States. I automated the process of chart creation which draws focus away from data and code integrity. 
 
Motivation:

●	The process of editing charts up to governor level is rigorous and time-consuming. Editors must type out many iterations of suggested edits and research assistants must, with varying degrees of technical skill, make these custom changes in R often not included in the current R plotting package on tight deadlines.

●	This application eliminates the need for this process. With this new application, anyone regardless of technical background can quickly and easily make exhibits. 

 
 
Technical Achievements:

●	Solely built out the user interface, server, and plotting function underlying the charts in R.

●	Soft-coded: the application is coded such that sections only need to compile a very basic datafile in R. It then uses list indexing to auto-populate with these datasets and display all the series names within the datasets.

●	The most technically challenging portion of development was in saving the inputs to the application to reload and modify them later. This requires saving all UI elements and reactive values in the server to file, then re-pushing this information to the application to use again in the future. So, you must set the application in a state where it is constantly waiting for inputs but is comfortable just taking supplied reactive values and modifying the UI inputs accordingly. 
 

 
Features:

●	Simple chart edits can be made and seen in real-time like changing date range, the color of series, including a second y-axis, displaying different increments on the x-axis like showing day, business day, month, year and/or custom ticks, and many more. 

●	Some notable features include a checkbox to create a stacked line chart, a bar chart, to do a moving average on the data, to scale the data, and to do a change in values since a specific date.

●	Once done designing, the final exhibit is generated and can be saved to any location on the user’s computer. The inputs can be saved for later and reloaded and modified again.
