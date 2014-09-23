MindMelder
==========

Syntax to draft contracts with terminal-style commands (think: "style_PromissoryNote" sticks a set of variables into a 
promissory note template).  This was initially presented by Jonathan Moore and Boris Polania ([bpolania](https://github.com/bpolania)) at [Code the Deal](http://codethedeal.com).  

We hope that our members and followers will more fully develop the ontology of the syntax, as well as develop some applications for the final product (how about a GUI?).  We think there are a number of applications for this syntax:

* The log of commands could serve as metadata for a document that could be read, or written, by humans (and machines) more quickly.
* Humans could write scripts that automate the creation of hundreds of documents in a few seconds, with little to no technical knowledge (or knowledge of MS Word's more automatable features).
* In some cases, it may be possible to hardcode and detect bugs and logical inconsistencies in contracts.  E.g., you could get an error message if you use an undefined term.
* Defining terms and cross-referencing terms and sections in a very easy way.

-----

About Mind Melder

Mind Melder is a rudimentary IDE and interpreter for a very basic scripting language (we called it LegalScript) based on concepts defined by Sergio de Cesare and Guido L. Geerts in their paper Toward a Perdurantist Ontology of Contracts (included in this repo). The basic idea is that companies can be defined as a bundle of contracts and that the relationships between companies and contracts can be abstracted into a discrete set of elements (objects).

Even though LegalScript was intended to be a prototype for the Code the Deal hack and in some parts (mostly the contracts paragraphs and meta-data) it’s hard-coded, it essentially confirmed some of Cesare and Geerts’ assumptions about the parts and relationships inside a contract. Nevertheless javascript proved to be not a good tool for text processing, so for any further advancements in the creation of a scripting language would be more effective if tools like flex and bison are used.

Finally, Mind Melder served mostly as a tool for showing  the idea to a public (i.e. hackathon judges and general public) but it’s our opinion that on the long term it could evolve to be an integrated IDE/SDK for LegalScript or something like it.
