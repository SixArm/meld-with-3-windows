# meld-with-3-windows: launch meld merge tool with 3 windows.

  * window 1: diff from BASE to LOCAL
  * window 2: diff from BASE to REMOTE
  * window 3: three-pane view

Meld is a visual diff and merge tool targeted at developers.

Meld helps you compare files, directories, and projects.

## Setup

To use this script, first add this to your gitconfig:

    [merge]
      tool = meld-with-3-windows
    [mergetool "meld-with-3-windows"]
      cmd = $HOME/bin/gitmerge $BASE $LOCAL $REMOTE $MERGED

See http://blog.wuwon.id.au/2010/09/painless-merge-conflict-resolution-in.html

## About ##

  * Command: meld-with-3-windows
  * Version: 1.1.0
  * Created: 2013-09-18
  * Updated: 2016-02-09
  * License: GPL
  * Contact: Joel Parker Henderson (joel@joelparkerhenderson.com)
