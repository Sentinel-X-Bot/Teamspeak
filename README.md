# Sentinel X - Teamspeak Integration

With this integration, you can now protect not only Discord and FiveM but also Teamspeak servers. Whether you're managing a community, a gaming server, or a collaborative workspace, our solution offers enhanced security measures to safeguard your online environment. Stay in control and ensure a safe and enjoyable experience for all your users across different platforms.



## Configuration
To run this integration, you will need to modifiy the config.json to contain the following variables

#### Core Intergration Config
`api_key` - you can get this from the [#teamspeak-api-keys](https://discord.com/channels/1090639048776876223/1223429801436774486) in our discord found [HERE](https://discord.sentinelx.org)

`discord_webhook_url` - you can create this in any channel where you have the correct permissions, this is where all alerts are sent like when a flagged user joins ([guide](https://support.discord.com/hc/en-us/articles/228383668-Intro-to-Webhooks))

`warn_reputation` - Limit before a warning gets sent using the discord webhook 

`kick_reputation` - Limit before the user gets kicked, with a notification that gets sent using the discord webhook

`ban_reputation` - Limit before the user gets banned, with a notification that gets sent using the discord webhook

#### Teamspeak Connection Config
`host` - The IP address of your teamspeak server

`queryport` - The SERVER_QUERY port that your teamspeak server is configured to use. (Set to the default that TS uses already)

`serverport` - The SERVER_PORT (Set to the default that TS uses already)

`username` - SERVER_QUERY username (Set to the default that TS uses already)

`password` - SERVER_QUERY password (You can get this when you first get the teamspeak, if you dont have this saved please follow this [tutorial](https://support.teamspeak.com/hc/en-us/articles/360002712898-How-do-I-change-or-reset-the-password-of-the-serveradmin-Server-Query-account))

#### Generic Config
`community_name` - This will be  used when a member connects and in the alert messages allowing you to quickly identify what community the alert has come from.

`kick_timeout_seconds` - This is the timeout before the the user gets kicked for not linking their teamspeak and discord

`debug` - Enables some useful debug messages for when things arent working as expected (generally this should be set to 'false' unless you are debugging with Sentinel X Staff, or maybe you just like extra information given 🤷) 'true' or 'false' are accepted in this line.

## Usage

To run this intergration you first need to download the zip and extract it. 
Once you have configured the config.json, you then simply run the EXE.


## Disclaimers

We (Sentinel X) are not affiliated with teamspeak or discord in anyway

## License

Copyright (C) Sentinel X - All Rights Reserved
Unauthorized copying, modification or distribution of this file, via any medium is strictly prohibited
Proprietary and confidential
Written by Sentinel X Management Team <sentinelxgdpr@gmail.com>, November 2023

