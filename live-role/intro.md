# Introduction to Live Role

## What is Live Role?

Live Role allows you to promote streamers in your server through two ways: &#x20;

* **An automatic role that gets added when someone streams on Twitch.** Streamcord will detect their purple "streaming" status and add the configure role when they begin their stream. When they lose the streaming status, Streamcord will remove the live role.
* **Notifications when someone receives the live role.** This allows you to replace a traditional self-promotion system. Live Role Notifications function as a less "hands on" approach to streamer notifications, as all you have to do is set a template message and a channel. There is also no 25 streamer limit for Live Role Notifications, at the expense of some customization options.\
  [**Learn more about Live Role Notifications**](live-role-notifications/)****

### Filter roles

Live Role also supports a basic blacklist/whitelist system called the "filter role." Users who have the designated filter role will receive the live role when they stream, and users without the filter role do not. This allows you to restrict the benefits of Live Role to a certain group of people, such as subscribers, team members, or just a few select streamers.&#x20;

## How many Live Roles can I set up?

Currently, [Streamcord Pro](https://streamcord.io/twitch/pro) users can set up to 5 Live Role configurations on their server, and users on the free bot can set 1. Each configuration has its own live and filter roles, and rules for [Live Role Notifications](live-role-notifications/).

You can learn more about advanced features for Live Role at [this page](advanced-features.md).

## Limitations

Due to the way that Live Role works, there are a couple restraints that you should be aware of.

Streamcord does not directly contact Twitch for information about your current stream status. Bots cannot directly view the Twitch account that you've connected to Discord unless you explicitly authorize them to do so. Instead, Streamcord will look for a purple "streaming" status on your Discord profile. To receive the status, you'll have to [link your Twitch account to Discord](https://support.discord.com/hc/en-us/articles/212112068-Twitch-Integration-FAQ) and enable [streamer mode](https://support.discord.com/hc/en-us/articles/218485407-Streamer-Mode-101) when you go live.

### Limitations for new streamers

Because of a recent change on Discord's end, non-affiliated Twitch users may no longer receive live roles when streaming, as your Discord account might not display the purple "streaming" status. If your linked Twitch channel is an affiliate or partner, this won't affect you, and Live Role will still continue to work as normal.

## Terminology

Some terms used for Live Role may be confusing to some users, so we've laid them out here for you to understand the language used in these documentation pages:

| Term                                      | Definition                                                                                 |
| ----------------------------------------- | ------------------------------------------------------------------------------------------ |
| <p>Live Role</p><p>(with capitals)</p>    | Feature that allows you to give custom roles to server members when they stream on Twitch. |
| <p>live role</p><p>(without capitals)</p> | The actual role that is given to server members when they go live.                         |
| filter role                               | Chooses which members will / will not receive the live role when they go live.             |

## How do I set up Live Role?

{% content-ref url="via-dashboard.md" %}
[via-dashboard.md](via-dashboard.md)
{% endcontent-ref %}

###
