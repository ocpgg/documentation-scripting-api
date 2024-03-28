### [MuseDotNet.Framework](./MuseDotNet-Framework.md 'MuseDotNet.Framework').[QuestData](./QuestData.md 'MuseDotNet.Framework.QuestData')
## QuestData.SetOnCancelCallback(MuseDotNet.Framework.PlayerCallback) Method
Sets the callback function that is called when the quest is canceled for a player  
```csharp
public bool SetOnCancelCallback(MuseDotNet.Framework.PlayerCallback callback);
```
#### Parameters
<a name='MuseDotNet-Framework-QuestData-SetOnCancelCallback(MuseDotNet-Framework-PlayerCallback)-callback'></a>
`callback` [PlayerCallback(MuseDotNet.Framework.Player)](./PlayerCallback(Player).md 'MuseDotNet.Framework.PlayerCallback(MuseDotNet.Framework.Player)')  
  
#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')  
`true` if the callback set for the quest or `false` if the quest is not valid for the callback  
