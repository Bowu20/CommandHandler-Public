# CommandHandler-Public
This is the public repo CH2(?) [which is private] for the general public to make suggestions for features, commands, and more.

What is CH2?
CH2 is the 2nd version of the CommandHandler [@Bowu20](https://github.com/Bowu20) created to making bots in Go Lang as easy as it was in [Discord.js-Commando](https://www.npmjs.com/package/discord.js-commando).

## Features so far

- Handlers
  - Message
  - Message response
    - By this I mean bot sends a message, user replies to said message without a command, it handles it.
    - Step Handler sort of adds onto this adding multi-layer message response handling.
  - Reaction
  - Pagination
  - Permission Requirements
  - Server / DM locks

- Database
  - Based on [GORM](https://gorm.io/)
  - Adheres to GORM's anti-racing documentation.
  - Multi prefix handling

- Modules
  - Blacklisting (checked = finished)
    - [x] Message content
    - [ ] Username
    - [ ] UserID
    - [ ] Servername
  - Captcha
    - Generates text captcha, future integrations for image captcha are possible.
  - ❌ Tickets (NOT STARTED IN THE SLIGHTEST)

- Predefined commands (not all may be listed below)
  - dm - Sends a DM to users
  - nuke - Nukes a channel while preserving permissions and other details
  - prefix - Reference multi prefix handling
  - say - Says something as the bot
  - userinfo - Shows user information, nitro check not possible, [reference](https://github.com/discordjs/discord.js/issues/3047#issuecomment-459978357)

- Misc
  - Cooldown
  - Cycling Status
  - Delete button (coded for Ratchy originally)
  - Template engine
    - Works for text and embeds
