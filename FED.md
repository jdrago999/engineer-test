
# FED Exercise

## Questions:

## Using JSFiddle.com and Mocky.io:

* Make 4 buttons:
  1. Dark Red - "Button 1"
  2. Light Blue - "Button 2"
  3. Orange - "Button 3"
  4. Medium Gray - "Button 4"
* Responsive:
  - Desktop = all on same row
  - Tablet = two rows of two buttons, in a 2x2 grid
  - Mobile = four rows, one button each row, filling entire row
* Behavior:
  - All buttons: On hover, highlight unless disabled.
  - Button 1: On click, unless we already have, make a JSONP request to http://www.mocky.io/v2/55f067dac4e7b4450d7a6b5f
    - Store the results in memory, to be used later.
    - If `success` is `true`, display the results as a list of 3 columns sorted by price in descending order.
  - Button 2: On click, unless we already have, make a JSONP request to the same address:
    - Store the results in memory, to be used later.
    - If `success` is `true`, display the results as a list of 3 columns sorted by location name in ascending order.
  - Button 3: On click, show/hide results.
  - Button 4: On click, enable/disable buttons 1 and 2.
