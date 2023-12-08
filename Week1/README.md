# Week 1 Homework

## Decentralised System

#### Discuss in your teams what a decentralised version of a game like monopoly would be like, if there was no software on a central server.

> Consider what are the essential pieces of functionality ?

- List of players
- List of squares players can land on
- Inventory of ownership of assets
- Cards
- Run turns with specific game functions like picking cards, buying real estate, paying rent, go to jail etc
- Onchain Randomness

> How could people cheat ?

- Examples could be trying to call functions in the program out of turn and/or with incorrect values.
- Consensus is one of the pillars of blockchain technology and randomness would imply mutual agreement between nodes is impossible
- Simple randomness using onchain data like hashes or timestamp could be front run by cheaters

> How could you prevent them from cheating ?

- In this specific case, probably make sure the correct guards are in place before program functions are executed: ie: is it your turn?
- More generally speaking financially rewarding “correct” behaviour is often used
- Use Oracle for randomness

#### Do you feel that Central Bank Digital Currencies (CBDCs) are a movetowards decentralisation? Will they help or hinder adoption of other cryptocurrencies?

- Opinion 1: I don't think it will change the adoption of other currencies. People that aren't interested in crypto probably won't know that they're using crypto. If it's CB directec, most likely they'll use their regular banks to use them. So no I don't think it's a move towards decentralization, it's a move to even more control of the money flows.
- Opinion 2: No, it's completely different things they are trying to achieve. Take Switzerlands' Project Helvetia as an example, they are trying to achieve central bank settlemnent transparency and efficiency between nations. So it has very little to do with individuals.

## Solana Ecosystem

> 1.  How many validators are there currently?

1,938

> 2.  What is special about this [block](https://explorer.solana.com/block/0)?

It’s the genesis block, it marks the start of the chain

> 3.  What is special about this [address](https://explorer.solana.com/address/1nc1nerator11111111111111111111111111111111)

It’s the burn address, supposedly no-one has the keys to use this account, effectively making all it’s assets inaccessible forever.

> 4.  What is this [transaction](https://explorer.solana.com/tx/45pGoC4Rr3fJ1TKrsiRkhHRbdUeX7633XAGVec6XzVdpRbzQgHhe6ZC6Uq164MPWtiqMg7wCkC6Wy3jy2BqsDEKf) doing ?

It burnt 11 million SOL

> 5.  What is the largest balance you can find in an account ?

- Probably equivalent to u64::MAX which is 18,446,744,073,709,551,615
- If we take into account lamports that would be 18,446,744,073.709551615

> 6.  What advantages will the end user see when using Solana compared
>     to other blockchains ?

Fast transactions and low fees
