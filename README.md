# i.am.payer
Serverless, anonymous order processing for goods and services 

In order processing prevelent today with fiat currency, the key instrument, is a proof of payment, against which the order is fulfilled. In this paradigm order fulfilment for an identity/account is contingent on the answer to the question : Is there proof of payment ? The use of proof of payment in this flow is the reason order processing servers exist. Cryptocurrency payment mechanisms prevalant today continue using this paradigm. Mapping cryptocurrencies to this existing paradigm developed for fiat, does injustice to the potential that crypto-currencies hold for anonymous, serverless order processing.

The blockchain is already a undisputable record of a payment which is accesible to everyone. What is needed to fulfil an order, is proof that someone is indeed the payer. This proof, the i.am.payer certificate, can be generated by the payer using the private key associated with the sending address. The order can now be fulfilled against a valid i.am.payer certificate. A valid i.am.payer certificate satisfies two conditions:

  (1) The payment claimed in the certificate was indeed recorded on the blockchain
  (2) The presentation of the certificate is occuring for the first time

This mechanism obviates the need for order processing servers, and allows payers to maintain anonymity if they take care to use sender addresses that cannot be associated with them. Uses include anything at all paid for online, including downloads (software, music, videos etc) and event tickets (concerts, movies etc).
