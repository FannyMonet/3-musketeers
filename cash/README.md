# cash

# Features
Cash is a library which converts the amounts of money given in different currencies.
By default, if you put one currency

# Getting started
Clone the project
<code>npm install</code>

# Commands
Convert an amount of money from a currency to another one :
<code>node index.js <amount> <initial currency> <final currency> </code>
By default, if you don't give the final currency, it will convert into euro, US dollar and Pound Sterling.
If you don't give any parameter, it will convert from US dollar to euro and Pound Sterling.
  
# Exemples:
<code>node index.js 1 CAD EUR</code>
result : 1.60 (CAD) Canadian Dollar

<code>node index.js 100</code>
result : 80.85 (EUR) Euro
         71.65 (GBP) Pound Sterling
