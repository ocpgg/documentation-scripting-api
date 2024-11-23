### [MuseDotNet.Framework](./MuseDotNet-Framework.md 'MuseDotNet.Framework').[QuestData](./QuestData.md 'MuseDotNet.Framework.QuestData')
## QuestData.Complete(MuseDotNet.Framework.Player[], bool) Method
Completes the quest for players  
```csharp
public bool Complete(MuseDotNet.Framework.Player[] players, bool canEndMatch=true);
```
#### Parameters
<a name='MuseDotNet-Framework-QuestData-Complete(MuseDotNet-Framework-Player--_bool)-players'></a>
`players` [Player](./Player.md 'MuseDotNet.Framework.Player')[[]](https://docs.microsoft.com/en-us/dotnet/api/System.Array 'System.Array')  
The players that will also be used in the match condition, if enabled  
  
<a name='MuseDotNet-Framework-QuestData-Complete(MuseDotNet-Framework-Player--_bool)-canEndMatch'></a>
`canEndMatch` [System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')  
If `true`, the match can be ended in accordance with the [players](#MuseDotNet-Framework-QuestData-Complete(MuseDotNet-Framework-Player--_bool)-players 'MuseDotNet.Framework.QuestData.Complete(MuseDotNet.Framework.Player[], bool).players')  
  
#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')  
`true` on success or `false` on failure  
