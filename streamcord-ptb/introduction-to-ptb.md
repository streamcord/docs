# Introduction to PTB

{% hint style="warning" %}
**Streamcord's PTB program has been discontinued as of September 6th, 2022.** This documentation page will remain for posterity.
{% endhint %}

Streamcord PTB allows everyone to test the next major version of Streamcord's backend code.

The Streamcord PTB bot must be invited to your server in order to use PTB features.

### What does PTB include now?

The Public Test Build version currently contains a completely rewritten version of Streamcord's backend. This includes:

* A new Live Role handler
* A new slash command handler

The following features have been _removed_ in the PTB bot:

* Audio commands (`!twitch listen`)
* Live Role Event Logs

### What will PTB include in the future?

In the future, we will expand the PTB to include:

* A new dashboard
  * An updated UX/UI
  * Easier management of notifications & Live Role
  * Statistics for [Click Analytics](../notifications/spyglass/click-analytics.md)
  * Easier Streamcord Pro subscription management
* More notification & Live Role features
* Other new features

These features will eventually be pushed to the main bot after a public beta period. Please note that there is no ETA for these features, and they may be changed or scrapped entirely at any time.

### How do I add the PTB bot to my server?

You can invite Streamcord PTB to your server via [https://link.streamcord.io/ptb\_invite](https://link.streamcord.io/ptb\_invite).

{% hint style="danger" %}
**Do not remove the normal Streamcord bot from your server.** As of now, the PTB dashboard relies on the main bot in order to communicate with Discord. You should keep both bots in your server if you want to use PTB features.
{% endhint %}

**The PTB bot uses a different dashboard link. **_****_ In order to manage notifications and Live Role configurations, you can visit [https://ptb.streamcord.io](https://ptb.streamcord.io). Note that this version of the dashboard can only manage the PTB bot in your server. It also does not implement the dashboard rewrite yet.
