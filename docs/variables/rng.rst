$(rng)
======

Resolve a random number between given numbers.

Usage:
    $(rng ``<min>`` ``<max>``)

Arguments:
    * ``min`` **<required>** - The minimum number that can be chosen
    * ``max`` **<required>** - The maximum number that can be chosen

Example Command:
    **name**: !roll

    **response**: You rolled a $(rng 1 100)

    **output**::

        user:     !roll
        botisimo: You rolled a 76
        user:     !roll
        botisimo: You rolled a 33
