# MxzCat (Pronounced "mix-cat")
"Underthinking component design."

## What is a MxzCat?
A MxzCat is a fundamental building block for [Rabble](http://www.musicat.co/the-rabble/)'s "MUSICatThulhu" rewrite of the MUSICat application. A MxzCat can be described as "making a LEGO™ out of a _useful data component_ whose _nature and purpose are (pretty much) fixed_."

In other words, 
 - We pull out the fundamental pieces of data and concept that MUSICat works with.
 - We make them into MxzCats: fixed, finished items with simple, well-understood behavior.
 - To build an application, we wire MxzCats together with code that governs the high-level behavior of the application.

### Why do this?
The core purpose of a MxzCat is _minimizing per-customer cost_, especially ongoing cost of ownership.

#### First: because it's feasible.
MUSICat involves a high proportion of data items that fit the description:
 - A "useful data component" is one that recurs, in whole, thoughout the application; and that has a small, tightly definable set of interactions. In other words, a block with formal and conceptual integrity.
 - A component whose "nature and purpose are (pretty much) fixed" is one that supports investment in a one-and-done style of programming.

#### Second: because it provides pivotal business benefit.
The central point of the MxzCat model is _cost control via exaggerated simplicity._ 

Most software is written without the benefit of the constraints of the MxzCat concept. Current software practice has evolved under pressure to tame the enormous complexity of fluid requirements and behavioral descriptions of arbitrary specificity. As a result, contemporary "full-stack development" is large, unwieldy, very expensive (particularly in terms of total cost of ownership), and failure-prone.

If you reject the principle that a purpose-appropriate set of LEGO™-style snappable software components can rein in the cost of software development... you should stop reading. Surely you have other things to do with your day.

Rabble, though: Rabble needs to contain per-customer cost as much as possible. This is partly for business-model reasons; but primarily it's a mission statement: Rabble works to contain costs for libraries themselves. 

MUSICat has evolved to the point at which it expresses a very well-suited set of core functions for its purpose. As such, it offers a very stable set of candidate component definitions.

Hence this project.

### The name...
Ok. We needed a different name. "CatThulhu" was SO taken. "MCat" was too generic. "MsCat" probably violates some Microsoft patent. "MxCat" seemed cool but "mx" is a very populated googlespace. "Mzcat" seems camped by people whose online persona is chick-centric; which is in itself fine, but which carries freight that this project doesn't. 

So. MxzCat. Pronounced "**mix**cat".

## The MxzCat Concept
A MxzCat is not very groundbreaking. It’s really a fairly old-fashioned idea, just seldom if ever implemented properly. (Kind of along the lines of "Marxism has never been tried.")

A MxzCat begins with a conceptual definition. From that, we derive **versioned** specifications. Implementation versioning, for a MxzCat-based application, is a mere housekeeping detail. The **specification version is the important thing**:

 - It defines whether any two MxzCats can snap together.
 - It is a potential parameter constraint for functions.

A MxzCat exists in several senses:
 - **A MxzCat is a datamodel.** The datamodel represents the meaningfully persistable state of the MxzCat.
 - **A MxzCat is an API.** The API is the only sanctioned way to communicate with a MxzCat.
 - **A MxzCat is a semantics attachment map.** This map is an unambiguous designator of the datamodel elements: much like XPath in an XML structure. These points may be mapped to any defined set of top-level Semantic tags.
 - **A MxzCat is an instantiated part of a running application.** The component is implementation-agnostic: it can be created in any context, in any language, on any platform, as long as the basic behavioral contract is obeyed.

Here are the parts of a MxzCat
###

