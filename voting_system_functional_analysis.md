It had occurred to me while working on [RFC 150](https://github.com/polkadot-fellows/RFCs/pull/150) and [RFC 151](https://github.com/polkadot-fellows/RFCs/pull/151) that there are several properties of our voting system ([read OpenGov](https://polkadot.subsquare.io/referenda)) which are vast improvements upon current analog deployments. I have not yet seen these discussed or promulgated, and thought the community may enjoy pondering on them. There is no action item, simply meant to be an appreciation of the elegant and powerful system we have built.

### Arbitrary Closeness of Approximation
In OpenGov, one can either vote directly or delegate their vote. For instance, if I do not enjoy keeping up with policy, it may be worth it for me to delegate, even if that delegate only represents me accurately 85% of the time. Whereas if that remaining 15% matters greatly to me, I can always just vote directly. This guarantees our voters an arbitrary closeness of approximation to their true political will. From 0% accuracy, I don't care at all, to 100%, I'd never let anyone vote for me.

In arenas where this is not the case, i.e. static republics, we see large psychological frictions induced by the system not being able to self organize this way. People are stuck picking representatives that may poorly approximate them, and the citizens begin to feel a separation from their State. There's me, and there's the government, we are not a cohesive entity. Removing this pain point not only frees us from that friction, but increases citizen involvement.

### Balancing Between Accuracy and Energy Use
Due to overlap among voters, there is a nonlinear relationship between the fidelity of representation and the actual energy expended to achieve it. To illustrate, let's say that Bob delegates to Alice, who represents him with 80% accuracy. The voting system now approximates their ground truth preferences with 90% fidelity, 100% for Alice and 80% for Bob. However, the energy expended to achieve this is now only 1/2, as Bob no longer needs expend his metabolic energy on this task - A 50% reduction in energy usage for a 10% reduction in accuracy.

It is well known that [energy is limited](https://ourworldindata.org/electricity-mix), so a system that allows for this accuracy - energy tradeoff would be difficult to over appreciate. Moreover, because each voter can at any moment decide to vote or delegate, OpenGov allows for a continuous reorganization of this tradeoff, expending more or less energy to suit our current needs.

### Parameterizations of Power
Additionally, because a delegated democracy can reparameterize itself continuously, we get a highly adaptive organization of power. We tend to view the delegated democracy as soundly in the democracy camp, but if we were to all delegate to one person, it would effectively parameterize itself as a dictatorship... And this is good! There is both intuition for, and empirical precedent set for consolidated power being effective in select situations. Unsurprisingly, we've seen attempts at allowing governments to reparameterize like this in the past, i.e. Rome and its [wartime dictators](https://en.wikipedia.org/wiki/Roman_dictator).

Polkadot again organizes itself towards whichever concentration of power is necessary for the times, ensuring we're always moving at the speed, and with the cohesion, that the community deems necessary for survival.

### Scale
But perhaps most important is that we can now do all this at a global scale. It is not impossible to achieve all the aforementioned properties using analog counterparts. It is, however, infeasible to scale the logistics of them beyond a small population size. Polkadot's biggest achievement is unlocking these properties, for the first time, at a global level for a single community.

I hope you have found something in here you haven't previously considered. We've really built something glorious!