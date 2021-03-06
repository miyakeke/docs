---
layout: relation
title: 'aux'
shortdef: 'auxiliary'
# The filename "aux" is not allowed on Windows, so we redirect instead
# (see https://github.com/UniversalDependencies/docs/issues/20)
redirect_from: "fr/dep/aux.html"
udver: '2'
---

An auxiliary of a clause is a [non-main verb](u-pos/AUX) of the clause.

For the passive [voice](sv-feat/Voice), the relation is not labeled `aux` but [aux:pass]().

~~~ sdparse
On peut nager dans le lac \n One can swim in the lake
aux(nager, peut)
~~~

~~~ sdparse
Quelles conséquences cela a - t - il eu ? \n What consequences did this have ?
aux(eu, a)
~~~

The `aux` relation is also used in **UD_French-Spoken**:

~~~ sdparse
c'est l'esprit qui a peut-être changé \n it's the spirit that may have changed
aux(changé,a)
~~~

There is another subrelation used to annotate the causative constructions: the [aux:caus]() relation.

N.B.: Modals like _pouvoir_, _vouloir_ etc. are annotated with an `aux` relation in **UD_French-ParTUT**.
Other French treebanks do not consider them as auxiliary verbs.
