Scripts Tab
===========

Scripts are used to extend the workflow in various ways. Scripts can be
External Methods, Python Scripts, DTML methods, or any other callable Zope
object. They are accessible by name in expressions, eg::

  scripts/myScript

or::

  python:scripts.myScript(arg1, arg2...)

From transitions, as before and after scripts, they are invoked with a
'state_change' object as the first argument; see the Expressions section for
more details on the 'state_change' object.

Objects under the scripts are managed in the usual ZMI fashion.
