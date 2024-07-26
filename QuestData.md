### [MuseDotNet.Framework](./MuseDotNet-Framework.md 'MuseDotNet.Framework')
## QuestData Struct
Represents quest data  
```csharp
public readonly struct QuestData :
System.IEquatable<MuseDotNet.Framework.QuestData>
```
Implements [System.IEquatable&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1 'System.IEquatable`1')[QuestData](./QuestData.md 'MuseDotNet.Framework.QuestData')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1 'System.IEquatable`1')  
### Constructors
- [QuestData(MuseDotNet.Framework.MuseType)](./QuestData-QuestData(MuseType).md 'MuseDotNet.Framework.QuestData.QuestData(MuseDotNet.Framework.MuseType)')
### Properties
- [IsSubsequent](./QuestData-IsSubsequent.md 'MuseDotNet.Framework.QuestData.IsSubsequent')
### Methods
- [Cancel(MuseDotNet.Framework.Player, MuseDotNet.Framework.QuestCancellationType)](./QuestData-Cancel(Player_QuestCancellationType).md 'MuseDotNet.Framework.QuestData.Cancel(MuseDotNet.Framework.Player, MuseDotNet.Framework.QuestCancellationType)')
- [Complete(MuseDotNet.Framework.Player, MuseDotNet.Framework.MatchConditionGroup)](./QuestData-Complete(Player_MatchConditionGroup).md 'MuseDotNet.Framework.QuestData.Complete(MuseDotNet.Framework.Player, MuseDotNet.Framework.MatchConditionGroup)')
- [Complete(MuseDotNet.Framework.Player[])](./QuestData-Complete(Player--).md 'MuseDotNet.Framework.QuestData.Complete(MuseDotNet.Framework.Player[])')
- [Deliver(MuseDotNet.Framework.Player)](./QuestData-Deliver(Player).md 'MuseDotNet.Framework.QuestData.Deliver(MuseDotNet.Framework.Player)')
- [Equals(MuseDotNet.Framework.QuestData)](./QuestData-Equals(QuestData).md 'MuseDotNet.Framework.QuestData.Equals(MuseDotNet.Framework.QuestData)')
- [Equals(object)](./QuestData-Equals(object).md 'MuseDotNet.Framework.QuestData.Equals(object)')
- [ForEachQuestPlayer(MuseDotNet.Framework.PlayerCallback)](./QuestData-ForEachQuestPlayer(PlayerCallback).md 'MuseDotNet.Framework.QuestData.ForEachQuestPlayer(MuseDotNet.Framework.PlayerCallback)')
- [GetHashCode()](./QuestData-GetHashCode().md 'MuseDotNet.Framework.QuestData.GetHashCode()')
- [HasPlayer(MuseDotNet.Framework.Player)](./QuestData-HasPlayer(Player).md 'MuseDotNet.Framework.QuestData.HasPlayer(MuseDotNet.Framework.Player)')
- [Reward(MuseDotNet.Framework.Player)](./QuestData-Reward(Player).md 'MuseDotNet.Framework.QuestData.Reward(MuseDotNet.Framework.Player)')
- [SetOnCancelCallback(MuseDotNet.Framework.PlayerCallback)](./QuestData-SetOnCancelCallback(PlayerCallback).md 'MuseDotNet.Framework.QuestData.SetOnCancelCallback(MuseDotNet.Framework.PlayerCallback)')
- [SetOnCompleteCallback(MuseDotNet.Framework.PlayerCallback)](./QuestData-SetOnCompleteCallback(PlayerCallback).md 'MuseDotNet.Framework.QuestData.SetOnCompleteCallback(MuseDotNet.Framework.PlayerCallback)')
- [SetOnDeliverCallback(MuseDotNet.Framework.PlayerCallback)](./QuestData-SetOnDeliverCallback(PlayerCallback).md 'MuseDotNet.Framework.QuestData.SetOnDeliverCallback(MuseDotNet.Framework.PlayerCallback)')
- [Update(MuseDotNet.Framework.Player, string, string, float, int, int, bool)](./QuestData-Update(Player_string_string_float_int_int_bool).md 'MuseDotNet.Framework.QuestData.Update(MuseDotNet.Framework.Player, string, string, float, int, int, bool)')
### Operators
- [operator ==(MuseDotNet.Framework.QuestData, MuseDotNet.Framework.QuestData)](./QuestData-op_Equality(QuestData_QuestData).md 'MuseDotNet.Framework.QuestData.op_Equality(MuseDotNet.Framework.QuestData, MuseDotNet.Framework.QuestData)')
- [operator !=(MuseDotNet.Framework.QuestData, MuseDotNet.Framework.QuestData)](./QuestData-op_Inequality(QuestData_QuestData).md 'MuseDotNet.Framework.QuestData.op_Inequality(MuseDotNet.Framework.QuestData, MuseDotNet.Framework.QuestData)')
