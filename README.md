# Demonologist-Widget
A widget for streamers who play Demonologist to track evidence and ghost types


To set it up we are going to need to create a custom widget.
I use Streamelements. You can add this to an existing overlay or make a new overlay.
Once you have the overlay open and you see the blue + button click it go to static/custom and then click custom widget.
This will make a new widget. From there click into open editor.
Now, You will want to copy everything from the HTML document into the HTML tab in the editor. Go Ahead and replace everything in it.
You will repeat that for each seperate document CSS goes into the CSS Tab, JS goes into the JS tab, and Fields goes into the fields tab.
Again Replace everything in each category. Data you do not need to touch.
From there should you have done it right, you will now see under where it says OPEN EDITOR drop down menu's this is how from here you can customize the widget to your
liking. From changing the chat commands to customizing the borders.


Make sure you hit the giant blue SAVE button.


If this is going to be a seperate overlay and not put into your main overlay, go to sources, add new browser source, add like you would any other overlay.

If you have any questions feel free to reach out to me VIA discord and I will answer as quick as I can.

Note these are sample commands below!


Name Reset	!gr "name"	Reset the ghost with the name

Name Input	!gn "name"	Change name to "name"

Map Input	!map "map"	Set the map name. Replace with a command from the map list below

Difficulty Input	!diff "difficulty"	Set the map name. Replace with a command from the map list below

Toggle Sightings	!sight "sighting"	Toggles Sightings for the Location On or Off, See Sightings

Toggle Possession	!poss "possession"	Toggles Possession found for the Location, Defaults to None displayed as ?, See Cursed Possessions

Toggle EMF	!emf	Cycle EMF to next state: Off -> On -> Negative -> Off

Toggle Spirit Box	!sb	Cycle Spirit Box to next state: Off -> On -> Negative -> Off

Toggle Fingerprints	!fp	Cycle Fingerprints to next state: Off -> On -> Negative -> Off

Toggle Stains	!es	Cycle Ectoplasm Stains to next state: Off -> On -> Negative -> Off

Toggle Canvas Drawing	!ecd	Cycle Easel Canvas Drawing to next state: Off -> On -> Negative -> Off

Toggle Freezing Temps	!ft	Cycle Freezing Temps to next state: Off -> On -> Negative -> Off

Toggle Reaction	!esg	Cycle ESG Ghost Reaction to next state: Off -> On -> Negative -> Off

Optional Objectives	!oo "a" "b" "c"

!oo "a"	Set the optional objectives. Replace a, b or c with the objective you'd like below, See Optional Objectives

Toggle Optional Objective 1	!o1	Toggles Optional Objective 1 from being marked or not

Toggle Optional Objective 2	!o2	Toggles Optional Objective 2 from being marked or not


Toggle Optional Objective 3	!o3	Toggles Optional Objective 3 from being marked or not

ca = Candle, si = Silhoutte, ph = Photo, td = Time of Death, st = Stock, ub = Underbarrel, ba = Barrel

Set Counter Name	!setcounter "phrase"

!setcounter2 "phrase"	Set's the phrase before the number in the counter

Set Counter Number	!setcounternumber "num"

!setcounter2number "num"	Set's the number in the counter to the number input

Increment the counter by 1	!counterup

!counter2up	Adds one to the counter number

Decrement the counter by 1	!counterdown

!counter2down	Subtracts one from the counter number
