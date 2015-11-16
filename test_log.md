#### Test 49526184480b105 Logs

Status: 
```

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":23}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_49526184480b105/Sub/serverApp/index.js',
  '{"devices":{"android":23}}' ]

JSON { devices: { android: 23 } }



android : Error: Command failed: Error: Command failed: run_.sh aborted
 [0m


```
###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  f56ad48d Test has  SUCCEEDED
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on f56ad48d 
Device test finished on LGH8153b36be34 
STOP log received from  W3D7N15428022572 Test has  SUCCEEDED
Device test finished on W3D7N15428022572 
Android task is completed 
```

Logcat output:
```
samsung-SM-A500FU: 
--------- beginning of main
,--------- beginning of system
D/ActivityThread( 6074): Added TimaKeyStore provider
V/ActivityThread( 1478): updateVisibility : ActivityRecord{1a8da7f1 token=android.os.BinderProxy@2c5cede {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
V/ActivityThread( 3186): updateVisibility : ActivityRecord{2ab0c246 token=android.os.BinderProxy@14e9dab0 {com.wssyncmldm/com.wssyncmldm.ui.XUIDialogActivity}} show : false
,W/jxcore-log( 6074): Initializing JXcore engine
W/jxcore-log( 6074): JXcore engine is ready
W/jxcore-log( 6074): Starting JXcore engine
W/jxcore-log( 6074): Platform android
W/jxcore-log( 6074): 
W/jxcore-log( 6074): Process ARCH arm
W/jxcore-log( 6074): 
I/jxcore-log( 6074): JXcore Cordova bridge is ready!
I/jxcore-log( 6074): 
W/jxcore-log( 6074): JXcore engine is started
E/jxcore-log( 6074): >> samsung-SM-A500FU
E/jxcore-log( 6074): 
I/jxcore-log( 6074): Total memory 1983791104
I/jxcore-log( 6074): 
I/jxcore-log( 6074): Free memory 32956416
I/jxcore-log( 6074): 
I/jxcore-log( 6074): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6074): 
I/jxcore-log( 6074): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6074): 
I/jxcore-log( 6074): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6074): 
I/jxcore-log( 6074): Size 720 1280
I/jxcore-log( 6074): 
I/jxcore-log( 6074): Screen Brightness 5
I/jxcore-log( 6074): 
E/jxcore-log( 6074): Dummy Error Log.
E/jxcore-log( 6074): 
,I/jxcore-log( 6074): getBuffer is called!!!!
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): Bluetooth turned on
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): WiFi turned off
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): WiFi turned on
I/jxcore-log( 6074): 
,D/ActivityThread( 6136): Added TimaKeyStore provider
,D/ActivityThread( 6166): Added TimaKeyStore provider
,D/ActivityThread( 6181): Added TimaKeyStore provider
,D/ActivityThread( 6206): Added TimaKeyStore provider
,D/ActivityThread( 6225): Added TimaKeyStore provider
,I/jxcore-log( 6074): No internet connection
I/jxcore-log( 6074): 
,D/ActivityThread( 6241): Added TimaKeyStore provider
,D/ActivityThread( 6253): Added TimaKeyStore provider
,D/ActivityThread( 6275): Added TimaKeyStore provider
,D/ActivityThread( 6291): Added TimaKeyStore provider
,D/ActivityThread( 6311): Added TimaKeyStore provider
,D/ActivityThread( 6363): Added TimaKeyStore provider
,V/ActivityThread( 6074): updateVisibility : ActivityRecord{1c131d69 token=android.os.BinderProxy@2eadb14c {com.example.hello/com.example.hello.MainActivity}} show : true
,I/jxcore-log( 6074): No internet connection
I/jxcore-log( 6074): 
,D/ActivityThread( 6404): Added TimaKeyStore provider
,D/ActivityThread( 6420): Added TimaKeyStore provider
,D/ActivityThread( 6436): Added TimaKeyStore provider
,W/ActivityThread( 6436): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/ActivityThread( 6461): Added TimaKeyStore provider
,D/ActivityThread( 6479): Added TimaKeyStore provider
,I/jxcore-log( 6074): No internet connection
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): No internet connection
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): No internet connection
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): No internet connection
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): WiFi
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): Response status code was: 200
I/jxcore-log( 6074): 
,I/jxcore-log( 6074): ****TEST TOOK:  12245  ms ****
I/jxcore-log( 6074): 
I/jxcore-log( 6074): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6074): 
,V/ActivityThread( 1478): updateVisibility : ActivityRecord{1a8da7f1 token=android.os.BinderProxy@2c5cede {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,V/ActivityThread( 3186): updateVisibility : ActivityRecord{2ab0c246 token=android.os.BinderProxy@14e9dab0 {com.wssyncmldm/com.wssyncmldm.ui.XUIDialogActivity}} show : true
,D/ActivityThread( 6599): Added TimaKeyStore provider
,D/ActivityThread( 6623): Added TimaKeyStore provider
,D/ActivityThread( 6613): Added TimaKeyStore provider
,D/ActivityThread( 6644): Added TimaKeyStore provider
,D/ActivityThread( 6661): Added TimaKeyStore provider
,D/ActivityThread( 6677): Added TimaKeyStore provider
,D/ActivityThread( 6692): Added TimaKeyStore provider
,D/ActivityThread( 6712): Added TimaKeyStore provider
,D/ActivityThread( 6722): Added TimaKeyStore provider


LGE-LG-H815: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log( 8324): Initializing JXcore engine
W/jxcore-log( 8324): JXcore engine is ready
W/jxcore-log( 8324): Starting JXcore engine
W/jxcore-log( 8324): Platform android
W/jxcore-log( 8324): 
W/jxcore-log( 8324): Process ARCH arm
W/jxcore-log( 8324): 
I/jxcore-log( 8324): JXcore Cordova bridge is ready!
I/jxcore-log( 8324): 
W/jxcore-log( 8324): JXcore engine is started
E/jxcore-log( 8324): >> LGE-LG-H815
E/jxcore-log( 8324): 
I/jxcore-log( 8324): Total memory 2968948736
I/jxcore-log( 8324): 
I/jxcore-log( 8324): Free memory 86515712
I/jxcore-log( 8324): 
I/jxcore-log( 8324): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 8324): 
I/jxcore-log( 8324): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 8324): 
I/jxcore-log( 8324): userPath [ 'www' ]
I/jxcore-log( 8324): 
I/jxcore-log( 8324): Size 1440 2392
I/jxcore-log( 8324): 
I/jxcore-log( 8324): Screen Brightness 255
I/jxcore-log( 8324): 
E/jxcore-log( 8324): Dummy Error Log.
E/jxcore-log( 8324): 
,I/jxcore-log( 8324): getBuffer is called!!!!
I/jxcore-log( 8324): 
,I/jxcore-log( 8324): Bluetooth turned on
I/jxcore-log( 8324): 
,I/jxcore-log( 8324): WiFi turned off
I/jxcore-log( 8324): 
,I/jxcore-log( 8324): WiFi turned on
I/jxcore-log( 8324): 
,I/jxcore-log( 8324): No internet connection
I/jxcore-log( 8324): 
,I/jxcore-log( 8324): No internet connection
I/jxcore-log( 8324): 
,I/jxcore-log( 8324): No internet connection
I/jxcore-log( 8324): 
,I/jxcore-log( 8324): No internet connection
I/jxcore-log( 8324): 
,I/jxcore-log( 8324): No internet connection
I/jxcore-log( 8324): 
,I/jxcore-log( 8324): No internet connection
I/jxcore-log( 8324): 
,E/ActivityThread( 5073): Failed to find provider info for com.google.android.wearable.settings
,I/jxcore-log( 8324): WiFi
I/jxcore-log( 8324): 
,I/jxcore-log( 8324): Response status code was: 200
I/jxcore-log( 8324): 
,I/jxcore-log( 8324): ****TEST TOOK:  13220  ms ****
I/jxcore-log( 8324): 
I/jxcore-log( 8324): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 8324): 


HUAWEI-ALE-L21: 
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
--------- beginning of main
,W/jxcore-log( 5633): Initializing JXcore engine
W/jxcore-log( 5633): JXcore engine is ready
,W/jxcore-log( 5633): Starting JXcore engine
,W/jxcore-log( 5633): Platform android
W/jxcore-log( 5633): 
W/jxcore-log( 5633): Process ARCH arm
W/jxcore-log( 5633): 
,I/jxcore-log( 5633): JXcore Cordova bridge is ready!
I/jxcore-log( 5633): 
,W/jxcore-log( 5633): JXcore engine is started
,E/jxcore-log( 5633): >> HUAWEI-ALE-L21
E/jxcore-log( 5633): 
,I/jxcore-log( 5633): Total memory 1949741056
I/jxcore-log( 5633): 
,I/jxcore-log( 5633): Free memory 17907712
I/jxcore-log( 5633): 
,I/jxcore-log( 5633): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5633): 
I/jxcore-log( 5633): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5633): 
,I/jxcore-log( 5633): userPath [ 'www' ]
I/jxcore-log( 5633): 
,I/jxcore-log( 5633): Size 720 1184
I/jxcore-log( 5633): 
,I/jxcore-log( 5633): Screen Brightness 242
I/jxcore-log( 5633): 
,E/jxcore-log( 5633): Dummy Error Log.
E/jxcore-log( 5633): 
,I/jxcore-log( 5633): getBuffer is called!!!!
I/jxcore-log( 5633): 
,I/jxcore-log( 5633): Bluetooth turned on
I/jxcore-log( 5633): 
,I/jxcore-log( 5633): WiFi turned off
I/jxcore-log( 5633): 
,I/jxcore-log( 5633): WiFi turned on
I/jxcore-log( 5633): 
,I/jxcore-log( 5633): No internet connection
I/jxcore-log( 5633): 
,I/jxcore-log( 5633): No internet connection
I/jxcore-log( 5633): 
,I/jxcore-log( 5633): No internet connection
I/jxcore-log( 5633): 
,I/jxcore-log( 5633): No internet connection
I/jxcore-log( 5633): 
,I/jxcore-log( 5633): No internet connection
I/jxcore-log( 5633): 
,I/jxcore-log( 5633): WiFi
I/jxcore-log( 5633): 
,I/jxcore-log( 5633): Response status code was: 200
I/jxcore-log( 5633): 
I/jxcore-log( 5633): ****TEST TOOK:  11376  ms ****
I/jxcore-log( 5633): 
,I/jxcore-log( 5633): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5633): 


```

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed 
```

Logcat output:
```
LGE-LG-D722: 
--------- beginning of main
--------- beginning of system
,W/ActivityThread( 1894): Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 1894): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 1894): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3407)
W/ActivityThread( 1894): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3496)
W/ActivityThread( 1894): 	at android.app.ActivityThread.access$1100(ActivityThread.java:155)
W/ActivityThread( 1894): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1352)
W/ActivityThread( 1894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ActivityThread( 1894): 	at android.os.Looper.loop(Looper.java:135)
W/ActivityThread( 1894): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/ActivityThread( 1894): 	at java.lang.reflect.Method.invoke(Native Method)
W/ActivityThread( 1894): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ActivityThread( 1894): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/ActivityThread( 1894): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,W/jxcore-log( 3990): Initializing JXcore engine
W/jxcore-log( 3990): JXcore engine is ready
,W/jxcore-log( 3990): Starting JXcore engine
,W/jxcore-log( 3990): Platform android
W/jxcore-log( 3990): 
W/jxcore-log( 3990): Process ARCH arm
W/jxcore-log( 3990): 
,W/ActivityThread( 4218): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/jxcore-log( 3990): JXcore Cordova bridge is ready!
I/jxcore-log( 3990): 
W/jxcore-log( 3990): JXcore engine is started
,E/jxcore-log( 3990): >> LGE-LG-D722
E/jxcore-log( 3990): 
,I/jxcore-log( 3990): Total memory 906309632
I/jxcore-log( 3990): 
I/jxcore-log( 3990): Free memory 28426240
I/jxcore-log( 3990): 
I/jxcore-log( 3990): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3990): 
I/jxcore-log( 3990): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3990): 
I/jxcore-log( 3990): userPath [ 'www' ]
I/jxcore-log( 3990): 
I/jxcore-log( 3990): Size 720 1196
I/jxcore-log( 3990): 
,I/jxcore-log( 3990): Screen Brightness 255
I/jxcore-log( 3990): 
E/jxcore-log( 3990): Dummy Error Log.
E/jxcore-log( 3990): 
,I/jxcore-log( 3990): getBuffer is called!!!!
I/jxcore-log( 3990): 
,E/ActivityThread( 4444): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@2b518be9 that was originally bound here
E/ActivityThread( 4444): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@2b518be9 that was originally bound here
E/ActivityThread( 4444): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 4444): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 4444): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 4444): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 4444): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4444): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4444): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4444): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4444): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4444): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4444): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4444): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4444): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4444): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4444): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4444): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/jxcore-log( 3990): Bluetooth turned on
I/jxcore-log( 3990): 
,I/jxcore-log( 3990): WiFi turned off
I/jxcore-log( 3990): 
,I/jxcore-log( 3990): WiFi turned on
I/jxcore-log( 3990): 
,I/jxcore-log( 3990): No internet connection
I/jxcore-log( 3990): 
,I/jxcore-log( 3990): No internet connection
I/jxcore-log( 3990): 
,I/jxcore-log( 3990): No internet connection
I/jxcore-log( 3990): 
,I/jxcore-log( 3990): WiFi
I/jxcore-log( 3990): 
,I/jxcore-log( 3990): Response status code was: 200
I/jxcore-log( 3990): 
I/jxcore-log( 3990): ****TEST TOOK:  9414  ms ****
I/jxcore-log( 3990): 
I/jxcore-log( 3990): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3990): 


LGE-Nexus 5: 
--------- beginning of system
--------- beginning of main
,W/ActivityThread( 2779): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/jxcore-log( 2837): Initializing JXcore engine
W/jxcore-log( 2837): JXcore engine is ready
,W/jxcore-log( 2837): Starting JXcore engine
,W/jxcore-log( 2837): Platform android
W/jxcore-log( 2837): 
W/jxcore-log( 2837): Process ARCH arm
W/jxcore-log( 2837): 
,I/jxcore-log( 2837): JXcore Cordova bridge is ready!
I/jxcore-log( 2837): 
,W/jxcore-log( 2837): JXcore engine is started
,E/jxcore-log( 2837): >> LGE-Nexus 5
E/jxcore-log( 2837): 
I/jxcore-log( 2837): Total memory 1946181632
I/jxcore-log( 2837): 
I/jxcore-log( 2837): Free memory 305459200
I/jxcore-log( 2837): 
,I/jxcore-log( 2837): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2837): 
I/jxcore-log( 2837): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2837): 
,I/jxcore-log( 2837): userPath [ 'www' ]
I/jxcore-log( 2837): 
,I/jxcore-log( 2837): Size 1080 1776
I/jxcore-log( 2837): 
,I/jxcore-log( 2837): Screen Brightness 82
I/jxcore-log( 2837): 
,E/jxcore-log( 2837): Dummy Error Log.
E/jxcore-log( 2837): 
,I/jxcore-log( 2837): getBuffer is called!!!!
I/jxcore-log( 2837): 
,I/jxcore-log( 2837): Bluetooth turned on
I/jxcore-log( 2837): 
,I/jxcore-log( 2837): WiFi turned off
I/jxcore-log( 2837): 
,I/jxcore-log( 2837): WiFi turned on
I/jxcore-log( 2837): 
,I/jxcore-log( 2837): No internet connection
I/jxcore-log( 2837): 
,I/jxcore-log( 2837): No internet connection
I/jxcore-log( 2837): 
,I/jxcore-log( 2837): No internet connection
I/jxcore-log( 2837): 
,I/jxcore-log( 2837): No internet connection
I/jxcore-log( 2837): 
,I/jxcore-log( 2837): WiFi
I/jxcore-log( 2837): 
,I/jxcore-log( 2837): Response status code was: 200
I/jxcore-log( 2837): 
,I/jxcore-log( 2837): ****TEST TOOK:  10286  ms ****
I/jxcore-log( 2837): 
I/jxcore-log( 2837): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2837): 


```

####Node name: thali03
Console output:
```
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
STOP log received from  320414cd475f91e3 Test has  SUCCEEDED
STOP log received from  TA4750HV7I Test has  SUCCEEDED
Device test finished on 320414cd475f91e3 
Device test finished on TA4750HV7I 
Android task is completed 
```

Logcat output:
```
samsung-SM-G800F: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
D/ActivityThread( 6806): Added TimaKesytore provider
,W/jxcore-log( 6806): Initializing JXcore engine
,W/jxcore-log( 6806): JXcore engine is ready
,W/jxcore-log( 6806): Starting JXcore engine
,W/jxcore-log( 6806): Platform android
W/jxcore-log( 6806): 
,W/jxcore-log( 6806): Process ARCH arm
W/jxcore-log( 6806): 
,I/jxcore-log( 6806): JXcore Cordova bridge is ready!
I/jxcore-log( 6806): 
,W/jxcore-log( 6806): JXcore engine is started
,E/jxcore-log( 6806): >> samsung-SM-G800F
E/jxcore-log( 6806): 
,I/jxcore-log( 6806): Total memory 1319530496
I/jxcore-log( 6806): 
,I/jxcore-log( 6806): Free memory 32256000
I/jxcore-log( 6806): 
I/jxcore-log( 6806): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6806): 
,I/jxcore-log( 6806): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6806): 
,I/jxcore-log( 6806): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6806): 
,I/jxcore-log( 6806): Size 720 1280
I/jxcore-log( 6806): 
,I/jxcore-log( 6806): Screen Brightness 134
I/jxcore-log( 6806): 
,E/jxcore-log( 6806): Dummy Error Log.
E/jxcore-log( 6806): 
,I/jxcore-log( 6806): getBuffer is called!!!!
I/jxcore-log( 6806): 
,I/jxcore-log( 6806): Bluetooth turned on
I/jxcore-log( 6806): 
I/jxcore-log( 6806): WiFi turned off
I/jxcore-log( 6806): 
I/jxcore-log( 6806): WiFi turned on
I/jxcore-log( 6806): 
,D/ActivityThread( 6858): Added TimaKesytore provider
,I/jxcore-log( 6806): No internet connection
I/jxcore-log( 6806): 
,D/ActivityThread( 6890): Added TimaKesytore provider
,D/ActivityThread( 6904): Added TimaKesytore provider
,D/ActivityThread( 6916): Added TimaKesytore provider
,I/jxcore-log( 6806): No internet connection
I/jxcore-log( 6806): 
,D/ActivityThread( 6928): Added TimaKesytore provider
,D/ActivityThread( 6941): Added TimaKesytore provider
,D/ActivityThread( 6956): Added TimaKesytore provider
,I/jxcore-log( 6806): No internet connection
I/jxcore-log( 6806): 
,D/ActivityThread( 6969): Added TimaKesytore provider
,I/jxcore-log( 6806): No internet connection
I/jxcore-log( 6806): 
,D/ActivityThread( 7016): Added TimaKesytore provider
,D/ActivityThread( 7035): Added TimaKesytore provider
,D/ActivityThread( 7045): Added TimaKesytore provider
,I/jxcore-log( 6806): No internet connection
I/jxcore-log( 6806): 
,I/jxcore-log( 6806): WiFi
I/jxcore-log( 6806): 
,I/jxcore-log( 6806): Response status code was: 200
I/jxcore-log( 6806): 
,I/jxcore-log( 6806): ****TEST TOOK:  11429  ms ****
I/jxcore-log( 6806): 
,I/jxcore-log( 6806): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6806): 
,D/ActivityThread( 7107): Added TimaKesytore provider
,D/ActivityThread( 7119): Added TimaKesytore provider
,D/ActivityThread( 7153): Added TimaKesytore provider
,D/ActivityThread( 7166): Added TimaKesytore provider
,D/ActivityThread( 7184): Added TimaKesytore provider
,D/ActivityThread( 7199): Added TimaKesytore provider
,D/ActivityThread( 7213): Added TimaKesytore provider
,D/ActivityThread( 7229): Added TimaKesytore provider
,D/ActivityThread( 7251): Added TimaKesytore provider
,D/ActivityThread( 7269): Added TimaKesytore provider
,D/ActivityThread( 7286): Added TimaKesytore provider
,D/ActivityThread( 7299): Added TimaKesytore provider
,D/ActivityThread( 7311): Added TimaKesytore provider
,D/ActivityThread( 7325): Added TimaKesytore provider
,D/ActivityThread( 7340): Added TimaKesytore provider
,D/ActivityThread( 7363): Added TimaKesytore provider


motorola-XT1039: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,W/jxcore-log( 3807): Initializing JXcore engine
,W/jxcore-log( 3807): JXcore engine is ready
,W/jxcore-log( 3807): Starting JXcore engine
,W/jxcore-log( 3807): Platform android
W/jxcore-log( 3807): 
,W/jxcore-log( 3807): Process ARCH arm
W/jxcore-log( 3807): 
,I/jxcore-log( 3807): JXcore Cordova bridge is ready!
I/jxcore-log( 3807): 
,W/jxcore-log( 3807): JXcore engine is started
,E/jxcore-log( 3807): >> motorola-XT1039
E/jxcore-log( 3807): 
,I/jxcore-log( 3807): Total memory 893136896
I/jxcore-log( 3807): 
I/jxcore-log( 3807): Free memory 40288256
I/jxcore-log( 3807): 
I/jxcore-log( 3807): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3807): 
,I/jxcore-log( 3807): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3807): 
,I/jxcore-log( 3807): userPath [ 'www' ]
I/jxcore-log( 3807): 
,I/jxcore-log( 3807): Size 720 1184
I/jxcore-log( 3807): 
,I/jxcore-log( 3807): Screen Brightness 10
I/jxcore-log( 3807): 
,E/jxcore-log( 3807): Dummy Error Log.
E/jxcore-log( 3807): 
,I/jxcore-log( 3807): getBuffer is called!!!!
I/jxcore-log( 3807): 
,I/jxcore-log( 3807): Bluetooth turned on
I/jxcore-log( 3807): 
,I/jxcore-log( 3807): WiFi turned off
I/jxcore-log( 3807): 
,I/jxcore-log( 3807): WiFi turned on
I/jxcore-log( 3807): 
,I/jxcore-log( 3807): No internet connection
I/jxcore-log( 3807): 
,I/jxcore-log( 3807): No internet connection
I/jxcore-log( 3807): 
,I/jxcore-log( 3807): No internet connection
I/jxcore-log( 3807): 
,E/ActivityThread( 1558): Failed to find provider info for com.motorola.blur.setupprovider
,E/ActivityThread( 1558): Failed to find provider info for com.motorola.blur.setupprovider
,I/jxcore-log( 3807): No internet connection
I/jxcore-log( 3807): 
,E/ActivityThread( 1384): Failed to find provider info for com.google.android.wearable.settings
,I/jxcore-log( 3807): WiFi
I/jxcore-log( 3807): 
,I/jxcore-log( 3807): Response status code was: 200
I/jxcore-log( 3807): 
I/jxcore-log( 3807): ****TEST TOOK:  10320  ms ****
I/jxcore-log( 3807): 
,I/jxcore-log( 3807): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3807): 


LGE-LG-D855: 
--------- beginning of main
--------- beginning of system
W/ActivityThread( 4448): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/ActivityThread( 4526): Failed to find provider info for com.lge.lgaccount.provider
,W/ActivityThread( 2086): Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 2086): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 2086): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3321)
W/ActivityThread( 2086): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3407)
W/ActivityThread( 2086): 	at android.app.ActivityThread.access$1100(ActivityThread.java:148)
W/ActivityThread( 2086): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1312)
W/ActivityThread( 2086): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ActivityThread( 2086): 	at android.os.Looper.loop(Looper.java:135)
W/ActivityThread( 2086): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ActivityThread( 2086): 	at java.lang.reflect.Method.invoke(Native Method)
W/ActivityThread( 2086): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ActivityThread( 2086): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ActivityThread( 2086): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,W/jxcore-log( 4622): Initializing JXcore engine
,W/jxcore-log( 4622): JXcore engine is ready
W/jxcore-log( 4622): Starting JXcore engine
,W/jxcore-log( 4622): Platform android
W/jxcore-log( 4622): 
W/jxcore-log( 4622): Process ARCH arm
W/jxcore-log( 4622): 
,I/jxcore-log( 4622): JXcore Cordova bridge is ready!
I/jxcore-log( 4622): 
W/jxcore-log( 4622): JXcore engine is started
,E/jxcore-log( 4622): >> LGE-LG-D855
E/jxcore-log( 4622): 
,I/jxcore-log( 4622): Total memory 2995761152
I/jxcore-log( 4622): 
I/jxcore-log( 4622): Free memory 826892288
I/jxcore-log( 4622): 
I/jxcore-log( 4622): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4622): 
I/jxcore-log( 4622): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4622): 
I/jxcore-log( 4622): userPath [ 'www' ]
I/jxcore-log( 4622): 
I/jxcore-log( 4622): Size 1440 2392
I/jxcore-log( 4622): 
I/jxcore-log( 4622): Screen Brightness 50
I/jxcore-log( 4622): 
E/jxcore-log( 4622): Dummy Error Log.
E/jxcore-log( 4622): 
,I/jxcore-log( 4622): getBuffer is called!!!!
I/jxcore-log( 4622): 
,D/ActivityThread( 4899): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,E/ActivityThread( 4899): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@215bf6ce that was originally bound here
E/ActivityThread( 4899): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@215bf6ce that was originally bound here
E/ActivityThread( 4899): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
E/ActivityThread( 4899): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
E/ActivityThread( 4899): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
E/ActivityThread( 4899): 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
E/ActivityThread( 4899): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4899): 	at com.android.emailcommon.service.H.a(SourceFile:181)
E/ActivityThread( 4899): 	at com.android.emailcommon.service.H.mb(SourceFile:224)
E/ActivityThread( 4899): 	at com.android.email.service.n.j(SourceFile:160)
E/ActivityThread( 4899): 	at com.android.email.provider.b.a(SourceFile:171)
E/ActivityThread( 4899): 	at com.android.email.provider.b.F(SourceFile:115)
E/ActivityThread( 4899): 	at com.android.email.service.EmailBroadcastProcessorService.kD(SourceFile:305)
E/ActivityThread( 4899): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:130)
E/ActivityThread( 4899): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4899): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4899): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4899): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/jxcore-log( 4622): Bluetooth turned on
I/jxcore-log( 4622): 
,I/jxcore-log( 4622): WiFi turned off
I/jxcore-log( 4622): 
,I/jxcore-log( 4622): WiFi turned on
I/jxcore-log( 4622): 
,I/jxcore-log( 4622): No internet connection
I/jxcore-log( 4622): 
,I/jxcore-log( 4622): No internet connection
I/jxcore-log( 4622): 
,I/jxcore-log( 4622): WiFi
I/jxcore-log( 4622): 
,I/jxcore-log( 4622): Response status code was: 200
I/jxcore-log( 4622): 
I/jxcore-log( 4622): ****TEST TOOK:  8451  ms ****
I/jxcore-log( 4622): 
I/jxcore-log( 4622): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4622): 
,W/ActivityThread( 5534): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());


```

####Node name: thali04
Console output:
```
STOP log received from  0be0c6c6 Test has  SUCCEEDED
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on 0be0c6c6 
Device test finished on ZX1C223JKW 
Android task is completed 
```

Logcat output:
```
samsung-SM-N910C: 
--------- beginning of system
,--------- beginning of main
D/ActivityThread(10988): Added TimaKeyStore provider
V/ActivityThread( 3997): updateVisibility : ActivityRecord{295fda43 token=android.os.BinderProxy@371b40b4 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
,V/ActivityThread(10988): updateVisibility : ActivityRecord{1dbca67a token=android.os.BinderProxy@1100d779 {com.example.hello/com.example.hello.MainActivity}} show : true
,W/jxcore-log(10988): Initializing JXcore engine
W/jxcore-log(10988): JXcore engine is ready
,W/jxcore-log(10988): Starting JXcore engine
,W/jxcore-log(10988): Platform android
W/jxcore-log(10988): 
W/jxcore-log(10988): Process ARCH arm
W/jxcore-log(10988): 
,I/jxcore-log(10988): JXcore Cordova bridge is ready!
I/jxcore-log(10988): 
W/jxcore-log(10988): JXcore engine is started
,E/jxcore-log(10988): >> samsung-SM-N910C
E/jxcore-log(10988): 
,I/jxcore-log(10988): Total memory 2970812416
I/jxcore-log(10988): 
I/jxcore-log(10988): Free memory 101412864
I/jxcore-log(10988): 
I/jxcore-log(10988): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10988): 
I/jxcore-log(10988): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10988): 
,I/jxcore-log(10988): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(10988): 
,I/jxcore-log(10988): Size 1440 2560
I/jxcore-log(10988): 
,I/jxcore-log(10988): Screen Brightness 134
I/jxcore-log(10988): 
E/jxcore-log(10988): Dummy Error Log.
E/jxcore-log(10988): 
,I/jxcore-log(10988): getBuffer is called!!!!
I/jxcore-log(10988): 
,I/jxcore-log(10988): Bluetooth turned on
I/jxcore-log(10988): 
,I/jxcore-log(10988): WiFi turned off
I/jxcore-log(10988): 
,I/jxcore-log(10988): WiFi turned on
I/jxcore-log(10988): 
,D/ActivityThread(11104): Added TimaKeyStore provider
,D/ActivityThread(11133): Added TimaKeyStore provider
,D/ActivityThread(11149): Added TimaKeyStore provider
,D/ActivityThread(11175): Added TimaKeyStore provider
,I/jxcore-log(10988): No internet connection
I/jxcore-log(10988): 
,D/ActivityThread(11217): Added TimaKeyStore provider
,D/ActivityThread(11238): Added TimaKeyStore provider
,W/ActivityThread(11238): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/jxcore-log(10988): No internet connection
I/jxcore-log(10988): 
,D/ActivityThread(11268): Added TimaKeyStore provider
,D/ActivityThread(11286): Added TimaKeyStore provider
,D/ActivityThread(11309): Added TimaKeyStore provider
,D/ActivityThread(11326): Added TimaKeyStore provider
,I/jxcore-log(10988): No internet connection
I/jxcore-log(10988): 
,D/ActivityThread(11342): Added TimaKeyStore provider
,D/ActivityThread(11357): Added TimaKeyStore provider
,D/ActivityThread(11378): Added TimaKeyStore provider
,D/ActivityThread(11395): Added TimaKeyStore provider
,D/ActivityThread(11418): Added TimaKeyStore provider
,D/ActivityThread(11436): Added TimaKeyStore provider
,D/ActivityThread(11457): Added TimaKeyStore provider
,I/jxcore-log(10988): No internet connection
I/jxcore-log(10988): 
,D/ActivityThread(11479): Added TimaKeyStore provider
,D/ActivityThread(11569): Added TimaKeyStore provider
,D/ActivityThread(11608): Added TimaKeyStore provider
,I/jxcore-log(10988): WiFi
I/jxcore-log(10988): 
,D/ActivityThread(11626): Added TimaKeyStore provider
,I/jxcore-log(10988): Response status code was: 200
I/jxcore-log(10988): 
I/jxcore-log(10988): ****TEST TOOK:  10309  ms ****
I/jxcore-log(10988): 
I/jxcore-log(10988): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(10988): 
,D/ActivityThread(11654): Added TimaKeyStore provider


samsung-SM-G900F: 
--------- beginning of system
,--------- beginning of main
D/ActivityThread( 7568): Added TimaKeyStore provider
,W/jxcore-log( 7568): Initializing JXcore engine
W/jxcore-log( 7568): JXcore engine is ready
W/jxcore-log( 7568): Starting JXcore engine
W/jxcore-log( 7568): Platform android
W/jxcore-log( 7568): 
W/jxcore-log( 7568): Process ARCH arm
W/jxcore-log( 7568): 
D/ActivityThread( 7636): Added TimaKeyStore provider
I/jxcore-log( 7568): JXcore Cordova bridge is ready!
I/jxcore-log( 7568): 
W/jxcore-log( 7568): JXcore engine is started
E/jxcore-log( 7568): >> samsung-SM-G900F
E/jxcore-log( 7568): 
I/jxcore-log( 7568): Total memory 1787449344
I/jxcore-log( 7568): 
I/jxcore-log( 7568): Free memory 69885952
I/jxcore-log( 7568): 
I/jxcore-log( 7568): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7568): 
I/jxcore-log( 7568): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 7568): 
I/jxcore-log( 7568): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 7568): 
I/jxcore-log( 7568): Size 1080 1920
I/jxcore-log( 7568): 
I/jxcore-log( 7568): Screen Brightness 134
I/jxcore-log( 7568): 
E/jxcore-log( 7568): Dummy Error Log.
E/jxcore-log( 7568): 
,I/jxcore-log( 7568): getBuffer is called!!!!
I/jxcore-log( 7568): 
,I/jxcore-log( 7568): Bluetooth turned on
I/jxcore-log( 7568): 
,I/jxcore-log( 7568): WiFi turned off
I/jxcore-log( 7568): 
,I/jxcore-log( 7568): WiFi turned on
I/jxcore-log( 7568): 
,I/jxcore-log( 7568): No internet connection
I/jxcore-log( 7568): 
,D/ActivityThread( 7702): Added TimaKeyStore provider
,D/ActivityThread( 7719): Added TimaKeyStore provider
,I/jxcore-log( 7568): No internet connection
I/jxcore-log( 7568): 
,D/ActivityThread( 7741): Added TimaKeyStore provider
,D/ActivityThread( 7760): Added TimaKeyStore provider
,D/ActivityThread( 7780): Added TimaKeyStore provider
,D/ActivityThread( 7801): Added TimaKeyStore provider
,I/jxcore-log( 7568): No internet connection
I/jxcore-log( 7568): 
,D/ActivityThread( 7822): Added TimaKeyStore provider
,D/ActivityThread( 7848): Added TimaKeyStore provider
,I/jxcore-log( 7568): No internet connection
I/jxcore-log( 7568): 
,D/ActivityThread( 7927): Added TimaKeyStore provider
,I/jxcore-log( 7568): No internet connection
I/jxcore-log( 7568): 
,D/ActivityThread( 7966): Added TimaKeyStore provider
,D/ActivityThread( 8006): Added TimaKeyStore provider
,D/ActivityThread( 8025): Added TimaKeyStore provider
,I/jxcore-log( 7568): WiFi
I/jxcore-log( 7568): 
,I/jxcore-log( 7568): Response status code was: 200
I/jxcore-log( 7568): 
I/jxcore-log( 7568): ****TEST TOOK:  11458  ms ****
I/jxcore-log( 7568): 
I/jxcore-log( 7568): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7568): 
,D/ActivityThread( 8081): Added TimaKeyStore provider
,E/ActivityThread( 8081): Unable to setupGraphicsSupport due to missing cache directory
,D/ActivityThread( 8096): Added TimaKeyStore provider
,E/ActivityThread( 8096): Unable to setupGraphicsSupport due to missing cache directory


motorola-XT1072: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 5750): Initializing JXcore engine
W/jxcore-log( 5750): JXcore engine is ready
,W/jxcore-log( 5750): Starting JXcore engine
,W/jxcore-log( 5750): Platform android
W/jxcore-log( 5750): 
,W/jxcore-log( 5750): Process ARCH arm
W/jxcore-log( 5750): 
,I/jxcore-log( 5750): JXcore Cordova bridge is ready!
I/jxcore-log( 5750): 
W/jxcore-log( 5750): JXcore engine is started
,E/jxcore-log( 5750): >> motorola-XT1072
E/jxcore-log( 5750): 
,I/jxcore-log( 5750): Total memory 916258816
I/jxcore-log( 5750): 
,I/jxcore-log( 5750): Free memory 34816000
I/jxcore-log( 5750): 
,I/jxcore-log( 5750): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5750): 
,I/jxcore-log( 5750): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5750): 
,I/jxcore-log( 5750): userPath [ 'www' ]
I/jxcore-log( 5750): 
,I/jxcore-log( 5750): Size 720 1184
I/jxcore-log( 5750): 
,I/jxcore-log( 5750): Screen Brightness 82
I/jxcore-log( 5750): 
E/jxcore-log( 5750): Dummy Error Log.
E/jxcore-log( 5750): 
,I/jxcore-log( 5750): getBuffer is called!!!!
I/jxcore-log( 5750): 
,I/jxcore-log( 5750): Bluetooth turned on
I/jxcore-log( 5750): 
,I/jxcore-log( 5750): WiFi turned off
I/jxcore-log( 5750): 
,I/jxcore-log( 5750): WiFi turned on
I/jxcore-log( 5750): 
,I/jxcore-log( 5750): No internet connection
I/jxcore-log( 5750): 
,I/jxcore-log( 5750): No internet connection
I/jxcore-log( 5750): 
,I/jxcore-log( 5750): No internet connection
I/jxcore-log( 5750): 
,W/ActivityThread( 5928): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/jxcore-log( 5750): No internet connection
I/jxcore-log( 5750): 
,I/jxcore-log( 5750): No internet connection
I/jxcore-log( 5750): 
,I/jxcore-log( 5750): No internet connection
I/jxcore-log( 5750): 
,W/ActivityThread( 6186): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/jxcore-log( 5750): WiFi
I/jxcore-log( 5750): 
,I/jxcore-log( 5750): Response status code was: 200
I/jxcore-log( 5750): 
I/jxcore-log( 5750): ****TEST TOOK:  12354  ms ****
I/jxcore-log( 5750): 
I/jxcore-log( 5750): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5750): 
,E/ActivityThread( 1962): Failed to find provider info for com.google.android.wearable.settings
,W/ActivityThread( 6345): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());


```

####Node name: thali05
Console output:
```
STOP log received from  SH47FWM00508 Test has  SUCCEEDED
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
STOP log received from  1d6a772d Test has  SUCCEEDED
Device test finished on SH47FWM00508 
Device test finished on 1d6a772d 
Device test finished on ZX1G429CRK 
Android task is completed 
```

Logcat output:
```
samsung-SM-N9005: 
--------- beginning of main
,--------- beginning of system
D/ActivityThread( 6564): Added TimaKeyStore provider
D/ActivityThread( 6578): Added TimaKeyStore provider
V/ActivityThread( 1434): updateVisibility : ActivityRecord{e1a2e20 token=android.os.BinderProxy@2157793f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
V/ActivityThread( 1434): updateVisibility : ActivityRecord{e1a2e20 token=android.os.BinderProxy@2157793f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
,W/jxcore-log( 6578): Initializing JXcore engine
W/jxcore-log( 6578): JXcore engine is ready
,W/jxcore-log( 6578): Starting JXcore engine
,W/jxcore-log( 6578): Platform android
W/jxcore-log( 6578): 
W/jxcore-log( 6578): Process ARCH arm
W/jxcore-log( 6578): 
,D/ActivityThread( 6639): Added TimaKeyStore provider
,I/jxcore-log( 6578): JXcore Cordova bridge is ready!
I/jxcore-log( 6578): 
W/jxcore-log( 6578): JXcore engine is started
,E/jxcore-log( 6578): >> samsung-SM-N9005
E/jxcore-log( 6578): 
,I/jxcore-log( 6578): Total memory 2971471872
I/jxcore-log( 6578): 
,I/jxcore-log( 6578): Free memory 339206144
I/jxcore-log( 6578): 
I/jxcore-log( 6578): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6578): 
I/jxcore-log( 6578): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6578): 
,I/jxcore-log( 6578): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 6578): 
,I/jxcore-log( 6578): Size 1080 1920
I/jxcore-log( 6578): 
,I/jxcore-log( 6578): Screen Brightness 162
I/jxcore-log( 6578): 
E/jxcore-log( 6578): Dummy Error Log.
E/jxcore-log( 6578): 
,I/jxcore-log( 6578): getBuffer is called!!!!
I/jxcore-log( 6578): 
,D/ActivityThread( 6657): Added TimaKeyStore provider
,D/ActivityThread( 6673): Added TimaKeyStore provider
,D/ActivityThread( 6688): Added TimaKeyStore provider
,D/ActivityThread( 6704): Added TimaKeyStore provider
,D/ActivityThread( 6720): Added TimaKeyStore provider
,D/ActivityThread( 6735): Added TimaKeyStore provider
,D/ActivityThread( 6757): Added TimaKeyStore provider
,V/ActivityThread( 6578): updateVisibility : ActivityRecord{d12759c token=android.os.BinderProxy@364fc291 {com.example.hello/com.example.hello.MainActivity}} show : true
,I/jxcore-log( 6578): Bluetooth turned on
I/jxcore-log( 6578): 
,I/jxcore-log( 6578): WiFi turned off,
I/jxcore-log( 6578): 
,I/jxcore-log( 6578): WiFi turned on
I/jxcore-log( 6578): 
,D/ActivityThread( 6846): Added TimaKeyStore provider
,I/jxcore-log( 6578): No internet connection
I/jxcore-log( 6578): 
,D/ActivityThread( 6901): Added TimaKeyStore provider
,D/ActivityThread( 6917): Added TimaKeyStore provider
,D/ActivityThread( 6936): Added TimaKeyStore provider
,I/jxcore-log( 6578): No internet connection
I/jxcore-log( 6578): 
,D/ActivityThread( 6956): Added TimaKeyStore provider
,D/ActivityThread( 6975): Added TimaKeyStore provider
,I/jxcore-log( 6578): No internet connection
I/jxcore-log( 6578): 
,D/ActivityThread( 7000): Added TimaKeyStore provider
,D/ActivityThread( 7018): Added TimaKeyStore provider
,D/ActivityThread( 7038): Added TimaKeyStore provider
,I/jxcore-log( 6578): No internet connection
I/jxcore-log( 6578): 
,D/ActivityThread( 7065): Added TimaKeyStore provider
,I/jxcore-log( 6578): No internet connection
I/jxcore-log( 6578): 
,I/jxcore-log( 6578): WiFi
I/jxcore-log( 6578): 
,D/ActivityThread( 7160): Added TimaKeyStore provider
,I/jxcore-log( 6578): Response status code was: 200
I/jxcore-log( 6578): 
I/jxcore-log( 6578): ****TEST TOOK:  11623  ms ****
I/jxcore-log( 6578): 
,I/jxcore-log( 6578): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6578): 
,D/ActivityThread( 7180): Added TimaKeyStore provider
,D/ActivityThread( 7198): Added TimaKeyStore provider
,D/ActivityThread( 7221): Added TimaKeyStore provider
,D/ActivityThread( 7243): Added TimaKeyStore provider
,D/ActivityThread( 7285): Added TimaKeyStore provider
,V/ActivityThread( 1434): updateVisibility : ActivityRecord{e1a2e20 token=android.os.BinderProxy@2157793f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,D/ActivityThread( 7339): Added TimaKeyStore provider
,E/ActivityThread( 7339): Unable to setupGraphicsSupport due to missing cache directory
,D/ActivityThread( 7357): Added TimaKeyStore provider


motorola-Nexus 6: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log( 3622): Initializing JXcore engine
W/jxcore-log( 3622): JXcore engine is ready
W/jxcore-log( 3622): Starting JXcore engine
W/jxcore-log( 3622): Platform android
W/jxcore-log( 3622): 
W/jxcore-log( 3622): Process ARCH arm
W/jxcore-log( 3622): 
I/jxcore-log( 3622): JXcore Cordova bridge is ready!
I/jxcore-log( 3622): 
W/jxcore-log( 3622): JXcore engine is started
E/jxcore-log( 3622): >> motorola-Nexus 6
E/jxcore-log( 3622): 
I/jxcore-log( 3622): Total memory 3113791488
I/jxcore-log( 3622): 
I/jxcore-log( 3622): Free memory 1003888640
I/jxcore-log( 3622): 
I/jxcore-log( 3622): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3622): 
I/jxcore-log( 3622): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3622): 
I/jxcore-log( 3622): userPath [ 'www' ]
I/jxcore-log( 3622): 
I/jxcore-log( 3622): Size 1440 2392
I/jxcore-log( 3622): 
I/jxcore-log( 3622): Screen Brightness 82
I/jxcore-log( 3622): 
E/jxcore-log( 3622): Dummy Error Log.
E/jxcore-log( 3622): 
I/jxcore-log( 3622): getBuffer is called!!!!
I/jxcore-log( 3622): 
,D/ActivityThread( 3789): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,I/jxcore-log( 3622): Bluetooth turned on
,I/jxcore-log( 3622): 
,I/jxcore-log( 3622): WiFi turned off
I/jxcore-log( 3622): 
,I/jxcore-log( 3622): WiFi turned on
I/jxcore-log( 3622): 
,I/jxcore-log( 3622): No internet connection
I/jxcore-log( 3622): 
,I/jxcore-log( 3622): No internet connection
I/jxcore-log( 3622): 
,I/jxcore-log( 3622): No internet connection
I/jxcore-log( 3622): 
,I/jxcore-log( 3622): No internet connection
I/jxcore-log( 3622): 
,I/jxcore-log( 3622): WiFi
I/jxcore-log( 3622): 
,I/jxcore-log( 3622): Response status code was: 200
I/jxcore-log( 3622): 
I/jxcore-log( 3622): ****TEST TOOK:  10303  ms ****
I/jxcore-log( 3622): 
I/jxcore-log( 3622): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3622): 
,--------- beginning of crash
,E/ActivityThread( 1374): Performing stop of activity that is not resumed: {com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
E/ActivityThread( 1374): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
E/ActivityThread( 1374): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3344)
E/ActivityThread( 1374): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3425)
E/ActivityThread( 1374): 	at android.app.ActivityThread.access$1100(ActivityThread.java:151)
E/ActivityThread( 1374): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1332)
E/ActivityThread( 1374): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 1374): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 1374): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/ActivityThread( 1374): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 1374): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 1374): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/ActivityThread( 1374): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,I/ActivityThread( 4456): Removing dead content provider:android.content.ContentProviderProxy@11135057


HTC-HTC One_M8: 
--------- beginning of main
--------- beginning of system
,D/ActivityThread( 4286): Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider
,W/jxcore-log( 4305): Initializing JXcore engine,
W/jxcore-log( 4305): JXcore engine is ready
,W/jxcore-log( 4305): Starting JXcore engine
,W/jxcore-log( 4305): Platform android,
W/jxcore-log( 4305): 
W/jxcore-log( 4305): Process ARCH arm
W/jxcore-log( 4305): 
,I/jxcore-log( 4305): JXcore Cordova bridge is ready!,
I/jxcore-log( 4305): 
W/jxcore-log( 4305): JXcore engine is started
,E/jxcore-log( 4305): >> HTC-HTC One_M8,
E/jxcore-log( 4305): 
I/jxcore-log( 4305): Total memory 1912020992
I/jxcore-log( 4305): 
I/jxcore-log( 4305): Free memory 160911360
I/jxcore-log( 4305): 
I/jxcore-log( 4305): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4305): 
,I/jxcore-log( 4305): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4305): 
,I/jxcore-log( 4305): userPath [ 'www' ],
I/jxcore-log( 4305): 
,I/jxcore-log( 4305): Size 1080 1776
I/jxcore-log( 4305): 
,I/jxcore-log( 4305): Screen Brightness 142,
I/jxcore-log( 4305): 
,E/jxcore-log( 4305): Dummy Error Log.,
E/jxcore-log( 4305): 
,W/ActivityThread( 4511): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/ActivityThread( 4531): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/jxcore-log( 4305): getBuffer is called!!!!,
I/jxcore-log( 4305): 
,E/ActivityThread( 4820): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@2f4d1608 that was originally bound here,
E/ActivityThread( 4820): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@2f4d1608 that was originally bound here
E/ActivityThread( 4820): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1183)
E/ActivityThread( 4820): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1077)
E/ActivityThread( 4820): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1880)
E/ActivityThread( 4820): 	at android.app.ContextImpl.bindService(ContextImpl.java:1863)
,E/ActivityThread( 4820): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4820): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4820): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4820): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4820): 	at com.android.email.provider.b.a(SourceFile:198),
E/ActivityThread( 4820): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4820): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4820): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4820): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4820): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4820): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread( 4820): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ActivityThread( 4891): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,W/ActivityThread( 4917): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/jxcore-log( 4305): Bluetooth turned on
I/jxcore-log( 4305): 
,I/jxcore-log( 4305): WiFi turned off
I/jxcore-log( 4305): 
,I/jxcore-log( 4305): WiFi turned on,
I/jxcore-log( 4305): 
,E/ActivityThread( 4531): Failed to find provider info for com.google.android.wearable.settings
,W/ActivityThread( 5137): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/jxcore-log( 4305): No internet connection
I/jxcore-log( 4305): 
,I/jxcore-log( 4305): No internet connection,
I/jxcore-log( 4305): 
,I/jxcore-log( 4305): No internet connection,
I/jxcore-log( 4305): 
,E/ActivityThread( 4383): Failed to find provider info for com.htc.vowifi,
,E/ActivityThread( 4383): Failed to find provider info for com.htc.vowifi,
,W/ActivityThread( 5556): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,I/jxcore-log( 4305): WiFi,
I/jxcore-log( 4305): 
,I/jxcore-log( 4305): Response status code was: 200,
I/jxcore-log( 4305): 
I/jxcore-log( 4305): ****TEST TOOK:  9257  ms ****
I/jxcore-log( 4305): 
I/jxcore-log( 4305): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4305): 
,W/ActivityThread( 5829): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());


```

####Node name: thali06
Console output:
```
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
STOP log received from  FA55PYS00566 Test has  SUCCEEDED
Device test finished on 022678fb504e29b0 
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 7970f88c 
Device test finished on FA55PYS00566 
Android task is completed 
```

Logcat output:
```
samsung-SM-A300FU: 
--------- beginning of main
--------- beginning of system
,D/ActivityThread( 5995): Added TimaKeyStore provider
V/ActivityThread( 1477): updateVisibility : ActivityRecord{3c0b894c token=android.os.BinderProxy@6b7f2fb {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
,V/ActivityThread( 5995): updateVisibility : ActivityRecord{214e22f0 token=android.os.BinderProxy@3f02e6a2 {com.example.hello/com.example.hello.MainActivity}} show : true
,W/jxcore-log( 5995): Initializing JXcore engine
W/jxcore-log( 5995): JXcore engine is ready
,W/jxcore-log( 5995): Starting JXcore engine
,W/jxcore-log( 5995): Platform android
W/jxcore-log( 5995): 
W/jxcore-log( 5995): Process ARCH arm
W/jxcore-log( 5995): 
,I/jxcore-log( 5995): JXcore Cordova bridge is ready!
I/jxcore-log( 5995): 
,W/jxcore-log( 5995): JXcore engine is started
,E/jxcore-log( 5995): >> samsung-SM-A300FU
E/jxcore-log( 5995): 
,I/jxcore-log( 5995): Total memory 1451114496
I/jxcore-log( 5995): 
,I/jxcore-log( 5995): Free memory 23314432
I/jxcore-log( 5995): 
I/jxcore-log( 5995): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5995): 
I/jxcore-log( 5995): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5995): 
,I/jxcore-log( 5995): userPath [ 'www' ]
I/jxcore-log( 5995): 
,I/jxcore-log( 5995): Size 540 960
I/jxcore-log( 5995): 
,I/jxcore-log( 5995): Screen Brightness 160
I/jxcore-log( 5995): 
,E/jxcore-log( 5995): Dummy Error Log.
E/jxcore-log( 5995): 
,I/jxcore-log( 5995): getBuffer is called!!!!
I/jxcore-log( 5995): 
,D/ActivityThread( 6044): Added TimaKeyStore provider
,I/jxcore-log( 5995): Bluetooth turned on
I/jxcore-log( 5995): 
,I/jxcore-log( 5995): WiFi turned off,
I/jxcore-log( 5995): 
,I/jxcore-log( 5995): WiFi turned on
I/jxcore-log( 5995): 
,D/ActivityThread( 6082): Added TimaKeyStore provider
,D/ActivityThread( 6112): Added TimaKeyStore provider
,D/ActivityThread( 6127): Added TimaKeyStore provider
,D/ActivityThread( 6144): Added TimaKeyStore provider
,I/jxcore-log( 5995): No internet connection
I/jxcore-log( 5995): 
,W/ActivityThread( 6144): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/ActivityThread( 6173): Added TimaKeyStore provider
,D/ActivityThread( 6192): Added TimaKeyStore provider
,D/ActivityThread( 6208): Added TimaKeyStore provider
,D/ActivityThread( 6225): Added TimaKeyStore provider
,D/ActivityThread( 6242): Added TimaKeyStore provider
,I/jxcore-log( 5995): No internet connection,
I/jxcore-log( 5995): 
,D/ActivityThread( 6257): Added TimaKeyStore provider
,D/ActivityThread( 6280): Added TimaKeyStore provider
,D/ActivityThread( 6298): Added TimaKeyStore provider
,D/ActivityThread( 6316): Added TimaKeyStore provider
,I/jxcore-log( 5995): No internet connection
I/jxcore-log( 5995): 
,D/ActivityThread( 6382): Added TimaKeyStore provider
,I/jxcore-log( 5995): No internet connection
I/jxcore-log( 5995): 
,I/jxcore-log( 5995): No internet connection
I/jxcore-log( 5995): 
,I/jxcore-log( 5995): WiFi
I/jxcore-log( 5995): 
,I/jxcore-log( 5995): Response status code was: 200
I/jxcore-log( 5995): 
,I/jxcore-log( 5995): ****TEST TOOK:  11269  ms ****
I/jxcore-log( 5995): 
I/jxcore-log( 5995): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5995): 
,D/ActivityThread( 6495): Added TimaKeyStore provider
,D/ActivityThread( 6512): Added TimaKeyStore provider
,D/ActivityThread( 6532): Added TimaKeyStore provider


HTC-HTC One M8s: 
--------- beginning of system
--------- beginning of main
,W/ActivityThread( 4887): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/jxcore-log( 4916): Initializing JXcore engine
W/jxcore-log( 4916): JXcore engine is ready
W/jxcore-log( 4916): Starting JXcore engine
W/jxcore-log( 4916): Platform android
W/jxcore-log( 4916): 
W/jxcore-log( 4916): Process ARCH arm
W/jxcore-log( 4916): 
I/jxcore-log( 4916): JXcore Cordova bridge is ready!
I/jxcore-log( 4916): 
W/jxcore-log( 4916): JXcore engine is started
E/jxcore-log( 4916): >> HTC-HTC One M8s
E/jxcore-log( 4916): 
I/jxcore-log( 4916): Total memory 1931808768
I/jxcore-log( 4916): 
I/jxcore-log( 4916): Free memory 85659648
I/jxcore-log( 4916): 
I/jxcore-log( 4916): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4916): 
I/jxcore-log( 4916): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4916): 
I/jxcore-log( 4916): userPath [ 'www' ]
I/jxcore-log( 4916): 
I/jxcore-log( 4916): Size 1080 1776
I/jxcore-log( 4916): 
I/jxcore-log( 4916): Screen Brightness 142
I/jxcore-log( 4916): 
E/jxcore-log( 4916): Dummy Error Log.
E/jxcore-log( 4916): 
,I/jxcore-log( 4916): getBuffer is called!!!!,
I/jxcore-log( 4916): 
,E/ActivityThread( 4511): Failed to find provider info for com.google.android.wearable.settings
,W/ActivityThread( 5139): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,E/ActivityThread( 4511): Failed to find provider info for com.google.android.wearable.settings
,W/ActivityThread( 5297): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,I/jxcore-log( 4916): Bluetooth turned on
I/jxcore-log( 4916): 
,I/jxcore-log( 4916): WiFi turned off,
I/jxcore-log( 4916): 
,I/jxcore-log( 4916): WiFi turned on
I/jxcore-log( 4916): 
,I/jxcore-log( 4916): No internet connection,
I/jxcore-log( 4916): 
,I/jxcore-log( 4916): No internet connection,
I/jxcore-log( 4916): 
,E/ActivityThread( 5427): Failed to find provider info for com.htc.vowifi
,E/ActivityThread( 5427): Failed to find provider info for com.htc.vowifi,
,I/jxcore-log( 4916): No internet connection
I/jxcore-log( 4916): 
,W/ActivityThread( 5706): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
,I/jxcore-log( 4916): No internet connection
I/jxcore-log( 4916): 
,I/jxcore-log( 4916): No internet connection
I/jxcore-log( 4916): 
,I/jxcore-log( 4916): WiFi,
I/jxcore-log( 4916): 
,I/jxcore-log( 4916): Response status code was: 200,
I/jxcore-log( 4916): 
I/jxcore-log( 4916): ****TEST TOOK:  11468  ms ****
I/jxcore-log( 4916): 
I/jxcore-log( 4916): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4916): 
,W/ActivityThread( 5980): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());


LGE-LG-D802: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,W/jxcore-log( 4451): Initializing JXcore engine
W/jxcore-log( 4451): JXcore engine is ready
W/jxcore-log( 4451): Starting JXcore engine
W/jxcore-log( 4451): Platform android
W/jxcore-log( 4451): 
W/jxcore-log( 4451): Process ARCH arm
W/jxcore-log( 4451): 
I/jxcore-log( 4451): JXcore Cordova bridge is ready!
I/jxcore-log( 4451): 
W/jxcore-log( 4451): JXcore engine is started
E/jxcore-log( 4451): >> LGE-LG-D802
E/jxcore-log( 4451): 
I/jxcore-log( 4451): Total memory 1943035904
I/jxcore-log( 4451): 
I/jxcore-log( 4451): Free memory 412061696
I/jxcore-log( 4451): 
I/jxcore-log( 4451): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4451): 
,I/jxcore-log( 4451): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4451): 
I/jxcore-log( 4451): userPath [ 'www' ]
I/jxcore-log( 4451): 
I/jxcore-log( 4451): Size 1080 1776
I/jxcore-log( 4451): 
I/jxcore-log( 4451): Screen Brightness 255
I/jxcore-log( 4451): 
,E/jxcore-log( 4451): Dummy Error Log.
E/jxcore-log( 4451): 
,I/jxcore-log( 4451): getBuffer is called!!!!
I/jxcore-log( 4451): 
,I/jxcore-log( 4451): Bluetooth turned on
I/jxcore-log( 4451): 
,I/jxcore-log( 4451): WiFi turned off
I/jxcore-log( 4451): 
,I/jxcore-log( 4451): WiFi turned on
I/jxcore-log( 4451): 
,I/jxcore-log( 4451): No internet connection
I/jxcore-log( 4451): 
,I/jxcore-log( 4451): No internet connection
I/jxcore-log( 4451): 
,I/jxcore-log( 4451): No internet connection
I/jxcore-log( 4451): 
,I/jxcore-log( 4451): No internet connection
I/jxcore-log( 4451): 
,E/ActivityThread(  962): Failed to find provider info for com.lge.ims.provisioning
,I/jxcore-log( 4451): WiFi
I/jxcore-log( 4451): 
,I/jxcore-log( 4451): Response status code was: 200
I/jxcore-log( 4451): 
I/jxcore-log( 4451): ****TEST TOOK:  10250  ms ****
I/jxcore-log( 4451): 
,I/jxcore-log( 4451): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4451): 


```

####Node name: thali07
Console output:
```
Error! Unexpected exit on device c5afcdcb app:com.example.hello code:0 
child process exited with code 0 on device c5afcdcb 
STOP log received from  4db5c8cc Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Android task is completed 
```

Logcat output:
```
samsung-SM-G900F: 
--------- beginning of main
--------- beginning of system
D/ActivityThread( 5745): Added TimaKeyStore provider
,D/ActivityThread( 5764): Added TimaKeyStore provider
D/ActivityThread( 5781): Added TimaKeyStore provider
D/ActivityThread( 5820): Added TimaKeyStore provider
,D/ActivityThread( 5877): Added TimaKeyStore provider
D/ActivityThread( 5909): Added TimaKeyStore provider
,D/ActivityThread( 5926): Added TimaKeyStore provider
,W/jxcore-log( 5820): Initializing JXcore engine
W/jxcore-log( 5820): JXcore engine is ready
,W/jxcore-log( 5820): Starting JXcore engine
,D/ActivityThread( 5945): Added TimaKeyStore provider
,W/jxcore-log( 5820): Platform android
W/jxcore-log( 5820): 
W/jxcore-log( 5820): Process ARCH arm
W/jxcore-log( 5820): 
,I/jxcore-log( 5820): JXcore Cordova bridge is ready!
I/jxcore-log( 5820): 
W/jxcore-log( 5820): JXcore engine is started


samsung-SM-A500FU: 
--------- beginning of main
--------- beginning of system
D/ActivityThread( 2808): Added TimaKeyStore provider
D/ActivityThread( 2838): Added TimaKeyStore provider
D/ActivityThread( 2868): Added TimaKeyStore provider
,E/ActivityThread( 2868): Failed to find provider info for flipboard.auth.internal.debug
E/ActivityThread( 2868): Failed to find provider info for flipboard.auth.internal
D/ActivityThread( 2898): Added TimaKeyStore provider
D/ActivityThread( 2915): Added TimaKeyStore provider
D/ActivityThread( 2947): Added TimaKeyStore provider
,D/ActivityThread( 2971): Added TimaKeyStore provider
,V/ActivityThread( 1505): updateVisibility : ActivityRecord{4f1fff9 token=android.os.BinderProxy@843e32b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,D/ActivityThread( 2986): Added TimaKeyStore provider
,V/ActivityThread( 1505): updateVisibility : ActivityRecord{4f1fff9 token=android.os.BinderProxy@843e32b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
,D/ActivityThread( 3004): Added TimaKeyStore provider
,D/ActivityThread( 3038): Added TimaKeyStore provider
,D/ActivityThread( 3076): Added TimaKeyStore provider
,W/ActivityThread( 3076): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/ActivityThread( 3103): Added TimaKeyStore provider
,W/ActivityThread( 2838): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/ActivityThread( 3151): Added TimaKeyStore provider
,D/ActivityThread( 3168): Added TimaKeyStore provider
,D/ActivityThread( 3183): Added TimaKeyStore provider
,D/ActivityThread( 3192): Added TimaKeyStore provider
,D/ActivityThread( 3213): Added TimaKeyStore provider
,D/ActivityThread( 3235): Added TimaKeyStore provider
,W/jxcore-log( 2986): Initializing JXcore engine
W/jxcore-log( 2986): JXcore engine is ready
,W/jxcore-log( 2986): Starting JXcore engine
,W/jxcore-log( 2986): Platform android
W/jxcore-log( 2986): 
,W/jxcore-log( 2986): Process ARCH arm
W/jxcore-log( 2986): 
,I/jxcore-log( 2986): JXcore Cordova bridge is ready!
I/jxcore-log( 2986): 
,W/jxcore-log( 2986): JXcore engine is started
,D/ActivityThread( 3275): Added TimaKeyStore provider
,E/jxcore-log( 2986): >> samsung-SM-A500FU,
E/jxcore-log( 2986): 
,I/jxcore-log( 2986): Total memory 1983787008
I/jxcore-log( 2986): 
,I/jxcore-log( 2986): Free memory 61624320
I/jxcore-log( 2986): 
I/jxcore-log( 2986): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2986): 
I/jxcore-log( 2986): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2986): 
,I/jxcore-log( 2986): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 2986): 
,I/jxcore-log( 2986): Size 720 1280
I/jxcore-log( 2986): 
I/jxcore-log( 2986): Screen Brightness 5
I/jxcore-log( 2986): 
E/jxcore-log( 2986): Dummy Error Log.
E/jxcore-log( 2986): 
,D/ActivityThread( 3299): Added TimaKeyStore provider
,D/ActivityThread( 3319): Added TimaKeyStore provider
,W/ActivityThread( 3299): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/ActivityThread( 3336): Added TimaKeyStore provider
,D/ActivityThread( 3343): Added TimaKeyStore provider
,D/ActivityThread( 3368): Added TimaKeyStore provider
,I/jxcore-log( 2986): getBuffer is called!!!!
I/jxcore-log( 2986): 
,D/ActivityThread( 3385): Added TimaKeyStore provider
,D/ActivityThread( 3408): Added TimaKeyStore provider
,D/ActivityThread( 3422): Added TimaKeyStore provider
,D/ActivityThread( 3439): Added TimaKeyStore provider
,D/ActivityThread( 3458): Added TimaKeyStore provider
,D/ActivityThread( 3478): Added TimaKeyStore provider
,D/ActivityThread( 3486): Added TimaKeyStore provider
,D/ActivityThread( 3520): Added TimaKeyStore provider
,D/ActivityThread( 3537): Added TimaKeyStore provider
,D/ActivityThread( 3552): Added TimaKeyStore provider
,D/ActivityThread( 3572): Added TimaKeyStore provider
,D/ActivityThread( 3584): Added TimaKeyStore provider
,D/ActivityThread( 3610): Added TimaKeyStore provider
,D/ActivityThread( 3629): Added TimaKeyStore provider
,D/ActivityThread( 3653): Added TimaKeyStore provider
,D/ActivityThread( 3666): Added TimaKeyStore provider
,D/ActivityThread( 3683): Added TimaKeyStore provider
,D/ActivityThread( 3710): Added TimaKeyStore provider,
,D/ActivityThread( 3726): Added TimaKeyStore provider
,D/ActivityThread( 3749): Added TimaKeyStore provider
,D/ActivityThread( 3768): Added TimaKeyStore provider
,D/ActivityThread( 3792): Added TimaKeyStore provider
,D/ActivityThread( 3816): Added TimaKeyStore provider
,D/ActivityThread( 3830): Added TimaKeyStore provider
,D/ActivityThread( 3854): Added TimaKeyStore provider
,D/ActivityThread( 3873): Added TimaKeyStore provider
,D/ActivityThread( 3888): Added TimaKeyStore provider
,D/ActivityThread( 3904): Added TimaKeyStore provider
,D/ActivityThread( 3921): Added TimaKeyStore provider
,D/ActivityThread( 3945): Added TimaKeyStore provider
,D/ActivityThread( 3966): Added TimaKeyStore provider
,D/ActivityThread( 3984): Added TimaKeyStore provider
,D/ActivityThread( 4010): Added TimaKeyStore provider
,D/ActivityThread( 4032): Added TimaKeyStore provider
,D/ActivityThread( 4051): Added TimaKeyStore provider
,D/ActivityThread( 4076): Added TimaKeyStore provider,
,D/ActivityThread( 4101): Added TimaKeyStore provider
,D/ActivityThread( 4124): Added TimaKeyStore provider,
,D/ActivityThread( 4144): Added TimaKeyStore provider
,D/ActivityThread( 4170): Added TimaKeyStore provider
,I/jxcore-log( 2986): Bluetooth turned on
I/jxcore-log( 2986): 
,D/ActivityThread( 4188): Added TimaKeyStore provider
,I/jxcore-log( 2986): WiFi turned off
I/jxcore-log( 2986): 
,I/jxcore-log( 2986): WiFi turned on
I/jxcore-log( 2986): 
,D/ActivityThread( 4209): Added TimaKeyStore provider
,D/ActivityThread( 4247): Added TimaKeyStore provider
,D/ActivityThread( 4273): Added TimaKeyStore provider
,D/ActivityThread( 4291): Added TimaKeyStore provider
,D/ActivityThread( 4309): Added TimaKeyStore provider
,D/ActivityThread( 4319): Added TimaKeyStore provider
,I/jxcore-log( 2986): No internet connection
I/jxcore-log( 2986): 
,D/ActivityThread( 4348): Added TimaKeyStore provider
,D/ActivityThread( 4371): Added TimaKeyStore provider
,D/ActivityThread( 4389): Added TimaKeyStore provider
,I/jxcore-log( 2986): No internet connection
I/jxcore-log( 2986): 
,W/ActivityThread( 4389): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/jxcore-log( 2986): No internet connection
I/jxcore-log( 2986): 
,D/ActivityThread( 4481): Added TimaKeyStore provider
,E/ActivityThread( 4481): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@1e02ccb7 that was originally bound here
E/ActivityThread( 4481): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@1e02ccb7 that was originally bound here
E/ActivityThread( 4481): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 4481): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 4481): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 4481): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 4481): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 4481): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4481): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4481): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4481): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4481): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4481): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4481): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4481): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4481): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4481): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 4481): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/ActivityThread( 4520): Added TimaKeyStore provider
,D/ActivityThread( 4540): Added TimaKeyStore provider
,I/jxcore-log( 2986): No internet connection
I/jxcore-log( 2986): 
,E/ActivityThread( 4520): Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,D/ActivityThread( 4577): Added TimaKeyStore provider
,D/ActivityThread( 4604): Added TimaKeyStore provider
,I/jxcore-log( 2986): No internet connection
I/jxcore-log( 2986): 
,D/ActivityThread( 4643): Added TimaKeyStore provider
,D/ActivityThread( 4664): Added TimaKeyStore provider
,W/ActivityThread( 4643): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/ActivityThread( 4664): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/ActivityThread( 4695): Added TimaKeyStore provider
,D/ActivityThread( 4710): Added TimaKeyStore provider
,D/ActivityThread( 4728): Added TimaKeyStore provider
,I/jxcore-log( 2986): No internet connection
I/jxcore-log( 2986): 
,D/ActivityThread( 4748): Added TimaKeyStore provider
,W/ActivityThread( 4748): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/ActivityThread( 4797): Added TimaKeyStore provider
,D/ActivityThread( 4820): Added TimaKeyStore provider
,I/jxcore-log( 2986): WiFi
I/jxcore-log( 2986): 
,I/jxcore-log( 2986): Response status code was: 200
I/jxcore-log( 2986): 
I/jxcore-log( 2986): ****TEST TOOK:  12392  ms ****
I/jxcore-log( 2986): 
I/jxcore-log( 2986): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2986): 
,D/ActivityThread( 4837): Added TimaKeyStore provider
,D/ActivityThread( 4871): Added TimaKeyStore provider
,D/ActivityThread( 4889): Added TimaKeyStore provider


```

####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  SUCCEEDED
STOP log received from  HT574YC04723 Test has  SUCCEEDED
Device test finished on 4325e43f 
Device test finished on HT574YC04723 
Android task is completed 
```

Logcat output:
```
samsung-SM-A300FU: 
--------- beginning of main
,--------- beginning of system
D/ActivityThread( 5645): Added TimaKeyStore provider
W/ActivityThread( 5645): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/ActivityThread( 5681): Added TimaKeyStore provider
V/ActivityThread( 3166): updateVisibility : ActivityRecord{22124756 token=android.os.BinderProxy@1079a6dc {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
,V/ActivityThread( 5681): updateVisibility : ActivityRecord{2a3b6284 token=android.os.BinderProxy@288eef16 {com.example.hello/com.example.hello.MainActivity}} show : true
,W/jxcore-log( 5681): Initializing JXcore engine
W/jxcore-log( 5681): JXcore engine is ready
,W/jxcore-log( 5681): Starting JXcore engine
,W/jxcore-log( 5681): Platform android
W/jxcore-log( 5681): 
W/jxcore-log( 5681): Process ARCH arm
W/jxcore-log( 5681): 
,I/jxcore-log( 5681): JXcore Cordova bridge is ready!,
I/jxcore-log( 5681): 
W/jxcore-log( 5681): JXcore engine is started
,E/jxcore-log( 5681): >> samsung-SM-A300FU
E/jxcore-log( 5681): 
,I/jxcore-log( 5681): Total memory 1451114496
I/jxcore-log( 5681): 
,I/jxcore-log( 5681): Free memory 27619328
I/jxcore-log( 5681): 
I/jxcore-log( 5681): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5681): 
I/jxcore-log( 5681): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5681): 
,I/jxcore-log( 5681): userPath [ 'www' ],
I/jxcore-log( 5681): 
,I/jxcore-log( 5681): Size 540 960
I/jxcore-log( 5681): 
,I/jxcore-log( 5681): Screen Brightness 255
I/jxcore-log( 5681): 
,E/jxcore-log( 5681): Dummy Error Log.
E/jxcore-log( 5681): 
,I/jxcore-log( 5681): getBuffer is called!!!!
I/jxcore-log( 5681): 
,I/jxcore-log( 5681): Bluetooth turned on
I/jxcore-log( 5681): 
,I/jxcore-log( 5681): WiFi turned off,
I/jxcore-log( 5681): 
,I/jxcore-log( 5681): WiFi turned on
I/jxcore-log( 5681): 
,D/ActivityThread( 5749): Added TimaKeyStore provider
,D/ActivityThread( 5782): Added TimaKeyStore provider
,D/ActivityThread( 5801): Added TimaKeyStore provider
,D/ActivityThread( 5813): Added TimaKeyStore provider
,I/jxcore-log( 5681): No internet connection
I/jxcore-log( 5681): 
,D/ActivityThread( 5836): Added TimaKeyStore provider
,D/ActivityThread( 5851): Added TimaKeyStore provider
,D/ActivityThread( 5870): Added TimaKeyStore provider
,D/ActivityThread( 5905): Added TimaKeyStore provider
,D/ActivityThread( 5939): Added TimaKeyStore provider
,D/ActivityThread( 5954): Added TimaKeyStore provider
,D/ActivityThread( 5976): Added TimaKeyStore provider
,I/jxcore-log( 5681): No internet connection
I/jxcore-log( 5681): 
,I/jxcore-log( 5681): No internet connection
I/jxcore-log( 5681): 
,I/jxcore-log( 5681): No internet connection
I/jxcore-log( 5681): 
,I/jxcore-log( 5681): No internet connection,
I/jxcore-log( 5681): 
,I/jxcore-log( 5681): WiFi
I/jxcore-log( 5681): 
,I/jxcore-log( 5681): Response status code was: 200
I/jxcore-log( 5681): 
,I/jxcore-log( 5681): ****TEST TOOK:  11259  ms ****
I/jxcore-log( 5681): 
I/jxcore-log( 5681): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5681): 
,V/ActivityThread( 3166): updateVisibility : ActivityRecord{22124756 token=android.os.BinderProxy@1079a6dc {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/ActivityThread( 6092): Added TimaKeyStore provider
,D/ActivityThread( 6104): Added TimaKeyStore provider
,D/ActivityThread( 6122): Added TimaKeyStore provider
,D/ActivityThread( 6140): Added TimaKeyStore provider


HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log( 2457): Initializing JXcore engine
,W/jxcore-log( 2457): JXcore engine is ready
,W/jxcore-log( 2457): Starting JXcore engine
,W/jxcore-log( 2457): Platform android
W/jxcore-log( 2457): 
,W/jxcore-log( 2457): Process ARCH arm
W/jxcore-log( 2457): 
,I/jxcore-log( 2457): JXcore Cordova bridge is ready!
I/jxcore-log( 2457): 
,W/jxcore-log( 2457): JXcore engine is started
,E/jxcore-log( 2457): >> HTC-HTC Desire 820
E/jxcore-log( 2457): 
,I/jxcore-log( 2457): Total memory 1964650496
I/jxcore-log( 2457): 
I/jxcore-log( 2457): Free memory 773087232
I/jxcore-log( 2457): 
I/jxcore-log( 2457): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2457): 
,I/jxcore-log( 2457): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2457): 
,I/jxcore-log( 2457): userPath [ 'www' ]
I/jxcore-log( 2457): 
,I/jxcore-log( 2457): Size 720 1184
I/jxcore-log( 2457): 
,I/jxcore-log( 2457): Screen Brightness 10
I/jxcore-log( 2457): 
,E/jxcore-log( 2457): Dummy Error Log.
E/jxcore-log( 2457): 
,I/jxcore-log( 2457): getBuffer is called!!!!
I/jxcore-log( 2457): 
,I/jxcore-log( 2457): Bluetooth turned on
I/jxcore-log( 2457): 
,I/jxcore-log( 2457): WiFi turned off
I/jxcore-log( 2457): 
,I/jxcore-log( 2457): WiFi turned on
I/jxcore-log( 2457): 
,I/jxcore-log( 2457): No internet connection
I/jxcore-log( 2457): 
,I/jxcore-log( 2457): No internet connection
I/jxcore-log( 2457): 
,I/jxcore-log( 2457): No internet connection
I/jxcore-log( 2457): 
,I/jxcore-log( 2457): No internet connection
I/jxcore-log( 2457): 
,I/jxcore-log( 2457): No internet connection
I/jxcore-log( 2457): 
,I/jxcore-log( 2457): WiFi
I/jxcore-log( 2457): 
,I/jxcore-log( 2457): Response status code was: 200
I/jxcore-log( 2457): 
,I/jxcore-log( 2457): ****TEST TOOK:  11359  ms ****
I/jxcore-log( 2457): 
,I/jxcore-log( 2457): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2457): 
,D/ActivityThread( 3342): Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider


```

####Node name: thali09
Console output:
```
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
Device test finished on CC51WYC03425 
Android task is completed 
```

Logcat output:
```
HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
D/ActivityThread( 3062): Loading provider com.htc.htccupd_settings: com.htc.providers.settings.HtcCupdProvider
,W/jxcore-log( 3107): Initializing JXcore engine
W/jxcore-log( 3107): JXcore engine is ready
W/jxcore-log( 3107): Starting JXcore engine
,W/jxcore-log( 3107): Platform android
W/jxcore-log( 3107): 
,W/jxcore-log( 3107): Process ARCH arm
W/jxcore-log( 3107): 
,I/jxcore-log( 3107): JXcore Cordova bridge is ready!
I/jxcore-log( 3107): 
,W/jxcore-log( 3107): JXcore engine is started
,E/jxcore-log( 3107): >> HTC-HTC Desire 820
E/jxcore-log( 3107): 
,I/jxcore-log( 3107): Total memory 1964650496
I/jxcore-log( 3107): 
I/jxcore-log( 3107): Free memory 661667840
I/jxcore-log( 3107): 
I/jxcore-log( 3107): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3107): 
,I/jxcore-log( 3107): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3107): 
,I/jxcore-log( 3107): userPath [ 'www' ]
I/jxcore-log( 3107): 
,I/jxcore-log( 3107): Size 720 1184
I/jxcore-log( 3107): 
,I/jxcore-log( 3107): Screen Brightness 142
I/jxcore-log( 3107): 
,E/jxcore-log( 3107): Dummy Error Log.
E/jxcore-log( 3107): 
,I/jxcore-log( 3107): getBuffer is called!!!!
I/jxcore-log( 3107): 
,I/jxcore-log( 3107): Bluetooth turned on
I/jxcore-log( 3107): 
,I/jxcore-log( 3107): WiFi turned off
I/jxcore-log( 3107): 
,I/jxcore-log( 3107): WiFi turned on
I/jxcore-log( 3107): 
,I/jxcore-log( 3107): No internet connection
I/jxcore-log( 3107): 
,I/jxcore-log( 3107): No internet connection
I/jxcore-log( 3107): 
,I/jxcore-log( 3107): No internet connection
I/jxcore-log( 3107): 
,I/jxcore-log( 3107): No internet connection
I/jxcore-log( 3107): 
,I/jxcore-log( 3107): WiFi
I/jxcore-log( 3107): 
,I/jxcore-log( 3107): Response status code was: 200
I/jxcore-log( 3107): 
I/jxcore-log( 3107): ****TEST TOOK:  10349  ms ****
I/jxcore-log( 3107): 
,I/jxcore-log( 3107): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3107): 


LGE-Nexus 5: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,W/jxcore-log( 2251): Initializing JXcore engine
,W/jxcore-log( 2251): JXcore engine is ready
,W/jxcore-log( 2251): Starting JXcore engine
,W/jxcore-log( 2251): Platform android
W/jxcore-log( 2251): 
,W/jxcore-log( 2251): Process ARCH arm
W/jxcore-log( 2251): 
,I/jxcore-log( 2251): JXcore Cordova bridge is ready!
I/jxcore-log( 2251): 
,W/jxcore-log( 2251): JXcore engine is started
,E/jxcore-log( 2251): >> LGE-Nexus 5
E/jxcore-log( 2251): 
,I/jxcore-log( 2251): Total memory 1945137152
I/jxcore-log( 2251): 
I/jxcore-log( 2251): Free memory 870285312
I/jxcore-log( 2251): 
I/jxcore-log( 2251): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2251): 
,I/jxcore-log( 2251): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2251): 
,I/jxcore-log( 2251): userPath [ 'www' ]
I/jxcore-log( 2251): 
,I/jxcore-log( 2251): Size 1080 1776
I/jxcore-log( 2251): 
,I/jxcore-log( 2251): Screen Brightness 1
I/jxcore-log( 2251): 
,E/jxcore-log( 2251): Dummy Error Log.
E/jxcore-log( 2251): 
,I/jxcore-log( 2251): getBuffer is called!!!!
I/jxcore-log( 2251): 
,I/jxcore-log( 2251): Bluetooth turned on
I/jxcore-log( 2251): 
,I/jxcore-log( 2251): WiFi turned off
I/jxcore-log( 2251): 
,I/jxcore-log( 2251): WiFi turned on
I/jxcore-log( 2251): 
,I/jxcore-log( 2251): No internet connection
I/jxcore-log( 2251): 
,I/jxcore-log( 2251): No internet connection
I/jxcore-log( 2251): 
,I/jxcore-log( 2251): No internet connection
I/jxcore-log( 2251): 
,I/jxcore-log( 2251): No internet connection
I/jxcore-log( 2251): 
,I/jxcore-log( 2251): WiFi
I/jxcore-log( 2251): 
,I/jxcore-log( 2251): Response status code was: 200
I/jxcore-log( 2251): 
I/jxcore-log( 2251): ****TEST TOOK:  10215  ms ****
I/jxcore-log( 2251): 
,I/jxcore-log( 2251): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2251): 


```




#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":23}}
Integration server has received  [ 'jx',
  '/home/pi/Test/server_49526184480b105/Sub/serverApp/index.js',
  '{"devices":{"android":23}}' ]

JSON { devices: { android: 23 } }


```

