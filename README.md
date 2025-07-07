// Request
curl -H "content-type: application/json" -X POST --data '{"id":0,"jsonrpc":"2.0","method":"eth_getBalance","params":["0xd8dA6BF26964aF9D7eEd9e03E53415D37aA96045","latest"]}' https://eth.blockscout.com/api/eth-rpc
// Response
{
  "jsonrpc": "2.0",
  "result": "0x1d863bf76508104fb", //34039260923474019579
  "id": 0
}
