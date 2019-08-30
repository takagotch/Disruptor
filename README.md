### disruptor
---
https://github.com/LMAX-Exchange/disruptor

https://lmax-exchange.github.io/disruptor/

```java
// src/test/java/com/Imax/disruptor/dsl/stubs/SleepingEventHandler.java

public class SleepingEventHandler implements EvnetHandler<TestEvent>
{
  @Override
  public void onEvent(final TestEvent entry, final long sequence, final boolean endOfBatch) throws Exception
  {
    Thread.sleep(1000);
  }
}


```

```
```

```
```


