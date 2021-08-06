


# HTML/CSS Demos


<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Purpose](#purpose)
- [Files](#files)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Purpose

This archive contains very basic stuff that demos how (some) browsers deal with certain edge cases in
HTML+CSS processing. For example—provided you have the correct font (EBGaramond) installed on your system,
and have cloned this repo to your ocal
machine—[`public/ligatures-with-intervening-tags.html`](public/ligatures-with-intervening-tags.html) shows
that at least Chrome-derived browsers (such as Brave) can suprise you when dealing with ligatures: While
being *capable* of isolating individual glyphs from a ligature like `ffi` (as shown by one line where the
size of the first `f` is increased), they are also capable (or, refuse to isolate the same character) when
only the *color*, not the size of a letter is modified:

![](blob/master/public/ligatures-with-intervening-tags.html.png?raw=true)



## Files

* [`public/iclql-dba-tags-markup.html`](public/iclql-dba-tags-markup.html)
* [`public/ligatures-with-intervening-tags.html`](public/ligatures-with-intervening-tags.html)


