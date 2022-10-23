# Drawing shapes


Using a library...

```py
from joy import *
```

Draw a circle

```py
c = circle()
show(c)
```

Circle is drawn with its center at (0, 0), that is at `x=0` and `y=0`.

The above command is same as `circle(x=0, y=0)`. Try it!

### Change the center of circle

```py
c = circle(x=25)
show(c)
```

This moves the circle 25 units towards positive X-axis (horizontally).

### Change direction of circle center

It can go the other direction as well.

```py
c = circle(x=-25)
show(c)
```

### Move the circle center vertically

```py
c = circle(y=25)
show(c)
```

It can go the other direction as well.

```py
c = circle(y=-25)
show(c)
```

### Change x, y center coordinates

```py
c = circle(x=25, y=25)
show(c)
```

Supported shapes:
- `circle()`
- `rectangle()`
- `line()`
- `ellipse()`
