#Wildcard
A wildcard in Linux is a symbol or a set of symbols that stands in for other characters. It can be used to substitute for any other character or characters in a string. For example, you can use a wildcard to get a list of all files in a directory that begin with the letter 
three common wildcard in Linux:

? – matches a single character. For example, O??d matches anything that begins with O, ends with d and has two characters in between (like Oind, Okhd, Oerd, but not Oereed, Oad, Oerererd.)
* – matches any character or set of characters, including no character. For example, O*d matches anything that begins with O and ends with d (like Oind, Okhd, Oerd, Oereed, Oad, Oerererd, Od, Oarmeerrd). The number of characters in between O and d is not important.
Bracketed values – match characters enclosed in square brackets. For example, O[ac]d matches only Oad and Ocd. You can also specify a range of values: O[a-e]d matches Oad, Obd, Ocd, Odd and Oed.

 check https://geek-university.com/linux/wildcard/ to read more about wildcard

Using tar with --checkpoint-action options, number of actions can be defined.
