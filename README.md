# Scraping Top Repositories for Topics on GitHub

## Github
GitHub is an Internet hosting service for software development and version control using Git. It provides the distributed version control of Git plus access control, bug tracking, software feature requests, task management, continuous integration, and wikis for every project. Headquartered in California, it has been a subsidiary of Microsoft since 2018.

It is commonly used to host open-source software development projects. As of January 2023, GitHub reported having over 100 million developers and more than 372 million repositories, including at least 28 million public repositories. It is the largest source code host as of November 2021.

## Web Scraping
Web scraping, web harvesting, or web data extraction is data scraping used for extracting data from websites. Web scraping software may directly access the World Wide Web using the Hypertext Transfer Protocol or a web browser. While web scraping can be done manually by a software user, the term typically refers to automated processes implemented using a bot or web crawler. It is a form of copying in which specific data is gathered and copied from the web, typically into a central local database or spreadsheet, for later retrieval or analysis.

***Steps to follow to complete the task***
- We will scrape the GitHub repositories topic page: https://github.com/topics with the help of Python requests and BeautifulSoup Library.
- We will create a list of all the topics with description and their Url and save it into the pandas dataframe.
- Each topic is further scraped, and extracting the username, repo title, repo URLs, and number of stars they received.
- Saving the whole data in the data folder with topic_name.csv with the below format:

Repo Name,Username,Stars,Repo URL

three.js,mrdoob,69700,https://github.com/mrdoob/three.js

libgdx,libgdx,18300,https://github.com/libgdx/libgdx

## References
- Building a Python Web Scraping Project From Scratch. [link](https://jovian.com/aakashns/python-web-scraping-project-guide)
- [Github Topics](https://github.com/topics)
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- Building Webscrapping project by Jovian. [link](https://www.youtube.com/watch?v=RKsLLG-bzEY)
