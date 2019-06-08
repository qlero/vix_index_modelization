Desc: Implementation with a Jupyter Notebook of the VIX index modelization provided in its CBOE white paper, which you can browse here:

> https://www.cboe.com/micro/vix/vixwhite.pdf 

Packages necessary to run the script: 

> datetime, pandas, numpy, matplotlib,  math, re, requests, xml.etree.ElementTree scipy, yahoo_fin

Disclaimer: The use of the yahoo_fin module can lead to some issue when running outside of market hours as yahoo may sometimes
set the bid and ask value of options to 0 (happened on June 6th, 2019)

Update on June 8th, 2019:
1. Updated function comments
2. Updated how near- and next-term Fridays are calculated
3. Updated markdowns for: pronounciation, punctuation, missing information
4. Patched the VIX formula: some days could yield a negative sigma square
5. Updated the README.md to reflect changes

