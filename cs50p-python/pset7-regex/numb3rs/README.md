# [NUMB3RS](https://cs50.harvard.edu/python/2022/psets/7/numb3rs/#numb3rs)

In Season 5, Episode 23 of  [NUMB3RS](https://en.wikipedia.org/wiki/Numbers_(TV_series)), a supposed  [IP address](https://en.wikipedia.org/wiki/IP_address)  appears on screen,  `275.3.6.28`, which isn’t actually a valid  [IPv4](https://en.wikipedia.org/wiki/IPv4)  (or  [IPv6](https://en.wikipedia.org/wiki/IPv6)) address.

An IPv4 address is a numeric identifier that a device (or, on TV, hacker) uses to communicate on the internet, akin to a postal address in the real world, typically formatted in  [dot-decimal notation](https://en.wikipedia.org/wiki/Dot-decimal_notation)  as  `#.#.#.#`. But each  `#`  should be a number between  `0`  and  `255`, inclusive. Suffice it to say  `275`  is not in that range! If only NUMB3RS had validated the address in that scene!

In a file called  `numb3rs.py`, implement a function called  `validate`  that expects an IPv4 address as input as a  `str`  and then returns  `True`  or  `False`, respectively, if that input is a valid IPv4 address or not.

Either before or after you implement `validate` in `numb3rs.py`, additionally implement, in a file called `test_numb3rs.py`, **two or more** functions that collectively test your implementation of `validate` thoroughly, each of whose names should begin with `test_` so that you can execute your tests with:
