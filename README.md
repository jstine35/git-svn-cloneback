# Requirements

 - BASH 4.1 or compatible shell

# Quick Installation

My curently recommended way to install this onto your system for running is to first ensure
you have the following path added to your `PATH` (in many cases, this will already exist):

> ~/bin

From there you can quickly and easily export these functions from this git repository into
your PATH:

```
$ git --remote=https://github.com/jstine35/git-svn-cloneback archive master | tar -x -C ~/bin
```

# Developer Installation

Clone this somewhere, and add that dir to your `PATH`

## Citations

I was originally inspired by [svn-utils](https://github.com/jonathancone/svn-utils)
by [Jonathan Cone](https://github.com/jonathancone), but I wanted something that didn't have
a dependency on Python.

At the same time I decided to upgrade to using BASH 4.x syntax, and also standardize some use
of terminology, such as using the term `--depth` instead of `--limit`
