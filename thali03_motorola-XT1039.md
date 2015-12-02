#### Test 50388019193a02f_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 3418): 
D/AndroidRuntime( 3418): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3418): CheckJNI is OFF
D/dalvikvm( 3418): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3418): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3418): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3418): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3418): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3418): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3418): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3418): failed to load memtrack module: -2
D/AndroidRuntime( 3418): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1020): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3418
W/WindowManager( 1020): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1020): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3434 uid=10426 gids={50426, 3003, 3001, 3002}
D/AndroidRuntime( 3418): Shutting down VM
D/dalvikvm( 3418): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3434): Binding Chromium to main looper Looper (main, tid 1) {41f9cd88}
I/LibraryLoader( 3434): Expected native library version number "",actual native library version number ""
I/chromium( 3434): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3434): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1020): Message: 20
D/BluetoothManagerService( 1020): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@420d2bd0:true
D/BluetoothAdapter( 3434): 1106973048: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3434): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3434): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3434): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3434): Local Branch: 
I/Adreno-EGL( 3434): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3434): Local Patches: NONE
I/Adreno-EGL( 3434): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3434): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 3434): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3434): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3434): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3434): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3434): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3434): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3434): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3434): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3434): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3434): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 3434): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3434): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3434): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3434): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3434): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3434): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3434): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 3434): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 3434): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3434): Enabling debug mode 0
,W/AwContents( 3434): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3434): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1020): Displayed com.example.hello/.MainActivity,cp,ca,369
I/ActivityManager( 1020): Displayed com.example.hello/.MainActivity: +337ms (total +369ms)
,I/chromium( 3434): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 3434): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/JsMessageQueue( 3434): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3434): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x41fa1030
,D/dalvikvm( 3434): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x41fa1030
,D/jxcore_app_log( 3434): JniHelper::setJavaVM(0x415e9fa8), pthread_self() = 1610510624
,D/JX-Cordova( 3434): jxcore cordova android initializing
,W/jxcore-log( 3434): Initializing JXcore engine
,W/jxcore-log( 3434): JXcore engine is ready
,W/jxcore-log( 3434): Starting JXcore engine
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,W/jxcore-log( 3434): Platform android
W/jxcore-log( 3434): 
,W/jxcore-log( 3434): Process ARCH arm
W/jxcore-log( 3434): 
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
,I/jxcore-log( 3434): JXcore Cordova bridge is ready!
I/jxcore-log( 3434): 
,W/jxcore-log( 3434): JXcore engine is started
,E/jxcore-log( 3434): >> motorola-XT1039
E/jxcore-log( 3434): 
,I/jxcore-log( 3434): Total memory 893136896
I/jxcore-log( 3434): 
I/jxcore-log( 3434): Free memory 31809536
I/jxcore-log( 3434): 
,I/jxcore-log( 3434): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3434): 
,I/jxcore-log( 3434): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3434): 
,I/jxcore-log( 3434): userPath [ 'www' ]
I/jxcore-log( 3434): 
,I/jxcore-log( 3434): Size 720 1184
I/jxcore-log( 3434): 
,I/jxcore-log( 3434): Screen Brightness 10
I/jxcore-log( 3434): 
,E/jxcore-log( 3434): Dummy Error Log.
E/jxcore-log( 3434): 
,I/jxcore-log( 3434): getBuffer is called!!!!
I/jxcore-log( 3434): 
,I/MMApiBackOffService( 1539): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1539): MMApiBackOffService told us it's okay to retry the waiting requests: 2
,D/MMApiWebService( 1539): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1539): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1539): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1539): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1539): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1539): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1539): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiBackOffService( 1539): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1539): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1539): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1539): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 60000
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1539): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,D/BluetoothManagerService( 1020): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1020): Disable(): Service is not Connected Or Bluetooth is not enabled
,D/WifiService( 1020): New client listening to asynchronous messages
,D/WifiService( 1020): setWifiEnabled: false pid=3434, uid=10426
,E/WifiService( 1020): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3434): ****TEST TOOK:  5054  ms ****
I/jxcore-log( 3434): 
I/jxcore-log( 3434): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3434): 
,D/AndroidRuntime( 3498): 
D/AndroidRuntime( 3498): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3498): CheckJNI is OFF
,D/dalvikvm( 3498): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 3498): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3498): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3498): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 3498): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 3498): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,E/memtrack( 3498): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 3498): failed to load memtrack module: -2
,D/AndroidRuntime( 3498): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1020): Force stopping com.example.hello appid=10426 user=-1: uninstall pkg
,I/ActivityManager( 1020): Killing 3434:com.example.hello/u0a426 (adj 0): stop com.example.hello
,W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1020):   Force finishing activity ActivityRecord{428f1ee8 u0 com.example.hello/.MainActivity t3}
,I/WindowState( 1020): WIN DEATH: Window{420dd638 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService( 1020): Client connection lost with reason: 4
,W/PackageSettings( 1020): Skipping PackageSetting{4225e118 com.test.thalitest/10425} due to missing metadata
,W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager( 1020): Force stopping com.example.hello appid=10426 user=0: pkg removed
,D/dalvikvm( 2161): GC_EXPLICIT freed 2402K, 44% free 9770K/17224K, paused 2ms+3ms, total 45ms
,I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
,I/LatinIME:LogUtils( 1186): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449078442
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
,I/LatinIME:LogUtils( 1186): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,D/dalvikvm( 2126): GC_EXPLICIT freed 4696K, 45% free 9626K/17224K, paused 16ms+5ms, total 64ms
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
I/LatinIME:LogUtils( 1186): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
W/GeofencerStateMachine( 1200): Ignoring removeGeofence because network location is disabled.
D/VoicemailCleanupService( 3002): Cleaning up data for package: com.example.hello
D/dalvikvm( 1299): GC_EXPLICIT freed 2791K, 33% free 11591K/17224K, paused 2ms+5ms, total 120ms
,I/Launcher( 1299): Deferring update until onResume
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
,I/OtaApp  ( 1539): [info] > Updatetime from metadata: 10
,D/Checkin ( 1539): publish the event [tag = MOT_OTA event name = LOG]
,D/dalvikvm( 1020): GC_EXPLICIT freed 1507K, 15% free 17749K/20760K, paused 7ms+10ms, total 137ms
,D/dalvikvm( 1020): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/OtaApp  ( 1539): [debug] > cancelling the previous pending intent set for install later
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
I/OtaApp  ( 1539): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1539): publish the event [tag = MOT_OTA event name = LOG]
,I/Launcher( 1299): Deferring update until onResume
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
,I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
,D/OtaApp  ( 1539): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1539): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/LatinIME:LogUtils( 1186): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449078442
,I/InternalIcingCorporaPro( 2161): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,W/InputMethodManagerService( 1020): Got RemoteException sending setActive(false) notification to pid 3434 uid 10426
,W/Binder  ( 1186): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1186): java.lang.NullPointerException
W/Binder  ( 1186): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1186): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1186): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1186): 	at dalvik.system.NativeStart.run(Native Method)
I/ActivityManager( 1020): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3529 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,D/dalvikvm(  278): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 3ms+2ms, total 23ms
,W/ContextImpl( 3529): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
,D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
,D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
,D/PackageBroadcastService( 1388): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1388): Clearing selected account for com.example.hello
D/ChimeraCfgMgr( 1388): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1388): Module APK com.google.android.play.games already loaded
,D/BackupManagerService( 1020): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,V/BackupManagerService( 1020): removePackageParticipantsLocked: uid=10426 #1
D/ChimeraCfgMgr( 1388): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1388): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1388): Removing dialog suppression flag for package com.example.hello
,E/NetworkScheduler.SchedulerReceiver( 1335): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1335): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 1388): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1388): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1388): 0 metrics were deleted when clearing package com.example.hello.
,D/gH_CompatibleDatabase( 1388): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/dalvikvm( 1200): GC_EXPLICIT freed 1978K, 41% free 10258K/17224K, paused 4ms+6ms, total 42ms
D/gH_CompatibleDatabase( 1388): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1388): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1388): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,I/PeopleContactsSync( 1388): CP2 sync disabled
,D/dalvikvm( 1335): GC_EXPLICIT freed 913K, 39% free 10526K/17224K, paused 2ms+10ms, total 50ms
,D/gH_CompatibleDatabase( 1388): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1388): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1388): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1388): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1388): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1388): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,E/DataBuffer( 1200): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@422072b0)
,I/dalvikvm( 3079): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3079): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3079): VFY: replacing opcode 0x6e at 0x0013
I/ActivityManager( 1020): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3553 uid=10058 gids={50058}
,I/ActivityManager( 1020): Killing 3223:com.android.calendar/u0a7 (adj 15): empty #9
I/Icing   ( 1388): doRemovePackageData com.example.hello
,I/InternalIcingCorporaPro( 2161): UpdateCorporaTask done [took 174 ms] updated apps [took 174 ms] 
W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1020): GC_EXPLICIT freed 504K, 15% free 17800K/20760K, paused 14ms+14ms, total 299ms
,D/Documents( 3553): Loading roots for com.android.providers.downloads.documents
,D/AndroidRuntime( 3498): Shutting down VM
,D/dalvikvm( 3498): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
I/ActivityManager( 1020): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=3567 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
I/ActivityManager( 1020): Killing 3310:com.google.android.partnersetup/u0a25 (adj 15): empty #9
W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1020): Killing 3284:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Documents( 3553): Loading roots for com.android.externalstorage.documents
,D/dalvikvm( 3567): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f9b480, skipping init
I/openssl ( 3567): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3567): Crypto mode 0 already enabled
I/ActivityManager( 1020): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3584 uid=10020 gids={50020, 1028, 1015, 1023}
,I/ActivityManager( 1020): Killing 3002:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/ExternalStorage( 3584): After updating volumes, found 1 active roots
,D/Documents( 3553): Updating roots due to change at content://com.android.externalstorage.documents/root
,D/Documents( 3553): Loading roots for com.android.providers.media.documents
,D/Documents( 3553): Loading roots for com.google.android.apps.docs.storage
,D/Documents( 3553): Update found 7 roots in 186ms
D/Documents( 3553): Used cached roots for com.android.providers.downloads.documents
,D/Documents( 3553): Loading roots for com.android.externalstorage.documents
D/Documents( 3553): Used cached roots for com.android.providers.media.documents
D/Documents( 3553): Used cached roots for com.google.android.apps.docs.storage
,D/Documents( 3553): Update found 7 roots in 7ms

```
