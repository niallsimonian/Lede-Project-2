Lede Project 2 : 'Trump still the biggest draw for Fox News Viewers'
 https://niallsimonian.github.io/LedeProjects/

In this project, with regards to data scraping, I aimed to demostrate my ability to used Python + BeautifulSoup to scrape data from the HTML of multiple web pages and then analyze that data using Pandas. 
Additionaly, I aimed to create export SVG files from DataWrapper and get comfortable editing/annotating them with Adobe Illustrator. I also wanted to play around with AI2HTML, in order to create dynamic graphs that change to fit different screen widths. 

With regards to findings, I discovered that "The Five" is by far the most popular show for Fox News (at least in the month of June). In addition, I noticed that President trump still seems to be one of the biggest draws for viewers to the network, as evident by episodes reacting to his indictment receiving the most views - as well as Bret Baier's interview with him outperforming all of his other episodes. 

I aqquired the data for this project through a site called Mediaite which consolidates nightly cable news ratings by episode/time of show. I created a jupyter notebook to scrape/parse the data for the first date and then, because each page had an identical format, I simply changed the link in the notebook for all the dates I wanted. I chose the four week period because this was the most accesible data. 
 
The data analysis process consisted of first eliminating the excess data- meaning the data for CNN, Newsweek, MSNBC etc. I originally intended to do more than one news-network, but simply ran out of time. I then had to create two new columns to split the views/shows because they were contained in the same column. From there, I was able to export my first csv file. I then created an additional csv file, using pandas, that sorted the episodes by view count. 

I progressed the most during this project in my data scraping and visualization skills. By the end of the project, I felt very comfortable looking through HTML code using the Inspector, in order to find out how to extract it. This was in part due to the fact that I explored a number of topics/sources before settling on this one. In addition, I taught myself AI2HTML using Soma's Youtube videos and related resources online; I now have the software readily available and would feel comfortable applying it in limited capacity (for now!). 

If I had more time, I would have tried to create a horizonal scrollytelling site with my primary graph that I could have then animated to highlight certain dates. However, after begining to try this, I realized I simply could not get it done in time. Additionally, I would have expanded my analysis to include the other networks found in the original data set.  

Original ata can be found at : https://www.mediaite.com/category/daily-ratings/
Trump Drawing was sourced from: https://friendlystock.com">FriendlyStock


-Niall Simonian
