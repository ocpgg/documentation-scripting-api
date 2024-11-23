### [MuseDotNet.Framework](./MuseDotNet-Framework.md 'MuseDotNet.Framework').[QuestData](./QuestData.md 'MuseDotNet.Framework.QuestData')
## QuestData.Complete(MuseDotNet.Framework.Player, MuseDotNet.Framework.MatchConditionGroup, bool) Method
Completes the quest for a player  
```csharp
public bool Complete(MuseDotNet.Framework.Player player, MuseDotNet.Framework.MatchConditionGroup matchConditionGroup=MuseDotNet.Framework.MatchConditionGroup.None, bool canEndMatch=true);
```
#### Parameters
<a name='MuseDotNet-Framework-QuestData-Complete(MuseDotNet-Framework-Player_MuseDotNet-Framework-MatchConditionGroup_bool)-player'></a>
`player` [Player](./Player.md 'MuseDotNet.Framework.Player')  
The player  
  
<a name='MuseDotNet-Framework-QuestData-Complete(MuseDotNet-Framework-Player_MuseDotNet-Framework-MatchConditionGroup_bool)-matchConditionGroup'></a>
`matchConditionGroup` [MatchConditionGroup](./MatchConditionGroup.md 'MuseDotNet.Framework.MatchConditionGroup')  
The group that will be affected by the match condition set for the quest  
  
<a name='MuseDotNet-Framework-QuestData-Complete(MuseDotNet-Framework-Player_MuseDotNet-Framework-MatchConditionGroup_bool)-canEndMatch'></a>
`canEndMatch` [System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')  
If `true`, the match can be ended in accordance with the [matchConditionGroup](#MuseDotNet-Framework-QuestData-Complete(MuseDotNet-Framework-Player_MuseDotNet-Framework-MatchConditionGroup_bool)-matchConditionGroup 'MuseDotNet.Framework.QuestData.Complete(MuseDotNet.Framework.Player, MuseDotNet.Framework.MatchConditionGroup, bool).matchConditionGroup')  
  
#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')  
`true` on success or `false` on failure  
