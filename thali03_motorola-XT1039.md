#### Test 5038801932cd575_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MMApiBackOffService( 1537): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1537): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1537): MMApiBackOffService told us it's okay to retry the waiting requests: 2
D/MMApiWebService( 1537): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1537): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1537): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1537): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/MMApiWebService( 1537): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1537): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1537): ProvisionWS.Response.setError: error RadioDownError
D/Checkin ( 1537): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1537): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
D/Checkin ( 1537): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1537): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1537): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1537): publish the event [tag = MOT_CCE event name = LOG]
D/Checkin ( 1537): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1537): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 60000
D/Checkin ( 1537): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1537): MMApiWebService told us not to continue at the moment with this request: devices.json
D/Checkin ( 1537): publish the event [tag = MOT_CCE event name = LOG]
D/AndroidRuntime( 3431): 
D/AndroidRuntime( 3431): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3431): CheckJNI is OFF
D/dalvikvm( 3431): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3431): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3431): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3431): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3431): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3431): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3431): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3431): failed to load memtrack module: -2
D/AndroidRuntime( 3431): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1004): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3431
W/WindowManager( 1004): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1004): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3447 uid=10406 gids={50406, 3003, 3001, 3002}
D/AndroidRuntime( 3431): Shutting down VM
D/dalvikvm( 3431): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3447): Binding Chromium to main looper Looper (main, tid 1) {41f1f9c0}
I/LibraryLoader( 3447): Expected native library version number "",actual native library version number ""
I/chromium( 3447): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3447): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1004): Message: 20
D/BluetoothManagerService( 1004): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@420c9e90:true
D/BluetoothAdapter( 3447): 1106460544: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3447): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3447): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3447): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3447): Local Branch: 
I/Adreno-EGL( 3447): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3447): Local Patches: NONE
I/Adreno-EGL( 3447): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3447): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 3447): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3447): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3447): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3447): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3447): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3447): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3447): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3447): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3447): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3447): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 3447): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3447): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3447): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3447): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3447): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3447): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3447): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 3447): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 3447): CordovaWebView is running on device made by: motorola
,I/MDMCTBK (  272): NetlinkHandler, power_supply subsys
I/MDMCTBK (  272): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  272): checkDefaultInst, current pid is = 272
I/MDMCTBK (  272): checkDefaultInst, pid match
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  272): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  272): MdmCutbackHndler,Could not open ''
,D/OpenGLRenderer( 3447): Enabling debug mode 0
,W/AwContents( 3447): nativeOnDraw failed; clearing to background color.
,W/AwContents( 3447): nativeOnDraw failed; clearing to background color.
,I/LaunchCheckinHandler( 1004): Displayed com.example.hello/.MainActivity,cp,ca,365
I/ActivityManager( 1004): Displayed com.example.hello/.MainActivity: +341ms (total +365ms)
W/IInputConnectionWrapper( 3447): showStatusIcon on inactive InputConnection
,I/chromium( 3447): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 3447): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/JsMessageQueue( 3447): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3447): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x41f23e38
,D/dalvikvm( 3447): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x41f23e38
D/jxcore_app_log( 3447): JniHelper::setJavaVM(0x4156dfa8), pthread_self() = 1609234592
,D/JX-Cordova( 3447): jxcore cordova android initializing
,W/jxcore-log( 3447): Initializing JXcore engine
,W/jxcore-log( 3447): JXcore engine is ready
,W/jxcore-log( 3447): Starting JXcore engine
,W/jxcore-log( 3447): Platform android
W/jxcore-log( 3447): 
,W/jxcore-log( 3447): Process ARCH arm
W/jxcore-log( 3447): 
,I/jxcore-log( 3447): JXcore Cordova bridge is ready!
I/jxcore-log( 3447): 
,W/jxcore-log( 3447): JXcore engine is started
,E/jxcore-log( 3447): >> motorola-XT1039
E/jxcore-log( 3447): 
,I/jxcore-log( 3447): Total memory 893136896
I/jxcore-log( 3447): 
I/jxcore-log( 3447): Free memory 30334976
I/jxcore-log( 3447): 
I/jxcore-log( 3447): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3447): 
,I/jxcore-log( 3447): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3447): 
,I/jxcore-log( 3447): userPath [ 'www' ]
I/jxcore-log( 3447): 
,I/jxcore-log( 3447): Size 720 1184
I/jxcore-log( 3447): 
,I/jxcore-log( 3447): Screen Brightness 10
I/jxcore-log( 3447): 
,E/jxcore-log( 3447): Dummy Error Log.
E/jxcore-log( 3447): 
,I/jxcore-log( 3447): getBuffer is called!!!!
I/jxcore-log( 3447): 
,D/BluetoothManagerService( 1004): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1004): Disable(): Service is not Connected Or Bluetooth is not enabled
,D/WifiService( 1004): New client listening to asynchronous messages
,D/WifiService( 1004): setWifiEnabled: false pid=3447, uid=10406
,E/WifiService( 1004): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3447): ****TEST TOOK:  5052  ms ****
I/jxcore-log( 3447): 
I/jxcore-log( 3447): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3447): 
,D/AndroidRuntime( 3519): 
D/AndroidRuntime( 3519): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3519): CheckJNI is OFF
,D/dalvikvm( 3519): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 3519): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3519): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3519): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 3519): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 3519): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,E/memtrack( 3519): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 3519): failed to load memtrack module: -2
,D/AndroidRuntime( 3519): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1004): Force stopping com.example.hello appid=10406 user=-1: uninstall pkg
,I/ActivityManager( 1004): Killing 3447:com.example.hello/u0a406 (adj 0): stop com.example.hello
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1004):   Force finishing activity ActivityRecord{4289e010 u0 com.example.hello/.MainActivity t3}
,I/WindowState( 1004): WIN DEATH: Window{42119240 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService( 1004): Client connection lost with reason: 4
,W/PackageSettings( 1004): Skipping PackageSetting{421df588 com.test.thalitest/10403} due to missing metadata
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager( 1004): Force stopping com.example.hello appid=10406 user=0: pkg removed
,I/InputReader( 1004): Reconfiguring input devices.  changes=0x00000010
,I/LatinIME:LogUtils( 1183): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/LatinIME:LogUtils( 1183): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/PackageManager( 1004): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1004):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1004):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1004):   Scheme: "sms"
,W/GeofencerStateMachine( 1201): Ignoring removeGeofence because network location is disabled.
,D/VoicemailCleanupService( 3035): Cleaning up data for package: com.example.hello
,D/dalvikvm( 2178): GC_EXPLICIT freed 2733K, 42% free 10045K/17224K, paused 2ms+3ms, total 110ms
I/OtaApp  ( 1537): [info] > Updatetime from metadata: 10
,D/Checkin ( 1537): publish the event [tag = MOT_OTA event name = LOG]
,D/dalvikvm( 1295): GC_EXPLICIT freed 2792K, 33% free 11592K/17224K, paused 2ms+4ms, total 110ms
,D/dalvikvm( 2145): GC_EXPLICIT freed 4672K, 45% free 9634K/17224K, paused 2ms+5ms, total 43ms
,I/PackageManager( 1004): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1004):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1004):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1004):   Scheme: "smsto"
I/LatinIME:LogUtils( 1183): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1448315245
,D/dalvikvm( 1004): GC_EXPLICIT freed 1175K, 15% free 17835K/20760K, paused 4ms+40ms, total 140ms
,I/Launcher( 1295): Deferring update until onResume
,D/OtaApp  ( 1537): [debug] > cancelling the previous pending intent set for install later
I/OtaApp  ( 1537): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1537): publish the event [tag = MOT_OTA event name = LOG]
,I/PackageManager( 1004): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1004):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1004):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1004):   Scheme: "mms"
,I/PackageManager( 1004): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1004):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1004):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1004):   Scheme: "mmsto"
,D/OtaApp  ( 1537): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/PackageManager( 1004): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1004):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1004):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1004):   Scheme: "sms"
,D/OtaApp  ( 1537): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,W/InputMethodManagerService( 1004): Got RemoteException sending setActive(false) notification to pid 3447 uid 10406
,I/PackageManager( 1004): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1004):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1004):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1004):   Scheme: "smsto"
W/Binder  ( 1183): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1183): java.lang.NullPointerException
W/Binder  ( 1183): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1183): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1183): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1183): 	at dalvik.system.NativeStart.run(Native Method)
I/InternalIcingCorporaPro( 2178): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/Launcher( 1295): Deferring update until onResume
,I/LatinIME:LogUtils( 1183): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1448315245
,I/PackageManager( 1004): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1004):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1004):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1004):   Scheme: "mms"
,I/PackageManager( 1004): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1004):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1004):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1004):   Scheme: "mmsto"
,D/BackupManagerService( 1004): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,V/BackupManagerService( 1004): removePackageParticipantsLocked: uid=10406 #1
,I/ActivityManager( 1004): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3553 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,W/ContextImpl( 3553): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
,D/dalvikvm( 1004): GC_EXPLICIT freed 665K, 15% free 17725K/20760K, paused 4ms+11ms, total 165ms
,D/PackageBroadcastService( 1379): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1379): Clearing selected account for com.example.hello
,I/LocationSettingsChecker( 1379): Removing dialog suppression flag for package com.example.hello
,D/ChimeraCfgMgr( 1379): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1379): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1379): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1379): Module APK com.google.android.play.games already loaded
,I/InternalIcingCorporaPro( 2178): UpdateCorporaTask done [took 130 ms] updated apps [took 130 ms] 
,E/NetworkScheduler.SchedulerReceiver( 1323): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1323): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 1379): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1379): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1379): 0 metrics were deleted when clearing package com.example.hello.
,D/gH_CompatibleDatabase( 1379): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,I/PeopleContactsSync( 1379): CP2 sync disabled
,I/Icing   ( 1379): doRemovePackageData com.example.hello
,D/gH_CompatibleDatabase( 1379): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
I/dalvikvm( 3117): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3117): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 3117): VFY: replacing opcode 0x6e at 0x0013
,D/gH_CompatibleDatabase( 1379): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1379): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1379): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1379): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1379): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1379): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1379): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1379): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager( 1004): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3577 uid=10058 gids={50058}
,D/AndroidRuntime( 3519): Shutting down VM
,D/dalvikvm( 3519): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+1ms, total 3ms
,I/ActivityManager( 1004): Killing 3248:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/dalvikvm(  275): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 3ms+2ms, total 23ms
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 18ms
,D/Documents( 3577): Loading roots for com.android.providers.downloads.documents
,D/dalvikvm(  275): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 17ms
,I/ActivityManager( 1004): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=3590 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/ActivityManager( 1004): Killing 3326:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1004): Killing 3288:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Documents( 3577): Loading roots for com.android.externalstorage.documents
,D/dalvikvm( 3590): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f1e548, skipping init
I/openssl ( 3590): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3590): Crypto mode 0 already enabled
I/ActivityManager( 1004): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3605 uid=10020 gids={50020, 1028, 1015, 1023}
,I/ActivityManager( 1004): Killing 3035:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/ExternalStorage( 3605): After updating volumes, found 1 active roots
,D/Documents( 3577): Updating roots due to change at content://com.android.externalstorage.documents/root
,D/Documents( 3577): Loading roots for com.android.providers.media.documents
,D/Documents( 3577): Loading roots for com.google.android.apps.docs.storage
,D/Documents( 3577): Update found 7 roots in 187ms
D/Documents( 3577): Used cached roots for com.android.providers.downloads.documents
,D/Documents( 3577): Loading roots for com.android.externalstorage.documents
D/Documents( 3577): Used cached roots for com.android.providers.media.documents
D/Documents( 3577): Used cached roots for com.google.android.apps.docs.storage
,D/Documents( 3577): Update found 7 roots in 6ms
,E/MP-Decision( 1478): Error(-22) changing core 2 status to offline

```
