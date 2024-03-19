### [MuseDotNet.Framework](./MuseDotNet-Framework.md 'MuseDotNet.Framework').[QuestData](./QuestData.md 'MuseDotNet.Framework.QuestData')
## QuestData.Progress(MuseDotNet.Framework.Player, string, bool) Method
Progresses the quest for a player  
```csharp
public bool Progress(MuseDotNet.Framework.Player player, string value, bool trivial=false);
```
#### Parameters
<a name='MuseDotNet-Framework-QuestData-Progress(MuseDotNet-Framework-Player_string_bool)-player'></a>
`player` [Player](./Player.md 'MuseDotNet.Framework.Player')  
The player  
  
<a name='MuseDotNet-Framework-QuestData-Progress(MuseDotNet-Framework-Player_string_bool)-value'></a>
`value` [System.String](https://docs.microsoft.com/en-us/dotnet/api/System.String 'System.String')  
The arbitrary text of the quest with progress  
  
<a name='MuseDotNet-Framework-QuestData-Progress(MuseDotNet-Framework-Player_string_bool)-trivial'></a>
`trivial` [System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')  
The indicator of significance of the quest progress update, when `true`, doesn't trigger animation in the quest log UI  
  
#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')  
`true` on success or `false` on failure  
