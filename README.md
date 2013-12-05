This is a simple [conky](http://conky.sourceforge.net/) config tailored to
work on my ThinkPad x60, thus it would problably not work much if you are not
running the IBM ACPI module.

![Hell, yes!](http://i.imgur.com/z6WaAbx.png)
![Fucking awesome, right?](http://i.imgur.com/5QHzXGH.gif)

Features
--------
- An indicator for your ThinkLight™
- Battery status
- Volume and brightness controls
- CPU and Memory usage
- Disk usage
- Network usage
- Status aware icons
- CapsLk indicator

Things to add
-------------
- Disk usage in external drives / devices
- Services running on the machine
- An script to generate a conkyrc file based on user input?

Installation
------------
    git clone git@github.com:eskerda/thinky.git ~/.thinky
    cp ~/.thinky/fonts/*.ttf ~/.fonts
    conky -c ~/.thinky/conkyrc

FAQ
---
Q: Don't you think that polling all these scripts is a bit overkill?

A: If 'overkill' is a problem, you shouldn't be running conky anyway.

Credits
-------
- [OswaldFont](https://github.com/vernnobile/OswaldFont) by Vernon Adams
- The icons provided in the thinky-glyphs.ttf file are part of the
  following iconic fontsets:
    - [Font Awesome](http://fontawesome.io)
    - [Typicons](http://typicons.com)
    - [Entypo](http://www.entypo.com/)
    - Repackaged into a single file using [Fontello](http://fontello.com)

