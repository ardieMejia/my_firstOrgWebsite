+++
title = "Syntax (arrays)"
author = ["Wan Ardie Mejia"]
draft = false
+++

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
