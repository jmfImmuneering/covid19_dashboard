# covid19_dashboard
Wrangling covid19 data into data visuals

So far this just pulls the data from the Johns Hopkins initiative and does some basic graphing and comparisons. As a result, this data cannot be used for commercial purposes (my company is in my github name, but this is not a commercial endeavor or related to Immuneering in any way). Particularly interesting to me in this is that I like to understand a bit about time-resolved data, and the flat display of other dashboards doesn't really communicate that. 

# TODOS
I can think of a few features that should be added.
1. Dependencies - will sort that out to make this easier on others to run - but so far nothing exotic is necessary. It's clearly going to be easier to run this on a *nix-based system (`wget` is used).
2. Features - I'd like to add lagged-comparison to make CFR more meaningful - though this is questionable because insufficient testing across many countries makes this hard to interpret. But I'd like to at least capture the information.
3. I'm a newb with plotly - clearly there are ways to make this better but I'm actively exploring. 
