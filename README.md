Steps to better understanding your Interactive Brokers account:

1. Create Flex requests that retrieve every available field

2. Save returned Flex XML reports for contiguous non-overlapping periods of
   time. At time of this writing I was able to create annual reports for 2011
   through 2014, and 2015 year-to-date.

3. Use the FlexStatement class to parse individual reports, or modify
   `analyze-comprehensive.py` to your suiting to roll up multiple years of P&L.