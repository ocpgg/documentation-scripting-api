### [MuseDotNet.Framework](./MuseDotNet-Framework.md 'MuseDotNet.Framework').[Actor](./Actor.md 'MuseDotNet.Framework.Actor')
## Actor.TryActivateAbilityWithTarget(string, MuseDotNet.Framework.Actor) Method
Activates an ability with a target if the actor have been granted the ability  
```csharp
public bool TryActivateAbilityWithTarget(string tag, MuseDotNet.Framework.Actor target);
```
#### Parameters
<a name='MuseDotNet-Framework-Actor-TryActivateAbilityWithTarget(string_MuseDotNet-Framework-Actor)-tag'></a>
`tag` [System.String](https://docs.microsoft.com/en-us/dotnet/api/System.String 'System.String')  
  
<a name='MuseDotNet-Framework-Actor-TryActivateAbilityWithTarget(string_MuseDotNet-Framework-Actor)-target'></a>
`target` [Actor](./Actor.md 'MuseDotNet.Framework.Actor')  
  
#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')  
`true` if the actor has the ability and can activate it with a target or `false` if the ability can not be activated  
