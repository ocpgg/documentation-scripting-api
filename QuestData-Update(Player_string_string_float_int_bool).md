### [MuseDotNet.Framework](./MuseDotNet-Framework.md 'MuseDotNet.Framework').[QuestData](./QuestData.md 'MuseDotNet.Framework.QuestData')
## QuestData.Update(MuseDotNet.Framework.Player, string, string, float, int, bool) Method
Updates the quest for a player  
```csharp
public bool Update(MuseDotNet.Framework.Player player, string progress=null, string title=null, float percentage=-1f, int battleStars=-1, bool trivial=false);
```
#### Parameters
<a name='MuseDotNet-Framework-QuestData-Update(MuseDotNet-Framework-Player_string_string_float_int_bool)-player'></a>
`player` [Player](./Player.md 'MuseDotNet.Framework.Player')  
The player  
  
<a name='MuseDotNet-Framework-QuestData-Update(MuseDotNet-Framework-Player_string_string_float_int_bool)-progress'></a>
`progress` [System.String](https://docs.microsoft.com/en-us/dotnet/api/System.String 'System.String')  
The arbitrary text of the quest progress or `null` to keep the last value  
  
<a name='MuseDotNet-Framework-QuestData-Update(MuseDotNet-Framework-Player_string_string_float_int_bool)-title'></a>
`title` [System.String](https://docs.microsoft.com/en-us/dotnet/api/System.String 'System.String')  
The arbitrary text of the quest title or `null` to keep the last value  
  
<a name='MuseDotNet-Framework-QuestData-Update(MuseDotNet-Framework-Player_string_string_float_int_bool)-percentage'></a>
`percentage` [System.Single](https://docs.microsoft.com/en-us/dotnet/api/System.Single 'System.Single')  
The progress bar percentage between `0.0f` and `1.0f` or `-1.0f` to keep the last value  
  
<a name='MuseDotNet-Framework-QuestData-Update(MuseDotNet-Framework-Player_string_string_float_int_bool)-battleStars'></a>
`battleStars` [System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32 'System.Int32')  
The amount of battle stars granted to the player for the completion of the quest or `-1` to keep the last value  
  
<a name='MuseDotNet-Framework-QuestData-Update(MuseDotNet-Framework-Player_string_string_float_int_bool)-trivial'></a>
`trivial` [System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')  
The indicator of significance of the quest progress update, when `true`, doesn't trigger animation in the quest log UI  
  
#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')  
`true` on success or `false` on failure  
