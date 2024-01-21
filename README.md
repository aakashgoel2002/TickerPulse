# TickerPulse
**A Data Scraping Project, which fetches the current price of Stock, Crypto and Commodities.**

Step 1: Clone this Repository

`git clone https://github.com/aakashgoel2002/TickerPulse.git`
`cd TickerPulse/`

Step 2: Install Docker on the local system

`pip install docker`

Step3: Build the Docker Image

`docker build -t ticker-pulse:latest .`

Step 4: Run the Docker Image

`docker run -d -p 5000:5000 ticker-pulse:latest`

The Web-App is Live on the localhost port 5000 of your system.
