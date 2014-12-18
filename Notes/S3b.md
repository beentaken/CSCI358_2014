#Providing C.I.A.: Cryptographic constructs

##Providing C.I. and the other A.

- confidientality
	- cleartext: directly available
	- plaintext: input to encryption
	- ciphertext: output from encryption
	- encryption: providing confidentiality
	- decryption: revealing content
- integrity
- authentication

Shannon's Statement - "Assume the enemy knows the system"

##Keys.

- number of solutions

##Symmetric key encryption.

- block
	- block length
	- key space
	- balance
	- modes
- steam

##Key transport.

- hard to get keys from one place to another
##Public key cryptography.

- like telephone
- one way transform with trapdoor

##Fitting things together.

- symmetric 
	- fast
	- hard to setup
- PKI
	- slow
	- authenticity and efficieny are the problems
	
##Hashing

- used for providing integrity for messages
- transforms data to a fixed length
- needs some attributes
	- one way/ pre image resistanct
		- given a hash, its hard to find an input that products the same hash
	- collision resistance
		- hard to find two messages with the same hash
	- second pre-image resistance
		- given a message it is hard to find another message with same hash
		
##Other properties

- anonymity
- tranceablity
- privacy
- denialibaity
- non-repudablity
- accountablity
- freshness

