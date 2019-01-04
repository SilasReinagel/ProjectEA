
----

# Chapter 1 - Elegant Architecture

----

## The Winchester Mystery House

I grew up in the California Bay Area, as my father worked in Silicon Valley. Just to the south of Silicon Valley, there is a famous mansion, the Winchester Mystery House. 

The Winchester Mystery House is an architectural marvel! It is a gorgeous house, which is immactulately maintained. At first glance, from the outside, it appears to be a fairly normal, if colorful, mansion. Yet, a few peculiarities immediately jump out to a more discerning eye. Each window has a different shape and style and no two curtains are quite the same. When you tour the mansion, you quickly discover that the inside architecture is even more wild and peculiar than the outside. 

//TODO: [insert image here]

There are staircases leading to nowhere. There are doors build into walls, which are suspended above the floor. There are banisters at unusual places. Archways lean against the vaulted roof in the attic. Artwork is intentionally hung at very odd angles along some walls. Sometimes there is a window placed on the inside of a wall, with no view to the outside. There are wild, winding corridors, which make traversing it's floors quite the adventure.

//TODO: [insert image here]

The strangest thing about the Winchester Mystery House is that all of this design is intentionally, and structurally sound. The design of the house primarily originated in the mind of its designer, Sarah Winchester. The house is well taken care of, and people visit from all over just to see it. Yet, it's a very whimsical house. Most of its features are not designed for practical function. Much of it is different simply because of the superstitious desire to confuse ghosts and to alleviates curses.

----

## The General Software Landscape

In today's software landscape, there are a great many systems which share many properties with the Winchester Mystery House. They are incrementally developed, shaped very oddly, hard to navigate, difficult to understand, yet their designers have all-too-clear stories on precisely how their systems ended up in the shapes their present shapes. These systems are costly, hard to maintain, and impossible to reuse. They are, in a word, inelegant.

If the goal of writing software is simply to make money or to create artificial job security, then elegance is not the goal. Inelegance creates necessity. Inelegance creates a need for future effort and work. 

However, if you are a creator and a craftsman, then you take pride in your software creations. Your goal is to create something of quality that continues to deliver value long after your contributions. This book is my attempt to teach the timeless principles of Elegant Architecture that I have discovered in my years of creating software.

----

## The Seven Aspects Of Software Quality 

//TODO: Adapt these to be about Systems instead of about Software

**Reliability:** Software is reliable if it behaves consistently. The functionality of a program should be predictable and repeatable. Errors should occur rarely or not at all. Errors that do occur should be handled gracefully and proactively. Users should never ask themselves whether the software will work correctly.

**Understandability:** The structure, components, and source code must be understandable. They must be clear. They must be well-organized. They must behave the way a developer would expect. Anything in the code that causes developers confusion reveals that the code is lacking in understandability. High-quality source code always appears simple and obvious.

**Modifiability:** It should be easy to add or change the behavior of a system. Flexible systems require changing very few lines of code to alter a behavior. For the expected dimensions of change, an application should have plugin points that allow the application to be used with different contextual elements. Tight coupling to an element that is expected to change is absolutely unacceptable.

**Usability:** Software products must be simple and easy to use. The common use cases should be as obvious and clearly presented as possible. Software should not require excessive configuration. Users should feel empowered by your software. They should not need internet searches to discover core application functionality.

**Testability:** The functionality of software must be verifiable. The process of testing the software must be easy. Each business use case should be directly testable. Clear verification metrics must be available. Highly testable software will ship with a comprehensive automated test suite.

**Portability:** Portable software is usable in different environments and contexts. It is highly reusable. Portable software is decoupled from specific operating systems, types of hardware, and deployment contexts. Extremely portable software is reusable across projects and problem domains.

**Efficiency:** Efficient software uses as few physical resources as possible. It is fast. It is memory-efficient. It consumes few CPU cycles. It uses little battery life. It makes few external service calls. It minimizes the number of database calls. Efficient software accomplishes as much as possible with the least amount of resources.

----

## Elegance

Merriam-Webster defines *Elegance* as:

1
  **a :** refined grace or dignified propriety
  **b :** tasteful richness of design or ornamentation the sumptuous elegance of the furnishings
  **c :** dignified gracefulness or restrained beauty of style 
  **d :** scientific precision, neatness, and simplicity 

My definition: 
"Elegant architecture is the shape of a system which is optimally designed to meet its present and ongoing functional and non-functional requirements."

In practice, an elegantly architected system is one which consists primarily of small, general purpose components, loosely coupled together with a clearly documented arrangement and simple, minimal configuration. 



