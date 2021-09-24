+++
title = "Hello:"
author = ["Wan Ardie Mejia"]
draft = false
+++

## My new shiny website published "directly" from my personal .org files {#my-new-shiny-website-published-directly-from-my-personal-dot-org-files}

-   _So it doesnt interfere with the flow of my thoughts when using Emacs_
-   _All generated from my personal org files_
-   _All I have to do is type something like this:_

<!--listend-->

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

_... and type C-c C-e H A and it publishes to the entire "project" with the help of Emacs ox-hugo package_
