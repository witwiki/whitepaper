Rex White Paper

# White Paper

Update 19/08/2016: A few things have changed since we wrote this whitepaper, and will probably continue to be tweaked as development on the platform continues.  The core structure will stay the same, but things like fees and distribution schedules may be tweaked before we do the full launch.

## A Decentralized Multiple Listing Service and Real Estate Smart Contract Application  

Rex: We are referring to the DAO, Rex  
REX: We are referring to the token, REX

Real property, property defined as anything that is owned by a person or entity that has any interest in land, real estate, or the improvements on it, has existed since man first settled the ancient lands of Mesopotamia in 4500 BCE [[4]](#references) [[6]](#references). Over time, title was created as a legal means to document property ownership. Traditionally, obtaining reliable property information and an accurate chain of title was difficult. Today, with advances in technology, data has become much easier to ascertain. However, the data has become controlled, manipulated, and governed by centralized organizations, resulting in exorbitant transaction and listing fees. With recent advances in peer-to-peer data distribution and blockchain technology, Rex recognizes the opportunity to streamline the transaction process and provide an inexpensive means to disseminate real estate information. The result will be low transaction costs and a means for users to view and list property data, virtually, for free.

### Table of Contents

* [Today](#today)
	* What is a multiple listing service?
	* The current transaction process

* [History](#history)
	* Blockchain
	* 1.0 & 2.0 Listing Services: Black's Guide/CoStar/Loopnet
	* Today’s process for transferring Title
 
* [Ethereum](#ethereum)
	* What is Ethereum?
	* Why is Rex building on Ethereum? 

* [IPFS/Swarm](#ipfsswarm)
	* Current data distribution model
	* What is IPFS/Swarm?
	* Benefits to Rex

* [Problem/Solution](#problem--solution)
	* Unreliable, limited access, expensive information
	* Streamline the transaction process 

* [Rex](#rex)
	* Phase I
	* Phase II
	* Token Release Schedule
	* Transaction Fees
	* Funding

* [Concerns](#concerns)

* [Conclusion](#conclusion)

* [Founder Biographies](#founder-bios)

* [Links](#links)

<a name="today"></a>
## Today


What is a multiple listing service?


A multiple listing service (MLS, also “multiple listing system” or “multiple listings service”), is a suite of services that enables real estate brokers to establish contractual offers of compensation (from brokers), facilitate cooperation with other broker participants, and accumulate and disseminate information to enable appraisals. An MLS also acts as a facility for the orderly correlation and dissemination of listing information to better serve brokers’ clients, landlords, tenants, and the public [[5]](#references). A multiple listing service’s database and software are used by real estate brokers and real estate owners to share information about properties with other brokers/owners/buyers/tenants.


The current transaction process:

A buyer/tenant/broker searching for a house, office, warehouse, or retail space typically starts their search with on an online platform such as CoStar, Loopnet (commercial) or Zillow, Trend, or Investorist (residential). The accessible data is limited before the user hits a paywall. The data beyond the paywall is usually relevant for a short period of time and specific to one geographic location. The same is true for a seller/landlord/broker seeking to list a property. The above platforms require memberships that enlist high annual fees and collect superfluous data about their users.


![Search](/assets/search.png)

After a buyer/broker subscribes, they engage the listing owner/agent. In the United States, the buyer’s broker and the seller’s broker first negotiate the price. Next, the buyer and seller have their attorneys draft, edit, and finalize the Purchase & Sale Agreement (PSA). Within the PSA is a list of terms the buyer and seller must perform in order for the transaction to be consummated. The buyer is typically permitted 60-90 days to perform due diligence. Due diligence includes, but is not limited to:

1. Title report
2. Structural inspection 
3. Electrical inspection
4. Well/septic inspection
5. Roof inspection
6. Environmental inspection
7. Lien queries

During due diligence, the seller will perform certain obligations as spelled out in the PSA:

1. Building repairs
2. Municipal approvals
3. Cure outstanding judgments/liens
4. Obtain a certificate of occupancy 

Throughout the transaction, the buyer and seller communicate through their hired attorneys and real estate brokers. The chain of communication inevitably leads to delays.


![listing](/assets/communication.png)

The delays lead to higher attorney fees. Finally, once both sides meet their respected obligations, a closing date is set. The following is a brief list of documentation required for the transaction to take place:


1.	Title search
2.	Real estate transfer/bulk sale tax requirements
3.	Insurance requirements 
4.	Inspection reports
5.	Commission invoices
6.	Funds


A typical closing can take 2-4 hours. In the United States, closing costs average $10,000 for residential sales and $20,000 for commercial sales (subject to the size of the deal).

Example:


Bob wants to sell a mixed use building in Princeton, New Jersey:


Address: 236 Nassau Street

Price: $3,500,000

9 1-bedroom apartments

2 retail units

Net Operating Income: $175,000

Capitalization Rate: 5%

Bob decides to list 236 Nassau Street on Loopnet.com. After several weeks with no traction, Bob decides to signup for Loopnet's premium addition ($299.95/month). Loopnet's premium edition grants Bob access to similar properties listed in Princeton. After three more weeks and no action, Bob decides to obtain comparable properties to see if he priced his property correctly. Bob pays $90.00 to obtain three comps. Bob realizes the data isn't helpful and tries to return the service for his money back. Loopnet denies Bob’s request, but provides a credit for Bob to obtain future comparable properties instead. Next, Bob realizes his property is at the bottom of the search query. For an additional fee of $399.95 for 30 days, Bob can have 236 Nassau Street listed as "platinum" in the search results. Bob proceeds with the platinum listing.

Finally, Alison's broker comes across Bobs listing through the search query and presents it to Alison. Alison likes the property and decides to proceed with an offer. Alison's broker puts in an offer for $3,400,000. Bob accepts the offer contingent on the following:

1.	Alison must provide evidence she can get a 70/30 loan to value financing with her lender.
2.	Alison must complete her inspections no later than the 60th day after the PSA is duly executed (structural, electrical, environmental, roof).
3.	Alison must close five days after the due diligence period ends. 


Alison agrees to Bob's terms contingent on the following: 


1.	Bob must repair the damaged sidewalks in front of the building and obtain an electrical inspection from Princeton Township.
2.	Bob must replace the cast iron waste line with PVC. 
3.	Bob must replace the damaged roof shingles. 
4.	Bob’s building must pass a fire inspection.


Bob and Alison's attorney draft the contract. Alison deposits $175,000 in her attorney’s escrow account. On the 60th day, Bob and Alison's attorneys communicate both parties have performed the obligations stipulated in the PSA. A closing a date is scheduled, and after several hours of paperwork, title is passed. Finally, Alison goes to the municipality to record the deed to provide actual ownership.

Combined, Alison and Bob paid +/- $40,000 in transaction costs. 

<a name="history"></a>
## History

### Blockchain

The blockchain is a distributed database or public ledger that gained popularity following the release of Bitcoin. It maintains a continuously growing list of all transactions in a particular network that have ever been executed. The “blocks” are added in chronological order with cryptography to prevent tampering, thus becoming an indelible record of every transaction in the network and accessible to every participant [[1]](#references).

### Listing Service 1.0 (Pre-Internet) 

Pre-internet, the commercial real estate industry relied on Black's Guide (or alike services) for dependable real estate information. Black's Guide provided a bi-annual paper release of available listings in the northeast. Local Markets throughout the world used similar systems to disseminate property information. Content quickly became dated and unreliable to the broker. 

### Listing Service 2.0 (Post-Internet, Pre-Blockchain)

![listing](/assets/listing20.png)


In the United States, there are two main commercial listing providers:

1.	CoStar

2.	Loopnet

Loopnet is a “freemium” commercial platform allowing non-paying subscribers to have limited access to property information. Loopnet is infamous in the brokerage community for providing dated, unreliable content with exorbitant fees for additional services:

-$299.95/month  - Up to 10 listings 

-$399.95 for a 30-day period to list your property as a “Platinum Property” 

-$90.00 one time fee to view “up to 3 comparable properties”

Loopnet has a poor reputation outside the brokerage community too. Common complaints include the lack of price transparency, user experience, and dated information [[2]](#references). Loopnet also limits the amount of data a “non subscriber” can view. Loopnet was recently purchased by CoStar, which is now operating as an unofficial monopoly in the United States. 

CoStar (CSGP) is a publicly traded company located in Washington D.C. CoStar provides the brokerage community with detailed property information including price, type, building size, vacancies, and general market trends through paid research associates. CoStar charges an annual minimum fee of $3,500 USD per certificate, per computer. CoStar hires an army of researches that constantly contact real estate brokers to verify listing information. The flaws of the system include:

1.	An unsustainable business model:

	* First, the evolution of technology provides cheaper, more accessible information. Although CoStar content is more reliable than most they have one large obstacle: Brokers provide fragmented information to protect long-term interests. For example: 

		Broker A provides CoStar with a recent deal they transacted:

		Tenant: ABC Inc. 
		Size: 20,000/SF 
		Address: 123 Main Street 
		Term: 5 years
		Price: $25/SF

		CoStar then publishes the transaction on their database. Broker B views the transaction. Broker B starts soliciting the tenant in year four with the knowledge ABC Inc's lease expires within 12 months. Broker A is now competing with Broker B for ABC Inc's business. 

		The result is most brokers provide little or fragmented information in which CoStar is building an unrelaible data base.  

	* Second, CoStar has overhead issues as a result of their research arm. 

2.	CoStar’s audience is limited to the brokerage community. Mostly due to cost, the average buyer/seller doesn’t have access to the data. This excludes a large portion of the market looking to purchase, sell or lease property. CoStar also doesn't not provide detailed property data such as title, tax, encumbrances, easements and environmental reports.  

<a name="ethereum"></a>
## Ethereum

### What is Ethereum? 

The Ethereum system has sometimes been described as a single shared computer that is run by the network of users, on which resources are parceled out and paid for by Ether.

### Why is Rex building on Ethereum?

Data needs to be on a server. A server is generally owned or leased by a corporation. Therefore, the individual relinquishes control of their data. 

This simple fact leads to massive abuse of power and greed by the owner of the server/data.

We now have the means of decentralizing data. BitTorrent, Swarm, and IPFS can do that on their own, but the blockchain provides the ability to organize and order the data with no central authority. Ethereum provides a means to mesh together the blockchain, data distribution, and currency all under one roof. Ether acts as a convenient medium in which Ether can be exchanged for REX, and REX will fuel the application. This is the absolute value Rex sees for blockchain and Ethereum technology. 

Rex is building on the Ethereum protocol for several reasons. The first reason is to provide a distributed database that is not maintained or operated by one central authority. This provides two advantages:

1.	The user always has access to their information.
 
2.	There is more price stability. No central authority owns the information thus placing capital controls on the data.

Over time, Rex will provide a comprehensible history of each individual parcel. Rex will implement the use of smart contracts through escrow, title, and identity services, while simultaneously compiling the data in an easy to read, traceable format. Ethereum provides the foundation to make this possible. Contracts will be accessible in real time thus providing practical, usable information.

<a name="ipfsswarm"></a>
## IPFS/SWARM 

Data distribution (Today)

The HTTP protocol has been a useful tool to send and receive data packets from one or more central servers to the requesting node:


![http](/assets/http.png)
  


However, today we distribute much larger packets of information. If a large number of users request the same packets of information, the server can become overwhelmed. This results in latency, downtime, and maintenance requirements. Inevitably, this drives up costs for the owner who passes them on to the user. In 2016, the HTTP protocol has become a dated and antiquated technology. We are at an inflection point where nodes no longer need to communicate through one centralized route but rather from peer-to-peer. 

What is IPFS/Swarm?

IPFS: 

The Interplanetary File System (IPFS) is a new hypermedia distribution protocol, addressed by content and identities. IPFS enables the creation of completely distributed applications. It aims to make the web faster, safer, and more open.

IPFS is a peer-to-peer distributed file system that seeks to connect all computing devices with the same system of files. In some ways, IPFS is similar to the Web, but IPFS could be seen as a single BitTorrent swarm, exchanging objects within one Git repository. In other words, IPFS provides a high throughput content-addressed block storage model, with content-addressed hyperlinks. This forms a generalized Merkle DAG, a data structure upon which one can build versioned file systems, blockchains, and even a Permanent Web. IPFS combines a distributed hashtable, an incentivized block exchange, and a self-certifying namespace. IPFS has no single point of failure, and nodes do not need to trust each other [[3]](#references).

Swarm:

Swarm is a distributed storage platform and content distribution service. It is a native base layer service of the Ethereum web 3 stack. The primary objective of Swarm is to provide a sufficiently decentralized and redundant store of Ethereum's public records. In particular Swarm stores and distributes Đapp code and data as well as blockchain data. From an economic point of view, it allows participants to efficiently pool their storage and bandwidth resources in order to provide the aforementioned services to all participants.

From the end user's perspective, Swarm is not that different from WWW, except that uploads are not sent to a specific server. The objective is to provide a peer-to-peer storage and serving solution that is DDOS-resistant, has zero-downtime, is fault-tolerant and censorship-resistant, and is self-sustaining due to a built-in incentive system, which uses peer-to-peer accounting and allows trading resources for payment. Swarm is designed to deeply integrate with the devp2p multiprotocol network layer of Ethereum as well as with the Ethereum blockchain for domain name resolution, service payments, and content availability insurance [[8]](#references).

How IPFS and Swarm can work together: 

According to Viktor Tron, IPFS enables Swarm to redefine itself as a modular system where standard interfaces allow mutually interchangeable components. Swarm offers an operational mode where the retrieval end of the protocol could use the IPFS distributed hash table (DHT) or the default IPFS stack could use Swarm's erasure coding scheme or incentive system [[7]](#references).


Benefits to Rex:

IPFS/Swarm coupled with Ethereum will enable Rex to distribute data across hundreds of nodes with no central server. The result is a low cost solution that will enable users to virtually view real estate information for free. 

<a name="blah"></a>
## Problem / Solution
Problem:

1. Current MLS databases are expensive and the information is unreliable.

2. Transacting real estate is expensive, time consuming, and inefficient. Banks, lawyers, and title companies charge high fees and delay the process.


Solution

1.   Create a decentralized multiple listing service with low listing fees. *Get users comfortable with smart contracts and token use. 

2.   Create a platform that will process/standardize purchase and sale agreements, leases, escrows, and eventually the transfer of title.

Rex will create an international multiple listing service. Over time, Rex will transition users to the convenience and comfort of transacting real estate via Rex’s platform. 

<a name="rex"></a>
## Rex

Reed Hastings built Netflix with the idea of streamlining the way consumers view content. Using Hastings’ platform, consumers could rent a video online to avoid the inconveniences associated with traditional retail rentals (time, travel, and late fees). The value of Netflix was created through the maturity of digital technology and the comfort of paying/obtaining content via the internet. Netflix capitalized on both opportunities and remained patient through the transition period. Today, Netflix is one of the largest content providers in the world.

Rex envisions that blockchain technology will take a similar path. The technology requires time to evolve and the consumer requires trust in the system. 

Rex will roll out its platform in two phases:

**Phase 1:**
  
![ipfs](/assets/rexmls.png)

A decentralized, global, multiple listing service. Users can virtually view/list properties for free while becoming comfortable with cryptographic transactions. Initially, Rex will focus on the commercial industry in the United States. As the platform develops, Rex will incorporate residential and begin to scale internationally. Rex believes Phase I does not violate or obstruct any existing US Laws.

As the technology advances and user trust is gained, Rex will begin the roll out into Phase II.

**Phase II:**

Rex will offer escrow, title, and legal agreements through smart contracts. Starting in the United States, Phase II will require a heavy focus on the legality of smart real estate contracts. Most laws have not been written and it will take Rex’s team to lobby on behalf of the crypto/real estate community creating these laws. Rex will capitalize on existing relationships we have in the real estate industry and expand the team with specialized lobbyists in Washington. As Rex scales internationally, we will expand the team. Local teams will assist to make sure Rex is complying with local laws and regulations. 


Token Specifics & Release Schedule

Rex has their own internal token exchange: RexDex (Rex Decentralized Exchange). The RexDex will provide a means for users to exchange Ether for Rex and visa versa. 

Liquidity Injection Distribution (L.I.D.)

Rex invented a new means of token distribution, the Liquidity Injection Distribution. L.I.D. is the process in which the top 10 bidders on the RexDex (price * duration) are rewarded every six hours with up to 35,000 newly issued REX.

With an initial coin supply of zero, there needs to be a way for Rex to distribute the REX tokens as fairly as possible. There will be 4 ways users can obtain REX.

1. Place buy orders on the REXDEX, hope to win the Liquidity Injection Distribution rewards, or have someone take your offer
2. Participate in the REX token swap 
3. Claim 'The DAO' reward points for REX 
4. Start submitting listings as a registered broker and receive listing rewards (for a limited time)


Rex token information

* 1,000,000,000 max token supply
* 0 initial supply
* 50 REX fee for uploading a batch of listings (adjusted to be around 10-20c)

* DexLid distribution schedule
  * Supply < 500,000,000 reward = 35,000 every 6 hours
  * Supply < 750,000,000 reward = 15,000 every 6 hours
  * Supply < 1,000,000,000 reward = 7,000 every 6 hours
  * At full distribution speed it will take 30-40 years to issue all 1 billion

* At full distribution speed and < 500,000,000 supply we are creating about 50million REX per year.
  * DexLid winners receive 50% of their offer
  * DexLid winners pay 50% of their offered price for the 50% reward
  * REX sellers pay 0.5% REX fee per trade


**Rewards**

Initially, the RexToken contract will allow the creators to issue rewards based on evidence of listings. Registered listees will be eligible for a 100-500 REX reward for each valid listing they add to the system, with a bonus reward of 1,000 REX if it is listed exclusively (which will be proven after a month or two).

REX will have an auto reward for "registered" sellers with a 1-month payment delay. If they are found to be listing fake listings, the user will be banned, named & shamed, and lose their 1-month pending payments.

By doing automated rewards, Rex can keep issuing rewards for up to 1,000,000 listings a year, at which point REX would be issuing 100,000,000 or 10% supply per year. At this point, the rewards will be discontinued. 

**RexDAO 1 year of successful operation reward**

Rex will make available 10,000,000 REX tokens to the RexDAO after 12 months of operation, which the RexDAO holders can use at their discretion. It may be implemented as a staggered release, i.e. 1 million REX per 6 months, up to the 10 million.  

### Transaction Fees

RexDex (Rex Decentralized Exchange) is built into the UI; users can use it to buy/sell REX tokens against Ethereum. Initially, no one will have any REX and users will place their bids on the RexDex. After 6 hours, the LID (Liquidity Injection Distribution) process will reward the top 10 (price * duration) with UP TO 35,000 newly issued REX. If the top 10 bids are greater than 70,000 of REX, then the max 35,000 REX will be issued. As an example, let’s say the bid begins at 0.0002 ETH per REX. The contract (i.e. REX) takes half the Ether being bid. In this example 35,000 / 2 = 17,500 REX * 0.0002 ETH = 3.5 ETH or roughly $35 USD. This happens every 6 hours.

In addition to earning the proceeds of the LID process, REX will charge a low 0.3% fee on every sale of REX via the RexDex. 

Example:

There are 500,000 REX sold every day. That's 1,500 REX the DAO will earn per day in RexDex fees. Priced as above, @ 0.0002 ETH per REX is about 0.3 ETH, or about $3 USD a day.

Selling: 

Let’s say there is lot of selling of REX: all the top bids are being consumed (i.e. sellers are selling) then the LID process "top 10 bids" will have been consumed, and it will not issue any REX for that 6 hour window. Rex supply could only be at 1 million REX (instead of 1 billion) and it will stop inflating the supply completely until the selling stops.

With no inflation and fees being taken in RexDex fees, listing upload fees etc., the supply should be dropping. 

<a name="funding"></a>
### Funding

Initially, Rex will hold two fundraising campaigns:

Token Swap #1: Prototype to beta release. We estimate a 6-9 month period with a budget of 45,000 ETH (Token swap forcefully closed at 90,000 ETH). A large focus will be on mastering data distribution, implementing a streamlined user experience and the release of a soft beta launch. 

Funds will be deployed as follows:

1. Add to the core development team 
2. Legal
4. Travel expenses (promote Rex at real estate conferences/events)
5. Marketing 

Token Swap #2: Following the release/testing of beta, Rex will raise Campaign #2. Campaign #2 will be a larger round that will fund the continuation of Phase I and begin Phase II of the Rex platform. 

<a name="concerns"></a>
### Concerns

Rex is going to have to overcome the following three hurdles in relation to revenue:

1.	Convincing users to "jump ship" from existing, well-populated MLS systems to Rex. The real estate community is typically naïve when it comes to new technologies. Paying users to list should mitigate some of these concerns.  

2.	Legal: After careful research, we believe Phase I does not violate any US/Australian laws. In Phase II, regulation is largely unwritten. Rex will be a pioneer in the implementation of smart real estate contracts. The development team is engaging a major US law firm that specializes in crypto currency for parts of Phase I and continuing that work into Phase II. 

<a name="conclusion"></a>
### Conclusion

The internet has matured through two major iterations. The first was the creation of the HTTP protocol, static web pages, and content creation/distribution. The second iteration consisted of building applications on top of the HTTP protocol (the transition from content creation by owner to content creation by user i.e. Facebook, Twitter). The third iteration, as Rex sees it, is data democratization. 

We believe your listing data should be free. With today’s advances in storage/bandwidth, projects like IPFS/Swarm, and flexible blockchains like Ethereum, we can rebuild the old systems into decentralized platforms. Users will retain real estate data and not become a product of a larger corporation. Thus, the large corporations will be faced with new competition from their former products or "users.” 

<a name="founders"></a>
### Founder Bios

**Stephen King**

Stephen is an entrepreneur with a focus in commercial real estate and blockchain technology. Since 2013, Stephen has lead King Realty Group in Princeton, New Jersey and participated in over forty-five million dollars in real estate transactions. Stephen is the founder of Princeton Ethereum Meetup. 

**Russell McLernon**

Russell is the technology strategist. He brings over 15 years of experience in enterprise software development and over 7 years in blockchain related development and projects. He is a passionate supporter of cross platform development, blockchains and decentralized systems in general.

<a name="links"></a>
## Links

**Rex Landing Page**  
http://www.rexmls.com/

**Rex Blog Page**  
http://www.rexmls.com/blog/


<a name="references"></a>
## References

1. https://cre.tech/will-sleepy-real-estate-industry-wake-blockchain
2. http://www.yelp.com/biz/loopnet-san-francisco-2 
3. https://ipfs.io/
4. http://legal-dictionary.thefreedictionary.com/Property+(ownership+right)
5. https://en.wikipedia.org/wiki/Multiple_listing_service
6. http://digitalcommons.law.yale.edu/cgi/viewcontent.cgi?article=1409&context=fss_papers
7. http://www.ibtimes.co.uk/ethereums-viktor-tron-talks-about-swarm-skeleton-web-3-0-1560654
8. http://swarm-gateways.net/bzz:/swarm/
