# reddit-blaster
Simple script to quickly mass-edit all of your Reddit comments and posts. 

This script requires Python 3 to run. It was developed using Python 3.10 but should still work with older versions of 3.x (pre-3.6 not recommended). 

# Usage
When running the script, you will first be prompted for an API key, which can be generated [here](https://google.com). 

The script will then ask if you want to [e]dit, [a]ppend, or [p]repend your comments with additional content. 

## Edit
Using this option will overwrite all of your comments entirely with the content supplied.

```
This is a comment!
```
*would become...*
```
New content added here!
```

## Append
Using this option will append a new line, followed by the supplied content, to all of your comments.

```
This is a comment!
```
*would become...*
```
This is a comment!

New content added here!
```

## Prepend
Behavior is identical to Append, but will add it before the original comment. 

```
This is a comment!
```
*would become...*
```
New content added here!

This is a comment!
```
