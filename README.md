# MxzCat
"Underthinking component design."

## What is a MxzCat?
A fundamental building block for Rabble's "MUSICatThulhu" rewrite of the MUSICat application.

### The name...
Ok. We needed a different name. CatThulhu is SO taken. “MCat” was too generic. “MsCat” probably violates some Microsoft patent. “MxCat” seemed cool but “mx” is a very populated place. “Mzcat” is camped by people whose online persona probably involves being a chick. 

So. Official name is MxzCat. Pronounced “**mix**cat”.

### The concept
A MxzCat is not very groundbreaking. It’s really a fairly old-fashioned idea, just implemented strictly. (Kind of along the lines of “Marxism has never been tried.”)

The core purpose of a MxzCat is _minimizing per-customer cost_, which most definitely includes ongoing cost of ownership.

The central point of the MxzCat model is _cost control via exaggerated simplicity._ This goal is played out like this:

We design a group of MxzCats, focusing on best balance between:
 - Maximum resilience in the face of expected problem space.
 - Minimal coupling at the MxzCat API.
 - Minimal external dependency.

There is one further design principle that makes the entire concept possible: Once written to its API, a MxzCat does not change.

Design is an art not a science, so we approach this with an appealing mix of delicacy and bigotry. We follow these guides:
 - 80/20 rule. (i.e., don’t waste time studying the unlikely cases.)
 - Redefine the problem simplewards. If a design decision is teetering between simple/less capable and complicated/more capable, leave the greater capability for some other time.
 - Do Not Compromise The Rules.
 - 
This will be **`design version 0.1`**. (Note that _we version the design specs, not the implementation._) Or rather, implementation versioning is an internal housekeeping thing.

We write simple reference implementations of the MxzCats. This will probably cause us to push to **`design version 0.2`**. So be it.

We use the reference implementations as design/functional templates to generate real implementations.

A MxzCat exists in several senses:
 - **A MxzCat is a datamodel.** The datamodel represents the meaningfully persistable state of the MxzCat.
 - **A MxzCat is an API.** A _versioned_ API. The API is the only way to communicate with a MxzCat.
 - **A MxzCat is a semantics attachment map.** This map is an unambiguous designator of the datamodel components, mapped to a defined set of top-level Semantic tags.
 - **A MxzCat is an instantiated part of a running application.** The component is implementation-agnostic: it can be created in any context, in any language, on any platform, as long as the basic behavioral contract is obeyed.
