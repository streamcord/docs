# Commands List

Streamcord supports the native slash commands subsystem. All commands start with **`/`**.

{% hint style="danger" %}
**Prefixed commands have been disabled as of December 28th, 2021.** If you were previously using the old system of typing `!twitch` to run commands, you will need to switch over to the new slash commands system.

If you don't see Streamcord's slash commands in your server, click on this link and choose your server from the list: [https://link.streamcord.io/invite](https://link.streamcord.io/invite)
{% endhint %}

Command arguments that include `<>` denote required fields, and arguments that include `[]` denote optional fields. **Don't include these characters when typing commands.**

All references to Twitch channels will show as "streamer-name", where you provide what comes exactly after "twitch.tv/" in their profile URL. Don't enter the entire link, and don't @ a Discord user.

{% tabs %}
{% tab title="General" %}
### help

Shows basic help and information about Streamcord.\
**Usage:** `/help`

### info

Shows basic bot information and stats\
**Usage:** `/info`

### invite

Shows a link to invite Streamcord to another server.\
**Usage:** `/invite`

### language list

Shows a list of available translations. Use the button within the message to switch pages.\
**Usage:** `/language list`

### language set

Sets Streamcord's language for your account. Enter a valid language code from the language list command.\
**Usage:** `/language set <language-code>`\
**Examples:**\
• `/language set es-ES`

• `/language set ar`

### ping&#x20;

Test Streamcord's connection to Discord.\
**Usage:** `/ping`
{% endtab %}

{% tab title="Twitch" %}
### clips from game

Gets a clip from the specified game.\
**Usage:** `/clips from game <game>`\
**Example:** `/clips from game Fortnite`

### clips from user

Gets a clip from the specified Twitch channel.\
**Usage:** `/clips from user <streamer-name>`\
**Example:** `/clips from user Monstercat`

### user

Shows info about the specified Twitch channel.\
**Usage:** `/user <streamer-name>`\
**Example:** `/user tfue`
{% endtab %}

{% tab title="Notifications" %}
### notifications help

Display help for setting up notifications.\
**Usage:** `/notifications help`

## Learn more about streamer notifications

{% content-ref url="../notifications/intro.md" %}
[intro.md](../notifications/intro.md)
{% endcontent-ref %}

{% content-ref url="../notifications/legacy/add-legacy.md" %}
[add-legacy.md](../notifications/legacy/add-legacy.md)
{% endcontent-ref %}

{% content-ref url="../notifications/spyglass/add-spyglass.md" %}
[add-spyglass.md](../notifications/spyglass/add-spyglass.md)
{% endcontent-ref %}
{% endtab %}

{% tab title="Live Role" %}
### liverole check

Displays the live role configuration within the server.\
**Usage:** `/liverole check`

### liverole forceupdate

Manually update members' roles in the server if they get out of sync\
**Usage:** `/liverole forceupdate`

### liverole help

Display help for setting up Live Role.\
**Usage:** `/liverole help`\
****

## Learn more about Live Role

{% content-ref url="../live-role/intro.md" %}
[intro.md](../live-role/intro.md)
{% endcontent-ref %}

{% content-ref url="../live-role/via-dashboard.md" %}
[via-dashboard.md](../live-role/via-dashboard.md)
{% endcontent-ref %}
{% endtab %}
{% endtabs %}













