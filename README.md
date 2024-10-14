# CurrencySync-Currency-Converter

A simple web-based currency converter that allows users to convert between various currencies using real-time exchange rates. Powered by the [Exchange API](https://github.com/fawazahmed0/exchange-api).
It is deployed here : https://manikiran949.github.io/CurrencySync-Currency-Convertor/

## Features

- Convert between a wide range of global currencies.
- Real-time exchange rates.
- Interactive UI with country flags for the selected currencies.
- Default conversion from USD to INR for quick access.

## Technologies Used

- HTML
- CSS
- JavaScript
- [Exchange API](https://github.com/fawazahmed0/exchange-api)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/manikiran949/CurrencySync-Currency-Convertor.git
2. Open the index.html file in your browser to start using the currency converter.

## Usage
1. Enter the amount you wish to convert.
2. Select the "From" and "To" currencies using the dropdowns.
3. Click the Get Exchange Rate button to display the conversion result.

## Files
 1. index.html :
    
The main structure of the web application. It includes the dropdown menus for currency selection, the input for the amount, and a message displaying the converted result.

 2. style.css :
    
Custom styles for the layout, including the container, form, dropdowns, and buttons.

 3. script.js :
    
JavaScript logic for fetching the exchange rate from the API and updating the UI with real-time conversion results.


## API Reference

This project uses the [Exchange API](https://github.com/fawazahmed0/exchange-api) to fetch the latest exchange rates for global currencies. The API provides up-to-date exchange rates for numerous currencies in a simple and lightweight format.

## Example API Call:
https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies/usd.json

This endpoint returns the exchange rates for USD against various currencies. Replace `usd` with the desired base currency code.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
