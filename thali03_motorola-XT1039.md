#### Test 502422853393492_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
,I/MMApiBackOffService( 1541): MMAPIWebServiceRequest backOff fired!
D/Checkin ( 1541): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1541): MMApiBackOffService told us it's okay to retry the waiting requests: 3
D/MMApiWebService( 1541): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1541): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1541): doRequest(): polling manager says we're not connected, returning with an error: 
D/MMApiWebService( 1541): doRequest(): polling manager says we're not connected, returning with an error: devices.json
I/MMApiWebService( 1541): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1541): ProvisionWS.Response: Missing mandatory message data in response from DM server...
D/Checkin ( 1541): publish the event [tag = MOT_CCE event name = LOG]
E/MMApiProvisionService( 1541): ProvisionWS.Response.setError: error RadioDownError
I/MMApiBackOffService( 1541): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
D/Checkin ( 1541): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1541): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1541): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1541): publish the event [tag = MOT_CCE event name = LOG]
D/Checkin ( 1541): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1541): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 60000
D/Checkin ( 1541): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1541): MMApiWebService told us not to continue at the moment with this request: devices.json
D/Checkin ( 1541): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1541): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/MMApiWebService( 1541): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1541): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 1541): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1541): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 60000
D/Checkin ( 1541): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1541): MMApiWebService told us not to continue at the moment with this request: 
D/Checkin ( 1541): publish the event [tag = MOT_CCE event name = LOG]
D/AndroidRuntime( 3507): 
D/AndroidRuntime( 3507): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3507): CheckJNI is OFF
D/dalvikvm( 3507): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3507): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3507): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3507): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3507): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3507): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3507): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3507): failed to load memtrack module: -2
D/AndroidRuntime( 3507): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1022): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3507
W/WindowManager( 1022): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1022): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3523 uid=10437 gids={50437, 3003, 3001, 3002}
D/AndroidRuntime( 3507): Shutting down VM
D/dalvikvm( 3507): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
D/dalvikvm(  277): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+3ms, total 22ms
W/ContextImpl( 1260): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1260): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+7ms, total 23ms
D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 18ms
V/WebViewChromiumFactoryProvider( 3523): Binding Chromium to main looper Looper (main, tid 1) {426ff9b8}
I/LibraryLoader( 3523): Expected native library version number "",actual native library version number ""
I/chromium( 3523): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3523): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1022): Message: 20
D/BluetoothManagerService( 1022): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42f6ec80:true
D/BluetoothAdapter( 3523): 1114718088: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3523): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3523): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3523): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3523): Local Branch: 
I/Adreno-EGL( 3523): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3523): Local Patches: NONE
I/Adreno-EGL( 3523): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3523): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 3523): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3523): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3523): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3523): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3523): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3523): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3523): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3523): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3523): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3523): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 3523): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3523): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3523): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3523): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3523): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3523): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3523): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 3523): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 3523): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3523): Enabling debug mode 0
,W/AwContents( 3523): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3523): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1022): Displayed com.example.hello/.MainActivity,cp,ca,348
I/ActivityManager( 1022): Displayed com.example.hello/.MainActivity: +316ms (total +349ms)
,I/chromium( 3523): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 3523): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/JsMessageQueue( 3523): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3523): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x42703e40
,D/dalvikvm( 3523): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x42703e40
,D/jxcore_app_log( 3523): JniHelper::setJavaVM(0x41e18f78), pthread_self() = 1610857104
,D/JX-Cordova( 3523): jxcore cordova android initializing
,W/jxcore-log( 3523): Initializing JXcore engine
,W/jxcore-log( 3523): JXcore engine is ready
,W/jxcore-log( 3523): Starting JXcore engine
,W/jxcore-log( 3523): Platform android
W/jxcore-log( 3523): 
,W/jxcore-log( 3523): Process ARCH arm
W/jxcore-log( 3523): 
,I/jxcore-log( 3523): JXcore Cordova bridge is ready!
I/jxcore-log( 3523): 
,W/jxcore-log( 3523): JXcore engine is started
,E/jxcore-log( 3523): >> motorola-XT1039
E/jxcore-log( 3523): 
,I/jxcore-log( 3523): Total memory 893136896
I/jxcore-log( 3523): 
I/jxcore-log( 3523): Free memory 28827648
I/jxcore-log( 3523): 
,I/jxcore-log( 3523): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3523): 
,I/jxcore-log( 3523): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3523): 
,I/jxcore-log( 3523): userPath [ 'www' ]
I/jxcore-log( 3523): 
,I/jxcore-log( 3523): Size 720 1184
I/jxcore-log( 3523): 
,I/jxcore-log( 3523): Screen Brightness 10
I/jxcore-log( 3523): 
E/jxcore-log( 3523): Dummy Error Log.
E/jxcore-log( 3523): 
,I/jxcore-log( 3523): getBuffer is called!!!!
I/jxcore-log( 3523): 
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
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
,D/BluetoothManagerService( 1022): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1022): Disable(): Service is not Connected Or Bluetooth is not enabled
,D/WifiService( 1022): New client listening to asynchronous messages
,D/WifiService( 1022): setWifiEnabled: false pid=3523, uid=10437
,E/WifiService( 1022): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3523): ****TEST TOOK:  5060  ms ****
I/jxcore-log( 3523): 
,I/jxcore-log( 3523): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3523): 
,D/AndroidRuntime( 3593): 
D/AndroidRuntime( 3593): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3593): CheckJNI is OFF
,D/dalvikvm( 3593): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 3593): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 3593): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3593): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 3593): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 3593): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,E/memtrack( 3593): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 3593): failed to load memtrack module: -2
,D/AndroidRuntime( 3593): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1022): Force stopping com.example.hello appid=10437 user=-1: uninstall pkg
,I/ActivityManager( 1022): Killing 3523:com.example.hello/u0a437 (adj 0): stop com.example.hello
,W/ContextImpl( 1260): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1022):   Force finishing activity ActivityRecord{431983b0 u0 com.example.hello/.MainActivity t3}
,I/WindowState( 1022): WIN DEATH: Window{42f89418 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService( 1022): Client connection lost with reason: 4
,I/dalvikvm( 1022): Total arena pages for JIT: 15
,W/PackageSettings( 1022): Skipping PackageSetting{429bfdc0 com.test.thalitest/10434} due to missing metadata
,I/ActivityManager( 1022): Force stopping com.example.hello appid=10437 user=0: pkg removed
,D/dalvikvm( 2159): GC_EXPLICIT freed 4692K, 45% free 9621K/17224K, paused 3ms+15ms, total 61ms
,W/ContextImpl( 1260): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/InputReader( 1022): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "sms"
,I/LatinIME:LogUtils( 1196): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,D/dalvikvm( 2192): GC_EXPLICIT freed 2479K, 44% free 9812K/17224K, paused 2ms+3ms, total 110ms
,I/LatinIME:LogUtils( 1196): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,D/dalvikvm( 1022): GC_EXPLICIT freed 1338K, 13% free 17734K/20216K, paused 2ms+14ms, total 102ms
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "smsto"
D/dalvikvm( 1299): GC_EXPLICIT freed 2792K, 33% free 11592K/17224K, paused 2ms+6ms, total 133ms
I/Launcher( 1299): Deferring update until onResume
,W/ContextImpl( 1260): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mms"
W/GeofencerStateMachine( 1214): Ignoring removeGeofence because network location is disabled.
D/VoicemailCleanupService( 3088): Cleaning up data for package: com.example.hello
I/OtaApp  ( 1541): [info] > Updatetime from metadata: 10
D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1541): [debug] > cancelling the previous pending intent set for install later
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mmsto"
I/OtaApp  ( 1541): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1541): publish the event [tag = MOT_OTA event name = LOG]
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "sms"
D/OtaApp  ( 1541): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
D/dalvikvm( 1541): GC_CONCURRENT freed 6313K, 38% free 10806K/17224K, paused 2ms+6ms, total 55ms
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "smsto"
D/OtaApp  ( 1541): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/InternalIcingCorporaPro( 2192): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/Launcher( 1299): Deferring update until onResume
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mms"
,I/ActivityManager( 1022): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3623 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mmsto"
,W/InputMethodManagerService( 1022): Got RemoteException sending setActive(false) notification to pid 3523 uid 10437
W/Binder  ( 1196): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1196): java.lang.NullPointerException
W/Binder  ( 1196): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1196): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1196): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1196): 	at dalvik.system.NativeStart.run(Native Method)
,W/ContextImpl( 3623): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
,I/LatinIME:LogUtils( 1196): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449414044
D/BackupManagerService( 1022): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
V/BackupManagerService( 1022): removePackageParticipantsLocked: uid=10437 #1
,D/PackageBroadcastService( 1379): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1379): Clearing selected account for com.example.hello
,I/LocationSettingsChecker( 1379): Removing dialog suppression flag for package com.example.hello
D/ChimeraCfgMgr( 1379): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1379): Module APK com.google.android.play.games already loaded
,D/gH_CompatibleDatabase( 1379): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1379): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1379): 0 metrics were deleted when clearing package com.example.hello.
,D/gH_CompatibleDatabase( 1379): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/ChimeraCfgMgr( 1379): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1379): Module APK com.google.android.play.games already loaded
,D/gH_CompatibleDatabase( 1379): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1379): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1379): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1379): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1379): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
E/NetworkScheduler.SchedulerReceiver( 1353): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1353): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 1379): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1379): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1379): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1379): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/PeopleContactsSync( 1379): CP2 sync disabled
,I/dalvikvm( 3163): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
,W/dalvikvm( 3163): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3163): VFY: replacing opcode 0x6e at 0x0013
,I/ActivityManager( 1022): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3645 uid=10058 gids={50058}
D/dalvikvm( 1214): GC_EXPLICIT freed 1360K, 41% free 10256K/17224K, paused 3ms+8ms, total 53ms
,I/LatinIME:LogUtils( 1196): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449414044
,E/DataBuffer( 1214): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42747ab8)
I/Icing   ( 1379): doRemovePackageData com.example.hello
,I/InternalIcingCorporaPro( 2192): UpdateCorporaTask done [took 167 ms] updated apps [took 167 ms] 
,D/Documents( 3645): Loading roots for com.android.providers.downloads.documents
I/ActivityManager( 1022): Killing 3320:com.android.calendar/u0a7 (adj 15): empty #9
W/ContextImpl( 1260): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1022): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=3663 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/ActivityManager( 1022): Killing 3396:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1260): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1022): Killing 3374:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1260): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/dalvikvm( 1022): GC_EXPLICIT freed 779K, 13% free 17749K/20216K, paused 7ms+13ms, total 338ms
,D/AndroidRuntime( 3593): Shutting down VM
,D/dalvikvm( 3593): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms
,D/Documents( 3645): Loading roots for com.android.externalstorage.documents
,D/dalvikvm( 3663): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x426fe6a0, skipping init
I/openssl ( 3663): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3663): Crypto mode 0 already enabled
I/ActivityManager( 1022): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3680 uid=10020 gids={50020, 1028, 1015, 1023}
,I/ActivityManager( 1022): Killing 3088:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1260): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/ExternalStorage( 3680): After updating volumes, found 1 active roots
,D/Documents( 3645): Updating roots due to change at content://com.android.externalstorage.documents/root
,D/Documents( 3645): Loading roots for com.android.providers.media.documents
,D/Documents( 3645): Loading roots for com.google.android.apps.docs.storage
,D/Documents( 3645): Update found 7 roots in 196ms
,D/Documents( 3645): Used cached roots for com.android.providers.downloads.documents
,D/Documents( 3645): Loading roots for com.android.externalstorage.documents
,D/Documents( 3645): Used cached roots for com.android.providers.media.documents
D/Documents( 3645): Used cached roots for com.google.android.apps.docs.storage
,D/Documents( 3645): Update found 7 roots in 7ms

```
