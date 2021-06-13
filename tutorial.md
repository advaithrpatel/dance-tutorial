# tutorial
# Dance Tutorial

## Step 1

Create a function.

```blocks
function.Dosomething
```
## Step 2

Rename it as 'dance'    

```blocks
function.dance
```

## Step 3

Add following code

```blocks
function Dance() {
 basic.showLeds(`
        . # # # .
        . # # # .
        # . # . #
        . # # # .
        . . # . .
        `)
    basic.pause(100)
    basic.showLeds(`
        . # # # .
        . # # # .
        . . # . .
        # # # . .
        . . # . .
        `)
    basic.pause(100)
    basic.showLeds(`
        . # # # .
        . # # # .
        . . # . .
        . . # # #
        . . # . .
        `)
    basic.pause(100)
    basic.showLeds(`
        . # # # .
        . # # # .
        . . # . .
        # # # # #
        . . # . .
        `)
}
```

## Step 4

Create another function.

```blocks
function.dance2
```

## Step 5
Add following code

```blocks
function dance2() {
    basic.showLeds(`
        . . # # #
        . . # # #
        . . . # .
        . # # # .
        . . . # .
        `)
    basic.pause(100)
    basic.showLeds(`
        . . # # #
        . . # # #
        . . . # .
        . . . # #
        . . . # .
        `)
    basic.pause(100)
    basic.showLeds(`
        . . # # #
        . . # # #
        . . . # .
        . # # # #
        . . . # .
        `)
}
```

## Step 6

Create another function.

```blocks
function.dance3
```

## Step 7

Add following code.

```blocks
function dance3() {
    basic.showLeds(`
        # # # . .
        # # # . .
        . # . . .
        # # . . .
        . # . . .
        `)
    basic.pause(100)
    basic.showLeds(`
        # # # . .
        # # # . .
        . # . . .
        . # # # .
        . # . . .
        `)
    basic.pause(100)
    basic.showLeds(`
        # # # . .
        # # # . .
        . # . . .
        # # # # .
        . # . . .
        `)
}
```

## Step 8

Call all three functions.
Try it out on your micro:bit.
```blocks
basic.forever(function on_forever() {
    Dance()
    dance2()
    dance3()
})
```

Congratulations , you did it!