# Implementation of Trees in C
AVL is currently in development.
It is planned to support all data types other than integer using a similar structure as the Abstract-Array project on my profile.
There is currently only support for the integer binary tree, offering functions to add and remove values from the tree and use a variety of other functions
to interact with it.

At the moment, tree.c contains all of the function content and make_tree.c tests them by arbitrarily picking random values and calling all of the functions on a tree holding those values.

Simply copy the repository and run "make" and you'll be able to run it yourself. Alternatively, you can incorporate this setup into a different repository by copying everything except make_tree.c and including tree.h in the program.
