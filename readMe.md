This was done as part of a coding assignment for Spiridonov Polytechnic LLC

Acceptance Criteria
When I open the page, I see the following items
A number input field with no value, labeled "Filter Max"
A number input field with no value, labeled "Threshold Max"
A single-column table with
a header row containing the text "Value"
body with rows/cells that contain the following values
7
12
18
20
3
88
When I click the header ("Value") of the table
the table values are sorted in the ascending order
If I click the header of the table again, the sort order of the values in the table is toggled (so if the current order is ascending, then after the click, it should be descending and vice versa)
When I enter in a value for the "Filter Max" input
the table values greater than the value I've specified are not shown
If I remove the value for the "Filter Max" input,
all the values are shown
When I enter in a value for the "Threshold Max" input
the text of the table values greater than the value I've specified is colored red (text of values that do not meet the criteria remains the default color - black)
If I remove the value for the "Threshold Max" input,
all the text of the table values returns to the default color (black)