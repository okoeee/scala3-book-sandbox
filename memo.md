
## error
sbt: 1.2.4

compile時に↓のエラー
```
[error] ## Exception when compiling 1 sources to /Users/kazuma.yokoe/dev/sandbox/scala-3-book-sandbox/target/scala-2.13/classes
[error] The compiler bridge sources org.scala-sbt:compiler-bridge_2.13:1.2.3:compile could not be retrieved.
[error]
[error]         Note: Unresolved dependencies path:
[error]                 org.scala-sbt:compiler-bridge_2.13:1.2.3
[error]                   +- org.scala-sbt.temp:temp-module-52f238aede5a1d8d7a484c2bec27a144810e2ac0:1.2.3
[error] sbt.internal.inc.ZincComponentCompiler.$anonfun$compileAndInstall$3(ZincComponentCompiler.scala:272)
[error] sbt.internal.inc.ZincComponentCompiler.$anonfun$compileAndInstall$3$adapted(ZincComponentCompiler.scala:262)
```

