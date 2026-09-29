START

  // ---------- STEP 1: LOAD THE DATASET ----------
  OPEN the data file
  IF the file won't open THEN
      SHOW an error message and STOP
  END IF
  LOOK at the first few rows to make sure it loaded right
  COUNT how many rows and columns there are

  // ---------- STEP 2: CLEAN THE DATA ----------
  // 2a. Remove duplicates
  DELETE any rows that appear more than once

  // 2b. Handle missing values
  FOR EACH column
      IF a number is missing THEN fill it with the middle value (median)
      IF a word/category is missing THEN fill it with "Unknown"
  END FOR

  // 2c. Fix formatting
  MAKE sure numbers are stored as numbers and dates as dates
  MAKE text consistent (e.g., "ny" and "NY" both become "NY")

  // 2d. Handle outliers
  LOOK for values that are way too high or too low
  IF a value is clearly a mistake THEN fix or remove it

  // 2e. Double-check
  MAKE sure values make sense (e.g., no negative ages)

  // ---------- STEP 3: CALCULATE SUMMARY STATISTICS ----------
  FOR EACH number column
      FIND the average, middle value, smallest, and largest
      FIND how spread out the values are (standard deviation)
  END FOR
  FOR EACH category column
      COUNT how often each category appears
  END FOR

  // ---------- STEP 4: CREATE A VISUALIZATION ----------
  PICK a chart that fits your question:
      how values are spread out      → histogram
      comparing groups               → bar chart
      change over time               →
