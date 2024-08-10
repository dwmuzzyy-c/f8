Scenario: Creating a Two-Column Layout with a Clearfix
Imagine you want to create a simple two-column layout where the left column contains some text and the right column contains an image. 
Below these columns, you want a footer section that starts on a new line, below both columns.

Visual Representation:
+---------------------------+
| Left Column | Right Column|
|             |             |
|             |             |
+---------------------------+
|         Footer            |
+---------------------------+

Floating Columns:
The .left-col is floated to the left, taking up 50% of the container’s width.
The .right-col is floated to the right, also taking up 50% of the container’s width.
This creates a two-column layout where the left column contains text and the right column contains an image.
Clearing Floats:
The .footer has the clear: both; property. This ensures that the footer starts on a new line, below both floated columns. Without this, the footer might appear next to the floated elements instead of below them.