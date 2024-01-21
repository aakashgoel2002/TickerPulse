# TickerPulse
**A Data Scraping Project, which fetches the current price of Stock, Crypto and Commodities.**

Step 1: Install Docker on the local system

`pip install docker`

Step2: Build the Docker Image

`docker build -t ticker-pulse:latest .`

Step 3: Run the Docker Image

`docker run -d -p 5000:5000 ticker-pulse:latest`

Your Web-App is Live on the localhost port 5000 of your system.
