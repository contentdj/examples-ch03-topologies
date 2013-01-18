Run with

``` sh
mvn -e compile exec:java -Dexec.classpathScope=compile -Dexec.mainClass="countword.TopologyMain" -Dexec.args="src/main/resources/words.txt"
```

And
``` sh
mvn -e compile exec:java -Dexec.classpathScope=compile -Dexec.mainClass="drpc.DRPCTopologyMain"
```
