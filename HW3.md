#Q1. Reading

#Q2. Reading

#Q3. 

##Library

- staff
- patron
- contractor

##Restaurant
- staff 
  - bar
  - wait
  - 
- patron
- contractor
- manager/ owner

##Zoo
- staff 
- patron
- contractor


#Q4.

Yes.

since there is a appearent weakspot in your systems you will know where the **likely** attacks will take place this will help with your defence against the attacks since you can focus resources accordingly. Furturmore you can use the weakspot as a honeypot or have the weakspot as a isolated environment.

#Q5.

Referenced
https://en.wikipedia.org/wiki/Base_rate_fallacy
https://en.wikipedia.org/wiki/Base_rate

In terms of a base rate fallacy for false positive and false negatives it would be a case of

You have a system and it has a 90% chance of identifying correctly positive and negatives. 

However when it when incorrectly identifies it has a 99% chance of being the other case (*my phrasing is probs bad here*).

Even thought it is unlikely of being incorrectly identified (10%) since people thing it it extremely likely to be the other case. However people will focus on the 99% since they are people even though it is unlikely to fall in that scenario.   

#Q6.

referenced
http://en.wikipedia.org/wiki/Biometrics

>equal error rate or crossover error rate (EER or CER): the rate at which both acceptance and rejection errors are equal. The value of the EER can be easily obtained from the ROC curve. The EER is a quick way to compare the accuracy of devices with different ROC curves. In general, the device with the lowest EER is the most accurate.

#Q7.

Unsure

#Q8.

referenced
http://en.wikipedia.org/wiki/Biometrics

1. the sensor picks up details
1. the gathered data is processed for clarification and cleaning
1. the raw data is translated into a template
1. biometric information is captured and stored
1. subsequent uses are detected and compared to the original

#Q9.

a.

- can repeat use key/ large key space
- can reuse the same metric without isolation
- is a one way transformation

b. 

- the system should have a very high false acceptance rate (ie it is more likely to fail even if you are correct)
- the system should have a very low false rejection rate (ie it should less likely to if you are incorrect)

- In the first case the auth can be verified by another means 
- for the second case it very likely to allow someone to enter who is mallious

c. 

http://link.springer.com/referenceworkentry/10.1007%2F978-0-387-73003-5_478

>Security attacks based on generating artificial data, injecting it in the system and after analyzing the output, modify such data, as to improve the output. This is done recursively till the output is the desired result. In biometrics this attack can be used to generate a synthetic sample, by analyzing the matching score returned by the system.

#Q10.

a. 

- listening and recording other people conversions
- falsely representing a scene for scams

b.

- uptime
	- how do you ensure that the device is running all the time with no down time
	- how you do know the device is not interfeared with
- integity
	- how you do ensure that the device did not have data inserted by an external source

c.

- confidentality
	- you need to confident that that data is secure and stored as ciphertext until it needs to be accessed
- integrity
	- the data must not be able to be altered or misrepsented
- authentication
	- the device should be only be able to be used by you and the 'authorities'
- anonymity
	- this will not exist in this system, you are trying to identify people
- traceabilty
	- this is a feature of the system
- privacy
	- the data is only accessable by you and the authorities
- denialabilty
	- you should not be able to denial the data
- non-repudiably
	- this is the feature of the system
- accountabilty
	- this is a feature of the system
- freshness
	- the device should always be recording.