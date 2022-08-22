
# Markdown

Markdown is essentially a way to make content for the web without having to learn a programming language. It's designed to be simple and be more like how you would write normally in your day to day. It does have some special characters but it's significantly less complicated to learn and use compared to something like HTML.

- **Headings:**  
use # symbols numbering from 1 # to 6 #'s, with 1 being the largest. Then a space followed by whatever text you want your header to be.
- **Paragraphs:**  
To create a Paragraph, seperate lines of text by using a blank line inbetween. See below.

> "Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
>
> Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat."

- **Line Breaks:**
To create a linebreak, use 2 white spaces after the last word, letter or sentence. Then begin on the line under and it will be a new seperate line.
- **Emphasis:**  
  - **Bold:**  
  To make text or any other character Bold you do 2 asteriks before and after (** **).
  - *Italic:*  
  To do Italic is just like Bolt but with 1 asterik (* *).
  - ***Bold and Italic:***  
  To do Bold and Italic at the sametime you do 3 asteriks before and after (*** ***). 
- Blockquotes:  
  - Single Paragraph:  
  You do an > plus a space then begin typing whatever you want the BQ to be.  
  - Multiple Paragraphs:  
  To do a multi Paragraph BQ you do the same as for a single BQ but you add an > on each blank line between Paragraphs.
  You can nest a BQ by doing two >>'s infront of the paragraph you want to nest.
  - BQ's can contain most Markdown formated elements but not all. You have to experiment. 
  - BQ best practice is to put a blank line before and after each BQ.
- Lists
  - Unordered list:  
  In order to do an UL you simply add a (-) with a space after it and then add whatever you want to the list. An example would be (- blah). If you want to start an UL with a number followed by a period you need to "escape" the (.) with a backslash before it, otherwise it will become an OL. Example (`- 1\.`).
  - Ordered list:  
  To do an OL you start with the number 1 and add a period (1.) and then when you want to go to the next list item you just start on a new line and do the number 2 with a period (2.) and so on.
  - Adding elements in Lists:  
  To add another element in a list while preserving the continuity of the list, indent the element four spaces or one tab, as shown in the following examples. Reference the Basic Syntax reading. Have to add a space between each UL item or two spaces after each UL item. E.g. of a Blockquote Element.
  - First item
  - Second item
  
      > BQ
      
  - Third item   
      
  You can nest an UL in an OL, indent 4 spaces. You can also do an OL inside an OL the same way.
  
- Code  
To denote a word or phrase as code, enclose it in backticks \` \`.
To escape double backticks you do one backslash with no spaces infront of each backtick.
- Horizontal Rules  
Do three dashes (---) on a line by themselves.
---
- Links  
\[name](website link)
Quickly turn a URL or an email into a link enclose the it in angle brackets <>.
Formating links add asterisks before and after the brackets and parens. For code, add backticks inside the brackets.
- Images  
!\[alt text](image link or path) optional "description" inside parens for when person mouses over the image.   

- Escaping Characters  
To display a literal character otherwise used to foramt text in MD add a backslash (\) in front of the character with no spaces. E.g. \`code\` which would normally show up as `code`.

[Back to my home page](README.md)

