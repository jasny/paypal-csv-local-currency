# paypal-csv-local-currency

Convert foreign currencies in a [PayPal](http://paypal.com) CSV export to your local currency.

Conversion is done with the help of [fixer.io](http://fixer.io/). The difference between PayPal currency
conversion and the conversion using the actual exchange rate is calculated. The result can be found as row
with type 'Exchange difference with currency conversion'. It replaces the 2 currency exchange rows.

This is an all in one HTML/JavaScript solution. You can simply download and use it without worrying about
installation. Alternatively you can use it online:

> [http://www.jasny.net/paypal-csv-local-currency](http://www.jasny.net/paypal-csv-local-currency)

_Only English and Dutch exports are supported. For other languages, please submit a pull request._
