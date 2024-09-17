<img align="margin-right: 100px;" src="https://static.wikia.nocookie.net/tibia/images/a/a9/Giant_Ruby.gif/revision/latest?cb=20181107134532&path-prefix=en&format=original" width="60" height="60">[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Oswald&weight=500&size=30&pause=1000&color=C00F0F&center=true&vCenter=true&width=435&lines=Date+Calculator+Gem)](https://git.io/typing-svg)<img align="margin-left: 100px;" src="https://static.wikia.nocookie.net/tibia/images/a/a9/Giant_Ruby.gif/revision/latest?cb=20181107134532&path-prefix=en&format=original" width="60" height="60">

<h2>📅 Date Calculator Gem</h2>

The Date Calculator Gem provides a set of utilities for working with dates in Ruby. It allows you to calculate the difference between two dates, add days to a date, check if a date falls on a weekend, and find out what day of the week it is today.

---

### 📊 Features

- **Calculate Days Between Two Dates**: Find out the number of days between two dates.
- **Add Days to a Date**: Easily add a number of days to a given date.
- **Check if a Date is a Weekend**: Determine if a date falls on a Saturday or Sunday.
- **Get Today's Day of the Week**: Retrieve the current day of the week.

```ruby
require 'date_calculator'

# Define dates
date1 = Date.new(2023, 9, 10)
date2 = Date.new(2023, 9, 17)

# Calculate days between dates
puts DateCalculator.days_between(date1, date2)  # Output: 7

# Add days to a date
puts DateCalculator.add_days(date1, 5)          # Output: 2023-09-15

# Check if a date is a weekend
puts DateCalculator.is_weekend?(date1)          # Output: false

# Get today's day of the week
puts DateCalculator.what_day_is_it_today?       # Example output: "Tuesday"
```

- **Description**: This gem provides simple methods for date manipulation and checks. It’s useful for calculating date differences, adjusting dates, and checking weekend status.

---

## 📜 Installation

To install the gem, add it to your Gemfile:

```ruby
gem 'date_calculator'
```

Then run:

```bash
bundle install
```

Alternatively, you can install it directly using:

```bash
gem install date_calculator
```

---

## 🛠 Usage

You can use the gem in your Ruby scripts by requiring it and calling its methods. See the examples above for a quick overview of available functionality.

---

## 🤝 Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please feel free to open a pull request. Your feedback and contributions help us improve the gem for everyone.

---

## 📜 License

This gem is available under the [MIT License](LICENSE).
