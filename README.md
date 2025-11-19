# typsting

`typsting` - a Typst typesetting game.

## Requirements

You need to have `chafa`, `trap`, `typst`.

## Usage

1. You need to create a file (`formulas.typ` by default) and write formulas to it.
2. Make script executable and just run it:
```bash
chmod +x typsting
./typsting
```

## Hacking

1. To replace a default filepath (`formulas.typ`), you need to change `FILEPATH` variable.
2. To replace default fail counts (5), you need to change `fails` variable.

## Typst requirements (and formula format)

For correct formula rendering you need to follow the following format:
```typst
$ formula $
```

For multiple formulas:
```typst
$ formula1 $
$ formula2 $
```
