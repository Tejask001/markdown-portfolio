<!-- HEADINGS -->
# Headings
To create a heading, add one to six # symbols before your heading text. The number of # you use will determine the size of the heading. Add a space after '#' symbol.

Example Code:

```
# This is a heading
```
># This is a Heading

<br>

<!-- STYLING TEXT -->
# Styling Text
<!-- ITALICS -->
## Italics
For Italics enclose text within (* *) or within (_ _) 

Example code:
```
_This text is Italics_

*This text is Italics*
```
>_This text is Italics_

>*This text is Italics*

<br>

## Bold
For Bold enclose Text within(** **) or within (__ __)

Example code:
```
**This text is bold**

__This text is bold__
```

>**This text is bold**

>__This text is bold__

<br>

## Nested Bold and Italics
Enclose the part to be bold within (** **) and part to be Italics within (_ _)

OR

Italics part within (* *) and bold part within (__ __)

>Do not use the same symbol like * for both italics and bold
or _ for both italics and bold


Example code:

```
**This whole line is bold but this text is in _italics_**

*This whole text is in italics but this text is in __bold__*
```
>**This whole line is bold but this text is in _italics_**

>*This whole text is in italics but this text is in __bold__*

<br>

## Quoting Text
To quote a part of Tex add (>) symbol in front of it

Example:
```
This line is not a quote
> This line is a quote
```
This line is not a quote
>This line is a quote

<br>

# Adding Links
To add links use ([]) to enclose text that will be hyperlinked and then next to add the link within closed brackets "()"

Example code :
```
[Github Docs](https://docs.github.com/en)
```
[Github Docs](https://docs.github.com/en)

<br>

# Code Blocks
For highlighting code that is inline use single backticks(``)

Example:
```
This line contains a `code` inline.
```

> This line contains a `code` inline.

For Adding a whole code block, enclose it within triple backticks before and after.

Example:
````
```
This  is a code block
```
````

>```
>This is a code block
>```

You can also add language specific Syntax highlighting by just adding the language name right after the triple backticks.

Example code:


````
```c++
int i = 0;
cout << i << endl;
```
````
>```c++
>int i = 0;
>cout << i << endl;
>```
<br>

# Adding Images
You can add images by adding ! before square brackets and adding alt text within the brackets. Then eclose the link to the image within closed brackets

Example Code:
```
![Image of a cute dog](https://premiumpethouse.com/public/img/dog-breeds/golden-retriever/golden-retriever-puppy-outstanding-quality.jpg)
```
>![Image of a cute dog](https://premiumpethouse.com/public/img/dog-breeds/golden-retriever/golden-retriever-puppy-outstanding-quality.jpg)

The alt text is used by screen readers and displayed if image is not loaded
<br>

# Lists
You can make an unordered list by preceding one or more lines of text with - or *.

Example code:
```
- list item 1
- list item 2
- list item 3
```
>- list item 1
>- list item 2
>- list item 3

<br>
To order your list, precede each line with a number.
 
 Example Code:
 ```
1. list item 1
2. list item 2
3. list item 3
 ```
>1. list item 1
>2. list item 2
>3. list item 3

<br>

## Nested Lists
To create a nested list type space characters in front of your nested list item, until the list marker character (- or *) lies directly below the first character of the text in the item above it.

Example code:
```
1. First list item
   -First Nested list item
    -Second Nested List item
```
>1. First list item
>    - First Nested list item
>      - Second Nested List item

<br>

# Task Lists
To create a task list, add dashes (-) and brackets with a space ([ ]) in front of task list items. To select a checkbox, add an x in between the brackets ([x]).

Example Code:
```
- [ ] Make Markdown Cheatsheet
- [X] Make Markdown Documentatioj for self
```
>- [ ] Make Markdown Cheatsheet
>- [X] Make Markdown Documentatioj for self

<br>

>:warning: Not all appplications support task lists

<br>

# Collapsed Section
Any Markdown within the ''< details >" (no spaces in actual syntax but used here because it was not rendering correctly block will be collapsed until the reader clicks  to expand the details. Within the "< details >" block, use the "< summary >' tag to create a label to the right of .

Example Code:
```
<details><summary>CLICK ME</summary>
Hi I am a collapsed section!!
</details>
```

><details><summary>CLICK ME</summary>
>Hi I am a collaped section!!
></details>













