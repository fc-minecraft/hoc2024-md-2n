### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Choose the costumes

## Step 1
Look at the lock to see what numbers it's displaying and then use the closet to find which costume pieces matche that number. Once you've matched them up, use the ``||hoc:head, body, and legs||`` block to open the lock.

#### ~ tutorialhint
The lock needs the ``||agent:Knight||`` costume to open. Set the head, body and legs to use the ``||agent:Knight||`` items.


```ghost
    hoc._costume_activity(HeadWear_Activity.Knight_Helmet, MidWear_Activity.Knight_Top, LowerWear_Activity.Knight_Legs)
```
```template     
    \\
```

```package
hoc2024-ts=github:ReWrite-Media/hoc2024-ts/n/costume#v0.0.112
```