### [MuseDotNet.Framework](./MuseDotNet-Framework.md 'MuseDotNet.Framework')
## Player Struct
Represents a player state that persists throughout a session  
```csharp
public readonly struct Player :
System.IEquatable<MuseDotNet.Framework.Player>
```
Implements [System.IEquatable&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1 'System.IEquatable`1')[Player](./Player.md 'MuseDotNet.Framework.Player')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1 'System.IEquatable`1')  
### Properties
- [Name](./Player-Name.md 'MuseDotNet.Framework.Player.Name')
- [Team](./Player-Team.md 'MuseDotNet.Framework.Player.Team')
### Methods
- [AddTag(string)](./Player-AddTag(string).md 'MuseDotNet.Framework.Player.AddTag(string)')
- [AddToTeam(MuseDotNet.Framework.TeamData)](./Player-AddToTeam(TeamData).md 'MuseDotNet.Framework.Player.AddToTeam(MuseDotNet.Framework.TeamData)')
- [ClearPlayerStart()](./Player-ClearPlayerStart().md 'MuseDotNet.Framework.Player.ClearPlayerStart()')
- [Equals(MuseDotNet.Framework.Player)](./Player-Equals(Player).md 'MuseDotNet.Framework.Player.Equals(MuseDotNet.Framework.Player)')
- [Equals(object)](./Player-Equals(object).md 'MuseDotNet.Framework.Player.Equals(object)')
- [GetCharacter()](./Player-GetCharacter().md 'MuseDotNet.Framework.Player.GetCharacter()')
- [GetHashCode()](./Player-GetHashCode().md 'MuseDotNet.Framework.Player.GetHashCode()')
- [GetPlayerStart()](./Player-GetPlayerStart().md 'MuseDotNet.Framework.Player.GetPlayerStart()')
- [GetTeamAttitude(MuseDotNet.Framework.Player)](./Player-GetTeamAttitude(Player).md 'MuseDotNet.Framework.Player.GetTeamAttitude(MuseDotNet.Framework.Player)')
- [HasTag(string)](./Player-HasTag(string).md 'MuseDotNet.Framework.Player.HasTag(string)')
- [RemoveFromTeam(MuseDotNet.Framework.TeamData)](./Player-RemoveFromTeam(TeamData).md 'MuseDotNet.Framework.Player.RemoveFromTeam(MuseDotNet.Framework.TeamData)')
- [RemoveTag(string)](./Player-RemoveTag(string).md 'MuseDotNet.Framework.Player.RemoveTag(string)')
- [Restart()](./Player-Restart().md 'MuseDotNet.Framework.Player.Restart()')
- [RestartAsSpectator()](./Player-RestartAsSpectator().md 'MuseDotNet.Framework.Player.RestartAsSpectator()')
- [SetOnCharacterPreSpawnCallback(MuseDotNet.Framework.Callback)](./Player-SetOnCharacterPreSpawnCallback(Callback).md 'MuseDotNet.Framework.Player.SetOnCharacterPreSpawnCallback(MuseDotNet.Framework.Callback)')
- [SetOnCharacterSpawnedCallback(MuseDotNet.Framework.CharacterCallback)](./Player-SetOnCharacterSpawnedCallback(CharacterCallback).md 'MuseDotNet.Framework.Player.SetOnCharacterSpawnedCallback(MuseDotNet.Framework.CharacterCallback)')
- [SetOnPlayerSpectatorCallback(MuseDotNet.Framework.PlayerCallback)](./Player-SetOnPlayerSpectatorCallback(PlayerCallback).md 'MuseDotNet.Framework.Player.SetOnPlayerSpectatorCallback(MuseDotNet.Framework.PlayerCallback)')
- [SetPlayerStart(MuseDotNet.Framework.Actor)](./Player-SetPlayerStart(Actor).md 'MuseDotNet.Framework.Player.SetPlayerStart(MuseDotNet.Framework.Actor)')
- [SetRespawnDelay(float)](./Player-SetRespawnDelay(float).md 'MuseDotNet.Framework.Player.SetRespawnDelay(float)')
### Operators
- [operator ==(MuseDotNet.Framework.Player, MuseDotNet.Framework.Player)](./Player-op_Equality(Player_Player).md 'MuseDotNet.Framework.Player.op_Equality(MuseDotNet.Framework.Player, MuseDotNet.Framework.Player)')
- [operator !=(MuseDotNet.Framework.Player, MuseDotNet.Framework.Player)](./Player-op_Inequality(Player_Player).md 'MuseDotNet.Framework.Player.op_Inequality(MuseDotNet.Framework.Player, MuseDotNet.Framework.Player)')
