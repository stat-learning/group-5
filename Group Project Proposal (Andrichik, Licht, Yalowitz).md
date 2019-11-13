---
title: "Group Project Proposal"
output:
  pdf_document: default
  html_document: default

---
Joe Yalowitz, Eva Licht, Alyssa Andrichik
  
1) Portland updates its 911 Dispatch feed every thirty seconds, providing a list and location of the 100 most recent 911 calls.  (http://www.civicapps.org/datasets/911-dispatch-incidents-kml, http://www.civicapps.org/datasets/911-dispatch-incidents-georss).  This unique dataset would allow us to train a model using one set of 100 incidents and test using more recent sets of 100 incidents. We would use other datasets from the same source to compile several questions, all of which are predictive.
  a) Can we predict the location of pedestrian traffic accidents using the streetlights     (http://www.civicapps.org/datasets/streetlights), sidewalks (http://www.civicapps.org/datasets/sidewalks), and curbs (http://www.civicapps.org/datasets/curbs) datasets?
  b) Can we predict assault locations using previous crime (http://www.civicapps.org/datasets/crime-incidents-2012) datasets?
  c) Can we predict time and/or location of future drunk driving incidents based on previous drunk driving incidents?

2) Can we build a model that accurately predicts what the overall perception of corruption is for a country in Africa based on the rates of various types of bribery in that country? For example, maybe a high percentage of people having to bribe the police leads to a higher perception of corruption in a country than a high percentage of people bribing schools? Regression. Predictive. We will train our data using Transparency International's Global Corruption Barometer for Africa. https://www.transparency.org/files/content/pages/GCB_Africa_2019_Methodology_and_Data.zip

3) Could we build a model to see if we can predict someone’s Harry Potter Hogwart’s house based on a demographic data and a media consumption survey that we create. This would be a classification and predictive problem. For the data, we would have to create a survey that included various demographic questions and questions about tv show, movie, book, and music preferences, and then include a question on what Hogwart’s house they identify with (including brief descriptions of each house) and then would see if interactions between the other survey questions can function as a predictive model for the Hogwart’s House.