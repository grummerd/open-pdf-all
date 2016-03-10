What is open-pdf-all?
------------------------

Handy bash scripts to help open pdf files. Either one pdf at a time or all the pdfs in a folder. Recommend using with a file manager; much more user friendly to right click a folder or the desktop and choose the action "Open pdf all"

Requirements
---------------

open-pdf-all was written in bash on ubuntu. The pdf viewer is evince. Hope to get feedback to extend to other Linux distributions and pdf viewers

Intended use cases
-------------------

- from the command line

- as a file manager action

open-pdf-all manual
-----------------------

open-pdf-all [optional folder]

Optional folder
  If folder is empty then opens all pdfs in the current folder 

Usage Examples

- open-pdf-all

Opens all pdf in the current folder

- open-pdf-all /home/homefolder/Documents/

Opens all pdfs in folder /home/homefolder/Documents

open-pdf manual
------------------

open-pdf [optional file] [optional path]

optional file
  Just the file's base name (asdf.pdf). Looks for the file in the current folder

optional path
  Specify a path. Defaults to current folder if empty. The path may contain an optional trailing slash
  
Usage Examples

- open-pdf

Prompts for a file name in the current folder. Type in the file name will open the pdf. This is a fallback use case

- open-pdf asdf.pdf

Opens asdf.pdf from the current folder

- open-pdf asdf.pdf /home/homefolder/Documents/

Opens asdf.pdf located in folder /home/homefolder/Documents/ rather than the current folder

Donations
-------------

- By bitcoin 

149nxQ1mGFapajmPujiSXQnuzeggNRU5kE

A percentage of donations will be donated to other projects. All donations and re-donations will be cataloged in donations.md

When making donations, please send a PM with a url or reddit user name. Will cite the donors when making a redonation

The bitcoin address above will change from time to time. Used bitcoin addresses will be written in donations.md, plz do not send to them
