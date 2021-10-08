+++
title = "Bash:"
author = ["Wan Ardie Mejia"]
draft = false
+++

## 1) Syntax (numbers and strings) {#article1}

-   <https://stackoverflow.com/questions/1362298/convert-floating-point-variable-to-integer>
    -   Displaying floating-point in a C-style (printf) manner. Very handy.
-   <https://stackoverflow.com/questions/19482123/extract-part-of-a-string-using-bash-cut-split>
    -   Complete and more elegant way to cut strings into pieces, other than turning it into arrays first.
-   <https://stackabuse.com/substrings-in-bash/>
    -   Some weird but useful ones of string manipulation
        -   using pipe (|) and cut -> | cut


## 2) Syntax (arrays) {#article2}

-   <https://opensource.com/article/18/5/you-dont-know-bash-intro-bash-arrays>
    -   basic array syntax
-   <https://linuxhint.com/use-ifs-in-bash/>
    -   very handy to remember this or keep in this tip close at hand. Dealing with arrays in loops. The site where I learnt this trick:

<!--listend-->

```bash
for i in *
do
    read -a myArray <<< "$i"
    echo ${myArray[1]}
done
```

-   <http://www.masteringunixshell.net/qa35/bash-how-to-print-array.html>
    -   how to print bash array


## 3) Syntax (functions) {#article3}

<https://ryanstutorials.net/bash-scripting-tutorial/bash-functions.php>

-   functions in Bash allows coder to treat the code like normal terminal usage. So, -- ls -- can have a (script scope) alias using function ls(){ #--some code }. And $1 has the same property.


## 4) Syntax (files and folder) {#article4}

<https://www.cyberciti.biz/faq/howto-check-if-a-directory-exists-in-a-bash-shellscript/>


## 5) Syntax (case statement, for loops, user input) {#article5}

<https://tldp.org/LDP/Bash-Beginners-Guide/html/sect%5F07%5F03.html>

-   case statements

<https://www.thegeekstuff.com/2011/07/bash-for-loop-examples/>

-   some VERY USEFUL bash for loops. Some VERY SIMPLE ones.

<https://askubuntu.com/questions/446156/pause-execution-and-wait-for-user-input>

-   wait for user input
