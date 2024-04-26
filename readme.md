Functional requirements of the simple survey Vue app using in-DOM:

1. If the user enters “idk” (for ‘I don’t know’) into any of the text inputs, then a line of text should appear just above the button
   that says “Knight: AAAAAAAAHHHHHHHHHHH!!!. This should happen as soon as the last keypress event.
2. If the user provides 3 answers (> length 0) none of which are “idk”) then a line of text should appear just above the button
   that says “Bridgekeeper: Alright, off you go then”. This should happen as soon as the last keypress satisfying the condition.
3. When the “Go again” button is clicked, the 3rd question switches between the 2 options shown.

Constraints:

1. You need to complete this as an HTML file using the no build tools method as shown in the code walkthroughs.
2. No CSS should be included for this activity.
3. This has to be an entirely Vue implementation, no using vanilla JS DOM manipulation or low-level event handlers.
