# Age-Calculator
A simple Python program that calculates a person's age not just in years, but also in months and total days lived, using system date and leap year handling.

**Product Goal**: To build a user friendly script that converts a person's age in years into an exact breakdown of years, months, and days using precise calendar logic.

**Key Decision**: The logic incorporates Python’s built-in calendar.isleap() to accurately count leap years, ensuring correct day totals. Month lengths are computed manually for full control over leap year February handling.

**Safety Workflow:** User inputs (name and age) are taken as basic console input. The program uses the system’s local time to avoid manual date entry and prevent user errors related to dates.

**Outcome:** A lightweight, educational Python script that demonstrates date arithmetic, leap-year logic, and time module usage—ideal for beginners learning Python fundamentals and time-based calculations.
