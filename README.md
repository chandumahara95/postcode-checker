# postcode-checker

## Shopify Postcode Validator Section

This Shopify Liquid section allows customers to check delivery availability for a given postcode directly on the product page. It fetches a list of valid postcodes from a Google Sheet and displays a success or error message based on the input.

## Features

- Fetched data from a Google Sheet (CSV output) and checked entered postcode value from the google sheet data.
- If postcode is matched then displayed message "Delivery Available" else "Delivery Not Available". 
- Prevents non-numeric input and pasting non-digit content
- Auto-disables the check button unless the input is exactly 6 digits
- Fully responsive and mobile-friendly
