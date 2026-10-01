Wow addon to track people across a guild that are marked as "Kill On Sight", need to include a guild match as well so we can tag all the olympus peeps

## TODO
- [ ] Maintain a list of characters
  - [ ] all info added must be timestamped for syncing 
  - [ ] storage method for char name, guild, class, level, last seen, note, timestamp
  - [ ] Right click a target, add them to the list
  - [ ] if killed by another player, prompt a 'add to list'
  - [ ] ability to delete list
  - [ ] updates the level val and guild based on the last time someone is seen
  - [ ] manual form, fill out all req info
  - [ ] req charname & note only, once someone is seen then add them  
- [ ] Guild Sync
  - [ ] create a new text channel for those in the guild with the addon
  - [ ] create a format to send list info to others in the guild
  - [ ] compare timestamps, update with the latest of whoever is online
- [ ] Guild Match
  - [ ] place to track guild names to target
  - [ ] fuzzy find characters ("%olympus%" to find all olympus guilds)
  - [ ] this needs to not add the characters to the list just the guild
  - [ ] same treatment as a character on list
- [ ] Notification
  - [ ] notify guild member of new addition
  - [ ] notify player if a marked character was last seen in the zone, within like an hour or so
  - [ ] notify player if a marked character is currently in their zone
  - [ ] notify player if a marked character is in range / can be targeted
  - [ ] notify guild that player killed marked character
