<img src="./imgs/Greetings.png"/>

# Interesting Procedural Generation resources...
>In computing, procedural generation is a method of creating data algorithmically as opposed to manually, typically through a combination of human-generated assets and algorithms coupled with computer-generated randomness and processing power.
> - [Wikipedia : Procedural Generation](https://en.wikipedia.org/wiki/Procedural_generation)


## What IS Proc Gen?
### In Simple Terms, ProcGen -> Procedural Generation
A Process for **Creation** of Content
- Uses **curated rules** or building blocks
- Plus usually a Sprinkle of **Randomization**
- An **an Engine** to make sense of it all.
  
.. it's usually code that uses small bits of content legos, put together in random ways to create *dynamic* content that can cover a wide range of possibilities in place of *static* content.

### Some of my Favorite Things that Use ProcGen
| Thing  | Details |
| ------------- | ------------- |
| [Dwarf Fortress](http://www.bay12games.com/dwarves/) | The deepest, most intricate simulation of a world that's ever been created.  |
| [Art Toy](https://www.gdcvault.com/play/1024213/Practical-Procedural-Generation-for) | A beautiful animated flower generator, that relies on an array of ints as 'genes'. |
| [Cave of Qud](http://www.cavesofqud.com/) | Is a science fantasy RPG & roguelike epic. It's set in a far future that's deeply simulated, richly cultured, and rife with sentient plants. |
| [Spore](https://www.spore.com/) | Spore is a 2008 life simulation real-time strategy God game developed by Maxis, published by Electronic Arts and designed by Will Wright. |
| [Nested](http://orteil.dashnet.org/nested) | A universe simulator. |

### But Proc Gen is not **JUST** for games.
> If you can define it. You can generate it.
- [Procedurally Generated Beethoven](https://www.youtube.com/watch?v=esRdmKYucIw&feature=youtu.be)
- [SkyKnit - Procedurally Generated Knitting](https://aiweirdness.com/post/173096796277/skyknit-when-knitters-teamed-up-with-a-neural)
- [Procedural Generated Terrain](http://www.mit.edu/~jessicav/6.S198/Blog_Post/ProceduralGeneration.html)

.... the problem is in the _defining_.

### The Two Biggest Issues - SCOPE and OATMEAL!

**SCOPE - The Problem**
> You've decided to SIMULATE THE WORLD!
```
Everything's so big!
And all the details so intricate.
And there's SO many edge cases!
I could be defining things FOREVER
```
**SCOPE - The Solution**
```
START SMALL!
Small parts.
Small pieces.
Small timeline!
```

**[OATMEAL](https://galaxykate0.tumblr.com/post/139774965871/so-you-want-to-build-a-generator) - The Problem**
> You've got everything down to the smallest oat able to be generated in infinite detail!
```
There's lots of detail!
And SO much variation!
... but very little observable difference.
... and thus ultimately little impact.
```
**OATMEAL - The Solution**
```
FAIL FAST!
Try it.
Tweak it.
Expand it!
```

>  ... basically this should sound a lot like writing most software. Find your MVP and iterate iterate iterate!

## [Tracery](http://tracery.io/)
> One of my Favorite Proc Gen Tools; 
### The Basics
> An author-focused, curated, simple text generation tool by [Kate Compton](https://twitter.com/galaxykate)
- [Originally Written in Javascript](https://github.com/galaxykate/tracery) (but 'ported to many others!)
- Requires a JSON structured Grammar
- Expands rules to generate text...
- ... but remember, html is ultimately just a special text!
### What does it mean to make an ‘author-focused’ generative text tool? 
> We consider the potential authors for such a generative tool to be creative persons who
are interested in the expressivity of language and the aesthetics of prose. They
may not self-identify as ‘programmers’ or want to write code, but they want
to create generative text that is algorithmically combinatorial and surprising,
while still seeing their authorial ‘voice’ in the finished text.
> - [Tracery : An Author Focused Generative Text Tool](http://www.galaxykate.com/pdfs/ComptonKybartasMateas15-Tracery%20An%20Author-Focused%20Generative%20Text%20Tool.pdf)
