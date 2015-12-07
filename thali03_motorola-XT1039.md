#### Test 502422852e23b2c_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 3492): 
D/AndroidRuntime( 3492): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3492): CheckJNI is OFF
D/dalvikvm( 3492): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3492): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3492): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3492): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3492): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3492): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3492): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3492): failed to load memtrack module: -2
D/AndroidRuntime( 3492): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1020): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3492
W/WindowManager( 1020): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1020): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3508 uid=10440 gids={50440, 3003, 3001, 3002}
D/AndroidRuntime( 3492): Shutting down VM
D/dalvikvm( 3492): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/dalvikvm(  276): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+3ms, total 24ms
W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+6ms, total 26ms
D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+5ms, total 23ms
V/WebViewChromiumFactoryProvider( 3508): Binding Chromium to main looper Looper (main, tid 1) {425ab8d8}
I/LibraryLoader( 3508): Expected native library version number "",actual native library version number ""
I/chromium( 3508): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3508): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1020): Message: 20
D/BluetoothManagerService( 1020): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42679f70:true
D/BluetoothAdapter( 3508): 1113325224: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3508): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3508): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3508): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3508): Local Branch: 
I/Adreno-EGL( 3508): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3508): Local Patches: NONE
I/Adreno-EGL( 3508): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3508): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 3508): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3508): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3508): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3508): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3508): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3508): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3508): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3508): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3508): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3508): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 3508): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3508): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3508): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3508): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 3508): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3508): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3508): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 3508): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 3508): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3508): Enabling debug mode 0
,W/AwContents( 3508): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3508): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1020): Displayed com.example.hello/.MainActivity,cp,ca,369
I/ActivityManager( 1020): Displayed com.example.hello/.MainActivity: +339ms (total +369ms)
,I/chromium( 3508): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 3508): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/JsMessageQueue( 3508): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3508): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x425afd60
,D/dalvikvm( 3508): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x425afd60
,D/jxcore_app_log( 3508): JniHelper::setJavaVM(0x41cc4f78), pthread_self() = 1610069032
,D/JX-Cordova( 3508): jxcore cordova android initializing
,W/jxcore-log( 3508): Initializing JXcore engine
,W/jxcore-log( 3508): JXcore engine is ready
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,W/jxcore-log( 3508): Starting JXcore engine
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,W/jxcore-log( 3508): Platform android
W/jxcore-log( 3508): 
,W/jxcore-log( 3508): Process ARCH arm
W/jxcore-log( 3508): 
,I/jxcore-log( 3508): JXcore Cordova bridge is ready!
I/jxcore-log( 3508): 
,W/jxcore-log( 3508): JXcore engine is started
,E/jxcore-log( 3508): >> motorola-XT1039
E/jxcore-log( 3508): 
,I/jxcore-log( 3508): Total memory 893136896
I/jxcore-log( 3508): 
I/jxcore-log( 3508): Free memory 31920128
I/jxcore-log( 3508): 
,I/jxcore-log( 3508): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3508): 
,I/jxcore-log( 3508): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3508): 
,I/jxcore-log( 3508): userPath [ 'www' ]
I/jxcore-log( 3508): 
,I/jxcore-log( 3508): Size 720 1184
I/jxcore-log( 3508): 
,I/jxcore-log( 3508): Screen Brightness 10
I/jxcore-log( 3508): 
,E/jxcore-log( 3508): Dummy Error Log.
E/jxcore-log( 3508): 
,I/jxcore-log( 3508): getBuffer is called!!!!
I/jxcore-log( 3508): 
,I/MMApiBackOffService( 1545): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1545): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1545): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1545): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1545): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1545): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1545): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/MMApiWebService( 1545): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,E/MMApiProvisionService( 1545): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1545): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1545): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1545): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 1545): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1545): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1545): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1545): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1545): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 60000
,D/Checkin ( 1545): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1545): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1545): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1545): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/Checkin ( 1545): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1545): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1545): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1545): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1545): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 60000
,D/Checkin ( 1545): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1545): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1545): publish the event [tag = MOT_CCE event name = LOG]
,D/BluetoothManagerService( 1020): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1020): Disable(): Service is not Connected Or Bluetooth is not enabled
,D/WifiService( 1020): New client listening to asynchronous messages
,D/WifiService( 1020): setWifiEnabled: false pid=3508, uid=10440
,E/WifiService( 1020): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3508): ****TEST TOOK:  5050  ms ****
I/jxcore-log( 3508): 
I/jxcore-log( 3508): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3508): 
,D/AndroidRuntime( 3572): 
D/AndroidRuntime( 3572): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3572): CheckJNI is OFF
,D/dalvikvm( 3572): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 3572): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3572): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3572): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 3572): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 3572): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,E/memtrack( 3572): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 3572): failed to load memtrack module: -2
,D/AndroidRuntime( 3572): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1020): Force stopping com.example.hello appid=10440 user=-1: uninstall pkg
,I/ActivityManager( 1020): Killing 3508:com.example.hello/u0a440 (adj 0): stop com.example.hello
,W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1020):   Force finishing activity ActivityRecord{42f7df58 u0 com.example.hello/.MainActivity t3}
,I/WindowState( 1020): WIN DEATH: Window{42d9c058 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService( 1020): Client connection lost with reason: 4
,W/PackageSettings( 1020): Skipping PackageSetting{42872b18 com.test.thalitest/10439} due to missing metadata
,W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager( 1020): Force stopping com.example.hello appid=10440 user=0: pkg removed
,I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
,I/OtaApp  ( 1545): [info] > Updatetime from metadata: 10
,D/Checkin ( 1545): publish the event [tag = MOT_OTA event name = LOG]
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
,I/LatinIME:LogUtils( 1185): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449497330
,I/LatinIME:LogUtils( 1185): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/LatinIME:LogUtils( 1185): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,D/OtaApp  ( 1545): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1545): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/Checkin ( 1545): publish the event [tag = MOT_OTA event name = LOG]
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
,D/dalvikvm( 2102): GC_EXPLICIT freed 4698K, 45% free 9627K/17224K, paused 9ms+6ms, total 89ms
,D/dalvikvm( 1545): GC_CONCURRENT freed 6325K, 38% free 10781K/17224K, paused 10ms+4ms, total 85ms
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
D/OtaApp  ( 1545): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,W/GeofencerStateMachine( 1206): Ignoring removeGeofence because network location is disabled.
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
,D/OtaApp  ( 1545): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/dalvikvm( 1020): GC_EXPLICIT freed 1480K, 15% free 17765K/20744K, paused 8ms+11ms, total 179ms
,D/VoicemailCleanupService( 3039): Cleaning up data for package: com.example.hello
,W/InputMethodManagerService( 1020): Got RemoteException sending setActive(false) notification to pid 3508 uid 10440
W/Binder  ( 1185): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1185): java.lang.NullPointerException
W/Binder  ( 1185): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1185): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1185): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1185): 	at dalvik.system.NativeStart.run(Native Method)
,D/dalvikvm( 1300): GC_EXPLICIT freed 2855K, 33% free 11629K/17224K, paused 11ms+20ms, total 185ms
,D/dalvikvm( 1020): WAIT_FOR_CONCURRENT_GC blocked 65ms
,I/Launcher( 1300): Deferring update until onResume
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
,D/dalvikvm( 2134): GC_EXPLICIT freed 2970K, 42% free 10049K/17224K, paused 3ms+14ms, total 228ms
,I/Launcher( 1300): Deferring update until onResume
,I/LatinIME:LogUtils( 1185): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449497330
,I/InternalIcingCorporaPro( 2134): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/ActivityManager( 1020): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3604 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,W/ContextImpl( 3604): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
,D/BackupManagerService( 1020): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,V/BackupManagerService( 1020): removePackageParticipantsLocked: uid=10440 #1
D/PackageBroadcastService( 1373): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1373): Clearing selected account for com.example.hello
,D/ChimeraCfgMgr( 1373): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1373): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1373): Removing dialog suppression flag for package com.example.hello
,D/ChimeraCfgMgr( 1373): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1373): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1385): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1385): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 1373): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1373): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1373): 0 metrics were deleted when clearing package com.example.hello.
,D/gH_CompatibleDatabase( 1373): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1373): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1373): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1373): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1373): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1373): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
I/dalvikvm( 3112): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3112): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/gH_CompatibleDatabase( 1373): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/dalvikvm( 3112): VFY: replacing opcode 0x6e at 0x0013
D/gH_CompatibleDatabase( 1373): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1373): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1373): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager( 1020): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3624 uid=10058 gids={50058}
,I/PeopleContactsSync( 1373): CP2 sync disabled
,D/dalvikvm( 1206): GC_EXPLICIT freed 1391K, 41% free 10257K/17224K, paused 2ms+6ms, total 43ms
,I/Icing   ( 1373): doRemovePackageData com.example.hello
,E/DataBuffer( 1206): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@425d84f8)
,I/InternalIcingCorporaPro( 2134): UpdateCorporaTask done [took 142 ms] updated apps [took 142 ms] 
,I/ActivityManager( 1020): Killing 3267:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/dalvikvm( 1020): GC_EXPLICIT freed 485K, 15% free 17689K/20744K, paused 51ms+12ms, total 241ms
,D/Documents( 3624): Loading roots for com.android.providers.downloads.documents
,I/ActivityManager( 1020): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=3643 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/ActivityManager( 1020): Killing 3384:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1020): Killing 3353:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/AndroidRuntime( 3572): Shutting down VM
,D/dalvikvm( 3572): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+1ms, total 3ms
,D/Documents( 3624): Loading roots for com.android.externalstorage.documents
,D/dalvikvm( 3643): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x425aa760, skipping init
I/openssl ( 3643): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3643): Crypto mode 0 already enabled
I/ActivityManager( 1020): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3658 uid=10020 gids={50020, 1028, 1015, 1023}
,I/ActivityManager( 1020): Killing 3039:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/ExternalStorage( 3658): After updating volumes, found 1 active roots
,D/Documents( 3624): Updating roots due to change at content://com.android.externalstorage.documents/root
,D/Documents( 3624): Loading roots for com.android.providers.media.documents
,D/Documents( 3624): Loading roots for com.google.android.apps.docs.storage
,D/Documents( 3624): Update found 7 roots in 179ms
D/Documents( 3624): Used cached roots for com.android.providers.downloads.documents
,D/Documents( 3624): Loading roots for com.android.externalstorage.documents
D/Documents( 3624): Used cached roots for com.android.providers.media.documents
D/Documents( 3624): Used cached roots for com.google.android.apps.docs.storage
,D/Documents( 3624): Update found 7 roots in 6ms

```
