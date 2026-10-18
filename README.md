# K.I.S.S (KEEP IT SIMPLE, STUPID): A TLDR OF GITHUB MARKDOWN FOR ABSOLUTE BEGINNERS

<a name="introduction"></a>
## 👋INTRODUCTION

Hello, Dear Reader!

I will be frank: at best, official technical documentation is usually dry, overwhelming, and kind of feels like this sometimes...like reading the hardware manuals of your ancestors

<p align="center">
  <img width="224" height="500" alt="NOBODY READS THE MANUAL" src="https://github.com/user-attachments/assets/fe771af5-f285-4bc1-a7c0-ba87bb7f06f2"/> 
</p>

We all have seen how attention spans have been dwindling the last several decades, so I do not put any blame upon others who just wish to figure out things as quickly as possible—like trying to figure out how to format clean repository layouts, making a text block stand out, and the other basic features of GitHub Markdown. In my humble but honest opinion, you do not need a novel breakdown of obscure syntax edge cases, nor reading the manual (BLASPHEMY!) or pages of a website. 

Living with the struggle of ADHD (Attention-Deficit Hyperactive Disorder) made me realize sometimes we just need the essentials, and fast. Too many guides tend to overwhelm beginners, myself included (and I'm a tech guy), with loads of word salad and lack of pretty pictures (media literacy joke mind you).

That is why I wrote this GitHub Documentation README as my first personal Githob Repository. Adhering to the classic engineering principle of K.I.S.S. (Keep It Simple, Stupid), this ancient art was passed down to me by my father, and his father, and our forefathers. This repository serves as a streamlined TL;DR guide for GitHub-Flavored Markdown.

Whether you are looking to clean up your own repository presentation or just need a quick formatting sanity check, this guide will hopefully strip away the amount of word-salad to give you exactly what you need to know (in Markdown and in HTML where applicable), and what it looks like in practice. 

**NOTE: IF YOU WOULD LIKE TO PRACTICE THIS IN REAL TIME, I HIGHLY RECOMMEND USING JBT'S LIVE GFM EDITOR**

<p align="center">
  <a href="https://jbt.github.io/markdown-editor"><strong>HOLD CTRL AND CLICK HERE TO OPEN JBT'S LIVE GFM EDITOR</strong></a>
</p>

I do hope this helps you all along with how I learned everything by writing this documentation and TLDR guide.

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
* [Blockquotes](#blockquotes)
  * [Blockquotes with Multiple Paragraphs](#blockquotes-with-multiple-paragraphs)
  * [Nested Blockquotes](#nested-blockquotes)
* [Code](#code)
  * [Code Blocks](#code-blocks)
* [Links](#links)
  * [Adding Titles](#adding-titles)
  * [URLs and Email Addresses](#urls-and-email-addresses)
  * [Formatting Links](#formatting-links)
  * [Reference style Links](#reference-style-links)
* [Images](#images)
  * [Linking Images](#linking-images)
* [Lists](#lists)
  * [Ordered Lists](#ordered-lists)
  * [Unordered Lists](#unordered-lists)
  * [Adding Elements in Lists](#adding-elements-in-lists)
    * [Paragraphs in Lists](#paragraphs-in-lists)
    * [Blockquotes in Lists](#blockquotes-in-lists)
    * [Code Blocks in Lists](#code-blocks-in-lists)
    * [Nested Lists](#nested-lists)
* [Horizontal Rules](#horizontal-rules)
* [Tables](#tables)
* [Escaping Characters](#escaping-characters)
* [Conclusion](#conclusion)
* [Resources](#resources)



#### For accessibility and convenience, please click the button to the right of your screen to return to the Table of Contents at any time. This is utilized in every section/sub-section

<p align="right">
  <a href="#table-of-contents">
    <kbd> 🔺 Return to Table of Contents</kbd>
  </a>
</p>

## Headings

Headings are the basis of any kind of formatting. Without headings,

Everything  
Would look like  
a Mess  
Like This

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
<em><strong>THIS IS BOLD AND ITALICIZED TEXT</strong></em>
```

<em><strong>THIS IS BOLD AND ITALICIZED TEXT </strong></em>

**NOTE: NO UNDERSCORES. CAPICHE**

<p align="right">
  <a href="#table-of-contents">
    <kbd> 🔺 Return to Table of Contents</kbd>
  </a>
</p>

## Blockquotes

Blockquotes are good for when you want to quote someone as a reply on Reddit, but can also be used as another way to separate text visually from the main body if you need to highlight something. To use a blockquote, **simply using the right > arrow near the M key onto the start of the sentence** like so:

```
> This is a blockquote
```

> This is a blockquote

<p align="right">
  <a href="#table-of-contents">
    <kbd> 🔺 Return to Table of Contents</kbd>
  </a>
</p>

### Blockquotes with Multiple Paragraphs

To use a blockquote for multiple lines, **simply using the right > arrow onto multiple lines at the start of the sentence, the blank lines, and the next sentences** like so:

```
> This is the start of the blockquote
>
> This is the middle
>
> This is the end of the blockquote
```
> This is the start of the blockquote
>
> This is the middle
>
> This is the end of the blockquote

<p align="right">
  <a href="#table-of-contents">
    <kbd> 🔺 Return to Table of Contents</kbd>
  </a>
</p>

### Nested Blockquotes

If you want to make a nested blockquote, **simply using the right > arrow onto the first line, two >> arrows at the nested sentence, then back to one > arrow on the blank lines, and the final sentences** like so:

```
> This is the start of the blockquote
>
>> This is a nested blockquote
> This is the middle
>
> This is the end of the blockquote
```
> This is the start of the blockquote
>
>> This is a nested blockquote
> This is the middle
>
> This is the end of the blockquote

**NOTE: YOU CAN ALSO USE BLOCKQUOTES WITH OTHER FORMATS LIKE SO:**

```
> ### A Generic Title Header
>
> - Unlisted Number 1
> - Unlisted Number 2
>
>  *Some italicized font* and **bold text** with ***bold and italicized text***
```

> ### A Generic Title Header
>
> - Unlisted Number 1
> - Unlisted Number 2
>
>  *Some italicized font* and **bold text** with ***bold and italicized text***

<p align="right">
  <a href="#table-of-contents">
    <kbd> 🔺 Return to Table of Contents</kbd>
  </a>
</p>

## Code

Sometimes we just need to put in a bit of code in our documentation, or need to highlight an important word as a command.

**If you use the backtick "`" before and after the word, you can denote a word or phrase as code** like so:

```
Please type the command `Hello World!`
```

Please type the command `Hello World!`

You can also use HTML's code function like so:

```
Please type the command <code>Hello World!</code>
```

Please type the command <code>Hello World!</code>

**NOTE: TO ESCAPE BACKTICKS, USE TWO OF THEM AT THE START AND END LIKE SO:**

```
`` Be careful of `ESCAPING` backticks! ``
```

`` Be careful of `ESCAPING` backticks! ``

***OR***

```
<code> Be careful of `ESCAPING` backticks!</code>
```

<code> Be careful of `ESCAPING` backticks!</code>

<p align="right">
  <a href="#table-of-contents">
    <kbd> 🔺 Return to Table of Contents</kbd>
  </a>
</p>

### Code Blocks

If you notice how I always put the syntax in code boxes, it's quite simple: **just put three backticks ``` at the start and end of your code** like so:


<img width="400" height="120" alt="Code Block" src="https://github.com/user-attachments/assets/78362924-a1cd-40c3-b911-9bae60d3a997" />

```
Example code goes here
  You can format it any way you like
        !@//As long as you close the three backticks
```

<p align="right">
  <a href="#table-of-contents">
    <kbd> 🔺 Return to Table of Contents</kbd>
  </a>
</p>

## Links

Links are the easiest way to direct someone to resources, an external website, or your own works and projects. To add a link, simply **put some text inside some [] *square brackets*, followed by the *URL* in () *parenthesis*** like so:

```
[Here is a Special Present for You, Please Click Here](https://youtu.be/dQw4w9WgXcQ)
```

[Here is a Special Present for You, Please Click Here](https://youtu.be/dQw4w9WgXcQ)

**DONT'T FORGET TO HOLD *CTRL* WHEN CLICKING OR HIT BACK**

<p align="right">
  <a href="#table-of-contents">
    <kbd> 🔺 Return to Table of Contents</kbd>
  </a>
</p>

### Adding Titles

You can also add little title highlights that leave little messages and notes when you highlight over links. To do this, **add some *""* quotation marks with the title** like so:

```
[Here is a Special Present for You, Please Click Here](https://youtu.be/dQw4w9WgXcQ "You totally should click this")
```

[Here is a Special Present for You, Please Click Here](https://youtu.be/dQw4w9WgXcQ "You totally should click this")


<p align="right">
  <a href="#table-of-contents">
    <kbd> 🔺 Return to Table of Contents</kbd>
  </a>
</p>

### URLs and Email Addresses

You can also link to someone's email address or your own so whoever clicks on it goes straight to their email program along to quickly link things. To do so, **use the *< >* closed brackets followed like the text**, like so: 

```
<https://theuselessweb.com>
<statefarmfireclaims@statefarm.com>
```

<https://theuselessweb.com>
<statefarmfireclaims@statefarm.com>

<p align="right">
  <a href="#table-of-contents">
    <kbd> 🔺 Return to Table of Contents</kbd>
  </a>
</p>

### Formatting Links

If you want to, you can mix in some formatting with your links. 

**EXAMPLE 1:**

```
First you should click on **[THIS LINK](https://youtu.be/jE-6n4dO95A?t=11)**
Then you should click on *[THIS LINK](https://youtu.be/jEI3N9kIyP4?t=7)*
Then finally, click on[`THIS LINK`](#this-link)







THIS LINK
[CLICK HERE FOR THE THIRD VIDEO](https://youtu.be/Fx7eZItF8u0)
```

First you should click on **[THIS LINK](https://youtu.be/jE-6n4dO95A?t=11)**  
Then you should click on *[THIS LINK](https://youtu.be/jEI3N9kIyP4?t=7)*  
Then finally, click on [`THIS LINK`](#this-link)  

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
 
### THIS LINK
[CLICK HERE FOR THE THIRD VIDEO](https://youtu.be/Fx7eZItF8u0)

<p align="right">
  <a href="#table-of-contents">
    <kbd> 🔺 Return to Table of Contents</kbd>
  </a>
</p>

### Reference style Links

There is also a function to make links somewhat more readable in an academic style of referencing links. That way, it can make it a bit neater and add some accessibility if you need to add a quick link. The way that it's structured is in two parts: the text with a number, and then the actual link itself

To set up the first part of the Reference-style links, **make four [] *square brackets*, fill the text in one, and the number in the other.** For example:

```
[The Meaning of Life] [1]
```
Then for the next part, you need to **format two [] *square brackets* followed by : *colon* with the URL. All of the following formats can be applied:**

```
[1]: https://youtu.be/aboZctrHfK8
[1]: https://youtu.be/aboZctrHfK8 "The Meaning of Life"
[1]: https://youtu.be/aboZctrHfK8 'The Meaning of Life'
[1]: https://youtu.be/aboZctrHfK8 (The Meaning of Life)
[1]: <https://youtu.be/aboZctrHfK8> "The Meaning of Life"
[1]: <https://youtu.be/aboZctrHfK8> 'The Meaning of Life'
[1]: <https://youtu.be/aboZctrHfK8> (The Meaning of Life)
```

When you put it altogether, it should look something like this:

```
Have you ever wondered about the Meaning of Life? Well, click across to find out what [The Meaning of Life][the-meaning-of-life] truly is!

[the-meaning-of-life]: https://youtu.be "The Meaning of Life"

```

Have you ever wondered about the Meaning of Life? Well, click across to find out what [The Meaning of Life][the-meaning-of-life] truly is!

[the-meaning-of-life]: https://youtu.be "The Meaning of Life"

<p align="right">
  <a href="#table-of-contents">
    <kbd> 🔺 Return to Table of Contents</kbd>
  </a>
</p>

## Images

As the old adage goes:

*A picture is worth a thousand words*

And sometimes, it's just nice to add pretty little pictures to your GitHub project, repository, or documentation. Or you simply need a screenshot.

To add an image, **Add an "!" exclamation mark with some alt text in [], and the URL inside the () followed by a title in "" quotation marks** like so:

![Grumpy Cat](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS17tGThNGO41sKEI3iGzLnvY_PjAj3v-p0zPPMedaqgo0TWcOZQipS9WZ8&s=10 "Grumpy Cat")

Now you are probably thinking ***"This picture is way too big! How do I fix it?!"***

Not to worry. All you have to do is **copy paste the image into your markdown and let the code generate. Once it generates, just adjust the numbers of the *height* and *width* and if you want, add a *paragraph* tag with the *center* function, like so:**

```
<p align="center">
<img width="250" height="350" alt="Grumpy Cat" src="https://github.com/user-attachments/assets/6291ab4b-4ac5-480e-bd04-eb50df17f7ed" />
</p>
```

<p align="center">
<img width="250" height="350" alt="Grumpy Cat" src="https://github.com/user-attachments/assets/6291ab4b-4ac5-480e-bd04-eb50df17f7ed" />  
</p>

<p align="center">
<em><strong></strong>and Voilà, a Centered Grumpy Cat</em> 
</p>

<p align="right">
  <a href="#table-of-contents">
    <kbd> 🔺 Return to Table of Contents</kbd>
  </a>
</p>

### Linking Images

You can also use images to link to an external website by clicking on them. However, the process can be a little messy on Markdown. Here, I will try to break down the syntax line by line:

```
OPEN THE FIRST SQUARE BRACKET
[
! <----------- EXCLAMATION MARK GOEX NEXT
[ALT TEXT GOES HERE]
(URL OF IMAGE OR CODE OF COPY PASTED IMAGE GOES HERE
"TITLE GOES HERE")
CLOSE THE FIRST SQUARE BRACKET
]
(URL HYPERLINK GOES HERE)
```
Now let's put an actual example here:

```
[![FREE CANDY](https://i.imgur.com/Qp0keUz.png "FREE CANDY")](https://i.imgur.com/geoNYwt.png)
```

**NOTE: YOU WILL NEED TO HOLD DOWN *CNTRL* WHEN CLICKING SO YOU CAN OPEN A NEW TAB. OR MAKE SURE TO HIT THE BACK BUTTON IF YOU CLICK BELOW**

[![FREE CANDY](https://i.imgur.com/Qp0keUz.png "FREE CANDY")](https://i.imgur.com/geoNYwt.png)

So after clicking the image, I'm sure you can see two issues with this:

1. The image is too big, taking up too much space
2. You cannot edit the size of the image with Markdown, but that changes the whole syntax

As with most other situations, you can fix this using HTML format instead of GitHub markdown. Breaking it down, it looks like this:

```
<p align="center"> <------- TYPE THIS FIRST
<a href="URL OF THE WEBPAGE LINK GOES HERE"> <----- THIS WILL OPEN THE HYPERLINK
    THE COPY-PASTED GITHUB IMAGE CODE GOES BELOW HERE (WITH WIDTH AND HEIGHT ADDED)
    <img width="NUMBER" height="NUMBER" alt="ALT TEXT GOES HERE" src="GITHUB UPLOADED IMAGE URL GOES HERE" title="HOVER TITLE GOES HERE"/>
  CLOSE THE HYPERLINK ANCHOR TAG
  </a>
CLOSE THE HTML PARAGRAPH TAG
</p>
```

You use the same *paragraph center align* function along with linking with *a href*. With the new example being like so:

```
<p align="center">
  <a href="https://i.imgur.com/geoNYwt.png"> 
    <img width="300" height="300" alt="FREE CANDY" src="https://i.imgur.com/Qp0keUz.png" title="FREE CANDY"/>
  </a>
</p>
```
<p align="center">
  <a href="https://i.imgur.com/geoNYwt.png"> 
    <img width="300" height="300" alt="FREE CANDY" src="https://i.imgur.com/Qp0keUz.png" title="FREE CANDY"/>
  </a>
</p>

**REMEMBER TO HOLD DOWN *CNTRL* OR HIT THE BACK BUTTON AFTER CLICKING**

<p align="right">
  <a href="#table-of-contents">
    <kbd> 🔺 Return to Table of Contents</kbd>
  </a>
</p>


## Lists

Lists are an incredibly useful way to have certain points organized in either bullet points, numbers, or hyphens when making a checklist or multiple factors/conditions to your explanation and documentation.

### Ordered Lists

To make an ordered list with numbers, simply **type the number 1 followed by a "." then press Enter once you are finished.** The text will automatically keep numbering until you delete the number. Like so:

```
1. Ordered List 1
2. Ordered List 2
3. Ordered List 3
4. Ordered List 4
5. Ordered List 5
```
1. Ordered List 1
2. Ordered List 2
3. Ordered List 3
4. Ordered List 4
5. Ordered List 5

You can also use HTML's ordered list function like so:

```
<ol>
  <li> Ordered List 1 </li>
  <li> Ordered List 2 </li>
  <li> Ordered List 3 </li>
  <li> Ordered List 4 </li>
  <li> Ordered List 5 </li>
</ol>
```

<ol>
  <li> Ordered List 1 </li>
  <li> Ordered List 2 </li>
  <li> Ordered List 3 </li>
  <li> Ordered List 4 </li>
  <li> Ordered List 5 </li>
</ol>

<p align="right">
  <a href="#table-of-contents">
    <kbd> 🔺 Return to Table of Contents</kbd>
  </a>
</p>

### Unordered Lists

To make an unordered list with hyphens, simply **type the - hyphen, + plus sign, or asterisk, then press Enter once you are finished.** The text will automatically keep numbering until you delete the hyphen. Like so:

```
- Unordered List 1
- Urordered List 2
- Unordered List 3
- Urordered List 4
- Unordered List 5

+ Unordered List 6
+ Urordered List 7
+ Unordered List 8
+ Urordered List 9
+ Unordered List 10

* Unordered List 11
* Urordered List 12
* Unordered List 13
* Urordered List 14
* Unordered List 15
```
- Unordered List 1
- Urordered List 2
- Unordered List 3
- Urordered List 4
- Unordered List 5

+ Unordered List 6
+ Urordered List 7
+ Unordered List 8
+ Urordered List 9
+ Unordered List 10

* Unordered List 11
* Urordered List 12
* Unordered List 13
* Urordered List 14
* Unordered List 15

You can also use HTML's unordered list function like so:

```
<ul>
  <li> Unordered List 1 </li>
  <li> Unordered List 2 </li>
  <li> Unordered List 3 </li>
  <li> Unordered List 4 </li>
  <li> Unordered List 5 </li>
</ul>
```

<ul>
  <li> Unordered List 1 </li>
  <li> Unordered List 2 </li>
  <li> Unordered List 3 </li>
  <li> Unordered List 4 </li>
  <li> Unordered List 5 </li>
</ul>

**NOTE: IF YOU WISH TO HAVE NUMBERS IN AN UNORDERED LIST, USE THE FORWARDSLASH \ TO ESCAPE THE NUMBER AND "."**

```
- 1984\. A warning to humanity
- Privacy is a human right to all of our society
```

- 1984\. A warning to humanity
- Privacy is a human right to all of our society

<p align="right">
  <a href="#table-of-contents">
    <kbd> 🔺 Return to Table of Contents</kbd>
  </a>
</p>

## Adding Elements in Lists

Sometimes you may want to combine other elements in lists such as paragraphs, blockquotes, code blocks, images, or even nested lists. In order to add elements, **be sure to hit SPACE 4 times OR hit TAB ONCE**

Here is how you add each element:

### Paragraphs in Lists

```
* This is the first list item
* This is second list item

  This is a paragraph

* Here is the third list item
* Here is the fourth list item
```

* This is the first list item
* This is second list item

  This is a paragraph

* Here is the third list item
* Here is the fourth list item

<p align="right">
  <a href="#table-of-contents">
    <kbd> 🔺 Return to Table of Contents</kbd>
  </a>
</p>

### Blockquotes in Lists

```
* The first part of the list
* The second part of the list
 > This is a blockquote inserted inside of the list
* The third part of the list
* The fourth part of the list
```

* The first part of the list
* The second part of the list
 > This is a blockquote inserted inside of the list
* The third part of the list
* The fourth part of the list

<p align="right">
  <a href="#table-of-contents">
    <kbd> 🔺 Return to Table of Contents</kbd>
  </a>
</p>

### Code Blocks in Lists

```
  <html>
    <head>
    </head>
  </html>
```

 <html>
    <head>
    </head>
  </html>

<p align="right">
  <a href="#table-of-contents">
    <kbd> 🔺 Return to Table of Contents</kbd>
  </a>
</p>

### Nested Lists

Nested lists have some variety to them. You can do it like this:

```
1. Ordered List 1
2. Ordered List 2
3. Ordered List 3
    - Unordered List 1
    - Unordered List 2
4. Ordered List 4
```
1. Ordered List 1
2. Ordered List 2
3. Ordered List 3
    - Unordered List 1
    - Unordered List 2
4. Ordered List 4

**OR**

```
- Unordered List 1
- Unodered List 2
- Unordered List 3
    1. Ordered List 1
    2. Ordered List 2
- Unordered List 4
```
- Unordered List 1
- Unodered List 2
- Unordered List 3
    1. Ordered List 1
    2. Ordered List 2
- Unordered List 4

**OR, WITH HTML***

```
<ol>
  <li>Ordered List 1</li>
  <li>Ordered List 2</li>
  <li>Ordered List 3</li>
    <ul>
      <li>Unordered List 1</li>
      <li>Unordered List 2</li>
    </ul>
  <li>Ordered List 4</li>
</ol>
```
<ol>
  <li>Ordered List 1</li>
  <li>Ordered List 2</li>
  <li>Ordered List 3</li>
    <ul>
      <li>Unordered List 1</li>
      <li>Unordered List 2</li>
    </ul>
  <li>Ordered List 4</li>
</ol>

**OR**

```
<ul>
  <li>Unordered List 1</li>
  <li>Unordered List 2</li>
  <li>Unordered List 3</li>
    <ol>
      <li>Ordered List 1</li>
      <li>Ordered List 2</li>
    </ol>
  <li>Unordered List 4</li>
</ul>
```
<ul>
  <li>Unordered List 1</li>
  <li>Unordered List 2</li>
  <li>Unordered List 3</li>
    <ol>
      <li>Ordered List 1</li>
      <li>Ordered List 2</li>
    </ol>
  <li>Unordered List 4</li>
</ul>

<p align="right">
  <a href="#table-of-contents">
    <kbd> 🔺 Return to Table of Contents</kbd>
  </a>
</p>

## Horizontal Rules

You have the option to also create a sort of divider between sections. To create the divider,<strong>you can use either three \*\*\* *asterisks*, three --- *hyphens* or three ___ *underscores*</strong>. All will have the same output, like so:

```
First

***

Second

---

Third

___
```

First

***

Second

---

Third

___

<p align="right">
  <a href="#table-of-contents">
    <kbd> 🔺 Return to Table of Contents</kbd>
  </a>
</p>

## Tables

If you want to have that extra bit of organization, you can create tables in Markdown. It is a little tricky to do, as you need to <strong>make combinations of the | *pipe* key (Shift + forwardslash) and -- *hyphens**. The -- *hyphens* make up the horizontal lines while the | *pipes* make up the vertical lines.</strong> Let me show you an example:

```
| Table 1 | Table 2 | Table 3 |
| -------- | -------- | -------- |
| Table 1A | Table 2A | Table 3A |
| Table 1B | Table 2B | Table 3B |
| Table 1C | Table 2C | Table 3C |
| Table 1D | Table 2D | Table 3D |
```

| Table 1 | Table 2 | Table 3 |
| -------- | -------- | -------- |
| Table 1A | Table 2A | Table 3A |
| Table 1B | Table 2B | Table 3B |
| Table 1C | Table 2C | Table 3C |
| Table 1D | Table 2D | Table 3D |

Notice how it automatically changes colors for the title headers and zebra stripes the rows for easier reading. Convenient, huh?

<p align="right">
  <a href="#table-of-contents">
    <kbd> 🔺 Return to Table of Contents</kbd>
  </a>
</p>

## Escaping Characters

Sometimes you need to use a character that is reserved for a function. To use it as text, **simply use the \ *back slash* along with the character next to it with no spaces**. These are all the characters you can escape:

```
\	backslash
`	backtick (see also escaping backticks in code)
*	asterisk
_	underscore
{ }	curly braces
[ ]	brackets
< >	angle brackets
( )	parentheses
#	pound sign
+	plus sign
-	minus sign (hyphen)
.	dot
!	exclamation mark
| pipe
```

Adding a \ *back slash* to each would make it display like so:

```
\\	backslash
\`	backtick (see also escaping backticks in code)
\*	asterisk
\_	underscore
\{ \}	curly braces
\[ \]	brackets
\< \>	angle brackets
\( \)	parentheses
\#	pound sign
\+	plus sign
\-	minus sign (hyphen)
\.	dot
\!	exclamation mark
\| pipe
```

\\	backslash  
\`	backtick (see also escaping backticks in code)  
\*	asterisk  
\_	underscore  
\{ \}	curly braces  
\[ \]	brackets  
\< \>	angle brackets  
\( \)	parentheses  
\#	pound sign  
\+	plus sign  
\-	minus sign (hyphen)  
\.	dot  
\!	exclamation mark  
\| pipe

<p align="right">
  <a href="#table-of-contents">
    <kbd> 🔺 Return to Table of Contents</kbd>
  </a>
</p>

## Conclusion

Congratulations! You made it to the end of the tutorial! Good job! Hopefully now you have mastered the fundamentals of GitHub Markdown and some useful HTML tricks as well. Good for you! Remember, you can always use this README as a quick reference if you ever forget anything. I tried to make it as easy to read as possible along with quickly being able to jump around each subsection or return back to the table of contents. Of course, you can always use CTRL + F to quickly find things as well if need be. *Variety is the Spice of Life*, after all.

Now go out there and start making your GitHub documentation look great!

<p align="center">
  <img src="https://media1.tenor.com/m/NII7Z9YQLsMAAAAC/go-for-it-you-can-do-it.gif" alt="You can do it!">
</p>

## Resources

Here are some resources you can use if you are more curious or need more information. **HOLD CTRL WHILE CLICKING**:

- [Basic Syntax Markdown Guide](https://www.markdownguide.org/basic-syntax/) - The entire basis of what I based my GitHub tutorial on. I tried to condense and TLDR it while making it more functional and accessible to beginners
- [Intermediate/Advanced Syntax](https://www.markdownguide.org/extended-syntax/) - This is some more advanced stuff if you'd like to do more complicated things in GitHub Markdown
- [Live Interactive Markdown Tutorial](https://www.markdowntutorial.com/) - This is more of a live, interactive tutorial if you don't wish to read everything or do everything together step-by-step
- [A Comprehensive Guide to Getting Started on GitHub](https://docs.github.com/en/get-started/start-your-journey/what-is-github) - Incredibly useful and detailed guide that I thought I would link here as a handy dandy resource

<p align="right">
  <a href="#introduction">
    <kbd> 🔺 Return to Top</kbd>
  </a>
</p>
