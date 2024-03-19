### [MuseDotNet.Framework](./MuseDotNet-Framework.md 'MuseDotNet.Framework').[Actor](./Actor.md 'MuseDotNet.Framework.Actor')
## Actor.SetOnInventoryItemDroppedCallback(MuseDotNet.Framework.CharacterInventoryItemDroppedCallback) Method
Sets the callback function that is called when the character drops an inventory item into the world  
```csharp
public bool SetOnInventoryItemDroppedCallback(MuseDotNet.Framework.CharacterInventoryItemDroppedCallback callback);
```
#### Parameters
<a name='MuseDotNet-Framework-Actor-SetOnInventoryItemDroppedCallback(MuseDotNet-Framework-CharacterInventoryItemDroppedCallback)-callback'></a>
`callback` [CharacterInventoryItemDroppedCallback(MuseDotNet.Framework.Actor)](./CharacterInventoryItemDroppedCallback(Actor).md 'MuseDotNet.Framework.CharacterInventoryItemDroppedCallback(MuseDotNet.Framework.Actor)')  
  
#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')  
`true` if the callback set for the actor or `false` if the actor is not appropriate for the callback  
