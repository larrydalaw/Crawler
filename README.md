# Crawler
Java crawler implementation using crawler4j
Uses latimes.com as a seed site to produce statistics. 
Sample output in Crawlreport_LAtimes.txt

Generates 3 csv files:  
1.Fetch : All visited sites with the Http status codes  
2.Visit : Data of all the websites successfully crawled  
3.Urls : All outgoing links with tags as OK(belonging to domain latimes.com) or N_OK(not belonging to latimes.com)
