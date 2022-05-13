## High Level Test Cases
|TEST ID| DESCRIPTION| EXPECTED I/P| EXPECTED O/P| ACTUAL O/P| STATUS|
| :-----|:-----------|:------------|:------------|:------------|:------------|
|HL01|check if the BUTTON is pressed|program execution|Microcontroller/Engine starts|LED ON(RED)| PASS|
|HL01|check if the BUTTON is pressed|program execution|	WIPER starts|LED ON(BLUE)| PASS|
|HL01|check if the BUTTON is pressed|program execution|	WIPER starts|LED ON(GREEN)| PASS|
|HL01|check if the BUTTON is pressed|program execution|	WIPER starts|LED ON(ORANGE)| PASS|
|HL01|check if the BUTTON is pressed|-|Microcontroller/Engine stops|LED TURNED OFF| PASS|


## Low Level Test Cases

|TEST ID| DESCRIPTION| EXPECTED I/P| EXPECTED O/P| ACTUAL O/P| STATUS|
| :-----|:-----------|:------------|:------------|:------------|:------------|
|HL01|check if the BUTTON is pressed|program execution|Microcontroller/Engine starts|LED ON(RED)| PASS|
|HL01|check if the BUTTON is pressed|program execution|WIPER starts and speed of wiper is slow	|LED ON(BLUE)| PASS|
|HL01|check if the BUTTON is pressed|program execution|WIPER starts and speed of wiper is moderate	|LED ON(GREEN)| PASS|
|HL01|check if the BUTTON is pressed|program execution|WIPER starts and speed of wiper is good|LED ON(ORANGE)| PASS|
|HL01|check if the BUTTON is pressed|-|Microcontroller/Engine stops|LED TURNED OFF| PASS|
