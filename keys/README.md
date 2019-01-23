first word (2byte) for each button, dependent on selector position.

```
          /=------ PRESS ----=\         /=------ RELEASE -----=\
SELECTOR  left    middle  right
          07FE    0BFE    OFFE          0480      0880      0C80
YELLOW    05FE    09FE    0DFE          0480      0880      0C80
BLUE      07EE    0BEE    0FEE          0480      0880      0C80
ORANGE    07DE    0BDE    0FDE          0480      0880      0C80
GREEN     07BE    0BBE    0FBE          0480      0880      0C80
RED       06FE    0AFE    0EFE          0480      0880      0C80
CLOUD     07F6    0BF6    0FF6          0480      0880      0C80
BALL      07FA    0BFA    0FFA          0480      0880      0C80
purple    07FC    0BFC    0FFC          0480      0880      0C80
ON->OFF   17FE    1BFE    1FFE          17FE      1BFE      1FFE
OFF->ON (console on)  nothing
OFF-ON  (console off) nothing, it doesn't wake up the console
LOCAL sw  nothing
```
