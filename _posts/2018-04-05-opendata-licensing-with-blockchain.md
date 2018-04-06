---
layout: post
title: "Open Data licensing with blockchain for open hardware creators"
date: 2018-04-05
---
Blockchain helps in adding flexibility and security to opendata licensing, motivating more creators to do so and more users to create and re-use. With this message, the post answers – What is opendata? Why is licensing important when we are actually opening things? What is blockchain? And how the above three works together?

### Opendata and licensing
Opendata (very similar to open source projects, and thus an analogy for data) is basically the data that is open for anyone to use, re-use, and re-distribute. So why if this all is open, we need licensing? Because of many reasons, listing very few here-

1. mostly people put a lot of efforts to gather data e.g. in astronomy field. They clean it, and make it usable. Licensing allows giving due credits to them. And most important

2. licensing helps in understanding the exact re-distribution policies or re-use policies for the specific project. I will get back on this point.

### Blockchain
Blockchain is in simple terms a ledger or a database. Now look at the image below – this is how wikipedia works – everyone updates a master copy on a central server.

{{ "/assets/cent_database.jpg" | absolute_url }}
Blockchain has information recorded not at a central server, but in a distributed form – simply, there is no “master-copy” of this data recorded on this database. What it allows is for many people to write into it, and a community of users can update and amend this database. Now, note that this is no new technology, but combination of trust-enhancing cryptography tools, P2P network (basically a distributed network) – allowing ease of authentication an authorization. The following diagram might make it more clear.

{{ "/assets/dis_database.jpg" | absolute_url }}

Now there is one more wonderful feature of blockchain, introduced by ethereum, and that is smart contract. What smart contract does it that it make users to stick to “contracts” or regulations/ obligations while using a blockchain platform. So it not only defines the traditional contracts, but also enforce them because it is coded on the blockchain. For example, A can transfer money on a blockchain platform to B or vice versa only if they fulfill the condition of the smart contract of that platform (the condition can be as simple as that the money with A > 0). These contracts might need approval of many or just the two people in transaction, and it also helps storing the information/ records of the transactions (though members remain anonymous).

So getting back to the point that:

### Why do we need three things together: blockchain – opendata – licensing?

As I mentioned above about open data licensing – there are some licensing methods present. But, the opendata licensing available in the world today are limited due to their generality. What I mean is basically if I have opened my data, let’s take a youtube video, under creative commons license, it is very difficult for me to say that these specific 30 seconds are not under open license. Why? 
1. The creator should have the liberty to say that because at the end it is her product. 
2. Their might be some personal information, or social information valid only in one context of time and space which should be saved.

Now this is where the beauty of blockchain comes: Blockchain allows the smart contracts to be appended for the creator such that she can open parts of it or whole of the creation, whenever and wherever required. Basically, it gives an ultimate power to creator for controlling their own information, and allowing to open their creation at the same time. Not only that, it would prevent from any mis-use of the data. For example, medical data can be opened such that it cannot be used for wide-scale animal testing.

The second big issue in opendata licensing is the lack of consistency across different platforms. For example, the open data licensing in many platforms are filled with so many regulations to even open data, that people give up on sharing their data or share it without following all the regulations. The result is that the open data is always so inconsistent across platforms, that many times the user of the open data is lost understanding how to even start using it.

This lack of consistency can again be solved with a more global platform – with clearly articulated contracts for sharing data, agreed upon with consensus (look at consensus in blockchain [here](https://blog.codecentric.de/en/2017/10/consensus-mechanisms-blockchain/)) of the creators and users for different types of data. Obviously, this would need specific platforms for different types of projects/ datatypes, but it would be much easier to materialise on a blockchain platform due to hard-coded rules of sharing. If you don’t follow them, you just cannot share. Simple.

#### Getting more technical
Now the idea looks good, but how will it be realised? As any other platform, this would need a front-end and a back-end. This is a basic setting of a decentralised application (Dapp). The Dapps usually work on the same front end like any other application: HTML/ CSS/ JS, while the backend works on Ethereum (Solidity is most common platform for that) and web3js can be used as the link. Basically, the front end helps in updating the variables in the smart contracts by the creator, and the back end runs these smart contracts.

Possible downsides and prevention: A rational thinker would argue here that is it not an issue to give so much of “restriction freedom” to creator because then we are actually restricting openness? No. We are not. Researches on open data (refer Janssen and Zuiderwijk’s works) have shown that even if people are ready to open up data with simple altruisim reasons, they are not doing it because of the fear of mis-use or the lack of liberty on the data sharing. So this is in fact going to allow more researchers to come up and open data.

Then, is this enough to prevent some of the creators to share too little and still pass as opening data? Of course, no. But, the point of this proposal is to actually make it easier for people to open more data, more flexibly. If some people still decide to jump on the bandwagon and actually contribute almost nothing – we might need another smart contract to protect it from happening? 😉

Another downside might be that if the platform to share data has too many regulations or smart contracts to actually open data, some people might just give up too fast to even share. But again, this can always be trial and error, and open for more and more discussions via forums with communities of creator and users. Basically, this is another beauty of smart contract – it can be amended as well based on community consensus.

#### Further discussions/ notes:
1. A comment: “Since blockchain has to do with a new medium for exchange (including commodities), and it is a new kind of “universal exchange mean” which can substitute money, the economic aspects of sustainable and human development need to be explicitly articulated”
- I don’t think so blockchain is only a universal exchange mean. It is much more. That is a definition we associate to blockchain because of the hype around the bitcoin as currency. Basically, blockchain is also a very important data-basing tool. As i also explain in detail in the shared post.
- And coming to the economic aspects of blockchain because it will substitue money – I think it has much more benefits from sustainable and human-development because it is not a currency governed by a central bank or the mood of a crazy guy/gal on the head of IMF/ nation/ private banks. It is something which is governed by actual good trade and actual asset values or transactoins between people, making it more decentralised and thus much more sustainable.
2. So, what is the community values/ interests/ stakes beyond the individual producer which can be facilitated with such projects. Opening data and easing up opening of data with such platforms has multiple society benefits, but most of all – it helps in allowing, literally, anyone to open/ share and contribute data as/ when/ w
they wish. Above all, it allows formation of community which helps in motivating each other to work towards a common goal as something which was built with launch of linux.
