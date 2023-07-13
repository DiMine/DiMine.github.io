<style>
body {
background-color: DarkSlateGray;
color: white;
}
/* unvisited link */
a:link {
  color: whitesmoke;
}

/* visited link */
a:visited {
  color: snow;
}

/* mouse over link */
a:hover {
  color: ghostwhite;
}

/* selected link */
a:active {
  color: white;
}
</style>
<title>Bots</title>
<link rel="shortcut icon" type="image/ico" href="Pogpega.ico"/>
<meta name="description" content="Commands for ThatOneGuyWhoSpamsPogpega's PogpegaBots">
<meta content="PogpegaBot Commands" property="og:title" />

# MAIN BOT
All of the commands work with Pogpega, Pogpega IceCold, Pogpega SoSnowy, Pogpega  IceCold at the beginning of the message.
 
 
### LED COMMANDS  
There are 4 LEDs connected to my pi:  
- Blue - Lights up when BTMC is live  
- Red - Lights up for 5 seconds when I get pinged using >ping  
- Green - Controlled by &gt;led on and &gt;led off  
- RGB - Controlled by &gt;led rgb {color}  
<br>

#### &gt;led  
Explains how the led works  
  
#### &gt;led on|off|status  
Turns the led on or off, or says whether the led is currently on or off  
  
#### &gt;led rgb {color}  
Changes the color of the RGB LED   
Valid inputs are red, green, blue, white, yellow, purple, teal, off  
(The R, G, and B channels can be either 0 or 1 so the colors are very limited)  
  
### OFFLINE CHAT COMMANDS  
If you use these commands in online chat, it will send the output to PogpegaBot's twitch chat.
  
#### &gt;badtranslate {text}  
Puts the specified text through a translator in a bunch of different languages and back to english  

#### &gt;cam  
Sends the link to the [rtsp page](https://pogpega.farm/rtsp)  
(Works with @)  
  
#### &gt;camera  
See above  
  
#### &gt;cbot {insert text here}  
Talk to cleverbot with the "insert text here" being what it sees  
  
#### &gt;chat {insert text here}  
Talk to chatterbot with the insert text here being what it sees (this bot almost never gives cohesive responses and has no message history)  
  
#### &gt;code  
Sends the shortened link to the bot's github repo  
  
#### &gt;commands  
Sends the link to this page  
  
#### &gt;deadchat  
Sends the dead chat copypasta  
  
#### &gt;deceit  
𝒟𝐼𝒟 𝒴𝒪𝒰 𝒥𝒰𝒮𝒯 𝒮𝒜𝒴 𝒯𝐻𝐸 𝒟𝐸𝒞𝐸𝐼𝒯   
  
#### &gt;dm {text}  
DMs me on discord with the message and twitch username  
  
#### &gt;dm2 {text}  
Same as &gt;dm but dms NekoPavel instead of me  
  
#### &gt;emit  
Secret command  
  
#### &gt;emojify {insert text here}  
Attempts to add emojis between words although it doesnt work that well  
  
#### &gt;experiment  
Checks an API to see the latest experiment by the Canadian government    
  
#### &gt;follow (Currently broken)  
Checks if you are following me on twitch  
  
#### &gt;gamba {amount to bet} {chance of winning (1 out of x, higher is more risk more reward)}  
Gamble away all your pogpegas  
  
#### &gt;generate {insert text here} (Currently broken)  
Makes an AI generate text using the input as a starting point  
  
#### &gt;give {username} {amount}  
Gives the specified user the specified amount of pogpegas. Works with or without the @ and any capitalization.  
You cannot give pogpegas to hrfarmer_ or kexiv_  
  
#### &gt;guess {5 letter word}  
Guess a 5 letter word in wordle  
  
#### &gt;homies  
Don't have chatterino homies? Follow the link to get it.  
  
#### &gt;manualcheck  
Triggers a check to see if BTMC is online.  
Admin only  
  
#### &gt;manualoffline  
Manually tells PogpegaBot that BTMC is offline.  
Admin only  
  
#### &gt;manualonline  
Manually tells PogpegaBot that BTMC is online.  
Admin only  
  
#### &gt;markov {username (optional)}  
Creates a markov chain using messages sent by the twitch user  
Data comes from my chatterino logs, so lots of info is missing  
  
#### &gt;markovword {word}  
Creates a markov chain using messages sent by the BTMC's twitch chat, starting from the specified word  
Data comes from my chatterino logs, so lots of info is missing  
  
#### &gt;maxfarm  
Sends the max amount of pogpegas in a single message  
  
#### &gt;online  
Check to see if BTMC is online  
  
#### &gt;pasta {new|random|search|legacysearch|delete}  
Do stuff with the copypasta library. With new, search, and delete you need to specify extra text to do stuff.
Legacysearch uses the old search implementation which barely works  
Delete is Admin (+ kexiv_) only  
  
#### &gt;ping  
If 2 seconds go by and the pinger bot hasnt said anything, the main bot will say that I am asleep.
  
#### &gt;pogpegafarm  
POGPEGA FARMING  
  
#### &gt;pogpegas  
Tells you how many pogpegas you have.
  
#### &gt;pogpegas {username}  
Tells you how many pogpegas the specified user has. Capitalization and the @ symbol aren't needed.  
Pogpegas are a useless currency that the pogpegabot counts. Every Pogpega (the emote) sent will give +1 pogpega, and solving a wordle will give pogpegas that scales based on which guess won.
  
#### &gt;pyramid {number from 2-10} {text to pyramidize}  
Makes a pyramid. If no text is specified will default to Pogpega.  
Only works if the bot is a mod/vip
  
#### &gt;remind {time} {message}  
Pings you with the specified message after {time} seconds.  
  
#### &gt;repeat {insert text here}  
Repeats the specified text  
  
#### &gt;reset  
Reset the chat history with cleverbot  
Admin only  
  
#### &gt;rice  
no you meant !rice  
  
#### &gt;scramble  
Scrambles a PogpegaBot command that can be guessed for pogpegas  
  
#### &gt;servo {number from 500-2500}  
Make the servo motor connected to my pi rotate to the specified point  
  
#### &gt;servo location  
Says the current angular location of the servo  
  
#### &gt;servo seizure  
Give the servo a seizure  
  
#### &gt;similarity "{text}" "{more text}"  
Compares the similarity of the first text to the second text. Will break if the text has quotation marks within it.  
Also requires quotation marks even if its just one word.  
  
#### &gt;status  
Sends a message that I can specify and change  
  
#### &gt;tab {@user (optional)}  
Reminds you or the specified user (requires the @ symbol) that they can use the tab button to auto-complete emotes.  
  
#### &gt;test  
Check's the ping for PogpegaBot  
  
#### &gt;toxic {text}  
Uses an api to determine the toxicity of the specified text.  
  
#### &gt;translate {2 letter language code (example: english = en)} {text to translate} (Currently broken)  
Translates the text to the language specified  
  
#### &gt;update  
Sends the latest PogpegaBot update  
  
#### &gt;uptime  
Sends how long it has been since PogpegaBot was last restarted  
  
#### &gt;wordle  
Start a game of wordle  
  
#### &gt;wordle stop  
Stop the current game of wordle  
Admin only  
  
  
  
### FITBIT COMMANDS
These commands use the Fitbit API to display my daily stats  
  
  
#### &gt;refresh  
Refresh the stats  

#### &gt;calories  
Says how many calories I have burned today  
  
#### &gt;sleep  
Says how much sleep I got last night  
  
#### &gt;steps  
Says how many steps I have gotten today  
  
  
  
### OTHER COMMANDS
Commands that don't use the > prefix
  
  
#### !bored  
Spam pogpega  
  
#### !prefix  
Says that the prefix is >  
  
#### !stoic  
![reeferSad](https://cdn.7tv.app/emote/62bc8c37a9acb46ce56f0f07/2x.gif) so ture  
  
  
  
### RANDOM CHANCE  
These commands only have a certain chance of happening  
  
  
#### !pull  
Pull on these nuts lmao gottem  
1 in 15  
 
#### !roll  
Roll on these nuts lmao gottem  
1 in 15  
  
#### !skin  
Call out the skin frogs  
1 in 15  
 
#### Boolin ?  
We boolin  
MrDutchBoi only  
1 in 3  

#### FRICK  
Frick soran  
Soran2202 only  
1 in 5  
  
#### Get 20% off Manscaped with code  
Use code Pogpega !!!  
1 in 3  
  
#### @homies  
Says PINGED  
1 in 20  
  
#### Pogpega /  
Says Pogpega / back  
1 in 3  
  
#### Use code  
Use code Pogpega !!!  
1 in 5  
  
  
  
### osu! COMMANDS  
These commands interact with the owo discord bot and can get osu stats  
  
  
#### &gt;link  
Says which (if any) osu username is linked to the twitch user  

#### &gt;link {username}  
Link the specified osu username to the twitch user who used the command  
  
#### &gt;rs {username (optional)}  
Shows the most recent score for the player  
  
#### &gt;c {username (optional)}  
Shows the player's score on the most recently accessed map  
  
#### &gt;sc {username} {map link}  
Shows the player's score on the specified map  
  
#### &gt;map {map link}  
Shows the stats of the specified map  
  
#### &gt;osu {username (optional)}  
Shows the stats from the player's osu profile  
  
#### &gt;osutop {username (optional)}  
Shows the player's top pp plays  
  
#### &gt;mania {username (optional)}  
Shows the stats from the player's osu!mania profile  
  
#### &gt;maniatop {username (optional)}  
Shows the player's top pp plays from osu!mania  
  
#### &gt;taiko {username (optional)}  
Shows the stats from the player's osu!taiko profile  
  
#### &gt;taikotop {username (optional)}  
Shows the player's top pp plays in osu!taiko  
  
#### &gt;ctb {username (optional)}  
Shows the stats from the player's osu!catch profile  
  
#### &gt;ctbtop {username (optional)}  
Shows the player's top pp plays in osu!catch  
  
  
  
# PINGER BOT  
Commands for ThatOneBotWhoPingsPogpega  
If enough partly consecutive messages contain either Pog, I WAS HERE, WHAT, or KEKWait, I will be told there is a pog moment on stream (it also gets triggered when 40+ subs are gifted at once because streamelements says PogU which contains Pog)  
  
#### &gt;ping {message}  
Sends me a desktop notification with the specified message  
  
#### Use code  
Like PogpegaBot's Use code command, but with a different message  
  
  
  
# STARTER BOT  
Commands for ThatOneBotWhoStartsPogpega  
#### &gt;restart  
If the PogpegaBot breaks, use this to restart it. (also this is disabled because the part that crashes is a different script and everything in this bot is in try catches so it hopefully shouldnt break :COPIUM:  
  
#### &gt;shock  
Restarts the script for the bot that triggers the osu bot  
 
#### Use code  
Like PogpegaBot's Use code command, but with a different message  
  
  
# COMING SOON if i ever get around to it  
- Put the led/servo commands into a separate script so the main script can run without sudo  
- Counters for how many times each command has been used  
- Make the rgb led use full color spectrum  
- Make my own markov algorithm  
- Find new APIs for >generate and >translate  