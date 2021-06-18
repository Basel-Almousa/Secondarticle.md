# **Introduction**
**This book has been written with two very
different types of people in mind:**  
1. Those who want to learn how to design and build websites from scratch.  
2. Anyone who has a website (that may be built using a content management system, blogging software, or an
e-commerce platform) and wants more control over the
appearance of their pages.
## Is it hard to Learn?
Many books that teach HTML and CSS
resemble dull manuals. To make it easier for
you to learn, we threw away the traditional
template used by publishers and redesigned
this book from scratch.
## The Structure of This Book: 
1. HTML  
We will spend the first chapter
looking at how HTML is used to
create web pages. You will see
that you start by writing down
the words you want to appear
on your page. You then add tags
or elements to the words so
that the browser knows what is
a heading, where a paragraph
begins and ends, and so on.
The rest of this section
introduces the tags you have
at your disposal to create web
pages, grouped into chapters on:
text, lists, links, images, tables,
forms, video audio and flash, and
miscellaneous elements.
I should warn you that the
examples in the first nine
chapters are not exciting to look
at, yet they are the foundation of
every web page. The following
chapters on CSS will show you
how to make your pages look a
lot more interesting.
2. CSS  
We start this section with a
chapter that explains how CSS
uses rules to enable you to
control the styling and layout
of web pages. We then go on to
look at the wide variety of CSS
properties you can use in your
CSS rules. These properties
generally fall into one of two
categories:
Presentation: How to control
things like the color of text, the
fonts you want to use and the
size of those fonts, how to add
background colors to pages (or
parts of a page), and how to add
background images.
Layout: How to control where
the different elements are
positioned on the screen. You
will also learn several techniques
that professionals use to make
their pages more attractive.
3. Practical  
We end up with some helpful
information that will assist you in
building better websites.
We look at some new tags that
will be introduced in HTML5 to
help describe the structure of
your pages. HTML5 is the latest
version of HTML (still under
development at the time of
writing). Before learning about
these elements, you need a good
grasp of how CSS is used to
control the design of web pages.
There is a chapter that talks you
through a design process that
you might like to follow when
creating a new website.
Finally, we end up looking at
topics that will help you once
you have built your site, such
as putting it on the web, search
engine optimisation (SEO) and
using analytics software to track
who comes to your site and what
they are looking at.
## How Websites Are Created?
- All websites use HTML and CSS, but content
management systems, blogging software, and
e-commerce platforms often add a few more
technologies into the mix.
## How the Web Works?
 **When you visit a website, the web server
hosting that site could be anywhere in the
world. In order for you to find the location of
the web server, your browser will first connect
to a Domain Name System (DNS) server.**  
1. When you connect to the web,
you do so via an Internet Service
Provider (ISP). You type a
domain name or web address
into your browser to visit a site;
for example: google.com,
bbc.co.uk, microsoft.com.  
2. Your computer contacts a
network of servers called
Domain Name System (DNS)
servers. These act like phone
books; they tell your computer
the IP address associated with
the requested domain name.
An IP address is a number
of up to 12 digits separated
by periods / full stops. Every
device connected to the web
has a unique IP address; it is
like the phone number for that
computer.  
3. The unique number that the
DNS server returns to your
computer allows your browser
to contact the web server
that hosts the website you
requested. A web server is a
computer that is constantly
connected to the web, and is set
up especially to send web pages
to users.  
4. The web server then sends the
page you requested back to your
web browser.  
# **Structure**
Many web pages act like electronic versions of these
documents. For example, newspapers show the same stories
in print as they do on websites; you can apply for insurance
over the web; and stores have online catalogs and e-commerce
facilities.
In all kinds of documents, structure is very important in helping
readers to understand the messages you are trying to convey
and to navigate around the document. So, in order to learn how
to write web pages, it is very important to understand how to
structure documents. In this chapter you will:  
- See how HTML describes the structure of a web page
- Learn how tags or elements are added to your document
- Write your first web page
# How Pages Use Structure?
- Think about the stories you
read in a newspaper: for each
story, there will be a headline,
some text, and possibly some
images. If the article is a long
piece, there may be subheadings
that split the story into separate
sections or quotes from those
involved. Structure helps readers
understand the stories in the
newspaper.  
- The structure is very similar
when a news story is viewed
online (although it may also
feature audio or video). This is
illustrated on the right with a
copy of a newspaper alongside
the corresponding article on its
website.  
- Now think about a very different
type of document — an
insurance form. Insurance forms
often have headings for different
sections, and each section
contains a list of questions with
areas for you to fill in details or
checkboxes to tick. Again, the
structure is very similar online.  
# Structuring Word Documents
- The use of headings and
subheadings in any document
often reflects a hierarchy of
information. For example, a
document might start with
a large heading, followed by
an introduction or the most
important information.
- This might be expanded upon
under subheadings lower down
on the page. When using a word
processor to create a document,
we separate out the text to give
it structure. Each topic might
have a new paragraph, and each
section can have a heading to
describe what it covers.
- On the right, you can see a
simple document in Microsoft
Word. The different styles for
the document, such as different
levels of heading, are shown
in the drop down box. If you
regularly use Word, you might
have also used the formatting
toolbar or palette to do this.
# Attributes Tell Us More About Elements
- Attributes provide additional information
about the contents of an element. They appear
on the opening tag of the element and are
made up of two parts: a name and a value,
separated by an equals sign.
# Code in a Content Management System
- If you are working with a content
management system, blogging
platform, or e-commerce
application, you will probably
log into a special administration
section of the website to control
it. The tools provided in the
administration sections of these
sites usually allow you to edit
parts of the page rather than
the entire page, which means
you will rarely see the <html>,
<head>, or <body> elements.
Looking at the content
management system on the
opposite page, you have a box
that allows you to enter a title
for the page, another box for the
main article, a way to enter a
publication date, and something
to indicate which section of the
site this page belongs in.
- For an e-commerce store, you
might have boxes that allow you
to enter a title for the product,
a description of the product, its
price, and the quantity available.
That is because they use a single
'template' to control all of the
pages for a section of the site.
(For example, an e-commerce
system might use the same
template to show all of their
products.) The information
you supply is placed into the
templates.
- The advantage of this approach
is that people who do not know
how to write web pages can
add information to a website
and it is also possible to change
the presentation of something
in the template, and it will
automatically update every page
that uses that template. If you
imagine an e-commerce store
with 1,000 items for sale, just altering one template is a lot
easier than changing the page
for each individual product.
- In systems like this, when
you have a large block of text
that you can edit, such as a
news article, blog entry or the
description of a product in an
e-commerce store, you will often
see a text editor displayed.
Text editors usually have
controls a little like those on
your word processor, giving
you different options to style
text, add links or insert images.
Behind the scenes these editors
are adding HTML code to your
text, just like the code you have
seen earlier in this chapter.
Many of these editors will have
an option that allows you to see
(and edit) the code that they
produce.
- Once you know how to read and
edit this code, you can take more
control over these sections of
your website.
- In the example above, you can
see that the text editor has a tab
for Visual / HTML views of what
the user enters. Other systems
might have a button (which
often shows angle brackets) to
indicate how to access the code.
Some content management
systems offer tools that also
allow you to edit the template
files. If you do try to edit
template files you need to check
the documentation for your CMS
as they all differ from each other.
You need to be careful when
editing template files because
if you delete the wrong piece of
code or add something in the
wrong place the site may stop
working entirely.
# Looking at How Other sites are Built
- When the web was first taking
off, one of the most common
ways to learn about HTML and
discover new tips and techniques
was to look at the source code
that made up web pages.
- These days there are many
more books and online tutorials
that teach HTML, but you can
still look at the code that a web
server sends to you. To try this
out for yourself, simply go to the
sample code for this chapter, at
www.htmlandcssbook.com/
code/ and click on the link called
"View Source."
- Once you have opened this
page, you can look for the View
menu in your browser, and select
the option that says Source or
View source. (The title changes
depending on what browser you
are using.)
- You should see a new window
appear, and it will contain the
source code that was used to
create this page.
- You can see this result in the
photograph on the right. The
page you see is the window at
the top; the code is below.
- At first this code might look
complicated but don't be
discouraged. By the time you
have finished the next chapter
of this book, you will be able to
understand it.
- All of the examples for this book
are on the website, and you can
use this simple technique on any
of the example pages to see how
they work.
- You can also download all of
the code for this book from the
same website by clicking on the
"Download" link.
# ** Extra Markup**
In EXTRA MARKUP, we will focus on some helpful topics that are
not easily grouped together. You will learn about:  
- The different versions of HTML and how to indicate which
version you are using
- How to add comments to your code
- Global attributes, which are attributes that can be used on
any element, including the class and id attributes
- Elements that are used to group together parts of the page
where no other element is suitable
- How to embed a page within a page using iframes
- How to add information about the web page using the
<meta> element
- Adding characters such as angled brackets and copyright
symbols
# The Evolution of HTML
> 
>
*Since the web was first created, there have
been several different versions of HTML.*
- **HTML 4**  
**Released 1997**  
With the exception of a few
elements added in HTML5
(which have been highlighted),
the elements you have seen in
this book were all available in
HTML 4.
Although HTML 4 had some
presentational elements to
control the appearance of pages,
authors are not recommended to
use them any more. (Examples
include the <center> element
for centering content on a
page, <font> for controlling
the appearance of text, and
<strike> to put a line through
the text — all of these can be
achieved with CSS instead.)
- **XHTML 1.0**  
**Released 2000**  
In 1998, a language called XML
was published. Its purpose
was to allow people to write
new markup languages. Since
HTML was the most widely used
markup language around, it was
decided that HTML 4 should be
reformulated to follow the rules
of XML and it was renamed
XHTML. This meant that
authors had to follow some new,
more strict rules about writing
markup. For example:  
1. Every element needed a
closing tag (except for empty
elements such as <img />).
2. Attribute names had to be in
lowercase.
3. All attributes required a value,
and all values were to be
placed in double quotes.
4. Deprecated elements should
no longer be used.
5. Every element that was
opened inside another
element should be closed
inside that same element.
- **HTML5**  
**Released 2000**  
In HTML5, web page authors do
not need to close all tags, and
new elements and attributes will
be introduced. At the time of
writing, the HTML5 specification
had not been completed, but
the major browser makers had
started to implement many of
the new features, and web page
authors were rapidly adopting
the new markup.
Despite the fact that HTML5
is not yet completed, you can
safely take advantage of the
new features of the language as
long as you endeavour to ensure
that users with older browsers
will be able to view your pages
(even though some of the extra
features will not be visible to
them).  
> -- *Jon Duckett*