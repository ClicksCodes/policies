### Nucleus Privacy Policy
##### By Clicks

-----

#### Data we collect 

[Your server](#server)

[Verify](#verify)

[Transcripts](#transcripts)

[Mod Notes and History](#notes)

-----

### Definitions

1. \[Square brackets] indicate exemptions
  - U indicates users
  - R indicates roles
  - C indicates channels

2. {Curly brackets} indicate feature requirements
  - P indicates premium 


### Server

Nucleus stores information about your server needed to function. Below is a list of all data stored:

- The server's ID
- Notifications to only send once
- If NSFW / small images should be deleted
- If malware should be deleted
- Which words should be filtered, and \[U/R/C]
- If invites should be deleted, and \[U/R/C]
- If mass mentions should be deleted, and \[U/R/C], and which roles are allowed to be mentioned
- Which channels should have their content deleted automatically, \[U/R]
- Which channels should have their messages automatically published
- If members should get a message when they join, and what role to give when they join
- Which channels are marked as "stats channels", and what name they should have
- What should be logged and where
- Where staff notifications should be logged
- Where attachments should be logged {P}
- Which role to give when a user verifies
- Which channel tickets should be created under, the custom types (and if they are in use), the role to ping, and the max tickets per user
- The link and button text to send on messages when a user is kicked, banned, softbanned, warned, or their nickname is changed
- The link, text and role to give when a user is muted, and if the users should be timed out
- The list of tracks in the server (each with a name, if previous roles should be kept, if a role is required, the list of roles, and a list of roles who can manage the track)
- The list of tags in the server (each has a name and a property)
- The role menus in the server (each with a name, description, minimum and maximum choices, and options, each with a name, description, and role)


# Verify
         
If verification is used, additional information is stored temporarily in-memory about the user. The complete list is below:
- The user's ID
- The ID of the role given when verified
- The name of the role given when verified
- The servers ID
- The servers icon URL
- The servers member count
- The code the URL should contain


# Transcripts

The following data is stored for transcripts:
- Member (IDs, Avatars, nicknames & discriminators)
- Guild ID
- Channel ID
- Messages (Embeds, Content, Timestamps, Flags, Attachments, Stickers)

Transcripts are created when you purge messages or archive a support ticket. They are stored encrypted in a database accessible only with a 64-character code and a 48-character encryption key. We do not store the key, so if you lose the key we will not be able to restore your transcripts. 

All transcripts are permanently deleted from our servers after 30 days although you may still view transcripts that are stored elsewhere (e.g. ones which have been exported to Discord). By default, we export all transcripts to your Discord logs.

The data which we store on transcripts can be deleted from /privacy, you must delete exported transcripts or encryption keys yourself as we do not control these.


# Notes
#### Mod notes and history

The following data is stored for mod notes:
- Guild ID
- Member ID
- Note string

User warns, bans, joins, etc. are stored for the /mod about command. This is for moderator use only and to view a history of the user's past events.

This data can be deleted from /privacy

# Profile scanning

If moderators scan for NSFW images or banned words in profiles Nucleus stores the following for under a minute:
- The user's profile picture

Additionally, Nucleus stores a one-way hash of the image along with whether it was NSFW. No user data is stored with this hash and it is impossible to reverse it to get the original image. We only store this data to avoid us rescanning images in the future, it is never used (and indeed not very useful) for any other purpose.

# Delete my data

Nucleus contains multiple easy way for server staff to delete data.

Any of the following will delete all data about a guild, permanently:
- Removing the bot from your server
- As the server owner, deleting data from the last page of `/privacy`

Verification information is only stored in memory and expires after 1 hour

Transcripts are stored with guild data so will be deleted in any of the normal circumstances but can additionally only survive for 30 days on our servers. Staff are strongly advised to keep transcript exports if they wish to view transcripts for longer than 30 days.
