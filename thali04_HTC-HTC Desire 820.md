#### Test 72314330ebceebb_thali04_HTC-HTC Desire 820 Logs


```

org.thaliproject.p2p.btconnectorlib.ApplicationTest:..
org.thaliproject.p2p.btconnectorlib.ConnectionManagerTest:..........................
org.thaliproject.p2p.btconnectorlib.DiscoveryManagerTest:........
Process crashed while executing testChangeBluetoothStateDuringDiscovery(org.thaliproject.p2p.btconnectorlib.DiscoveryManagerTest):
java.lang.IllegalStateException: BT Adapter is not turned ON
	at android.bluetooth.le.BluetoothLeUtils.checkAdapterStateOn(BluetoothLeUtils.java:136)
	at android.bluetooth.le.BluetoothLeScanner$1.handleMessage(BluetoothLeScanner.java:85)
	at android.os.Handler.dispatchMessage(Handler.java:102)
	at android.os.Looper.loop(Looper.java:168)
	at android.app.ActivityThread.main(ActivityThread.java:5885)
	at java.lang.reflect.Method.invoke(Native Method)
	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:797)
	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:687)
INSTRUMENTATION_RESULT: shortMsg=java.lang.IllegalStateException
INSTRUMENTATION_RESULT: longMsg=java.lang.IllegalStateException: BT Adapter is not turned ON
INSTRUMENTATION_CODE: 0
,
```
