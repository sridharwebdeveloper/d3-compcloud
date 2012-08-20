# Comparative Word Cloud Layout

This is a layout for creating comparative word clouds.

Comparative word clouds are like normal word clouds, except they
compare the words used in two sources.

The words are sized based on the number of times they are used in
either article. They words are placed in the cloud based on how
relatively often they are used--words that are used about the same
number of times in both articles tend to appear closer to the middle,
with words disproportionately used in one article or another appearing
closer to the top or bottom. Their placement is not absolute, however,
and I recommend showing that information in color or some other way.

![Example cloud created from two Jay Rosen posts](https://s3.amazonaws.com/zthomae-project-pics/rosencloud.PNG)

## Usage

See the sample in `examples/` for the source generating the word cloud pictured above.

This layout requires [D3](http://mbostock.github.com/d3/).  It’s similar to
[d3.layout.force](https://github.com/mbostock/d3/wiki/Force-Layout), in that
it’s **asynchronous** and **stateful**.

## Bugs

* Words sometimes appear off-canvas.

## Based heavily on [Jason Davies'](http://www.jasondavies.com) Word Cloud Layout.

### Description:

This is a [Wordle](http://www.wordle.net/)-inspired word cloud layout written
in JavaScript. It uses HTML5 canvas and sprite masks to achieve
near-interactive speeds.

See [here](http://www.jasondavies.com/wordcloud/) for an interactive
demonstration along with implementation details.