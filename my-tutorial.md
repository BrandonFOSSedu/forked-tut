## Suspicious Crates 

```blocks
player.say(":)")
```

# Suspicious Crates
Help Wonder Woman navigate through the crates and find the missing painting piece. Search each one and if she finds the missing puzzle piece, have her break the box to get it.

I'm an update that won't be on main site!

```blocks
player.say(":)")
```


```ghost
player.onChat("run", function () {
    if (ww.locatePainting(Direction.Forward)) {
        ww.retrievePainting(Direction.Forward)
        ww.moveWW(Direction.Forward, 0)
    }
    for (let index = 0; index < 4; index++) {
        
    }
    while (!(false)) {
        
    }	
})
```
