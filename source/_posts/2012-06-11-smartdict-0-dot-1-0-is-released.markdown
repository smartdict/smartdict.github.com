---
layout: post
title: "Smartdict 0.1.0 is released"
date: 2012-06-11 02:30
comments: true
categories:
---

I'm glad to announce Smartdict version 0.1.0 is released!
There are number of improvements:

* Automatic language detection based on alphabetic. (E.g. you are using
English-Russian translation, it detects either Russian or English word is written)
* [LingvoYandex driver](http://lingvo.yandex.ru/ruby/%D1%81%20%D0%B0%D0%BD%D0%B3%D0%BB%D0%B8%D0%B9%D1%81%D0%BA%D0%BE%D0%B3%D0%BE/)
for English-Russian translations. You can configure drivers in file `~/.smartdict/configuration.yml` in `drivers` section.
* Fixed number of GUI bugs.

## Installation

```bash
gem install smartdict
```

## Backward compatibility note

The DB schema was changed. If you've used Smartdict before please
remove `~/.smartdict` directory to make it regenerate DB schema
and configuration file.


## Screenshots

### Smartdict GUI
To run the application use `smartdict-gtk` command.
![Smartdict](http://i1078.photobucket.com/albums/w484/greyblake/-Smartdict.png)


### Smartdict CLI
To use command line version it's enough to have `smartdict-core` gem installed.
![Smartdict](http://i1078.photobucket.com/albums/w484/greyblake/smartdict-cli-010.png)
