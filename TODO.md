## misc

[] handle changing user color (preferably change color of the avatarright away)

[] *important!* bug: interrupted by talking animation while walking to bonk (LisadiKaprio)

[] bug: hugged a person twice (nc_para_) (situation: !hug bacing, !hug lisadikaprio; what happened: hugged bacing, then hugged lisa, then hugged bacing again, then talking animation happened)

[] emojis flying around like emotes:

-> Moscowwbish: you should be able to use a regex to extract emojis out of text and render them onto the canvas as text

-> Moscowwbish: the default font should support emojis

[] *important!* bug: not all animated emotes displaying (lisadiAchanchanchanteachan displaying, anim emotes from edu's / anomon's channels aren't displaying)

-> caching issue? (why is achan emote displaying hmmm)

-> compression issue?

# random idea: character traits

-> specific people aquire specific (long-lasting?) traits over the course of the game?

-> example: lonely - gets hugged twice as often / randomly by others

# user-to-user interactions

[] deduct 30 xp points when hugging

[] log window: "%username spends 30 xp to hug %username!"

-> [] deduct 60 xp points when bonking

# labors

[] !hunt

  -> [] background of a forest appears in some specific place on the canvas with dissolve (in case noone is doing hunting already)

  -> LISA TODO [] png forest location png (same for gather)

  -> [] user walks to that place (anywhere between x1 and x2, so all avatars don't just stand in one place)

  -> [] an animated icon appears above the user, indicating hunting

  -> [] the app already decides what item the user gets 

  -> [] after a specific amount of time, the labor is done, and the user plays the get-item animation, with the item's icon appearing above its head, with slow movement up, then stop, then movement up with dissolve to disappear

  -> [] afterwards, the user continues its routine of idle walking, meanwhile an icon with the same popping up animation appears above its head, saying they got 100 xp

  -> [] user has an inventory that stores the new item

[] !gather

  -> LISA TODO [] png forest location png (same for hunt)

[] !mine

  -> LISA TODO [] png cave location png

[] !fish

  -> LISA TODO [] png lake location png

# item interactions

[] !consume %item

  -> 

[] !craft %item

  ->

# log window

[] 

# stats
* info that gets saved and can be looked up, or that allows silly stuff like "AnnoyingEdu is the number 1 hugger" or "kirinokirino is the most active player!"

[] inventory!

[] basically save amount of every interaction/labor that took place

  -> most hugs, most bonks, most hunting, most gathering, most fishing, most mining, most labors performed, most items consumed, most items crafted, most stealing performed, most being stolen from (wait... maybe that's a bit too much?.. idk. maybe only pick the most interesting from those)

# misc

[] !give xp to someone else

[] RENAME xp to coins?

[] !lurk

  -> LISA TODO: [] sleeping/hiding user sprites

  -> log window: "%username has something better to do. Have a nice lurk!"

[] user appears by coming into the screen from the left or the right (no talking animation plays yet)

[] if user hasn't written anything in chat for 20 minutes: play z z z animation above their head and make them stop the idle walking routine

  -> LISA TODO: z z z spritesheet

  -> LISA TODO: sleeping/hiding user sprites

  -> *important!* LISA TODO: think of something better for that (they get smaller? lay on the ground? go to specific location?)


# DONE

[x] *important!* when talking: +15 xp animation above the user's head 

  -> LISA TODO: [x] spritesheet

  -> [x] appearing above its head, with slow movement up, then stop and float up and down for ~3 secs, then movement up with dissolve to disappear

  -> [x] save this type of animation to be used later for gained items and other xp gains

  

* log window: TLDR: same as bot's chat messages in para's farm game, but packed onto the game canvas in some corner, not written in actual twitch chat
[x] *important!* basic layout

[x] *important!* messages when something happens

  -> "Hello %username, thanks for chatting!" on user's first chat/appearence"

  -> "%username hasn't written much in chat for a while now... Seems like they fell asleep!"

[x] error messages when user tries to perform invalid action

[x] !stats for user to ask for infos/inventory

[x] (stats) amount of xp!

[x] *important!* reduce size by 2

  -> LISA TODO [x] bonk user sprites

  [x] *important!* !hug %username

  -> [x] user who typed it floats over to the user he/she wants to hug, then they both perform a hug animation (the one who's on the left performs hug-right and the one who's on the right performs hug-left animation), then they continue on with their routine

  -> [x] if the users perform a talking or consuming animation, it should stop

[x] *important!* save display name, be able to !hug the display name

[x] be able to hug with @

[x] be able to hug with randomcase (toLowercase)

[x] fix bug?

-> [x] be able to mirror the sprites i drew through script

[x] *important!* log window: "Welcome back %username!" after the user has texted again after falling asleep

[x] *important!* !bonk %username

  -> [x] user who typed it floats over to the user he/she wants to bonk, then they both perform a bonk animation , then they continue on with their routine

[-] after hugging, avatars should walk off in separate directions (not in the same one)

[x] *important!* avatar should walk around 2 times faster when going for a hug
