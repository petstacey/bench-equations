# Bench-Calculations

Script to produce Excel formulas to calculate bench levels for the next 4 weeks

## Use

Available flags

-column = start column (string) for calculation
-row = start row (int) for calculation
-weeks = number of weeks to derive formula for

```
./bin/linux/app -column=T -row=12 -weeks=52
```

or

```
make run
```

Thiw will run with defaults of column "T", row 12 and 52 weeks