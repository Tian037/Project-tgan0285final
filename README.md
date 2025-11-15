# Project-tgan0285-final
Creative Coding – Individual Variation

⸻

Individual Variation – User Input
For my individual extension, I implemented a mouse-based User Input interaction that allows the viewer to “pick up” apples once they fall to the ground.

When an apple reaches the "landed" state, it remains on the ground instead of resetting to its original position.
In mousePressed(), the mouse coordinates are converted into the 600×800 design space, and the program checks whether the click falls within the radius of a landed apple. If so, the apple is removed from the array and the counter variable pickedCount increases by one.

A live counter (“Picked Apples”) is displayed in the upper-right corner of the screen to give immediate feedback.
This creates a playful experience of collecting apples one by one and demonstrates the required User Input method.

⸻

How to Run
	1.	Open index.html in any browser.
	2.	Press SPACE to flip gravity.
	3.	Click fallen apples to pick them up.

⸻

Technologies
	•	p5.js
	•	JavaScript
	•	HTML / CSS

⸻

Author
Tian Gan – IDEA9103 Creative Coding
