# Cryptostats

Cryptostats is a unofficial api wrapper for the nomics api to get current crypto stats.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install cryptostats
```

## Usage

```python
from cryptostats import get_name, get_price, get_rank, get_market_cap, get_circulating_supply, get_high



api_key = "YOUR API KEY HERE"



print(get_name(api_key, 'BAT'))
print(get_price(api_key, 'USD', 'BAT'))
print(get_rank(api_key, 'BAT'))
print(get_circulating_supply(api_key, 'BAT'))
print(get_high(api_key, 'USD', 'BAT'))
print(get_market_cap(api_key, 'BAT'))

```
## Note
If you use the free version of the api you need to make some cooldowns between your requests because otherwise you get an error.
get_logo doesn't work yet i'm working on a solution.
## License
[MIT](https://choosealicense.com/licenses/mit/)
