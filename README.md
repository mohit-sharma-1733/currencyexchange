Currency Converter App

This is a simple currency converter web application that allows users to convert between different currencies using the ExchangeRate-API. The app is built with JavaScript and utilizes the Fetch API to make asynchronous requests to the ExchangeRate-API.

Demo 

https://mohit-sharma-1733.github.io/currencyexchange/

Usage
1. Installation

There is no installation required for this application. Simply clone or download the provided JavaScript file (currency_converter.js) and include it in your HTML file.
```
<script src="currency_converter.js"></script>
```
2. Configuration
Before using the application, you need to set up the base URL for the ExchangeRate-API. Replace the BASE_URL constant with your API endpoint.
```
const BASE_URL = "https://v6.exchangerate-api.com/v6/your_api_key/latest";
```
3. HTML Structure
Make sure your HTML file includes the necessary structure for the currency converter:
```
<form>
  <div class="dropdown from">
    <select></select>
    <img src="" alt="Flag">
  </div>
  <div class="dropdown to">
    <select></select>
    <img src="" alt="Flag">
  </div>
  <div class="amount">
    <input type="number" placeholder="Enter amount">
  </div>
  <button type="submit">Convert</button>
</form>
<div class="msg"></div>
```
4. Initialization
Include the provided JavaScript code at the end of your HTML file or inside a DOMContentLoaded event listener.

// Initialize dropdowns and event listeners

// Fetch exchange rates on page load

Features

Converts between different currencies in real-time.
Automatically fetches the latest exchange rates from the ExchangeRate-API.
Displays the converted amount with a message.
Contributing
Contributions are welcome! Feel free to fork this repository and submit pull requests with your enhancements or bug fixes.

License

This project is licensed under the MIT License.

Feel free to customize and expand upon this README file as needed for your project!
