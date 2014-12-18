#Access Control

##What is access control

- access: able to do something or get somewhere
- control: to restrict or allow
- access control: being able to restrict or allow particular actions

##Representations and implementation

- how?
	- we write rules
- access control is about the implementation
- difficult to implement

##who should be able to access what

- a rule for everyone
- a rule of everything
- a rule for every action
- principle of least privilege

##Some formalism

- subjects: entities that use
- objects: entities that ae used
- actions: the way in which subjects can use objects

- collection of a above is a good example of access triples

1. a rule for everyone
2. a rule for everything
3. a rule for every action

^ for every situsation

###Least Privilege

- give subjects as much access or authority as they need to carry out their job and no more

####Side effects 

- least time of permission
- default deny

###Operating principes

- separation of duty
- separaction of function
- auditing

##Logical and physical

- logical: computing
- physical: doors

##Questions

- subjects of system?
- objects in out system
- actions in our system
- what tuples are allowable 

##Answers 

- security policy model: statement of protection properties a system must have
- security target: records the correpondance  between the protection mechanisms implemented and the access control objectives
- protection profile: similar to the above but in implementation indepentent language

###Multilevel security

- BLP: confidentiality based
	- no write down, no read up
- Biba: integrity based
	- no write up, no read down

###Lipner Model

- makes a lattice

####Classification for confidentiality

- CAM: audit manager
- CSL: system low

####Categories for confidentity

- CP: production
- CD: development
- CSD: System development

####Classification for integrity

- ISP:system program
- IO: production programs
- ISL: system low

####Categories for integrity

- ID: development
- IP: production

- Then you put this in a matrix
