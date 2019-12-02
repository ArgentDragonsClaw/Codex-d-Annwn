# Codex d'Annwn

The Codex d-Annwn is a mobile-friendly 5e spellbook that organizes a set of homebrew spells.

See the latest compiled build [here](https://argentdragonsclaw.github.io/Codex-d-Annwn/). 

Grimoire is forked from [https://thebombzen.com/grimoire/](https://thebombzen.com/grimoire/).



## Changelog
* Initial commit for the Codex

## To Do
* Most spells

## Structure
Spells can be found inside `_posts/`. Each spell gets its own post, written and stored as a [Markdown](https://daringfireball.net/projects/markdown/basics) file. The date is arbitrary and never displayed, but still necessary for [Jekyll](https://jekyllrb.com) to process the posts properly.

If you'd like to help fill out the rest of the spells from the PHB, for each new spell you make:

1. Make a new post inside `_posts/` for each new spell, and copy the formatting from another spell.
2. Submit a pull request for the spell(s) when you're finished, and that's it! Thank you so much. :)

## Build Instructions
I've edited _config.yml for my own build purposes, but if you've got [Jekyll](https://jekyllrb.com) set up locally, the following should create the build from your friendly command line terminal:
`jekyll serve -Vw --no-watch --baseurl ""`

## Thanks

Thanks to [@thebombzen](https://github.com/thebombzen/) for writing the fork, and [@ephe](https://github.com/ephe/) for writing the original version of this thing in the first place.