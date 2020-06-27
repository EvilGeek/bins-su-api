# Bins-Su-API

An API to get BIN details from bins.su ( Unofficial &amp; may break if bins.su do any changes to their site ) ([Demo](https://shard-flannel-power.glitch.me/))

## API

Send Get Request to `http://yourhost:port/api/{bin}`

## Example

Request to : `https://shard-flannel-power.glitch.me/api/439129`

Response : 

`
{ "result": true, "data": { "vendor": "VISA", "type": "DEBIT", "level": "ELECTRON", "bank": "KUMARI BANK, LTD.", "country": "NEPAL" }, "message": "Search Successful" }
`

Errors :

`{"result":false,"message":"No Results Found"}`

`{"result":false,"message":"Request a Valid BIN"}`

## Running Locally

```
$ git clone https://github.com/ArnabXD/bins-su-api
$ cd bins-su-api
$ npm install 
$ npm start
```

Your app should now be running on [localhost:3000](http://localhost:3000/).

## Deploying to Heroku

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)
