## 🏳️ Discord Flags 
### User Flags
| Flag             | Bitwise | Internal Name                | Description                                                 | Public | Documented |
|------------------|:-------:|------------------------------|-------------------------------------------------------------|:------:|:----------:|
| 1                | 1<<0    | STAFF                        | Discord Employee                                            | ✓      | ✓         |
| 2                | 1<<1    | PARTNER                      | Discord Partner                                             | ✓      | ✓         |
| 4                | 1<<2    | HYPESQUAD                    | HypeSquad Events                                            | ✓      | ✓         |
| 8                | 1<<3    | BUG_HUNTER_LEVEL_1           | Bug Hunter Level 1                                          | ✓      | ✓         |
| 16               | 1<<4    | MFA_SMS                      | SMS recovery for 2FA enabled                                |        |            |
| 32               | 1<<5    | PREMIUM_PROMO_DISMISSED      | Dismissed Nitro promotion                                   |        |            |
| 64               | 1<<6    | HYPESQUAD_ONLINE_HOUSE_1     | HypeSquad Online House Bravery                              | ✓      | ✓         |
| 128              | 1<<7    | HYPESQUAD_ONLINE_HOUSE_2     | HypeSquad Online House Brilliance                           | ✓      | ✓         |
| 256              | 1<<8    | HYPESQUAD_ONLINE_HOUSE_3     | HypeSquad Online House Balance                              | ✓      | ✓         |
| 512              | 1<<9    | PREMIUM_EARLY_SUPPORTER      | Early Supporter                                             | ✓      | ✓         |
| 1024             | 1<<10   | TEAM_USER                    | Team User                                                   | ✓      | ✓         |
| 2048             | 1<<11   | INTERNAL_APPLICATION         | Relates to partner/verification applications.               |        |            |
| 4096             | 1<<12   | SYSTEM                       | System User                                                 | ✓      | ✓         |
| 8192             | 1<<13   | HAS_UNREAD_URGENT_MESSAGES   | Has an unread system message                                |        |            |
| 16384            | 1<<14   | BUG_HUNTER_LEVEL_2           | Bug Hunter Level 2                                          | ✓      | ✓         |
| 32768            | 1<<15   | UNDERAGE_DELETED             | Pending deletion for being underage in DOB prompt           |        |            |
| 65536            | 1<<16   | VERIFIED_BOT                 | Verified Bot                                                | ✓      | ✓         |
| 131072           | 1<<17   | VERIFIED_DEVELOPER           | Early Verified Bot Developer                                | ✓      | ✓         |
| 262144           | 1<<18   | CERTIFIED_MODERATOR          | Moderator Programs Alumni                                   | ✓      | ✓         |
| 524288           | 1<<19   | BOT_HTTP_INTERACTIONS        | Bot has set an interactions endpoint url                    | ✓      | ✓         |
| 1048576          | 1<<20   | SPAMMER                      | User is disabled for being a spammer                        | ✓      |            |
| 2097152          | 1<<21   | DISABLE_PREMIUM              | Disables Nitro Features                                     |        |            |
| 4194304          | 1<<22   | ACTIVE_DEVELOPER             | User is an active developer                                 | ✓      | ✓         |
| 8589934592       | 1<<33   | HIGH_GLOBAL_RATE_LIMIT       | Account has a high global ratelimit                         |        |            |
| 17179869184      | 1<<34   | DELETED                      | Account has been deleted                                    |        |            |
| 34359738368      | 1<<35   | DISABLED_SUSPICIOUS_ACTIVITY | Account has been disabled for suspicious activity           |        |            |
| 68719476736      | 1<<36   | SELF_DELETED                 | Account was deleted by the user                             |        |            |
| 137438953472     | 1<<37   | PREMIUM_DISCRIMINATOR        | User has a premium discriminator                            | ✓      |            |
| 274877906944     | 1<<38   | USED_DESKTOP_CLIENT          | User has used the desktop client                            | ✓      |            |
| 549755813888     | 1<<39   | USED_WEB_CLIENT              | User has used the web client                                | ✓      |            |
| 1099511627776    | 1<<40   | USED_MOBILE_CLIENT           | User has used the mobile client                             | ✓      |            |
| 2199023255552    | 1<<41   | DISABLED                     | User is currently temporarily or permanently disabled       |        |            |
| 8796093022208    | 1<<43   | VERIFIED_EMAIL               | User has a verified email                                   | ✓      |            |
| 17592186044416   | 1<<44   | QUARANTINED                  | User account is quarantined                                 |        |            |
| 1125899906842624 | 1<<50   | COLLABORATOR                 | User is a collaborator and has staff permissions            | ✓      |            |
| 2251799813685248 | 1<<51   | RESTRICTED_COLLABORATOR      | User is a restricted collaborator and has staff permissions | ✓      |            |

### Application Flags
| Flag             | Bitwise | Internal Name                | Description                                                 | Public | Documented |
|------------------|:-------:|------------------------------|-------------------------------------------------------------|:------:|:----------:|
| 2                | 1<<1    | EMBEDDED_RELEASED            | Embedded app is available to play                           |        |            |
| 4                | 1<<2    | MANAGED_EMOJI                | App has the ability to create Twitch-style emojis           |        |            |
| 8                | 1<<3    | EMBEDDED_IAP                 | Embedded app has the ability to create in-app purchases     |        |            |
| 16               | 1<<4    | GROUP_DM_CREATE              | App has permission to create group DMs                      |        |            |
| 32               | 1<<5    | RPC_PRIVATE_BETA             | Allows the application to access the local RPC server       |        |            |
| 64               | 1<<6    | APPLICATION_AUTO_MODERATION_RULE_CREATE_BADGE | Powered by AutoMod                         |        |            |
| 256              | 1<<8    | ALLOW_ASSETS                 | Allows the app to create activity assets                    |        |            |
| 512              | 1<<9    | ALLOW_ACTIVITY_ACTION_SPECTATE | Allows the app to enable activity spectating              |        |            |
| 1024             | 1<<10   | ALLOW_ACTIVITY_ACTION_JOIN_REQUEST | Allows the app to enable join requests for activities |        |            |
| 2048             | 1<<11   | RPC_HAS_CONNECTED            | Indicates whether the app has accessed the local RPC server before |        |            |
| 4096             | 1<<12   | GATEWAY_PRESENCE             |                                                             |        |            |
| 8192             | 1<<13   | GATEWAY_PRESENCE_LIMITED     |                                                             |        |            |
| 16384            | 1<<14   | GATEWAY_GUILD_MEMBERS        |                                                             |        |            |
| 32768            | 1<<15   | GATEWAY_GUILD_MEMBERS_LIMITED |                                                            |        |            |
| 65536            | 1<<16   | VERIFICATION_PENDING_GUILD_LIMIT | Indicates unusual growth of an app that prevents verification. |        |            |
| 131072           | 1<<17   | EMBEDDED                     | Indicates if an app is embedded within the Discord client   |        |            |
| 262144           | 1<<18   | GATEWAY_MESSAGE_CONTENT      |                                                             |        |            |
| 524288           | 1<<19   | GATEWAY_MESSAGE_CONTENT_LIMITED |                                                          |        |            |
| 1048576          | 1<<20   | EMBEDDED_FIRST_PARTY         | Indicates a first-party embedded app                        |        |            |
| 8388608          | 1<<23   | APPLICATION_COMMAND_BADGE    | Indicates if an app has registered global application commands. |        |            |
| 16777216         | 1<<24   | ACTIVE                       | Indicates if an app is considered active                    |        |            |

