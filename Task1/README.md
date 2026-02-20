Each group member should provide feedback on the other group members’ work. Be detailed and specific where possible. The quality of this feedback can play a part in your grade.

You can provide feedback to your group members in many different ways (live in a meeting, offline, or however else you devise) but the feedback must be documented here! 

Please replace “Feedback giver #x” with a group member’s name below and add feedback as a bulleted list below. Note: There is a pencil icon on the top right of the README file (when you are viewing the README.md file) that allows you to edit.

- Amanda Baright
  + Great introduction section. I loved the general overview of the impact of pollutants like benzene, the information on the dataset of interest, and the high-level overview of what task 1 examines. I especially like how you introduce the gradient descent algorithm in an approachable way, one geared towards the report's audience. Similarly, the description of the two different approaches is well explained and sets up the narrative part of the report.
  + In the data cleaning portion of the report, I recommend converting the `-200` values to be `NaN` as this would allow you to use `.dropna()` to drop any missing values for a variable of interest.
  + This is more for ease of readability, but you could consider renaming the variables to something more meaningful. For example, the (GT) values could have the (GT) piece removed, and the sensor variables could be relabeled as `sensorCompound`.
  + For the user-defined functions created throughout the program, I recommend adding docstrings to provide additional information on the function you are creating. This could include specifying the type of inputs, what the function is doing on a high level, and what the function is returning.
  + For the decimals you are working with throughout the report, I recommend using `.round(decimals = 2)` to have cleaner outputs. Additionally, for some of the print statements, you may want to consider adding a string component that provides context on the number being printed.
  + Overall, I liked how much narrative you added to the report. These narratives help add much-needed context to what the gradient descent methods are, how they are being used, and what to expect with the output.


- Feedback giver #2
  + item
