# DiscordLists

Tracking servers in Discord's community programs.

To check the features of a server via an invite, paste the server's invite code in the following URL: https://discordapp.com/api/invite/[invitecode] 

e.g.: https://discordapp.com/api/invite/events - the server's features are `VIP_REGIONS, BANNER, VERIFIED, VANITY_URL, INVITE_SPLASH`.
 
----
 
#### partners.txt - Partnered servers (dis.gd/partners)
* Features: **`PARTNERED,`**`VANITY_URL, VIP_REGIONS, INVITE_SPLASH`
* The server owner will have the Partner badge.

#### verified.txt - Verified servers (dis.gd/vfs)
* Features: **`VERIFIED,`**`VANITY_URL, VIP_REGIONS, INVITE_SPLASH, FEATURABLE, DISCOVERABLE, LURKABLE, BANNER`

#### hypesquad-events.txt - HypeSquad Event Organizer servers (dis.gd/hypesquad)
* Features: `VANITY_URL, VIP_REGIONS, INVITE_SPLASH`
* The server owner will have the HypeSquad events badge.

---- 

#### Guild feature glossary

* `ANIMATED_ICON` - Ability to upload an animated icon, similar to animated profile pictures for Nitro members. Displays on hover and invite links on desktop, and plays constantly on mobile.

* `BANNER` - Ability to set a [banner image](https://discordapp.com/developers/docs/game-and-server-management/vanity-perks#server-banner-background) that will display above the channel list.

* `COMMERCE` - Ability to create and use [store channels](https://discordapp.com/developers/docs/game-and-server-management/special-channels#store-channels).

* `DISCOVERABLE` - Visible in Server Discovery.

* `FEATURABLE` - Makes the server featurable in the activity feed and other special promotions.

* `INVITE_SPLASH` - Ability to set a background image that will display on all invite links.

* `LURKABLE` - Enables normal and guest [lurking](https://discordapp.com/developers/docs/game-and-server-management/special-channels#special-channels-and-lurker-mode).

* `MORE_EMOJI` - Adds 150 extra emoji slots to each category (normal and animated). Not used in server boosting.

* `NEWS` - Ability to create and use [news channels](https://discordapp.com/developers/docs/game-and-server-management/special-channels#news-channels).

* `PARTNERED` - Partner checkmark near the server name and in mutual server lists. 

* `VANITY_URL` - Ability to set a vanity URL (custom discord.gg invite link).

* `VERIFIED` - Verification checkmark near the server name and in mutual server lists. 

* `VIP_REGIONS` - Ability to use special voice regions with a better stability: US East VIP, US West VIP and Amsterdam VIP.

----

#### Community program feature comparison 

| Community Program            | Vanity URL | Invite Splash | VIP Regions | Maximum Voice Bitrate | Server Owner Badge | Server Checkmark       | Extra Emoji Slots  | Animated Icon | Banner | Lurking | News Channels | Store Channels |
|------------------------------|------------|---------------|-------------|-----------------------|--------------------|------------------------|--------------------|---------------|--------|---------|---------------|----------------|
| Partner                      | ✓          | ✓             | ✓           | 128kbps               | Partner            | Partner Checkmark      |                    |               |        |         |               |                |
| Verification                 | ✓          | ✓             | ✓           | 128kbps               |                    | Verification Checkmark |                    |               | ✓      | ✓       |               |                |
| HypeSquad Event Organizer    | ✓          |               | ✓           | 128kbps               | HypeSquad Events   |                        |                    |               |        |         |               |                |
| Open Source                  | ✓          | ✓             |             |                       |                    |                        |                    |               |        |         |               |                |
| Server boosting tier 1       |            | ✓             |             | 128kbps               |                    |                        | 50 (100 total)     | ✓             |        |         |               |                |
| Server boosting tier 2       |            | ✓             |             | 256kbps               |                    |                        | 100 (150 total)    | ✓             | ✓      |         |               |                |
| Server boosting tier 3       | ✓          | ✓             |             | 384kbps               |                    |                        | 200 (250 total)    | ✓             | ✓      |         |               |                |
| Commerce (Developer License) |            |               |             |                       |                    |                        |                    |               |        | ✓       | ✓             | ✓              |
