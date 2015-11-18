#### Test 50388019f4ce509_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1019): sending alarm Alarm{42839ce8 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
V/AlarmManager( 1019): sending alarm Alarm{42839000 type 3 android}
V/AlarmManager( 1019): sending alarm Alarm{42838f40 type 2 com.google.android.gms}
V/AlarmManager( 1019): sending alarm Alarm{42839da8 type 0 com.android.vending}
D/ConnectivityService( 1019): Done.
D/ConnectivityService( 1019): Setting timer for 720seconds
--------- beginning of /dev/log/main
D/Finsky  ( 3130): [274] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 3130): [1] 5.onFinished: Installation state replication succeeded.
D/AndroidRuntime( 3404): 
D/AndroidRuntime( 3404): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3404): CheckJNI is OFF
D/dalvikvm( 3404): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3404): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3404): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3404): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3404): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3404): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3404): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3404): failed to load memtrack module: -2
D/AndroidRuntime( 3404): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3404
W/WindowManager( 1019): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1019): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3419 uid=10378 gids={50378, 3003, 3001, 3002}
D/AndroidRuntime( 3404): Shutting down VM
D/dalvikvm( 3404): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 7ms
W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/dalvikvm(  277): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 5ms+2ms, total 24ms
W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 20ms
D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
V/WebViewChromiumFactoryProvider( 3419): Binding Chromium to main looper Looper (main, tid 1) {41f079c0}
I/LibraryLoader( 3419): Expected native library version number "",actual native library version number ""
I/chromium( 3419): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3419): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothAdapter( 3419): 1106362256: getState() :  mService = null. Returning STATE_OFF
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42583d10:true
I/Adreno-EGL( 3419): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3419): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3419): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3419): Local Branch: 
I/Adreno-EGL( 3419): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3419): Local Patches: NONE
I/Adreno-EGL( 3419): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3419): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 3419): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3419): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3419): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3419): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3419): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3419): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3419): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3419): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3419): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3419): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 3419): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3419): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3419): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3419): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3419): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3419): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3419): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 3419): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3419): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3419): Enabling debug mode 0
,W/AwContents( 3419): nativeOnDraw failed; clearing to background color.
,I/LaunchCheckinHandler( 1019): Displayed com.example.hello/.MainActivity,cp,ca,378
I/ActivityManager( 1019): Displayed com.example.hello/.MainActivity: +347ms (total +378ms)
W/AwContents( 3419): nativeOnDraw failed; clearing to background color.
W/IInputConnectionWrapper( 3419): showStatusIcon on inactive InputConnection
,I/chromium( 3419): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 3419): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/JsMessageQueue( 3419): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3419): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x41f0be48
,D/dalvikvm( 3419): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x41f0be48
D/jxcore_app_log( 3419): JniHelper::setJavaVM(0x41553fa8), pthread_self() = 1609120848
,D/JX-Cordova( 3419): jxcore cordova android initializing
,W/jxcore-log( 3419): Initializing JXcore engine
,W/jxcore-log( 3419): JXcore engine is ready
,W/jxcore-log( 3419): Starting JXcore engine
,W/jxcore-log( 3419): Platform android
W/jxcore-log( 3419): 
,W/jxcore-log( 3419): Process ARCH arm
W/jxcore-log( 3419): 
,I/jxcore-log( 3419): JXcore Cordova bridge is ready!
I/jxcore-log( 3419): 
,W/jxcore-log( 3419): JXcore engine is started
,E/jxcore-log( 3419): >> motorola-XT1039
E/jxcore-log( 3419): 
,I/jxcore-log( 3419): Total memory 893136896
I/jxcore-log( 3419): 
I/jxcore-log( 3419): Free memory 38608896
I/jxcore-log( 3419): 
I/jxcore-log( 3419): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3419): 
,I/jxcore-log( 3419): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3419): 
,I/jxcore-log( 3419): userPath [ 'www' ]
I/jxcore-log( 3419): 
,I/jxcore-log( 3419): Size 720 1184
I/jxcore-log( 3419): 
,I/jxcore-log( 3419): Screen Brightness 10
I/jxcore-log( 3419): 
,E/jxcore-log( 3419): Dummy Error Log.
E/jxcore-log( 3419): 
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2434 
,I/jxcore-log( 3419): getBuffer is called!!!!
I/jxcore-log( 3419): 
,I/MMApiBackOffService( 1543): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1543): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1543): MMApiBackOffService told us it's okay to retry the waiting requests: 2
,D/MMApiWebService( 1543): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1543): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1543): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,D/MMApiWebService( 1543): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1543): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,E/MMApiProvisionService( 1543): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1543): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1543): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1543): connectStatus(): app: MMAPIWebServiceRequest backing off: 30000 ms until next web service attempt
,D/Checkin ( 1543): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1543): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1543): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1543): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1543): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1543): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 30000
,D/Checkin ( 1543): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1543): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/Checkin ( 1543): publish the event [tag = MOT_CCE event name = LOG]
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
,D/WifiService( 1019): New client listening to asynchronous messages
,D/WifiService( 1019): setWifiEnabled: false pid=3419, uid=10378
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3419): ****TEST TOOK:  5050  ms ****
I/jxcore-log( 3419): 
I/jxcore-log( 3419): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3419): 
,D/AndroidRuntime( 3470): 
D/AndroidRuntime( 3470): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3470): CheckJNI is OFF
,D/dalvikvm( 3470): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 3470): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3470): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3470): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 3470): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 3470): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,E/memtrack( 3470): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 3470): failed to load memtrack module: -2
,D/AndroidRuntime( 3470): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1019): Force stopping com.example.hello appid=10378 user=-1: uninstall pkg
,I/ActivityManager( 1019): Killing 3419:com.example.hello/u0a378 (adj 0): stop com.example.hello
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/WindowState( 1019): WIN DEATH: Window{429dacf0 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService( 1019): Client connection lost with reason: 4
,I/ActivityManager( 1019):   Force finishing activity ActivityRecord{4298d480 u0 com.example.hello/.MainActivity t3}
,W/PackageSettings( 1019): Skipping PackageSetting{42206c08 com.test.thalitest/10377} due to missing metadata
,I/ActivityManager( 1019): Force stopping com.example.hello appid=10378 user=0: pkg removed
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/dalvikvm( 2144): GC_EXPLICIT freed 4648K, 45% free 9622K/17224K, paused 2ms+5ms, total 64ms
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
I/OtaApp  ( 1543): [info] > Updatetime from metadata: 10
D/Checkin ( 1543): publish the event [tag = MOT_OTA event name = LOG]
,I/LatinIME:LogUtils( 1186): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/LatinIME:LogUtils( 1186): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,D/dalvikvm( 1297): GC_EXPLICIT freed 2692K, 33% free 11589K/17224K, paused 2ms+4ms, total 95ms
,I/Launcher( 1297): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,D/OtaApp  ( 1543): [debug] > cancelling the previous pending intent set for install later
,W/GeofencerStateMachine( 1202): Ignoring removeGeofence because network location is disabled.
,I/OtaApp  ( 1543): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1543): publish the event [tag = MOT_OTA event name = LOG]
,D/dalvikvm( 1019): GC_EXPLICIT freed 1946K, 13% free 17883K/20348K, paused 3ms+10ms, total 120ms
,I/LatinIME:LogUtils( 1186): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1447834412
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/dalvikvm( 2176): GC_EXPLICIT freed 3002K, 42% free 10057K/17224K, paused 2ms+7ms, total 155ms
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,D/VoicemailCleanupService( 3072): Cleaning up data for package: com.example.hello
,D/dalvikvm( 1019): WAIT_FOR_CONCURRENT_GC blocked 88ms
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,D/OtaApp  ( 1543): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,W/InputMethodManagerService( 1019): Got RemoteException sending setActive(false) notification to pid 3419 uid 10378
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
W/Binder  ( 1186): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1186): java.lang.NullPointerException
W/Binder  ( 1186): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1186): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1186): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1186): 	at dalvik.system.NativeStart.run(Native Method)
I/Launcher( 1297): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,D/OtaApp  ( 1543): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
I/InternalIcingCorporaPro( 2176): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/ActivityManager( 1019): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3500 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,I/LatinIME:LogUtils( 1186): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1447834412
,D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,V/BackupManagerService( 1019): removePackageParticipantsLocked: uid=10378 #1
,W/ContextImpl( 3500): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
,D/dalvikvm( 1019): GC_EXPLICIT freed 655K, 13% free 17754K/20348K, paused 3ms+12ms, total 171ms
,I/dalvikvm( 3130): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3130): VFY: unable to resolve virtual method 338: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3130): VFY: replacing opcode 0x6e at 0x0013
,I/InternalIcingCorporaPro( 2176): UpdateCorporaTask done [took 96 ms] updated apps [took 95 ms] 
,D/PackageBroadcastService( 1380): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1380): Clearing selected account for com.example.hello
,D/ChimeraCfgMgr( 1380): Loading module com.google.android.gms.games from APK com.google.android.gms
,I/LocationSettingsChecker( 1380): Removing dialog suppression flag for package com.example.hello
,E/NetworkScheduler.SchedulerReceiver( 1337): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1337): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 1380): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1380): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1380): 0 metrics were deleted when clearing package com.example.hello.
,D/gH_CompatibleDatabase( 1380): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/ActivityManager( 1019): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3521 uid=10058 gids={50058}
,D/gH_CompatibleDatabase( 1380): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1380): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1380): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,I/PeopleContactsSync( 1380): CP2 sync disabled
,D/gH_CompatibleDatabase( 1380): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1380): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1380): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1380): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1380): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
I/Icing   ( 1380): doRemovePackageData com.example.hello
,I/ActivityManager( 1019): Killing 3299:com.android.calendar/u0a7 (adj 15): empty #9
,D/gH_CompatibleDatabase( 1380): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/AndroidRuntime( 3470): Shutting down VM
D/dalvikvm( 3470): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+1ms, total 3ms
,D/Documents( 3521): Loading roots for com.android.providers.downloads.documents
,I/ActivityManager( 1019): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=3540 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/ActivityManager( 1019): Killing 3323:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Killing 3243:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 3540): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f06688, skipping init
I/openssl ( 3540): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3540): Crypto mode 0 already enabled
D/Documents( 3521): Loading roots for com.android.externalstorage.documents
,I/ActivityManager( 1019): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3556 uid=10020 gids={50020, 1028, 1015, 1023}
,I/ActivityManager( 1019): Killing 3072:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/ExternalStorage( 3556): After updating volumes, found 1 active roots
,D/Documents( 3521): Updating roots due to change at content://com.android.externalstorage.documents/root
,D/Documents( 3521): Loading roots for com.android.providers.media.documents
,D/Documents( 3521): Loading roots for com.google.android.apps.docs.storage
,D/Documents( 3521): Update found 7 roots in 188ms
D/Documents( 3521): Used cached roots for com.android.providers.downloads.documents
,D/Documents( 3521): Loading roots for com.android.externalstorage.documents
D/Documents( 3521): Used cached roots for com.android.providers.media.documents
D/Documents( 3521): Used cached roots for com.google.android.apps.docs.storage
,D/Documents( 3521): Update found 7 roots in 6ms

```
