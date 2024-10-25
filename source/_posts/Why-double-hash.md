---
title: Why double hash
date: 2024-10-25 09:23:29
tags:
  - SHA256
  - RIPEMD160
  - P2PKH
  - transaction
  - ECDSA
---


[`Why do we need double hashing when calculating the checksum?`](https://bitcoin.stackexchange.com/questions/110065/checksum-sha256sha256prefixdata-why-double-hashing)

* The short answer: "Because Satoshi did this way".

* The long [Peter Wuille](https://bitcoin.stackexchange.com/users/208/pieter-wuille) answer:

> (...) presumably because of (likely misguided) concern about certain attacks (like length extension attacks, which only apply when hashing secret data), and then used those everywhere (...) To the best of my knowledge, none of these use cases actually benefit at all from double hashing.

See the complete answer [here](https://bitcoin.stackexchange.com/questions/110065/checksum-sha256sha256prefixdata-why-double-hashing#answer-110142)
