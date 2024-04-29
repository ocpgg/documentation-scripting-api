### [MuseDotNet.Framework](./MuseDotNet-Framework.md 'MuseDotNet.Framework').[Muse](./Muse.md 'MuseDotNet.Framework.Muse')
## Muse.SendNotification(string, MuseDotNet.Framework.NotificationScope, MuseDotNet.Framework.NotificationPriority, bool, MuseDotNet.Framework.Player, MuseDotNet.Framework.QuestData) Method
Sends a notification to players  
```csharp
public static void SendNotification(string formattedMessage, MuseDotNet.Framework.NotificationScope scope, MuseDotNet.Framework.NotificationPriority priority, bool displayAsBigNotification, MuseDotNet.Framework.Player player=default(MuseDotNet.Framework.Player), MuseDotNet.Framework.QuestData questData=default(MuseDotNet.Framework.QuestData));
```
#### Parameters
<a name='MuseDotNet-Framework-Muse-SendNotification(string_MuseDotNet-Framework-NotificationScope_MuseDotNet-Framework-NotificationPriority_bool_MuseDotNet-Framework-Player_MuseDotNet-Framework-QuestData)-formattedMessage'></a>
`formattedMessage` [System.String](https://docs.microsoft.com/en-us/dotnet/api/System.String 'System.String')  
The formatted message that supports rich text  
  
<a name='MuseDotNet-Framework-Muse-SendNotification(string_MuseDotNet-Framework-NotificationScope_MuseDotNet-Framework-NotificationPriority_bool_MuseDotNet-Framework-Player_MuseDotNet-Framework-QuestData)-scope'></a>
`scope` [NotificationScope](./NotificationScope.md 'MuseDotNet.Framework.NotificationScope')  
The scope of players that should receive the notification  
  
<a name='MuseDotNet-Framework-Muse-SendNotification(string_MuseDotNet-Framework-NotificationScope_MuseDotNet-Framework-NotificationPriority_bool_MuseDotNet-Framework-Player_MuseDotNet-Framework-QuestData)-priority'></a>
`priority` [NotificationPriority](./NotificationPriority.md 'MuseDotNet.Framework.NotificationPriority')  
The priority of the notification when displayed as a big notification  
  
<a name='MuseDotNet-Framework-Muse-SendNotification(string_MuseDotNet-Framework-NotificationScope_MuseDotNet-Framework-NotificationPriority_bool_MuseDotNet-Framework-Player_MuseDotNet-Framework-QuestData)-displayAsBigNotification'></a>
`displayAsBigNotification` [System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')  
The option to display the notification as a big notification  
  
<a name='MuseDotNet-Framework-Muse-SendNotification(string_MuseDotNet-Framework-NotificationScope_MuseDotNet-Framework-NotificationPriority_bool_MuseDotNet-Framework-Player_MuseDotNet-Framework-QuestData)-player'></a>
`player` [Player](./Player.md 'MuseDotNet.Framework.Player')  
The player that is used in the context of the notification with the [Player](./NotificationScope.md#NotificationScope-Player 'MuseDotNet.Framework.NotificationScope.Player'), [Team](./NotificationScope.md#NotificationScope-Team 'MuseDotNet.Framework.NotificationScope.Team'), and [Alliance](./NotificationScope.md#NotificationScope-Alliance 'MuseDotNet.Framework.NotificationScope.Alliance') or `default` otherwise  
  
<a name='MuseDotNet-Framework-Muse-SendNotification(string_MuseDotNet-Framework-NotificationScope_MuseDotNet-Framework-NotificationPriority_bool_MuseDotNet-Framework-Player_MuseDotNet-Framework-QuestData)-questData'></a>
`questData` [QuestData](./QuestData.md 'MuseDotNet.Framework.QuestData')  
The quest that is used in the context of the notification with the [Quest](./NotificationScope.md#NotificationScope-Quest 'MuseDotNet.Framework.NotificationScope.Quest') or `default` otherwise  
  
### Example
Send a notification to a player  
```csharp

Muse.SendNotification($"Welcome to the world {Player.Name}!", NotificationScope.Player, NotificationPriority.High, true, Player);

```

  
Send a notification to quest players  
```csharp

Muse.SendNotification($"The quest {QuestData.GetTitle()} begins!", NotificationScope.Quest, NotificationPriority.High, true, Player, QuestData);

```  
