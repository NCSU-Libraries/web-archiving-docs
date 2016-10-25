# Recurring Crawl Quality Assurance
While most of the heavy quality assurance work occurs during the process of adding a new seed to the collection, certain steps must take place to ensure that recurring crawls are not encountering any errors. There are two main aspects to recurring crawl quality assurance. During the qualitative analysis phase you will want to visually inspect websites as they appear in the wayback machine to ensure proper rendering. In addition to visual inspection, you will want to take a close look at crawl reports to gain better insight into the amount and types of data being collection.

## Qualitative Analysis
It is important to maintain ongoing visual inspections of our archived seeds to ensure that they continue to render properly to visitors of the archive. After each recurring crawl (for monthly and quarterly seeds) you should inspect the home page and first level navigation items of the site. Ideally this should be done within about one week from the conclusion of the recurring crawl. The same type of inspection should be done on a monthly basis for the seeds that are in the daily and weekly crawl frequencies.

## Quantitative Analysis
Due to the large number of seeds in our collection, we have to rely on quantitative data to better understand the efficacy of our crawls. Using the amount of data collected on any given crawl, and comparing it to other recurring crawl reports allows us to identify any outliers which may indicate an issue. For example if the monthly crawl generally returns about 6GB of data and then in one month jumps to 10GB there may be an issue, and you will need to closely inspect the crawl report.

### Data Budget Management
We have a set data quota per year that we must remain within. This is why maintaining an active awareness of our current data budget, and the average data usage for recurring crawls is helpful. We have created [this Google Spreadsheet](https://docs.google.com/spreadsheets/d/126EbXKlCVFKFWxf8rb6wjbqCKzDGBB1FuW8sA-nspZg/edit#gid=183371544) to help us track our data usage throughout the year.


### Major Website Changes
It is important to document when a website we are currently crawling undergoes major changes or a complete redesign which could change the quality of the crawl. This will prompt the web archiving technician to complete a test crawl on the redesigned site, to ensure that regular recurring crawls will complete correctly.
