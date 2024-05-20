# Dataset Columns:

DAY: The date or day of the trade.
EDGE: The difference between the trade price and the theoretical price.
EDGE_EUR: EDGE converted into EUR by multiplying the volume and a fixed currency offset.
VOLUME: Volume in lots of contracts traded.
GW: Numeric identifier for the exchange gateway/path the order was sent through.
LATENCY: Total system latency for the order (in nanoseconds).
SUCCESS: Indicator of whether the order was successfully traded (1 for success, 0 for failure).