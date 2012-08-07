# Decrypt
This program takes over the screen, prints flickering random characters and slowly makes the piped content (or input file) visible. Effectively, it does what hackers on tv-shows have.

## Examples

Do this for example:
```tree ~/Downloads | ./decrypt.py```

or
```jp2a my_favourite_cat.jpg --term-width | ./decrypt.py```



## Use cases:

Recover some friends hard drive (i.e.: he destroyed his mbr). After the "hard" work has been done, act like you are having a hard time and run some of his personal files through this program and ask if he recognizes the content.

Awesomeness guaranteed.


## Remarks

Warning: keeps the entire input in memory and uses an O(n^2) algorithm. It is not efficient cpu/ram wise. Easy rewrite is possible but this is just for fun.