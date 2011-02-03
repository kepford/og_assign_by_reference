$Id$

README.txt for og_assign_by_reference
-------------------------------------

Q: Why do you need this module?

A: You need this module if you want users to be able to post new nodes into Organic
Groups that they don't belong to.

This module provides a configurable action that can be used on a new node to place
it into one or more organic groups.

The action takes the values of a nodereference field (or fields) that is configured
to reference organic groups, and assigns the node into those groups.

The action works well when configured to run "after saving a new post." 
