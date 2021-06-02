# Forms
## Types of form controls:

1. ADDING TEXT:
- Password input
- Text area (multi-line)
- Text input (single-line) 

2. Making Choices:
- Radio buttons
- Checkboxes
- Drop-down boxes 

3. Submitting Forms:
- Submit buttons
- Image buttons (subscribe)

4. Uploading Files: 
- File upload

## Form Structure 
"<form" action="http://www.example.com/subscribe.php"
method="get">
"<p>" This is where the form controls will appear.
 "</p>"
  "</form>"

## Text Input
"<form" action="http://www.example.com/login.php">
"<p>"Username:
 "<input" type="text" name="username" size="15"
 maxlength="30" />
"</p>
"</form>"

## Password Input
"<form" action="http://www.example.com/login.php">
"<p>"Username:
 "<input" type="text" name="username" size="15"
 maxlength="30" />
"</p>"
"<p>"Password:
 "<input" type="password" name="password" size="15"
 maxlength="30" />
"</p>"
"</form>"

## Text Area
"<form" action="http://www.example.com/comments.php">
"<p>"What did you think of this gig?</p>
 "<textarea" name="comments" cols="20" rows="4">Enter
 your comments..."</textarea>"
"</form>"

## Radio Button
"<form" action="http://www.example.com/profile.php">
"<p>"Please select your favorite genre:
 "<br />"
 "<input" type="radio" name="genre" value="rock"
 checked="checked" /> Rock
"<input" type="radio" name="genre" value="pop" />
 Pop
 "<input" type="radio" name="genre" value="jazz" />
 Jazz
"</p>"
"</form>"

## Checkbox
"<form" action="http://www.example.com/profile.php">
"<p>"Please select your favorite music service(s):
 "<br />"
 "<input" type="checkbox" name="service"
 value="itunes" checked="checked" /> iTunes
 "<inpu"t" type="checkbox" name="service"
 value="lastfm" /> Last.fm
 "<input" type="checkbox" name="service"
 value="spotify" /> Spotify
"</p>"
"</form>"

## Drop Down List Box
"<form action="http://www.example.com/profile.php">"
"<p>"What device do you listen to music on?"</p>"
"<select name="devices">"
 "<option value="ipod">"iPod"</option>'
 "<option" value="radio">Radio"</option>"
 "<option" value="computer">Computer"</option>"
 "</select>"
"</form>"

## Multiple Select Box
"<form action="http://www.example.com/profile.php">"
"<p>"Do you play any of the following instruments?
 (You can select more than one option by holding
 down control on a PC or command key on a Mac
 while selecting different options.)"</p>"
"<select name="instruments" size="3"
 multiple="multiple">"
 "<option value="guitar" selected="selected">"
 Guitar"</option>"
'<option value="drums">"Drums'</option>'
 "<option value="keyboard"
 selected="selected">"Keyboard"</option>"
 "<option value="bass">"Bass"</option>"
"</select>"
"</form>"

## Submit Button
"<form action="http://www.example.com/subscribe.php">"
"<p>"Subscribe to our email list:"</p>"
"<input type="text" name="email" />"
"<input type="submit" name="subscribe"
 value="Subscribe" />"
"</form>"

## Image Button
"<form action="http://www.example.org/subscribe.php">
<p>Subscribe to our email list:</p>
 <input type="text" name="email" />
 <input type="image" src="images/subscribe.jpg"
 width="100" height="20" />
</form>"

# Bullet Point Styles
- " list-style-type ": The list-style-type property allows you to control the shape or style of a bullet point (also known as a marker). 

## Images for Bullets
 - " list-style-image ": we can specify an image to act as a bullet point using the list-style-image property 

 ## Positioning the Marker
 - "list-style-position ": This property can take one of
two values: outside & inside 

## List Shorthand
- "list-style":  it allows you to express the markers' style, image and position properties in any order.

## Gaps Between Cells
- "border-spacing", "border-collapse"

## Cursor Styles
- "cursor" : this property allows you to control the type of mouse cursor that should be displayed to users.

# Events
Examples of some events:

-load:  Web page has finished loading
-unload: Web page is unloading (usually because a new page was requested)
-error: Browser encounters a JavaScript error or an asset doesn't exist
-scroll:  User has scrolled up or down the page


## HOW EVENTS TRIGGER JAVASCRIPT CODE
1. Select t he element node(s) you want the script to respond to. 
2. Indicate which event on the selected node(s) will trigger the response. 
3. State the code you want to run when the event occurs. 

## THREE WAYS TO BIND AN EVENT TO AN ELEM ENT
1. HTML EVENT HANDLERS 
2. TRADITIONAL DOM EVENT HANDLERS
3. DOM LEVEL 2 EVENT LISTENERS 

## TRADITIONAL DOM EVENT HANDLERS 
" element .onevent functionName ; "

## EVENT LISTENERS
Event listeners are a more recent approach to handling events. They can deal with more than one function at a time but they are not supported in older browsers. 

"element .addEventlistener('event', functionName [, Boolean]) ; "


