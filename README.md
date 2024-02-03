# Statistical analysis of passenger satisfaction with the services of the top 5 best Russian airlines in 2022✈️

### #webscraping #textanalysis #2Dcontingencytables #chisquare #python #excel #satisfaction
**Note:** Since this is a scientific paper for conference, there is many terminology and complex procedures in this work. You can read the conclusion after each part of the analysis to get a complete comprehensive of the analysis.

## Q&A about the analysis: 
1. What is the subject of the analysis? What is the top 5 best Russian airlines? These are: Aeroflot, Rossiya Airlines, S7 Airlines, Pobeda Airlines, Ural Airlines (airline order based on ratings from the website **[Hike It!](https://hikeit.ru/news/best-airlines)**).
2. How do we have dataset? The dataset was collected by me by scraping information in the two websites: TripAdvisor and Yandex Maps. (You can find the dataset in .csv file above).
3. What are the characteristics of the data set? The volume of collected data is 2458 reviews with 4 features: airline name, month, number of stars and comment content. In addition, the star rating system uses a 5-point scale, including: “Extremely unsatisfied”, “Unsatisfied”, “OK”, “Satisfied”, and “Extremely satisfied”.
4. Which analysis method will we apply? Throughout this work, method of analyzing two-dimensional contingency tables is conducted to evaluate the relationship between airlines service and their passenger’s satisfaction based on the number of stars in online reviews. Moreover, we can use basic test analysis method to extract the aspects most mentioned by the customer in their reviews.
5. What is the structure of the analysis? The analysis can be divided into three parts:
    
    1. Statistical analysis of the relationship between the airline name and the number of stars.
    
    2. Statistical analysis of the relationship between the month the review was written and the number of stars.
    
    3. Analysis content of the comments.
