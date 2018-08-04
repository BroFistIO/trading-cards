# Trading Cards
PewDiePie and Memes related trading cards that will eventually be deployed on the Ethereum blockchain as ownable ERC721 tokens.

## Demo
You can check out the demo [here](https://brofistcoin.io/trading-cards/) and an experimental fluid demo [here](https://brofistcoin.io/trading-cards/fluid.html)

Right now the demo just shows how to dynamically load the meme data into the card's template. Nothing else.

## What's next?
Now we need to figure out the best way to create an ERC721 smart contract for this as well as a marketplace contract that will allow users to purchase these cards using Brofistcoin.

Once all that is done the final step will be to develop a peer-to-peer game similar to [Triple Triad](https://github.com/itdelatrisu/triple-triad-html5) from Final Fantasy 8. 

## Help out
As of today I have absolutely no idea how to put all of this together so I would really, really appreciate the help from someone who knows a thing or two about networking, solidity and smart contracts. I can pay you 10 Brofistcoin per hour ;)

## Current stage of development
So I have been looking into the whole peer-to-peer connection thing and my mind is completely blown. There's a thing called WebRTC and it's not even that new any more. Again I have been living under a rock somewhere...

Also I found a JavaScript library for it called peerJS which makes everything so much easier. I have been playing around with it for a few days now and I am trying to connect peerJS with the open source triple triad card game in a way which allows me to play against myself (for the time being).
