# DiscordLists
![](https://repository-images.githubusercontent.com/160703561/d3ad6f83-69e3-4726-928a-89b0804dca0e)

Community-sourced documentation and data collection project around the Discord app.

To check the features of a guild via an instant invite code, add the invite code to the following URL: https://discord.com/api/invite/[invitecode] 

e.g.: https://discord.com/api/invite/discord-townhall - the guild's features are `"ANIMATED_ICON", "AUTO_MODERATION", "MEMBER_VERIFICATION_GATE_ENABLED", "PREVIEW_ENABLED", "BANNER", "NEW_THREAD_PERMISSIONS", "WELCOME_SCREEN_ENABLED", "PARTNERED", "VIP_REGIONS", "VERIFIED", "AUTOMOD_TRIGGER_KEYWORD_FILTER", "VANITY_URL", "AUTOMOD_TRIGGER_SPAM_LINK_FILTER", "ANIMATED_BANNER", "INVITE_SPLASH", "THREE_DAY_THREAD_ARCHIVE", "ROLE_ICONS", "PRIVATE_THREADS", "MEMBER_PROFILES", "THREADS_ENABLED", "NEWS", "SEVEN_DAY_THREAD_ARCHIVE", "COMMUNITY", "FEATURABLE", "GUILD_COMMUNICATION_DISABLED_GUILDS"`
 
 *Cover image created by [Dhanish Danu](https://dhanish.xyz/)*.
 
----
 
#### partners.txt - Partnered servers ([dis.gd/partners](https://dis.gd/partners))
* Features: **`PARTNERED,`**`VANITY_URL, VIP_REGIONS, INVITE_SPLASH, BANNER, ANIMATED_ICON`
* The server owner will have the Partner badge.
* Certain very old partnered guilds are missing the `PARTNERED` feature but will have the other features 

#### verified.txt - Verified servers ([dis.gd/vfs](https://dis.gd/vfs))
 * Features: **`VERIFIED,`**`VANITY_URL, DISCOVERABLE, INVITE_SPLASH`

#### HypeSquad Event Organizer servers ([dis.gd/hypesquad](https://dis.gd/hypesquad))
* Features: **`VANITY_URL, `**`VIP_REGIONS, INVITE_SPLASH`
* The server owner will have the HypeSquad Events badge.

#### Community servers ([dis.gd/communityservers](https://dis.gd/communityservers))
* Features: **`COMMUNITY, `**`NEWS`

#### Student Hubs ([dis.gd/studenthubs](https://dis.gd/studenthubs))
* Features: **`HUB`**

# Guild Feature Glossary

Guild Features | Description
-------------- | ---------------
`ACTIVITIES_ALPHA` |
`ACTIVITIES_EMPLOYEE` | 
`ACTIVITIES_INTERNAL_DEV` |
`ANIMATED_BANNER` | Ability to upload an animated [banner image](https://support.discord.com/hc/en-us/articles/360028716472-Server-Banner-Background-Invite-Splash-Image) that will display above the channel list.
`ANIMATED_ICON` | Ability to upload an animated icon, similar to animated profile pictures for Nitro members. Displays on hover and invite links on desktop, and plays constantly on mobile.
`APPLICATION_COMMAND_PERMISSIONS_V2` | Guild is using the [new Application Command Permission logic](https://discord.com/developers/docs/change-log#nov-17-2022) .
`AUTO_MODERATION` | Ability to enable AutoMod.
`AUTOMOD_TRIGGER_KEYWORD_FILTER` |
`AUTOMOD_TRIGGER_ML_SPAM_FILTER` | Given to guilds previously in the `2022-03_automod_trigger_ml_spam_filter` experiment overrides
`AUTOMOD_TRIGGER_SPAM_LINK_FILTER` |
`BANNER` | Ability to set a [banner image](https://support.discord.com/hc/en-us/articles/360028716472-Server-Banner-Background-Invite-Splash-Image) that will display above the channel list. 
`BFG` |  
`BOOSTING_TIERS_EXPERIMENT_MEDIUM_GUILD` |
`BOOSTING_TIERS_EXPERIMENT_SMALL_GUILD` |
`BOT_DEVELOPER_EARLY_ACCESS` | Enables early access features for bot and library developers.
`BURST_REACTIONS` | Enables burst reactions for the guild
`COMMUNITY_EXP_LARGE_GATED` |
`COMMUNITY_EXP_LARGE_UNGATED` |
`COMMUNITY_EXP_MEDIUM` |
`CHANNEL_HIGHLIGHTS` |
`CHANNEL_HIGHLIGHTS_DISABLED` | 
`COMMUNITY` | [Gain access to Server Discovery, Insights, Community Server News, and Announcement Channels](https://support.discord.com/hc/en-us/articles/360035969312-Public-Server-Guidelines).
`CREATOR_MONETIZABLE` |
`CREATOR_MONETIZABLE_DISABLED` |
`CREATOR_MONETIZABLE_PROVISIONAL` |
`CREATOR_MONETIZABLE_RESTRICTED` | 
`CREATOR_MONETIZABLE_WHITEGLOVE` |
`CREATOR_MONETIZATION_APPLICATION_ALLOWLIST` |
`CREATOR_STORE_PAGE` |
`DEVELOPER_SUPPORT_SERVER` | Given to guilds that are set as the support server in [App Directory](https://support-dev.discord.com/hc/en-us/articles/6378525413143-App-Directory-App-profile-page).
`DISCOVERABLE_DISABLED` | Guild is permanently removed from Discovery by Discord.
`DISCOVERABLE` | Visible in Server Discovery.
`ENABLED_DISCOVERABLE_BEFORE` | Given to servers that have enabled Discovery at any point.
`EXPOSED_TO_ACTIVITIES_WTP_EXPERIMENT` | Given to guilds previously in the `2021-11_activities_baseline_engagement_bundle` experiment overrides
`GUILD_AUTOMOD_DEFAULT_LIST` | Given to guilds in the `2022-03_guild_automod_default_list` experiment overrides
`GUILD_COMMUNICATION_DISABLED_GUILDS` | Given to guilds previously in the `2021-11_guild_communication_disabled_guilds` experiment overrides
`GUILD_HOME_OVERRIDE` | Gives the guild access to the Home feature, enables Treatment 2 of the `2022-01_home_tab_guild` experiment overrides
`GUILD_HOME_TEST` | Gives the guild access to the Home feature, enables Treatment 1 of the `2022-01_home_tab_guild` experiment
`GUILD_MEMBER_VERIFICATION_EXPERIMENT` | Given to guilds previously in the `2021-11_member_verification_manual_approval` experiment
`GUILD_ONBOARDING` | Guild has access to the Onboarding feature
`GUILD_ONBOARDING_ADMIN_ONLY` | 
`GUILD_ONBOARDING_EVER_ENABLED` | 
`GUILD_ONBOARDING_HAS_PROMPTS` |
`GUILD_ROLE_SUBSCRIPTIONS` | Given to guilds previously in the `2021-06_guild_role_subscriptions` experiment overrides
`GUILD_ROLE_SUBSCRIPTION_PURCHASE_FEEDBACK_LOOP` | Given to guilds previously in the `2022-05_mobile_web_role_subscription_purchase_page` experiment overrides
`GUILD_ROLE_SUBSCRIPTION_TRIALS` | Given to guilds previously in the `2022-01_guild_role_subscription_trials` experiment overrides
`HAD_EARLY_ACTIVITIES_ACCESS` | Server previously had access to voice channel activities and can bypass the boost level requirement
`HAS_DIRECTORY_ENTRY` | Guild is in a directory channel.
`HUB` | [Student Hubs](https://dis.gd/studenthubs) contain a directory channel that let you find school-related, student-run servers for your school or university.
`INCREASED_THREAD_LIMIT` | Allows the server to have 1,000+ active threads
`INTERNAL_EMPLOYEE_ONLY` | Restricts the guild so that only users with the staff flag can join.
`INVITE_SPLASH` | Ability to set a background image that will display on all invite links.
`INVITES_DISABLED` | [Prevents new members from joining](https://support.discord.com/hc/en-us/articles/8458903738647-Pause-Invites-FAQ) and shows an error when attemping to join the server.
`LINKED_TO_HUB` | 
`MARKETPLACES_CONNECTION_ROLES` | 
`MEMBER_PROFILES` | Allows members to customize their avatar, banner and bio for that server.
`MEMBER_VERIFICATION_GATE_ENABLED` | Has member verification gate enabled, requiring new users to pass the verification gate before interacting with the server.
`MEMBER_VERIFICATION_MANUAL_APPROVAL` | 
`MOBILE_WEB_ROLE_SUBSCRIPTION_PURCHASE_PAGE` | Given to guilds previously in the `2022-05_mobile_web_role_subscription_purchase_page` experiment overrides
`MONETIZATION_ENABLED` | Allows the server to set a team in dev portal to receive role subscription payouts
`MORE_EMOJI` | Adds 150 extra emoji slots to each category (normal and animated emoji). Not used in server boosting.
`MORE_STICKERS` | Adds 60 total sticker slots no matter how many it had before. Not used in server boosting.
`NEWS` | Ability to create and use [~~news~~ announcement channels](https://support.discord.com/hc/en-us/articles/360028384531-Channel-Following-FAQ) which can be followed, and shows the Announcements analytics tab in the guild settings.
`NEW_THREAD_PERMISSIONS` | Guild has [new thread permissions](https://support.discord.com/hc/en-us/articles/4403205878423-Threads-FAQ#h_01FDGC4JW2D665Y230KPKWQZPN).
`PARTNERED` | Partner badge near the server name and in mutual server lists.
`PREMIUM_TIER_3_OVERRIDE` | Forces the server to server boosting level 3
`PREVIEW_ENABLED` | Allows a user to view the server without passing membership gating.
`RAID_ALERTS_ENABLED` | 
`RELAY_ENABLED` | Shards connections to the guild to different nodes that relay information between each other.
`RESTRICT_SPAM_RISK_GUILDS` |
`ROLE_ICONS` | Ability to set an image or emoji as a role icon.
`ROLE_SUBSCRIPTIONS_AVAILABLE_FOR_PURCHASE` | Allows servers members to purchase role subscriptions.
`ROLE_SUBSCRIPTIONS_ENABLED` | Ability to view and manage role subscriptions.
`ROLE_SUBSCRIPTIONS_ENABLED_FOR_PURCHASE` | 
`SOUNDBOARD` | Given to guilds previously in the `2021-12_soundboardl` experiment overrides
`TEXT_IN_STAGE_ENABLED` | 
`TEXT_IN_VOICE_ENABLED` | Show a chat button inside voice channels that opens a dedicated text channel in a sidebar similar to thread view.
`THREADS_ENABLED_TESTING` | Used by bot developers to test their bots with threads in guilds with 5 or less members and a bot. ~~Also gives the premium thread features.~~
`THREADS_ENABLED` | Enabled threads early access.
`THREAD_DEFAULT_AUTO_ARCHIVE_DURATION` | Unknown, presumably used for testing changes to the thread default auto archive duration.
`THREADS_ONLY_CHANNEL` | Given to guilds previously in the `2021-07_threads_only_channel` experiment overrides
`TICKETED_EVENTS_ENABLED` | Ability to view and manage ticketed events.
`TICKETING_ENABLED` | 
`VANITY_URL` | Ability to set a vanity URL (custom discord.gg invite link).
`VERIFIED` | Verification checkmark near the server name and in mutual server lists.
`VIP_REGIONS` | ~~Ability to use special voice regions with better stability: US East VIP, US West VIP, and Amsterdam VIP.~~ Deprecated, replaced with 384kbps max bitrate
`VOICE_CHANNEL_EFFECTS` |  Given to guilds previously in the `2022-06_voice_channel_effects` experiment overrides
`VOICE_IN_THREADS` | 
`WELCOME_SCREEN_ENABLED` | Has welcome screen enabled, a modal shown to new joiners that features different channels, and a short description of the guild.

Deprecated Guild Features | Description
------------ | -------------
`CHANNEL_BANNER` | Ability to set a channel banner that will display above the Channel Information sidebar.
`COMMERCE` | Ability to create and use [store channels](https://discord.com/developers/docs/game-and-server-management/special-channels#store-channels).
`EXPOSED_TO_BOOSTING_TIERS_EXPERIMENT` |
`FEATURABLE` | Previously used to control which servers were displayed under the "Featured" category in Discovery
`FORCE_RELAY` | Shards connections to the guild to different nodes that relay information between each other.
`LURKABLE` | N/A
`MEMBER_LIST_DISABLED` | Created for the Fortnite server blackout event on Oct 13, 2019, when viewing the member list it would show "There's nothing to see here.".
`PRIVATE_THREADS` | Ability to create private threads. Is now a base feature.
`PUBLIC` | Deprecated in favor of `COMMUNITY`
`PUBLIC_DISABLED` | Deprecated in favor of `COMMUNITY`
`SEVEN_DAY_THREAD_ARCHIVE` | Ability to use seven-day archive time for threads.
`THREE_DAY_THREAD_ARCHIVE` | Ability to use three-day archive time for threads.


#### Community program feature comparison 

| Community Program              | Vanity URL | Invite Splash | VIP Regions | Maximum Voice Bitrate | Server Owner Badge | Server Badge            | Extra Emoji Slots | Animated Icon | Banner | Lurking | Announcement Channels | Store Channels | Directory Channels| Discovery          | Threads Extra Features   | Role Icons |
|--------------------------------|------------|---------------|-------------|-----------------------|--------------------|-------------------------|-------------------|---------------|--------|---------|-----------------------|----------------|-------------------|--------------------|--------------------------|------------|
| Partner                        | ✓          | ✓             | ✓           | 384kbps               | Partner            | Partner icon            |                   |               | ✓      |         | ✓                     |                |                   |                    |                          |            |
| Verification                   | ✓          |               | ✓           | 384kbps               |                    | Verification checkmark* |                   |               |        | ✓       | ✓                     |                |                   | Enabled by default |                          |            |
| HypeSquad Event Organizer      | ✓          |               | ✓           | 128kbps               | HypeSquad Events   |                         |                   |               |        |         |                       |                |                   |                    |                          |            |
| Open Source                    | ✓          | ✓             |             |                       |                    |                         |                   |               |✓       |         |                       |                |                   |                    |                          |            |
| Server boosting tier 1         |            | ✓             |             | 128kbps               |                    | Boost tier 1 icon       | 50 \(100 total\)  | ✓             |        |         |                       |                |                   |                    |      |            |
| Server boosting tier 2         |            | ✓             |             | 256kbps               |                    | Boost tier 2 icon       | 100 \(150 total\) | ✓             | ✓      |         |                       |                |                   |                    |      | ✓          |
| Server boosting tier 3         | ✓          | ✓             |             | 384kbps               |                    | Boost tier 3 icon  i    | 200 \(250 total\) | ✓             | ✓      |         |                       |                |                   |                    | Private Threads          | ✓          |
| Commerce \(Developer License\) |            |               |             |                       |                    |                         |                   |               |        | ✓       | ✓                     | ✓              |                   |                    |                          |            |
| Community                      |            |               |             |                       |                    |                         |                   |               |        | ✓       | ✓                     |                |                   | Can apply          |                          |            |
| Student Hub                    |            |               |             |                       |                    | Directory channel icon  |                   |               |        |         |                       |                | ✓                 |                    |                          |            |

\* If the guild is a hub this will be a directory channel icon with a green instead of a grey background instead.
