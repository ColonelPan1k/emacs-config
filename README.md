# Emacs


![Emacs](https://raw.githubusercontent.com/kmg731/emacs-config/master/screenshots/Screenshot%20from%202021-08-10%2022-29-09_UPDATED.png)


This is my daily config for Emacs that I've reorganized and built up over the
last year or so of using emacs just about every day. I spend the majority of my
time working in emacs and need it to be well-suited to everything I do. I
recenlty did a major overhaul using org-mode and org-babel. Using this, it's
much easer to keep organized and much more literate.

I've decided that, rather than having a whole repo for my dotfiles, it was
better to just keep one for my emacs config. Since Emacs is really the only
application I use, it seemed unnecessary to keep everything else around. In a
worst-case scenario, if I lost my zshrc, it would take an hour or so to get it
back up to 99% of what it was prior to that. If I lost my emacs config though,
I'd have to spend a few days remaking it. The goal of my emacs config is to keep
everything I'd need as well-contained as I can within emacs. I haven't managed
to work myself into a purely emacs environment yet, but I feel like I'm getting
close. Outside of emacs, I use my terminal (really there to keep it on a
separate monitor) and firefox. If there's ever an app I start using outside of
emacs, I will usually try to find something to replicate the functionality
within emacs as soon as I can (and typically it ends up being easier to use
and with more functionality than whatever was outside of emacs).

## Changes

Some of the changes I've made since I last updated my emacs config:
- Properly setup and configure Org-roma
  - Learn what all the fuss is about with org-roam
	- Learn that I too am now part of the fuss with org-roam
	  (seriously, it's the best possible program for note taking)
- Set up helm autocompletion
- Hackernews dashboard reader
- Ignore certain electric-pair-mode pairs in specific buffers
- Add linting to PyMode
- Move org files from within `~/.emacs.d` to a separate home directory
- Properly configure source blocks and add shortcuts
  for different programming languages
- Edit emacs lock file handling so it doesn't keep freaking out FastAPI


## Things left to do

- Learn and configure magit
  - Move zsh git aliases to magit (things like gsb, gcmsg, etc)
- Find a python autocomplete framework that works and isn't slow
- Anything else that pops up and needs a quick fix
- Properly learn emacs lisp

## Credits

Much of my config is inspired by the config files of [Harry R. Schwartz](https://github.com/hrs/dotfiles/blob/main/emacs/dot-emacs.d/configuration.org)
and [David Wilson](https://github.com/daviwil/dotfiles/blob/master/Emacs.org)).
