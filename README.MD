## ConfigFileBackup
Sends a backup of the SquadJS configuration file to a discord channel everytime SquadJS is restarted and a change in the config file is detected.
This plugin cannot be used in case the configuration is a string set as environment variable

### Example configuration
```json
{
    "plugin": "ConfigFileBackup",
    "enabled": true,
    "discordClient": "discord",
    "channelID": "112233445566778899",
    "secondsWaitBeforeCreatingBackup": 120
}
```
