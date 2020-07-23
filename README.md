# implied
Fork of [implied](https://github.com/cran/implied) intended to add additional (untested) functionality to remove margin if you have both back and lay prices from a betting exchange. This takes the probability gap between back and lay prices, finds this difference relative to the differences for selections in the rest of the market and removes margin accordingly.

Has the benefit of being capped between back and lay prices, and is potentially less sensitive to extreme illiquidity than the midpoint.
