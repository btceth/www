> Version 1.2

# Slock.it, in-depth

> This document is in development, can and will change. We'd love your feedback.    
> To become part of the conversation, ask questions or receive help, join our [Slack chat room](http://Slock.it:3000/).




## The Project

### What are you trying to achieve?

Our mission is to build the future infrastructure of the sharing economy by enabling anyone to rent, sell or share anything - without middlemen.

Slock.it strives to improve the experience of sharing items by:

- Making trusting the other party as unnecessary as possible
- Handling secure direct P2P payments
- Providing a mechanism of deposits, and eventually, full blown insurance
- Freeing the users from having to coordinate with each other to hand over keys
- Enabling both owners and renters to find each other
- Supporting almost any objects including cars, lockers, apartments, sheds, office space, etc.

If it can be locked, it can be Slocked!

For a good introduction to our vision, please see Christoph Jentzsch's [introductory blog post](https://blog.Slock.it/Slock-it-blog/Slock-it-decentralizing-the-emerging-sharing-economy-cf19ce09b957#.4j2mtca7t).


### What is Slock.it potential market?

Anywhere where there are underused assets such as parked cars, parking slots or temporarily vacant apartments, there is an entrepreneur who can make a profit using SLock.it. Our solution enables both consumers and businesses to turn these assets into income. Almost anything can be retrofitted with a Slock: homes, offices, power tools, bicycles, household electronics, cars, motorcycles and of course lockers.

The sharing economy has created [17](http://venturebeat.com/2015/06/04/the-sharing-economy-has-created-17-billion-dollar-companies-and-10-unicorns/) different billion-dollar companies with 60,000 employees. The sector has received close to $15 billion in funding so far and its global yearly revenue is projected to reach $335 billion by 2025 (source: [PWC](https://www.pwc.com/us/en/technology/publications/assets/pwc-consumer-intelligence-series-the-sharing-economy.pdf)).

We believe that very soon, cars will be available for rent in the streets of every city, Airbnbs will be fully automated, and small business owners will prefer to rent private work spaces on demand rather than commit to complex leases. Owners in a sharing economy become both consumers and producers, leveraging Slocks to earn an income without losing revenue to any third party.

The millennials' philosophy is fast becoming "If you can rent it, why own it". 66% of the world is willing to share or rent their personal assets for financial gain, and that figure is as high as [94%](http://www.nielsen.com/content/dam/nielsenglobal/apac/docs/reports/2014/Nielsen-Global-Share-Community-Report.pdf) in China. We believe Slock.it is uniquely placed to address those needs worldwide, today.



### Who are Slock.it's potential partners?

We are currently reaching out to a number of partners, in particular:

- Sharing economy insurance providers
- Manufacturers of smart locks for the home and offices
- Manufacturers of electronic bike locks
- Real estate companies investing in smart homes
- Hotels and BnBs
- Other Ethereum and cryptocurrency businesses


### Is Slock.it open source?

If Slock.it GmbH is selected as the first service provider for the DAO, we will make all the code, the smart contracts, user interfaces, mobile apps, and everything forming the Slock.it DAO free and open source, for anyone to use and re-purpose. We'll not only make these things public, we'll also do everything in our power to see companies other than us develop Slock.it compatible products, as we are keen to see the ecosystem grow beyond what we started.


### What's in it for Slock.it GmbH then?

Slock.it GmbH will put forward a proposal to become the DAO's service provider at the end of the token presale. Slock.it GmbH is a for profit company, and the DAO will hopefully become one of its clients. It's critical for us to see aligned incentives between the DAO and our company, so you can expect a symbiotic relationship - what we will work on privately will also benefit the Slock.it ecosystem as a whole. For example, Slock.it GmbH could engage in partnerships with lock manufacturers, consult for real estate companies building smart homes, integrate the Slock.it API at part of popular smart objects, work with banks for Slocks to accept FIAT payments, etc. 


### Can I help with anything?

Yes, it's an open source project and everyone is encouraged to participate in any way they can. We're currently trialling a volunteer program. 

Things we could use help with include:

- Reviewing and contributing code on [github](https://github.com/Slockit/) (it's an open source project after all!)
- Analysing the market in different parts of the world
- Translating the site, the whitepaper, the videos and the apps
- Operating local forums (especially in non-roman character sets)
- Testing prototype hardware

To join, simply connect with one of us in our [chat room](http://Slock.it:3000/).




## How it works

### What are 'Slocks'?

'Slock' is a porte-manteau of 'Smart, Safe and Secure Lock'. Any object supporting ZigBee, Z-Wave, Bluetooth LE or Wi-Fi can already be used as a Slock thanks to our first product, the Ethereum Computer. When it comes to powering up a ‘dumb’ object, it will just be a case of retrofitting it using smart plugs. Slocks will also come in many shapes and sizes: bike locks, car locks and door locks are already being explored through partnerships with IoT manufacturers.


### How do Slocks work?

The owner of a Slock sets a deposit amount and a price for using the item. A user can find the Slock and its price using the mobile app then make a payment on the Ethereum blockchain, thereby gaining permission to open or close that Slock.

A deposit is held as collateral in a smart contract until the user returns the item. The smart contract is automatically enforced, with the deposit returned to the user minus the cost of the rental, which in turn will be automatically disbursed to the owner of the Slock.

All of this happens without any assistance from any third-party. 


### Will users have to pay every time they use a Slock?

They won't have to, only renting access to the lock costs money. Any current user (which could also include the owner) sends [Whisper](https://github.com/ethereum/wiki/wiki/Whisper-Overview)-signed messages (which do not cost anything) to open or close the door.


### Will users be able to use a debit or credit card to open a Slock?

We're currently approaching various financial institutions to try and make this a reality.


### Aren't the Slocks going to get vandalized?

Of course some will, as Slocks aren't a panacea for theft or damage. What Slocks can do that traditional locks cannot, is provide an insurance option 'baked' into the usage contract. The first implementation of this insurance will be setting a deposit, which in the case of items that are too cumbersome to transport - or are of a low enough value - will work quite well. A more complex future implementation will include a link to a sharing economy insurance contract, something we are currently working on with partners.


### What happens if there is no power or Internet?

The same thing that would happen if any other smart lock was employed: some will 'fail secure' while others will 'fail safe'. Which mode of operation is used is not determined by the Slock DAO, but instead by the use case and local regulation. For example, fire rated and hotel room doors will probably 'fail safe' while a locker will certainly 'fail secure').




## The Product

### What exactly is the "Ethereum Computer"?

It’s the easiest entry point to the world of Ethereum, without having to struggle setting up a client, buying ether from an exchange or worrying about security updates.

The Ethereum computer is a tiny, preinstalled, preconfigured home server running both an optimized Ethereum node and exciting new decentralised applications, including Mist. The Ethereum Computer is putting identity, funds and personal information back under the users’ control, and we think it’s going to change _everything_.

Think of a little box that manages your permissions and identity, with strong encryption and permission control. Inside you’ll find a web3 identity vault, a Slock gateway to your IoT, and even experimental software like an IPFS server to rent your unused hard drive space — automatically.

- It’s the easier way to browse Dapps.
- It’s a secure gatekeeper between the web & web3 to your home or small office IoT, communicating wirelessly with your smart objects.
- And it’s also a brilliant development platform, packaging all the software needed to build Ethereum Dapps as part of a straightforward, optimized image.


### What could I do with the Ethereum Computer?

- Enable your entire home to communicate with the blockchain: rent your flat, or share any Slock.it enabled smart object directly and securely.
- Try out new, exciting applications: The Ethereum Computer is a full blown implementation of the Ethereum stack, and therefore can serve any Dapp via HDMI out to your home theater.
- Browse web3 securely: you can simply point your browser, mobile phone or tablet to the Ethereum Computer, and the 3rd party web servers will only be used to serve static HTML assets, while your precious keys will safely stay within the confines of your home.
- Participate in experimental programs: the Ethereum Computer can be used to run an IPFS node, perhaps even receiving rewards for renting your unused hard drive space.
- Develop applications with Ethereum and never have to worry about installation difficulties. We’ll sort out updates and compatibility issues between the various components of the Ethereum 'stack' (Whisper, EVM, Web3.js, Swarm, etc), and will push updates only when we have tested the framework top to bottom.
- Help secure the Ethereum network and get rewarded for it (once Ethereum has switched to PoS), without having to dedicate larger, more expensive and less secure equipment to that task.


### Will it be hackable/open?

Absolutely. We'll not only make the devkit images publicly available, but also all of the detailed code that went into building the 'stack' so you can modify/improve on the installation. One thing we're aiming to do is use a hardware (board+SoC) combination that is commercially available so that one could completely rebuild the Ethereum Computer from scratch if they wanted to. Having some GPIO available will also allow anyone to connect wired objects to the Ethereum network. We want you to be able to experiment!


### When will the Ethereum Computer become available for sale?

Sometime in 2017, although we anticipate devkits much earlier as part of an iterative development process.


### Will it be useful for mining?

The Ethereum Computer is a full Ethereum client and therefore perfectly capable to have its mining function enabled. That said, it would not be a good platform to mine on while Ethereum is still using proof of work, as its form factor prevents it from having the hashing power GPUs have. The Ethereum Computer will be a perfectly appropriate platform to help secure the network, but only once Ethereum switches to proof of stake.




## The Presale


### When is the Slock token presale?

It will take place at the beginning of 2016 and will last roughly two months. Further details will be released soon. 


### Why do a Slock token presale?

We're using smart contracts build on the Ethereum blockchain so people all over the world can be empowered to build a new future for the sharing economy, and in exchange for their early help, they will receive a reward in the form of Slock tokens which holds many benefits.

In order to keep governance fair and decentralized, a DAO will be created so that the funds held by the sharing community will never be centrally managed. A small fee representing the cost of decentralization is taken from each Slock transaction not paid in Slock tokens and returned to the DAO, giving it an option to reinvest the profits to support its growth.

Slock tokens holders will be able to vote on important decisions relating to the management of the DAO, including redistributing profits amongst Slock token holders. 


### What are Slock tokens?

Slock tokens allows the holders to:

- Vote on important issues in the DAO 
- Open or close Slocks without having to pay a fee to the DAO
- Trade them peer to peer or on exchanges
- If voted by the DAO, get access to a portion of the profits generated by Slocks, proportionally to how many tokens they hold


### What if users want to own a Slock outright?

It's possible, by paying a one-time deployment fee to the DAO. This will remove the per-use fee. Note that the amount in question will be determined by the DAO itself as it engages with the service provider.


### Can I mine Slock tokens?

No. Slock tokens are used purely to represent the proportion of votes a Slock token holder is entitled to as part of the DAO. If you would like to mine something, try [ether](https://github.com/ethereum/go-ethereum/wiki/Mining).


### Will I be able to send, receive and exchange Slock tokens?

Yes, there will be functions build in the smart contract to send/receive Slock tokens and peer to peer exchange will be possible from day one. 


### Will I need to be a programmer to purchase tokens?

No, we want to be inclusive every step of the way so that as many people as possible can participate in this new sharing community. The purchase process will be done entirely online via a simple website. If you already have an ether wallet, you'll be able to use that, or the site will just generate a wallet for you.
 

### Will anyone hold 'premined' tokens?

No. No one will get an unfair advantage: the only tokens in circulation will be the ones purchased during the Slock token presale.


### Will there be another opportunity to purchase tokens?

There will be only one Slock token presale. Once launched during the course of 2016, the Slock DAO will be fully autonomous and decentralized. How it then manages itself, including decisions on its finances, is entirely up to 'it'. Slock token holders will hold voting rights, be able to submit proposals, and pass motions.


### How will the DAO control the funds it receives during the presale?

The Slock token holders will elect the service provider of their choosing, and the conditions under which funds are distributed. These decisions are entirely governed by smart contracts, and accessible through a simple online interface.


### Is there a minimum goal for the presale?

Yes. A minimum of 700,000 ether (equivalent) is required to build a meaningful DAO and first product. If the minimum is not reached, participants in the presale will be able to get their funds back (denominated in ether).


### Will the presale accept Bitcoin, Doge, etc.?

Yes, we have partnered with Shapeshift so that the Slock token presale will accept most cryptocurrencies in existence, including Ether, Bitcoin, Litecoin, Doge, Maidsafe, StorjcoinX, Bitshares, BitUSD, Nxt, Dash, Clams and many, many others.


### Will the Slock token presale accept FIAT currencies?

Not directly. In order to take part, you must use a cryptocurrency. To exchange FIAT for cryptocurrencies you could use an exchange such as [Kraken](https://kraken.com).




## The DAO

### DA.. what?

A Decentralized Autonomous Organization (DAO) is a form of company which operates entirely on the blockchain. In our case, the DAO is made up of Slock token holders that can review proposals and cast their votes to elect and direct a service provider which will represent them in the physical world. This process is very similar to selecting a vendor or supplier. A DAO is however superior in many respects to a traditional company in the sense that all the decisions it makes are transparent, its finances can be audited by anyone and corruption is impossible.


### Is this just for geeks?

Definitely not. In order to make decisions, token holders will be able to vote using a straightforward interface using Mist, the Ethereum browser. You'll have to be able to install software on your machine, and use what essentially looks and feel like a website. That's it.


### What can the DAO do exactly?

The DAO can choose a service provider to implement a technology or develop a product, either by sending funds directly or signing a smart contract. The smart contract specifies the terms of the relationship between the DAO and its service provider.

Once a provider has been selected, the DAO can call functions on the service provider smart contract, setting the values of operating parameters which could include, for example, what percentage of each Slock transaction is used to further fund the DAO, or what milestones have to be reached before the service provider receives certain payments.

What parameters are available depend on the service provider's smart contract and could range from a 'hands off' approach to having the DAO hold complete operational control.


### Who can submit proposals to vote on?

Any Slock token holder.


### How often can the DAO vote on proposals?

As often as it wishes to.


### How will votes take place?

Version 1 of the DAO will be released at the end of the presale to hold the funds and allow basic voting. The voting will take place via the [official Ethereum GUI wallet](https://github.com/ethereum/mist/releases), through an automatically generated HTML interface. Version 2 of the DAO (to be released at the launch of the project) will make use a completely customized Dapp accessible via [Mist](https://www.youtube.com/watch?v=IgNjs_WaFSc), the official Ethereum Dapp browser.


### How can the DAO protect its funds from ether's volatility?

The Slock DAO can enter into a hedging contract to protect its funds from ether's volatility. This contract could be provided by a third party. Slock.it GmbH intends to submit a proposal on hedging to the DAO at the end of the presale.


### Why doesn't Slock.it GmbH raise money through a direct crowdsale instead?

Because we believe DAOs are the future of how businesses will be structured. A DAO will provide much greater security and transparency than a traditional presale as investors will stay in control of the funds even after the presale has ended. DAOs also bring about open governance by allowing any Slock token holder to vote on all major business decisions.

<br><br>

*Note: the following section of the document is technical and covers advanced topics that originate from Vitalik Buterin's blog post on [The Subjectivity / Exploitability Tradeoff](https://blog.ethereum.org/2015/02/14/subjectivity).*

### What's a 51% attack, and how do you prevent it?

If someone was to acquire 51% of the Slock tokens, they could vote themselves as the service provider, and then send 100% of the funds to their own account. In order to prevent this, the Slock DAO is able to split itself proportionally to the vote results, leaving the attacker with their funds and the rest of the  participants with their own. Because of this mechanism, there is no incentive to run such an attack, since it is not only unprofitable, but the attacker would also be stuck with worthless tokens from their own fork of the DAO.


### Why is there only a single service provider at any given time?

For safety reasons. In order to prevent a 51% attack, we needed to introduce the rule that the DAO may split up in case there is no mutual agreement on a selecting a service provider, which in turn removes any incentive to even attempt to bring about such an attack. Having room for more than a single service provider would negate this failsafe.


### How often can the DAO change service provider?

At anytime.


### What is the process for selecting a new service provider?

This takes place in two steps. The first step is a simple vote on keeping the existing service provider or choosing a new one. The second step is a confirmation vote, where the minority, having lost the previous vote but comfortable the winner is indeed not an attacker, can vote alongside the majority in order to avoid splitting the DAO. On the other hand, if the minority does suspects a 51% attack, it's important for it to keep its ability to stick with its decision to split the DAO, effectively rendering any attack unprofitable.






