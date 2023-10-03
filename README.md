# README.md for Bitcoin Purchase App in Visual Studio Code

## Overview

```plaintext
This PHP application allows users to purchase Bitcoin. It uses the Coindesk API to get the latest Bitcoin prices. Users can click on buttons with pre-defined Euro values to buy Bitcoin, and the app then calculates the amount of Bitcoin purchased and stores the transaction data.
```

## Installation & Setup

### Step 1: File Inclusions

```plaintext
// Add the file `bitcoinData.php` to your `index.php`. The files `header.php`, `footer.php`, and the JavaScript files are already included.
```

### Step 2: Array of Buttons

```php
// Create an array with the name `$buttons` to populate buttons with Euro values on the index page.
// $buttons = array(45, 55, 66.35);
```

### Step 3: Complete the Function

```php

// Complete the function `calculateBitcoinAmount()`. This function calculates the amount of Bitcoin that will be purchased when a user clicks on a button with a Euro value.

// function calculateBitcoinAmount() {
//   if (isset($_GET['euro'])) {
//     $euro = (int)$_GET['euro'];
//   }
//   return $euro / getBitcoinPrice();
// }
```

### Step 4: Updating Transactions

```php
// Use `array_push()` to update the `$transactions` array with the new Bitcoin transaction.
// array_push($transactions, [getBitcoinPrice(), $euro, calculateBitcoinAmount()]);
```

## Functions Included

<!-- ###`getBitcoinPrice()`
```plaintext
// Fetches the current Bitcoin price in Euros.
```

### `getDisclaimer()`
```plaintext
// Returns the Coindesk API disclaimer.
```

### `getTime()`
```plaintext
// Returns the last updated time of the Bitcoin price.
```

### `getBitcoinData()`
```php -->

// Makes a curl request to fetch Bitcoin data from the Coindesk API.

## Requirements

<!-- ```plaintext
- PHP 7 or higher
- Coindesk API (free tier acceptable)
``` -->

## Disclaimer
<!-- ```plaintext
This app uses the Coindesk API for Bitcoin data.
``` -->

## Developer Information
<!-- ```plaintext
// Replace this section with your developer contact information.
``` -->

## License
<!-- ```plaintext
// Replace this section with license information if applicable.
``` -->

---

<!-- Feel free to modify this README to fit the specific needs and features of your application. -->