#Math procedures and heuristics

##Getting a handle on concepts and new mathematical objects

####Test understanding by generating specific examples

Everytime I read a new definition or concept, I should test my understanding on a very simple example (or maybe two examples?)


####Theorems take in conditions, and output conclusions

Lemmas and theorems should be thought about as from some set of conditions and to some set of conditions. Lemmas and theorems are like machines that can only take particular inputs, but output particular nice properties.
For instance the Linear Dependence lemma is a lemma from linear dependence. You need linear dependence as a prerequisite for it to work.


##General mathematical problem solving strategies

####When stuck, review the chapter
When I'm stuck trying to solve a p-set problem, go back and review the chapter

####Try some specific, simple, values

When looking at problem, you may want to play with small examples to formulate conjectures. Take the first few instances (or small instances, or easy instances, or simple instances) of the values in question and see how they play out, and come up with guesses about how they behave based on the first few examples.

####Reasoning via cases
You can sometimes divide up a large number of situations into a small number of discrete cases, and prove things about each case. 
For instance, a when an integer is divided by 3, the remainder will either be 0, 1, or 2. 

####Draw pictures

If a problem affords you an opportunity to draw a picture, you should draw the picture.

####Write down my approach

When I’m stuck it is useful to write down the approach that I’m trying (“isolate the y”, or “try filling in x with a specific value”), so that 1) I don’t get lost and forget what I’m doing and 2) so that I can see which tacts bear fruit.

####Write "what do I do now?"


###Proof strategies


| Proof strategy      				| Trigger                    |
| ----------- 						| -----------                |
|Simple algebraic manipulation	|
|Proof by induction      			|Anytime I need to prove a property of a "numberline set", the natural numbers, or the reals|
|Proving the contrapositive 		|When I am trying to prove an implication, and the antecedent of the implication is big and confusing|
|Reasoning via cases          	|I can identify a small number of discrete cases that are collectively exhaustive|
|Proof by contradiction (assume the conclusion and derive a contradiction)| |
| Find a counterexample				|I suspect the theorem is false|




####Proving by induction

Anytime I need to prove a property of a set of "numberline numbers", the natural numbers, or the reals, you should start with a proof by induction.

####Proving the contrapositive

When you are trying to prove an implication, and the antecedent of the implication is big and confusing, you are better off proving the contrapositive

Examples:

* Prove (cubed root(x) + 5) / (square_root(x) +6) = 1/x => x != 8
* Convert to x = 8 => (cubed root(x) + 5) / (square_root(x) +6) != 1/x


Specific TAPS

* When I need to prove and iff statement, I first have to prove one implication, and then prove the other one separately.
* When I have an implication, p => q to prove, I always have the choice of proving p => q directly, or proving the contrapositive, - q => - p. I need to examine p vs. - p, and q vs. - q, and determine which seems easier to work with.


##Specific mathematical moves

###Alegbra


####Distribute negatives to get them out of the way

I think I need to distribute negatives. I can’t really keep track of them in my head.


####Take a step that moves you closer to the conclusion

A move: try taking a step that moves you closer towards the conclusion (i.e. if a hypothesis is a > b, and you want to prove that a^2 > b^2, try multiplying both sides of the inequality by a or b.)

[Maybe this one goes in general problem solving strategies.]


####Get to 0 on one side

Heurisic: it is sometimes useful to transform an inequality so that one side of the inequality is 0, because that allows for doing multiplicative transformations that only change one side of inequality.

See [here](https://roamresearch.com/#/app/eli/page/HFImWTV5Z).

####Explore allowable moves

Do breadth first search on allowable moves from the starting position, and keeping an eye out for terms that are in common with the conclusion that you are attempting to prove.