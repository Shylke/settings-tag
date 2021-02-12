
 # **Settings Tag(s):**

 ## __General:__

`{settings;prefix}` = gets the server's prefix.


## __Fun:__
`{settings;plugins.fun}` = gets the general config in a raw format.

`{settings;plugins.fun.options}` = gets all the fun plugin's options. Just starboard to be honest.

`{settings;plugins.fun.options.starboard}` = gets starboard channel's id.

`{settings;plugins.fun.restrictions}` = gets the fun plugin's restrictions (black/whitelists, required perms).

`{settings;plugins.fun.restrictions.mode}` = tells you whetever you're using a blacklist or a whitelist.

`{settings;plugins.fun.restrictions.roles}` = gets you the black/whitelisted roles.

`{settings;plugins.fun.restrictions.channels}` = gets you the black/whitelisted channels.

`{settings;plugins.fun.restrictions.permissions}` = gets you the fun plugin's required perms.

`{settings;plugins.fun.state}` = tells you if the fun plugin is enabled or not.


## __Gatekeeper:__ 
`{settings;plugins.gatekeeper}` = gets the general config in a raw format.

`{settings;plugins.gatekeeper.dm}` = gets you a raw format of the join message (DM option).

`{settings;plugins.gatekeeper.channel}` = gets you a raw format of the join message.

`{settings;plugins.gatekeeper.leave}` = gets you a raw format of the leave message.

`{settings;plugins.gatekeeper.dm.content}` = gets you the content of the join message (DM option).

`{settings;plugins.gatekeeper.channel.content}` = gets you the content of the join message.

`{settings;plugins.gatekeeper.leave.content}` = gets you the content of the leave message.

`{settings;plugins.gatekeeper.channel.channel}` = gets you the join messages' channel's id.

`{settings;plugins.gatekeeper.leave.channel}` = gets you the leave messages' channel's id.

`{settings;plugins.gatekeeper.state}` = tells you if the gatekeeper plugin is enabled or not.


## __Info:__
`{settings;plugins.info}` = gets the general config in a raw format.

`{settings;plugins.info.state}` = tells you if the info plugin is enabled or not.

`{settings;plugins.info.restrictions}` = gets the info plugin's restrictions (black/whitelists, required perms).

`{settings;plugins.info.restrictions.mode}` = tells you whetever you're using a blacklist or a whitelist.

`{settings;plugins.info.restrictions.roles}` = gets you the black/whitelisted roles.

`{settings;plugins.info.restrictions.channels}` = gets you the black/whitelisted channels.

`{settings;plugins.info.restrictions.permissions}` = gets you the info plugin's required perms.


## __Moderation:__
`{settings;plugins.moderation}` = gets the general config in a raw format.

`{settings;plugins.moderation.restrictions}` = gets the moderation plugin's restrictions (black/whitelists, required perms).

`{settings;plugins.moderation.restrictions.mode}` = tells you whetever you're using a blacklist or a whitelist.

`{settings;plugins.moderation.restrictions.roles}` = gets you the black/whitelisted roles.

`{settings;plugins.moderation.restrictions.channels}` = gets you the black/whitelisted channels.

`{settings;plugins.moderation.restrictions.permissions}` = gets you the moderation plugin's required perms.

`{settings;plugins.moderation.logs.action}` = gets the action log's channel id.

`{settings;plugins.moderation.logs.mod}` = gets the mod log's channel id.

`{settings;plugins.moderation.state}` = tells you if the moderation plugin is enabled or not.

### __Filters:__
`{settings;plugins.moderation.filters.phrases}` = general raw config of the phrases filter.

`{settings;plugins.moderation.filters.spoilers}` = general raw config of the spoilers filter.


#### __Capitalization:__
`{settings;plugins.moderation.filters.capitalization}` = general raw config of the capitalization filter.

`{settings;plugins.moderation.filters.capitalization.action}` = tells you what Atlas does when the filter gets triggered. Output is a number. (`0` or `No output :c` = `Disabled`, `1` = `Delete the Message`, `2` = `Delete the Message & Warn the User`, `3` = `Warn the User`)

`{settings;plugins.moderation.filters.capitalization.exempt}` = gives you a list of exempt roles/channels.

`{settings;plugins.moderation.filters.capitalization.exempt.channels}` = gives you a list of exempt channels.

`{settings;plugins.moderation.filters.capitalization.exempt.roles}` = gives you a list of exempt roles.

`{settings;plugins.moderation.filters.capitalization.sanction}` = tells you whetever bots/mods/ticket channels are sanctioned.

`{settings;plugins.moderation.filters.capitalization.sanction.bots}` = tells you if the `Sanction Bots` option is toggled on (`true`).

`{settings;plugins.moderation.filters.capitalization.sanction.moderators}` = tells you if the `Sanction moderators` option is toggled on (`true`).

`{settings;plugins.moderation.filters.capitalization.sanction.tickets}` = tells you if the `Sanction Ticket Channels` option is toggled on (`true`).

`{settings;plugins.moderation.filters.capitalization.threshold}` = gives you the threshold needed to trigger the filter.


#### __Cursing:__
`{settings;plugins.moderation.filters.cursing}` = general raw config of the cursing filter.

`{settings;plugins.moderation.filters.cursing.action}` = tells you what Atlas does when the filter gets triggered. Output is a number. (`0` or `No output :c` = `Disabled`, `1` = `Delete the Message`, `2` = `Delete the Message & Warn the User`, `3` = `Warn the User`)

## __Levels:__
`{settings;plugins.levels}` = gets the general config in a raw format.

`{settings;plugins.levels.options}` = gets all the levels and role rewards, plus the level up message and other info in a raw format.

`{settings;plugins.levels.options.rewards}` = gets all the levels and role rewards in a raw format.

`{settings;plugins.levels.options.rewards.0.level}` = gets the first level requirement.

`{settings;plugins.levels.options.rewards.0.content}` = gets the first role reward's id.

`{settings;plugins.levels.restrictions}` = gets the levels plugin's restrictions (black/whitelists, required perms).

`{settings;plugins.levels.restrictions.mode}` = tells you whetever you're using a blacklist or a whitelist.

`{settings;plugins.levels.restrictions.roles}` = gets you the black/whitelisted roles.

`{settings;plugins.levels.restrictions.channels}` = gets you the black/whitelisted channels.

`{settings;plugins.levels.restrictions.permissions}` = gets you the levels plugin's required perms.

`{settings;plugins.levels.state}` = tells you if the level plugin is enabled or not.


## __Music:__
`{settings;plugins.music}` = gets the general config in a raw format.

`{settings;plugins.music.options}` = gets you all the music plugin's options.

`{settings;plugins.music.options.player_buttons}` = tells you if the "Player Buttons" option is toggled on (`true`).

`{settings;plugins.music.options.hide_nowplaying}` = tells you if the "Hide "Now Playing" Messages" option is toggled on (`true`).

`{settings;plugins.music.options.small_msgs}` = tells you if the "Small Player Messages" option is toggled on (`true`).

`{settings;plugins.music.options.show_results}` = tells you if the "Show Results" option is toggled on (`true`).

`{settings;plugins.moderation.restrictions}` = gets the music plugin's restrictions (black/whitelists, required perms).

`{settings;plugins.music.restrictions.mode}` = tells you whetever you're using a blacklist or a whitelist.

`{settings;plugins.music.restrictions.roles}` = gets you the black/whitelisted roles.

`{settings;plugins.music.restrictions.channels}` = gets you the black/whitelisted channels.

`{settings;plugins.music.restrictions.permissions}` = gets you the music plugin's required perms.

`{settings;plugins.music.state}` = tells you if the music plugin is enabled or not.


## __Roles:__
`{settings;plugins.roles}` = gets the general config in a raw format.

`{settings;plugins.roles.options}` = gets you all the role plugin's options with all the roles in a raw format.

`{settings;plugins.roles.options.iam}` = gets all the iam roles' ids.

`{settings;plugins.roles.options.iam.0}` = gets the first iam role's id. Replace `0` with a higher number to get other roles (1 = 2nd iam role, 2 = 3rd iam role, etc...).

`{settings;plugins.roles.options.join}` = gets all the join roles' ids.

`{settings;plugins.roles.options.join.0}` = gets the first join role's id. Replace `0` with a higher number to get other roles (1 = 2nd join role, 2 = 3rd join role, etc...).

`{settings;plugins.roles.options.reaction_dm}` = tells you if the `Direct-message members when they toggle a role` option is toggled on (`true`).

`{settings;plugins.roles.restrictions}` = gets the roles plugin's restrictions (black/whitelists, required perms).

`{settings;plugins.roles.restrictions.mode}` = tells you whetever you're using a blacklist or a whitelist.

`{settings;plugins.roles.restrictions.roles}` = gets you the black/whitelisted roles.

`{settings;plugins.roles.restrictions.channels}` = gets you the black/whitelisted channels.

`{settings;plugins.roles.restrictions.permissions}` = gets you the roles plugin's required perms.

`{settings;plugins.roles.state}` = tells you if the roles plugin is enabled or not.

## __Suggestions:__
`{settings;plugins.suggestions}` = gets the general config in a raw format.

`{settings;plugins.suggestions.state}` = tells you if the suggestions plugin is enabled or not.


## __Tickets:__
`{settings;plugins.tickets}` = gets the general config in a raw format.

`{settings;plugins.tickets.options}` = gets you all the tickets plugin's options with all the roles in a raw format.

`{settings;plugins.tickets.options.message}` = gets the ticket's opening message.

`{settings;plugins.tickets.options.category}` = gets you the tickets' category's id.

`{settings;plugins.tickets.options.support}` = gets you the tickets plugin's support role's id.

`{settings;plugins.tickets.restrictions}` = gets the tickets plugin's restrcitions (black/whitelists, required perms).

`{settings;plugins.tickets.restrictions.mode}` = tells you whetever you're using a blacklist or a whitelist.

`{settings;plugins.tickets.restrictions.roles}` = gets you the black/whitelisted roles.

`{settings;plugins.tickeets.restrictions.channels}` = gets you the black/whitelisted channels.

`{settings;plugins.tickets.restrictions.permissions}` = gets you the tickets plugin's required perms.

`{settings;plugins.tickets.state}` = tells you if the tickets plugin is enabled or not.


## __Utilities:__
`{settings;plugins.utilities}` = gets the general config in a raw format.

`{settings;plugins.utilities.state}` = tells you if the utilities plugin is enabled or not.

`{settings;plugins.utlities.restrictions}` = gets the utilities plugin's restrcitions (black/whitelists, required perms).

`{settings;plugins.utilities.restrictions.mode}` = tells you whetever you're using a blacklist or a whitelist.

`{settings;plugins.utilities.restrictions.roles}` = gets you the black/whitelisted roles.

`{settings;plugins.utilities.restrictions.channels}` = gets you the black/whitelisted channels.

`{settings;plugins.utilities.restrictions.permissions}` = gets you the utilities plugin's required perms.

