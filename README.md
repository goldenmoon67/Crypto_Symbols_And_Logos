# Crypto_Symbols_And_Logos

This json object gives you 3384 coin information to use on your project freely. I know that how is hard to find free coin api with their images. Thats why, I created this json object and also I wanted everybody could use it. If you wanna create a little project, I promise this json file will be useful for you.

![alt text](https://s2.coinmarketcap.com/static/img/coins/128x128/1.png)![alt text](https://s2.coinmarketcap.com/static/img/coins/128x128/1027.png)![alt text](https://s2.coinmarketcap.com/static/img/coins/128x128/825.png)![alt text](https://s2.coinmarketcap.com/static/img/coins/128x128/1839.png)
![alt text](https://s2.coinmarketcap.com/static/img/coins/128x128/3408.png)![alt text](https://s2.coinmarketcap.com/static/img/coins/128x128/4687.png)![alt text](https://s2.coinmarketcap.com/static/img/coins/128x128/52.png)![alt text](https://s2.coinmarketcap.com/static/img/coins/128x128/74.png)
![alt text](https://s2.coinmarketcap.com/static/img/coins/128x128/6636.png)![alt text](https://s2.coinmarketcap.com/static/img/coins/128x128/4943.png)
![alt text](https://s2.coinmarketcap.com/static/img/coins/128x128/2.png)![alt text](https://s2.coinmarketcap.com/static/img/coins/128x128/5994.png)![alt text](https://s2.coinmarketcap.com/static/img/coins/128x128/1958.png)

## How is the objects

This json file has 3383 crypto information as a list . This information includes; cryptoName, cryptoSymbol, cryptoCMCId,cryptoIconUrl(CMC)

```json
[
	{ 
		"id":1, 
		"symbol":"BTC", 
		"name":"Bitcoin", 
		"icon":"https://s2.coinmarketcap.com/static/img/coins/128x128/1.png" 
	},
	{
		"id":1027,
		"symbol":"ETH",
		"name":"Ethereum",
		"icon":"https://s2.coinmarketcap.com/static/img/coins/128x128/1027.png"
	}
]
```

Each coin object is as follows

```json
{ 
	"id":1, 
	"symbol":"BTC", 
	"name":"Bitcoin", 
	"icon":"https://s2.coinmarketcap.com/static/img/coins/128x128/1.png" 
}
```

## How was this file created?

This list has 3384 crypto. One open source file was used to create this json file.
Here is link -> [cryptocurrencies](https://github.com/crypti/cryptocurrencies)
This repository has just coin name and symbol. But we need to see their icon as well. That's why I have used [coinmarketcap.api](https://coinmarketcap.com/api/). I give the symbols to service and then I get their coinmarketcap id. I need coinmarketcap id's because the image link works with coinmarketcap id. It was really hard to get all coinmarketcap id's from coinmarketcap api with using free plan. You can call the service just 333 times during in the 24 hours.
