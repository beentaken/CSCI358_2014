#Requirements Engineering, Threat Modelling and Risk Management

##Design methodologies

This is basically your run of the mill software engineering principles

###Issues

- testing theory was super important

###Safety Critical Systems

- cost of failure is infinite
	- tends to follow the waterfall model

###Analysing Reliability

- top down/ deductive
	- fault tree, event tree, threat trees
	- start with an undesirable outcome and draw down possible causes
- bottom up/ inductive
	- failure modes and effects analysis
	- looks at consequences of each system components failing
		- when do things fail
		- where do we need to detect
		- likely effects
		- how serious is a failure

###Misuse Modelling

- similar to usecase but reversed
		
##Security Requirements Engineering

threat model -> security policy -> security mechanisms

- top down needs risk mgmt and assessment infrastructure
- infrastructures needs to be able to
	- stop devs building systems vulnerable to known bugs
	- monitor and act on changing protection requirements, effectly on a changing security policy

###Why change

- to fix
	-Bug fixing pointers
		- learn vulns
		- respond appropriately
		- rapid patch distribution
		- manage the media
- improve
	- engineering is an experience fed process
- deal with external changes (ecosystem)
	- new tech 
- deal with internal changes (organizational)
	- changes in the way parts of org interact

##Risk Management

- “Management is that for which there is no algorithm. Where there is an algorithm, it’s administration.”

- Identify assets and their values.
- Identify vulnerabilities and threats, and the associated results and costs.
- Identify attacks and the associated probabilities.
- Identify appropriate counter measures and the costs thereof.
- Balance the cost of the countermeasures against the value.

##Types of vulnerablilities

- behavioural and attitudinal
- Misinterpretations
- physical
- technical 

##Types of threats

- non malicious
- malicous
- treat things in threat classes

##Options for dealing with risk

- disown the risk
- counter measures
- transfer/ share the risk
- accepting the risk

##More formal risk management

- cost benefit analysis
- Single loss expectancy 
- Annualized loss expectancy
- Risk matrices
