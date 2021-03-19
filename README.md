# Twitter Crypto Sentiment Analysis
Using Twint to bypass twitter API call limit.

## How do **I** start?

Tested on an Ubuntu 18.04 Hyper-V Virtual Machine as root

1. Install Twint: ```pip install twint```
2. Run Twint with your cryptocurrency. This project uses Ethereum. Also include a date. ```twint --since 2021-3-19 -s ethereum -o ether-tweets-new.csv --csv```
