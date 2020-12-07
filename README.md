# CircuitPython
 The follwing files are my first foray into CircuitPython.
## Table of Contents
* [Table of Contents](#TableOfContents)
* [Hello_CircuitPython](#Hello_CircuitPython)
* [CircuitPython_Servo](#CircuitPython_Servo)
* [CircuitPython_LCD](#CircuitPython_LCD)
---

## Hello_CircuitPython

### Description & Code
Description goes here

Here's how you make code look like code:

```python
import board
import neopixel
import time

dot = neopixel.NeoPixel(board.NEOPIXEL, 1)

while True:
    print("Make it blue!")
    dot.fill((0,0,255))
    time.sleep(.5)
    print("Make it turquoise")
    dot.fill((0,229,238))
    time.sleep(.5)

```


### Evidence

### Images

### Reflection

## CircuitPython_Servo

### Description & Code

```python
Code goes here

```

### Evidence

### Images

### Reflection


## CircuitPython_LCD

### Description & Code

```python
Code goes here

```

### Evidence

### Images

### Reflection

