## 🏳️ Discord Flags 

### User Flags
| Flag             | Bitwise | Internal Name                | Description                                                 | Public | Documented |
|------------------|:-------:|------------------------------|-------------------------------------------------------------|:------:|:----------:|
| 1                | 1<<0    | STAFF                        | Discord Employee                                            | ✔      | ✔         |
| 2                | 1<<1    | PARTNER                      | Discord Partner                                             | ✔      | ✔         |
| 4                | 1<<2    | HYPESQUAD                    | HypeSquad Events                                            | ✔      | ✔         |
| 8                | 1<<3    | BUG_HUNTER_LEVEL_1           | Bug Hunter Level 1                                          | ✔      | ✔         |
| 16               | 1<<4    | MFA_SMS                      | SMS recovery for 2FA enabled                                | ❌     | ❌        |
| 32               | 1<<5    | PREMIUM_PROMO_DISMISSED      | Dismissed Nitro promotion                                   | ❌     | ❌        |
| 64               | 1<<6    | HYPESQUAD_ONLINE_HOUSE_1     | HypeSquad Online House Bravery                              | ✔      | ✔         |
| 128              | 1<<7    | HYPESQUAD_ONLINE_HOUSE_2     | HypeSquad Online House Brilliance                           | ✔      | ✔         |
| 256              | 1<<8    | HYPESQUAD_ONLINE_HOUSE_3     | HypeSquad Online House Balance                              | ✔      | ✔         |
| 512              | 1<<9    | PREMIUM_EARLY_SUPPORTER      | Early Supporter                                             | ✔      | ✔         |
| 1024             | 1<<10   | TEAM_USER                    | Team User                                                   | ✔      | ✔         |
| 2048             | 1<<11   | INTERNAL_APPLICATION         | Relates to partner/verification applications.               | ❌     | ❌        |
| 4096             | 1<<12   | SYSTEM                       | System User                                                 | ✔      | ✔         |
| 8192             | 1<<13   | HAS_UNREAD_URGENT_MESSAGES   | Has an unread system message                                | ❌     | ❌        |
| 16384            | 1<<14   | BUG_HUNTER_LEVEL_2           | Bug Hunter Level 2                                          | ✔      | ✔         |
| 32768            | 1<<15   | UNDERAGE_DELETED             | Pending deletion for being underage in DOB prompt           | ❌     | ❌        |
| 65536            | 1<<16   | VERIFIED_BOT                 | Verified Bot                                                | ✔      | ✔         |
| 131072           | 1<<17   | VERIFIED_DEVELOPER           | Early Verified Bot Developer                                | ✔      | ✔         |
| 262144           | 1<<18   | CERTIFIED_MODERATOR          | Moderator Programs Alumni                                   | ✔      | ✔         |
| 524288           | 1<<19   | BOT_HTTP_INTERACTIONS        | Bot has set an interactions endpoint url                    | ✔      | ✔         |
| 1048576          | 1<<20   | SPAMMER                      | User is disabled for being a spammer                        | ✔      | ❌        |
| 2097152          | 1<<21   | DISABLE_PREMIUM              | Disables Nitro Features                                     | ❌     | ❌        |
| 4194304          | 1<<22   | ACTIVE_DEVELOPER             | User is an active developer                                 | ✔      | ✔         |
| 8589934592       | 1<<33   | HIGH_GLOBAL_RATE_LIMIT       | Account has a high global ratelimit                         | ❌     | ❌        |
| 17179869184      | 1<<34   | DELETED                      | Account has been deleted                                    | ❌     | ❌        |
| 34359738368      | 1<<35   | DISABLED_SUSPICIOUS_ACTIVITY | Account has been disabled for suspicious activity           | ❌     | ❌        |
| 68719476736      | 1<<36   | SELF_DELETED                 | Account was deleted by the user                             | ❌     | ❌        |
| 137438953472     | 1<<37   | PREMIUM_DISCRIMINATOR        | User has a premium discriminator                            | ✔      | ❌        |
| 274877906944     | 1<<38   | USED_DESKTOP_CLIENT          | User has used the desktop client                            | ✔      | ❌        |
| 549755813888     | 1<<39   | USED_WEB_CLIENT              | User has used the web client                                | ✔      | ❌        |
| 1099511627776    | 1<<40   | USED_MOBILE_CLIENT           | User has used the mobile client                             | ✔      | ❌        |
| 2199023255552    | 1<<41   | DISABLED                     | User is currently temporarily or permanently disabled       | ❌     | ❌        |
| 8796093022208    | 1<<43   | VERIFIED_EMAIL               | User has a verified email                                   | ✔      | ❌        |
| 17592186044416   | 1<<44   | QUARANTINED                  | User account is quarantined                                 | ❌     | ❌        |
| 1125899906842624 | 1<<50   | COLLABORATOR                 | User is a collaborator and has staff permissions            | ✔      | ❌        |
| 2251799813685248 | 1<<51   | RESTRICTED_COLLABORATOR      | User is a restricted collaborator and has staff permissions | ✔      | ❌        |

### Purchased User Flags
| Flag     | Bitwise | Internal Name | Description                          |
|----------|:-------:| ------------- |--------------------------------------|
| 1        | 1<<0    | NITRO_CLASSIC | The user has purchased Nitro classic |
| 2        | 1<<1    | NITRO         | The user has purchased regular Nitro |
| 4        | 1<<2    | GUILD_BOOST   | The user has purchased a guild boost |
| 8        | 1<<3    | NITRO_BASIC   | The user has purchased Nitro basic   |

### Premium Usage User Flags
| Flag     | Bitwise | Internal Name         | Description                                  |
|----------|:-------:|-----------------------|----------------------------------------------|
| 1        | 1<<0    | PREMIUM_DISCRIMINATOR | The user has utilized premium discriminators |
| 2        | 1<<1    | ANIMATED_AVATAR       | The user has utilized animated avatars       |
| 4        | 1<<2    | PROFILE_BANNER        | The user has utilized profile banners        |

### Application Flags
| Flag     | Bitwise | Internal Name                                 | Description                                                                                            | Public | Documented |
|----------|:-------:|-----------------------------------------------|--------------------------------------------------------------------------------------------------------|:------:|:----------:|
| 2        | 1<<1    | EMBEDDED_RELEASED                             | Indicates if an embedded app is available to play                                                      | ✔      | ❌         |
| 4        | 1<<2    | MANAGED_EMOJI                                 | Indicates if the app has the ability to create Twitch-style emojis                                     | ❌     | ❌         |
| 8        | 1<<3    | EMBEDDED_IAP                                  | Embedded app has the ability to create in-app purchases                                                | ✔      | ❌         |
| 16       | 1<<4    | GROUP_DM_CREATE                               | App has permission to create group DMs                                                                 | ❌     | ❌         |
| 32       | 1<<5    | RPC_PRIVATE_BETA                              | Allows the application to access the local RPC server                                                  | ❌     | ❌         |
| 64       | 1<<6    | APPLICATION_AUTO_MODERATION_RULE_CREATE_BADGE | Powered by AutoMod                                                                                     | ✔      | ❌         |
| 256      | 1<<8    | ALLOW_ASSETS                                  | Allows the app to create activity assets                                                               | ❌     | ❌         |
| 512      | 1<<9    | ALLOW_ACTIVITY_ACTION_SPECTATE                | Allows the app to enable activity spectating                                                           | ❌     | ❌         |
| 1024     | 1<<10   | ALLOW_ACTIVITY_ACTION_JOIN_REQUEST            | Allows the app to enable join requests for activities                                                  | ❌     | ❌         |
| 2048     | 1<<11   | RPC_HAS_CONNECTED                             | Indicates whether the app has accessed the local RPC server before                                     | ❌     | ❌         |
| 4096     | 1<<12   | GATEWAY_PRESENCE                              | Intent required for bots in 100 or more servers to receive presence_update events                      | ✔      | ✔          |
| 8192     | 1<<13   | GATEWAY_PRESENCE_LIMITED                      | Intent required for bots in under 100 servers to receive presence_update events                        | ✔      | ✔          |
| 16384    | 1<<14   | GATEWAY_GUILD_MEMBERS                         | Intent required for bots in 100 or more servers to receive member-related events like guild_member_add | ✔      | ✔          |
| 32768    | 1<<15   | GATEWAY_GUILD_MEMBERS_LIMITED                 | Intent required for bots in under 100 servers to receive member-related events like guild_member_add   | ✔      | ✔          |
| 65536    | 1<<16   | VERIFICATION_PENDING_GUILD_LIMIT              | Indicates unusual growth of an app that prevents verification.                                         | ❌     | ✔          |
| 131072   | 1<<17   | EMBEDDED                                      | Indicates if an app is embedded within the Discord client                                              | ❌     | ✔          |
| 262144   | 1<<18   | GATEWAY_MESSAGE_CONTENT                       | Intent required for bots in 100 or more servers to receive message content                             | ✔      | ✔          |
| 524288   | 1<<19   | GATEWAY_MESSAGE_CONTENT_LIMITED               | Intent required for bots in under 100 servers to receive message content                               | ✔      | ✔          |
| 1048576  | 1<<20   | EMBEDDED_FIRST_PARTY                          | Indicates a first-party embedded app                                                                   | ❌     | ❌         |
| 2097152  | 1<<21   | UNKNOWN_FLAG_21                               |                                                                                                        | ✔      | ❌         |
| 8388608  | 1<<23   | APPLICATION_COMMAND_BADGE                     | Indicates if an app has registered global application commands                                         | ✔      | ✔          |
| 16777216 | 1<<24   | ACTIVE                                        | Indicates if an app is considered active                                                               | ❌     | ✔          |
| 67108864 | 1<<26   | IFRAME_MODAL                                  | Allows the app to use IFrame modals                                                                    | ✔      | ❌         |

### Activity Flags
| Flag | Bitwise | Internal Name               |
|------|:-------:|-----------------------------|
| 1    | 1<<0    | INSTANCE                    |
| 2    | 1<<1    | JOIN                        |
| 4    | 1<<2    | SPECTATE                    |
| 8    | 1<<3    | JOIN_REQUEST                |
| 16   | 1<<4    | SYNC                        |
| 32   | 1<<5    | PLAY                        |
| 64   | 1<<6    | PARTY_PRIVACY_FRIENDS       |
| 128  | 1<<7    | PARTY_PRIVACY_VOICE_CHANNEL |
| 256  | 1<<8    | EMBEDDED                    |

### Channel Flags
| Flag  | Bitwise | Internal Name                              | Description                                                                                            |
|-------|:-------:|--------------------------------------------|--------------------------------------------------------------------------------------------------------|
| 1     | 1<<0    | GUILD_FEED_REMOVED                         | This guild channel has been removed from the guild's feed                                              |
| 2     | 1<<1    | PINNED                                     | This thread is pinned to the top of its parent forum channel                                           |
| 4     | 1<<2    | ACTIVE_CHANNELS_REMOVED                    | This guild channel has been removed from the guild's active channels                                   |
| 16    | 1<<4    | REQUIRE_TAG                                | This forum channel requires a tag to create threads in                                                 |
| 32    | 1<<5    | SPAM                                       | This channel is marked as spam                                                                         |
| 128   | 1<<7    | GUILD_RESOURCE_CHANNEL                     | This guild channel is used as a read-only resource for onboarding and is not shown in the channel list |
| 256   | 1<<8    | CLYDE_AI                                   | This thread is created by Clyde AI, which has full access to all message content                       |
| 512   | 1<<9    | SCHEDULED_FOR_DELETION                     | This guild channel is scheduled for deletion and is not shown in the UI                                |
| 1024  | 1<<10   | MEDIA_CHANNEL                              | Indicates that this channel is a media channel                                                         |
| 2048  | 1<<11   | SUMMARIES_DISABLED                         | Indicates that ai powered summaries are disabled for this channel                                      |
| 4096  | 1<<12   | APPLICATION_SHELF_CONSENT                  | This that the private channel's recipients consented to the application shelf                          |
| 8192  | 1<<13   | ROLE_SUBSCRIPTION_TEMPLATE_PREVIEW_CHANNEL | Indicates that this channel is part of a role subscription template preview                            |
| 16384 | 1<<14   | BROADCASTING                               | Indicates if there is a global broadcast on that channel                                             |
| 32768 | 1<<15   | HIDE_MEDIA_DOWNLOAD_OPTIONS                | Hides the media download options for media channels                                                    |

### System Channel Flags
| Flag | Bitwise | Internal Name                                            | Description                                                   |
|------|:-------:|----------------------------------------------------------|---------------------------------------------------------------|
| 1    | 1<<0    | SUPPRESS_JOIN_NOTIFICATIONS                              | Suppress member join notifications                            |
| 2    | 1<<1    | SUPPRESS_PREMIUM_SUBSCRIPTIONS                           | Suppress premium subscription (boost) notifications           |
| 4    | 1<<2    | SUPPRESS_GUILD_REMINDER_NOTIFICATIONS                    | Suppress guild setup tips                                     |
| 8    | 1<<3    | SUPPRESS_JOIN_NOTIFICATION_REPLIES                       | Hide member join sticker reply buttons                        |
| 16   | 1<<4    | SUPPRESS_ROLE_SUBSCRIPTION_PURCHASE_NOTIFICATIONS        | Suppress role subscription purchase and renewal notifications |
| 32   | 1<<5    | SUPPRESS_ROLE_SUBSCRIPTION_PURCHASE_NOTIFICATION_REPLIES | Hide role subscription sticker reply buttons                  |

### Thread Member Flags
| Flag | Bitwise | Internal Name  | Description                                                          |
|------|:-------:|----------------|----------------------------------------------------------------------|
| 1    | 1<<0    | HAS_INTERACTED | The user has interacted with the thread                              |
| 2    | 1<<1    | ALL_MESSAGES   | The user receives notifications for all messages                     |
| 4    | 1<<2    | ONLY_MENTIONS  | The user receives notifications only for messages that @mention them |
| 8    | 1<<3    | NO_MESSAGES    | The user does not receive any notifications                          |

### Message Flags
| Flag | Bitwise | Internal Name                          | Description                                                                       |
|------|:-------:|----------------------------------------|-----------------------------------------------------------------------------------|
| 1    | 1<<0    | CROSSPOSTED                            | This message has been published to subscribed channels (via Channel Following)    |
| 2    | 1<<1    | IS_CROSSPOST                           | This message originated from a message in another channel (via Channel Following) |
| 4    | 1<<2    | SUPPRESS_EMBEDS                        | Embeds will not be included when serializing this message                         |
| 8    | 1<<3    | SOURCE_MESSAGE_DELETED                 | The source message for this crosspost has been deleted (via Channel Following)    |
| 16   | 1<<4    | URGENT                                 | This message came from the urgent message system                                  |
| 32   | 1<<5    | HAS_THREAD                             | This message has an associated thread, with the same ID as the message            |
| 64   | 1<<6    | EPHEMERAL                              | This message is only visible to the user who invoked the interaction              |
| 128  | 1<<7    | LOADING                                | This message is an interaction response and the bot is "thinking"                 |
| 256  | 1<<8    | FAILED_TO_MENTION_SOME_ROLES_IN_THREAD | Some roles were not mentioned and added to the thread                             |
| 1024 | 1<<10   | SHOULD_SHOW_LINK_NOT_DISCORD_WARNING   | This message contains a link that impersonates Discord                            |
| 4096 | 1<<12   | SUPPRESS_NOTIFICATIONS                 | This message will not trigger push and desktop notifications                      |
| 8192 | 1<<13   | VOICE_MESSAGE                          | This message's audio attachments are rendered as voice messages                   |

### Guild Member Flags
| Flag | Bitwise | Internal Name           | Description                                                |
|------|:-------:|-------------------------|------------------------------------------------------------|
| 1    | 1<<0    | DID_REJOIN              | This guild member has left and rejoined the guild          |
| 2    | 1<<1    | COMPLETED_ONBOARDING    | This guild member has completed onboarding                 |
| 4    | 1<<2    | BYPASSES_VERIFICATION\* | This guild member bypasses guild verification requirements |
| 8    | 1<<3    | STARTED_ONBOARDING      | This guild member has started onboarding                   |

### SKU Flags
| Flag | Bitwise | Internal Name                  | Description                                                                      |
|------|:-------:|--------------------------------|----------------------------------------------------------------------------------|
| 1    | 1<<0    | PREMIUM_PURCHASE               | Whether the SKU is a premium purchase                                            |
| 2    | 1<<1    | HAS_FREE_PREMIUM_CONTENT       | Whether the SKU is free premium content                                          |
| 4    | 1<<2    | AVAILABLE                      | Whether the SKU is available for purchase                                        |
| 8    | 1<<3    | PREMIUM_AND_DISTRIBUTION       | Whether the SKU is a premium or distribution product                             |
| 16   | 1<<4    | STICKER_PACK                   | Whether the SKU is a premium sticker pack                                        |
| 32   | 1<<5    | GUILD_ROLE_SUBSCRIPTION        | Whether the SKU is a guild role subscription                                     |
| 64   | 1<<6    | PREMIUM_SUBSCRIPTION           | Whether the SKU is a Discord premium subscription or related first-party product |
| 128  | 1<<7    | APPLICATION_GUILD_SUBSCRIPTION | Whether the SKU is a application subscription                                    |
| 256  | 1<<8    | APPLICATION_USER_SUBSCRIPTION  | Whether the SKU is a application subscription                                    |
