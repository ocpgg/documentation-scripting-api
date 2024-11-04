### [MuseDotNet.Framework](./MuseDotNet-Framework.md 'MuseDotNet.Framework').[Muse](./Muse.md 'MuseDotNet.Framework.Muse')
## Muse.CancelNotification(string, MuseDotNet.Framework.NotificationScope, MuseDotNet.Framework.NotificationType, MuseDotNet.Framework.Player, MuseDotNet.Framework.QuestData) Method
Cancels a notification with the given message key.  
```csharp
public static void CancelNotification(string messageKey, MuseDotNet.Framework.NotificationScope scope, MuseDotNet.Framework.NotificationType type, MuseDotNet.Framework.Player player=default(MuseDotNet.Framework.Player), MuseDotNet.Framework.QuestData questData=default(MuseDotNet.Framework.QuestData));
```
#### Parameters
<a name='MuseDotNet-Framework-Muse-CancelNotification(string_MuseDotNet-Framework-NotificationScope_MuseDotNet-Framework-NotificationType_MuseDotNet-Framework-Player_MuseDotNet-Framework-QuestData)-messageKey'></a>
`messageKey` [System.String](https://docs.microsoft.com/en-us/dotnet/api/System.String 'System.String')  
The key used for canceling a notification  
  
<a name='MuseDotNet-Framework-Muse-CancelNotification(string_MuseDotNet-Framework-NotificationScope_MuseDotNet-Framework-NotificationType_MuseDotNet-Framework-Player_MuseDotNet-Framework-QuestData)-scope'></a>
`scope` [NotificationScope](./NotificationScope.md 'MuseDotNet.Framework.NotificationScope')  
The scope of players that should have the notification removed  
  
<a name='MuseDotNet-Framework-Muse-CancelNotification(string_MuseDotNet-Framework-NotificationScope_MuseDotNet-Framework-NotificationType_MuseDotNet-Framework-Player_MuseDotNet-Framework-QuestData)-type'></a>
`type` [NotificationType](./NotificationType.md 'MuseDotNet.Framework.NotificationType')  
The UI the notification should be removed from in the context of the notification with the [CallToAction](./NotificationType.md#NotificationType-CallToAction 'MuseDotNet.Framework.NotificationType.CallToAction'), [Chat](./NotificationType.md#NotificationType-Chat 'MuseDotNet.Framework.NotificationType.Chat'), [Notification](./NotificationType.md#NotificationType-Notification 'MuseDotNet.Framework.NotificationType.Notification'), or [BigNotification](./NotificationType.md#NotificationType-BigNotification 'MuseDotNet.Framework.NotificationType.BigNotification')  
  
<a name='MuseDotNet-Framework-Muse-CancelNotification(string_MuseDotNet-Framework-NotificationScope_MuseDotNet-Framework-NotificationType_MuseDotNet-Framework-Player_MuseDotNet-Framework-QuestData)-player'></a>
`player` [Player](./Player.md 'MuseDotNet.Framework.Player')  
The player that is used in the context of the notification with the [Player](./NotificationScope.md#NotificationScope-Player 'MuseDotNet.Framework.NotificationScope.Player'), [Team](./NotificationScope.md#NotificationScope-Team 'MuseDotNet.Framework.NotificationScope.Team'), and [Alliance](./NotificationScope.md#NotificationScope-Alliance 'MuseDotNet.Framework.NotificationScope.Alliance') or `default` otherwise  
  
<a name='MuseDotNet-Framework-Muse-CancelNotification(string_MuseDotNet-Framework-NotificationScope_MuseDotNet-Framework-NotificationType_MuseDotNet-Framework-Player_MuseDotNet-Framework-QuestData)-questData'></a>
`questData` [QuestData](./QuestData.md 'MuseDotNet.Framework.QuestData')  
The quest that is used in the context of the notification with the [Quest](./NotificationScope.md#NotificationScope-Quest 'MuseDotNet.Framework.NotificationScope.Quest') or `default` otherwise  
  
### Example
Cancels a notification for one player  
```csharp

Muse.CancelNotification($"WelcomeMessageKey", NotificationScope.Player, NotificationType.BigNotification, Player);

```

  
Cancels a notification for quest players  
```csharp

Muse.CancelNotification($"WelcomeMessageKey", NotificationScope.Quest, NotificationType.BigNotification, Player);

```  
