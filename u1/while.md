## Aufgabe 1: WHILE Programme

### Syntactic sugar
Wir definieren folgenden Syntactic sugar:

`x3 := x1 - x2` ist eine Kurzschreibweise für:
	
	x4 := x1
	x5 := x2
	WHILE x2 ≠ 0 DO
		x4 := x4 - 1
		x5 := x5 - 1
	END	
	x3 := x4


### Programm 1: (x, y) -> x DIV y

	x0 := 0
	IF x2 ≠ 0 DO
		WHILE x1 ≠ 0 DO
			x1 := x1 - x2
			x0 := x0 + 1
		END
	END

### Programm 2: (x, y) -> x MOD y

	x0 := x1
	WHILE x1 ≠ DO
		x0 := x1
		x1 := x1 - x2
	END
Anmerkung: für y = 0 terminiert das Programm nicht.
