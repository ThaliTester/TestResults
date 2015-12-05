#### Test 50388019f33194e_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 3432): 
D/AndroidRuntime( 3432): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3432): CheckJNI is OFF
D/dalvikvm( 3432): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3432): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3432): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3432): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3432): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3432): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3432): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3432): failed to load memtrack module: -2
D/AndroidRuntime( 3432): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1020): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3432
W/WindowManager( 1020): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1020): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3448 uid=10435 gids={50435, 3003, 3001, 3002}
D/AndroidRuntime( 3432): Shutting down VM
D/dalvikvm( 3432): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+0ms, total 3ms
W/ContextImpl( 1231): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1231): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3448): Binding Chromium to main looper Looper (main, tid 1) {41fb7ba8}
I/LibraryLoader( 3448): Expected native library version number "",actual native library version number ""
I/chromium( 3448): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3448): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1020): Message: 20
D/BluetoothManagerService( 1020): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@421c1218:true
D/BluetoothAdapter( 3448): 1107083400: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3448): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3448): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3448): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3448): Local Branch: 
I/Adreno-EGL( 3448): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3448): Local Patches: NONE
I/Adreno-EGL( 3448): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3448): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 3448): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3448): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3448): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3448): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3448): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3448): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3448): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3448): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3448): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3448): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 3448): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3448): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3448): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3448): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3448): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3448): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3448): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 3448): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3448): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3448): Enabling debug mode 0
,W/AwContents( 3448): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3448): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1020): Displayed com.example.hello/.MainActivity,cp,ca,376
I/ActivityManager( 1020): Displayed com.example.hello/.MainActivity: +353ms (total +376ms)
,I/chromium( 3448): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 3448): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/JsMessageQueue( 3448): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3448): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x41fbbf40
,D/dalvikvm( 3448): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x41fbbf40
,D/jxcore_app_log( 3448): JniHelper::setJavaVM(0x41606fa8), pthread_self() = 1609848320
,D/JX-Cordova( 3448): jxcore cordova android initializing
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,W/jxcore-log( 3448): Initializing JXcore engine
,W/jxcore-log( 3448): JXcore engine is ready
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,W/jxcore-log( 3448): Starting JXcore engine
,W/jxcore-log( 3448): Platform android
W/jxcore-log( 3448): 
,W/jxcore-log( 3448): Process ARCH arm
W/jxcore-log( 3448): 
,I/jxcore-log( 3448): JXcore Cordova bridge is ready!
I/jxcore-log( 3448): 
,W/jxcore-log( 3448): JXcore engine is started
,E/jxcore-log( 3448): >> motorola-XT1039
E/jxcore-log( 3448): 
,I/jxcore-log( 3448): Total memory 893136896
I/jxcore-log( 3448): 
I/jxcore-log( 3448): Free memory 34758656
I/jxcore-log( 3448): 
I/jxcore-log( 3448): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3448): 
,I/jxcore-log( 3448): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3448): 
,I/jxcore-log( 3448): userPath [ 'www' ]
I/jxcore-log( 3448): 
,I/jxcore-log( 3448): Size 720 1184
I/jxcore-log( 3448): 
,I/jxcore-log( 3448): Screen Brightness 10
I/jxcore-log( 3448): 
,E/jxcore-log( 3448): Dummy Error Log.
E/jxcore-log( 3448): 
,I/jxcore-log( 3448): getBuffer is called!!!!
I/jxcore-log( 3448): 
,I/MMApiBackOffService( 1526): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1526): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1526): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1526): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1526): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1526): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1526): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1526): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
I/MMApiBackOffService( 1526): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
D/MMApiWebService( 1526): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,D/Checkin ( 1526): publish the event [tag = MOT_CCE event name = LOG]
,E/MMApiProvisionService( 1526): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1526): ProvisionWS.Response.setError: error RadioDownError
I/MMApiWebService( 1526): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1526): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1526): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1526): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1526): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 60000
,D/MMApiWebService( 1526): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/Checkin ( 1526): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1526): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1526): MMApiWebService told us not to continue at the moment with this request: devices.json
,I/MMApiWebService( 1526): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1526): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1526): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1526): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 60000
,D/Checkin ( 1526): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1526): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1526): publish the event [tag = MOT_CCE event name = LOG]
,D/dalvikvm( 1526): GC_CONCURRENT freed 6302K, 38% free 10774K/17224K, paused 3ms+5ms, total 45ms
,D/BluetoothManagerService( 1020): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1020): Disable(): Service is not Connected Or Bluetooth is not enabled
,D/WifiService( 1020): New client listening to asynchronous messages
,D/WifiService( 1020): setWifiEnabled: false pid=3448, uid=10435
,E/WifiService( 1020): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3448): ****TEST TOOK:  5050  ms ****
I/jxcore-log( 3448): 
I/jxcore-log( 3448): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3448): 
,D/AndroidRuntime( 3511): 
D/AndroidRuntime( 3511): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3511): CheckJNI is OFF
,D/dalvikvm( 3511): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 3511): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 3511): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3511): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 3511): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 3511): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,E/memtrack( 3511): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 3511): failed to load memtrack module: -2
,D/AndroidRuntime( 3511): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1020): Force stopping com.example.hello appid=10435 user=-1: uninstall pkg
I/ActivityManager( 1020): Killing 3448:com.example.hello/u0a435 (adj 0): stop com.example.hello
W/ContextImpl( 1231): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1020):   Force finishing activity ActivityRecord{42994320 u0 com.example.hello/.MainActivity t3}
,I/WindowState( 1020): WIN DEATH: Window{428dfed0 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService( 1020): Client connection lost with reason: 4
,W/PackageSettings( 1020): Skipping PackageSetting{42279dd8 com.test.thalitest/10434} due to missing metadata
,W/ContextImpl( 1231): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1231): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager( 1020): Force stopping com.example.hello appid=10435 user=0: pkg removed
,D/dalvikvm( 2067): GC_EXPLICIT freed 4726K, 45% free 9630K/17224K, paused 2ms+7ms, total 43ms
,I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
,I/OtaApp  ( 1526): [info] > Updatetime from metadata: 10
,D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
,D/dalvikvm( 2099): GC_EXPLICIT freed 3590K, 42% free 10095K/17224K, paused 3ms+5ms, total 73ms
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
,I/LatinIME:LogUtils( 1193): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/LatinIME:LogUtils( 1193): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,D/dalvikvm( 1289): GC_EXPLICIT freed 2787K, 33% free 11591K/17224K, paused 2ms+4ms, total 36ms
,W/GeofencerStateMachine( 1214): Ignoring removeGeofence because network location is disabled.
,D/OtaApp  ( 1526): [debug] > cancelling the previous pending intent set for install later
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
I/OtaApp  ( 1526): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1526): publish the event [tag = MOT_OTA event name = LOG]
,D/VoicemailCleanupService( 3012): Cleaning up data for package: com.example.hello
,I/LatinIME:LogUtils( 1193): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449275306
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
D/OtaApp  ( 1526): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/Launcher( 1289): Deferring update until onResume
,D/OtaApp  ( 1526): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
,W/InputMethodManagerService( 1020): Got RemoteException sending setActive(false) notification to pid 3448 uid 10435
,W/Binder  ( 1193): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1193): java.lang.NullPointerException
W/Binder  ( 1193): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1193): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1193): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1193): 	at dalvik.system.NativeStart.run(Native Method)
,D/dalvikvm( 1020): GC_EXPLICIT freed 1577K, 15% free 17822K/20804K, paused 4ms+11ms, total 116ms
,D/dalvikvm( 1020): WAIT_FOR_CONCURRENT_GC blocked 105ms
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
,I/InternalIcingCorporaPro( 2099): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/Launcher( 1289): Deferring update until onResume
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
,I/ActivityManager( 1020): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3542 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,I/LatinIME:LogUtils( 1193): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449275306
W/ContextImpl( 3542): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
,D/PackageBroadcastService( 1373): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1373): Clearing selected account for com.example.hello
D/ChimeraCfgMgr( 1373): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1373): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1373): Removing dialog suppression flag for package com.example.hello
,I/InternalIcingCorporaPro( 2099): UpdateCorporaTask done [took 118 ms] updated apps [took 118 ms] 
E/NetworkScheduler.SchedulerReceiver( 1361): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1361): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/ChimeraCfgMgr( 1373): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1373): Module APK com.google.android.play.games already loaded
,D/gH_CompatibleDatabase( 1373): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1373): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1373): 0 metrics were deleted when clearing package com.example.hello.
,D/gH_CompatibleDatabase( 1373): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,I/PeopleContactsSync( 1373): CP2 sync disabled
,D/gH_CompatibleDatabase( 1373): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,I/Icing   ( 1373): doRemovePackageData com.example.hello
D/BackupManagerService( 1020): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,V/BackupManagerService( 1020): removePackageParticipantsLocked: uid=10435 #1
D/gH_CompatibleDatabase( 1373): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1373): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/dalvikvm( 3076): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3076): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 3076): VFY: replacing opcode 0x6e at 0x0013
D/dalvikvm( 1214): GC_EXPLICIT freed 1358K, 41% free 10257K/17224K, paused 2ms+6ms, total 52ms
D/gH_CompatibleDatabase( 1373): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1373): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1373): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1373): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1373): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1373): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager( 1020): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3565 uid=10058 gids={50058}
,I/ActivityManager( 1020): Killing 3207:com.android.calendar/u0a7 (adj 15): empty #9
,E/DataBuffer( 1214): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@420047f8)
W/ContextImpl( 1231): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1020): GC_EXPLICIT freed 639K, 15% free 17692K/20804K, paused 4ms+15ms, total 233ms
,D/AndroidRuntime( 3511): Shutting down VM
,D/dalvikvm( 3511): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms
,D/Documents( 3565): Loading roots for com.android.providers.downloads.documents
,I/ActivityManager( 1020): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=3581 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/ActivityManager( 1020): Killing 3317:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1231): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1020): Killing 3288:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1231): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm(  277): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+3ms, total 21ms
,D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 17ms
,D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 3581): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41fc1190, skipping init
I/openssl ( 3581): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3581): Crypto mode 0 already enabled
,D/Documents( 3565): Loading roots for com.android.externalstorage.documents
,I/ActivityManager( 1020): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3597 uid=10020 gids={50020, 1028, 1015, 1023}
,I/ActivityManager( 1020): Killing 3012:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1231): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/ExternalStorage( 3597): After updating volumes, found 1 active roots
,D/Documents( 3565): Updating roots due to change at content://com.android.externalstorage.documents/root
,D/Documents( 3565): Loading roots for com.android.providers.media.documents
,D/Documents( 3565): Loading roots for com.google.android.apps.docs.storage
,D/Documents( 3565): Update found 7 roots in 190ms
D/Documents( 3565): Used cached roots for com.android.providers.downloads.documents
,D/Documents( 3565): Loading roots for com.android.externalstorage.documents
D/Documents( 3565): Used cached roots for com.android.providers.media.documents
D/Documents( 3565): Used cached roots for com.google.android.apps.docs.storage
,D/Documents( 3565): Update found 7 roots in 7ms

```
