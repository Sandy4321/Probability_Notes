##Important Definitions

- The core concept in probability theory is that of a *probability model.*  
- The first component of a probability model is a *sample space*, which is a set whose elements are called outcomes or *sample points*. 
- The second component of a probability model is a *class of events*, which can be considered for now simply as the class of all subsets of the sample space. 
- The third component is a *probability measure*, which can be regarded for now as the assignment of a non-negative number to each outcome, with the restriction that these numbers must sum to one over the sample space. 

###Difference between Outcome and Event

An **outcome** or **sample point** in a probability model corresponds to a complete result (with all detail specified) of the experiment being modeled. 

- For example, a game of cards is often appropriately modeled by the arrangement of cards within a shuffled 52 card deck, thus giving rise to a set of 52! outcomes.
- A poker hand with 4 aces is an event rather than an outcome in this model, since many arrangements of the cards can give rise to 4 aces in a given hand. 

The possible **outcomes** in a probability model (and in the experiment being modeled) are mutually exclusive and collectively constitute the entire sample space (space of possible results). 

- An outcome is often called a finest grain result of the model in the sense that an outcome $\omega$ contains no subsets other than the empty set and the singleton subset {$\omega$}. 

Thus **events** typically give only partial information about the result of the experiment, whereas an **outcome** fully specifies the result.

###Assigning probabilities for finite sample spaces

- For starters, something virtu­ally impossible should be assigned a probability close to 0 and something virtually certain should be assigned a probability close to 1.

- Between virtual impossibility and certainty, if one outcome appears to be closer to certainty than another, its probability should be correspondingly greater. 

**Using Symmentry**

Symmetry can often provide a better rationale for choosing probabilities. For example, the symmetry between H and T for a coin, or the symmetry between the the six faces of a die, motivates assigning equal probabilities, 1/2 each for H and T and 1/6 each for the six faces of a die. 

- This is reasonable and extremely useful, but there is no completely convincing reason for choosing probabilities based on symmetry.

**Using Relative frequency of outcomes**

Another approach is to perform the experiment many times and choose the probability of each outcome as the relative frequency of that outcome (i.e., the number of occurrences of that outcome divided by the total number of trials). Experience shows that the relative frequency of an outcome often approaches a limiting value with an increasing number of trials. 

###Axioms of Probability theory

