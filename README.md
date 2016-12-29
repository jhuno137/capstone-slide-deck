# Coursera - Data Science Specialization Capstone Project Slide Deck Files
  
PredictR is a Shiny app which contains a predictive algorithm similar
to the applications used in cell phones.
  
The application is hosted in [shinyapps.io](https://www.shinyapps.io/). The
URL for the app is: 
  
[https://acamacho.shinyapps.io/predictr/](https://acamacho.shinyapps.io/predictr/).
  
Main Features:

- Developed using R and most common packages used in Narutal Language Processing such as [mt](https://cran.r-project.org/web/packages/tm/index.html)  
- n-gram language model (unigrams up to four-grams)
- Markov Chain used to select candidated based on input
- Stupid Backoff smoothing method used to calulate scores on candidate words
- SQLite database to store language model
- Shiny App featuring a cell phone SMS application
