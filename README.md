# web_ant_apprunner

The Web Ant Crawler is developed to scrape through courses offered in the iNeuron website.

It scrapes list of all the courses provided in the iNeuron website including Category and SubCategories.
User then can browse through these categories / subcategories to view all the courses within them.
When user clicks on any course , they can view the summary detail of the course from the website.
User can then save the course detail in Amazon S3 storage.
All the course related data scraped is stored in mongo DB.
We also store the course related details in MySQL using this application.
This application is deployed in the Beanstalk , Azure & AWS. [This is AWS EC2 deployed code]
The application uses logging to log all the information.
All the required packages have been provided in the requirements.txt file.
Data is scraped only for learning purpose and is deleted and app removed from deployed server.
