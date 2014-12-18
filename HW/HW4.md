#Q1 - Reading

#Q2 - Schneier Newsletter

Refers to:
https://www.schneier.com/crypto-gram-1402.html#1

Title: Finding People's Locations Based on Their Activities in Cyberspace

##Reason for choosing this topic

I think as information security people we tend to be obsessed over the actual cryptographic methods but sometimes we tend to overlook the human factors and factors that are external to our systems. One of these are mobiles phones and the internet. And this article "Finding People's Locations Based on Their Activities in Cyberspace" is interesting as we can obfuscate and hide and encrypt our messages but we cant hide ourself.

##Summary of what this entry is about

This article is dealing with how a government security firms track people in the world via a various means. Namely using  
- triangulation using GSM networks complemented from the use of drones
- using wifi information 
- using applications/ webapps since they leak geo-locations 

##Security problem of reference

- communicating securely over each of OSI layers
- how modern technology (not that modern in terms of phone/ gsm, but modern for social networks or wifi networks)
- full end to end encryption

##How it relates to the subject

- 10: Physical Security
- 11: Development of Secure Systems

##Challenge Question

- How would you choose to balance of anonymity of people and traceability? 

#Q3 Zoo Animal

##Animal: Owl

###Properties
- can fly, cant swim
- has feathers 
- cant tolerate cold
- needs to eat 
- needs to drink
- is nocturnal 
- has talons
- small

###Secure Environment

Note: Im defining secure as the animal can not harm itself and nothing external can harm it

The owl should live in a closed off, perhaps covered by glass or net. The owl should be able to have access to food and water. The owl should be in a night cycle since it is a generally a nocturnal. The owl should be not be able to harm itself with its talons or harm others. 

##Animal: Bear

###Properties
- cant fly, cant swim
- has fur 
- may tolerate cold
- needs to eat 
- needs to drink
- very large 
- powerful 
- has claws

##Animal: Fish

###Properties
- cant fly, can swim, cant be on land
- has scales 
- may tolerate cold
- needs to eat 
- needs to drink
- is small
- must be in water

##General Properties

- animal abilities
- environment requirements 
- dietary requirements
- size requirements

#Q4 RFC2196

Refers to: http://www.rfc-editor.org/rfc/rfc2196.txt

## RFC2196 obsoletes RFC1244

Refers to: http://www.rfc-editor.org/rfc-index2.html

- it means that the information that was represented in rfc1244 is now outdated and the information is now represented in RFC2196 (with more updated information)

## RFC2196 obsoletes itself? Why?

It a way, yes, since infosec is constantly changing. 

## Section 4; Login Banners

Section: 4.5.4.5  Choose Your Opening Banner Carefully

- the reason why login banners should differ is that then you dont leak information and you know where abouts you are logging into.

## Section 6; Continuing Activities

Section 6: Ongoing Activities

###Ordering

1. Subscribe to advisories that are issued by various security incident response teams, like those of the CERT Coordination Center, and update your systems against those threats that apply to your site's technology.
1. Monitor security patches that are produced by the vendors of your equipment, and obtain and install all that apply.
1. Actively watch the configurations of your systems to identify any changes that may have occurred, and investigate all anomalies.
1. Regularly check for compliance with policies and procedures.  This audit should be performed by someone other than the people who define or implement the policies and procedures.
1. Read relevant mailing lists and USENET newsgroups to keep up to date with the latest information being shared by fellow administrators
1. Review all security policies and procedures annually (at a minimum).

###Justification

- The big advisories are fairly major, and will announce any new patches. If you don't patch at the time, you are open to a known exploit 
- if your vendors are exploited and you do not patch you will be exploited against 
- check if anyone is trying anything malicious 
- you need to ensure that the humans (are following procedures) (preventing human exploits)
- the mailing lists might have valuable but unpublished exploits and patches
- ensuring that your P&P are still sane after a year

- ordered them in order of things you can control to things that are hard to control


## Section 7; Tools

Reference: Westlund, Harold B. (2002). "NIST reports measurable success of Advanced Encryption Standard". Journal of Research of the National Institute of Standards and Technology.

- AES has been superseded by DES

#Q5 Humans

##Teller in bank

- you can threaten a teller for money
- tellers have a drawer of (considerable) money, and have easy access to it
- cash money

##HR person

- you can threaten for employment or information
- HR has access to private information and can allow for employment
- data/information & employment

##Sportsperson

- bribed
- sportperson can be used for its huge following this could be exploited
- following / influence

##Educator

- bribed
- they can teach bad information, which can be leveraged in someway?
- uneducated people

#Q6 Game Theory

##Dominant Strategy

- the strat that gives the best return a player, regardless of everyone else 

##Nash Equilibrium, differences from dominant strategy equilbrium

- nash: best payout for everyone
- dominant strat: best payout for player

The difference is payout for everyone (which can lead to a better net payout) (nash) comparied to best payout for one (or set of) players.

##Prisoners Dilemma

- the dominant strategy is not the best strategy since the payout for everyone becomes worse. However if you take the non dominate strategy is better for everyone.

#Q7 humancambridgepreproc.pdf

1. ordering wine
  - properties
    - secret commication
    - integrity
    - non-repudiation
  - well optimized
  - little threats
- lessons learned
  - repeated interactions give properites
  - lacks formal notation but is very standard

2. Voting
  - lessons to learn
    - when thinking about moving over to a new protocol we should consider what properties was good about the old system and that we are trying to replace
    - 

- Paying check 