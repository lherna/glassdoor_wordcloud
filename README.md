# Glassdoor WordCloud Generator
There are many wordcloud generator's out there that can be used universally with any website, but this project was started mainly to focus on glassdoor review's of companies (that I have worked on, specifically CHC CONSULTING, LLC). 

Webscraping the website itself, when the code is run it asks for the amount of websites that the user will wish to review given that there are multiple pages per company of reviews on glassdoor. Once the quantity of websites is entered, the next thing the user is asked for are the individual websites (URL) themselves. 

For example, on glassdoor if we search for CHC CONSULTING, we can see that there are multiple pages for reviews. 
In this case we would enter 10 for the first question and then start entering the URL's consecutively: 

https://www.glassdoor.com/Reviews/CHC-Consulting-Reviews-E806647.htm

https://www.glassdoor.com/Reviews/CHC-Consulting-Reviews-E806647_P2.htm

https://www.glassdoor.com/Reviews/CHC-Consulting-Reviews-E806647_P3.htm

https://www.glassdoor.com/Reviews/CHC-Consulting-Reviews-E806647_P4.htm

https://www.glassdoor.com/Reviews/CHC-Consulting-Reviews-E806647_P5.htm

https://www.glassdoor.com/Reviews/CHC-Consulting-Reviews-E806647_P6.htm

https://www.glassdoor.com/Reviews/CHC-Consulting-Reviews-E806647_P7.htm

https://www.glassdoor.com/Reviews/CHC-Consulting-Reviews-E806647_P8.htm

https://www.glassdoor.com/Reviews/CHC-Consulting-Reviews-E806647_P9.htm

https://www.glassdoor.com/Reviews/CHC-Consulting-Reviews-E806647_P10.htm

Once the website is scraped, HTML code is extracted and temporarily stored to be cleaned up through different functions.
Finally, a universal dataframe containing the information of all of the different websites is made and plots are made according to the popular words that you can see and choose all the way up to the final product - wordcloud. 
