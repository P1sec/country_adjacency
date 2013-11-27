Country adjacency dataset
=========================

Author: Omar Awile (omar@p1sec.com)
Date:   27.11.2013

JSON formatted datasets of country neighborhoods (country adjancencies).

The dataset was created from the Correlates of War datasets:

Correlates of War Project. Direct Contiguity Data, 1816-2006. Version 3.1.
Online: http://correlatesofwar.org.

This dataset depicts the last recorded state from CoW (December 2006) of country
neighborhood. Countries are considered neighbors if they are separated by a land
or river border or up to 24 miles of water.

This dataset comes in two flavors:
- Abbreviated country names following the abbreviations on:
  http://www.correlatesofwar.org/COW%20State%20list.xls
- Full country names

The data is formatted as follows:

{"CountryA" : ["CountryB", ..., "CountryN"], ...}

Finally, if CountryB is element of CountryA's neighbor list, then CountryA is
element of CountryB's neighbor list.

Feedback and Questions to:
- Omar Awile (omar@p1sec.com)
- Philippe Langlois (phil@p1sec.com)
