# Exhibition

Say it right:

> /ɛgs'hɪb'ɪʃ(ə)n/

So something like:

>  eggs hib ish'n

## What?

A static site generator

## License?

GPLv3 or later. See LICENSE for the actual text.

## Why though?

I've been using Hyde since forever, but I wasn't happy with it. I was also very unhappy with other static site generators (SSGs) that used Jinja2 for their templating needs:

* Pelican and the like are too blog focused. It didn't feel in the spirit of
  those projects to have a blog and a recipe list as two separate sections to a
  website.
* Hyde is everything I want, except for the complete lack of documentation and
  a massive code base that needs a lot of work to make it run on Python 3. It
  is also currently unmaintained.
  * I should also mention that there are huge parts of Hyde that do nothing for
    me, so starting from scratch made more sense than dealing with Hyde.

There are SSGs that aren't written in Python or don't use Jinja2 for their
templates, but I'm not interested in rewritting all the templates for the sites
that I have made with Hyde.

## What's the status of this project?

I'm not using it for anything serious yet, there are no tests, and there are no docs.