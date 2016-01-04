#### Test 50388019831b9e1_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 3487): 
D/AndroidRuntime( 3487): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3487): CheckJNI is OFF
D/dalvikvm( 3487): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3487): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3487): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3487): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3487): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3487): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3487): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3487): failed to load memtrack module: -2
D/AndroidRuntime( 3487): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1018): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3487
W/WindowManager( 1018): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1018): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3503 uid=10509 gids={50509, 3003, 3001, 3002}
D/AndroidRuntime( 3487): Shutting down VM
D/dalvikvm( 3487): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
D/dalvikvm(  278): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 1ms+3ms, total 21ms
W/ContextImpl( 1220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 23ms
D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 25ms
V/WebViewChromiumFactoryProvider( 3503): Binding Chromium to main looper Looper (main, tid 1) {421f7a70}
I/LibraryLoader( 3503): Expected native library version number "",actual native library version number ""
I/chromium( 3503): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3503): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1018): Message: 20
D/BluetoothManagerService( 1018): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42a6e060:true
D/BluetoothAdapter( 3503): 1109442624: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3503): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3503): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3503): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3503): Local Branch: 
I/Adreno-EGL( 3503): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3503): Local Patches: NONE
I/Adreno-EGL( 3503): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3503): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 3503): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3503): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3503): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3503): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3503): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3503): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3503): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3503): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3503): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3503): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 3503): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3503): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3503): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3503): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3503): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3503): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3503): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 3503): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 3503): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3503): Enabling debug mode 0
,W/AwContents( 3503): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3503): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1018): Displayed com.example.hello/.MainActivity,cp,ca,377
I/ActivityManager( 1018): Displayed com.example.hello/.MainActivity: +344ms (total +377ms)
,E/AndroidProtocolHandler( 3503): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/chromium( 3503): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 3503): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3503): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x421fbef8
,D/dalvikvm( 3503): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x421fbef8
,D/jxcore_app_log( 3503): JniHelper::setJavaVM(0x41910f78), pthread_self() = 1610654424
,D/JX-Cordova( 3503): jxcore cordova android initializing
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
,W/jxcore-log( 3503): Initializing JXcore engine
W/jxcore-log( 3503): JXcore engine is ready
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,W/jxcore-log( 3503): Starting JXcore engine
,W/jxcore-log( 3503): Platform android
W/jxcore-log( 3503): 
,W/jxcore-log( 3503): Process ARCH arm
W/jxcore-log( 3503): 
,I/jxcore-log( 3503): JXcore Cordova bridge is ready!
I/jxcore-log( 3503): 
,W/jxcore-log( 3503): JXcore engine is started
,E/jxcore-log( 3503): >> motorola-XT1039
E/jxcore-log( 3503): 
,I/jxcore-log( 3503): Total memory 893136896
I/jxcore-log( 3503): 
,I/jxcore-log( 3503): Free memory 34471936
I/jxcore-log( 3503): 
I/jxcore-log( 3503): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3503): 
,I/jxcore-log( 3503): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3503): 
,I/jxcore-log( 3503): userPath [ 'www' ]
I/jxcore-log( 3503): 
,I/jxcore-log( 3503): Size 720 1184
I/jxcore-log( 3503): 
,I/jxcore-log( 3503): Screen Brightness 10
I/jxcore-log( 3503): 
,E/jxcore-log( 3503): Dummy Error Log.
E/jxcore-log( 3503): 
,I/jxcore-log( 3503): getBuffer is called!!!!
I/jxcore-log( 3503): 
,I/MMApiBackOffService( 1531): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1531): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1531): MMApiBackOffService told us it's okay to retry the waiting requests: 3
D/MMApiWebService( 1531): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1531): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1531): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1531): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 1531): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1531): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1531): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1531): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiBackOffService( 1531): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 1531): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1531): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1531): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1531): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1531): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1531): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 60000
,D/Checkin ( 1531): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1531): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1531): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1531): doRequest(): polling manager says we're not connected, returning with an error: 
D/Checkin ( 1531): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1531): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1531): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1531): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 60000
,D/Checkin ( 1531): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1531): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1531): publish the event [tag = MOT_CCE event name = LOG]
,D/BluetoothManagerService( 1018): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1018): Disable(): Service is not Connected Or Bluetooth is not enabled
,D/WifiService( 1018): New client listening to asynchronous messages
,D/WifiService( 1018): setWifiEnabled: false pid=3503, uid=10509
,E/WifiService( 1018): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3503): ****TEST TOOK:  5049  ms ****
I/jxcore-log( 3503): 
I/jxcore-log( 3503): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3503): 
,D/AndroidRuntime( 3567): 
D/AndroidRuntime( 3567): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3567): CheckJNI is OFF
,D/dalvikvm( 3567): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 3567): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3567): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3567): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 3567): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 3567): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,E/memtrack( 3567): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 3567): failed to load memtrack module: -2
,D/AndroidRuntime( 3567): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1018): Force stopping com.example.hello appid=10509 user=-1: uninstall pkg
,I/ActivityManager( 1018): Killing 3503:com.example.hello/u0a509 (adj 0): stop com.example.hello
,W/ContextImpl( 1220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1018):   Force finishing activity ActivityRecord{42bb7070 u0 com.example.hello/.MainActivity t3}
,I/WindowState( 1018): WIN DEATH: Window{422bddb0 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService( 1018): Client connection lost with reason: 4
,W/PackageSettings( 1018): Skipping PackageSetting{424b7c98 com.test.thalitest/10507} due to missing metadata
,I/ActivityManager( 1018): Force stopping com.example.hello appid=10509 user=0: pkg removed
,D/dalvikvm( 2089): GC_EXPLICIT freed 4708K, 45% free 9623K/17224K, paused 2ms+5ms, total 38ms
,D/dalvikvm( 1366): GC_EXPLICIT freed 444K, 33% free 11608K/17224K, paused 3ms+5ms, total 71ms
,D/dalvikvm( 2121): GC_EXPLICIT freed 3764K, 42% free 10100K/17224K, paused 20ms+4ms, total 81ms
,W/ContextImpl( 1220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1202): Ignoring removeGeofence because network location is disabled.
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
,I/LatinIME:LogUtils( 1185): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,W/ContextImpl( 1220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/LatinIME:LogUtils( 1185): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
D/VoicemailCleanupService( 3063): Cleaning up data for package: com.example.hello
I/OtaApp  ( 1531): [info] > Updatetime from metadata: 10
D/Checkin ( 1531): publish the event [tag = MOT_OTA event name = LOG]
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
,D/dalvikvm( 1281): GC_EXPLICIT freed 2788K, 33% free 11591K/17224K, paused 5ms+7ms, total 71ms
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
,D/OtaApp  ( 1531): [debug] > cancelling the previous pending intent set for install later
,I/LatinIME:LogUtils( 1185): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1451921697
,I/OtaApp  ( 1531): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1531): publish the event [tag = MOT_OTA event name = LOG]
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
I/Launcher( 1281): Deferring update until onResume
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
,D/dalvikvm( 1018): GC_EXPLICIT freed 1480K, 15% free 17892K/20808K, paused 4ms+9ms, total 117ms
,D/dalvikvm( 1018): WAIT_FOR_CONCURRENT_GC blocked 88ms
,D/OtaApp  ( 1531): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
I/Launcher( 1281): Deferring update until onResume
,I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
,D/OtaApp  ( 1531): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,W/InputMethodManagerService( 1018): Got RemoteException sending setActive(false) notification to pid 3503 uid 10509
W/Binder  ( 1185): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1185): java.lang.NullPointerException
W/Binder  ( 1185): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1185): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1185): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1185): 	at dalvik.system.NativeStart.run(Native Method)
D/dalvikvm( 1531): GC_CONCURRENT freed 6304K, 38% free 10780K/17224K, paused 2ms+5ms, total 48ms
I/InternalIcingCorporaPro( 2121): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/ActivityManager( 1018): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3599 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
,W/ContextImpl( 3599): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
,I/LatinIME:LogUtils( 1185): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1451921697
I/dalvikvm( 3127): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3127): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3127): VFY: replacing opcode 0x6e at 0x0013
,D/PackageBroadcastService( 1366): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1366): Clearing selected account for com.example.hello
,I/LocationSettingsChecker( 1366): Removing dialog suppression flag for package com.example.hello
,D/ChimeraCfgMgr( 1366): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1366): Module APK com.google.android.play.games already loaded
,D/gH_CompatibleDatabase( 1366): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1366): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1366): 0 metrics were deleted when clearing package com.example.hello.
,D/gH_CompatibleDatabase( 1366): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/ChimeraCfgMgr( 1366): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1366): Module APK com.google.android.play.games already loaded
D/gH_CompatibleDatabase( 1366): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1366): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1366): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,E/NetworkScheduler.SchedulerReceiver( 1345): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1345): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 1366): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1366): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1366): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
I/Icing   ( 1366): doRemovePackageData com.example.hello
,D/gH_CompatibleDatabase( 1366): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1366): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1366): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
V/BackupManagerService( 1018): removePackageParticipantsLocked: uid=10509 #1
,I/ActivityManager( 1018): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3623 uid=10058 gids={50058}
,I/InternalIcingCorporaPro( 2121): UpdateCorporaTask done [took 167 ms] updated apps [took 167 ms] 
,D/Documents( 3623): Loading roots for com.android.providers.downloads.documents
,I/ActivityManager( 1018): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=3638 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/ActivityManager( 1018): Killing 3311:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1018): Killing 3350:com.android.defcontainer/u0a13 (adj 15): empty #9
,I/ActivityManager( 1018): Killing 3381:com.google.android.partnersetup/u0a25 (adj 15): empty #10
,W/ContextImpl( 1220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 1018): GC_EXPLICIT freed 584K, 15% free 17801K/20808K, paused 8ms+15ms, total 316ms
,D/AndroidRuntime( 3567): Shutting down VM
,D/dalvikvm( 3567): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms
,D/Documents( 3623): Loading roots for com.android.externalstorage.documents
,D/dalvikvm( 3638): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x421f6678, skipping init
I/openssl ( 3638): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3638): Crypto mode 0 already enabled
I/ActivityManager( 1018): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3657 uid=10020 gids={50020, 1028, 1015, 1023}
,I/ActivityManager( 1018): Killing 3063:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1220): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/ExternalStorage( 3657): After updating volumes, found 1 active roots
,D/Documents( 3623): Updating roots due to change at content://com.android.externalstorage.documents/root
,D/Documents( 3623): Loading roots for com.android.providers.media.documents
,D/Documents( 3623): Loading roots for com.google.android.apps.docs.storage
,D/Documents( 3623): Update found 7 roots in 197ms
D/Documents( 3623): Used cached roots for com.android.providers.downloads.documents
,D/Documents( 3623): Loading roots for com.android.externalstorage.documents
D/Documents( 3623): Used cached roots for com.android.providers.media.documents
D/Documents( 3623): Used cached roots for com.google.android.apps.docs.storage
,D/Documents( 3623): Update found 7 roots in 7ms

```
