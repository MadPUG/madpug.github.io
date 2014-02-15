---
layout: post
title:  "An Introduction to Scipy and Pandas"
date:   2014-02-15 19:59:59
---

At this month's [meetup][] [Oran Looney][olooney] gave an hour long 
presentation about [IPython][], [SciPy][], and [Pandas][]. After the meeting, 
One of the member's new to the group, William Blondeau, sent me an email with 
feedback.  With their permission, I'm posting a slightly edited group of 
excerpts from their email

**TL;DR** The Python scientific libraries are very powerful and easy to use. I 
expect we will be using this stuff more and more as we go forward. Python 
appears to be gaining ground as the go-to scientific computing solution.

The presenter, Oran Looney, is a Data Scientist with an academic background in 
physics modeling and visualization. He knows the problem domain 
professionally. The talk included wry allusions to the pain of dealing with 
weird heterogeneous data indicating he has first hand practical experience.

Overall it was a good talk for an audience that understands Python but is not 
familiar with the scientific side. The technologies are very mature and the 
scientific Python ecosystem is vigorous, as lucidly described in [Tal Yakoni's 
article][lunch].

The talk highlighted the following items:

- The [IPython][] interactive computing environment, which is an excellent fit 
  for cut-and-try scientific work

- The [SciPy][] library of open source scientific tools

- [pylab][], a user-friendly API package providing clean and straightforward 
  access to the SciPy goodness

- [NumPy][], the high-performance multidimensional array package with hefty 
  convenience support methods (linear algebra etc)

- [Pandas][], the Python Data Analysis Library

    - Specifically Pandas' [DataFrame API][dataframe]

- [MatPlotLib][], a powerful 2D plotting and visualization library

- [Anaconda][], a scientific-computing-cetnric package manager that, unlike 
  pip, is able to manage non-python packages too.

Thanks to Oran for a great presentation and Bill for this great set of notes!

[meetup]: http://www.meetup.com/MadPUG/events/160124632/
[olooney]: https://github.com/olooney
[IPython]: http://ipython.org
[SciPy]: http://www.scipy.org
[Pandas]: http://pandas.pydata.org/
[lunch]: http://www.talyarkoni.org/blog/2013/11/18/the-homogenization-of-scientific-computing-or-why-python-is-steadily-eating-other-languages-lunch/
[pylab]: http://wiki.scipy.org/PyLab
[NumPy]: http://www.numpy.org/
[MatPlotLib]: http://matplotlib.org/
[Anaconda]: http://continuum.io/downloads
[dataframe]: http://pandas.pydata.org/pandas-docs/stable/dsintro.html#dataframe
