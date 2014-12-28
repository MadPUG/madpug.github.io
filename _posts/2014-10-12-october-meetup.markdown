---
layout: post
title:  "October's Back-to-Back Talk Notes"
author: sigmavirus24
date:   2014-10-13 00:00:01
---

This month we had two members give presentations one after the other.

## A Bit of Appreciation

We found out the day of the meet up that the library's video cables had been 
stolen. Two members were able to bring their own so I'd like to especially 
thank Noah and Davi for bringing video cables.

## The Event

This month we had two people volunteer to give talks. They each had 30 minutes 
to present a topic.

## Using Python's two-way generators to run nondeterministic tree automata

First, Benet gave his talk. He had described it beforehand as:

> If I have trouble understanding something, my first instinct is to code it 
> up. So when I began reading about automata that read trees rather than 
> words, and had a hard time visualizing how that even works, I turned to the 
> Python REPL to see what I could figure out.
>
> PEP 342, implemented in Python 2.5, allows consumers of generators to not 
> only get values back while iterating over the generator, but to pass them 
> in. This seemed like a handy way to simulate runs of non-deterministic 
> automata, since it provides a channel for a consumer to resolve a 
> non-deterministic choice and proceed.
>
> This finally led me to the interesting exercise of writing a generator for 
> in-order tree traversal, becauseI could not find an iterative algorithm for 
> it in any of my algorithms textbooks.

Benet started the talk by giving us a brief review of Finite State Machines.  
He then used an abridged example of Python's Abstract Syntax Tree to show off 
the kind of trees he was interested in discussing. Next he described the 
bottom-up approach of applying a FSM to a tree. The simplest example he showed 
was a boolean expression tree. He then reviewed python's two-way generators.  
The talk finished with a review of Benet's iterator-based tree traversal 
function.


## A quick exploration of Modsplan

After Benet finished answering questions, Davi Post presented his project 
[Modsplan][modsplan], the Modular Specification of Programming Languages. 
Davi described how Modsplan was born from desire to play 
with languages via their specifications. The problem is that specifications 
are not always complete (or correct). Davi thought "What if a compiler could 
read a specification?" You could then test a compiler/specification against a 
reference implementation. What if languages that have common features could 
reuse pieces of specifications? Davi then proceeded to show off Modsplan's 
data flow and showed examples of the token, syntax, and definition 
sub-specifications. Each specification uses [Backus-Nauer Form (BNF)][BNF].

## Next Month

If [Django][Django] is your thing, we have a talk about integrating 
[Angular][angjs] with an existing Django project. We're also going to have a 
talk exploring some more advanced usage of [requests][requests]. So if web 
development or API consumption are your thing, be sure to join us.

[modsplan]: http://modsplan.com/
[BNF]: http://en.wikipedia.org/wiki/Backus%E2%80%93Naur_Form
[Django]: https://www.djangoproject.com/
[angjs]: https://angularjs.org/
[requests]: http://docs.python-requests.org/
