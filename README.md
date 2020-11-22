# stadium-attendance-prediction
Cross-validated Lasso regression for predicting attendance on football stadiums.

The idea behind this project is to build a **machine learning model** that would predict the number of attendees of polish ***Ekstraklasa*** (1st division) foootball matches as accurately as possible. It is important to mention, that unlike in *Bundesliga* or *Premier League*, polish stadiums are rarely completely filled. This in turn, creates the possibility to invstigate what lures people into buying tickets and what discourages them from doing so. The considered timespan begins with the start of 2013/14 season, when there was a major change in the league structure (final rounds were introduced and number of matches has increased) and ends with the Coronavirus outbreak in February 2020. This is an **end-to-end** project, that includes **data gathering** through web-scraping and external API, **data cleaning, transforming** and **modelling**. In result, a **cross-validated Lasso Regression** model has been developed.

If you are interested in results only, feel free to jump to the Analysis section of the Notebook straightforwardly.
