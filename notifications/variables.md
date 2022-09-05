# Using Variables

Notification variables allow you to insert special text into your announcement messages, such as the current streamer's title, game, and viewer count.

| Variable name                                                         | Description                              |
| --------------------------------------------------------------------- | ---------------------------------------- |
| `{stream.title}`                                                      | The stream's title                       |
| `{stream.viewers}`                                                    | The number of people watching the stream |
| `{stream.game}`                                                       | The game that is being played on stream  |
| `{user.twitch_url}`                                                   | The twitch.tv URL of the streamer        |
| <p><code>{user.twitch_name}</code></p><p><code>{user.name}</code></p> | The streamer's Twitch username           |
| `{everyone}`                                                          | Inserts an @everyone mention             |
| `{here}`                                                              | Inserts an @here mention                 |

If you want to mention a certain Discord user or role in your notification message, check out this page:

{% content-ref url="mentioning-users-roles.md" %}
[mentioning-users-roles.md](mentioning-users-roles.md)
{% endcontent-ref %}

