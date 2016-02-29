# Getting Started #
The documentation reader is intended to provide a great interface for technical users
browsing wiki documentation in Google Code project hosting.  In addition to the free search navigation
you would expect from Google, it offers traditional table-of-contents and index
keyword navigation.  Moreover, it is convenient:
  * [for project owners](TipsForAuthors.md), it is easy to set projects up for use in the documentation reader,
  * [for authors](TipsForAuthors.md), it is easy to write, edit, and organize documentation pages, and most of all
  * [for readers](TipsForReaders.md), it is easy not only to navigate the documentation of a given project, but also to collect documentation on a set of projects, to build a customized "reference library" of exactly the materials you actually use.  Searches are confined to this set of documentation, neither showing non-documentation results nor results from irrelevant projects.


# The screen #

The screen is divided into three basic areas: the upper header bar, the
left-side navigation bar with tabs for "Contents" and "Index," and the main
viewing area.  Let's take a look at each in turn.

First of all, in the header area, the "Help" link shows a pop-up of the various
keyboard shortcuts.  It is possible to use the keyboard to do anything in the documentation reader...a small point, perhaps, but one that can make an experienced user far faster and more productive.

![http://google-documentation-reader.googlecode.com/svn/wiki/images/headerbar.png](http://google-documentation-reader.googlecode.com/svn/wiki/images/headerbar.png)

Next, on the left hand side, is a navigation area.  The image shows that with
the "Contents" tab selected; we'll show the "Index" tab a bit later.  The
Contents view shows a tree representation of the tables of contents for each
project (here, we have two visible).  Again, keyboard navigation should work
properly, and you can easily move between looking at one project and then at
another.  Click any of the links, and the display area will update to show the
page you asked for.  Click on the small "+" and "-" buttons to expand or
collapse the tree.  With the keyboard, up/down navigate, enter selects, and
left/right arrows collapse and expand.

If you find the navigation area takes up too much screen space, you can
collapse it by clicking anywhere in the vertical bar containing the
"![http://google-documentation-reader.googlecode.com/svn/wiki/images/collapse.png](http://google-documentation-reader.googlecode.com/svn/wiki/images/collapse.png)" icon.

![http://google-documentation-reader.googlecode.com/svn/wiki/images/navcontents.png](http://google-documentation-reader.googlecode.com/svn/wiki/images/navcontents.png)

Finally, in the viewing area, we have the documentation currently being
displayed.  In the top right corner, the "Print" link is always available; the
"Edit" link is available only to members of the project, and provides a fast
route to edit the wiki page (for example, to immediately correct the typo an
editor just noticed on the page).  Under the blue separator line, a
"breadcrumbs" row identifies where in the table of contents this page is
organized, making it easy to go up to a parent node and then down to siblings
even if the navigation area is collapsed.

And, of course, the main documentation itself will usually contain links.  Most
links will go to other documentation sections, and will also cause the
selection in the Contents tab to be updated.  Other links will leave the documentation for some other site -- no worries, though, you can always hit "back" to come back to your previous state.  In the case here, it takes you to another site showing running example code.

![http://google-documentation-reader.googlecode.com/svn/wiki/images/viewing.png](http://google-documentation-reader.googlecode.com/svn/wiki/images/viewing.png)


# Searches #
Results of a "Search Contents" search are automatically restricted only to
documentation results.  Because the documentation reader has additional
information from the table of contents, we can also provide more information
in the search results, compared to what an ordinary web search can display: we
give the actual title of the page rather than the wiki word of its entry, and
the breadcrumbs to the page provide a link not only to the result page with
your search term, but to other containing sections as well.

![http://google-documentation-reader.googlecode.com/svn/wiki/images/search-screenshot.png](http://google-documentation-reader.googlecode.com/svn/wiki/images/search-screenshot.png)

# Using the Index #

The index is a collection of useful search terms put together by the what the authors of a given project. When you select the Index tab in the navigation area, you see a list of index links. Clicking one of those will run a search for that term exactly as though you
had typed it into the search box in the header area.

The value of the index is that it _suggests_ search terms you might not think to look for.  If you are looking for a concept but don't know what it is called, try looking in the index. You may find something interesting, even if you _do_ have some ideas of search terms for a free-text search!

The box labelled "Filter" above the keywords is useful when you have a very
large index, especially one from multiple projects merged together.  If you
type something in the filter box, the index list will adjust to show only
those index terms containing the string you have typed, as shown below.  To get
back to the entire list, just delete the filter string.

![http://google-documentation-reader.googlecode.com/svn/wiki/images/indexfilter.png](http://google-documentation-reader.googlecode.com/svn/wiki/images/indexfilter.png)