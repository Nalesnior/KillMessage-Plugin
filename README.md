# KillMessage-Plugin
Simple plugin for scp:sl for Exiled. It shows a message after player will kill other player.

## Configuration
```cs
public bool IsEnabled { get; set; } = true;

// Format of kill message
//   {killCount}   - Count of kills
//   {victim}      - Nickname of the victim
//   {victimRole}  - Role of the victim
public string KillMessageFormat { get; set; } = "You have {killCount} kills. You killed {victim} ({victimRole}).";
public string SucideMessageFormat { get; set; } = "Congratulations! You killed yourself!";
public float MessageDuration { get; set; } = 5f;
public bool Debug { get; set; } = false;
```
