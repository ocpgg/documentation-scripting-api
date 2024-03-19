### [MuseDotNet.Framework](./MuseDotNet-Framework.md 'MuseDotNet.Framework').[Actor](./Actor.md 'MuseDotNet.Framework.Actor')
## Actor.SetOnInteractSuccessCallback(MuseDotNet.Framework.InteractSuccessCallback) Method
Sets the callback function that is called when the actor successfully interacts with something in the world  
```csharp
public bool SetOnInteractSuccessCallback(MuseDotNet.Framework.InteractSuccessCallback callback);
```
#### Parameters
<a name='MuseDotNet-Framework-Actor-SetOnInteractSuccessCallback(MuseDotNet-Framework-InteractSuccessCallback)-callback'></a>
`callback` [InteractSuccessCallback(MuseDotNet.Framework.Actor, MuseDotNet.Framework.InteractionType, MuseDotNet.Framework.InteractionData)](./InteractSuccessCallback(Actor_InteractionType_InteractionData).md 'MuseDotNet.Framework.InteractSuccessCallback(MuseDotNet.Framework.Actor, MuseDotNet.Framework.InteractionType, MuseDotNet.Framework.InteractionData)')  
  
#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')  
`true` if the callback set for the actor or `false` if the actor is not appropriate for the callback  
