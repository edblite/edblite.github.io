---
layout: post
title:  "Project goals"
categories: [announcements]
---
# In one sentence
EDBLite is an effort to bring easy to use encrypted files to Python applications, simplifying the difficulties that
developers face when securely storing data in their systems.

# The wishlist
- Multiformat: [KDB, KDBX](https://gist.github.com/lgg/e6ccc6e212d18dd2ecd8a8c116fb1e45),
[Veracrypt](https://www.veracrypt.fr/en/Technical%20Details.html).
- Pythonic interface:
    - Based on [io](https://docs.python.org/3/library/io.html#io-overview). 
    - As intuitive as using the [open](https://docs.python.org/3/library/functions.html#open) function.
    - And a [with statement](https://docs.python.org/3/reference/compound_stmts.html#the-with-statement).
- Test coverage of 85-90%.
- Peer reviewed: this is for now a one person project, but dealing with crypto is quite a delicate topic. 
It will require at least a review by another developer, in order to reach version 1.0.
- Full documentation for the API.

# Maybes
- Async API, using [asyncio](https://docs.python.org/3/library/asyncio.html).
- File formats based on cloud storage, like Amazon S3.
