# Investment Game - Pygame

## Overview
Investment Game is a captivating simulation game developed in Pygame. The game challenges the player to act as an investor navigating the financial world, backed by a robust infrastructure developed using Numpy. By harnessing real-world financial data from sources like yfinance and NASDAQ's Quandl, players interact in a timelapsed environment that moves day-by-day. In this simulation:

- Players can opt to keep their finances in a savings account or dive into the diverse world of portfolio investments.
  
- Within the portfolio, they have the freedom to invest in a variety of stocks, monitoring their progress as days pass.

- Players can make crucial decisions every day: invest in specific stocks, divest, or pull back their investments to the safety of a savings account.

<img src="https://github.com/VenturaBleak/InvestmentGame/blob/master/Investment_Game.png" width="90%" height="90%">

## Repo Structure
### Main Directory:
- `utils/`: Folder containing utilities mainly for fetching and organizing real stock price data.
- `__init__.py`: Initialization file.
- `data_check.ipynb`: Jupyter notebook for data verification.
- `data_object_test.py`: Script to test data objects.
- `game.py`: Core game script powered by Pygame.
- `interface.py`: User interface related scripts.
- `simulation_backbone.py`: The core backbone of the simulation, built using Numpy.

### Utils Directory:
- `__init__.py`: Initialization file.
- `data_fetcher.py`: Script for retrieving stock price data.
- `data_object.py`: Defines data objects for structured storage.
- `data_prepper.py`: Prepares data for use in the game.

## Game Mechanics
As investors, players use real stock price data to make informed decisions. By simulating a time-lapse of days, the game offers a dynamic experience where stock prices fluctuate based on real-world data, challenging players to optimize their investments for maximum returns.

**Happy Investing!**
