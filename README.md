Updating the text file so that its content are as follows allowed me to reproduce the issue locally.

```txt
Equal and possible
6                           6
X                           0

Equal and possible
6                           6
X                           X

Equal and possible
6                           6
X                           XX

Equal and possible
6                           6
XX                          XXXX

Equal and possible
6                           11
XX                          X

Equal and possible
6                           11
X                           0

Equal and impossible
6                           11
0                           0

Equal and possible
6                           11
XXXXXX                      X

!Equal and impossible
6                           11
XXXXXX                      0

Equal and possible
10                          11
X                           0

!Equal and impossible
11                          6
0                           XXXXXX

possible
11                          6
X                           XXXXXXX

possible
11                          6
X                           XXX

!Equal and impossible
11                          10
X                           XXX

!Equal and impossible
11                          10
0                           0

Equal and impossible
4                           5
XX                          0
```
