# DiscordLists

Tracking servers in Discord's community programs.

To check the features of a guild via an instant invite code, add the invite code to the following URL: https://discordapp.com/api/invite/[invitecode] 

e.g.: https://discordapp.com/api/invite/events - the guild's features are `VERIFIED, ANIMATED_ICON, INVITE_SPLASH, VIP_REGIONS, FEATURABLE, DISCOVERABLE, NEWS, BANNER, VANITY_URL`.
 
----
 
#### partners.txt - Partnered servers (dis.gd/partners)
* Features: **`PARTNERED,`**`VANITY_URL, VIP_REGIONS, INVITE_SPLASH, NEWS`
* The server owner will have the Partner badge.
* Certain very old partnered guilds are missing the `PARTNERED` feature, but will have the other features 

#### verified.txt - Verified servers (dis.gd/vfs)
 * Features: **`VERIFIED,`**`VANITY_URL, VIP_REGIONS, INVITE_SPLASH, FEATURABLE, DISCOVERABLE, PUBLIC, BANNER, NEWS`

#### hypesquad-events.txt - HypeSquad Event Organizer servers (dis.gd/hypesquad)
* Features: `VANITY_URL, VIP_REGIONS, INVITE_SPLASH`
* The server owner will have the HypeSquad events badge.

---- 

#### Guild feature glossary

* `ANIMATED_ICON` - Ability to upload an animated icon, similar to animated profile pictures for Nitro members. Displays on hover and invite links on desktop, and plays constantly on mobile.

* `BANNER` - Ability to set a [banner image](https://discordapp.com/developers/docs/game-and-server-management/vanity-perks#server-banner-background) that will display above the channel list.

* `COMMERCE` - Ability to create and use [store channels](https://discordapp.com/developers/docs/game-and-server-management/special-channels#store-channels).

* `DISCOVERABLE` - Visible in Server Discovery.

* `ENABLED_DISCOVERABLE_BEFORE`

* `FEATURABLE` - Makes the server featurable in the activity feed and other special promotions.

* `INVITE_SPLASH` - Ability to set a background image that will display on all invite links.

* `PUBLIC` - Enables [lurking](https://discordapp.com/developers/docs/game-and-server-management/special-channels#special-channels-and-lurker-mode) via discovery, feed links and linked game cards.

* `MEMBER_LIST_DISABLED` - Hides the member list sidebar.

* `MORE_EMOJI` - Adds 150 extra emoji slots to each category (normal and animated emoji). Not used in server boosting.

* `NEWS` - Ability to create and use [~~news~~announcement channels](https://support.discordapp.com/hc/en-us/articles/360028384531-Channel-Following-FAQ) which can be followed, and shows the Annoucements analytics tab in the guild settings.

* `PARTNERED` - Partner badge near the server name and in mutual server lists. 

* `PUBLIC` - [Gain access to Server Discovery and Announcement Channels.](https://support.discordapp.com/hc/en-us/articles/360035969312-Public-Server-Guidelines)

* `PUBLIC_DISABLED` - Banned by Trust & Safety from being a public server due to Terms of Service violations.

* `RELAY_ENABLED` - Shards connections to the guild to different nodes that relay information between each other.

* `VANITY_URL` - Ability to set a vanity URL (custom discord.gg invite link).

* `VERIFIED` - Verification checkmark near the server name and in mutual server lists. 

* `VIP_REGIONS` - ~~Ability to use special voice regions with a better stability: US East VIP, US West VIP and Amsterdam VIP.~~ Deprecated, replaced with 384kbps max bitrate 

* `WELCOME_SCREEN_ENABLED` - Guild has welcome screen enabled, a modal shown to new joiners that features different channels and a short description of the guild.

----

#### Community program feature comparison 

| Community Program            | Vanity URL | Invite Splash | VIP Regions | Maximum Voice Bitrate | Server Owner Badge | Server Badge       | Extra Emoji Slots  | Animated Icon | Banner | Lurking | News Channels | Store Channels |
|------------------------------|------------|---------------|-------------|-----------------------|--------------------|------------------------|--------------------|---------------|--------|---------|---------------|----------------|
| Partner                      | ✓          | ✓             | ✓           | 384kbps               | Partner            | Partner Icon      |                    |               |        |         | ✓             |                |
| Verification                 | ✓          | ✓             | ✓           | 384kbps               |                    | Verification Checkmark |                    |               | ✓      | ✓       | ✓             |                |
| HypeSquad Event Organizer    | ✓          |               | ✓           | 128kbps               | HypeSquad Events   |                        |                    |               |        |         |               |                |
| Open Source                  | ✓          | ✓             |             |                       |                    |                        |                    |               |        |         |               |                |
| Server boosting tier 1       |            | ✓             |             | 128kbps               |                    |                        | 50 (100 total)     | ✓             |        |         |               |                |
| Server boosting tier 2       |            | ✓             |             | 256kbps               |                    |                        | 100 (150 total)    | ✓             | ✓      |         |               |                |
| Server boosting tier 3       | ✓          | ✓             |             | 384kbps               |                    |                        | 200 (250 total)    | ✓             | ✓      |         |               |                |
| Commerce (Developer License) |            |               |             |                       |                    |                        |                    |               |        | ✓       | ✓             | ✓              |
