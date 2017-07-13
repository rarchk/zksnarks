Introduction 
===

1. Alice and Bob are two parties and want to do a transaction like adding two numbers, where one number is held by Alice and another by Bob.
2. Both Alice and Bob does not trust each other, and hence do not want to reveal their inputs to each other directly. 
3. Traditionally, Alice and Bob can ask their common friend Max, whom they both trust, to take in their values and compute the result for them. 
4. But Alice and Bob just took `Principles of Information Security` in their undergrad, and want to solve this problem differently. 
5. They researched and knew about the existence of Zero Knowledge Proof, where without revealing their own inputs, Alice and Bob both can get such results. 
	- A proof S for language L has a property that 
		- soundness 
		- completeness 
		- hiding
	- furthermore the proof should be such that it could be efficiently computed
6. Alice and Bob tosses a coin, and Alice becomes prover and Bob becomes verifier. It means that Bob will give his input to Alice in such a way that Alice does not know what input is, and in return Alice must give right answer to Bob, after computing it. 
7. Clearly, if it is only just adding two numbers, Alice can deduce the input of Bob, if he also comes to know the result. 
8. Bob wants two gurantees 
	- The computation done by Alice is right 
	- The computation done by Alice involves use of correct inputs, not some cooked up inputs by Alice. (fairness of protocol)


## Addendum 
- Proofs vs Proofs of knowledge  (Statements about facts and Statements of personal knowledge)
- Schnorr identification protocol 
	- alice has a public key, but how do she proves to the world that she knows private key of that public key 
	- if you run two run of protocol with same k, then secret could be revealed 
	- ECDSA/DSA signatures 
	- If extractor exists, schnorr identification can be broken 

- Commitment 
something that both hides a digital value, while simultaneously ‘binding’ (or ‘committing’) the maker to it, so she can’t change her mind after the fact.

- You simply find a statement (in NP) that you wish to prove, such as our hash function example from above, then translate it into an instance of the 3-coloring problem.
- simulator attack 
- 

## Application
- zero-knowledge login systems 
- 

## References
1. **Matthew Green's blog on ZKP** [1](https://blog.cryptographyengineering.com/2014/11/27/zero-knowledge-proofs-illustrated-primer/) [2](https://blog.cryptographyengineering.com/2017/01/21/zero-knowledge-proofs-an-illustrated-primer-part-2/)	