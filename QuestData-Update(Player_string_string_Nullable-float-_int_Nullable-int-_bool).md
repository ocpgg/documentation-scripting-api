### [MuseDotNet.Framework](./MuseDotNet-Framework.md 'MuseDotNet.Framework').[QuestData](./QuestData.md 'MuseDotNet.Framework.QuestData')
## QuestData.Update(MuseDotNet.Framework.Player, string, string, System.Nullable&lt;float&gt;, int, System.Nullable&lt;int&gt;, bool) Method
Updates the quest for a player  
```csharp
public bool Update(MuseDotNet.Framework.Player player, string progress=null, string title=null, System.Nullable<float> percentage=-1f, int battleStars=-1, System.Nullable<int> questTimerSeconds=-1, bool trivial=false);
```
#### Parameters
<a name='MuseDotNet-Framework-QuestData-Update(MuseDotNet-Framework-Player_string_string_System-Nullable-float-_int_System-Nullable-int-_bool)-player'></a>
`player` [Player](./Player.md 'MuseDotNet.Framework.Player')  
The player  
  
<a name='MuseDotNet-Framework-QuestData-Update(MuseDotNet-Framework-Player_string_string_System-Nullable-float-_int_System-Nullable-int-_bool)-progress'></a>
`progress` [System.String](https://docs.microsoft.com/en-us/dotnet/api/System.String 'System.String')  
The arbitrary text of the quest progress or `null` to keep the last value  
  
<a name='MuseDotNet-Framework-QuestData-Update(MuseDotNet-Framework-Player_string_string_System-Nullable-float-_int_System-Nullable-int-_bool)-title'></a>
`title` [System.String](https://docs.microsoft.com/en-us/dotnet/api/System.String 'System.String')  
The arbitrary text of the quest title or `null` to keep the last value  
  
<a name='MuseDotNet-Framework-QuestData-Update(MuseDotNet-Framework-Player_string_string_System-Nullable-float-_int_System-Nullable-int-_bool)-percentage'></a>
`percentage` [System.Nullable&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Nullable-1 'System.Nullable`1')[System.Single](https://docs.microsoft.com/en-us/dotnet/api/System.Single 'System.Single')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Nullable-1 'System.Nullable`1')  
The progress bar percentage between `0.0f` and `1.0f`; use `null` to disable the percentage; use `-1.0f` to keep the last value  
  
<a name='MuseDotNet-Framework-QuestData-Update(MuseDotNet-Framework-Player_string_string_System-Nullable-float-_int_System-Nullable-int-_bool)-battleStars'></a>
`battleStars` [System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32 'System.Int32')  
The amount of battle stars granted to the player for the completion of the quest or `-1` to keep the last value  
  
<a name='MuseDotNet-Framework-QuestData-Update(MuseDotNet-Framework-Player_string_string_System-Nullable-float-_int_System-Nullable-int-_bool)-questTimerSeconds'></a>
`questTimerSeconds` [System.Nullable&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Nullable-1 'System.Nullable`1')[System.Int32](https://docs.microsoft.com/en-us/dotnet/api/System.Int32 'System.Int32')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Nullable-1 'System.Nullable`1')  
Seconds under something important happens in this quest; use `null` to disable the timer; use `-1` to keep the last value  
  
<a name='MuseDotNet-Framework-QuestData-Update(MuseDotNet-Framework-Player_string_string_System-Nullable-float-_int_System-Nullable-int-_bool)-trivial'></a>
`trivial` [System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')  
If `true`, doesn't trigger animation in the quest log UI  
  
#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')  
`true` on success or `false` on failure  
