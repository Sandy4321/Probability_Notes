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

- Fails when we try to compute the probability of an event from among an incountably infinite sample space. Evaluated probability of each outcome becomes zero when divided by the infinite posibilities of outcomes. 
- This can be overcome by assigning a probability density to each outcome and multiplying it with the event whose probability is to be evaluated.
- A similar problem occurs when trying to evaluate the probability of a H or T in a sample space of infinite trials. In this case, we calculate the probability through n trials and then evaluate for the infinite case by taking its limit to 0.

Before defining the axioms lets quickly go through some standard notations of set theory.

**Sample space, $\Omega$** - Set of all sample points for the given experiment.

**Events** - Subsets of the Sample space

**Union of Sets, $\cup_{i=1}^n A_i$** - Consists of all points that exist in **any** of $A_1$, $A_2$...$A_n$.

**Intersection of Sets, $\cap_{i=1}^n A_i$** - Consists of all points that exist in **all** of $A_1$, $A_2$... $A_n$.

###Axioms of Probability theory

Russian Mathematician, A.N.Kolmogorov put probability theory on a firm mathematical footing in 1932 with his *Axioms of probability theory*.


Probability models have 3 components: 

- A **sample space Ω**, which is an arbitrary set of sample points; 

- A collection of **events**, each of which is a subset of $\Omega$; 
- and a **probability measure**, which assigns a probability (a number in [0, 1]) to each event. 

####The Collection of events satisfies the following axioms:

- $\Omega$ is an event

- If $A_1$,$A_2$,... are events, then 􏰂complement $A^c$ is an event.
- If all sample points are singleton events, then all finite and countable sets are events (i.e., they are finite and countable unions of singleton sets).
- From **deMorgan’s law**,􏰆􏰄 $$ [\cup_n A^n]^c = \cap_n A_n^c $$so countable intersections of events are events. 
- All combinations of intersections and unions of events are also events.


###The probability measure on events satisfies the following axioms:- $Pr \{\Omega\} = 1$

- If A is an event, then $ Pr \{A\} \geq 0$.
- If $A_1$,$A_2$,... are disjoint events, then $$Pr \big\{\bigcup_{n=1}^n A_n \big\} = \sum_{n=1}^n Pr \big\{A_n\big\} = \lim_{m \rightarrow \infty} \sum_{n=1}^m  Pr \big\{ A_n \big\}  $$

####Consequences of the above axioms
- $Pr \{\phi\} = 0$

- $Pr \{A^c\} = 1 - Pr \{A\}$
- $Pr\{A\} \leq Pr \{B\} \leq 1$, if $A \subseteq B$
- $Pr \big\{\bigcup_{n} A_n \big\} \leq \sum_n Pr \big\{A_n \big\}$ 

where the last point can be enunciated with the example of $$Pr \{ A \cup B \} = Pr \{ A \} + Pr \{ B \} - Pr\{ A \cap B\} \leq Pr \{ A \} + Pr \{ B\}$$