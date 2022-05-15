# HIGH LEVEL TEST CASES :

|Test ID |	Description |	Exp.i/p	| Exp.o/p |	Actual o/p |	Output |
|:-------|:-----------------|:----------|:--------|:---------------|:----------|
|`H_01`|	check if the BUTTON is pressed	|program execution|	Engine starts	|RED LED ON	|PASS|
|`H_02`|	check if the BUTTON is pressed	|program execution|	Wiper starts	|BLUE LED ON	|PASS|
|`H_03`|	check if the BUTTON is pressed	|program execution|	Wiper starts	|GREEN LED ON	|PASS|
|`H_04`|	check if the BUTTON is pressed	|program execution|	Wiper starts	|ORANGE LED ON	|PASS|
|`H_05`|	check if the BUTTON is pressed	|-----------------|	Engine stop	| LED OFF	|PASS|





# LOW LEVEL TEST CASES :
|Test ID |	Description |	Exp.i/p |	Exp.o/p	|Actual o/p	| Output|
|:-------|:-------------|:--------|:--------|:----------|:-------|
|`L_01`|	check if the BUTTON is pressed      |	program execution     |	Engine starts	| RED LED ON	                                  |PASS|
|`L_02`|	check if the BUTTON is pressed again|	program execution     |	Wiper starts and runs at 35% (slow)	| BLUE LED ON	      |PASS|
|`L_03`|	check if the BUTTON is pressed again|	program execution     |	Wiper starts and runs at 70%	(medium)| GREEN LED ON	      |PASS|
|`L_04`|	check if the BUTTON is pressed again|	program execution     |	Wiper starts and runs at 100% (fast)|ORANGE LED ON	    |PASS|
|`L_05`|	check if the BUTTON is pressed again|	-----------------     |	Engine stop	|  LED OFF                                  	  |PASS|
