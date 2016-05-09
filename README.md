# Donacha.in

## Donations through DAOs:
 
An open source smart contract to manage a DAO’s charitable donations. 

Contract could be integrated with a DAO so it could share revenues with charities selected by the members. 

Conversion to fiat and donation to any approved charities around the world.

DAO’s token holders would vote if, how much, how often and who to donate to. 



## Donacha.in PROPOSAL to The DAO:

The DAO is ushering in a revolutionary restructuring of the economy, one based on decrentralisation and transparency. Many are hopeful that it'll make the world a more equitable, better place. True to this end, having a system where a small portion of investor profits are automatically and directly distributed to some of the world's best causes (as voted on by members of The DAO) seems fitting.

Adding a multisig address to whitelist - smart contract to accept portion of the reward tokens (e.g. 1% of profit).

Whitelisted address is a smart contract. It recieves funds from reward tokens, converts to fiat (exchanges API) and distributed to chosen charities (e.g. via JustGiving API).

Address is multisig and private keys held by DAO curators and an outside agreed organization (possibly Donachain Curators)

The reward tokens for charity are distibuted annually. DAO members would be able to submit a proposal to the smart contract, e.g. to vote for 4 causes to donate to 25% each, from a list made up of curated entries pulled from justgiving.com. On a specific date every year (e.g. 31st Dec), funds starts being automatically transmitted to the causes based on the outcome of the vote (intially direct to charities, or later by a seperate proposal to a corresponding smart contracts if the cause is not an organisation - e.g. helping refugees directly). Effectively, the list of entries for the vote would be smart contracts themselves. Vetting by the curators would ensure that only legitimate philanthropic endeavors make it onto the ballot.

Track donation from blockchain explorer and charity receipt. 

An opt-out clause to give DAO members the option to re-allocate their donations either back to themselves, or somewhere else. Would require a simple nominal transaction (i.e. gas only) to be made manually (but default is that 1% of profit is donated). This is analagous to being able to take ETH out of the DAO - i.e. it minimises downside of proposal (but wouldn't effect membership of The DAO).

TBD

Whitelist address has extrabalance account for sporadic donations. This can be topped up manually by people wanting to donate more (over and above the 1% default): For example a slackbot for donations, to allow individual members to donate easily and seamlessly.



## Ideas for specific causes:

* GiveWell recommended charities (the gold standard for doing the most good) - Against Malaria Foundation (mosquito nets), Schistomiasis Control Initiative (deworming), GiveDirecly (unconditional cash transfers).

* Disaster relief through Facebook API for disaster reports (unused funds are allocated to other chosen charities at end of year).

* Excluding religious and political charities.

* Direct support (not via charities), for example refugee camps, or something analagous to GiveDirectly (unconditional cash transfers to the poorest families in the world). Would require widespread use of a low cost dedicated Ethereum Computer such as Consensus Hackethon Runner Up, Community Relief, built: https://docs.google.com/presentation/d/1XsiPjlgFsuV1kUEvydlvEuJzSv-m49ilPI4mb0bbDBE/edit?usp=sharing  

* Reducing Catastrophic/Existential Risk (risk of civilisational collapse, or human extinction) - see http://www.globalchallenges.org/reports/Global-Catastrophic-Risk-Annual-Report-2016.pdf



## RESOURCES

* http://pledge1percent.org/ - This is the model inspiring the smart contract. Allowing startup contributing 1% equity donations to charities (by warrants executed upon liquidation event/exit). 

* Http://proofofdoantion.com - A trusted transparent bridge for bitcoin donations to charities, uing justgiving.com api, other services and supports Donachain initiative. 

* http://www.justgiving.com  A large online offline gateway for many approved charities in UK, US and other countries, but could add more charities who hold the Dao’s standards. 

* https://github.com/slockit/DAO/wiki/How-to-create-a-proposal

* http://www.givewell.org/



**Digital currencies have more than $10B in market cap. LET'S MAKE 1% OF IT GO TO CHARITIES! This would go to the ones in need, and set an example to the rest of the world** 

