#Q1 - READING

#Q2 - Prisoner Dilemma

Reference: http://plato.stanford.edu/entries/prisoner-dilemma/

## a. What is it?

Given a sitation of confessing (defecting) or remaining silent (cooperating) for two individuals might not cooperate given if it best outcome for both of them

## b. Pareto

### What strategy is Pareto efficient in this problem, but less likely to occur in practice?

Cooperating is pareto effiectent, but is unlikely to happen defect COULD lead to a higher payout.

### Why is it less likely to occur in practice?

People generally act selfishly and think of their own reward not the collective group.

## c.  Can the apparant conflict in the previous statement be resolved? If so, how?

Yes, allow for communcation then the individuals can agree (to some extent). 

#Q3 - READING RFC968

#Q4 - False Economy

An action that saves money in the beginning but over an extended period of time results in more money being spent. 

##Vimes 'boots'
> Take boots, for example. He earned thirty-eight dollars a month plus allowances. A really good pair of leather boots cost fifty dollars. But an affordable pair of boots, which were sort of OK for a season or two and then leaked like hell when the cardboard gave out, cost about ten dollars. Those were the kind of boots Vimes always bought, and wore until the soles were so thin that he could tell where he was in Ankh-Morpork on a foggy night by the feel of the cobbles.

> But the thing was that good boots lasted for years and years. A man who could afford fifty dollars had a pair of boots that'd still be keeping his feet dry in ten years' time, while the poor man who could only afford cheap boots would have spent a hundred dollars on boots in the same time and would still have wet feet.

#Q5 - False Economy in terms of software

The false economy, totally applies to software. 

Using the example of university assignments. University students will have been given a programming task to complete, however the code that is produced is only good for that one case, it will be, generally, quite difficult to expand on it to make a more complete solution if more tasks are needed. 

However when deleveloping code that is not used for a one off solution, it is much more imporant to consider about planning since the code will be needed for many interations and changes not just a short term solution. 

#Q6 - Skype

## a. Usage

Skype is an application that allows you to communicate via voice, text, or video.

## b. What advantages are there in having an evaluation that is independent?

It should remove any company bias and theorically allow for more comprehesive analysis. 

## c. What did the evaluator look at, and why?

- the system that underlies skype for security faults or issues, to help skype become a more secure system and remove obvious holes

## d. For each of those policy statements what cryptographic property is being provided?

### 1. Skype usernames are unique.

- traceablity

### 2. Users or applications must present a Skype username and its associated authentication credential (e.g., password) before they exercise that username’s identity or privileges. 

- authentication


### 3. Each peer correctly provides the other with proof of its username and privileges whenever a Skype session is established. Each verifies the other’s proof before the session is allowed carry messages (e.g., voice, video, files, or text). 

- integrity

### 4. Messages transmitted through a Skype session are encrypted from Skype-end to 
Skype-end. No intermediary node, if any exist, has access to the meaning of these 
messages. 

- confidientality

## e. Types of Skype Cryptography

### Random Number Generation

- used for cryptographic primitives
- allows for messages to be encrypted (policy number 4)

### Cryptographic primitives

- used during the application for various uses
- Used for authentication (2), and message encryption and decryption (4)


### Peer-to-Peer Key Agreement Protocol

- for key agreement between clients/ client-server
- used for peer proving (2)

## f. List the standards that the Skype design and implementation can be tied to. Have any of those
standards been superceded?

- AES
	- Has not been superceded
- RSA
	- Not been superceded (however, small key sizes can be broken)
- ISO 9796-2
	- Not been superceded
- SHA-1 Hash
	- Superceded in some applications depends on usage
- RC4
	- Superceded in terms of it is recommended to use a modern stream cipher

## g. How is protection against replay attacks provided?

> The attacker could observe multiple handshakes involving a target node. This would give access to multiple challenges and responses. The attacker could then send a challenge to the target pretending to be a previous peer. The target would respond with a challenge of its own. If the target challenge was identical to one that the attacker had observed previously for this caller, the attacker could then answer the challenge correctly and proceed to the next aspects of the key exchange protocol. However, because challenges are 64 bits long and chosen at random, the probability of this happening is low. The chance of getting a challenge repeat from the client is, in the case of few observations, the number of observations N over the total possibilities, N / 2^64.


## h. Why are the side–channel attacks not considered to be a serious issue against Skype?

- since to perform this attack you need to be on the same platform of the skype client, which can lead to a much larger superset of issues

## i. 
> Integer overflow in Skype client before 1.4.x.84 on Windows, before 1.3.x.17 on Mac OS, before 1.2.x.18 on Linux, and 1.1.x.6 and earlier allows remote attackers to cause a denial of service (crash) via crafted network data with a large Object Counter value, which leads to a resultant heap-based buffer overflow.

References: 
http://seclists.org/fulldisclosure/2005/Oct/533
http://web.nvd.nist.gov/view/vuln/detail?vulnId=CVE-2005-3267

## j. What is the overall impression of the evaluator?

Overall he was quite impressed, and felt that skype considered security well.

## k. What signifcant changes have there been with Skype since this review?

- microsoft bought out company
- increased market share 
- more clients platforms now (mobile)
