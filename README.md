# Velcro
## A Bootstrap Re-Implementation Challenge

### Introduction

Ever wondered how Bootstrap works under the hood? Let's strip the engine out and replace it with our own makeshift one. Does anyone learn to be an auto mechanic that way? Does this metaphor quite work? No, it does not.

Without metaphor: we're going to learn more about how Bootstrap works by implementing our own version called Velcro. Our HTML uses Bootstrap classes for its layout--`row` and `container` and `col-sm-4` and `col-12` and so on--but there's no Bootstrap css. We're going to make the Velcro versions of those classes and thus make our own bespoke drop-in replacement for Bootstrap.

It's going to be so good that people will confuse your version and Twitter's version.

It'll be like this:

---

![Spiderman and Fake Spiderman Point at Each Other](https://media1.tenor.com/images/837072ca19e3c5cebea76e2693f3100d/tenor.gif?itemid=11796793)


### Guidelines

* You'll be working _exclusively_ in `velcro.css`, which lays out in comment form which classes you'll need to re-implement. Don't touch the html, or even `style.css`.

* We've talked about how Bootstrap works under the hood, and we've even peeked at Bootstrap's code together (and perhaps you have individually as well). But no more peeking. You've got this!

* But one more note along those lines: Bootstrap uses Flexbox under the hood. Although there are certainly other ways to implement it, and you're welcome to explore them, Bootstrap switched to implementing their grid layout using Flexbox for good reason. It's definitely your path of least resistence here.

* Although there's work you could do on the margins and spacing, your focus should be on making the columns take up the correct (or correct-like) spacing at the  given layouts. Work on spacing out rows and columns only _after_ nailing the basic layouts of all three possible viewport sizes.

* Don't forget to check [Bootstrap's breakpoints](https://getbootstrap.com/docs/4.3/layout/overview/#responsive-breakpoints).

* Although you can probably figure out how these classes work from your Bootstrap experience, [this is how the result should look](http://velcro-goal.surge.sh/).