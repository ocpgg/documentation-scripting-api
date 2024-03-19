### [MuseDotNet.Framework](./MuseDotNet-Framework.md 'MuseDotNet.Framework').[Actor](./Actor.md 'MuseDotNet.Framework.Actor')
## Actor.SetOnManaChangedCallback(MuseDotNet.Framework.CharacterManaChangedCallback) Method
Sets the callback function that is called when the character mana changes  
```csharp
public bool SetOnManaChangedCallback(MuseDotNet.Framework.CharacterManaChangedCallback callback);
```
#### Parameters
<a name='MuseDotNet-Framework-Actor-SetOnManaChangedCallback(MuseDotNet-Framework-CharacterManaChangedCallback)-callback'></a>
`callback` [CharacterManaChangedCallback(float, float)](./CharacterManaChangedCallback(float_float).md 'MuseDotNet.Framework.CharacterManaChangedCallback(float, float)')  
  
#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')  
`true` if the callback set for the actor or `false` if the actor is not appropriate for the callback  
