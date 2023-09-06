# A webscraper for the site: adapt.io

In this project, I was asked to scrap company listings from the website: adapt.io

## Data Requirements

The data requirements come in two folds. The first data output required to have:
Company Name
Source URL

The second data output required to have:
- Company Name
- Company Link
- Company Web Domain
- Revenue
- Employee Size
- Industry
- Location
- Contact Details:
    - Contact Name
    - Contact Job Title
    - Contact Email Domain
    - Contact Department

I have also added **Similar Companies** to the data which might help to group companies later on.

## Technical Feasibility
I had to run multiple test crawls to investigate whether there will be problems scraping the data. The website tends to show *“Sorry, we're down for maintenance. :( Thanks for your patience, will be right back!”* when the website is visited repeatedly in a short amount of time. This is easier to counter than other forms of anti-bot countermeasures like captchas. The problem was solved by adding a sleep time to the scraper.


I have scraped all of the A companies which took about an hour and 51 minutes.

> The plan is to decrease the time of the scraping down to 1/4th of the time stated above.
