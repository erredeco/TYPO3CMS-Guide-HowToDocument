
.. include:: ../Includes.txt


.. highlight:: rst

.. _styled-numbered-lists:

=====================
Styled Numbered Lists
=====================

**On this page:**

.. rst-class:: compact-list

.. contents::
   :local:
   :backlinks: top


.. _styled_numbered-lists-normal:

Normally styled
===============

*Source:* ::

   #. abc
   #. bcd
   #. cde


*How it looks*

#. abc
#. bcd
#. cde



With XXL big numbers
====================

*Source:* ::

   rst-class:: bignums-xxl

   1. One one one bignums-xxl

      Lots of stories here ...

      ...


*How it looks:*


.. rst-class:: bignums-xxl

1. ONE One one bignums-xxl

   Lots of stories here ...

2. TWO Two two

   Lots of stories here ...


3. THREE Three three

   * Well, here we are again, old lovely...
   * You may now serve the fish.
   * Fish. Very good, Miss Sophie. Did you enjoy the soup?




With big numbers
================

*Source:* ::

   .. rst-class:: bignums

   1. ONE One one

      Delicious, James


*How it looks:*

.. rst-class:: bignums

1. ONE One one

   Delicious, James.

   Thank you, Miss Sophie, glad you enjoyed it.
   Little bit of North Sea haddock, Miss Sophie.

   I think we'll have white wine with the fish.

2. TWO Two two

   More ...

3. THREE Three three

   More ...



With big numbers - tip
======================

Uses the same color as background, that is used in a tip textblock.

*Source:* ::

   .. rst-class:: bignums-tip

   1. ONE One one bignums-tip

      More ...


*How it looks:*

.. rst-class:: bignums-tip

1. ONE One one bignums-tip

   More ...

2. TWO Two two

   More ...

3. THREE Three three

   More ...


With big numbers - attention
=============================


*Source:* ::

   .. rst-class:: bignums-attention

   1. ONE One one bignums-attention

      More ...


*How it looks:*


.. rst-class:: bignums-attention

1. ONE One one bignums-attention

   More ...

2. TWO Two two

   More ...

3. THREE Three three

   More ...



With big numbers - important
============================


*Source:* ::

   .. rst-class:: bignums-important

   1. ONE One one bignums-important

      More ...


*How it looks:*

.. rst-class:: bignums-important

1. ONE One one bignums-important

   More ...

2. TWO Two two

   More ...

3. THREE Three three

   More ...



With big numbers - warning
==========================

*Source:* ::

   .. rst-class:: bignums-warning

   1. ONE One one bignums-warning

      More ...


*How it looks:*


.. rst-class:: bignums-warning

1. ONE One one bignums-warning

   More ...

2. TWO Two two

   More ...

3. THREE Three three

   More ...



Nested bignums-xxl > bignums > normally styled
==============================================


*Source:* ::

.. rst-class:: bignums-xxl

   1. ONE One one bignums-xxl

      This is the story of my life ...

      .. rst-class:: bignums

      1. When I was young

         #. this
         #. and that
         #. and this


*How it looks:*

.. rst-class:: bignums-xxl

1. ONE One one bignums-xxl

   This is the story of my life ...

   .. rst-class:: bignums

   1. When I was young

      #. this
      #. and that
      #. and this

   2. When I was grown

      Oops, ...


   3. When I was old

      Oh dear, ...



More examples of nesting
========================

.. highlight:: shell

.. rst-class:: bignums-xxl

1. Prepare

   .. rst-class:: bignums-important

   #. Check the requirements

      #. Machine accessible?
      #. Is `abc` installed? Run::

            which abc

      #. Is `bcd` available?

   #. Get yourself a coffee

   #. Stop everything else!


2. Install

   Now the actual stuff.

   .. rst-class:: bignums

   #. Abc

      #. Download from ...
      #. unpack
      #. run installer

   #. Bcd

      #. Download from ...
      #. unpack
      #. run installer

   #. Cde

      #. Download from ...
      #. unpack
      #. run installer


3. Cleanup

   **BEWARE:**

   .. rst-class:: bignums-warning

   #. Do not xxx!
   #. Do not yyy!
   #. Do not zzz!


4. Be a happy user!

   .. rst-class:: bignums-tip

   #. Run the stuff all day
   #. Run the stuff all night
   #. Never ever stop again
