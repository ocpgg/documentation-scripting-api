### [MuseDotNet.Framework](./MuseDotNet-Framework.md 'MuseDotNet.Framework').[Actor](./Actor.md 'MuseDotNet.Framework.Actor')
## Actor.SetOnTimerCallback(MuseDotNet.Framework.TimerCallback, float, float, bool) Method
Sets the callback function that is called at certain intervals, only one timer callback can be set per actor  
```csharp
public bool SetOnTimerCallback(MuseDotNet.Framework.TimerCallback callback, float interval=1f, float startDelay=0f, bool loop=false);
```
#### Parameters
<a name='MuseDotNet-Framework-Actor-SetOnTimerCallback(MuseDotNet-Framework-TimerCallback_float_float_bool)-callback'></a>
`callback` [TimerCallback()](./TimerCallback().md 'MuseDotNet.Framework.TimerCallback()')  
The callback function  
  
<a name='MuseDotNet-Framework-Actor-SetOnTimerCallback(MuseDotNet-Framework-TimerCallback_float_float_bool)-interval'></a>
`interval` [System.Single](https://docs.microsoft.com/en-us/dotnet/api/System.Single 'System.Single')  
The frequency in seconds if looped, can't be less than one second  
  
<a name='MuseDotNet-Framework-Actor-SetOnTimerCallback(MuseDotNet-Framework-TimerCallback_float_float_bool)-startDelay'></a>
`startDelay` [System.Single](https://docs.microsoft.com/en-us/dotnet/api/System.Single 'System.Single')  
The delay in seconds before the first call  
  
<a name='MuseDotNet-Framework-Actor-SetOnTimerCallback(MuseDotNet-Framework-TimerCallback_float_float_bool)-loop'></a>
`loop` [System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')  
If `true`, loops the callback function  
  
#### Returns
[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')  
`true` if the callback set for the actor or `false` if the actor is not appropriate for the callback  
### Example
Set a looped timer callback to an actor  
```csharp

int Iteration = 0;
bool IsTimerSet = Actor.SetOnTimerCallback(() =>
{
	Actor.SetText($"Iteration value: {Iteration++}");
}, loop: true);

if (IsTimerSet)
{
	Debug.Log($"Timer callback is set to {Actor.Name}!");
}

```  
