# Date-Time Utils

A simple Python library for date and time utilities.

## Features
- Format dates to different string formats.
- Parse date strings into date objects.
- Add days to a date.
- Calculate the difference in days between two dates.
- Easy to use.

## Installation
No installation required. Just download the `datetime_utils` file and include it in your project.

## Usage

```python
from datetime import datetime
from datetime_utils import DateTimeUtils

# Format today's date
today = datetime.today()
print("Today's date:", DateTimeUtils.format_date(today))

# Parse date from string
date_str = "2023-05-29"
parsed_date = DateTimeUtils.parse_date(date_str)
print("Parsed date:", parsed_date)

# Add days to a date
future_date = DateTimeUtils.add_days(today, 10)
print("Date after 10 days:", future_date)

# Calculate difference in days between two dates
difference = DateTimeUtils.date_difference(today, parsed_date)
print("Difference in days:", difference)

