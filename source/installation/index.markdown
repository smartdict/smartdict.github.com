---
layout: page
title: "installation"
date: 2012-06-11 03:37
comments: true
sharing: true
footer: true
---

## Installation

### Prerequisites


#### Debian/Ubuntu

On Debian/Ubuntu you need to install the next packages:

* libglib2.0-dev
* ligatk1.0-dev
* libcairo-dev
* libsqlite3-dev
* libpango1.0-dev

To do that run:

```
apt-get install libglib2.0-dev ligatk1.0-dev libcairo-dev libsqlite3-dev libpango1.0-dev
```

Please report if you have issues or it's not complete list of required dependencies.


### Ruby version

Tested on MRI 1.9.3-p125


### Install the gem

```
gem install smartdict
```


## Running

Command line:

```
smartdict --help
```

GUI:

```
smartdict-gtk
```


## Configuring / adding new languages

Take a look at `$HOME/.smartdict/configuration.yml`.
