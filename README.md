# Markdown Syntax
---
## Comments
---
Headings are added just like in html 

"\<!--Comments go here -->"

## Headings
---
<p>You can add headings by putting a hashtag sign before your heading text. The number of hashtags increases with the increase in the heading level as seen below.</p>

# Heading 1 (1 hashtag)
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6 (6 hashtags)

---
## Italics
---
<p>We use " * " before and after the text we want to italicize.</p>

**Example:** \*italics\* => *italics*

---
## Strong/Bold
---
<p>We use " ** " before and after the text we want to bold.</p>

**Example:** \*Bold Text\* => **Bold text**

---
## Strikethrough text
---
<p>We use " ~~ " before and after the text we want to strikethrough text.</p>

**Example:** \~~ Bold Text\~~  becomes ~~Bold text~~ 

---
## Horizontal line
---

To make horizontal lines like the ones I am using to separate the sections, use three dashes "---"

---
## Escaping special character
---
To escape special characters used in markdown like \#, \*, *_ use a backlash before the character

---
## Blockquote
---
To add a blockquote, use the ">" sign before the text
<p>Example "> this is a blockquote"  will be displayed a seen below

>This is a blockquote

---
## Links
---
To display links, wrap link text in square brackets " [ ] " and the link itself in parenthesis " ( ) ". If there is any hover text, we put that in double quotes within the parenthesis.

**Example** \"\[My website](https://ocenchris.com "This is my website")" will display as => [My website](https://ocenchris.com "This is my website")

---
## Unordered lists
---
We can create Unordered lists by adding " * " before each item. Nested lists are added by indenting the nested items

**Example**

<p>\* Item 1</p> 
<p>TAB \* sub Item 1</p>
<p>TAB \* sub Item 2</p>
<p>\* Item 2</p>
<p>\* Item 3</p>

Is displayed as 

* Item 1 
    * sub Item 1
    * sub Item 2
* Item 2
* Item 3

---
## Ordered lists
---

We can create Ordered lists by adding " 1. " before each item. The items will be numbered automatically

**Example**

<p>1. Item 1</p> 
<p>1. Item 2</p>
<p>1. Item 3</p>

Is displayed as 

1. Item 1 
1. Item 2
1. Item 3

---
## Paragraph
---

We use paragraph tags like they are used in HTML. 

For Example "\<P>This is a paragraph \</p>" is displayed as 

<p>This is a paragraph</p>

---
## Images 
---
Displaying an image is similar to links except that we put an image before the square bracket.

**Example**

\"\!\[MAKDOWN LOGO](https://markdown-here.com/img/icon256.png)" will display the markdown logo ![MARKDOWN LOGO](https://markdown-here.com/img/icon256.png)


---
## GITHUB MARKDOWN
---
### Code Blocks 

We can add codeblocks in any language by adding triple backticks " ``` " followed by the name of the language and then the code. Don't forget to add the three backticks after the code.

<b>Examples</b>

In javascript => " \```Javascript CODE GOES HERE \```" 

```Javascript
 function add(num1, num2) {
    return num1 + num2;
  }
```
or Python => " \```Python CODE GOES HERE ``` "
```python
def add(num1, num2):
    return num1 + num2
```
---
## Tables
---
For Tables, use " | " for the borders on all sides of the table and use "--" under headings to hightlight the headings.

<b>Example</b>
| Name     | Email          |
| -------- | -------------- |
| John Doe | john@gmail.com |
| Jane Doe | jane@gmail.com |

---
## Task list
---
To create a task list, add a "*" before any item. add an X in square bracktes for done tasks and add empty sqaure brackets for tasks not yet done 

<b>Example</b>
* [x] Task 1
* [x] Task 2
* [ ] Task 3