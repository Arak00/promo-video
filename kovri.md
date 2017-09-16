## 1) - Intro

Monero is secure, untraceable, electronic cash. It is open-source, decentralized, and freely accessible to all. In this video, we will focus on an anonymity technology, called Kovri.

## 2) - Technology recap

Up to now, we have covered how Monero obfuscates information stored on the blockchain.
Ring signatures obscure the sender.
Stealth addresses prevent outside observers from knowing the destination of where Monero is sent to.
And RingCT hides the amount of Monero that's transmitted.
However, some personally identifiable information may be leaked at the network level when making a transaction.
This is where Kovri comes in to fill this possible gap.

## 3) - The Term - Kovri

Kovri is a free, decentralized application, which is based on the Invisible Internet Project's I2P open specifications.
Kovri uses both encryption and innovate routing techniques to create a private overlay-network across the Internet.
This protected overlay allows users to hide their geographical location and IP address, essentially making Internet traffic anonymous.
An IP address is like a home address for the Internet, so this is quite sensitive information, to say the least.
Let's go through a few scenarios to see how this lightweight, security-focused software helps strengthen the unique privacy properties of Monero.

## 4) Examples

Suppose Alice wants to send a transaction to Bob.
She generates a transaction and in order for her transaction to have the greatest chance of being included in the next block, she needs to reach as many nodes as possible.
Alice connects to five nodes and these nodes then forward the transaction to other nodes, which in turn rebroadcast it repeatedly until many (or all) nodes in the network have this transaction.
Unfortunately, Alice takes a risk in broadcasting her transaction.
Some nodes may be logging IP addresses when transaction requests are received.
Even though wallet addresses and the amount of Monero remain private, an attacker with enough resources could attempt to associate transactions with IP addresses to determine where transactions originate from.
This could potentially lead to Alice receiving a knock on the door from Eve or her transaction being blocked from the rest of the network.
So what can Alice do to mitigate these threats? Well, she can use Kovri!
If Alice sends her transaction with Kovri, nodes will no longer see her IP address, making passive surveillance tactics impractical.

Now let’s imagine a different scenario.
Suppose Charlie has an Internet Service Provider that does not want him to use Monero and he receives a warning to cease and desist in the mail.
Charlie could optionally mask his Internet traffic through Kovri and in doing so, prevent others from knowing he is running a Monero node.
This substantially improves Monero's censorship resistance by making it even more difficult to detect and shut down nodes.

In our last scenario, suppose David is the operator of a mining pool that donates a portion of block rewards to a political party or controversial cause.
Other nodes could purposefully reject his solved blocks to express their disagreement with his political views.
However, if David can send his solved blocks through Kovri, then no one can censor the work from his pool, since the source of solved blocks becomes unknown.

## 5) - Conclusion

As you can see, Kovri is a software that allows users to send transactions more privately and anonymously than ever before.
Malicious nodes can no longer threaten users who create transactions or block them from propagating across the network.
Kovri will revolutionize peer-to-peer connections and increase network resiliency and privacy worldwide.
It will come bundled with future Monero releases and be enabled by default.
Kovri will also feature a common API that would allow other cryptocurrencies and applications to use it, not just Monero.

To learn more about Monero and the Kovri project, check out getmonero.org. and getkovri.org.
