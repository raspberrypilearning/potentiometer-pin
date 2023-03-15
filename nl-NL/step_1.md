Importeer Pot uit de picozero-bibliotheek en stel vervolgens de pinnen in voor een potentiometer, gebruik daarbij de volgende code:

--- code ---
---
language: python filename: line_numbers: false line_number_start: 1
line_highlights:
---
from picozero import Pot

dial = Pot(0) # Connected to pin A0 (GP_26) --- /code ---
