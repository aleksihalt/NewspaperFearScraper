# NewspaperFearScraper

Scrapes newspaper websites and counts the number of occurences of words 'death', 'dead', and 'die' to compare scare-tactics of different media outlets.

### Background
Recently I have been interested in how different news media outlets treat the ongoing coronavirus situation. I have noticed my own mental health being affected by the amount of news that I read so I wanted to quantify the differences on some of these newspapers. My simple hypothesis was that newspapers like the Daily Mail rely on more fearmongering tactics than some of their competitors in order to attract clicks and readers. I created a webscraper that pulls titles and articles from the newspapers' websites and counts the occurences of "scary" words. The words I used for this simple exercise were "death", "die" and "dead". I created a scraper for the Daily Mail, and noticed that it also ran on the Guardian's website. I wanted to compare these two news outlets and see if they have significantly different usages of these words. 

The outcome was as expected. On the day of testing, The Daily Mail used the aforementioned words 4.12 times per article, and 0.2 times per title. 

On the same day, the Guardian used these words 2.07 times per article (half the amount of the Daily Mail), and only 0.018 times per title (one-tenth of the Daily Mail's usage). It would be interesting to take this further and track the progress of fearmongering over a longer period of time and with more newspapers.

I learned a lot about how websites are scraped and how to pull interesting information from a large set of writing. Also gained better understanding of how websites are laid out which will be useful in the field of web development.
