+++
title = "Hello:"
author = ["Wan Ardie Mejia"]
draft = false
+++

## A website detailing all of my personal .org files {#a-website-detailing-all-of-my-personal-dot-org-files}

**How  does one publish to a website directly from Emacs org mode (with the help of [hugo](https://gohugo.io/)?)**

-   With the help of [ox-hugo](https://ox-hugo.scripter.co/)

**What are some of the advantages of doing so?**

-   It doesnt interfere with the flow of your thoughts when using Emacs

**Here is an actual copy of the same org file used to produce this website**

```org
#+AUTHOR: Wan Ardie Mejia
#+TITLE: A promising attempt at publishing a website from org-mode
#+OPTIONS: toc:nil
#+EMAIL: wan_ahmad_ardie@yahoo.com
#+hugo_base_dir: /home/ardie/Documents/pulledFromWebsite/my_firstOrgWebsite
#+TAGS: theory practical
* Hello:
:PROPERTIES:
:EXPORT_FILE_NAME: _index
:EXPORT_HUGO_SECTION: /
:END:
** My new shiny website published "directly" from my personal .org files
 - /So it doesnt interfere with the flow of my thoughts when using Emacs/
 - /All generated from my personal org files/
 - /All I have to do is type something like this:/
#+INCLUDE: ./static/indexSnippet.org src org
/... and type C-c C-e H A and it publishes to the entire "project" with the help of Emacs ox-hugo package/
```

-   I then only type Ctl-c Ctl-e H A and it auto-publishes to an entire Hugo-compatible tree structure, which is ready to published online.
-   The most easiest (and fastest) process of creating a static site I have tried so far
