===========
System_type
===========

System_type
===========
The parameter is provides the program with a broad
overview of the type of system that will be simulated, and is used
by Python to initialize certain variable, and to control what variables
are asked for later.

**Type:** Enumerator

**Values:**

star
  System in which the central object is a star or WD

binary
  System with a secondary star, which can occult the central object and disk depending on phase

agn
  AGN or BH binary (currently)

previous
  In this case, one is starting from a previous run with python, and one want to either continue the
  run or change some parameters associated with radiation sources


**File:** python.c


