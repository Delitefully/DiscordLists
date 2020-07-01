# DiscordLists

Tracking servers in Discord's community programs.

To check the features of a guild via an instant invite code, add the invite code to the following URL: https://discord.com/api/invite/[invitecode] 

e.g.: https://discord.com/api/invite/discord-townhall - the guild's features are `INVITE_SPLASH", "NEWS", "DISCOVERABLE", "BANNER", "VERIFIED", "VANITY_URL", "ANIMATED_ICON", "PUBLIC", "FEATURABLE", "VIP_REGIONS", "COMMUNITY`.
 
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

* `BANNER` - Ability to set a [banner image](https://discord.com/developers/docs/game-and-server-management/vanity-perks#server-banner-background) that will display above the channel list.

* `COMMERCE` - Ability to create and use [store channels](https://discord.com/developers/docs/game-and-server-management/special-channels#store-channels).

* `COMMUNITY` - [Gain access to Server Discovery and Announcement Channels.](https://support.discord.com/hc/en-us/articles/360035969312-Public-Server-Guidelines). Enables [lurking](https://discord.com/developers/docs/game-and-server-management/special-channels#lurker-mode) via discovery and invites while logged out, as well as from crossposted announcements from news channels. 

* `DISCOVERABLE` - Visible in Server Discovery.

* `ENABLED_DISCOVERABLE_BEFORE` - Enabled Server Discovery before the Discovery Checklist launched.

* `FEATURABLE` - Makes the server featurable in the activity feed and other special promotions.

* `FORCE_RELAY` - Shards connections to the guild to different nodes that relay information between each other. 

* `INVITE_SPLASH` - Ability to set a background image that will display on all invite links.

* `MEMBER_LIST_DISABLED` - Hides the member list sidebar.

* `MORE_EMOJI` - Adds 150 extra emoji slots to each category (normal and animated emoji). Not used in server boosting.

* `NEWS` - Ability to create and use [~~news~~announcement channels](https://support.discord.com/hc/en-us/articles/360028384531-Channel-Following-FAQ) which can be followed, and shows the Annoucements analytics tab in the guild settings.

* `PARTNERED` - Partner badge near the server name and in mutual server lists. 

* ~~`PUBLIC`~~ - Deprecated in favor of `COMMUNITY`

* ~~`PUBLIC_DISABLED`~~ - Deprecated in favor of `COMMUNITY`

* `RELAY_ENABLED` - Shards connections to the guild to different nodes that relay information between each other.

* `VANITY_URL` - Ability to set a vanity URL (custom discord.gg invite link).

* `VERIFIED` - Verification checkmark near the server name and in mutual server lists. 

* `VIP_REGIONS` - ~~Ability to use special voice regions with a better stability: US East VIP, US West VIP and Amsterdam VIP.~~ Deprecated, replaced with 384kbps max bitrate 

* `WELCOME_SCREEN_ENABLED` - Guild has welcome screen enabled, a modal shown to new joiners that features different channels and a short description of the guild.

----

#### Community program feature comparison 

| Community Program              | Vanity URL | Invite Splash | VIP Regions | Maximum Voice Bitrate | Server Owner Badge | Server Badge           | Extra Emoji Slots | Animated Icon | Banner | Lurking | Announcement Channels | Store Channels | Discovery          |
|--------------------------------|------------|---------------|-------------|-----------------------|--------------------|------------------------|-------------------|---------------|--------|---------|-----------------------|----------------|--------------------|
| Partner                        | ✓          | ✓             | ✓           | 384kbps               | Partner            | Partner icon           |                   |               |        |         | ✓                     |                |                    |
| Verification                   | ✓          | ✓             | ✓           | 384kbps               |                    | Verification Checkmark |                   |               | ✓      | ✓       | ✓                     |                | Enabled by default |
| HypeSquad Event Organizer      | ✓          |               | ✓           | 128kbps               | HypeSquad Events   |                        |                   |               |        |         |                       |                |                    |
| Open Source                    | ✓          | ✓             |             |                       |                    |                        |                   |               |        |         |                       |                |                    |
| Server boosting tier 1         |            | ✓             |             | 128kbps               |                    | Boost tier 1 icon      | 50 \(100 total\)  | ✓             |        |         |                       |                |                    |
| Server boosting tier 2         |            | ✓             |             | 256kbps               |                    | Boost tier 2 icon      | 100 \(150 total\) | ✓             | ✓      |         |                       |                |                    |
| Server boosting tier 3         | ✓          | ✓             |             | 384kbps               |                    | Boost tier 3 icon      | 200 \(250 total\) | ✓             | ✓      |         |                       |                |                    |
| Commerce \(Developer License\) |            |               |             |                       |                    |                        |                   |               |        | ✓       | ✓                     | ✓              |                    |
| Community                         |            |               |             |                       |                    |                        |                   |               |        | ✓       | ✓                     |                | Can apply          |
