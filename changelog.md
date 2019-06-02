# Changelog
## V1.0.6
* Added command `die` which will restart bot, checks for permission level `ADMINISTRASTOR`.
## v1.0.5
* Edited `newreportschannel` to check for permission level `MANAGE_CHANNELS` when triggered, if the user doesn't have permission it won't allow them to use the command.
## v1.0.4
* Added Command `newreportschanel`, command when triggered will look for a `reportschannel` if none found it will create a new `reportschannel`.
* Edited Report Command, if there is no `reportschannel` found the bot will no longer create one but will reply and say that it cannot find the channel and the you can create one using the `newreportschannel` command.
## v1.0.3
* Edited report command so that it will actually send the report after creating the new reports channel
## v1.0.2
* Edited Help Command to include new command, `changelog` in help embeds.
## v1.0.1
* Added command `changelog`, command when triggered will give user the link to this document.
## v1.0.0
* Bot Created based off previous bot.
* Added Command Staff List.
* Edited Help Command to include permission level, Permission Level `"MANAGE_MESSAGES"` triggers Staff Commands Embed, if member doesn't have Permission level `"MANAGE_MESSAGES"` trigger Member Help Embed.
* Edited Report Command, if no `reportsChannel` found; bot creates a channel with the name reports and will send `reportEmbed` in the `reportsChannel` created.

