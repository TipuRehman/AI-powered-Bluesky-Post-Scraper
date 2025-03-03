AI-Powered Bluesky Post Scraper



Project Overview


This project is an AI-powered web scraper that extracts public posts, images, captions, and descriptions from Bluesky, a decentralized social media platform. The scraper automates the process of retrieving a user's latest post, their profile details, and associated images for further analysis.



Key Features


✅ Automated Post Scraping – Fetches the latest post, including its text, metadata, and images.

✅ Profile Data Extraction – Retrieves user details, profile picture, and bio from Bluesky.

✅ AI-Based Text & Image Analysis – Processes extracted text and images for sentiment analysis or content categorization.


✅ Selenium & BeautifulSoup Integration – Uses Selenium to handle dynamic web content and BeautifulSoup for parsing.


✅ Scalable & Extensible – Can be modified to support other social platforms with similar architectures.


Technology Stack


Python – Main programming language


Selenium – For automated web browsing


BeautifulSoup – For HTML parsing and data extraction


Requests – For handling HTTP requests


WebDriver Manager – For managing browser drivers


How It Works


Fetch Post Data – Sends a request to the target Bluesky post URL and scrapes title, description, and metadata.


Extract Profile Information – Uses Selenium WebDriver to navigate the owner's profile and extract profile picture, bio, and post details.


Save & Process Data – Stores extracted data for further AI-based analysis (e.g., sentiment detection, content classification).
