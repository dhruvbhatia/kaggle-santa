Kaggle 2013 Holiday Competition: Packing Santa's Sleigh
============

### Description
This is a <a href="http://julialang.org/">Julia</a> port of the MATLAB sample solution.

*A Naive Approach:
One possible approach would be to place the boxes in order going from top to bottom.  This will have the advantage of having 0 penalty for the ordering part of the metric, however the total height will likely not be very good.  To do this, we'll start by filling presents along the x-direction.  Once there's no more room in the x-direction, we increment
the y-direction.  Once there's no more room in the y-direction, we increment the z-direction.*

### How to use
- Save `presents.csv` in `data/`
- Run `solution.ji`
- Your solution will be saved as `data/output.csv` and your evaluation metric score will be printed.

### Evaluation score
This solution yields a score of **5,270,836**

### Links
<a href="http://www.kaggle.com/c/packing-santas-sleigh" target="_blank">Kaggle Competition page</a><br>
<a href="https://www.kaggle.com/c/packing-santas-sleigh/forums/t/6570/julia-port-of-matlab-sample-solution" target="_blank">Kaggle Forum post</a><br>
<a href="http://dhruvbhatia.com" target="_blank">My site</a>
