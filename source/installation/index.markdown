---
layout: page
title: "installation"
date: 2012-06-11 03:37
comments: true
sharing: true
footer: true
---

## Prerequisites


### Debian Squeeze (6.0)

```
apt-get install libglib2.0-dev libatk1.0-dev libcairo-dev libsqlite3-dev libpango1.0-dev libgtk2.0-dev
```

### Ubuntu 11.10

```
apt-get install libglib2.0-dev libatk1.0-dev libcairo-dev libsqlite3-dev libpango1.0-dev libgtk2.0-dev libgdk-pixbuf2.0
```

Please report if you have issues or it's not complete list of required dependencies.


## Ruby version

Tested on:

* MRI 1.8.7-p358
* MRI 1.9.2-p290
* MRI 1.9.3-p125


## Install the gem

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



## Copyright

Copyright (c) 2012 Potapov Sergey. The software is distributed under
[GNU GeneralPublic License version 2](http://www.gnu.org/licenses/gpl-2.0.txt).
See GPL-LICENSE.txt file for more details.
