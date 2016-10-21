# Ongoing Maintenance
In order to maintain consistency throughout the archive, and to ensure that it is properly updated there are a few recurring tasks that should be regularly carried out. By regularly updating crawl schedules, seed redirections and the active state of seeds in the collection we can ensure that the collection we are presenting aligns well with our collecting strategy.

## Crawl Schedules
Part of the organizational structure of our web archive is based on grouping similar sites together, and crawling them at similar frequencies. This allows us to crawl news sites with one frequency, major college or university-wide departmental sites with another, and smaller sites with yet another frequency. These frequencies roughly correspond to the likelihood that information on that website will change. You will also notice a correlation between the number of seeds and the frequency of crawls, the more frequent the crawl the fewer seeds that it is likely to contain. Currently we have the following regular crawls scheduled:

- Daily: The websites in our daily crawls include the main university website (ncsu.edu), the NC State University News site (news.ncsu.edu) as well as the two campus newspapers. Information on these sites is likely to change on a daily basis, so it is important to capture that data while it is available.

- Weekly: The websites included in our weekly crawls include the college and department level news sites. These sites change frequently, but not frequently enough to require daily crawling.

- Monthly: The websites in our monthly crawls mostly represent the main college-level websites as well as the websites of campus wide administrative units such as the libraries of the office of information technology.

- Quarterly: The websites in our quarterly crawls represent smaller department level websites throughout the organization.

### URL Redirection / Seed Updating
From time to time website configurations may change and a particular URL may be swapped out for a new version. Generally when this happens the old URL is redirected to the new URL for some period of time. However, redirections are rarely permanent. In the scope of Archive-It there are two types of redirections that we should be aware of, both should be handled differently.

- HTTP vs HTTPS - Often when adding a seed we may not notice that the site subtly redirects to an HTTPS version of the website even if the seed specified HTTP. It is best to catch these redirections while conducting QA before placing the seed into a scheduled crawl. However, if regular crawls have started, and you don't want a new seed it is likely fine as long as the seed URL is the insecure (HTTP) and is redirecting to the secure (HTTPS) version. The reason it is okay to rely on this redirection to continue is that the domain hasn't really changed, so the issue of the old domain going away (no longer being valid and registered) should not exist.

- Permanent - Due to regular updates of websites the URL structure may change. For example https://ncsu.edu/engr may become https://engr.ncsu.edu. This would be an example of a permanent, deliberate URL redirection. In this case you would likely want to add the new URL as a new seed, and use seed metadata to note where the new URL is being redirected from and where the old URL is redirecting to. You will also want to mark the old URL as inactive in the seed settings panel.

### Active / Inactive Seed and Collection Management
Archive-It gives administrators the option to label seeds or collections as active or inactive. Active seeds are crawled according to the schedule they are placed on. Inactive seeds remain visible as part of the collection but are not crawled according to the crawl schedule. The most common reason for setting a seed as inactive is that the URL for the seed is no longer valid. Either the website was taken down or the URL has been permanently redirected to a new URL. By marking it as inactive, visitors to the collection can still find the seed, and see all of the capture dates.
