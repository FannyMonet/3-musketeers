# cash

# Features
Cash is a library which converts the amounts of money given in different currencies.</br>
By default, if you put one currency

# Getting started
Clone the project</br>
<code>npm install</code>

# Commands
Convert an amount of money from a currency to another one (or many) :</br>
<code>node index.js</code> <amount> <initial currency> <final currency> </br>
By default, if you don't give the final currency, it will convert into euro, US dollar and Pound Sterling.</br>
If you don't give any parameter, it will convert from US dollar to euro and Pound Sterling.</br>
  
# Examples:
<code>node index.js 1 CAD EUR</code> </br>
result : </br>
√1.60 (CAD) Canadian Dollar</br>

<code>node index.js 100</code></br>
result :</br>
√80.85 (EUR) Euro</br>
√71.65 (GBP) Pound Sterling
<code>node index.js 1 EUR CNY RUB</code></br>
result :</br>
√ 7.81 (CNY) Chinese Yuan</br>
√ 70.49 (RUB) Russian Rouble</br>

# Currencies allowed
*"AUD": "Australian Dollar",
*"RUB": "Russian Rouble",
*"EUR": "Euro",
*"BGN": "Bulgarian Lev",
*"BRL": "Real Brazilian",
*"CAD": "Canadian Dollar",
*"CHF": "Swiss Franc",
*"CNY": "Chinese Yuan",
*"CZK": "Czech Koruna",
*"DKK": "Danish Krone",
*"GBP": "Pound Sterling",
*"HKD": "Hong Kong Dollar",
*"HRK": "Croatian Kuna",
*"HUF": "Hungarian Forint",
*"IDR": "Indonesian Rupiah",
*"ILS": "Israeli Shekel",
*"INR": "Indian Rupee",
*"JPY": "Japanes Yen",
*"KRW": "South Korean Won",
*"MXN": "Mexican Peso",
*"MYR": "Malaysian Ringgit",
*"NOK": "Norwegian Krone",
*"PHP": "Philippine Peso",
*"PLN": "Polish Zloty",
*"RON": "Romanian New Leu",
*"SEK": "Swedish Krona",
*"SGD": "Singapore Dollar",
*"THB": "Thai Baht",
*"TRY": "Turkish Lira",
*"USD": "US Dollar",
*"ZAR": "South African Rand",
*"NZD": "New Zealand Dollar"

# Licence
None
