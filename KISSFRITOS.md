## Going Beyond KISS

"Keep It Simple, Stupid!" is a rule of thumb long hailed for its utility in rebuking
overcomplicated plans or initiatives. However, as a guide to design, it lacks.

We propose here KISSFRITOS: "Keep It Small, Simple, Fast, & Resilient - In That Order - Stupid!"

This isn't simply an ironic joke. It's an extension of the traditional "KISS" meme into
the space of useful design concepts. It's a core guiding principle underlying MxzCat.

Let's break it down.

* **Small** is a wonderful way to write code. It's a way that almost nobody is ever
able to implement, because code is not generally terse; javascript, the nominal
language of MxzCat, being a mix of low-level and medium-level code, is pretty verbose.
A piece of code that is by intention small tends to grow to hundreds of lines in the
twinkling of an eye. But javascript cannot be blamed generically. The software industry
has for decades gone down the unproductive path of writing great big monolithic
edifices of code.

Small, however, is the only realistic way of making pieces of software that are
_simple_.

* **Simple** is the characteristic of separating code into parts that have discrete,
well-understood purposes or tasks; _and_ that have well-definied interfaces. This makes
it possible to reason about the code's behavior, and to use the code in a modular
way, without needing to dive deep into the implementation details.

Simplicity has lots of virtues (especially in cost/benefit ratio for the software
throughout its life), but one of the most significant advantages of simple code is
that it can be used to construct _fast_ applications.

* **Fast** is not something that is particularly discussed these days: Moore's
Law has made so much computing power so pervasively available that even obese
wheezing clunky applications twenty times their necessary size run fairly quickly.
Since running quickly is not as important (according to emergent conventions of
software development) as things like reduced developer time, the subtle effect
has been to make today's user increasingly accustomed to the behavior of obese
wheezing clunky applications twenty times their necessary size.

That said, a fast, snappy, responsive application is still going to impress users
and make them happy. And it remains a fact: monolithic, complicated applications
are very difficult to optimize for speed. (It's related to graph theory math: the
more interconnections there are, the harder it is to make changes that don't
spill out into the rest of the code. Simple isn't necessarily fast; but _simple
can be made to run fast_.)

* Small, Simple, and Fast are not very difficult concepts. **Resilience**, on
the other hand, is more subtle. The term encompasses multiple characteristics.

  - Resilient software, when it crashes, doesn't take unusual measures to bring
  back up.
  
  - Resilient software is not as likely to crash in the first place.
  
  - Resilient software is easier to repair when bugs appear.
  
  - Resilient software is less costly to modify when new requirements arise.
  
  - Resilient software is easier to move, to update, to redeploy without complication.
  
The meaning of "In That Order, Stupid" is left as an exercise for the reader.
