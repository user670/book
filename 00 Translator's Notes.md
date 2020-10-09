# Translator's Notes

This English translation of *An Introduction to Programming in Wenyan Language* is translated by me, User670.

First, I must admit that I'm **not fluent in either Classical Chinese nor English**. My first language is (contemporary) Mandarin Chinese, and despite having to learn Classical Chinese in school, I never got good at reading them. I learn English as a second/foreign language. There **will** be parts that I cannot fully understand the original text and/or cannot find the best way to express the idea in English.

There are also some liberties that I often take in order to make it easier for me to translate or to make the translation easier to understand (such as leaving out unnecessary metaphors or Chinese cultural references). The translation will cover all programming-related ideas in the original text, but will not be a word-for-word translation.

## Chapter-specific notes

### Chapter 1: Introduction
- The paragraph leading into the terminologies. In the original text, it says that programming started in the west with terms never heard of in ancient China, and thus need explanation so that everyone can understand. That would not make that much sense for an English context, thus I stripped it down to that.
- ¼× and ÒÒ are Chinese "Heavenly Stems". ¼× and ÒÒ are the first and second of the Heavenly Stems respectively, and thus are often used to mean "first" and "second" (as in grades, or as in order). The English equivalent would be `a` and `b`, as in `var a=3;`.
### Chapter 2: Variables
- Again, sorry for the lack of consideration of non-binary genders when it said sex is to be a boolean.


## Programming ideas that are language-specific

### Chapter 1: Introduction
- Quotation marks. In most modern, western languages, variables do not need quotation marks (although some languages use other symbols to indicate a variable, for example in PHP all variables have a `$` before the name), and both 'single quote' and "double quote" are used to mark some form of text (which differs by language. C/C++ uses single quote for characters and double quote for strings. In PHP and Ruby, both are strings, but double quoted strings allow more features like more escape characters or parsing variable values. In JavaScript and Python, single- and double-quoted strings are identical).
### Chapter 2: Variables
- Unnamed variables are often not in modern, western languages. The equivalent is the more intuitive "literals", i.e. literal values you type in the code. For example, you can type the literal number `3`, which the machine recognizes, but later discards because it's never used. You can then proceed to do something with the `3`, for example `3+5` (which you get 8, but in the same way it gets discarded unless you do something else to it), `print(3)` or `x=3` (which you do get to keep because you have a name assigned to it).
- Towards the end of the chapter, it says you can sigh (`àæ`) to discard unnamed variables. However, this key word is hardly, if ever, seen in the example programs of Wenyan, and is largely unnecessary because after compiling Wenyan to other langauges, literals will be automatically discarded; and even if in the future a direct Wenyan compiler is made, it will likely do the heavy lifting automatically ("garbage collecting", as the programmers call that).