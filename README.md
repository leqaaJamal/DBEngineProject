In this project we've built a small database engine that supports indixing with B+ and R trees.
We are using R trees for polygons and B+ trees for integers, booleans, Strings, etc.. 
We used the implementation of the B+ tree to make an implementation for R tree, we also used the implementation of B+ tree
from this source: https://github.com/AhmadElsagheer/DBMS/tree/master/SagSolheeriman-A1/src/BPTree , and we modified some
things in that implementation as it was not taking into considartion input with duplicates data, so we modified it to be able
to deal with duplicates
