# Introduction

This is an exploratory module to test the feasibility of developing a music theory library within
javascript / node. While I am not an expert in node, it seems like this approach might be closer to
a shippable app, because rendering / UI will be taken care of by a browser. This probably also
allows for packaging as a progressive web app or some other thing that I don't know much about.

In any case, I'm particularly interested in [vextab](https://github.com/0xfe/vextab) which is
under development by my colleague [Mohit Muthanna Cheppudira](https://twitter.com/11111110b).

In particular, this module seems to offer most of what [we](https://www.instagram.com/mista_rick/)
need to build our dream app.

# How does node app development work?

I guess you `npm install` dependencies, then a frozen file is generated that makes sure your
dependencies are always 'up to date'. Kinda cool - like an automatic python virtual environment.

Because I'm a total n00b at web developement and javascript, I'm gonna use this as a bit of a mini
blog.

So, I guess there is this concept called "Express" which is desireable for building apps - I'm
loosely following this setup here.

* [Mozilla's step by step guide](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/development_environment)

