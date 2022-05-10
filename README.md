# Python-projects

A final project for Webscrapping labs (WNE UW)

Both codes are responsible for scraping details about 100 most popular people from movie industry (source: movie database filmweb.pl) like:
- name
- birtplace, birthdate
- grade , number of opinions
- the most popular films in which the actor starred, his/her most popular roles
- number on the top list, his/her profession

See the output.csv file.

Beuatiful soup - just run file .py

Scrapy- for the results of scrapy go to scrapy folder, first run step1.py file using command 
'scrapy crawl step1 -o output.csv' - this file will write the links of 10 pages into a output.csv file. 

In the file step2.py from all those 10 links 10 pages will be scraped (together 10* 10 = 100 pages).
To get the final file with the scrapped data run command scrapy crawl filmweb2 -o final_output.csv.

