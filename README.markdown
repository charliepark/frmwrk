# Frmwrk (A Minimalist CSS Grid Framework)

## Overview

You might know of elaborate CSS frameworks for applying a grid layout. Blueprint, 960.gs, YUI, Compass, etc.
This is a much simpler grid layout. You define your column and gutter widths, and the number of columns you want on your page, and Frmwrk does the rest.

It's for use in Ruby and Rails applications, but could easily be ported to other languages / frameworks.

## How to Use

Just take the code in frmwrk.html.erb and stick it in the \<head> of your ERB file (either in a layout file or in a partial, if you're calling it from several pages).

You can change the 3 variables ("number\_of\_columns", "column\_width", and "gutter\_width") to be whatever you want, giving you the flexibility to set the number of columns you want, the width of the columns you want, and the width of the gutters that you want.

Once you have your framework set up the way you'd like, it's not a bad idea to copy your output and paste it into your external CSS file (and to remove it from your layout file), so the values don't have to be calculated each time.

## See a way Frmwrk can be improved?

Please feel free to fork it / patch it / get in touch. Thanks!