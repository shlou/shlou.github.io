---
layout: default
title:  "Markdown Tutorial"
date:   2018-11-08 12:59:42 +0800
categories: tutorials
---

## 1. Italics and Bold

To make a phrase italic in Markdown, you can surround words with an underscore (_ ).

Writing in Markdown is _not_ that hard!

Similarly, to make phrases bold in Markdown, you can surround words with two asterisks ( ** )

>I **will** complete these lessons!

Of course, you can use _both italics and bold_ in the same line. You can also span them **across multiple words**.

>"**Of course**," she whispered. Then, she shouted: "All I need is a little moxie!"

For the final exercise in this lesson, we're going to make some words bold and italic. In general, it doesn't matter which order you place the asterisks or underscores.

>If you're thinking to yourself, _**This is unbelievable**_, you'd probably be right.

## 2. Headers

To make headers in Markdown, you preface the phrase with a hash mark (#). You place the same number of hash marks as the size of the header you want. 

>
# Header one
## Header two
### Header three
#### Header four
##### Header five

You can't really make a header bold, but you can italicize certain words.

###### _Header six_

## 3. Links

There are two different link types in Markdown, but both of them render the exact same way. 

The first link style is called an inline link.

>Search for it.[Visit GitHub!](www.github.com)

You can add emphasis to link texts, if you like.

>[You're **really, really** going to want to see this.](www.dailykitten.com)

You can make links within headings, too.

> 
#### The Latest News from [the BBC](www.bbc.com/news)

The other link type is called a reference link. An advantage of the reference link style is that multiple links to the same place only need to be updated once.

>
Do you want to [see something fun][a fun place]?  
Well, do I have [the website for you][another fun place]!  

[a fun place]: www.zombo.com
[another fun place]: www.stumbleupon.com

## 4. Images

Images also have two styles, just like links, and both of them render the exact same way. The difference between links and images is that images are prefaced with an exclamation point ( ! ).

The first image style is called an inline image link. 

>
![A representation of Octdrey Catburn](http://octodex.github.com/images/octdrey-catburn.jpg)

For a reference image, you'll follow the same pattern as a reference link. 

>
[The first father][First Father]  
[The second first father][Second Father]

[First Father]: http://octodex.github.com/images/founding-father.jpg
[Second Father]: http://octodex.github.com/images/foundingfather_v2.png

## 5. Blockquotes

To create a block quote, all you have to do is preface a line with the "greater than" caret (>). 

I read this interesting quote the other day:

>"Her eyes had called him and his soul had leaped at the call. To live, to err, to fall, to triumph, to recreate life out of life!"

You can also place a caret character on each line of the quote. This is particularly useful if your quote spans multiple paragraphs. Block quotes can contain other Markdown elements, such as italics, images, or links.

## 6. Lists

There are two types of lists in the known universe: unordered and ordered. 

To create an unordered list, you'll want to preface each item in the list with an asterisk ( * ).

>
* Flour
* Cheese
* Tomatoes

An ordered list is prefaced with numbers, instead of asterisks. 

>
1. Cut the cheese
2. Slice the tomatoes
3. Rub the tomatoes in flour

Occasionally, you might find the need to make a list with more depth, or, to nest one list within another. All you have to do is to remember to indent each asterisk one space more than the preceding item. If need nested list inside a blockquotes, the nested list item should start with 3 spaces.

>* Calculus 
>   * A professor
>   * Has no hair
>   * Often wears green
>* Castafiore
>   * An opera singer
>   * Has white hair
>   * Is possibly mentally unwell

Suppose you want to create a bullet list that requires some additional context (but not another list). 

>1. Crack three eggs over a bowl.
>
>    Now, you're going to want to crack the eggs in such a way that you don't make a mess.
>
>    If you _do_ make a mess, use a towel to clean it up!
>
>2. Pour a gallon of milk into the bowl.
>
>    Basically, take the same guidance as above: don't be messy, but if you are, clean it up!
>
>3. Rub the salmon vigorously with butter.
>
>    By "vigorous," we mean a strictly vertical motion. Julia Child once quipped:
>  > Up and down and all around, that's how butter on salmon goes.
>4. Drop the salmon into the egg-milk bowl.
>
>    Here are some techniques on salmon-dropping:
>
>    * Make sure no trout or children are present
>    * Use both hands
>    * Always have a towel nearby in case of messes

## 7. Paragraphs

If you forcefully insert a new line, you end up breaking the togetherness. This is what's known as a hard break; what our poetry asks for is a soft break. You can accomplish this by inserting two spaces after each new line.

>
Do I contradict myself?  
Very well then I contradict myself,  
(I am large, I contain multitudes.)

Aside from formatting poetry, one of the common uses for these soft breaks is in formatting paragraphs in lists.

>
1. Crack three eggs over a bowl.  
 Now, you're going to want to crack the eggs in such a way that you don't make a mess.  
 If you _do_ make a mess, use a towel to clean it up!
2. Pour a gallon of milk into the bowl.  
 Basically, take the same guidance as above: don't be messy, but if you are, clean it up!