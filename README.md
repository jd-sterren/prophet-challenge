# prophet-challenge

# Results
Traffic patterns indicate that June, February, March, and December are the most popular months with Tuesdays and Thursdays being the top two days in the week.  The time of day least active is around 0700 to 1000 hours where it begins to gradually increase, peaking at midnight, prior to a quick decline.

Most of the questions in the beginning have been answered already.

# Notes
pct_change was used to determine the change from the previous row.
Rolling, as requested using a window of 4, allows calculations to occur within consecutive periods.
window1: [1,2,3,4]
window2: [2,3,4,5] and so on.

# References
pct_change. Pandas. https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.pct_change.html
Rolling. Pandas. https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.rolling.html