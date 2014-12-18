#Communication and cryptology

##What can we do with data?

- store
- transmit
- process

###The communication model.

- from A to B via transforms

###Desirable properties.

- security
	- Confidentiality: assets should be inaccessible to unauthorised parties
	- Integrity: assets should be unmodifiable or unforgeable, without detection, by authorised parties
	- availabiltiy: assets should be available to authorised people
- authenticity
	- needs access control
- reliability
- efficiency

##What is cryptology and why is it relevant?

- cryptology: entire discipline devoted to the study of all aspects of systems for achieving (information) security

###Cryptography and cryptanalysis.

- Cryptography is the sub-discipline of cryptology which deals with the design and implementation of secrecy systems.
- Cryptanalysis is the sub-discipline of cryptology which studies techniques for breaking the systems studied in cryptography

##Modern approaches to cryptography.

- security notions
	- goal
	- attack model
	
##What does it mean to be secure?

- computationally secure if the difficulty of achieving the goal under the given attack model is beyond the computational resources of an attacker

##Some terminology.

- compromised: by-passed or breached
- broke: if there is an attack that is better (computationally) than brute force

##“Layers of cryptography”.

1. secure systems
1. advanced protocol
1. basic protocols
1. primitives
1. axioms
