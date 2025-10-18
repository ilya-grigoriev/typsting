# typsting

`typsting` - a Typst typesetting game.

## Requirements

You need to have `chafa`, `trap`, `typst`.

## Hacking

1. To replace a default filepath (`formulas.typ`), you need to change `FILEPATH` variable.
2. To replace default fail counts (5), you need to change `fails` variable.

## Typst requirements

For correct formula rendering you need to follow the following format:
```typst
$ formula $
```

For multiple formulas:
```typst
$ formula1 $
$ formula2 $
```
