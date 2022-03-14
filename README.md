# binance-example

The tasks given for the home assignment:

Print the top 5 symbols with quote asset BTC and the highest volume over the last 24 hours in descending order.
Print the top 5 symbols with quote asset USDT and the highest number of trades over the last 24 hours in descending order.
Using the symbols from Q1, what is the total notional value of the top 200 bids and asks currently on each order book?
What is the price spread for each of the symbols from Q2?
Every 10 seconds print the result of Q4 and the absolute delta from the previous value for each symbol.
Make the output of Q5 accessible by querying http://localhost:8080/metrics using the Prometheus Metrics format.


Pre-requisite:
We have ran the python code on the Mac OS and can be ran on any instance with installed redhat enterprise linux

python3
pip3

sudo yum install -y python3-pip

pip3 install -r requirements.txt
pandas==1.2.3
requests==2.22.0
simplejson==3.16.0
prometheus-client==0.9.0

Usage
Instruction on how to run the script.

python3 client.py
