# easyscrape-bonanzasuggest
Scrape Etsy search suggestions with Python

<img src="https://github.com/amazingjoe/amazingjoe.github.io/blob/main/imgs/Easyscrape.png" width="50%"/>

## Instructions

1. Install:

```
pip install easyscrape-bonanzasuggest
```

2. Get Etsy Suggestions for a Search Term:

```python
from easyscrape_bonanzasuggest import querysuggestions as BS

# Request suggestions for a search term
BSResults = BS.query("Mony Python")
BSResults

['monty python holy', 'monty python', 'nwt monty python', 'monty python ', 'monty python newt', 'monty python and', 'monty python tv']
```

3. BS query returns a list of strings with the results.