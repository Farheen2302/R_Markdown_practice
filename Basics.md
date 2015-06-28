#Mark Down Basics
##Formatting
###Bold and Italic Format
*italic*
**bold**
--------------
##Headers

#Header 1
##Header 2
### header 3

----------------
## LISTS
###Unordered Lists
*Item 1
*Item 2
*Item 3
  + Sublist 3(a)
  + Sublist 3(b)
  + ......
  

##Ordered List
1. Item 1
2. I tem 2
  1. Sub item 2(i)
  2. Sub item 2(ii)


---------------
##R code Chunks  
``` {r}
summary(farheen$basics)
str(farheen$R_code)
```

###Inline R code  
There are ` r ncols(farheen$basics) ` in the Date frame 
--------------

##Links
*Simply write the link begining with http
https://github.com/Farheen2302/R_Markdown_practice/edit/master/Basics.md
*If you want to add the phrase 
[This is my Git repo](https://github.com/Farheen2302/R_Markdown_practice/edit/master/Basics.md)

--------
##Images
*This is similar to links just add ` ! ` in front   
![MARK DOWN](https://trinkerrstuff.files.wordpress.com/2014/11/rmarkdown.png?w=127&h=150)
![MARK DOWN](https://www.opencpu.org/images/markdown-everywhere.jpg)
![COOL MD GOD](http://i.imgur.com/jrwbX.jpg)

----------
##Blockquotes
> This is cool feature
> I like it

---------
##Plain Code Blocks
```
I am formatted code block , never evaluated
```
### Inline  code
We defined the `add` function to
compute the sum of two numbers.
--------
##Horizontal Rule / Page Break
*More than or equal to 6 '*' or '-' *
********
--------

--------
##Table
*never expected but its there*  
Column 1 | Column 2
-------- | --------
Row1     | Row 1
Row 2    | Row 2

