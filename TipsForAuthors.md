# Authoring Documentation #
How can you start using the documentation reader for _your_ docs?  It turns out to be pretty easy.

Your project must be hosted on code.google.com, of course. You may already be using the wiki feature for your project; that's great! All of the pages that you'll display with the documentation reader are stored in your project wiki. The documentation reader actually already works with any wiki hosted on code.google.com. However, to provide a coherent documentation structure, you can define a special wiki page named TableOfContents.

## TableOfContents: providing documentation structure ##
The TableOfContents page on your wiki should have a nested structure of bulleted lists (using the space-indented "`*`" wiki markup). It may also have some preamble text if you want. Each entry in the nested list is an entry in the table of contents; the list nesting defines sections and sub-sections. Here's an example TableOfContents for a fictional project, which has wiki pages Introduction, WhyUse, GettingStarted, HowItWorks, NonStandardSupport, and FAQ. Note that "Technical Notes" is just the header for a section, not a wiki page.

```
$PP_OFF
#summary TOC for the FooBar WhizBang

= Introduction =
FooBar WhizBang is an integrated solution for developing things.
It supports most standards, and will likely make you more popular.

  * [Introduction Introduction to WhizBang]
    * [WhyUse Why use WhizBang?]
    * [GettingStarted Getting Started with WhizBang]
  * Technical Notes
     * [HowItWorks How does WhizBang work?]
     * [NonStandardSupport Support for nonstandard situations]
  * [FAQ FAQ]
```

In general, table of content entries will be links, using markup syntax like this:

`  * [WikiWord Title for Wiki Word entry] `

This will create a section titled "Title for Wiki Word entry," and linking to the content on the wiki page WikiWord.  You may, optionally, have entries that are not links, with markup like this:

`  * Title for a section heading without its own wiki entry `

Which will, as the title suggests, make an entry which is the heading of a collection of other entries, but for which there is no content in the wiki.  To display these nodes, the documentation reader will create a page that consists only of the title and a list of the available children.

## Index: suggesting search terms ##
The other special wiki entry is named Index. If present, it should be a flat bulleted list of index terms.  The documentation reader will collect and collate the index terms for all the projects displayed; when a user selects an index term, the reader will search for any pages containing that term and display the results.  This is equivalent to the user typing a search keyword, but may be useful if the user doesn't know what term to search for, or if the user is (as some of us do) browsing the index itself for interesting items.

## Editing content ##
Project members browsing documentation that they have rights to edit will see an "Edit" link will appear on the top-right of the interface, next to the Print icon. Clicking on the Edit link brings the user to the wiki editing page for that topic, allowing a rapid find/edit/save cycle to fix documentation errors and to update for advances in your project.

## Reorganizing content ##
Content may be reorganized at any time by revising the TableOfContents or Index pages.  There is no analog to the Edit link for these more structural changes, however: go to the wiki edit page in the regular Google Code project hosting interface.