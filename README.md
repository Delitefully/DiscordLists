# DiscordLists
![](https://repository-images.githubusercontent.com/160703561/d3ad6f83-69e3-4726-928a-89b0804dca0e)

Community-sourced documentation and data collection project around the Discord app.

To check the features of a guild via an instant invite code, add the invite code to the following URL: https://discord.com/api/invite/[invitecode] 

e.g.: https://discord.com/api/invite/discord-townhall - the guild's features are `"ROLE_ICONS", "GUILD_COMMUNICATION_DISABLED_GUILDS", "FEATURABLE", "VANITY_URL", "CHANNEL_ICON_EMOJIS_GENERATED", "AUTOMOD_TRIGGER_USER_PROFILE", "PARTNERED", "TEXT_IN_STAGE_ENABLED", "GUILD_ONBOARDING_EVER_ENABLED", "NEW_THREAD_PERMISSIONS", "BANNER", "AUTOMOD_TRIGGER_SPAM_LINK_FILTER", "INVITE_SPLASH", "AUTO_MODERATION", "AUTOMOD_TRIGGER_KEYWORD_FILTER", "NEWS", "VIP_REGIONS", "GUILD_HOME_OVERRIDE", "HAS_DIRECTORY_ENTRY", "SOUNDBOARD", "PREVIEW_ENABLED", "THREADS_ENABLED", "DISCOVERABLE", "RESTRICT_SPAM_RISK_GUILDS", "ANIMATED_BANNER", "COMMUNITY", "GUILD_ONBOARDING_ADMIN_ONLY", "ANIMATED_ICON", "VERIFIED", "COMMUNITY_EXP_LARGE_GATED", "MEMBER_VERIFICATION_GATE_ENABLED", "WELCOME_SCREEN_ENABLED", "GUILD_WEB_PAGE_VANITY_URL", "MAX_FILE_SIZE_100_MB", "VIDEO_QUALITY_720_60FPS", "GUILD_TAGS", "AUDIO_BITRATE_128_KBPS", "ENHANCED_ROLE_COLORS", "VIDEO_QUALITY_1080_60FPS", "TIERLESS_BOOSTING_SYSTEM_MESSAGE", "TIERLESS_BOOSTING", "AUDIO_BITRATE_384_KBPS", "STAGE_CHANNEL_VIEWERS_300", "STAGE_CHANNEL_VIEWERS_150", "STAGE_CHANNEL_VIEWERS_50", "VIDEO_BITRATE_ENHANCED", "MEMBER_SAFETY_PAGE_ROLLOUT", "AUDIO_BITRATE_256_KBPS", "MAX_FILE_SIZE_50_MB"`
 
 *Cover image created by [Dhanish Danu](https://dhanish.xyz/)*.
 
----
 
#### [partners.txt](partners.txt) - Partnered servers ([dis.gd/partners](https://dis.gd/partners))
* Features: **`PARTNERED`**, `VANITY_URL`, `VIP_REGIONS`, `INVITE_SPLASH`, `BANNER`, `ANIMATED_ICON`
* The server owner will have the Partner badge.
* Certain very old partnered guilds are missing the `PARTNERED` feature but will have the other features 

#### [verified.txt](verified.txt) - Verified servers ([dis.gd/vfs](https://dis.gd/vfs))
 * Features: **`VERIFIED`**, `VANITY_URL`, `DISCOVERABLE`, `INVITE_SPLASH`

#### HypeSquad Event Organizer servers ([dis.gd/hypesquad](https://dis.gd/hypesquad))
* Features: **`VANITY_URL`**, `VIP_REGIONS`, `INVITE_SPLASH`
* The server owner will have the HypeSquad Events badge.

#### Community servers ([dis.gd/communityservers](https://dis.gd/communityservers))
* Features: **`COMMUNITY`**, `NEWS`

#### Student Hubs ([dis.gd/studenthubs](https://dis.gd/studenthubs))
* Features: **`HUB`**

# Guild Feature Glossary

Guild Features | Description
-------------- | ---------------
`ACTIVITIES_ALPHA` | Early access to voice channel activities
`ACTIVITIES_EMPLOYEE` | Employee-only access to voice channel activities
`ACTIVITIES_INTERNAL_DEV` | Internal development access to voice channel activities
`ACTIVITY_FEED_DISABLED_BY_USER` | User has disabled the activity feed feature
`ACTIVITY_FEED_ENABLED_BY_USER` | User has enabled the activity feed feature
`ANIMATED_BANNER` | Ability to upload an animated [banner image](https://support.discord.com/hc/en-us/articles/360028716472-Server-Banner-Background-Invite-Splash-Image) that will display above the channel list.
`ANIMATED_ICON` | Ability to upload an animated icon, similar to animated profile pictures for Nitro members. Displays on hover and invite links on desktop, and plays constantly on mobile.
`AUDIO_BITRATE_128_KBPS` | Enables 128kbps audio bitrate for voice channels
`AUDIO_BITRATE_256_KBPS` | Enables 256kbps audio bitrate for voice channels
`AUDIO_BITRATE_384_KBPS` | Enables 384kbps audio bitrate for voice channels
`AUTO_MODERATION` | Guild has set up auto moderation rules
`AUTOMOD_TRIGGER_KEYWORD_FILTER` | Server has enabled AutoMod keyword filtering
`AUTOMOD_TRIGGER_ML_SPAM_FILTER` | Given to guilds previously in the `2022-03_automod_trigger_ml_spam_filter` experiment overrides
`AUTOMOD_TRIGGER_SPAM_LINK_FILTER` | Server has enabled AutoMod spam link filtering
`AUTOMOD_TRIGGER_USER_PROFILE` | Server has enabled AutoMod for user profiles.
`BANNER` | Ability to set a [banner image](https://support.discord.com/hc/en-us/articles/360028716472-Server-Banner-Background-Invite-Splash-Image) that will display above the channel list. 
`BFG` | Internally documented as `big funky guild`
`BOOSTING_TIERS_EXPERIMENT_MEDIUM_GUILD` | Medium guild in boosting tiers experiment
`BOOSTING_TIERS_EXPERIMENT_SMALL_GUILD` | Small guild in boosting tiers experiment
`BOT_DEVELOPER_EARLY_ACCESS` | Enables early access features for bot and library developers.
`BURST_REACTIONS` | Enables burst reactions for the guild
`CHANNEL_BANNER` | Ability to set a channel banner that will display above the Channel Information sidebar.
`CHANNEL_EMOJIS_GENERATED` | 
`CHANNEL_HIGHLIGHTS` | 
`CHANNEL_HIGHLIGHTS_DISABLED` | 
`CHANNEL_ICON_EMOJIS_GENERATED` | 
`COMMERCE` | Ability to create and use [store channels](https://discord.com/developers/docs/game-and-server-management/special-channels#store-channels).
`COMMUNITY` | [Gain access to Server Discovery, Insights, Community Server News, and Announcement Channels](https://support.discord.com/hc/en-us/articles/360035969312-Public-Server-Guidelines).
`COMMUNITY_CANARY` | Community canary testing features
`COMMUNITY_EXP_LARGE_GATED` | 
`COMMUNITY_EXP_LARGE_UNGATED` | 
`COMMUNITY_EXP_MEDIUM` | 
`CREATOR_ACCEPTED_NEW_TERMS` | The server owner accepted the new monetization terms.
`CREATOR_MONETIZABLE` | Given to guilds that enabled role subscriptions through the manual approval system
`CREATOR_MONETIZABLE_DISABLED` | 
`CREATOR_MONETIZABLE_PENDING_NEW_OWNER_ONBOARDING` | The server has monetization enabled, but the new owner has not completed the onboarding process.
`CREATOR_MONETIZABLE_PROVISIONAL` | 
`CREATOR_MONETIZABLE_RESTRICTED` | 
`CREATOR_MONETIZABLE_WHITEGLOVE` | 
`CREATOR_MONETIZATION_APPLICATION_ALLOWLIST` | 
`CREATOR_STORE_PAGE` | 
`DEVELOPER_SUPPORT_SERVER` | Given to guilds that are set as the support server in [App Directory](https://support-dev.discord.com/hc/en-us/articles/6378525413143-App-Directory-App-profile-page).
`DISCOVERABLE` | Visible in Server Discovery.
`DISCOVERABLE_DISABLED` | Guild is permanently removed from Discovery by Discord.
`ENABLED_DISCOVERABLE_BEFORE` | Given to servers that have enabled Discovery at any point.
`ENABLED_MODERATION_EXPERIENCE_FOR_NON_COMMUNITY` | Moves the member list from the guild settings to the member tab for non-community guilds.
`ENHANCED_ROLE_COLORS` | Allows the server to use [enhanced role styles](https://support.discord.com/hc/en-us/articles/31444213087255-Enhanced-Role-Styles).
`EXPOSED_TO_ACTIVITIES_WTP_EXPERIMENT` | Given to guilds previously in the `2021-11_activities_baseline_engagement_bundle` experiment overrides
`EXPOSED_TO_BOOSTING_TIERS_EXPERIMENT` | 
`FEATURABLE` | Previously used to control which servers were displayed under the "Featured" category in Discovery
`FORCE_RELAY` | Shards connections to the guild to different nodes that relay information between each other.
`FORWARDING_DISABLED` | Blocks from the API and UX side ability to forward messages from the selected server.
`GENERATED_TEST_GUILD` | 
`GENSHIN_L30` | Related to Genshin Impact
`GUESTS_ENABLED` | Guild can create guest invites.
`GUILD_AUTOMOD_DEFAULT_LIST` | Given to guilds in the `2022-03_guild_automod_default_list` experiment overrides
`GUILD_COMMUNICATION_DISABLED_GUILDS` | Given to guilds previously in the `2021-11_guild_communication_disabled_guilds` experiment overrides
`GUILD_MEMBER_VERIFICATION_EXPERIMENT` | Given to guilds previously in the `2021-11_member_verification_manual_approval` experiment
`GUILD_ONBOARDING` | Guild has enabled onboarding
`GUILD_ONBOARDING_ADMIN_ONLY` | 
`GUILD_ONBOARDING_EVER_ENABLED` | Guild has ever enabled onboarding
`GUILD_ONBOARDING_HAS_PROMPTS` | 
`GUILD_PRODUCTS` | Given to guilds previously in the `2023-04_server_products` experiment overrides
`GUILD_PRODUCTS_ALLOW_ARCHIVED_FILE` | Allows a guild to upload archive files like `.zip` and `.tar.gz` to the server products.
`GUILD_ROLE_SUBSCRIPTIONS` | Given to guilds previously in the `2021-06_guild_role_subscriptions` experiment overrides
`GUILD_ROLE_SUBSCRIPTION_PURCHASE_FEEDBACK_LOOP` | Given to guilds previously in the `2022-05_mobile_web_role_subscription_purchase_page` experiment overrides
`GUILD_ROLE_SUBSCRIPTION_TIER_TEMPLATE` | 
`GUILD_ROLE_SUBSCRIPTION_TRIALS` | Given to guilds previously in the `2022-01_guild_role_subscription_trials` experiment overrides
`GUILD_SERVER_GUIDE` | Guild has enabled [server guide](https://support.discord.com/hc/en-us/articles/13497665141655)
`GUILD_TAGS` | Ability to create a [server tag](https://support.discord.com/hc/en-us/articles/31444248479639-Server-Tags)
`GUILD_WEB_PAGE_VANITY_URL` | 
`HAD_EARLY_ACTIVITIES_ACCESS` | Server previously had access to voice channel activities and can bypass the boost level requirement
`HAS_DIRECTORY_ENTRY` | Guild is in a directory channel.
`HIDE_FROM_EXPERIMENT_UI` | 
`HUB` | [Student Hubs](https://dis.gd/studenthubs) contain a directory channel that let you find school-related, student-run servers for your school or university.
`INCREASED_THREAD_LIMIT` | Allows the server to have 1,000+ active threads
`INTERNAL_EMPLOYEE_ONLY` | Restricts the guild so that only users with the staff flag can join.
`INVITES_DISABLED` | [Prevents new members from joining](https://support.discord.com/hc/en-us/articles/8458903738647) and shows an error when attemping to join the server.
`INVITE_SPLASH` | Ability to set a background image that will display on all invite links.
`LEADERBOARD_ENABLED` | 
`LINKED_TO_HUB` | The server is linked to a [Student Hub](https://dis.gd/studenthubs) and has a directory channel.
`LURKABLE` | The server is a lurkable server, which means that users can see the server without joining it.
`MARKETPLACES_CONNECTION_ROLES` | 
`MAX_FILE_SIZE_50_MB` | Increases maximum file upload size to 50MB
`MAX_FILE_SIZE_100_MB` | Increases maximum file upload size to 100MB
`MEMBER_LIST_DISABLED` | Created for the Fortnite server blackout event on Oct 13, 2019, when viewing the member list it would show "There's nothing to see here.".
`MEMBER_PROFILES` | Allows members to customize their avatar, banner and bio for that server.
`MEMBER_SAFETY_PAGE_ROLLOUT` | Assigns the experiment of the `Member Safety` panel and lockdowns to the guild
`MEMBER_VERIFICATION_GATE_ENABLED` | Has member verification gate enabled, requiring new users to pass the verification gate before interacting with the server.
`MEMBER_VERIFICATION_MANUAL_APPROVAL` | 
`MEMBER_VERIFICATION_ROLLOUT_TEST` | Used for testing member verification features
`MOBILE_WEB_ROLE_SUBSCRIPTION_PURCHASE_PAGE` | Given to guilds previously in the `2022-05_mobile_web_role_subscription_purchase_page` experiment overrides
`MONETIZATION_ENABLED` | Allows the server to set a team in dev portal to receive role subscription payouts
`MORE_EMOJI` | Adds 150 extra emoji slots to each category (normal and animated emoji). Not used in server boosting.
`MORE_SOUNDBOARD` | 
`MORE_STICKERS` | Adds 60 total sticker slots no matter how many it had before. Not used in server boosting.
`NEWS` | Ability to create and use [~~news~~ announcement channels](https://support.discord.com/hc/en-us/articles/360028384531) which can be followed, and shows the Announcements analytics tab in the guild settings.
`NEW_THREAD_PERMISSIONS` | Guild has [new thread permissions](https://support.discord.com/hc/en-us/articles/4403205878423#h_01FDGC4JW2D665Y230KPKWQZPN).
`NON_COMMUNITY_RAID_ALERTS` | Non-community guild is opt-in to raid alerts
`PARTNERED` | Partner badge near the server name and in mutual server lists.
`PREMIUM_TIER_3_OVERRIDE` | Forces the server to server boosting level 3
`PREVIEW_ENABLED` | Allows a user to view the server without passing membership gating.
`PRIVATE_THREADS` | Ability to create private threads. Is now a base feature.
`PRODUCTS_AVAILABLE_FOR_PURCHASE` | Guild has server products available for purchase
`PUBLIC` | Deprecated in favor of `COMMUNITY`
`PUBLIC_DISABLED` | Deprecated in favor of `COMMUNITY`
`RAID_ALERTS_DISABLED` | Guild is opt-out from raid alerts
`RAID_ALERTS_ENABLED` | Deprecated in favor of `RAID_ALERTS_DISABLED` since Discord switched to an [opt-out system](https://github.com/discord/discord-api-docs/pull/5778#discussion_r1160146853).
`RAPIDASH_TEST` | 
`RAPIDASH_TEST_REBIRTH` | Internal testing feature
`RELAY_ENABLED` | Shards connections to the guild to different nodes that relay information between each other.
`REPORT_TO_MOD_PILOT` | Enables reporting to moderator pilot features
`REPORT_TO_MOD_SURVEY` | Enables moderator survey features
`RESTRICT_SPAM_RISK_GUILDS` | 
`ROLE_ICONS` | Ability to set an image or emoji as a role icon.
`ROLE_SUBSCRIPTIONS_AVAILABLE_FOR_PURCHASE` | Allows servers members to purchase role subscriptions.
`ROLE_SUBSCRIPTIONS_ENABLED` | Ability to view and manage role subscriptions.
`ROLE_SUBSCRIPTIONS_ENABLED_FOR_PURCHASE` | 
`SERVER_PROFILES_TEST` | Testing feature for server profiles
`SEVEN_DAY_THREAD_ARCHIVE` | Ability to use seven-day archive time for threads.
`SHARD` | 
`SOUNDBOARD` | Given to guilds previously in the `2021-12_soundboard` experiment overrides
`STAGE_CHANNEL_VIEWERS_50` | Increases stage channel viewer limit to 50
`STAGE_CHANNEL_VIEWERS_150` | Increases stage channel viewer limit to 150
`STAGE_CHANNEL_VIEWERS_300` | Increases stage channel viewer limit to 300
`SUMMARIES_DISABLED_BY_USER` | The user has disabled the summaries feature.
`SUMMARIES_ENABLED` | Given to guilds in the `2023-02_p13n_summarization` experiment overrides
`SUMMARIES_ENABLED_BY_USER` | The user has enabled the summaries feature.
`SUMMARIES_ENABLED_GA` | Given to guilds in the `2023-02_p13n_summarization` experiment overrides
`SUMMARIES_LONG_LOOKBACK` | 
`SUMMARIES_OPT_OUT_EXPERIENCE` | 
`SUMMARIES_PAUSED` | 
`TEXT_IN_STAGE_ENABLED` | Shows a chat button inside stage channels that opens a dedicated text channel in a sidebar similar to thread view.
`TEXT_IN_VOICE_ENABLED` | Show a chat button inside voice channels that opens a dedicated text channel in a sidebar similar to thread view.
`THREADS_ENABLED` | Enabled threads early access.
`THREADS_ENABLED_TESTING` | Used by bot developers to test their bots with threads in guilds with 5 or less members and a bot. ~~Also gives the premium thread features.~~
`THREAD_DEFAULT_AUTO_ARCHIVE_DURATION` | Unknown, presumably used for testing changes to the thread default auto archive duration.
`THREADS_ONLY_CHANNEL` | Given to guilds previously in the `2021-07_threads_only_channel` experiment overrides
`THREE_DAY_THREAD_ARCHIVE` | Ability to use three-day archive time for threads.
`TIERLESS_BOOSTING` | Ability to use the new boosting system, which includes `Server Tags` and `Enhanced Role Styles`
`TIERLESS_BOOSTING_CLIENT_TEST` | Given to guilds previously in the `2025-02_skill_trees` experiment overrides
`TIERLESS_BOOSTING_SYSTEM_MESSAGE` | Related to `2025-06_tierless_boosting_system_message`
`TIERLESS_BOOSTING_TEST` | Given to guilds previously in the `2025-02_skill_trees` experiment overrides
`VALORANT_L30` | Related to Valorant
`VANITY_URL` | Ability to set a vanity URL (custom discord.gg invite link).
`VERIFIED` | Verification checkmark near the server name and in mutual server lists.
`VIDEO_BITRATE_ENHANCED` | Enables enhanced video bitrate
`VIDEO_QUALITY_720_60FPS` | Enables 720p 60fps video quality
`VIDEO_QUALITY_1080_60FPS` | Enables 1080p 60fps video quality
`VOICE_CHANNEL_EFFECTS` | Given to guilds previously in the `2022-06_voice_channel_effects` experiment overrides
`VOICE_IN_THREADS` | 
`WELCOME_SCREEN_ENABLED` | Has welcome screen enabled, a modal shown to new joiners that features different channels, and a short description of the guild.

Deprecated Guild Features | Description
------------ | -------------
`APPLICATION_COMMAND_PERMISSIONS_V2` | Guild has opted-in to the [new Application Command Permission logic](https://discord.com/developers/docs/change-log#nov-17-2022) before it was applied to all servers.
`CHANNEL_BANNER` | Ability to set a channel banner that will display above the Channel Information sidebar.
`CLAN` | The server is a clan server
`CLAN_DISCOVERY_DISABLED` | Clan server discovery disabled
`CLAN_PILOT_GENSHIN` | Part of the Genshin Impact clan pilot program
`CLAN_PILOT_VALORANT` | Part of the Valorant clan pilot program
`CLAN_SAFETY_REVIEW_DISABLED` | Clan safety review disabled
`CLYDE_DISABLED` | Given when a server administrator disables ClydeAI for the guild
`CLYDE_ENABLED` | Server has enabled Clyde AI
`CLYDE_EXPERIMENT_ENABLED` | Enables ClydeAI for the guild
`COMMERCE` | Ability to create and use [store channels](https://discord.com/developers/docs/game-and-server-management/special-channels#store-channels).
`EXPOSED_TO_BOOSTING_TIERS_EXPERIMENT` |
`FEATURABLE` | Previously used to control which servers were displayed under the "Featured" category in Discovery
`FORCE_RELAY` | Shards connections to the guild to different nodes that relay information between each other.
`GUILD_HOME_DEPRECATION_OVERRIDE` | 
`GUILD_HOME_OVERRIDE` | Gives the guild access to the Home feature, enables Treatment 2 of the `2022-01_home_tab_guild` experiment overrides
`GUILD_HOME_TEST` | Gives the guild access to the Home feature, enables Treatment 1 of the `2022-01_home_tab_guild` experiment
`LURKABLE` | N/A
`MEMBER_LIST_DISABLED` | Created for the Fortnite server blackout event on Oct 13, 2019, when viewing the member list it would show "There's nothing to see here.".
`PRIVATE_THREADS` | Ability to create private threads. Is now a base feature.
`PUBLIC` | Deprecated in favor of `COMMUNITY`
`PUBLIC_DISABLED` | Deprecated in favor of `COMMUNITY`
`RAID_ALERTS_ENABLED` | Deprecated in favor of `RAID_ALERTS_DISABLED` since Discord switched to an [opt-out system](https://github.com/discord/discord-api-docs/pull/5778#discussion_r1160146853).
`SEVEN_DAY_THREAD_ARCHIVE` | Ability to use seven-day archive time for threads.
`SHARED_CANVAS_FRIENDS_AND_FAMILY_TEST` | Given to guilds previously in the `2023-01_shared_canvas` experiment overrides
`THREE_DAY_THREAD_ARCHIVE` | Ability to use three-day archive time for threads.
`TICKETED_EVENTS_ENABLED` | Ability to view and manage ticketed events.
`TICKETING_ENABLED` | 
`VIP_REGIONS` | ~~Ability to use special voice regions with better stability: US East VIP, US West VIP, and Amsterdam VIP.~~ Deprecated, replaced with 384kbps max bitrate

#### Community program feature comparison 

| Community Program              | Vanity URL | Invite Splash | VIP Regions | Maximum Voice Bitrate | Server Owner Badge | Server Badge            | Extra Emoji Slots | Animated Icon | Banner | Lurking | Announcement Channels | Store Channels | Directory Channels| Discovery          | Role Icons |
|--------------------------------|------------|---------------|-------------|-----------------------|--------------------|-------------------------|-------------------|---------------|--------|---------|-----------------------|----------------|-------------------|--------------------|------------|
| Partner                        | Yes        | Yes           | Yes         | 384kbps               | Partner            | Partner icon            | Not applicable    | No            | Yes    | No      | Yes                   | No             | No                | No                 | No         |
| Verification                   | Yes        | No            | Yes         | 384kbps               | Not applicable     | Verification checkmark* | Not applicable    | No            | No     | Yes     | Yes                   | No             | No                | Enabled by default | No         |
| HypeSquad Event Organizer      | Yes        | No            | Yes         | 128kbps               | HypeSquad Events   | Not applicable          | Not applicable    | No            | No     | No      | No                    | No             | No                | No                 | No         |
| Open Source                    | Yes        | Yes           | No          | Not applicable        | Not applicable     | Not applicable          | Not applicable    | No            | Yes    | No      | No                    | No             | No                | No                 | No         |
| Server boosting tier 1         | No         | Yes           | No          | 128kbps               | Not applicable     | Boost tier 1 icon       | 50 \(100 total\)  | Yes           | No     | No      | No                    | No             | No                | No                 | No         |
| Server boosting tier 2         | No         | Yes           | No          | 256kbps               | Not applicable     | Boost tier 2 icon       | 100 \(150 total\) | Yes           | Yes    | No      | No                    | No             | No                | No                 | Yes        |
| Server boosting tier 3         | Yes        | Yes           | No          | 384kbps               | Not applicable     | Boost tier 3 icon  i    | 200 \(250 total\) | Yes           | Yes    | No      | No                    | No             | No                | No                 | Yes        |
| Commerce \(Developer License\) | No         | No            | No          | Not applicable        | Not applicable     | Not applicable          | Not applicable    | No            | No     | Yes     | Yes                   | Yes            | No                | No                 | No         |
| Community                      | No         | No            | No          | Not applicable        | Not applicable     | Not applicable          | Not applicable    | No            | No     | No      | Yes                   | No             | No                | Can apply          | No         |
| Student Hub                    | No         | No            | No          | Not applicable        | Not applicable     | Directory channel icon  | Not applicable    | No            | No     | No      | No                    | No             | Yes               | No                 | No         |

\* If the guild is a hub this will be a directory channel icon with a green instead of a grey background instead.

#### Server Boost Level Comparison

| Feature               | Base         | Level 1         | Level 2              | Level 3                                |
|-----------------------|--------------|-----------------|----------------------|----------------------------------------|
| Emotes/Emojis         | 50           | 100             | 150                  | 250                                    |
| Sticker Slots         | 5            | 15              | 30                   | 60                                     |
| Upload Limit          | 8MB          | 8MB             | 50MB for all members | 100MB for all members                  |
| Soundboard Slots      | 8            | 24              | 36                   | 48                                     |
| Stream Quality        | 720p @ 30fps | 720p @ 60fps    | 720p @ 60fps         | 720p @ 60fps                           |
| Audio Quality         | 96kbps       | 128kbps         | 256kbps              | 384kbps                                |
| Go Live Streams       | 720p @ 60fps | 720p @ 60fps    | 1080p @ 60fps        | 1080p @ 60fps                          |
| Vanity URL            | No           | No              | No                   | Yes (custom discord.gg link)           |
| Animated Server Icon  | No           | Yes             | Yes                  | Yes                                    |
| Server Banner         | No           | No              | Static               | Animated                               |
| Custom Role Icons     | No           | No              | Yes                  | Yes                                    |
| Video Channel Members | 25           | 25              | 25                   | 25                                     |
| Stage Channel Viewers | 10,000       | 10,000          | 10,000               | 10,000                                 |
| Video Stage Seats     | 50           | 50              | 150                  | 300 (+30 per additional boost past 14) |

#### Additional Server Limits

**These limits apply to all server boost levels:**

- **Total Member Count:** 25 million
- **Server Categories:** 50 max
- **Channels (total):** 500 max (includes voice, text, and categories)
- **Channels per Category:** 50 max
- **Roles:** 250 max
- **Unique Invite Codes:** 999 per server
- **Audit Log Retention:** 45 days
- **Followed Announcement Channels:** 10 per channel
- **Offline Member List:**
  - Hidden when server reaches 1,000+ members
  - Reappears when server drops below 800 members
- **Threads:**
  - 1,000 members max in private/public threads
  - 10 roles max mentioned in private threads
- **Rate Limits:**
  - No inherent message limits (except when slow mode enabled)
  - No limit on raised hands in stage channels
  - 1 shared screen per stage (no camera limit)

**Notes:**
- All servers get 8MB file upload by default (increased to 50MB at Level 2, 100MB at Level 3)
- Stage channel viewer limits are the same across all tiers (10,000)
- Video channel member limits remain at 25 for all tiers
- The "Video Stage Seats" at Level 3 continue increasing by +30 for each boost beyond 14
