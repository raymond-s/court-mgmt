Court Management
========================

Motivation
-----------
One of my friends on the badminton club was handling people on court hours through a physical collection of tags and a large whiteboard to represent who plays when. It was a slight hassle to bring to badminton everytime so I was asked to attempt to make a program to do it for us.

Dashboard
----------

Example dashboard:
![dashboard](https://cloud.githubusercontent.com/assets/10290698/20338042/9a234120-aba2-11e6-8ec5-ccedafc0fea6.png)

How it works
--------------
Dropdown menu in the top right corner has all recorded Membership IDs and matching tags on record. Selecting from this menu and push the tag into the TagID textbox for you to make any modifications (if you want to group people).

Can manually input other and custom tags in the TagID textbox to be sorted into the groups.

Tags in the dropdown menus that have a ? prefix means I was unable to determine which skill group the player belongd in. If said players come during court hours please note down what they are when you put them in and let me know of those corrects so I can fix them.

{ . } { ; } { * } are used to identify players as beginner, intermediate, and advanced skill level respectively.

Appending any other symbol (or digit, for that matter) will place that Tag into the Group category. Repeat the symbols for players who want to play together.

Clicking on the +Beginner, +Intermediate, +Advance, or +Group will append the first person from the top of the respective group into that group.

Clicking on the Court # will clear the court and put players back into the waitlist in their respective skill group.

Clicking directly on a player grid will take remove that player from this session's waitlist 

Clicking the TIMER will put on a timer until the next court change. Timer takes into account of people coming to check court placement so timer starts at a bit less than 15 minutes.

Click the "CLICK ME FOR AN UPDATING WAITLIST HEH" at the beginning to initialize some functions to fun continuously and keep the waitlists updating as you place and remove players.

Further clarification can be received by contacting the author (Raymond).

Notes
------------
No persistant storage. Information that is currently available is manually added in as a part of the "database" but cannot be editted directly.

Updates in the "database" will need to go through the author (Raymond) to be adjusted.