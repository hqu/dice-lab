# Classroom Dice Lab

A small simulation for a classroom exercise: 100 students each roll two dice five times.

- **Histogram:** each student's total across all ten dice.
- **Scatter plot:** the sum of die 1 (x) against the sum of die 2 (y), one dot per student.
- **Two bias scenarios** (switches in the top right, with an explanation on hover):
  - *Rich get richer:* if a student's first roll totals more than 10, any later die showing a 1 or 2 is re-rolled once.
  - *Gender bias:* students 1-50 are male, 51-100 are female; each die a female student rolls has 0.5 subtracted.

Switching a scenario reuses the same rolls, so you compare the same class. "Roll a new class" generates fresh dice.

Open `index.html` in a browser. No build step. Fonts load from Google Fonts when online.
