# Game and Title Filters

Game & Title Filters allow you to choose when Streamcord sends a notification based on the stream's title or game that is currently being played.

{% embed url="https://www.youtube.com/watch?v=C3JAQ0S2XJ0" %}

## How filters work

### Limits

Game and Title Filters only work for Spyglass notifications. They do not work for [Legacy](../legacy/) or [Live Role](../../live-role/live-role-notifications/) Notifications.

Additionally, there are limits on how many and which rules may be applied to notifications, depending on your Streamcord Pro subscription:

| Feature                   | Streamcord Free | Streamcord Pro |
| ------------------------- | :-------------: | :------------: |
| Game filter rules         |        ✔️       |       ✔️       |
| Stream title filter rules |        ❌        |       ✔️       |
| Rules per notification    |     Up to 1     |     Up to 5    |

### Regular Expressions (RegEx)

This feature makes use of [Regular Expressions](https://en.wikipedia.org/wiki/Regular\_expression), abbreviated as RegEx, to allow for flexibility and extensive customization in filter rules. Regular Expressions are sequences of characters that computers use to detect and find patterns in text.&#x20;

Here's an example of a Regular Expression:

<figure><img src="../../.gitbook/assets/regex.png" alt=""><figcaption><p>A Regular Expression that matches every capital letter, and every letter that follows it.</p></figcaption></figure>

Chances are, you won't need something that complicated. The main things to remember are:

* Some characters have more than one meaning, such as `.`, `+`, `*`, `?`, `^`, `$`, `(`, `)`, `[`, `]`, `{`, `}`, `|`, and `\`. To prevent unintended behavior, you need to "escape" them by preceding each special character with a backslash (`\`).
* The OR operator, `|`, allows you to tell Streamcord to search for different groups of characters. This is useful if you want the bot to notify for multiple games or keywords in a stream title.
* Streamcord will search for a _partial match_ of your pattern, meaning that if you set your rule to `Destiny`, you will be notified for any game that contains the word "Destiny", such as "Destiny 2" and "With Your Destiny".
* **Filter rules are case sensitive.** To tell Streamcord to ignore the capitalization of letters, start your pattern with `` ` `` and end it with `` `i ``.

{% hint style="info" %}
While Regular Expressions are powerful, they can also be very difficult and awkward to use. If you're unfamiliar with them, we recommend checking out a [tutorial on RegEx](https://www.sitepoint.com/learn-regex/) first.
{% endhint %}

Check [How to design your filter rules](game-and-title-filters.md#how-to-design-your-filter-rules) for examples on how to create RegEx rules.

{% hint style="warning" %}
Please note that Streamcord support staff will not create Regular Expression patterns for you. While we will do our best to assist everyone, we simply do not have enough time to teach everyone how to use RegEx. Check below for common scenarios and their patterns.
{% endhint %}

## How to design your filter rules

This section contains information on how to create your notification filter rules for a few common scenarios.

### Notify for only one game

Let's say you only want Streamcord to send a notification when a streamer is playing Fortnite. In your notification settings, add a new game rule, make sure the mode equals "matches" and set the pattern to `^Fortnite$`. The `^` locks the sequence "Fortnite" to the beginning of the game's name, and the `$` locks it to the end, meaning that the entire game's name must equal the word "Fortnite".

### Notify for multiple games

### Notify for all games except certain ones

### Notify for a game and keyword in title

## How to add a filter

