# Programming In General

Programming In General is a text resource for people to use to learn how to program.
This resource is recommended for both those seasoned verterans who want to learn something new
or even those who have never learned a programming language before.

Programming In General is written in a code agnostic format allowing readers to translate 
the examples to which ever programming language they would like.

Enjoy.

## PDF

I will always try to keep the lastest pdf version of the book provided in the repository, but if I forgot then you can build the pdf from source. 

## Build PDF

To build from source you must have latex and python installed.
To build you just run the provided "build" script which will compile the main .tex source
from the chapter subdirectories. Then it compiles the .pdf version from that

### Instructions:

    git clone git://github.com/brettlangdon/programming-in-general.git
    cd "programming-in-general"
    ./build
    
Output will be:

    "Programming In General.tex"
        and
    "Programming In General.pdf"
