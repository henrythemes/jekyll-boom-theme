# What's `jekyll-boom-theme`?

It's a jekyll starter theme for books using boom! - a microformat for books.


## What's Boom!

Boom! is a microformat - a series of conventions and best practices - first published in 
the article titled _Printing a Book with CSS: Boom!_ by Bert Bos, Håkon Wium Lie in November 2005.

> HTML and CSS, two of our favorite acronyms, are normally associated with web pages. And deservedly so:
> HTML is the dominant document format on the web and CSS is used to style most HTML pages. But, are they suitable for off-screen use?
> Can CSS be used for serious print jobs? To find out, we decided to take the ultimate challenge: to produce 
> the next edition of our book [(ed. note) Cascading Style Sheets - Designing for the Web]
> directly from HTML and CSS files. In this article we sketch our solution and quote from the style sheet used. Towards the end we
> describe the book microformat (boom!) we developed in the process.

[Find out more »](http://alistapart.com/article/boom)


## Live Demo

See a live demo @ [`henrythemes.github.io/jekyll-boom-theme` »](http://henrythemes.github.io/jekyll-boom-theme)




## Boom! Build & Update Notes

to be done


### Sections

```
A book consists of different types of sections. We propose to use
DIV elements with these class names:

    frontcover
    halftitlepage: contains the title of the book
    titlepage: contains the title of the book, name of author(s) and publisher
    imprint: left page with copyright, publisher, library printing information
    dedication: right page with short dedication
    foreword: written by someone other than the author(s)
    toc: table of contents
    preface: preface, including acknowledgements
    chapter: each chapter is given its own DIV element
    references: contains list of references
    appendix: each appendix is given its own 
    bibliography
    glossary
    index
    colophon: describes how the book was produced
    backcover

   A book will use several of the types listed above, but few books
   will use all of them.
```


### More Themes

See the [Dr. Jekyll's Themes](https://drjekyllthemes.github.io) directory.

### More Quick Starter Wizard Scripts

See the [Mr. Hyde's Scripts](https://github.com/mrhydescripts/scripts) library.


## Meta

**Questions? Comments?**

Post them to the [wwwmake forum](http://groups.google.com/group/wwwmake). Thanks!
