### [MuseDotNet.Framework](./MuseDotNet-Framework.md 'MuseDotNet.Framework').[Actor](./Actor.md 'MuseDotNet.Framework.Actor')
## Actor.SetOnDamageReceivedCallback(MuseDotNet.Framework.CharacterDamageReceivedCallback) Method
Sets the callback function that is called when the character receives damage  
```csharp
public bool SetOnDamageReceivedCallback(MuseDotNet.Framework.CharacterDamageReceivedCallback callback);
```
#### Parameters
<a name='MuseDotNet-Framework-Actor-SetOnDamageReceivedCallback(MuseDotNet-Framework-CharacterDamageReceivedCallback)-callback'></a>
`callback` [CharacterDamageReceivedCallback(MuseDotNet.Framework.Actor, float)](./CharacterDamageReceivedCallback(Actor_float).md 'MuseDotNet.Framework.CharacterDamageReceivedCallback(MuseDotNet.Framework.Actor, float)')  
  
#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')  
`true` if the callback set for the actor or `false` if the actor is not appropriate for the callback  
