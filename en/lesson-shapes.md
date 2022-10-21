# Drawing shapes


Using a library...

```py
from joy import *
```

Draw a circle

```py
circle()
```

Circle is drawn with its center at (0, 0), that is at `x=0` and `y=0`.

The above command is same as `circle(x=0, y=0)`. Try it!

### Change the center of circle

```py
circle(x=25)
```

This moves the circle 25 units towards positive X-axis (horizontally).

### Change direction of circle center

It can go the other direction as well.

```py
circle(x=-25)
```

### Move the circle center vertically

```py
circle(y=25)
```

It can go the other direction as well.

```py
circle(y=-25)
```

### Change x, y center coordinates

```py
circle(x=25, y=25)
```

Supported shapes:
- `circle()`
- `rectangle()`
- `line()`
- `ellipse()`
