# K.I.S.S (KEEP IT SIMPLE, STUPID): A TLDR OF GITHUB MARKDOWN FOR BEGINNERS

## 👋INTRODUCTION

Hello, Dear Reader!

I will be frank: at best, official technical documentation is usually dry, overwhelming, and kind of feels like this sometimes...like reading the hardware manuals of your ancestors

<p align="center">
  <img width="224" height="500" alt="NOBODY READS THE MANUAL" src="https://github.com/user-attachments/assets/fe771af5-f285-4bc1-a7c0-ba87bb7f06f2"/> 
</p>

We all have seen how attention spans have been dwindling the last several decades, so I do not put any blame upon others who just wish to figure out things as quickly as possible—like trying to figure out how to format clean repository layouts, making a text block stand out, and the other basic features of GitHub Markdown. In my humble but honest opinion, you do not need a novel breakdown of obscure syntax edge cases, nor reading the manual (BLASPHEMY!) or pages of a website. 

Living with the struggle of ADHD (Attention-Deficit Hyperactive Disorder) made me realize sometimes we just need the essentials, and fast. Too many guides tend to overwhelm beginners, myself included (and I'm a tech guy), with loads of word salad and lack of pretty pictures (media literacy joke mind you).

That is why I built this project. Adhering to the classic engineering principle of K.I.S.S. (Keep It Simple, Stupid), this ancient art was passed down to me by my father, and his father, and our forefathers. This repository serves as a streamlined TL;DR guide for GitHub-Flavored Markdown.

Whether you are looking to clean up your own repository presentation or just need a quick formatting sanity check, this guide will hopefully strip away the amount of word-salad to give you exactly what you need to know (in Markdown and in HTML where applicable), and what it looks like in practice.

<a name="table-of-contents"></a>
## 📖TABLE OF CONTENTS
* [Introduction](#introduction)
* [Headings](#headings)
* [Paragraphs](#paragraphs)
* [Line Breaks](#line-breaks)
* [Emphasis](#emphasis)
  * [Bold](#bold)
  * [Italic](#italic)
  * [Bold & Italic](#bold--italic)
* Blockquotes
  * Blockquotes with Multiple Paragraphs
  * Nested Blockquotes
  * Blockquotes with Other Elements
* Lists
  * Ordered Lists
  * Unordered Lists
    * Starting Unordered List Items With Numbers
    * Unordered List Best Practices
  * Adding Elements in Lists
    * Paragraphs
    * Blockquotes
    * Code Blocks
    * Images
    * Lists
* Code
  * Escaping Backticks
  * Code Blocks
* Horizontal Rules
* Links
  * Adding Titles
  * URLs and Email Addresses
  * Formatting Links
  * Reference-style Links
    * Formatting the First Part of the Link
    * Formatting the Second Part of the Link
    * An Example Putting the Parts Together
* Images
  * Linking Images
* Escaping Characters
  * Characters You Can Escape
* HTML

## Headings

Headings are the basis of any kind of formatting. Without headings,

Everything \
Would look like \
a Mess \
Like This \

To add Headings you can use the **Hash Sign (#)** to make up to **6 Headings**

```
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```
Resulting in this:

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

Alternatively you can also use HTML's way of the heading command like so:

```
<h1> Heading 1 </h1>
<h2> Heading 2 </h2>
<h3> Heading 3 </h3>
<h4> Heading 4 </h4>
<h5> Heading 5 </h5>
<h6> Heading 6 </h6>
```
<h1> Heading 1 </h1>
<h2> Heading 2 </h2>
<h3> Heading 3 </h3>
<h4> Heading 4 </h4>
<h5> Heading 5 </h5>
<h6> Heading 6 </h6>

**NOTE: DO NOT PUT HEADINGS LIKE #HEADING 1 OR IT MAY NOT FORMAT CORRECTLY, AND TRY TO USE BLANK LINES**

<p align="right">
  <a href="#table-of-contents">
    <kbd> 🔺 Return to Table of Contents</kbd>
  </a>
</p>

## Paragraphs

Paragraphs are the second half to the basis of formatting. To create a paragraph, all you have to do is **make a blank line by hitting Enter twice** like so:

```
This is the first paragraph.

This is the second paragraph.
```
This is the first paragraph.

This is the second paragraph.

**NOTE: DO NOT PUT TABS/SPACES IN FRONT OF PARAGRAPHS**

<p align="right">
  <a href="#table-of-contents">
    <kbd> 🔺 Return to Table of Contents</kbd>
  </a>
</p>

## Line Breaks

Sometimes you might want to add a line break to a sentence. Once you finish the sentence, **hit the Space bar twice, then hit Enter** like so:

```
This is the first sentence  
Followed by a line break
```

This is the first sentence  
Followed by a line break

Additionally, you can use HTML's break command:

```
<p> This is the first sentence <br>
Followed by a line break </p>
```

<p> This is the first sentence <br>
Followed by a line break </p>

**NOTE: YOU CAN USE THE BACKSLASH ("\\") AS A MEANS TO LINE BREAK, BUT IT IS NOT ALWAYS COMPATIBLE SO I WOULD BE CAREFUL**

```
Example of a sentence with a backslash \
Transitioning to the second sentence
```

Example of a sentence with a backslash \
Transitioning to the second sentence

<p align="right">
  <a href="#table-of-contents">
    <kbd> 🔺 Return to Table of Contents</kbd>
  </a>
</p>

## Emphasis

Using emphasis can sometimes help to *get the meaning across* or to **get people's attention** if you wish to make something ***stand out*** (I think you get it).

### Bold

To bold a piece of text, **simply add two asterisks in front and behind like so:**

```
------> ** THESE THINGS
**THIS IS BOLDED TEXT**
```
**THIS IS BOLDED TEXT**

You can also use HTML's version with the strong tags like so:

```
<strong> THIS IS BOLD TEXT </strong>
```

<strong> THIS IS BOLD TEXT </strong>

However...

**NOTE: WHILE YOU CAN USE UNDERSCORES TO BOLD, IT MAY NOT BE INCOMPATIBLE, SO STICK TO ASTERISKS**

<p align="right">
  <a href="#table-of-contents">
    <kbd> 🔺 Return to Table of Contents</kbd>
  </a>
</p>

## Italic

To italicize a piece of text, **simply add one asterisk in front and behind like so:**

```
------> * THIS THING
*THIS IS ITALICIZED TEXT*
```
*THIS IS ITALICIZED TEXT*

You can also use HTML's version with the em tags like so:

```
<em> THIS IS ITALICIZED TEXT </em>
```

<em> THIS IS ITALICIZED TEXT </em>

Once again...

**NOTE: DO NOT USE UNDERSCORES. BAD FORMATTING.**

<p align="right">
  <a href="#table-of-contents">
    <kbd> 🔺 Return to Table of Contents</kbd>
  </a>
</p>

## Bold & Italic

To **bold** and *italicize* a piece of text, ***simply add three asterisks in front and behind like so:***

```
------> *** THESE THINGS
***THIS IS BOLDED AND ITALICIZED TEXT***
```
***THIS IS BOLDED AND ITALICIZED TEXT***

You can also use HTML and combine both the strong and em tags like so:

```
<em><strong>THIS IS BOLD AND ITALICIZED TEXT </strong></em>
```

<em><strong>THIS IS BOLD AND ITALICIZED TEXT </strong></em>

**NOTE: NO UNDERSCORES. CAPICHE**

<p align="right">
  <a href="#table-of-contents">
    <kbd> 🔺 Return to Table of Contents</kbd>
  </a>
</p>
