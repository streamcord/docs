# Dashboard Error Codes

Error codes are based on the [Discord API](https://discord.com/developers/docs/topics/opcodes-and-status-codes#json). Listed below are the most common error codes, and a suggested fix.

| Code                                                                                    | Description                                                                                       | Fix                                                                                                                                                                                                                       |
| --------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <p><strong>10003</strong></p><p><strong>50001</strong></p><p><strong>50013</strong></p> | Streamcord does not have the correct permissions to send notifications in the configured channel. | <p>Give Streamcord the following permissions:</p><ul><li>View Channel</li><li>Send Messages</li><li>Embed Links</li><li>Attach Files</li><li>Use External Emoji</li><li>Mention @everyone, @here, and All Roles</li></ul> |

If you encounter an error code not listed on this page, please [reach out to our support staff](https://discord.gg/UNYzJqV) on Discord.

## How do I find my error code?

Under your server's [dashboard ](https://dash.streamcord.io/)page, find the "Notifications" tab. Find the 5-digit number in parenthesis under the notification's "Last Post" section.

![](<../.gitbook/assets/image (16).png>)

## Why are my notifications disabled?

Streamcord will automatically disable a notification when it encounters an error with permissions. This is done in order to reduce the load on our systems.

After fixing any permission errors, you can re-enable your notifications by clicking on the "Re-enable notifications" button under your server's notification page on the [dashboard](https://dash.streamcord.io/).&#x20;

**NOTE:** The error _may_ not disappear immediately after clicking the "Re-enable notifications" button. In such a case, the error should go away once the user starts the next stream and Streamcord successfully sends the notification.

![](<../.gitbook/assets/image (27).png>)
