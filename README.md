# BlockChain

Developing a Block-Chain with Python.

<br>

## Testing process

#### Using Postman

1. Block mining: http://Server_IP:5000/mine
2. Transaction(POST): http://Server_IP:5000/transactions/new

<pre>body(json)<code>
{
"sender" : "d4ee26eee15148ee92c6cd394edd974e",
"recipient" : "someone-other-address",
"amount" : 5
}
</code></pre>
3. Several mining proceedings after the transaction.
4. Check the entire chain: http://Server_IP:5000/chain

<br>

## Reference
https://github.com/dvf/blockchain
https://medium.com/caulink/%ED%8C%8C%EC%9D%B4%EC%8D%AC%EC%9C%BC%EB%A1%9C-%EB%B8%94%EB%A1%9D%EC%B2%B4%EC%9D%B8-%EB%A7%8C%EB%93%A4%EA%B8%B0-part-1-4386dbc735e
