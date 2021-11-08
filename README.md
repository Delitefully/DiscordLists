# DiscordLists

Tracking servers in Discord's community programs.

To check the features of a guild via an instant invite code, add the invite code to the following URL: https://discord.com/api/invite/[invitecode] 

e.g.: https://discord.com/api/invite/discord-townhall - the guild's features are `INVITE_SPLASH", "NEWS", "DISCOVERABLE", "BANNER", "VERIFIED", "VANITY_URL", "ANIMATED_ICON", "FEATURABLE", "VIP_REGIONS", "COMMUNITY`.
 
----
 
#### partners.txt - Partnered servers ([dis.gd/partners](https://dis.gd/partners))
* Features: **`PARTNERED,`**`VANITY_URL, VIP_REGIONS, INVITE_SPLASH, BANNER, ANIMATED_ICON`
* The server owner will have the Partner badge.
* Certain very old partnered guilds are missing the `PARTNERED` feature but will have the other features 

#### verified.txt - Verified servers ([dis.gd/vfs](dis.gd/vfs))
 * Features: **`VERIFIED,`**`VANITY_URL, DISCOVERABLE, INVITE_SPLASH`

#### HypeSquad Event Organizer servers ([dis.gd/hypesquad](https://dis.gd/hypesquad))
* Features: **`VANITY_URL, `**`VIP_REGIONS, INVITE_SPLASH`
* The server owner will have the HypeSquad Events badge.

#### Community servers ([dis.gd/communityservers](https://dis.gd/communityservers))
* Features: **`COMMUNITY, `**`NEWS`

#### Student Hubs ([dis.gd/studenthubs](https://dis.gd/studenthubs))
* Features: **`HUB`**

---- 

#### Guild feature glossary

* `ANIMATED_BANNER` - Ability to upload an animated [banner image](https://support.discord.com/hc/en-us/articles/360028716472-Server-Banner-Background-Invite-Splash-Image) that will display above the channel list.

* `ANIMATED_ICON` - Ability to upload an animated icon, similar to animated profile pictures for Nitro members. Displays on hover and invite links on desktop, and plays constantly on mobile.

* `BANNER` - Ability to set a [banner image](https://support.discord.com/hc/en-us/articles/360028716472-Server-Banner-Background-Invite-Splash-Image) that will display above the channel list.

* `CHANNEL_BANNER` - Ability to set a channel banner that will display above the member list.

* `COMMERCE` - Ability to create and use [store channels](https://discord.com/developers/docs/game-and-server-management/special-channels#store-channels).

* `COMMUNITY` - [Gain access to Server Discovery, Insights, Community Server News, and Announcement Channels](https://support.discord.com/hc/en-us/articles/360035969312-Public-Server-Guidelines).

* `DISCOVERABLE_DISABLED` — Guild is permanently removed from Discovery by Discord.

* `DISCOVERABLE` - Visible in Server Discovery.

* `ENABLED_DISCOVERABLE_BEFORE` - Given to servers that have enabled Discovery at any point.

* ~~`FEATURABLE`~~ - Deprecated

* ~~`FORCE_RELAY`~~ — Shards connections to the guild to different nodes that relay information between each other.

* `HAS_DIRECTORY_ENTRY` — Guild is in a directory channel.

* `HUB` — [Student Hubs](https://dis.gd/studenthubs) contain a directory channel that let you find school-related, student-run servers for your school or university.

* `INTERNAL_EMPLOYEE_ONLY` - Restricts the guild so that only users with the staff flag can join.

* `INVITE_SPLASH` - Ability to set a background image that will display on all invite links.

* ~~`LURKABLE`~~ - Deprecated

* `MEMBER_LIST_DISABLED` - Hides the member list sidebar.

* `MEMBER_VERIFICATION_GATE_ENABLED` - Has member verification gate enabled, requiring new users to pass the verification gate before interacting with the server.

* `MONETIZATION_ENABLED` — Allows the server to set a team in dev portal to cash out ticketed stage payouts

* `MORE_EMOJI` - Adds 150 extra emoji slots to each category (normal and animated emoji). Not used in server boosting.

* `MORE_STICKERS` — Adds 60 total sticker slots no matter how many it had before. Not used in server boosting.

* `NEWS` - Ability to create and use [~~news~~announcement channels](https://support.discord.com/hc/en-us/articles/360028384531-Channel-Following-FAQ) which can be followed, and shows the Announcements analytics tab in the guild settings.

* `NEW_THREAD_PERMISSIONS` — Guild has [new thread permissions](https://support.discord.com/hc/en-us/articles/4403205878423-Threads-FAQ#h_01FDGC4JW2D665Y230KPKWQZPN).

* `PARTNERED` - Partner badge near the server name and in mutual server lists.

* `PREMIUM_TIER_3_OVERRIDE` - Forces the server to server boosting level 3 (specifically created by Discord Staff Member "Jethro" for their personal server)

* `PREVIEW_ENABLED` - Allows a user to view the server without passing membership gating.

* `PRIVATE_THREADS` — Ability to create private threads

* ~~`PUBLIC_DISABLED`~~ - Deprecated in favor of `COMMUNITY`

* ~~`PUBLIC`~~ - Deprecated in favor of `COMMUNITY`

* `RELAY_ENABLED` - Shards connections to the guild to different nodes that relay information between each other.

* `ROLE_ICONS` - Ability to set an image or emoji as a role icon.

* `ROLE_SUBSCRIPTIONS_ENABLED` - Ability to view and manage role subscriptions.

* `ROLE_SUBSCRIPTIONS_AVAILABLE_FOR_PURCHASE` - Allows servers members to purchase role subscriptions.

* `SEVEN_DAY_THREAD_ARCHIVE` — Ability to use seven-day archive time for threads.

* `TEXT_IN_VOICE_ENABLED` - Show a chat button inside voice channels that opens a dedicated text channel in a sidebar similar to thread view.

* `THREADS_ENABLED_TESTING` — Used by bot developers to test their bots with threads in guilds with 5 or less members and a bot. ~~Also gives the premium thread features.~~

* `THREADS_ENABLED` — Enabled threads early access.

* `THREAD_DEFAULT_AUTO_ARCHIVE_DURATION` - Unknown, presumably used for testing changes to the thread default auto archive duration.

* `THREE_DAY_THREAD_ARCHIVE` — Ability to use three-day archive time for threads.

* `TICKETED_EVENTS_ENABLED`— Ability to view and manage ticketed events.

* `VANITY_URL` - Ability to set a vanity URL (custom discord.gg invite link).

* `VERIFIED` - Verification checkmark near the server name and in mutual server lists.

* `VIP_REGIONS` - ~~Ability to use special voice regions with better stability: US East VIP, US West VIP, and Amsterdam VIP.~~ Deprecated, replaced with 384kbps max bitrate

* `WELCOME_SCREEN_ENABLED` - Has welcome screen enabled, a modal shown to new joiners that features different channels, and a short description of the guild.

----

#### Community program feature comparison 

| Community Program              | Vanity URL | Invite Splash | VIP Regions | Maximum Voice Bitrate | Server Owner Badge | Server Badge            | Extra Emoji Slots | Animated Icon | Banner | Lurking | Announcement Channels | Store Channels | Directory Channels| Discovery          | Threads Extra Features   | Role Icons |
|--------------------------------|------------|---------------|-------------|-----------------------|--------------------|-------------------------|-------------------|---------------|--------|---------|-----------------------|----------------|-------------------|--------------------|--------------------------|------------|
| Partner                        | ✓          | ✓             | ✓           | 384kbps               | Partner            | Partner icon            |                   |               | ✓      |         | ✓                     |                |                   |                    |                          |            |
| Verification                   | ✓          |               | ✓           | 384kbps               |                    | Verification checkmark* |                   |               |        | ✓       | ✓                     |                |                   | Enabled by default |                          |            |
| HypeSquad Event Organizer      | ✓          |               | ✓           | 128kbps               | HypeSquad Events   |                         |                   |               |        |         |                       |                |                   |                    |                          |            |
| Open Source                    | ✓          | ✓             |             |                       |                    |                         |                   |               |        |         |                       |                |                   |                    |                          |            |
| Server boosting tier 1         |            | ✓             |             | 128kbps               |                    | Boost tier 1 icon       | 50 \(100 total\)  | ✓             |        |         |                       |                |                   |                    | 3 Day Thread Archive     |            |
| Server boosting tier 2         |            | ✓             |             | 256kbps               |                    | Boost tier 2 icon       | 100 \(150 total\) | ✓             | ✓      |         |                       |                |                   |                    | 7 Day Thread Archive     | ✓          |
| Server boosting tier 3         | ✓          | ✓             |             | 384kbps               |                    | Boost tier 3 icon  i    | 200 \(250 total\) | ✓             | ✓      |         |                       |                |                   |                    | Private Threads          | ✓          |
| Commerce \(Developer License\) |            |               |             |                       |                    |                         |                   |               |        | ✓       | ✓                     | ✓              |                   |                    |                          |            |
| Community                      |            |               |             |                       |                    |                         |                   |               |        | ✓       | ✓                     |                |                   | Can apply          |                          |            |
| Student Hub                    |            |               |             |                       |                    | Directory channel icon  |                   |               |        |         |                       |                | ✓                 |                    |                          |            |

\* If the guild is a hub this will be a directory channel icon with a green instead of a grey background instead.
