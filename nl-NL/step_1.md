Importeer Pot uit de picozero-bibliotheek en stel vervolgens de pinnen in voor een potentiometer, gebruik daarbij de volgende code:

--- code ---
---
language: python 
filename: 
line_numbers: false 
line_number_start: 1
line_highlights:
---
from picozero import Pot

instelwiel = Pot(0) # Aangesloten op pin A0 (GP26)

--- /code ---
