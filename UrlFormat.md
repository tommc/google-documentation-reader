## URL Format ##
URLs for documentation reader pages begin with `http://code.google.com/docreader/` and then have a token passed as a query parameter or fragment (with a "#" or a "?") to specify what you want to view. This section explains what it all means, and how you can construct URLs to get the documents you want to see.  We expect this process to get easier in future releases, but this should be helpful for your understanding.

### Specifying your projects ###
First, specify one or more projects that you want to read about, with the `p` parameter. For example, this URL lists two projects, `google-web-toolkit-doc-1-5` and `google-web-toolkit-incubator`.
```
http://code.google.com/docreader/#p=google-web-toolkit-doc-1-5,google-web-toolkit-incubator
```

### Selecting a project ###
Next, if you've got more than one project listed under `p`, specify the "selected project" with the parameter `s`. Parameters are separated with a `&`, as you would expect.
This URL loads Google Web Toolkit 1.5 and the GWT Incubator, and selects the latter.

```
http://code.google.com/docreader/#p=google-web-toolkit-doc-1-5,google-web-toolkit-incubator&s=google-web-toolkit-incubator
```

### Picking a page ###
Finally, to view a particular page, use the `t` parameter, for "topic". This specifies the "FastTree" page in the `google-web-toolkit-incubator` project.

```
http://code.google.com/docreader/#p=google-web-toolkit-doc-1-5,google-web-toolkit-incubator&s=google-web-toolkit-incubator&t=FastTree
```

If you want, instead, to bookmark a search query, use `q` instead of `t`:
```
http://code.google.com/docreader/#p=google-web-toolkit-doc-1-5,google-web-toolkit-incubator&s=google-web-toolkit&q=eclipse
```