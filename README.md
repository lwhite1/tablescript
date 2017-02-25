# tablescript
a  scripting language for tablesaw

I'm not sure how far I will take this, at present it is a hobby effort, but it's something I've wanted to do
for a few years so, maybe.

The idea is to write an interpreted, dynamically typed language that will get transpiled to Java and 
execute tablesaw commands in a more user-friendly way than is possible with native java tablesaw. 

I've looked at a number of existing language designs: Smalltalk & Newspeak, SQL & Quel, Julia & R, Python & Pandas,
as well Q and spreadsheets.  

##Desiderata:
* purely object oriented: prototype inheritence (no classes), everything is a message
* super simple syntax
* 3 kinds of messages: unary (a factorial), binary (3 * 4), and keyword (aString replace: "xyz" with: "123").
* reflective: Mirror-based?
* high performance: Hard work is done in Tablesaw's primative-heavy, native Java 
* modular
* Notebook-style interface
* REPL
* access control (public, private, ...)
* version-control friendly

I will provide additional information as the design solidifies.
