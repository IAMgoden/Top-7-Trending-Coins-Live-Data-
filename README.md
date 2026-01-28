# Top 7 Trending Coins (Live Data)

This repository runs an algorithm through the Ocean VS Code extension to fetch live cryptocurrency market data and determine the top 7 trending coins at the moment of execution. 
Results are generated in real time and reflect the current market activity.

# How it Works

+ The algorithm runs directly inside VS Code using the Ocean extension.

+ It retrieves live market data from a cryptocurrency API.

+ Coins are ranked based on current market activity to identify the top 7 trending assets.

# Getting Started
1. Requirements
VS Code (Version 1.96.0 or higher) [Download](https://code.visualstudio.com/).

Ocean Protocol VS Code Extension [Install from the Marketplace](https://marketplace.visualstudio.com/items?itemName=OceanProtocol.ocean-protocol-vscode-extension&ssr=false#overview).

2. Installation
Option A: Download as ZIP (Easier)

Go to this link.
Click the green <> Code button.
Select Download ZIP.
Unzip the folder.
Open the folder in VS Code.
You should see the Ocean Protocol icon in your Activity Bar. 

Option B: Using Git (Recommended) Open your terminal and run:

git clone https://github.com/stip1101/ocean-vs-code-algo-examples.git

3. How to Run a Job
Open the file algo.py.
At the top of the file, you will see a Configuration Section:
# ==========================================
#  Top 7 Trending Coins (Live Data)
Open the Ocean Protocol Extension panel in the sidebar.
Click Start FREE Compute Job.

4. Expected Output
When you run the script, you should see a ranked list of the top 7 trending cryptocurrencies, showing:

+ Coin name

+ Symbol

+ Trend score (e.g., 24-hour price change)
# Example output 
Top 7 Trending Coins (Live Data) - 2026-01-27 14:05:23
--------------------------------------------------
1. Bitcoin (BTC) - Trend Score: 3.42%
2. Ethereum (ETH) - Trend Score: 2.18%
3. Cardano (ADA) - Trend Score: 1.95%
...
Results are live and may vary each time you run the algorithm.

Powered for Ocean Protocol 🌊
