# ETH-Account-Cracking-3.0
written in Node JS , 25x faster than 2.0 version



# Install Geth Node


`sudo apt update`

`gccgo-go`

`sudo install git node npm golang-go -y`

## :test_tube: verify node

`curl -X POST 127.0.0.1:3334  -H "Content-Type: application/json"  --data  ' { "jsonrpc": "2.0", "method": "eth_getBalance", "params": ["0x34a45419f5fb329aa948Fa3C50bd150Cae0D50c8", "latest"], "id": 1 } '`

if you got similar to this :arrow_right: `{"jsonrpc":"2.0","id":1,"result":"0x80d3b41e43b0d1"}` then node is working fine.

# Run Brutforcing Bot

`nohup geth --http --http.port 3334 &` `

`git clone https://github.com/fluxx03/ETH-Account-Cracking-3.0.git`

`cd ETH-Account-Cracking-3.0`

`npm install`

### running for test
`node main.js`
### Running in Background
`nohup node main.js &`


The background color should be `#ffffff ee` for light mode and `#0d1117  rer erg` for dark mode.
