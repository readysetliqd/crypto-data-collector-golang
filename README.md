# crypto-data-collector-golang
Collects historical trade data from crypto exchanges and stores them in a timescaledb database

# Description
This program is meant to be the backend deployed on an AWS server and ran continuously. It will collect trade data from exchanges and store them into a timescaledb database. There will be a separate repo for the frontend installed locally to read data from the server.