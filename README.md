# Programming In General

Programming In General is a text resource for people to use to learn how to program.
This resource is recommended for both those seasoned verterans who want to learn something new
or even those who have never learned a programming language before.

Programming In General is written in a code agnostic format allowing readers to translate 
the examples to which ever programming language they would like.

Enjoy.

## PDF

I will always try to keep the lastest pdf version of the book provided in the repository, but if I forgot then you can build the pdf from source. 


## Contributing

Please! Fork this project, write a chapter, a section or even just fix my terrible grammar and make a pull request. I will ensure to give credit where credit due!

A few things to keep in mind when contributing actual writing, I have been keeping a few standards such as keeping a single empty space between paragraphs, new sections and code blocks.

There are three commands I have added to latex for this book, `\pigVar, \pigVal and \pigOut`, they are fairly easy to figure out. `\pigVar` is for when variables, functions, class properties, etc are stated in text, `\pigVal` is when values are stated in code and `\pigOut` is used when writing the output of code.
These commands are used as `\pigVar{name} is equal to \pigVal{22}`.

The main directory, chapter and section structure might be a little weird, I am new to latex and wanted a way to separate out chapters and sections and well of course I wrote a script to do it for me. Each chapter has its own directory, with its chapter number and name, the chapter introduction text is provided in a file with the same EXACT name as the chapter without the number and .tex on the end and all sections are numbers as 1.1, 1.2, etc and then their section name. They are 1.# because thats the way I did it and live with it.

Please take a look at some of the chapters and sections already written for a better understanding.
