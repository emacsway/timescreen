=======================================
Timescreen - Take periodic screenshots
=======================================

Timescreen - Take periodic screenshots.

Installation
=============

1. Install dependices::

    sudo apt-get install scrot imagemagick mplayer

2. Add timescreen/bin to your $PATH or add link like::

    ln -sf `pwd`/timescreen/bin/timescreen ~/bin/

3. Configure, if need, environment variables in your ~/.profile::

    export TIMESCREEN_MAX_WIDTH=640;
    export TIMESCREEN_QUALITY=65;
    export TIMESCREEN_DATA_ROOT=~/timescreens;
    export TIMESCREEN_INTERVAL=300;  # in seconds


Usage
======

Run in console on start::

    timescreen project_name

And press C-c on end of work.

Homepage https://bitbucket.org/evotech/timescreen
