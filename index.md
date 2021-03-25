# Alecta Help

### Command arguments are displayed in all caps.

### USER, CHANNEL | Mention, ID or Name can be provided. (Username not recommended)

### [__TEXT__] |  Text inside [] is an option addon, it isn't required for the command to work.

## User Management Commands
**`g!add employee USER`**
- Add an Employee to permission list on this server. Can provide more than one User at a time. 
- Requires Team Leader+

**`g!add team leader USER`**
- Add an Team Leader to permission list on this server. Can provide more than one User at a time. 
- Requires Team Leader+

**`g!add senior USER`**
- Add an Senior Mod to permission list on this server. Can provide more than one User at a time. 
- Requires Team Leader+

**`g!add advanced USER`**
- Add an Advanced Mod to permission list on this server. Can provide more than one User at a time. 
- Requires Senior+

**`g!add junior USER`**
- Add an Junior Mod to permission list on this server. Can provide more than one User at a time. 
- Requires Senior+

**`g!add trainee USER`**
- Add an Trainee Mod to permission list on this server. Can provide more than one User at a time. 
- Requires Senior+

**`g!remove employee USER`**
- Removes an Employee to permission list on this server. Can provide more than one User at a time. 
- Requires Team Leader+

**`g!remove team leader USER`**
- Removes an Team Leader to permission list on this server. Can provide more than one User at a time. 
- Requires Team Leader+

**`g!remove senior USER`**
- Removes an Senior Mod to permission list on this server. Can provide more than one User at a time. 
- Requires Team Leader+

**`g!remove advanced USER`**
- Removes an Advanced Mod to permission list on this server. Can provide more than one User at a time. 
- Requires Senior+

**`g!remove junior USER`**
- Removes an Junior Mod to permission list on this server. Can provide more than one User at a time. 
- Requires Senior+

**`g!remove trainee USER`**
- Removes an Trainee Mod to permission list on this server. Can provide more than one User at a time. 
- Requires Senior+

## Server Management Commands
**`g!add react role CHANNEL MESSAGE_ID ROLE [True/False (Custom Emote or Not)]`**
- Create a new Reaction Role on the Message provided with the Role. It will ask for the emote you wish to use when you use the command.	
- Requires Senior+

**`g!remove react role MESSAGE_ID`**	
- Removes a Reaction Role with the Message provided. A selection menu will be sent when used.
- Requires Senior+

## Modding Commands
**`g!support USER`**
- Add a User into a Support Room | Must be used in the support room you wish to add the player to.
- Requires Trainee+

**`g!clear room`**	
- Clears a Support Room, removing any players and deleting messages. 
- Requires Trainee+

**`g!purge MESSAGE_AMOUNT`**
- Mass message deletion in the used channel.
- Requires Trainee+

**`g!warn USER WARNING_REASON`**
- Warns a User with the given reason, reason is required.	
- Requires Junior+

**`g!mute USER [TIME]`**	
- Mutes a User, if time is provided will mute for that length (d for days, h for hours, m for minutes, s for seconds). 
- Requires Junior+

**`g!kick USER KICK_REASON`**	
- Kicks a User with the given reason, reason is required.	
- Requires Advanced+

**`g!ban USER BAN_REASON`**	
- Bans a User with the given reason, reason is required.	
- Requires Senior+

**`g!role USER ROLE`**	
- Adds or Removes a Role from the given User.
- Requires Trainee+

## Event Commands
**`g!multi event [CHANNEL]`**	
- Runs an Interactive Setup for a Multiple Choice Event.	
- Requires Senior+

**`g!end multi event`**	
- Ends the current Multiple Choice Event, Sending you .txt files with all entries.	
- Requires Senior+

**`g!request multi event data`**	
- Sends you the Data of the Current/Past Multiple Choice Event (Sends past only if you haven't started a new one).	
- Requires Team Leaders+

**`g!giveaway [CHANNEL] [TIME] [WINNERS] [REWARDS]`**	
- Starts an Interactive giveaway setup (You can provide the details in the command to shortcut it if you know how).	
- Requires Senior+


## Bot Games | Work in Progress
**`g!enable angels`**
- Enables the Angel Collection Mini-game.
- Requires Team Leader+

**`g!angel.channels CHANNELS`**
- Sets the provided Channels as active spawning Channels for the Angels.
- Requires Team Leader+

**`g!angel.removechannels CHANNELS`**
- Removes the provided Channels as spawning Channels for the Angels.
- Requires Team Leader+

**`g!claim`**	
- Claims the avaliable Angel in the Channel
- No Requirement

**`g!angels`**
- Displays the Uesrs Collected Angels
- No Requirement
