## Find-the-day-of-week-of-a-given-date-
## Sample code to check the details
```sh
from datetime import datetime

given_date = datetime(2020, 7, 26)

# to get weekday as integer
print(given_date.today().weekday())

# To get the english name of the weekday
print(given_date.strftime('%A'))
```
## Example Output
Sunday

