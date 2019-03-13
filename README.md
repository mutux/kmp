# KMP Knuth–Morris–Pratt string search algorithm implemented in Python

String algorithm for fun! Detailed information can be found on my blogger [MuTuX](http://www.mutux.com/2017/04/17/string-agorothms-kmp-in-python.html "mutux's blog on text mining").

## Examples

```
if __name__ == "__main__":
    kmp('abcbabca','abcbabcabcbabcbabcbabcabcbabcbabca')

    kmp('abab','ababcabababc')
```

## Results
```
========================================================
[-1, 0, 0, 0, 0, 1, 2, 3, 1]
0 7
15 22
26 33
[-1, 0, 0, 1, 2]
0 3
5 8
7 10

```

## Finally
Have fun!
