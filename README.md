# guile-turtle
A simple example on how to embed Guile Scheme to C using a simple “Tortoise” graphics program

## Requirements
1. [Guile](https://www.gnu.org/software/guile/)
2. [Gnuplot](http://www.gnuplot.info/)

## How to run

```bash
	make
	./turtle
```

## Commands
```
guile> (tortoise-move 1)
guile> (tortoise-turn 90)
guile> (tortoise-penup)
guile> (tortoise-move 5)
guile> (tortoise-pendown)
guile> (tortoise-move 1)
guile> (tortoise-reset)
```

### Note
If it complains about default terminal just export `GNUTERM=x11` or `qt`
