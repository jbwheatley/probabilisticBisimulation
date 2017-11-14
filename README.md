# probabilisticBisimulation
In the field of verification, model checking is a technique used to decide the correctness
of systems via a mathematical model, usually a transition system. We
will be studying systems that exhibits stochastic behaviour, and hence our focus is
on probabilistic model checking. In practice, it can be computationally intractable
to use probabilistic model checking algorithms when the state space of the model
is very large. In this case, we can use approximate probabilistic bisimulations
(APBs) to further abstract this model and reduce the state space, while preserving
a robust class of properties of the original model. The class of properties that
are preserved depends on the approximation error of the abstraction, and it is
this error we wish to address.
In this project we propose a new abstraction for reducing the state space of
large, labelled Markov chains, that leverages the semantics of uncertain Markov
processes { in particular interval Markov decision processes { and the existing
notion of APBs. In doing so we produce a model that in general has reduced onestep
abstraction error when compared to a like-sized APB, and we give bounds
on the propagation of this error in time that also outperform similarly derived
error propagation bounds for the classical abstraction. We also outline existing
methods for performing model checking via this new approach, and show that the
computational complexity of this process is comparable to that for model checking
via APBs.
