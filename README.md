# DiscordLists

Tracking servers in Discord's community programs.

To check the features of a guild via an instant invite code, add the invite code to the following URL: https://discord.com/api/invite/[invitecode] 

e.g.: https://discord.com/api/invite/discord-townhall - the guild's features are `INVITE_SPLASH", "NEWS", "DISCOVERABLE", "BANNER", "VERIFIED", "VANITY_URL", "ANIMATED_ICON", "FEATURABLE", "VIP_REGIONS", "COMMUNITY`.
 
----
 
#### partners.txt - Partnered servers (dis.gd/partners)
* Features: **`PARTNERED,`**`VANITY_URL, VIP_REGIONS, INVITE_SPLASH, BANNER, ANIMATED_ICON`
* The server owner will have the Partner badge.
* Certain very old partnered guilds are missing the `PARTNERED` feature, but will have the other features 

#### verified.txt - Verified servers (dis.gd/vfs)
 * Features: **`VERIFIED,`**`VANITY_URL, DISCOVERABLE, INVITE_SPLASH`

#### hypesquad-events.txt - HypeSquad Event Organizer servers (dis.gd/hypesquad)
* Features: `VANITY_URL, VIP_REGIONS, INVITE_SPLASH`
* The server owner will have the HypeSquad Events badge.

#### Community servers (dis.gd/communityservers)
* Features: `COMMUNITY, NEWS`

---- 

#### Guild feature glossary

* `ANIMATED_ICON` - Ability to upload an animated icon, similar to animated profile pictures for Nitro members. Displays on hover and invite links on desktop, and plays constantly on mobile.

* `BANNER` - Ability to set a [banner image](https://discord.com/developers/docs/game-and-server-management/vanity-perks#server-banner-background) that will display above the channel list.

* `COMMERCE` - Ability to create and use [store channels](https://discord.com/developers/docs/game-and-server-management/special-channels#store-channels).

* `COMMUNITY` - [Gain access to Server Discovery, Insights, Community Server News, and Announcement Channels](https://support.discord.com/hc/en-us/articles/360035969312-Public-Server-Guidelines).

* `DISCOVERABLE` - Visible in Server Discovery.

* `ENABLED_DISCOVERABLE_BEFORE` - Enabled Server Discovery before the Discovery Checklist launched.

* `DISCOVERABLE_DISABLED` — Guild is permanently removed from Discovery by Discord.

* ~~`FEATURABLE`~~ - Deprecated

* ~~`LURKABLE`~~ - Deprecated in favor of `PREVIEW_ENABLED`

* ~~`FORCE_RELAY`~~ Deprecated in favor of `RELAY_ENABLED`

* `INVITE_SPLASH` - Ability to set a background image that will display on all invite links.

* `MEMBER_LIST_DISABLED` - Hides the member list sidebar.

* `MEMBER_VERIFICATION_GATE_ENABLED` - Has member verification gate enabled, requiring new users to pass the verification gate before interacting with the server.

* `MORE_EMOJI` - Adds 150 extra emoji slots to each category (normal and animated emoji). Not used in server boosting.

* `NEWS` - Ability to create and use [~~news~~announcement channels](https://support.discord.com/hc/en-us/articles/360028384531-Channel-Following-FAQ) which can be followed, and shows the Annoucements analytics tab in the guild settings.

* `PARTNERED` - Partner badge near the server name and in mutual server lists. 

* `PREVIEW_ENABLED` - Enables [lurking](https://discord.com/developers/docs/game-and-server-management/special-channels#lurker-mode) via discovery and invites while logged out, as well as from crossposted announcements from news channels. 

* ~~`PUBLIC`~~ - Deprecated in favor of `COMMUNITY`

* ~~`PUBLIC_DISABLED`~~ - Deprecated in favor of `COMMUNITY`

* `RELAY_ENABLED` - Shards connections to the guild to different nodes that relay information between each other.

* `VANITY_URL` - Ability to set a vanity URL (custom discord.gg invite link).

* `VERIFIED` - Verification checkmark near the server name and in mutual server lists. 

* `VIP_REGIONS` - ~~Ability to use special voice regions with a better stability: US East VIP, US West VIP and Amsterdam VIP.~~ Deprecated, replaced with 384kbps max bitrate 

* `WELCOME_SCREEN_ENABLED` - Has welcome screen enabled, a modal shown to new joiners that features different channels and a short description of the guild.

* `TICKETED_EVENTS_ENABLED`— Ability to view and manage ticketed events.

* `MONETIZATION_ENABLED` — Has ticketed stages enabled.

* `MORE_STICKERS` — Sets the sticker slots to 60. Not used in server boosting.

* `HUB` — Not released

* `THREE_DAY_THREAD_ARCHIVE` — Ability to use three day archive time for threads.

* `SEVEN_DAY_THREAD_ARCHIVE` — Ability to use seven day archive time for threads.

* `PRIVATE_THREADS` — Ability to create private threads

* `THREADS_ENABLED_TESTING` — Used by bot developers to test their bots with threads in guilds with 5 or less members and a bot. Also gives the premium thread features.

* `THREADS_ENABLED` — Enabled threads early acess. 
----

#### Community program feature comparison 

| Community Program              | Vanity URL | Invite Splash | VIP Regions | Maximum Voice Bitrate | Server Owner Badge | Server Badge           | Extra Emoji Slots | Animated Icon | Banner | Lurking | Announcement Channels | Store Channels | Discovery          | Threads Extra Features   |
|--------------------------------|------------|---------------|-------------|-----------------------|--------------------|------------------------|-------------------|---------------|--------|---------|-----------------------|----------------|--------------------|--------------------------|
| Partner                        | ✓          | ✓             | ✓           | 384kbps               | Partner            | Partner icon           |                   |               | ✓      |         | ✓                     |                |                    |                          |
| Verification                   | ✓          |               | ✓           | 384kbps               |                    | Verification Checkmark |                   |               |        | ✓       | ✓                     |                | Enabled by default |                          |
by default |
| HypeSquad Event Organizer      | ✓          |               | ✓           | 128kbps               | HypeSquad Events   |                        |                   |               |        |         |                       |                |                    |                          |
| Open Source                    | ✓          | ✓             |             |                       |                    |                        |                   |               |        |         |                       |                |                    |                          |
| Server boosting tier 1         |            | ✓             |             | 128kbps               |                    | Boost tier 1 icon      | 50 \(100 total\)  | ✓             |        |         |                       |                |                    | Three Day Thread Archive |
| Server boosting tier 2         |            | ✓             |             | 256kbps               |                    | Boost tier 2 icon      | 100 \(150 total\) | ✓             | ✓      |         |                       |                |                    | Seven Day Thread Archive |
| Server boosting tier 3         | ✓          | ✓             |             | 384kbps               |                    | Boost tier 3 icon      | 200 \(250 total\) | ✓             | ✓      |         |                       |                |                    | Private Threads          |
| Commerce \(Developer License\) |            |               |             |                       |                    |                        |                   |               |        | ✓       | ✓                     | ✓              |                    |                          |
| Community                      |            |               |             |                       |                    |                        |                   |               |        | ✓       | ✓                     |                | Can apply          |                          |
