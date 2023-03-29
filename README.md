# Field Work Monitoring: Fall 2023

**Team members:** Dani Freund - I'm working alone on this one!

**Product title:** Do wolves stress beavers out? Monitoring field work for 2023 fall field season.

**Product type (report, presentation, Shiny app, etc.):** Shiny app. This may change depending on the type of data I use. Some of the data (wolf locations) are sensitive and cannot be shared with the public.

**Product purpose:** For my field work, myself and the field crew enters in hundreds of lines of data at the end of the day when we get back from the field. It's difficult and time consuming to keep up on checking the data for errors, and errors are inevitable given the amount of data that is recorded every day by exhausted technicians. I am going to build an app that updates every day during the field season after people have entered their data, and represents the data visually (maps, graphs, interactive tables, ect.) so that it is easier to check than just eyeballing a google sheet and hoping to catch errors.

**Data sources:** I will be using my own data, which is stored on google drive. I will potentially be using wolf locations from the GPS collar server that we use to track the wolves we study. My own data can be made publicly available, but the wolf locations cannot be because wolves are on the endangered species list and releasing their live locations to the public may make them targets. I plan to use this app this fall to check my data, which is after the class. So the data cannot be made available after the end of the class. After my field season, it may be possible to make the wolf data publicly available.

**Product features:** The main questions I am trying to answer are how much work was completed in a day by the field crew, how much work do we have left, and if there are any errors in the data entered.

The main data product will be a leaflet map showing what has been sampled for my fieldwork and what still needs to get done. I have started working on it and provided a screen shot of a rough draft below. It will show each pond where I do my work, and the transects that have been sampled.

![Rough Draft Map](images/Screenshot%202023-03-28%20at%208.45.05%20PM.png)

I'll also make a number of graphs and tables summarizing the data that has already been collected so I can quickly check everything in one document. My data is entered into a number of different google sheets, so having everything in one html document that is updated every evening will hopefully speed up my data checking process. These graphs and tables will hopefully include a number of warnings indicating if there are any errors in the data entered.

**Automation:** I am going to set a time every night where the code is run and updated. I will use this using actions in GitHub.

**Interactivity:** I want everything to be searchable for specific locations in my study area. For example, I can use a drop down menu to pick a specific pond and all graphs and tables (and maybe even maps if that's possible) will be filtered for that pond.

**Programming challenges:** The map will be a challenge. I have quite a few map layers planned for it that all come from different data sources. I'm also nervous about automating the code because I've never done that before.  

**Division of labor:** It just me bb!
