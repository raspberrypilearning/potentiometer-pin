Importe Pot depuis la bibliothèque picozero puis définis les broches d'un potentiomètre, utilise le code suivant :

--- code ---
---
language: python 
filename: 
line_numbers: false 
line_number_start: 1
line_highlights:
---
from picozero import Pot

cadran = Pot(0) # Connecté à la broche A0 (GP_26)

--- /code ---
