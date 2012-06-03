---
layout: post
title: "Smartdict introdution"
date: 2012-06-03 22:14
comments: true
categories:
---

Hello everyone. My name is [Sergey Potapov](http://github.com/greyblake), I am a
ruby developer and the creator/maintainer of Smartdict dictionary. In this post
I'm gonna tell you about the intention of Smartdict project and its main goals.


## History

I live in [Kharkov](http://en.wikipedia.org/wiki/Kharkiv)(Ukraine), so I am not
a native English speaker. Learning English a few years ago I've come up with
idea: I have to write every new English word down to memorize it latter, but
it would be really cool to automate the process. That has intended me to start
developing the software like Smartdict. I don't wanna learn all words in my
English textbook, I wanna learn words which I face in my daily practice.

Probably there already were some similar programs but I had some special requirements:

* It should be free and open source.
* It should be compatible to Unix like operation system, since I'm a Linux user.
* It should provide some core library, since I wanna use it within [Vim](http://www.vim.org/).
* It should be possible to fetch data from different sources like [GoldenDict](http://goldendict.org/) does.

I started developing. Sometimes I gave it up for a few months, then I came back.
In April 08, 2012 I released the very first version on [Github](https://github.com/smartdict/smartdict)
and [Rubygems](https://rubygems.org/gems/smartdict). It doesn't look like a lot
of people used it, but I got some feedback from my friends.

## Technologies

I've decided to use the next technologies to achieve my goals:

* Programming language: [ruby](http://www.ruby-lang.org)
* GUI: [GTK2](http://ruby-gnome2.sourceforge.jp), but it's possible to use another GUI libraries as well.
* Data storage: [SQLite](http://www.sqlite.org/) with [DataMapper](http://datamapper.org/) as an ORM.

I will write another blog post for developers where I'll dive deeper in internal
structure of the project and technologies.

## The current goals:

* Provide ability to track and learn translated words.
* Integration with [Anki](http://ankisrs.net/). That would be a really sweet thing!
* Create a Vim plugin based on [smartdict-core](https://github.com/smartdict/smartdict-core).

## Afterwords

I know it's a short introduction. More information will come soon.
There is a lot of work needs to be done. If you interesting in taking a part in
the development process please let me know, I'll appreciate your help!

Thanks.


P.S. Feel free to correct my English.
