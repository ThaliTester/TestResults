#### Test 50242285e707819_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 3456): 
D/AndroidRuntime( 3456): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3456): CheckJNI is OFF
D/dalvikvm( 3456): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3456): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3456): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3456): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3456): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3456): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3456): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3456): failed to load memtrack module: -2
D/AndroidRuntime( 3456): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1024): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3456
W/WindowManager( 1024): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1024): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3472 uid=10441 gids={50441, 3003, 3001, 3002}
D/AndroidRuntime( 3456): Shutting down VM
D/dalvikvm( 3456): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+1ms, total 3ms
W/ContextImpl( 1221): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1221): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3472): Binding Chromium to main looper Looper (main, tid 1) {41f928c0}
I/LibraryLoader( 3472): Expected native library version number "",actual native library version number ""
I/chromium( 3472): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3472): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1024): Message: 20
D/BluetoothAdapter( 3472): 1106944336: getState() :  mService = null. Returning STATE_OFF
D/BluetoothManagerService( 1024): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42809cf8:true
I/Adreno-EGL( 3472): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3472): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3472): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3472): Local Branch: 
I/Adreno-EGL( 3472): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3472): Local Patches: NONE
I/Adreno-EGL( 3472): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3472): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 3472): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3472): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3472): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3472): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3472): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3472): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3472): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3472): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3472): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3472): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 3472): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3472): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3472): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3472): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3472): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3472): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3472): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 3472): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 3472): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3472): Enabling debug mode 0
,W/AwContents( 3472): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3472): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1024): Displayed com.example.hello/.MainActivity,cp,ca,361
I/ActivityManager( 1024): Displayed com.example.hello/.MainActivity: +335ms (total +361ms)
,I/chromium( 3472): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 3472): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/JsMessageQueue( 3472): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3472): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x41f9a008
,D/dalvikvm( 3472): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x41f9a008
,D/jxcore_app_log( 3472): JniHelper::setJavaVM(0x415e3fa8), pthread_self() = 1610909648
,D/JX-Cordova( 3472): jxcore cordova android initializing
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,W/jxcore-log( 3472): Initializing JXcore engine
,W/jxcore-log( 3472): JXcore engine is ready
,W/jxcore-log( 3472): Starting JXcore engine
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,W/jxcore-log( 3472): Platform android
W/jxcore-log( 3472): 
,W/jxcore-log( 3472): Process ARCH arm
W/jxcore-log( 3472): 
,I/jxcore-log( 3472): JXcore Cordova bridge is ready!
I/jxcore-log( 3472): 
,W/jxcore-log( 3472): JXcore engine is started
,E/jxcore-log( 3472): >> motorola-XT1039
E/jxcore-log( 3472): 
,I/jxcore-log( 3472): Total memory 893136896
I/jxcore-log( 3472): 
I/jxcore-log( 3472): Free memory 30986240
I/jxcore-log( 3472): 
I/jxcore-log( 3472): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3472): 
,I/jxcore-log( 3472): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3472): 
,I/jxcore-log( 3472): userPath [ 'www' ]
I/jxcore-log( 3472): 
,I/jxcore-log( 3472): Size 720 1184
I/jxcore-log( 3472): 
,I/jxcore-log( 3472): Screen Brightness 10
I/jxcore-log( 3472): 
,E/jxcore-log( 3472): Dummy Error Log.
E/jxcore-log( 3472): 
,I/jxcore-log( 3472): getBuffer is called!!!!
I/jxcore-log( 3472): 
,I/MMApiBackOffService( 1535): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1535): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1535): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1535): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1535): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1535): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,D/MMApiWebService( 1535): doRequest(): polling manager says we're not connected, returning with an error: 
,E/MMApiProvisionService( 1535): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,I/MMApiWebService( 1535): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,E/MMApiProvisionService( 1535): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1535): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1535): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 1535): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1535): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1535): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1535): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1535): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1535): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 60000
,D/Checkin ( 1535): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1535): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/MMApiWebService( 1535): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/MMApiWebService( 1535): doRequest(): polling manager says we're not connected, returning with an error: 
D/Checkin ( 1535): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1535): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1535): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1535): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 60000
,D/Checkin ( 1535): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1535): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1535): publish the event [tag = MOT_CCE event name = LOG]
,D/BluetoothManagerService( 1024): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1024): Disable(): Service is not Connected Or Bluetooth is not enabled
,D/WifiService( 1024): New client listening to asynchronous messages
,D/WifiService( 1024): setWifiEnabled: false pid=3472, uid=10441
,E/WifiService( 1024): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3472): ****TEST TOOK:  5049  ms ****
I/jxcore-log( 3472): 
I/jxcore-log( 3472): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3472): 
,D/AndroidRuntime( 3544): 
D/AndroidRuntime( 3544): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3544): CheckJNI is OFF
,D/dalvikvm( 3544): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 3544): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3544): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3544): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 3544): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 3544): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,E/memtrack( 3544): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 3544): failed to load memtrack module: -2
,D/AndroidRuntime( 3544): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1024): Force stopping com.example.hello appid=10441 user=-1: uninstall pkg
,I/ActivityManager( 1024): Killing 3472:com.example.hello/u0a441 (adj 0): stop com.example.hello
,W/ContextImpl( 1221): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/WindowState( 1024): WIN DEATH: Window{4280cdc8 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService( 1024): Client connection lost with reason: 4
,I/ActivityManager( 1024):   Force finishing activity ActivityRecord{42955c20 u0 com.example.hello/.MainActivity t3}
,W/PackageSettings( 1024): Skipping PackageSetting{42257e10 com.test.thalitest/10439} due to missing metadata
,W/ContextImpl( 1221): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1221): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager( 1024): Force stopping com.example.hello appid=10441 user=0: pkg removed
,D/dalvikvm( 2082): GC_EXPLICIT freed 4723K, 45% free 9627K/17224K, paused 2ms+5ms, total 36ms
,I/OtaApp  ( 1535): [info] > Updatetime from metadata: 10
,D/Checkin ( 1535): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1535): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1535): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1535): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1535): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/InputReader( 1024): Reconfiguring input devices.  changes=0x00000010
,I/LatinIME:LogUtils( 1189): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/LatinIME:LogUtils( 1189): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "sms"
,I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "smsto"
,W/GeofencerStateMachine( 1206): Ignoring removeGeofence because network location is disabled.
,D/OtaApp  ( 1535): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/dalvikvm( 2126): GC_EXPLICIT freed 2472K, 44% free 9812K/17224K, paused 6ms+26ms, total 138ms
,D/dalvikvm( 1535): GC_CONCURRENT freed 6312K, 38% free 10800K/17224K, paused 3ms+5ms, total 76ms
,I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "mms"
,I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "mmsto"
,D/dalvikvm( 1288): GC_EXPLICIT freed 2788K, 33% free 11591K/17224K, paused 2ms+13ms, total 144ms
,I/Launcher( 1288): Deferring update until onResume
,D/VoicemailCleanupService( 3064): Cleaning up data for package: com.example.hello
,D/dalvikvm( 1024): GC_EXPLICIT freed 1412K, 15% free 17727K/20744K, paused 3ms+12ms, total 143ms
,D/dalvikvm( 1024): WAIT_FOR_CONCURRENT_GC blocked 44ms
,I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "sms"
,I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "smsto"
,I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 1024):   Scheme: "mms"
,W/InputMethodManagerService( 1024): Got RemoteException sending setActive(false) notification to pid 3472 uid 10441
W/Binder  ( 1189): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1189): java.lang.NullPointerException
W/Binder  ( 1189): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1189): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1189): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1189): 	at dalvik.system.NativeStart.run(Native Method)
,I/PackageManager( 1024): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1024):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1024):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1024):   Scheme: "mmsto"
I/LatinIME:LogUtils( 1189): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449499013
I/InternalIcingCorporaPro( 2126): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/Launcher( 1288): Deferring update until onResume
,I/ActivityManager( 1024): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3578 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,W/ContextImpl( 3578): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
,D/PackageBroadcastService( 1356): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1356): Clearing selected account for com.example.hello
,I/LatinIME:LogUtils( 1189): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449499013
,D/ChimeraCfgMgr( 1356): Loading module com.google.android.gms.games from APK com.google.android.play.games
,I/LocationSettingsChecker( 1356): Removing dialog suppression flag for package com.example.hello
,D/ChimeraModuleLdr( 1356): Module APK com.google.android.play.games already loaded
,D/BackupManagerService( 1024): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,V/BackupManagerService( 1024): removePackageParticipantsLocked: uid=10441 #1
,D/ChimeraCfgMgr( 1356): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1356): Module APK com.google.android.play.games already loaded
D/gH_CompatibleDatabase( 1356): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1356): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/NetworkScheduler.SchedulerReceiver( 1370): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1370): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_MetricsDatabase( 1356): 0 metrics were deleted when clearing package com.example.hello.
,D/gH_CompatibleDatabase( 1356): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1356): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1356): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1356): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1356): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1356): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1356): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1356): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1356): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1356): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/PeopleContactsSync( 1356): CP2 sync disabled
,I/dalvikvm( 3129): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3129): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3129): VFY: replacing opcode 0x6e at 0x0013
,I/Icing   ( 1356): doRemovePackageData com.example.hello
,D/dalvikvm( 1206): GC_EXPLICIT freed 1417K, 41% free 10257K/17224K, paused 3ms+5ms, total 47ms
,D/dalvikvm( 1024): GC_EXPLICIT freed 493K, 15% free 17722K/20744K, paused 7ms+14ms, total 216ms
I/ActivityManager( 1024): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3600 uid=10058 gids={50058}
I/ActivityManager( 1024): Killing 3190:com.android.providers.calendar/u0a8 (adj 15): empty #9
,D/dalvikvm(  277): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+3ms, total 22ms
,W/ContextImpl( 1221): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/InternalIcingCorporaPro( 2126): UpdateCorporaTask done [took 195 ms] updated apps [took 195 ms] 
,E/DataBuffer( 1206): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@41f9ff18)
,D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 19ms
,D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 17ms
,D/Documents( 3600): Loading roots for com.android.providers.downloads.documents
,D/AndroidRuntime( 3544): Shutting down VM
,I/ActivityManager( 1024): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=3617 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,D/dalvikvm( 3544): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
I/ActivityManager( 1024): Killing 3348:com.google.android.partnersetup/u0a25 (adj 15): empty #9
W/ContextImpl( 1221): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1024): Killing 3322:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1221): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Documents( 3600): Loading roots for com.android.externalstorage.documents
,D/dalvikvm( 3617): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f94568, skipping init
I/openssl ( 3617): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3617): Crypto mode 0 already enabled
,I/ActivityManager( 1024): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3633 uid=10020 gids={50020, 1028, 1015, 1023}
,I/ActivityManager( 1024): Killing 3064:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1221): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/ExternalStorage( 3633): After updating volumes, found 1 active roots
,D/Documents( 3600): Updating roots due to change at content://com.android.externalstorage.documents/root
,D/Documents( 3600): Loading roots for com.android.providers.media.documents
,D/Documents( 3600): Loading roots for com.google.android.apps.docs.storage
,D/Documents( 3600): Update found 7 roots in 187ms
D/Documents( 3600): Used cached roots for com.android.providers.downloads.documents
,D/Documents( 3600): Loading roots for com.android.externalstorage.documents
D/Documents( 3600): Used cached roots for com.android.providers.media.documents
D/Documents( 3600): Used cached roots for com.google.android.apps.docs.storage
,D/Documents( 3600): Update found 7 roots in 7ms

```
