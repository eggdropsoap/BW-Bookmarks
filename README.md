# BW Bookmarks
*Add bookmarks to the official digital BW book(s)*

## What is this?
The official PDF releases of BWHQ's flagship RPG lack bookmarks. BW Bookmarks is a collection of LaTeX scripts containing hand-compiled bookmark data for these digital releases. Running the scripts applies their list to the PDF, fixing the missing bookmarks.


## What do I need to use this?

1. A paid copy of [*Burning Wheel Gold Revised* from OneBookShelf](https://www.drivethrurpg.com/product/448187/Burning-Wheel-Gold-Revised) (for BWGR_bookmarked.tex), [*Burning Wheel Codex* from OneBookShelf](https://www.drivethrurpg.com/product/448189/Burning-Wheel-Codex?src=also_purchased) or [*Burning Wheel Anthology 2021* from OneBookShelf](https://www.drivethrurpg.com/product/441674/Burning-Wheel-Anthology-2021) (***not** affiliate links!*)
2. A reasonably current distribution of TeX, such as [TeX Live](https://tug.org/texlive/)
3. The script matching the book.

## How does it work?

LaTeX is a document-creation language widely-used in the scientific community. A LaTeX script is a text file with a list of instructions describing how to create a particular document.

In this case the instructions in the script are especially simple: read the official PDF in, and then write it right back out except with the pre-made list of bookmarks included. The result is a PDF with working bookmarks.

## Will this work for any book?

No, the list of bookmarks is pre-made to match the specific PDF book. A new script with a different set of hand-compiled bookmark data would be needed to add missing bookmarks to a different book.

## Why do it this way? It seems unnecessarily complicated.

Two reasons: **copyright**, and **avoiding duplication of work**.

The normal way to add missing bookmarks to a PDF is to open it in Acrobat Pro or somesuch, use the bookmark tool to create each bookmark one by one, and then save the file. That helps one person, but the fixed PDF can't be shared around while respecting the copyright of the book.

Using a LaTeX script instead lets everyone individually and privately update their own copy of the PDF with proper bookmarks.

Manually fixing PDF bookmarks is also a lot of work—work that can be better done once, instead of unnecessarily repeated by everyone who wants to fix a PDF. Also, not everyone has access to good PDF editing software, never mind the time and attention it takes to *click-click-click* and *type-type-type* hundreds of bookmarks into a GUI. A script lets that effort happen once up-front.

## Okay, but *how* do I use it?

See "INSTRUCTIONS" at the top of the script you're using for human-friendly instructions for using that script. LaTeX scripts are plain-text files so you can read it with any text editor.

## I found a typo!

Great! There's always at least one and *someone* needs to find it.

Open an [issue](https://github.com/eggdropsoap/BW-Bookmarks/issues) to let me know, or edit the script directly on GitHub and submit it as a suggested edit (a "pull request" in git parlance).
