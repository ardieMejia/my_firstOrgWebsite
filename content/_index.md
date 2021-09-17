+++
title = "Hello:"
author = ["Wan Ahmad Ardie bin spiderman"]
draft = false
+++

## My new shiny website published "directly" from my personal .org files {#my-new-shiny-website-published-directly-from-my-personal-dot-org-files}

-   _So it doesnt interfere with the flow of my thoughts when using Emacs_
-   _All generated from my org files_
-   _All I have to do is type something like this:_

    ```org
    ​* Heading1
    :PROPERTIES:
    :EXPORT_FILE_NAME: somefilename
    :EXPORT_HUGO_SECTION: directoryname
    :CUSTOM_ID: someID
    :END:
    ** Subheading1
    ​ - Lorem Ipsum has been the industry's standard dummy text ever since the 1500s,
    when an unknown printer took a galley of type and scrambled it to make a type
    specimen book. It has survived not only five centuries, but also the leap into
    electronic typesetting, remaining essentially unchanged.
    ```

_... and type C-c C-e H A and it publishes to the entire "project" with the help of Emacs ox-hugo package_
