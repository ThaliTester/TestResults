#### Test 72314330816037d_thali09_HTC-HTC One M9 Logs


```

org.thaliproject.p2p.btconnectorlib.ApplicationTest:..
org.thaliproject.p2p.btconnectorlib.ConnectionManagerTest:..........................
org.thaliproject.p2p.btconnectorlib.DiscoveryManagerTest:........
Error in testChangeBluetoothStateDuringDiscovery(org.thaliproject.p2p.btconnectorlib.DiscoveryManagerTest):
java.lang.AssertionError: 
Expected: is <RUNNING_BLE>
     but: was <NOT_STARTED>
	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
	at org.junit.Assert.assertThat(Assert.java:956)
	at org.junit.Assert.assertThat(Assert.java:923)
	at org.thaliproject.p2p.btconnectorlib.DiscoveryManagerTest.checkStateWithTimeout(DiscoveryManagerTest.java:60)
	at org.thaliproject.p2p.btconnectorlib.DiscoveryManagerTest.testChangeBluetoothStateDuringDiscovery(DiscoveryManagerTest.java:445)
	at java.lang.reflect.Method.invoke(Native Method)
	at java.lang.reflect.Method.invoke(Method.java:372)
	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
	at org.junit.runners.Suite.runChild(Suite.java:128)
	at org.junit.runners.Suite.runChild(Suite.java:27)
	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
	at android.support.test.internal.runner.TestExecutor.execute(TestExecutor.java:54)
	at android.support.test.runner.AndroidJUnitRunner.onStart(AndroidJUnitRunner.java:240)
	at android.app.Instrumentation$InstrumentationThread.run(Instrumentation.java:1992)
.......................................

Time: 560.036
There was 1 failure:
1) testChangeBluetoothStateDuringDiscovery(org.thaliproject.p2p.btconnectorlib.DiscoveryManagerTest)
java.lang.AssertionError: 
Expected: is <RUNNING_BLE>
     but: was <NOT_STARTED>
	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
	at org.junit.Assert.assertThat(Assert.java:956)
	at org.junit.Assert.assertThat(Assert.java:923)
	at org.thaliproject.p2p.btconnectorlib.DiscoveryManagerTest.checkStateWithTimeout(DiscoveryManagerTest.java:60)
	at org.thaliproject.p2p.btconnectorlib.DiscoveryManagerTest.testChangeBluetoothStateDuringDiscovery(DiscoveryManagerTest.java:445)
	at java.lang.reflect.Method.invoke(Native Method)
	at java.lang.reflect.Method.invoke(Method.java:372)
	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
	at org.junit.runners.Suite.runChild(Suite.java:128)
	at org.junit.runners.Suite.runChild(Suite.java:27)
	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
	at android.support.test.internal.runner.TestExecutor.execute(TestExecutor.java:54)
	at android.support.test.runner.AndroidJUnitRunner.onStart(AndroidJUnitRunner.java:240)
	at android.app.Instrumentation$InstrumentationThread.run(Instrumentation.java:1992)

FAILURES!!!
Tests run: 85,  Failures: 1


,
```
