#### Test 50388019385b4d9_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
,I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 3577): 
D/AndroidRuntime( 3577): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3577): CheckJNI is OFF
D/dalvikvm( 3577): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3577): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3577): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3577): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3577): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3577): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3577): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3577): failed to load memtrack module: -2
D/AndroidRuntime( 3577): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3577
W/WindowManager( 1019): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1019): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3593 uid=10478 gids={50478, 3003, 3001, 3002}
D/AndroidRuntime( 3577): Shutting down VM
D/dalvikvm( 3577): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 2ms
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/SFPerfTracer(  274):      triggers: (rate: 1:34) (compose: 0:4) (post: 0:1) (render: 0:5) (0:130 frames) (1:544)
D/SFPerfTracer(  274):        layers: (0:12) (FocusedStackFrame: 0:7)* (StatusBar: 0:213)* (NavigationBar: 0:41)* (com.android.systemui.ImageWallpaper: 0:7)* (com.android.launcher/com.android.launcher2.Launcher: 0:12)* (Starting com.motorola.ccc.ota: 0:34)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.InstallationActivity: 0:10)* (ElectronBeam: 0:27)* 
V/WebViewChromiumFactoryProvider( 3593): Binding Chromium to main looper Looper (main, tid 1) {41f039a8}
I/LibraryLoader( 3593): Expected native library version number "",actual native library version number ""
I/chromium( 3593): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3593): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@427f0d98:true
D/BluetoothAdapter( 3593): 1106346928: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3593): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3593): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3593): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3593): Local Branch: 
I/Adreno-EGL( 3593): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3593): Local Patches: NONE
I/Adreno-EGL( 3593): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3593): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 3593): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3593): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3593): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3593): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3593): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3593): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3593): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3593): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3593): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3593): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 3593): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3593): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3593): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3593): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3593): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3593): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3593): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 3593): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 3593): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3593): Enabling debug mode 0
,W/AwContents( 3593): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3593): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1019): Displayed com.example.hello/.MainActivity,cp,ca,350
I/ActivityManager( 1019): Displayed com.example.hello/.MainActivity: +321ms (total +350ms)
,I/chromium( 3593): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 3593): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/JsMessageQueue( 3593): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3593): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x41f08268
,D/dalvikvm( 3593): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x41f08268
D/jxcore_app_log( 3593): JniHelper::setJavaVM(0x41557fa8), pthread_self() = 1609902544
,D/JX-Cordova( 3593): jxcore cordova android initializing
,W/jxcore-log( 3593): Initializing JXcore engine
,W/jxcore-log( 3593): JXcore engine is ready
,W/jxcore-log( 3593): Starting JXcore engine
,W/jxcore-log( 3593): Platform android
W/jxcore-log( 3593): 
,W/jxcore-log( 3593): Process ARCH arm
W/jxcore-log( 3593): 
,I/jxcore-log( 3593): JXcore Cordova bridge is ready!
I/jxcore-log( 3593): 
,W/jxcore-log( 3593): JXcore engine is started
,E/jxcore-log( 3593): >> motorola-XT1039
E/jxcore-log( 3593): 
,I/jxcore-log( 3593): Total memory 893136896
I/jxcore-log( 3593): 
,I/jxcore-log( 3593): Free memory 36356096
I/jxcore-log( 3593): 
I/jxcore-log( 3593): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3593): 
,I/jxcore-log( 3593): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3593): 
,I/jxcore-log( 3593): userPath [ 'www' ]
I/jxcore-log( 3593): 
,I/jxcore-log( 3593): Size 720 1184
I/jxcore-log( 3593): 
,I/jxcore-log( 3593): Screen Brightness 10
I/jxcore-log( 3593): 
,E/jxcore-log( 3593): Dummy Error Log.
E/jxcore-log( 3593): 
,I/jxcore-log( 3593): getBuffer is called!!!!
I/jxcore-log( 3593): 
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MMApiBackOffService( 1541): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1541): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1541): MMApiBackOffService told us it's okay to retry the waiting requests: 2
,D/MMApiWebService( 1541): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1541): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1541): doRequest(): polling manager says we're not connected, returning with an error: 
,D/MMApiWebService( 1541): doRequest(): polling manager says we're not connected, returning with an error: devices.json
I/MMApiWebService( 1541): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,E/MMApiProvisionService( 1541): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1541): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1541): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1541): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 1541): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1541): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1541): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1541): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1541): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1541): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 60000
,D/Checkin ( 1541): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1541): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/Checkin ( 1541): publish the event [tag = MOT_CCE event name = LOG]
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
,D/WifiService( 1019): New client listening to asynchronous messages
,D/WifiService( 1019): setWifiEnabled: false pid=3593, uid=10478
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3593): ****TEST TOOK:  5052  ms ****
I/jxcore-log( 3593): 
I/jxcore-log( 3593): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3593): 
,D/AndroidRuntime( 3658): 
D/AndroidRuntime( 3658): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3658): CheckJNI is OFF
,D/dalvikvm( 3658): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 3658): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 3658): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3658): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 3658): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 3658): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,E/memtrack( 3658): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 3658): failed to load memtrack module: -2
,D/AndroidRuntime( 3658): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1019): Force stopping com.example.hello appid=10478 user=-1: uninstall pkg
,I/ActivityManager( 1019): Killing 3593:com.example.hello/u0a478 (adj 0): stop com.example.hello
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019):   Force finishing activity ActivityRecord{429954a8 u0 com.example.hello/.MainActivity t3}
,I/WindowState( 1019): WIN DEATH: Window{4299d390 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService( 1019): Client connection lost with reason: 4
,W/PackageSettings( 1019): Skipping PackageSetting{421cf1c8 com.test.thalitest/10476} due to missing metadata
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager( 1019): Force stopping com.example.hello appid=10478 user=0: pkg removed
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,I/LatinIME:LogUtils( 1187): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/LatinIME:LogUtils( 1187): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,D/dalvikvm( 1386): GC_EXPLICIT freed 1116K, 33% free 11697K/17224K, paused 4ms+6ms, total 90ms
,I/OtaApp  ( 1541): [info] > Updatetime from metadata: 10
,D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,I/LatinIME:LogUtils( 1187): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450189359
,W/GeofencerStateMachine( 1203): Ignoring removeGeofence because network location is disabled.
,D/OtaApp  ( 1541): [debug] > cancelling the previous pending intent set for install later
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
I/OtaApp  ( 1541): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
,D/dalvikvm( 2189): GC_EXPLICIT freed 3521K, 42% free 10095K/17224K, paused 3ms+8ms, total 132ms
,D/dalvikvm( 2157): GC_EXPLICIT freed 4713K, 45% free 9631K/17224K, paused 1ms+5ms, total 74ms
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
D/OtaApp  ( 1541): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
D/VoicemailCleanupService( 3080): Cleaning up data for package: com.example.hello
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,D/dalvikvm( 1300): GC_EXPLICIT freed 2856K, 33% free 11629K/17224K, paused 2ms+29ms, total 166ms
,I/Launcher( 1300): Deferring update until onResume
,D/dalvikvm( 1019): GC_EXPLICIT freed 2318K, 12% free 17789K/20156K, paused 4ms+14ms, total 167ms
,D/dalvikvm( 1019): WAIT_FOR_CONCURRENT_GC blocked 41ms
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,I/Launcher( 1300): Deferring update until onResume
,I/InternalIcingCorporaPro( 2189): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/ActivityManager( 1019): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3690 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,I/LatinIME:LogUtils( 1187): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1450189360
W/ContextImpl( 3690): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
,I/dalvikvm( 3161): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3161): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3161): VFY: replacing opcode 0x6e at 0x0013
,D/PackageBroadcastService( 1386): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1386): Clearing selected account for com.example.hello
D/ChimeraCfgMgr( 1386): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1386): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1386): Removing dialog suppression flag for package com.example.hello
,D/ChimeraCfgMgr( 1386): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1386): Module APK com.google.android.play.games already loaded
,D/gH_CompatibleDatabase( 1386): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1386): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1386): 0 metrics were deleted when clearing package com.example.hello.
,D/gH_CompatibleDatabase( 1386): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1386): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1386): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
E/NetworkScheduler.SchedulerReceiver( 2014): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 2014): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 1386): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1386): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1386): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
V/BackupManagerService( 1019): removePackageParticipantsLocked: uid=10478 #1
,I/ActivityManager( 1019): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3711 uid=10058 gids={50058}
D/gH_CompatibleDatabase( 1386): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1386): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1386): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1386): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/Icing   ( 1386): doRemovePackageData com.example.hello
,W/InputMethodManagerService( 1019): Got RemoteException sending setActive(false) notification to pid 3593 uid 10478
W/Binder  ( 1187): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1187): java.lang.NullPointerException
W/Binder  ( 1187): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1187): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1187): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1187): 	at dalvik.system.NativeStart.run(Native Method)
,D/OtaApp  ( 1541): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/ActivityManager( 1019): Killing 3348:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/InternalIcingCorporaPro( 2189): UpdateCorporaTask done [took 170 ms] updated apps [took 170 ms] 
,D/Documents( 3711): Loading roots for com.android.providers.downloads.documents
,D/dalvikvm( 1019): GC_EXPLICIT freed 455K, 12% free 17794K/20156K, paused 6ms+15ms, total 260ms
,I/ActivityManager( 1019): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=3730 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/ActivityManager( 1019): Killing 3461:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Killing 3430:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/AndroidRuntime( 3658): Shutting down VM
,D/dalvikvm( 3658): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 3ms
,D/Documents( 3711): Loading roots for com.android.externalstorage.documents
,D/dalvikvm( 3730): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f0d4c0, skipping init
I/openssl ( 3730): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3730): Crypto mode 0 already enabled
,I/ActivityManager( 1019): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3747 uid=10020 gids={50020, 1028, 1015, 1023}
,I/ActivityManager( 1019): Killing 3080:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1258): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/ExternalStorage( 3747): After updating volumes, found 1 active roots
,D/Documents( 3711): Updating roots due to change at content://com.android.externalstorage.documents/root
,D/Documents( 3711): Loading roots for com.android.providers.media.documents
,D/Documents( 3711): Loading roots for com.google.android.apps.docs.storage
,D/Documents( 3711): Update found 7 roots in 231ms
D/Documents( 3711): Used cached roots for com.android.providers.downloads.documents
,D/Documents( 3711): Loading roots for com.android.externalstorage.documents
D/Documents( 3711): Used cached roots for com.android.providers.media.documents
D/Documents( 3711): Used cached roots for com.google.android.apps.docs.storage
,D/Documents( 3711): Update found 7 roots in 6ms

```
