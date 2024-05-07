### [MuseDotNet.Framework](./MuseDotNet-Framework.md 'MuseDotNet.Framework')
## InteractionType Enum
Defines the interaction type  
```csharp
public enum InteractionType : System.Byte
```
### Fields
<a name='InteractionType-None'></a>
`None` 0  
No interaction  
  
<a name='InteractionType-Script'></a>
`Script` 1  
Indicates when a custom script handles the interaction  
  
<a name='InteractionType-PickupItem'></a>
`PickupItem` 2  
Indicates when an item is being picked up  
  
<a name='InteractionType-PickupAndEquipItem'></a>
`PickupAndEquipItem` 3  
Indicates when an item is being picked up and equipped  
  
<a name='InteractionType-PickupItemInventory'></a>
`PickupItemInventory` 4  
Indicates when an item is being picked up and added to the invetory  
  
<a name='InteractionType-ApplyEffect'></a>
`ApplyEffect` 5  
Indicates when an effect is being applied  
  
<a name='InteractionType-StartCrafting'></a>
`StartCrafting` 6  
Indicates when crafting is being started  
  
<a name='InteractionType-CancelCrafting'></a>
`CancelCrafting` 7  
Indicates when crafting is being cancelled  
  
<a name='InteractionType-SelectCraftingRecipe'></a>
`SelectCraftingRecipe` 8  
Indicates when a crafting recipe is being selected  
  
<a name='InteractionType-ChangeCraftingRecipeCategory'></a>
`ChangeCraftingRecipeCategory` 9  
Indicates when a crafting recipe category is being changed  
  
<a name='InteractionType-Harvest'></a>
`Harvest` 10  
Indicates when harvesting is being started  
  
<a name='InteractionType-DepositHeldItem'></a>
`DepositHeldItem` 11  
Indicates when a held item is being deposited  
  
<a name='InteractionType-RetrieveDepositedItem'></a>
`RetrieveDepositedItem` 12  
Indicates when a deposited item is being retrieved  
  
<a name='InteractionType-DepositBuildingRecipeItems'></a>
`DepositBuildingRecipeItems` 13  
Indicates when building recipe items are being deposited  
  
<a name='InteractionType-RevivePlayer'></a>
`RevivePlayer` 14  
Indicates when a player is being revived  
  
<a name='InteractionType-OpenInventory'></a>
`OpenInventory` 15  
Indicates when an inventory is being opened  
  
