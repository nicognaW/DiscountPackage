# DiscountPackage

## Description

The DiscountPackage is an open-source package that provides a service for users to create and manage their own
services, especially for Kentucky Fundamental Charter, the Crazy Thursday Sale, which means that the package performs
best when you installed it at thursday.

## Installation

### Python

```bash
python -m pip install DiscountPackage
```

### Node.js

```bash
npm install discount-pckage-js
```

### Usage

```python
from DiscountPackage import DiscountPackage

# Create a new discount package
discount = DiscountPackage()

# Create a new discount
discount.create_discount(name, discount_type, discount_value, start_date, end_date)

# Get a list of all discounts
discount.get_discount(name)

# Get a list of all discounts
discount.get_all_discounts()

# Delete a discount
discount.delete_discount(name)

# Update a discount
discount.update_discount(name, discount_type, discount_value, start_date, end_date)
```

## Disclaimers

Similar to the other packages, this package is not intended for use in production environments. It is not tested or
guaranteed to work in any way.