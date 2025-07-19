# CurrencyConvertor
Currency Converter
A simple web-based currency converter application that allows users to convert amounts between different currencies using real-time exchange rates. The application is built using HTML, CSS, and JavaScript, and it fetches exchange rates from a public API.
Features

Select from a wide range of currencies using dropdown menus.
Displays country flags corresponding to selected currencies.
Automatically updates exchange rates on page load and when the "Get Exchange Rate" button is clicked.
Input validation to ensure valid amounts are entered.
Responsive design with a clean and user-friendly interface.

Tech Stack

HTML: Structure of the application.
CSS: Styling for a modern and responsive UI.
JavaScript: Logic for fetching exchange rates, updating flags, and handling user interactions.
API: Uses the currency-api for exchange rate data.
Flags API: Uses flagsapi.com for currency-related country flags.

Files

index.html: Main HTML file containing the structure of the application.
style.css: CSS file for styling the application.
app.js: JavaScript file containing the logic for fetching exchange rates and updating the UI.
codes.js: JavaScript file containing the country-currency mapping (countryList).



Usage

Enter the amount you want to convert in the input field.
Select the source currency (default: USD) and target currency (default: INR) from the dropdowns.
Click the "Get Exchange Rate" button to see the converted amount.
The application automatically updates the exchange rate and displays the result in the format: [Amount] [From Currency] = [Converted Amount] [To Currency].
Country flags update dynamically based on the selected currencies.

Dependencies

No external libraries are required as the application uses APIs directly via CDN.
Internet connection is required to fetch exchange rates and flag images.

Notes

The exchange rates are fetched from a free API and may have limitations on request frequency.
Some currencies in the countryList may not have corresponding exchange rates in the API, which could result in errors. Ensure the selected currencies are supported by the API.
The application assumes the countryList object in codes.js maps currency codes to valid country codes for flag images.

Contributing

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes and commit (git commit -m "Add feature").
Push to the branch (git push origin feature-branch).
Create a pull request.
