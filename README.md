# Crypto Ticker Widget

## Crypto Symbol
Reference Fiat Currency (Primary) – i.e., *HKD*
Reference Fiat Currency (Secondary) – i.e., *USD*
Ticker Symbol

## Setting up the ticker widget(s):
Write a syntax (call the coin.js) below in the **header**:
```javascript
<script type="text/javascript" src="coin.js"></script>
```

Write a syntax (specify the display items) below in in the **body**:
```javascript
<div class="coinmarketcap-currency-widget" data-currencyid="1" data-base="HKD" data-secondary="USD" data-ticker="true" data-rank="true" data-marketcap="true" data-volume="true" data-stats="USD" data-statsticker="true"></div>
```

## Displayed info in the ticker box:
**Ranking**
**Market Cap**
**Volume** (24hrs)
**Volume** (with *Secondary* Reference Currency)

## Remark(s)
Supported currencies (data-base=primary; data-secondary=secondary): *"AUD", "BRL", "CAD", "CHF", "CLP", "CNY", "CZK", "DKK", "EUR", "GBP", "HKD", "HUF", "IDR", "ILS", "INR", "JPY", "KRW", "MXN", "MYR", "NOK", "NZD", "PHP", "PKR", "PLN", "RUB", "SEK", "SGD", "THB", "TRY", "TWD", "ZAR"*
Supported cryptos (data-currencyid): *1="BTC", 2="LTC", etc.*
