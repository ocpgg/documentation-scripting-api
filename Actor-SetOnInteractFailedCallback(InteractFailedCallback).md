### [MuseDotNet.Framework](./MuseDotNet-Framework.md 'MuseDotNet.Framework').[Actor](./Actor.md 'MuseDotNet.Framework.Actor')
## Actor.SetOnInteractFailedCallback(MuseDotNet.Framework.InteractFailedCallback) Method
Sets the callback function that is called when the actor tries and fails to interact with something in the world  
```csharp
public bool SetOnInteractFailedCallback(MuseDotNet.Framework.InteractFailedCallback callback);
```
#### Parameters
<a name='MuseDotNet-Framework-Actor-SetOnInteractFailedCallback(MuseDotNet-Framework-InteractFailedCallback)-callback'></a>
`callback` [InteractFailedCallback(MuseDotNet.Framework.Actor, MuseDotNet.Framework.InteractionType, MuseDotNet.Framework.InteractionData)](./InteractFailedCallback(Actor_InteractionType_InteractionData).md 'MuseDotNet.Framework.InteractFailedCallback(MuseDotNet.Framework.Actor, MuseDotNet.Framework.InteractionType, MuseDotNet.Framework.InteractionData)')  
  
#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')  
`true` if the callback set for the actor or `false` if the actor is not appropriate for the callback  
