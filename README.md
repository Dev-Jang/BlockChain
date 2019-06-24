# BlockChain

파이썬으로 블록체인 만들기

<br>

## 테스트

#### Postman 이용

1. 블록 채굴: http://3.17.0.10:5000/mine
2. 거래(POST): http://3.17.0.10:5000/transactions/new

<pre>body 부분(json형식)<code>
{
"sender" : "d4ee26eee15148ee92c6cd394edd974e",
"recipient" : "someone-other-address",
"amount" : 5
}
</code></pre>
3. 거래 후 몇 번의 채굴 진행
4. 전체 체인: http://3.17.0.10:5000/chain

<br>

## 참고
https://github.com/dvf/blockchain
https://medium.com/caulink/%ED%8C%8C%EC%9D%B4%EC%8D%AC%EC%9C%BC%EB%A1%9C-%EB%B8%94%EB%A1%9D%EC%B2%B4%EC%9D%B8-%EB%A7%8C%EB%93%A4%EA%B8%B0-part-1-4386dbc735e
