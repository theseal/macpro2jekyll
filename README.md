macpro2jekyll
===========

Rough tool to convert macpro html downloaded to jekyll.
Since the Wayback Machine didn't like non-ascii characters I needed to convert some of them..

## Notes
* Not all characters are handled(PRs are welcome)
* Articles may be empty (to due of lack of data from the Wayback Machine)
* Without output-dir macpro2jekyll will put all output in /tmp
* Provied one examle file

## Installation

    $ sudo gem install reverse_markdown nokogiri
    $ git clone https://github.com/theseal/macpro2jekyll

## Converting data
    $ ./macpro2jekyll in-file [output-dir]


[macpro.se](http://macpro.se)
