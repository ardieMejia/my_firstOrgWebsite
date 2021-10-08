+++
title = "7) How does one go about installing Emacs/Spacemacs/Doom Emacs and what not?"
author = ["Wan Ardie Mejia"]
draft = false
+++

-   <https://github.com/syl20bnr/spacemacs>
    -   The only link you'll need to start using Spacemacs.
-   Basically the process to install all variants of Emacs are the same (even when they look completely different!).
    -   You install the base Emacs
    -   You install the init folder (basically configuration folder). This is where the real magic of Spacemacs (and in Doom Emacs) happens, where your base program will read this config file everytime it starts, thereby producing a completely different program (depending on the config).
    -   This modification is highly robust (as you will discover that, if you accidentally deleted this config folder (.emacs.d), base Emacs will simply start as default classic and painful Emacs)
    -   Theres some more stuff going in the background. But this is good enough to understand
    -   It will look like this:

{{% spacamacsDiagram1 %}}

-   My version of emacs is 25.3.2. I recommend you install something later than 25.1 to "get with the times". Just a suggestion. (No, in fact, MAKE SURE above 25.1)
    -   Ubuntu 14.04's package manager does not have an updated Emacs. So I found this repository Kevin Kelley.
    -   Instructions can be found [here](https://ubuntuhandbook.org/index.php/2017/04/install-emacs-25-ppa-ubuntu-16-04-14-04/)\`
    -   Or just copy this (same thing):

<!--listend-->

```bash
sudo add-apt-repository ppa:kelleyk/emacs
sudo apt-get update
sudo apt-get install emacs25
```
