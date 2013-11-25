# Signal command map for Robotlegs2

## modify for support signal bus

change map(Class) to map(ISignal)

## Mapping a command

```as3
signalCommandMap.map(MySignalBus.FooSignal).toCommand(FooCommand);
```

## Unmapping a command

```as3
signalCommandMap.unmap(MySignalBus.FooSignal).fromCommand(FooCommand);
```

## MySignalBus

```as3
public class MySignalBus
{
	public const FooSignal:Signal = new Signal();
}
```
