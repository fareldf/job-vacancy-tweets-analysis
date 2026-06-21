# Job Vacancy Tweets Analysis
Twitter has become a popular platform for companies to share job vacancies and reach potential candidates. Analyzing companies, job positions, engagement, and posting patterns helps uncover hiring trends in the digital labor market.

**Disclaimer**: this analysis is still at a **basic level** and may contain errors or inaccuracies. So, further validation are recommended.

## Dataset
The data is downloaded from [Kaggle](https://www.kaggle.com/datasets/prasad22/job-vacancy-tweets). This dataset were collected between 1 January 2019 and 10 April 2023, with the help of snscrape library of Python and are provided in a CSV format by the author, Prasad Pratil.

This data consists of these columns:
- ID: The unique identifier of the tweet
- Timestamp: The date and time when the tweet was posted
- User: The Twitter handle of the user who posted the tweet
- Text: The content of the tweet
- Hashtag: The hashtags included in the tweet, if any
- Retweets: The number of retweets as of the time it was scraped
- Likes: The number of likes as of the time it was scraped
- Replies: The number of replies as of the time it was scraped
- Source: The source application or device used to post the tweet
- Location: The location listed on the user's Twitter profile, if any
- Verified_Account: A Boolean value whether the user's account has been verified
- Followers: The number of followers as of the time the tweet was scraped
- Following: The number of following as of the time the tweet was scraped

Link to the dashboard is [here](https://datastudio.google.com/reporting/59b6395a-47be-45f8-937e-93c99d67041c).
