This python notebook loads and transforms strings of Stock orders and processes the top movers in given stream of data.
Each order contains either buy/sell/cancel/limit/trade operations along with number of shares, timestamps and symbol tickers and other important information.

- Slicing of data in code can be done by defining message schema’s and slicing the raw data from the
schema’s (commented example mentioned).
- TimeStamps can be used to further drill down on data based on time intervals.
- Existing code can be updated with implementation of Spark (using PySpark) or other advanced parallel -computing frameworks.
