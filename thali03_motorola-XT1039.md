#### Test 50388019c82294c_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1015): sending alarm Alarm{42837cf8 type 2 android}
,D/ConnectivityService( 1015): Sampling interval elapsed, updating statistics ..
V/AlarmManager( 1015): sending alarm Alarm{42837dd0 type 3 android}
V/AlarmManager( 1015): sending alarm Alarm{42a92a58 type 2 com.google.android.gms}
V/AlarmManager( 1015): sending alarm Alarm{42837c28 type 0 com.android.vending}
D/ConnectivityService( 1015): Done.
D/ConnectivityService( 1015): Setting timer for 720seconds
--------- beginning of /dev/log/main
D/Finsky  ( 3133): [270] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 3133): [1] 5.onFinished: Installation state replication succeeded.
D/AndroidRuntime( 3406): 
D/AndroidRuntime( 3406): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3406): CheckJNI is OFF
D/dalvikvm( 3406): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3406): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3406): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3406): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3406): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3406): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3406): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3406): failed to load memtrack module: -2
D/AndroidRuntime( 3406): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1015): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3406
W/WindowManager( 1015): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1015): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3421 uid=10376 gids={50376, 3003, 3001, 3002}
D/AndroidRuntime( 3406): Shutting down VM
D/dalvikvm( 3406): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+0ms, total 3ms
W/ContextImpl( 1246): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1246): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3421): Binding Chromium to main looper Looper (main, tid 1) {41fe1bf0}
I/LibraryLoader( 3421): Expected native library version number "",actual native library version number ""
I/chromium( 3421): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3421): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1015): Message: 20
D/BluetoothManagerService( 1015): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@420fe1c0:true
D/BluetoothAdapter( 3421): 1107255264: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3421): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3421): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3421): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3421): Local Branch: 
I/Adreno-EGL( 3421): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3421): Local Patches: NONE
I/Adreno-EGL( 3421): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3421): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 3421): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3421): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3421): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3421): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3421): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3421): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3421): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3421): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3421): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3421): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3421): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3421): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3421): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3421): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3421): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3421): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3421): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 3421): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3421): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3421): Enabling debug mode 0
,W/AwContents( 3421): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3421): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1015): Displayed com.example.hello/.MainActivity,cp,ca,372
I/ActivityManager( 1015): Displayed com.example.hello/.MainActivity: +347ms (total +372ms)
,I/chromium( 3421): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 3421): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 3421): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/dalvikvm( 3421): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x41fe5e98
,D/dalvikvm( 3421): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x41fe5e98
D/jxcore_app_log( 3421): JniHelper::setJavaVM(0x4162efa8), pthread_self() = 1610009976
,D/JX-Cordova( 3421): jxcore cordova android initializing
,W/jxcore-log( 3421): Initializing JXcore engine
,W/jxcore-log( 3421): JXcore engine is ready
,W/jxcore-log( 3421): Starting JXcore engine
,W/jxcore-log( 3421): Platform android
W/jxcore-log( 3421): 
,W/jxcore-log( 3421): Process ARCH arm
W/jxcore-log( 3421): 
,I/jxcore-log( 3421): JXcore Cordova bridge is ready!
I/jxcore-log( 3421): 
,W/jxcore-log( 3421): JXcore engine is started
,E/jxcore-log( 3421): >> motorola-XT1039
E/jxcore-log( 3421): 
,I/jxcore-log( 3421): Total memory 893136896
I/jxcore-log( 3421): 
I/jxcore-log( 3421): Free memory 40542208
I/jxcore-log( 3421): 
,I/jxcore-log( 3421): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3421): 
,I/jxcore-log( 3421): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3421): 
,I/jxcore-log( 3421): userPath [ 'www' ]
I/jxcore-log( 3421): 
,I/jxcore-log( 3421): Size 720 1184
I/jxcore-log( 3421): 
,I/jxcore-log( 3421): Screen Brightness 10
I/jxcore-log( 3421): 
,E/jxcore-log( 3421): Dummy Error Log.
E/jxcore-log( 3421): 
,W/ContextImpl( 1246): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2434 
,I/jxcore-log( 3421): getBuffer is called!!!!
I/jxcore-log( 3421): 
,I/MMApiBackOffService( 1536): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1536): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1536): MMApiBackOffService told us it's okay to retry the waiting requests: 2
,D/MMApiWebService( 1536): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1536): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1536): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1536): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiWebService( 1536): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1536): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1536): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1536): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiBackOffService( 1536): connectStatus(): app: MMAPIWebServiceRequest backing off: 30000 ms until next web service attempt
,D/Checkin ( 1536): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1536): MMApiWebService told us not to continue at the moment with this request: devices.json
,I/MMApiWebService( 1536): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1536): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1536): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1536): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 30000
,D/Checkin ( 1536): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1536): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1536): publish the event [tag = MOT_CCE event name = LOG]
,D/BluetoothManagerService( 1015): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1015): Disable(): Service is not Connected Or Bluetooth is not enabled
,D/WifiService( 1015): New client listening to asynchronous messages
,D/WifiService( 1015): setWifiEnabled: false pid=3421, uid=10376
,E/WifiService( 1015): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3421): ****TEST TOOK:  5048  ms ****
I/jxcore-log( 3421): 
I/jxcore-log( 3421): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3421): 
,D/AndroidRuntime( 3487): 
D/AndroidRuntime( 3487): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3487): CheckJNI is OFF
,D/dalvikvm( 3487): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 3487): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3487): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3487): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 3487): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 3487): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,E/memtrack( 3487): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 3487): failed to load memtrack module: -2
,D/AndroidRuntime( 3487): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1015): Force stopping com.example.hello appid=10376 user=-1: uninstall pkg
,I/ActivityManager( 1015): Killing 3421:com.example.hello/u0a376 (adj 0): stop com.example.hello
,I/ActivityManager( 1015):   Force finishing activity ActivityRecord{428e9740 u0 com.example.hello/.MainActivity t3}
,W/ContextImpl( 1246): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/WindowState( 1015): WIN DEATH: Window{421c7970 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService( 1015): Client connection lost with reason: 4
,W/PackageSettings( 1015): Skipping PackageSetting{422de540 com.test.thalitest/10370} due to missing metadata
,W/ContextImpl( 1246): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1246): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager( 1015): Force stopping com.example.hello appid=10376 user=0: pkg removed
,I/InputReader( 1015): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/LatinIME:LogUtils( 1182): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "sms"
I/LatinIME:LogUtils( 1182): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "smsto"
D/dalvikvm( 1298): GC_EXPLICIT freed 2692K, 33% free 11589K/17224K, paused 1ms+4ms, total 86ms
,I/Launcher( 1298): Deferring update until onResume
,D/dalvikvm( 2160): GC_EXPLICIT freed 4671K, 45% free 9623K/17224K, paused 7ms+6ms, total 65ms
,I/LatinIME:LogUtils( 1182): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1447782220
,I/OtaApp  ( 1536): [info] > Updatetime from metadata: 10
D/Checkin ( 1536): publish the event [tag = MOT_OTA event name = LOG]
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "mms"
W/GeofencerStateMachine( 1198): Ignoring removeGeofence because network location is disabled.
D/dalvikvm( 2194): GC_EXPLICIT freed 2171K, 44% free 9767K/17224K, paused 2ms+4ms, total 130ms
,D/VoicemailCleanupService( 3058): Cleaning up data for package: com.example.hello
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "mmsto"
,D/OtaApp  ( 1536): [debug] > cancelling the previous pending intent set for install later
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/OtaApp  ( 1536): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "sms"
D/Checkin ( 1536): publish the event [tag = MOT_OTA event name = LOG]
D/dalvikvm( 1015): GC_EXPLICIT freed 2232K, 15% free 17837K/20876K, paused 4ms+11ms, total 141ms
D/dalvikvm( 1015): WAIT_FOR_CONCURRENT_GC blocked 105ms
I/Launcher( 1298): Deferring update until onResume
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "smsto"
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "mms"
,I/PackageManager( 1015): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1015):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1015):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1015):   Scheme: "mmsto"
,I/InternalIcingCorporaPro( 2194): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/OtaApp  ( 1536): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/ActivityManager( 1015): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3517 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
I/LatinIME:LogUtils( 1182): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1447782221
,D/OtaApp  ( 1536): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/dalvikvm(  275): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+3ms, total 26ms
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 20ms
,W/InputMethodManagerService( 1015): Got RemoteException sending setActive(false) notification to pid 3421 uid 10376
W/Binder  ( 1182): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1182): java.lang.NullPointerException
W/Binder  ( 1182): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1182): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1182): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1182): 	at dalvik.system.NativeStart.run(Native Method)
,W/ContextImpl( 3517): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
D/dalvikvm(  275): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 19ms
,I/InternalIcingCorporaPro( 2194): UpdateCorporaTask done [took 107 ms] updated apps [took 107 ms] 
I/dalvikvm( 3133): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3133): VFY: unable to resolve virtual method 338: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3133): VFY: replacing opcode 0x6e at 0x0013
,D/PackageBroadcastService( 1365): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1365): Clearing selected account for com.example.hello
,D/ChimeraCfgMgr( 1365): Loading module com.google.android.gms.games from APK com.google.android.gms
,I/LocationSettingsChecker( 1365): Removing dialog suppression flag for package com.example.hello
D/BackupManagerService( 1015): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,V/BackupManagerService( 1015): removePackageParticipantsLocked: uid=10376 #1
E/NetworkScheduler.SchedulerReceiver( 1331): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1331): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 1365): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1365): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1365): 0 metrics were deleted when clearing package com.example.hello.
,D/gH_CompatibleDatabase( 1365): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,I/ActivityManager( 1015): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3539 uid=10058 gids={50058}
D/gH_CompatibleDatabase( 1365): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1365): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1365): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,I/PeopleContactsSync( 1365): CP2 sync disabled
,D/gH_CompatibleDatabase( 1365): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1365): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1365): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1365): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1365): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1365): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/Icing   ( 1365): doRemovePackageData com.example.hello
,I/ActivityManager( 1015): Killing 3293:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1246): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Documents( 3539): Loading roots for com.android.providers.downloads.documents
,D/dalvikvm( 1015): GC_EXPLICIT freed 646K, 15% free 17748K/20876K, paused 3ms+13ms, total 256ms
,I/ActivityManager( 1015): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=3554 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/ActivityManager( 1015): Killing 3325:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1246): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1015): Killing 3251:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1246): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/AndroidRuntime( 3487): Shutting down VM
,D/dalvikvm( 3487): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms
,D/dalvikvm( 3554): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41fe03e0, skipping init
I/openssl ( 3554): Crypto mode not selected, openssl will run on its regular mode.
,I/openssl ( 3554): Crypto mode 0 already enabled
D/Documents( 3539): Loading roots for com.android.externalstorage.documents
,I/ActivityManager( 1015): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3571 uid=10020 gids={50020, 1028, 1015, 1023}
,I/ActivityManager( 1015): Killing 3058:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1246): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/ExternalStorage( 3571): After updating volumes, found 1 active roots
,D/Documents( 3539): Updating roots due to change at content://com.android.externalstorage.documents/root
,D/Documents( 3539): Loading roots for com.android.providers.media.documents
,D/Documents( 3539): Loading roots for com.google.android.apps.docs.storage
,D/Documents( 3539): Update found 7 roots in 206ms
D/Documents( 3539): Used cached roots for com.android.providers.downloads.documents
,D/Documents( 3539): Loading roots for com.android.externalstorage.documents
D/Documents( 3539): Used cached roots for com.android.providers.media.documents
D/Documents( 3539): Used cached roots for com.google.android.apps.docs.storage
,D/Documents( 3539): Update found 7 roots in 7ms

```
