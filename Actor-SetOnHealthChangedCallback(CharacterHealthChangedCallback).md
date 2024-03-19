### [MuseDotNet.Framework](./MuseDotNet-Framework.md 'MuseDotNet.Framework').[Actor](./Actor.md 'MuseDotNet.Framework.Actor')
## Actor.SetOnHealthChangedCallback(MuseDotNet.Framework.CharacterHealthChangedCallback) Method
Sets the callback function that is called when the character health changes  
```csharp
public bool SetOnHealthChangedCallback(MuseDotNet.Framework.CharacterHealthChangedCallback callback);
```
#### Parameters
<a name='MuseDotNet-Framework-Actor-SetOnHealthChangedCallback(MuseDotNet-Framework-CharacterHealthChangedCallback)-callback'></a>
`callback` [CharacterHealthChangedCallback(float, float)](./CharacterHealthChangedCallback(float_float).md 'MuseDotNet.Framework.CharacterHealthChangedCallback(float, float)')  
  
#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')  
`true` if the callback set for the actor or `false` if the actor is not appropriate for the callback  
