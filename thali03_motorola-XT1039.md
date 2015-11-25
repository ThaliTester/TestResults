#### Test 503880194bce128_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main,
I/MMApiBackOffService( 1540): MMAPIWebServiceRequest backOff fired!
D/Checkin ( 1540): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1540): MMApiBackOffService told us it's okay to retry the waiting requests: 2
D/MMApiWebService( 1540): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1540): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1540): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1540): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1540): ProvisionWS.Response.setError: error RadioDownError
D/MMApiWebService( 1540): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1540): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 1540): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1540): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
D/Checkin ( 1540): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1540): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1540): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1540): MMApiWebService told us not to continue at the moment with this request: 
D/Checkin ( 1540): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1540): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 60000
D/Checkin ( 1540): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1540): MMApiWebService told us not to continue at the moment with this request: devices.json
D/Checkin ( 1540): publish the event [tag = MOT_CCE event name = LOG]
D/AndroidRuntime( 3358): 
D/AndroidRuntime( 3358): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3358): CheckJNI is OFF
D/dalvikvm( 3358): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3358): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3358): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3358): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3358): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3358): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3358): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3358): failed to load memtrack module: -2
D/AndroidRuntime( 3358): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1021): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3358
W/WindowManager( 1021): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1021): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3374 uid=10413 gids={50413, 3003, 3001, 3002}
D/AndroidRuntime( 3358): Shutting down VM
D/dalvikvm( 3358): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3374): Binding Chromium to main looper Looper (main, tid 1) {4215fd58}
I/LibraryLoader( 3374): Expected native library version number "",actual native library version number ""
I/chromium( 3374): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3374): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1021): Message: 20
D/BluetoothManagerService( 1021): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@429973b0:true
D/BluetoothAdapter( 3374): 1108820296: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3374): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3374): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3374): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3374): Local Branch: 
I/Adreno-EGL( 3374): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3374): Local Patches: NONE
I/Adreno-EGL( 3374): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3374): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 3374): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3374): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3374): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3374): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3374): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3374): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3374): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3374): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3374): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3374): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 3374): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3374): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3374): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3374): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3374): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3374): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3374): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 3374): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 3374): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3374): Enabling debug mode 0
,W/AwContents( 3374): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3374): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1021): Displayed com.example.hello/.MainActivity,cp,ca,355
I/ActivityManager( 1021): Displayed com.example.hello/.MainActivity: +330ms (total +355ms)
,I/chromium( 3374): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 3374): Set native->JS mode to OnlineEventsBridgeMode
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,E/AndroidProtocolHandler( 3374): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/dalvikvm( 3374): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x42164000
,D/dalvikvm( 3374): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x42164000
,D/jxcore_app_log( 3374): JniHelper::setJavaVM(0x4187af78), pthread_self() = 1609310248
,D/JX-Cordova( 3374): jxcore cordova android initializing
,W/jxcore-log( 3374): Initializing JXcore engine
,W/jxcore-log( 3374): JXcore engine is ready
,W/jxcore-log( 3374): Starting JXcore engine
,W/jxcore-log( 3374): Platform android
W/jxcore-log( 3374): 
,W/jxcore-log( 3374): Process ARCH arm
W/jxcore-log( 3374): 
,I/jxcore-log( 3374): JXcore Cordova bridge is ready!
I/jxcore-log( 3374): 
,W/jxcore-log( 3374): JXcore engine is started
,E/jxcore-log( 3374): >> motorola-XT1039
E/jxcore-log( 3374): 
,I/jxcore-log( 3374): Total memory 893136896
I/jxcore-log( 3374): 
I/jxcore-log( 3374): Free memory 33017856
I/jxcore-log( 3374): 
I/jxcore-log( 3374): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3374): 
,I/jxcore-log( 3374): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3374): 
,I/jxcore-log( 3374): userPath [ 'www' ]
I/jxcore-log( 3374): 
,I/jxcore-log( 3374): Size 720 1184
I/jxcore-log( 3374): 
,I/jxcore-log( 3374): Screen Brightness 10
I/jxcore-log( 3374): 
,E/jxcore-log( 3374): Dummy Error Log.
E/jxcore-log( 3374): 
,I/jxcore-log( 3374): getBuffer is called!!!!
I/jxcore-log( 3374): 
,D/BluetoothManagerService( 1021): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1021): Disable(): Service is not Connected Or Bluetooth is not enabled
,D/WifiService( 1021): New client listening to asynchronous messages
,D/WifiService( 1021): setWifiEnabled: false pid=3374, uid=10413
,E/WifiService( 1021): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3374): ****TEST TOOK:  5050  ms ****
I/jxcore-log( 3374): 
I/jxcore-log( 3374): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3374): 
,D/AndroidRuntime( 3429): 
D/AndroidRuntime( 3429): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3429): CheckJNI is OFF
,D/dalvikvm( 3429): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 3429): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3429): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3429): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3429): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 3429): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,E/memtrack( 3429): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 3429): failed to load memtrack module: -2
,D/AndroidRuntime( 3429): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1021): Force stopping com.example.hello appid=10413 user=-1: uninstall pkg
,I/ActivityManager( 1021): Killing 3374:com.example.hello/u0a413 (adj 0): stop com.example.hello
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1021):   Force finishing activity ActivityRecord{42b3ff10 u0 com.example.hello/.MainActivity t3}
,I/WindowState( 1021): WIN DEATH: Window{42bef2e0 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService( 1021): Client connection lost with reason: 4
,W/PackageSettings( 1021): Skipping PackageSetting{42421610 com.test.thalitest/10411} due to missing metadata
,I/ActivityManager( 1021): Force stopping com.example.hello appid=10413 user=0: pkg removed
,D/dalvikvm( 2095): GC_EXPLICIT freed 4859K, 45% free 9630K/17224K, paused 2ms+5ms, total 52ms
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/InputReader( 1021): Reconfiguring input devices.  changes=0x00000010
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/OtaApp  ( 1540): [info] > Updatetime from metadata: 10
D/Checkin ( 1540): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1540): [debug] > cancelling the previous pending intent set for install later
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "sms"
I/LatinIME:LogUtils( 1193): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1193): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1193): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1448461076
I/OtaApp  ( 1540): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1540): publish the event [tag = MOT_OTA event name = LOG]
,W/GeofencerStateMachine( 1208): Ignoring removeGeofence because network location is disabled.
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "smsto"
,D/VoicemailCleanupService( 2964): Cleaning up data for package: com.example.hello
,D/dalvikvm( 2127): GC_EXPLICIT freed 3655K, 42% free 10098K/17224K, paused 2ms+4ms, total 138ms
,D/dalvikvm( 1021): GC_EXPLICIT freed 1991K, 12% free 17703K/20068K, paused 3ms+9ms, total 119ms
,D/dalvikvm( 1300): GC_EXPLICIT freed 2792K, 33% free 11592K/17224K, paused 2ms+6ms, total 156ms
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mms"
,I/Launcher( 1300): Deferring update until onResume
,D/OtaApp  ( 1540): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mmsto"
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "sms"
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "smsto"
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mms"
,I/Launcher( 1300): Deferring update until onResume
,I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mmsto"
,I/InternalIcingCorporaPro( 2127): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/LatinIME:LogUtils( 1193): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1448461076
,I/ActivityManager( 1021): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3462 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
W/InputMethodManagerService( 1021): Got RemoteException sending setActive(false) notification to pid 3374 uid 10413
W/Binder  ( 1193): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1193): java.lang.NullPointerException
W/Binder  ( 1193): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1193): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1193): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1193): 	at dalvik.system.NativeStart.run(Native Method)
D/OtaApp  ( 1540): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
W/ContextImpl( 3462): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
D/BackupManagerService( 1021): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
V/BackupManagerService( 1021): removePackageParticipantsLocked: uid=10413 #1
,D/PackageBroadcastService( 1373): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1373): Clearing selected account for com.example.hello
D/ChimeraCfgMgr( 1373): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1373): Module APK com.google.android.play.games already loaded
,I/InternalIcingCorporaPro( 2127): UpdateCorporaTask done [took 89 ms] updated apps [took 89 ms] 
,I/LocationSettingsChecker( 1373): Removing dialog suppression flag for package com.example.hello
,D/ChimeraCfgMgr( 1373): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1373): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1335): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1335): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 1373): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1373): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1373): 0 metrics were deleted when clearing package com.example.hello.
,D/gH_CompatibleDatabase( 1373): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1373): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1373): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1373): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1373): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1373): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1373): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1373): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1373): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1373): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/PeopleContactsSync( 1373): CP2 sync disabled
,I/Icing   ( 1373): doRemovePackageData com.example.hello
I/dalvikvm( 3045): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3045): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3045): VFY: replacing opcode 0x6e at 0x0013
,D/dalvikvm( 1021): GC_EXPLICIT freed 633K, 12% free 17696K/20068K, paused 5ms+24ms, total 227ms
,I/ActivityManager( 1021): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3485 uid=10058 gids={50058}
,I/ActivityManager( 1021): Killing 3094:com.android.providers.calendar/u0a8 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  277): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+3ms, total 22ms
,D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 18ms
,D/Documents( 3485): Loading roots for com.android.providers.downloads.documents
,D/AndroidRuntime( 3429): Shutting down VM
,D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 3429): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
I/ActivityManager( 1021): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=3499 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
I/ActivityManager( 1021): Killing 3257:com.google.android.partnersetup/u0a25 (adj 15): empty #9
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1021): Killing 3228:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Documents( 3485): Loading roots for com.android.externalstorage.documents
,D/dalvikvm( 3499): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x4215e570, skipping init
I/openssl ( 3499): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3499): Crypto mode 0 already enabled
,I/ActivityManager( 1021): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3516 uid=10020 gids={50020, 1028, 1015, 1023}
,I/ActivityManager( 1021): Killing 2964:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/ExternalStorage( 3516): After updating volumes, found 1 active roots
,D/Documents( 3485): Updating roots due to change at content://com.android.externalstorage.documents/root
,D/Documents( 3485): Loading roots for com.android.providers.media.documents
,D/Documents( 3485): Loading roots for com.google.android.apps.docs.storage
,D/Documents( 3485): Update found 7 roots in 200ms
D/Documents( 3485): Used cached roots for com.android.providers.downloads.documents
,D/Documents( 3485): Loading roots for com.android.externalstorage.documents
D/Documents( 3485): Used cached roots for com.android.providers.media.documents
D/Documents( 3485): Used cached roots for com.google.android.apps.docs.storage
,D/Documents( 3485): Update found 7 roots in 6ms

```
