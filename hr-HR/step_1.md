Import Pot from the picozero library then set the pins for a potentiometer, use the following code:

--- code ---
---
language: python filename: line_numbers: false line_number_start: 1
line_highlights:
---
from picozero import Pot

dial = Pot(0) # Connected to pin A0 (GP_26) --- /code ---
