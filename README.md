# LB-Kukoro-Butler
## What does this do?
Retrieves player name, stats and skills in Kukoro dungeon mode, and allows the streamer to retrieve the players and find which would be best to fight a given monster

## Twitch commands
* `!players`: List the name, stats and skills of all players who have done `!getinfo`
* `!player @player`: List the name, stats and skills of an individual player who has done `!getinfo`
* `!whocankill <enemy>`: Lists all players who have that enemy mentioned in their skills
* `!kill @<player>`: Removes that player from the list of players and removes their skills

## Example usage via Twitch chat
<details>
  <summary>Click to see examples</summary>

`!players`
```
@dannyvalz (L: 13, C: 17%, D : 13%): [come back critical hits to enemy troll] & [damage x3 against enemy troll of identical level as you]

@rd_reckless (L: 20, C: 13%, D : 10%): [level +2 all your team if you die by enemy minotaur] & [x1.5 damage against enemy minotaur]

@justspike (L: 15, C: 16%, D : 11%): [100% chance of critical against enemy cyclops if you are the last player alive] & [kill enemy cyclops with one hit if you have 3hp or less]

@mrsvalentinexx (L: 11, C: 11%, D : 11%): [level +1 all your team when you defeat enemy minotaur] & [x0.5 damage against enemy minotaur]
```

`!player @dannyvalz`
```
@dannyvalz (L: 13, C: 17%, D : 13%): [come back critical hits to enemy troll] & [damage x3 against enemy troll of identical level as you]
```

`!whocankill minotaur`
```
@rd_reckless - level +2 all your team if you die by enemy minotaur
@rd_reckless - x1.5 damage against enemy minotaur

@mrsvalentinexx - level +1 all your team when you defeat enemy minotaur
@mrsvalentinexx - x0.5 damage against enemy minotaur
```

`!kill @rd_reckless`
```
o7 @rd_reckless! Thank you for your service.
```

`!whocankill minotaur`
```
@mrsvalentinexx - level +1 all your team when you defeat enemy minotaur
@mrsvalentinexx - x0.5 damage against enemy minotaur
```
</details>


## How to install
1. Download the .lbe extension file from **[Releases](/releases)** section (please do not right click and save) 
2. Click on Install Extension in your LioranBoard Receiver
3. Select the extension file you downloaded 
4. Select your default Transmitter you are using. Make 100% sure it is the correct one. 
5. Refresh your Transmitter or close and reopen Lioranboard Receiver. 
6. Most extensions include a premade deck with buttons. If you do not see one, create a new button, add "Send to Extensions" command and select the extension you just installed. If you can only see the extension name with no input fields, it means it was not installed correctly. Repeat steps above.    

## Supporting me
If you enjoy this extension, please consider [following me on Twitch](https://twitch.tv/dannyvalz), or if you really wanted to make my day, [make a donation](https://streamlabs.com/dannyvalz/tip) during a stream and watch me gush with appreciation. 