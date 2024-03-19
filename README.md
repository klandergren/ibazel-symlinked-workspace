# ibazel-symlinked-workspace

## usage

On MacOS, travel to the workspace via the symlink:

```
cd holder/my-project
ibazel run //:simple
```

and then edit `simple.sh` to print a different message. `ibazel` does not detect
these changes and does not rebuild.

Note: the detection may not work at all or work inconsistently.
