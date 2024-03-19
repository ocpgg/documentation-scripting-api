### [MuseDotNet.Framework](./MuseDotNet-Framework.md 'MuseDotNet.Framework').[Actor](./Actor.md 'MuseDotNet.Framework.Actor')
## Actor.SetOnPreInteractCallback(MuseDotNet.Framework.PreInteractCallback) Method
Sets the callback function that is called when the actor can interact with an object in the world  
```csharp
public bool SetOnPreInteractCallback(MuseDotNet.Framework.PreInteractCallback callback);
```
#### Parameters
<a name='MuseDotNet-Framework-Actor-SetOnPreInteractCallback(MuseDotNet-Framework-PreInteractCallback)-callback'></a>
`callback` [PreInteractCallback(MuseDotNet.Framework.Actor, MuseDotNet.Framework.InteractionType, MuseDotNet.Framework.InteractionData)](./PreInteractCallback(Actor_InteractionType_InteractionData).md 'MuseDotNet.Framework.PreInteractCallback(MuseDotNet.Framework.Actor, MuseDotNet.Framework.InteractionType, MuseDotNet.Framework.InteractionData)')  
  
#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')  
`true` if the callback set for the actor or `false` if the actor is not appropriate for the callback  
