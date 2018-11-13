# Improved TU Delft PhD Thesis Template

This is an improved version of the [TU Delft PhD thesis
template,](https://www.tudelft.nl/en/tu-delft-corporate-design/downloads/)
versioned `ff9d073` (dissertation template from July 2nd, 2015). It
features a number of changes to increase both on- and off-screen
(printing) quality, as well as reduce printing costs. The layout is
very well-readable, but rather close to the low limits for font size
and page utilization (i.e., if anything, I would recommend to increase
font size or page margins).

## Style

Here is a side-by-side comparison of the two different styles.

| Old Style       |  New (this template) |
:----------------:|:---------------------:
![](readme-pics/prev_chapter.png) | ![](readme-pics/new_chapter.png)
![](readme-pics/prev_page.png) | ![](readme-pics/new_page.png)


To get a full picture of what this style looks, have a look at [my PhD thesis](https://repository.tudelft.nl/islandora/object/uuid:b2946104-2092-42bb-a1ee-3b085d110466?collection=research), which is set using the defaults in this repository. Note that there are small differences between the online and print versions (such as cutter's marks to trim pages and page alignment).

## Key Improvements

Specifically, it makes these key improvements over the TU Delft
dissertation house style: It ...

- actually compiles (well, at least on the tested Linux systems).
- has been used successfully in my dissertation and been approved by the TU Delft Graduate School.
- makes the page layout much better suited to printing, because of an increased binding offset width. Text does not go into the binding fold of the book. The writable part of the page is also centered better when printed.
- uses much nicer fonts for on- and off-screen readability, namely [Libertinus](https://github.com/libertinus-fonts/libertinus) for regular text and [Inconsolata](https://fonts.google.com/specimen/Inconsolata) for mono-spaced elements such as source code listings.
- comes with a large list of already included packages, placed in a compatible order (some LaTeX package orders cause hard-to-debug compile errors).
- reduces the number of pages that need color, thus reducing printing costs, while pertaining TU Delft's signature blue for key elements such as chapter titles.
- makes for more crisp printing, by converting 90% gray anthracite to a fully black tone. Gray scale values between 30% and 90% typically look blurry or faint in print because the printer simply uses less ink for them. To cater for this, I reduced the header text size to not interfere with the running text below.
- keeps a consistent style of reporting page numbers on top of pages.
- makes the screen and print versions of the PDF resemble each other more, while keeping the respective benefits of each format (for example, for on-screen PDFs, no offset binding adjustment is needed).
- makes the propositions page now fit a bigger amount of text. Moreover, the format of the propositions page now fits inside the thesis, instead of being the same size (which would stand out!).
- changes a couple of questionable defaults, such as the copyright notice by the author.
- includes commands to generate ready-to-be-printed PDFs with all fonts embedded, a typical requirement to publish PDFs.
- is also highly recommend to use the [LaTeX URL Eternalizer](https://github.com/Inventitech/url-eternalizer).
- comes with a useful set of predefined commands, such as `circled`, `ahref` and useful predefines for `lstlisting`s and such. 

## Setup and Installation

See the original [README](README.txt).