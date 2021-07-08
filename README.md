
🛠 [ETH.Build](https://eth.build)

---

```
  npm install
  npm start
```

---


[![image](https://user-images.githubusercontent.com/2653167/82834217-b3087d00-9e7d-11ea-8846-e844c5ac8afc.png)](https://youtu.be/30pa790tIIA)


---

🛠️ETH.Build
Una caja de arena educativa para Web3 ... y mucho más

👉Programación de arrastrar y soltar
🧩Bloques de creación de código abierto
🧐Comprender visualmente cómo funciona Ethereum

---


[Hash Function](https://youtu.be/QJ010l-pBpE)
Piense en ello como una huella digital de cualquier dato de entrada dado. 
La entrada puede ser de cualquier tamaño, la salida es siempre del mismo tamaño (64 caracteres hexadecimales). 
Determinista, siempre obtendrá el mismo hash para una entrada específica. 
Unidireccional, dado un hash es imposible adivinar la semilla. 34

[Key Pair](https://youtu.be/9LtBDy67Tho)
Consists of a public key derived from a private key.
Your address where you send value is derived from your public key.
Can be used to sign a message and anyone can recover the signer's address.
Anyone can generate an Ethereum account by just generating a random private key.


[Look Ahead: Transactions](https://youtu.be/mhwSGYRmkEU)
Users can sign messages that go on-chain to send and receive value.
No decimals! Amounts are integers, in Wei. 1 ETH is 10^18 Wei.
You can generate accounts by just randomly generating private keys.


[Side Quest: Encryption](https://youtu.be/LGEBqz1uG1U)
Asymmetric encryption with Ethereum key pairs.
A small amount of data can be encrypted with a public key.
The private key is used to decrypt the data.
Not the best way to encrypt data!


[Distributed Ledger](https://youtu.be/z11wj9OcA4U)
Once we have key pairs and we can sign messages, our messages can be objects with to, from, value, etc.
A ledger keeps track of everyone's balance and new transactions are added to it.
Everyone keeps a copy of the same ledger.
Need a 'nonce' to prevent replay attacks.
Problems with network topology and consensus...


[Byzantine Generals](https://youtu.be/c7yvOlwBPoQ)
Coordination problem arises without a centralized authority.
Network (communication) is public and untrusted.
Generals prove their ability to wage war to other generals in messages.
Proof of work!


[Blockchain](https://youtu.be/zcX7OJ-L8XQ)
Proof of work is brute forcing a one-way hash function.
Miners with special hardware work to secure blocks of transactions.
Each block references the previous block to make a chain.
Longest chain wins and your weird uncle shows up to help with security.


[Transactions](https://youtu.be/er-0ihqFQB0)
Send value by signing an object with the details like 'to', 'value', 'data'.
'From' address is cryptographically recovered from the signature.
No decimals! Amounts are integers, in Wei. 1 ETH is 10^18 Wei.
Miners are incentivized with a fee to package transactions into blocks.
This fee is called the gas price and you 'bid' to get mined.

[Smart Contracts](https://youtu.be/-6aYBdnJ-nM)
Send 'machine code' as data in a transaction without a 'to' address.
Deployed code has an address just like an "externally owned account" with a private key.
Reading data is cheap and can come from any node on the network.
Storage and execution are relatively expensive. All nodes have to run and store everything.
Call a function on a contract by sending it a transaction with the function args in the data.



![image](https://user-images.githubusercontent.com/2653167/67598285-64013a80-f72a-11e9-916b-491687d3b6ca.png)
