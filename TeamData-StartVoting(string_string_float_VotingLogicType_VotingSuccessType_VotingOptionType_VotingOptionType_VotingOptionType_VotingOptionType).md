### [MuseDotNet.Framework](./MuseDotNet-Framework.md 'MuseDotNet.Framework').[TeamData](./TeamData.md 'MuseDotNet.Framework.TeamData')
## TeamData.StartVoting(string, string, float, MuseDotNet.Framework.VotingLogicType, MuseDotNet.Framework.VotingSuccessType, MuseDotNet.Framework.VotingOptionType, MuseDotNet.Framework.VotingOptionType, MuseDotNet.Framework.VotingOptionType, MuseDotNet.Framework.VotingOptionType) Method
Initiates the voting for the team and its alliances  
```csharp
public MuseDotNet.Framework.VotingData StartVoting(string title, string description, float duration=30f, MuseDotNet.Framework.VotingLogicType votingLogicType=MuseDotNet.Framework.VotingLogicType.Custom, MuseDotNet.Framework.VotingSuccessType votingSuccessType=MuseDotNet.Framework.VotingSuccessType.SimpleMajority, MuseDotNet.Framework.VotingOptionType votingOptionLeft=default(MuseDotNet.Framework.VotingOptionType), MuseDotNet.Framework.VotingOptionType votingOptionTop=default(MuseDotNet.Framework.VotingOptionType), MuseDotNet.Framework.VotingOptionType votingOptionRight=default(MuseDotNet.Framework.VotingOptionType), MuseDotNet.Framework.VotingOptionType votingOptionBottom=default(MuseDotNet.Framework.VotingOptionType));
```
#### Parameters
<a name='MuseDotNet-Framework-TeamData-StartVoting(string_string_float_MuseDotNet-Framework-VotingLogicType_MuseDotNet-Framework-VotingSuccessType_MuseDotNet-Framework-VotingOptionType_MuseDotNet-Framework-VotingOptionType_MuseDotNet-Framework-VotingOptionType_MuseDotNet-Framework-VotingOptionType)-title'></a>
`title` [System.String](https://docs.microsoft.com/en-us/dotnet/api/System.String 'System.String')  
The title  
  
<a name='MuseDotNet-Framework-TeamData-StartVoting(string_string_float_MuseDotNet-Framework-VotingLogicType_MuseDotNet-Framework-VotingSuccessType_MuseDotNet-Framework-VotingOptionType_MuseDotNet-Framework-VotingOptionType_MuseDotNet-Framework-VotingOptionType_MuseDotNet-Framework-VotingOptionType)-description'></a>
`description` [System.String](https://docs.microsoft.com/en-us/dotnet/api/System.String 'System.String')  
The description  
  
<a name='MuseDotNet-Framework-TeamData-StartVoting(string_string_float_MuseDotNet-Framework-VotingLogicType_MuseDotNet-Framework-VotingSuccessType_MuseDotNet-Framework-VotingOptionType_MuseDotNet-Framework-VotingOptionType_MuseDotNet-Framework-VotingOptionType_MuseDotNet-Framework-VotingOptionType)-duration'></a>
`duration` [System.Single](https://docs.microsoft.com/en-us/dotnet/api/System.Single 'System.Single')  
The duration in seconds, can't be less than ten seconds  
  
<a name='MuseDotNet-Framework-TeamData-StartVoting(string_string_float_MuseDotNet-Framework-VotingLogicType_MuseDotNet-Framework-VotingSuccessType_MuseDotNet-Framework-VotingOptionType_MuseDotNet-Framework-VotingOptionType_MuseDotNet-Framework-VotingOptionType_MuseDotNet-Framework-VotingOptionType)-votingLogicType'></a>
`votingLogicType` [VotingLogicType](./VotingLogicType.md 'MuseDotNet.Framework.VotingLogicType')  
The event-driven implementation of the voting  
  
<a name='MuseDotNet-Framework-TeamData-StartVoting(string_string_float_MuseDotNet-Framework-VotingLogicType_MuseDotNet-Framework-VotingSuccessType_MuseDotNet-Framework-VotingOptionType_MuseDotNet-Framework-VotingOptionType_MuseDotNet-Framework-VotingOptionType_MuseDotNet-Framework-VotingOptionType)-votingSuccessType'></a>
`votingSuccessType` [VotingSuccessType](./VotingSuccessType.md 'MuseDotNet.Framework.VotingSuccessType')  
The condition for determining the success of the voting  
  
<a name='MuseDotNet-Framework-TeamData-StartVoting(string_string_float_MuseDotNet-Framework-VotingLogicType_MuseDotNet-Framework-VotingSuccessType_MuseDotNet-Framework-VotingOptionType_MuseDotNet-Framework-VotingOptionType_MuseDotNet-Framework-VotingOptionType_MuseDotNet-Framework-VotingOptionType)-votingOptionLeft'></a>
`votingOptionLeft` [VotingOptionType](./VotingOptionType.md 'MuseDotNet.Framework.VotingOptionType')  
The voting option that appears in the left slot of the voting panel  
  
<a name='MuseDotNet-Framework-TeamData-StartVoting(string_string_float_MuseDotNet-Framework-VotingLogicType_MuseDotNet-Framework-VotingSuccessType_MuseDotNet-Framework-VotingOptionType_MuseDotNet-Framework-VotingOptionType_MuseDotNet-Framework-VotingOptionType_MuseDotNet-Framework-VotingOptionType)-votingOptionTop'></a>
`votingOptionTop` [VotingOptionType](./VotingOptionType.md 'MuseDotNet.Framework.VotingOptionType')  
The voting option that appears in the top slot of the voting panel  
  
<a name='MuseDotNet-Framework-TeamData-StartVoting(string_string_float_MuseDotNet-Framework-VotingLogicType_MuseDotNet-Framework-VotingSuccessType_MuseDotNet-Framework-VotingOptionType_MuseDotNet-Framework-VotingOptionType_MuseDotNet-Framework-VotingOptionType_MuseDotNet-Framework-VotingOptionType)-votingOptionRight'></a>
`votingOptionRight` [VotingOptionType](./VotingOptionType.md 'MuseDotNet.Framework.VotingOptionType')  
The voting option that appears in the right slot of the voting panel  
  
<a name='MuseDotNet-Framework-TeamData-StartVoting(string_string_float_MuseDotNet-Framework-VotingLogicType_MuseDotNet-Framework-VotingSuccessType_MuseDotNet-Framework-VotingOptionType_MuseDotNet-Framework-VotingOptionType_MuseDotNet-Framework-VotingOptionType_MuseDotNet-Framework-VotingOptionType)-votingOptionBottom'></a>
`votingOptionBottom` [VotingOptionType](./VotingOptionType.md 'MuseDotNet.Framework.VotingOptionType')  
The voting option that appears in the bottom slot of the voting panel  
  
#### Returns
[VotingData](./VotingData.md 'MuseDotNet.Framework.VotingData')  
### Example
Use <a href="https://learn.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/named-and-optional-arguments#named-arguments" target="_blank">named arguments</a> to initiate the voting for the player's team  
```csharp

VotingData StealOrShareVoting = Player.Team.StartVoting
(
	title: "Steal or Share",
	description: "Make a decision to share loot with your allies or steal it",
	duration: 30.0f,
	votingLogicType: VotingLogicType.StealOrShare,
	votingSuccessType: VotingSuccessType.SimpleMajority,
	votingOptionLeft: VotingOptions.Steal,
	votingOptionRight: VotingOptions.Share
);

if (StealOrShareVoting != default)
{
	Debug.Log($"Voting was initiated by team {StealOrShareVoting.Team.GetTitle()}!"); 
}

```  
