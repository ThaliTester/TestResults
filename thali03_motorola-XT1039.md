#### Test 503880196b4ec73_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
,I/MMApiBackOffService( 1542): MMAPIWebServiceRequest backOff fired!
D/Checkin ( 1542): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1542): MMApiBackOffService told us it's okay to retry the waiting requests: 2
D/MMApiWebService( 1542): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1542): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1542): doRequest(): polling manager says we're not connected, returning with an error: 
D/MMApiWebService( 1542): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1542): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1542): ProvisionWS.Response.setError: error RadioDownError
I/MMApiWebService( 1542): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 1542): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1542): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
D/Checkin ( 1542): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1542): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1542): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1542): publish the event [tag = MOT_CCE event name = LOG]
D/Checkin ( 1542): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1542): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 60000
D/Checkin ( 1542): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1542): MMApiWebService told us not to continue at the moment with this request: devices.json
D/Checkin ( 1542): publish the event [tag = MOT_CCE event name = LOG]
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 3423): 
D/AndroidRuntime( 3423): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3423): CheckJNI is OFF
D/dalvikvm( 3423): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3423): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3423): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3423): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3423): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3423): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3423): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3423): failed to load memtrack module: -2
D/AndroidRuntime( 3423): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1017): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3423
W/WindowManager( 1017): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1017): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3439 uid=10405 gids={50405, 3003, 3001, 3002}
D/AndroidRuntime( 3423): Shutting down VM
D/dalvikvm( 3423): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+0ms, total 3ms
W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3439): Binding Chromium to main looper Looper (main, tid 1) {41ffeb68}
I/LibraryLoader( 3439): Expected native library version number "",actual native library version number ""
I/chromium( 3439): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3439): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1017): Message: 20
D/BluetoothManagerService( 1017): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42875ab0:true
D/BluetoothAdapter( 3439): 1107373912: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3439): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3439): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3439): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3439): Local Branch: 
I/Adreno-EGL( 3439): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3439): Local Patches: NONE
I/Adreno-EGL( 3439): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3439): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 3439): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3439): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3439): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3439): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3439): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3439): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3439): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3439): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3439): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3439): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 3439): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3439): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3439): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3439): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3439): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3439): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3439): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 3439): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3439): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3439): Enabling debug mode 0
,W/AwContents( 3439): nativeOnDraw failed; clearing to background color.
,W/AwContents( 3439): nativeOnDraw failed; clearing to background color.
,I/LaunchCheckinHandler( 1017): Displayed com.example.hello/.MainActivity,cp,ca,377
I/ActivityManager( 1017): Displayed com.example.hello/.MainActivity: +350ms (total +377ms)
W/IInputConnectionWrapper( 3439): showStatusIcon on inactive InputConnection
,I/chromium( 3439): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 3439): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/JsMessageQueue( 3439): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3439): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x42002e10
,D/dalvikvm( 3439): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x42002e10
D/jxcore_app_log( 3439): JniHelper::setJavaVM(0x4164bfa8), pthread_self() = 1610888872
,D/JX-Cordova( 3439): jxcore cordova android initializing
,W/jxcore-log( 3439): Initializing JXcore engine
,W/jxcore-log( 3439): JXcore engine is ready
,W/jxcore-log( 3439): Starting JXcore engine
,W/jxcore-log( 3439): Platform android
W/jxcore-log( 3439): 
,W/jxcore-log( 3439): Process ARCH arm
W/jxcore-log( 3439): 
,I/jxcore-log( 3439): JXcore Cordova bridge is ready!
I/jxcore-log( 3439): 
,W/jxcore-log( 3439): JXcore engine is started
,E/jxcore-log( 3439): >> motorola-XT1039
E/jxcore-log( 3439): 
,I/jxcore-log( 3439): Total memory 893136896
I/jxcore-log( 3439): 
,I/jxcore-log( 3439): Free memory 31277056
I/jxcore-log( 3439): 
,I/jxcore-log( 3439): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3439): 
,I/jxcore-log( 3439): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3439): 
,I/jxcore-log( 3439): userPath [ 'www' ]
I/jxcore-log( 3439): 
,I/jxcore-log( 3439): Size 720 1184
I/jxcore-log( 3439): 
,I/jxcore-log( 3439): Screen Brightness 10
I/jxcore-log( 3439): 
,E/jxcore-log( 3439): Dummy Error Log.
E/jxcore-log( 3439): 
,I/jxcore-log( 3439): getBuffer is called!!!!
I/jxcore-log( 3439): 
,D/BluetoothManagerService( 1017): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1017): Disable(): Service is not Connected Or Bluetooth is not enabled
,D/WifiService( 1017): New client listening to asynchronous messages
,D/WifiService( 1017): setWifiEnabled: false pid=3439, uid=10405
,E/WifiService( 1017): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3439): ****TEST TOOK:  5054  ms ****
I/jxcore-log( 3439): 
I/jxcore-log( 3439): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3439): 
,D/AndroidRuntime( 3504): 
D/AndroidRuntime( 3504): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3504): CheckJNI is OFF
,D/dalvikvm( 3504): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 3504): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 3504): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3504): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 3504): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 3504): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,V/AlarmManager( 1017): sending alarm Alarm{423c4670 type 3 android}
,E/memtrack( 3504): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 3504): failed to load memtrack module: -2
,D/AndroidRuntime( 3504): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1017): Force stopping com.example.hello appid=10405 user=-1: uninstall pkg
,I/ActivityManager( 1017): Killing 3439:com.example.hello/u0a405 (adj 0): stop com.example.hello
,W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1017):   Force finishing activity ActivityRecord{42192ed0 u0 com.example.hello/.MainActivity t3}
,I/WindowState( 1017): WIN DEATH: Window{4292fc10 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService( 1017): Client connection lost with reason: 4
,W/PackageSettings( 1017): Skipping PackageSetting{422bd450 com.test.thalitest/10403} due to missing metadata
,I/ActivityManager( 1017): Force stopping com.example.hello appid=10405 user=0: pkg removed
I/ActivityManager( 1017):   Force finishing activity ActivityRecord{42192ed0 u0 com.example.hello/.MainActivity t3 f}
,W/ActivityManager( 1017): Duplicate finish request for ActivityRecord{42192ed0 u0 com.example.hello/.MainActivity t3 f}
,W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/dalvikvm( 2132): GC_EXPLICIT freed 4701K, 45% free 9622K/17224K, paused 2ms+5ms, total 37ms
,D/dalvikvm( 2181): GC_EXPLICIT freed 2991K, 42% free 10048K/17224K, paused 5ms+4ms, total 47ms
,W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
,I/OtaApp  ( 1542): [info] > Updatetime from metadata: 10
,D/Checkin ( 1542): publish the event [tag = MOT_OTA event name = LOG]
,D/dalvikvm( 1300): GC_EXPLICIT freed 2791K, 33% free 11591K/17224K, paused 3ms+4ms, total 101ms
,I/LatinIME:LogUtils( 1184): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/LatinIME:LogUtils( 1184): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/Launcher( 1300): Deferring update until onResume
,D/OtaApp  ( 1542): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1542): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,W/GeofencerStateMachine( 1211): Ignoring removeGeofence because network location is disabled.
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "sms"
D/Checkin ( 1542): publish the event [tag = MOT_OTA event name = LOG]
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "smsto"
,D/dalvikvm( 1017): GC_EXPLICIT freed 1241K, 15% free 17763K/20772K, paused 11ms+9ms, total 119ms
,D/dalvikvm( 1017): WAIT_FOR_CONCURRENT_GC blocked 51ms
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mms"
I/Launcher( 1300): Deferring update until onResume
D/VoicemailCleanupService( 3028): Cleaning up data for package: com.example.hello
,I/LatinIME:LogUtils( 1184): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1448306520
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mmsto"
,D/OtaApp  ( 1542): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "sms"
,D/OtaApp  ( 1542): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,W/InputMethodManagerService( 1017): Got RemoteException sending setActive(false) notification to pid 3439 uid 10405
W/Binder  ( 1184): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1184): java.lang.NullPointerException
W/Binder  ( 1184): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1184): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1184): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1184): 	at dalvik.system.NativeStart.run(Native Method)
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "smsto"
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mms"
I/InternalIcingCorporaPro( 2181): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mmsto"
,I/ActivityManager( 1017): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3534 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,D/dalvikvm(  274): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+3ms, total 23ms
,D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,V/BackupManagerService( 1017): removePackageParticipantsLocked: uid=10405 #1
D/dalvikvm(  274): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 18ms
,I/LatinIME:LogUtils( 1184): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1448306520
,W/ContextImpl( 3534): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
D/dalvikvm(  274): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
,D/dalvikvm( 1017): GC_EXPLICIT freed 571K, 15% free 17705K/20772K, paused 4ms+14ms, total 194ms
,I/InternalIcingCorporaPro( 2181): UpdateCorporaTask done [took 117 ms] updated apps [took 117 ms] 
,D/PackageBroadcastService( 1378): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1378): Clearing selected account for com.example.hello
D/ChimeraCfgMgr( 1378): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1378): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1378): Removing dialog suppression flag for package com.example.hello
,D/ChimeraCfgMgr( 1378): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1378): Module APK com.google.android.play.games already loaded
,D/gH_CompatibleDatabase( 1378): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1378): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1378): 0 metrics were deleted when clearing package com.example.hello.
,D/gH_CompatibleDatabase( 1378): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
E/NetworkScheduler.SchedulerReceiver( 1332): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1332): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 1378): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1378): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1378): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1378): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1378): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1378): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1378): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1378): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1378): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/Icing   ( 1378): doRemovePackageData com.example.hello
,I/PeopleContactsSync( 1378): CP2 sync disabled
,I/dalvikvm( 3105): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3105): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3105): VFY: replacing opcode 0x6e at 0x0013
,I/ActivityManager( 1017): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3559 uid=10058 gids={50058}
,I/ActivityManager( 1017): Killing 3248:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/AndroidRuntime( 3504): Shutting down VM
D/dalvikvm( 3504): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+1ms, total 3ms
,D/Documents( 3559): Loading roots for com.android.providers.downloads.documents
,I/ActivityManager( 1017): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=3573 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/ActivityManager( 1017): Killing 3324:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1017): Killing 3295:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Documents( 3559): Loading roots for com.android.externalstorage.documents
,D/dalvikvm( 3573): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41ffd480, skipping init
I/openssl ( 3573): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3573): Crypto mode 0 already enabled
,I/ActivityManager( 1017): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3589 uid=10020 gids={50020, 1028, 1015, 1023}
,I/ActivityManager( 1017): Killing 3028:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/ExternalStorage( 3589): After updating volumes, found 1 active roots
,D/Documents( 3559): Updating roots due to change at content://com.android.externalstorage.documents/root
,D/Documents( 3559): Loading roots for com.android.providers.media.documents
,D/Documents( 3559): Loading roots for com.google.android.apps.docs.storage
,D/Documents( 3559): Update found 7 roots in 183ms
,D/Documents( 3559): Used cached roots for com.android.providers.downloads.documents
,D/Documents( 3559): Loading roots for com.android.externalstorage.documents
,D/Documents( 3559): Used cached roots for com.android.providers.media.documents
D/Documents( 3559): Used cached roots for com.google.android.apps.docs.storage
D/Documents( 3559): Update found 7 roots in 7ms

```
