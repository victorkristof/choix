choix
=====

``choix`` is a Python library that provides inference algorithms for models based
on Luce's choice axiom. These probabilistic models can be used to explain and
predict outcomes of comparisons between items.

- **Pairwise comparisons**: when the data consists of comparisons between two
  items, the model variant is usually referred to as the *Bradley-Terry* model.
  It is closely related to the Elo rating system used to rank chess players.
- **Partial rankings**: when the data consists of rankings over (a subset of)
  the items, the model variant is usually referred to as the *Plackett-Luce*
  model.
- **Top-1 lists**: another variation of the model arises when the data consists
  of discrete choices, i.e., we observe the selection of one item out of a
  subset of items.
- **Choices in a network**: when the data consists of counts of the number of
  visits to each node in a network, the model is known as the *Network Choice
  Model*.

``choix`` makes it easy to infer model parameters from these different types of
data, using a variety of algorithms:

* Luce Spectral Ranking
* Minorization-Maximization
* Rank Centrality
* Approximate Bayesian inference with expectation propagation

An easy way to get started is by exploring the notebooks_!


Contents
--------

.. toctree::
   :maxdepth: 2

   installation
   data
   regularization
   api
   references


Indices and tables
------------------

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

.. _notebooks: https://github.com/lucasmaystre/choix/tree/master/notebooks
