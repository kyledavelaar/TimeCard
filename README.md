# Clock In / Clock Out Desktop App

## FEATURES
- calculates how many hours worked each day and week
- Saves csv of hours to your machine so you can reference in the future
- if you forget to click login/logout you can manually change your hours for the week


## TODO
  - take [ms, ms] times per day and render them as form inputs
  - convert HH:MM to ms date and save them back into the [ms, ms]

  - csv
    - create/save csv in filesystem
    - let user choose location of where save

  - determine when new day starts: date == MM/dd/YYYY (date != prevDate)
    - reset timeWorkedToday = 0
    -

  - determine when new week (day == monday)
    - save csv of last weeks values
    - if multiple weeks have passed, set those weeks as blank csvs
    - reset timeWorkedInWeek = 0
    - clear saved values for that weeks clock in/out

  - user closes app without logging out
    - before close:
      - if clockedIn
        - clockOut User
