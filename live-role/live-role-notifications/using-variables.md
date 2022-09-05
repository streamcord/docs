# Using Variables

You can also use variables to insert special text into your Live Role notification messages.&#x20;

| Variable name         | Description                                                                                             |
| --------------------- | ------------------------------------------------------------------------------------------------------- |
| `{user.id}`           | The streamer's [numerical Discord ID](https://discord.com/developers/docs/reference#snowflakes).        |
| `{user.name}`         | The streamer's Discord username.                                                                        |
| `{user.nickname}`     | <p>The streamer's nickname in the server.<br>If they don't have one, their normal username is used.</p> |
| `{user.ping}`         | Inserts the user's @mention.                                                                            |
| `{user.stream_title}` | The Twitch stream's title. _(experimental)_                                                             |
| `{user.twitch_name}`  | The streamer's Twitch name.                                                                             |
| `{user.twitch_url}`   | The twitch.tv URL of the streamer.                                                                      |

{% hint style="warning" %}
**Please be respectful with the user.ping variable.** Not everyone wants to receive pings every time they stream.

We only recommend using it in small servers, or if you have configured a [filter role](../intro.md#filter-roles).
{% endhint %}
