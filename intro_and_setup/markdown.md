---
title: "Markdown"
author: "Albert"
output:
  github_document:
    toc: true
    toc_depth: 2
    fig_width: 5
    fig_height: 5
---

# Markdown tutorial

## What is Markdown? 

Markdown is a simple and lightweight markup language which is designed to be displayed on the web.

## How to use Markdown?

If you know how to type you know how to use Markdown! Writing with Mardown is the exact same task as writing in a text editor like Microsoft office. The only difference is that all the fancy buttons and options are removed and instead replaced with a series of image modifier commands that you can type to differentiate your text.

## Fancy editing

There are a ton of text modifiers you can use for Markdown. A long form instructional guide can be found [here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) while a shorter straight to the point version can be found [here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

Today we'll review the most important formatting commands you will need for most of your needs.

## The holy trinity

The holy trinity of markdown are headers, bolding, and links. Headers the simplest way to make sections pop, bold format allows you to emphasize important points, and links allow you to integrate your markdown documents into the web!

## Headers

Headers are very simple, all you need to do is add a # sign right before whatever text you want to make the header. Keep in mind the # must be on a new line (no text before it). The more #'s you add before the text, the smaller the header. For example here are a list of headers you can use ordered from largest to smallest.

```
# Largest
## Slightly less large
### Even less large
#### Even smaller
##### Smaller still
###### Smallest shown here (but you can go smaller!)
```

The reason why this did not register as a header is because I formatted it as a comment. By inserting three quotation marks before and after the block of text you wish to comment, it will not execute any formatting. Without the quotation marks here is what we get!

# Largest
## Slightly less large
### Even less large
#### Even smaller
##### Smaller still
###### Smallest shown here (but you can go smaller!)

## Bold

Bold is even easier than headers, all you need to do is add 2 * signs before and after whatever you want to bold.

```
**Whatever you want to bold**
```

And without comments:
**Whatever you want to bold**

## Links

Links are unfortunately not as easy. The format is as follows:
```
[What you want your link to say](Link you want to bring the user)
```
For example if I want to bring the user to www.google.com then replace the text in the parentheses and I would write
```
[What you want your link to say](www.google.com)
```
Without quotations it would be 
[What you want your link to say](www.google.com)

If want to change the text that my link shows up as I can just change what's in the square brackets.
```
[Here is my new text](www.google.com)
```
And of course, without the quotations:
[Here is my new text](www.google.com)

