[Assignment HOWTO]: https://github.com/hmc-cs111-fall2014/hmc-cs111-fall2014.github.io/wiki/Assignment-HOWTO
[Fowler]: https://sakai.claremont.edu/access/content/group/CX_mtg_80056/Fowler_Chapter2.pdf
[markdown]: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

# What _is_ a DSL?
###### _Submission deadline: Monday, Sept. 8 at 11:59pm_
###### _Critique deadline: Wednesday, Sept. 10 at noon_

In this assignment, you'll read an introductory chapter about DSLs, which will 
give us some shared terminology for talking about DSLs and their 
implementations. Then you'll find a DSL "in the wild" and describe its design 
and implementation using terminology from the reading. Finally, you'll write a
program in a cool DSL: ContextFree.

After this assignment, you should be able to:

- Recognize properties of a DSL, and evaluate those properties using common 
terms.
- Write in at least two DSLs (ContextFree and Markdown).
- Use GitHub as a submission system.

## Teamwork
For the technical part of the assignment, you'll work by yourself (though you're
free to talk about the assignment with anyone). For the critique part of the
assignment, you'll pick a partner and review each other's work.

## Read up on the assignment workflow
This [article][Assignment HOWTO] describes how we'll do our assignments on
GitHub. Be sure to read it before you start working on your assignment.

## Read Fowler's introduction to DSLs
Read [Fowler, Chapter 2][Fowler].<sup>1</sup> For the most part, this reading is 
self-contained. In a few places, Fowler references other parts of the book. 
Ignore these references; you can understand the reading without them. It may be 
helpful to know that, in Chapter 1, Fowler described a domain called Miss 
Grant's Controller. You can safely substitute the domain you choose for your DSL 
in place of Miss Grant's Controller. 

_<sup>1</sup> This copy of the reading is for class use only. You should not distribute
 it to anyone outside the class. You should destroy your digital copy when the 
 class is over._

## Find a DSL
Find a DSL---one that you think several other people in the class *won’t* know. 
When picking a DSL, it's good to find one for which you can find a few 
example programs, so you can get a good sense of it. Sometimes it's hard to be 
sure whether or not a language is actually a DSL. That's okay! If you find a 
language that you think *might* be a DSL, but you're not sure, then go with 
it---just assume that it *is* a DSL.

## Describe your DSL
Open the file `my-dsl.txt`, read the questions there, and edit the file to
include your answers to those questions. Back up your answers with any evidence 
that you can find about your DSL. Your answers must be formatted in [markdown].

_Note: there are many different kinds of markdown. If you already have a
favorite kind of markdown, feel free to use it. If you don't have a favorite,
you can use the same [markdown] that we use on the wiki._

## Learn, use, and critique ContextFree
1. Download ContextFree, a domain-specific language for making art. **You should
download version 2.2**, which is _not_ the current version of the language.
(download: [Windows](http://www.contextfreeart.org/download/ContextFreeInstall2.2.2.exe), 
[Mac](http://www.contextfreeart.org/download/ContextFree2.2.2.dmg),
[Linux](http://www.contextfreeart.org/download/ContextFreeSource2.2.2.tgz)).
_Note: the Mac version is also installed on the CS lab Macs._ The version 2.2
documentation is 
[here](http://contextfreeart.org/mediawiki/index.php/ Version_2_Syntax).

2. Write an interesting ContextFree program. Save your program in a file called
`firstname_lastname.cfdg` (where you fill in your first and last names, of
course).

3. Export a nice image from your program. (Choose the `Render` menu, then `Save
Image...`) Use a `.png` extension, so your filename should be `
firstname_lastname_variant.png` (where `variant` is the three-letter variant the
uniquely identifies this version of your program).

4. Answer the questions in `context-free.md`.

## Peer-review your partner's work
Once your partner has submitted, you can comment on their work. You should
provide feedback on all aspects of your partner's work, including the
information in `my-dsl.md`, `context-free.md`, their code, and their image. Here
are some questions you might consider / answer when providing feedback:

- Would you answer a question from the assignment differently than your partner
did? For example, do you agree with how your partner described the DSL-ness of
their language?
- Did your partner describe anything that you also experienced? For example, did
you try to do something in ContextFree that was difficult?
- If your partner has raised a question in `my-dsl.md` or `context-free.md`,
try to answer it!
- Did you learn any cool language features (from ContextFree or Markdown) that
might add to your partner's work?

## Tasks

- [ ] Identify a partner for the critique part of the assignment
- [X] Read the [Assignment HOWTO]
- [X] Read Fowler's [introduction to DSLs][Fowler]
- [X] Find a DSL
- [X] Describe your DSL's implementation and semantics in `my-dsl.md`
- [X] Write a ContextFree program in `firstname_lastname.cfdg`
- [X] Make and save a pretty picture in 
firstname_lastname_variant.png`
- [X] Answer the questions in `context-free.md`
- [ ] Submit your work
- [ ] Comment on your partner's work
