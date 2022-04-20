<h1>_Order Of Growth_</h1>



_A function  f(x)  is  said  to  be  growing  faster  than   g(x)_   if

            lim (n->infinite)   f(n)/g(n)  =  infinite 
            _OR_
            lim (n->infinite)   g(n)/f(n)  =  zero 

<h2>__Direct Way__</h2>



1. Ignore lower order forms;

2. Ignore leading constant;


<h3> How to Know which terms are of lower order ? </h3>

<b>_(c) < <b>(log(log n))</b> < <b>(log n)</b> <<b> (n^(1/3))</b> < <b>(n^(1/2))</b><<b> (n)</b> < <b>(n^2)</b> < <b>(n^3)</b> < <b>(n^4)</b> < <b>(2^n) </b> < <b>(n^n)_</b>

## Notation 

**Big O** -> Represents exact bound or upper Bound. 

**Theta** -> Represents exact bound.

**Omega** -> Represents exact or lower bound. (opposite of Big O).


Used for space and time Complexity for notation.

We only consider for worst cases for calculating TC.





_IMP POINTS_

1. If f(n) = Ω(g(n));

            then g(n) = O(f(n));

     Why this ? Because g(n) is lower or equal to f(n)
      and second expression means f(n) is upper or equal to      g(n);
Both have same meaning .


2. If f(n) = Θ(g(n)


            then f(n) = O(g(n) and f(n) = Ω(g(n))
            and g(n) = O(f(n) and g(n) = Ω(f(n).


