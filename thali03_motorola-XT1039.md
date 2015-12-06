#### Test 50242285576d0b0_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
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
E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 3422): 
D/AndroidRuntime( 3422): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3422): CheckJNI is OFF
D/dalvikvm( 3422): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3422): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3422): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3422): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3422): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3422): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3422): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3422): failed to load memtrack module: -2
D/AndroidRuntime( 3422): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3422
W/WindowManager( 1019): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1019): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3438 uid=10436 gids={50436, 3003, 3001, 3002}
D/AndroidRuntime( 3422): Shutting down VM
D/dalvikvm( 3422): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
W/ContextImpl( 1245): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1245): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/dalvikvm(  277): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 3ms+3ms, total 27ms
D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 19ms
D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 17ms
V/WebViewChromiumFactoryProvider( 3438): Binding Chromium to main looper Looper (main, tid 1) {41f5cad0}
I/LibraryLoader( 3438): Expected native library version number "",actual native library version number ""
I/chromium( 3438): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3438): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42a1a348:true
D/BluetoothAdapter( 3438): 1106710688: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3438): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3438): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3438): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3438): Local Branch: 
I/Adreno-EGL( 3438): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3438): Local Patches: NONE
I/Adreno-EGL( 3438): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
W/chromium( 3438): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 3438): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3438): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3438): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3438): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3438): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3438): VFY: replacing opcode 0x6e at 0x0008
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
W/dalvikvm( 3438): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3438): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3438): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3438): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3438): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3438): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3438): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3438): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 3438): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3438): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3438): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3438): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3438): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3438): Enabling debug mode 0
,W/AwContents( 3438): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3438): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1019): Displayed com.example.hello/.MainActivity,cp,ca,382
I/ActivityManager( 1019): Displayed com.example.hello/.MainActivity: +354ms (total +383ms)
,I/chromium( 3438): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 3438): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/JsMessageQueue( 3438): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3438): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x41f60f58
,D/dalvikvm( 3438): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x41f60f58
,D/jxcore_app_log( 3438): JniHelper::setJavaVM(0x415a8fa8), pthread_self() = 1609476800
,D/JX-Cordova( 3438): jxcore cordova android initializing
,W/jxcore-log( 3438): Initializing JXcore engine
,W/jxcore-log( 3438): JXcore engine is ready
,W/jxcore-log( 3438): Starting JXcore engine
,W/jxcore-log( 3438): Platform android
W/jxcore-log( 3438): 
,W/jxcore-log( 3438): Process ARCH arm
W/jxcore-log( 3438): 
,I/jxcore-log( 3438): JXcore Cordova bridge is ready!
I/jxcore-log( 3438): 
,W/jxcore-log( 3438): JXcore engine is started
,E/jxcore-log( 3438): >> motorola-XT1039
E/jxcore-log( 3438): 
,I/jxcore-log( 3438): Total memory 893136896
I/jxcore-log( 3438): 
I/jxcore-log( 3438): Free memory 32739328
I/jxcore-log( 3438): 
I/jxcore-log( 3438): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3438): 
,I/jxcore-log( 3438): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3438): 
,I/jxcore-log( 3438): userPath [ 'www' ]
I/jxcore-log( 3438): 
,I/jxcore-log( 3438): Size 720 1184
I/jxcore-log( 3438): 
,I/jxcore-log( 3438): Screen Brightness 10
I/jxcore-log( 3438): 
,E/jxcore-log( 3438): Dummy Error Log.
E/jxcore-log( 3438): 
,I/jxcore-log( 3438): getBuffer is called!!!!
I/jxcore-log( 3438): 
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
,I/MMApiBackOffService( 1542): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1542): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1542): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1542): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1542): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1542): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1542): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/MMApiWebService( 1542): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1542): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1542): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1542): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1542): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 1542): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1542): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1542): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1542): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1542): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1542): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 60000
,D/Checkin ( 1542): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1542): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/MMApiWebService( 1542): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1542): MMApiWebService told us not to continue at the moment with this request: devices.json
,I/MMApiWebService( 1542): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1542): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1542): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1542): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 60000
,D/Checkin ( 1542): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1542): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1542): publish the event [tag = MOT_CCE event name = LOG]
,D/dalvikvm( 1542): GC_CONCURRENT freed 6290K, 38% free 10773K/17224K, paused 4ms+4ms, total 53ms
,D/BluetoothManagerService( 1019): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1019): Disable(): Service is not Connected Or Bluetooth is not enabled
,D/WifiService( 1019): New client listening to asynchronous messages
,D/WifiService( 1019): setWifiEnabled: false pid=3438, uid=10436
,E/WifiService( 1019): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3438): ****TEST TOOK:  5051  ms ****
I/jxcore-log( 3438): 
I/jxcore-log( 3438): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3438): 
,D/AndroidRuntime( 3504): 
D/AndroidRuntime( 3504): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3504): CheckJNI is OFF
,D/dalvikvm( 3504): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 3504): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3504): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3504): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 3504): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 3504): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
,E/memtrack( 3504): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 3504): failed to load memtrack module: -2
,D/AndroidRuntime( 3504): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager( 1019): Force stopping com.example.hello appid=10436 user=-1: uninstall pkg
,I/ActivityManager( 1019): Killing 3438:com.example.hello/u0a436 (adj 0): stop com.example.hello
,W/ContextImpl( 1245): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019):   Force finishing activity ActivityRecord{422ed288 u0 com.example.hello/.MainActivity t3}
,I/WindowState( 1019): WIN DEATH: Window{42585430 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService( 1019): Client connection lost with reason: 4
,W/PackageSettings( 1019): Skipping PackageSetting{4221b628 com.test.thalitest/10434} due to missing metadata
,W/ContextImpl( 1245): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager( 1019): Force stopping com.example.hello appid=10436 user=0: pkg removed
,W/ContextImpl( 1245): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
I/OtaApp  ( 1542): [info] > Updatetime from metadata: 10
D/Checkin ( 1542): publish the event [tag = MOT_OTA event name = LOG]
I/LatinIME:LogUtils( 1184): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1184): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1184): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449411032
,W/GeofencerStateMachine( 1199): Ignoring removeGeofence because network location is disabled.
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,D/OtaApp  ( 1542): [debug] > cancelling the previous pending intent set for install later
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
I/OtaApp  ( 1542): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1542): publish the event [tag = MOT_OTA event name = LOG]
,D/dalvikvm( 2138): GC_EXPLICIT freed 4695K, 45% free 9622K/17224K, paused 8ms+9ms, total 99ms
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
D/VoicemailCleanupService( 3031): Cleaning up data for package: com.example.hello
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
D/OtaApp  ( 1542): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/dalvikvm( 2169): GC_EXPLICIT freed 4214K, 42% free 10131K/17224K, paused 2ms+5ms, total 63ms
,D/dalvikvm( 1019): GC_EXPLICIT freed 1581K, 15% free 17806K/20784K, paused 3ms+26ms, total 164ms
,D/OtaApp  ( 1542): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/dalvikvm( 1296): GC_EXPLICIT freed 2792K, 33% free 11594K/17224K, paused 2ms+11ms, total 174ms
,I/Launcher( 1296): Deferring update until onResume
,I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
,I/InternalIcingCorporaPro( 2169): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/ActivityManager( 1019): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3536 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
I/LatinIME:LogUtils( 1184): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449411032
,I/Launcher( 1296): Deferring update until onResume
W/ContextImpl( 3536): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
,D/PackageBroadcastService( 1382): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1382): Clearing selected account for com.example.hello
,D/ChimeraCfgMgr( 1382): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1382): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1382): Removing dialog suppression flag for package com.example.hello
,D/ChimeraCfgMgr( 1382): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1382): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1357): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1357): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/dalvikvm( 3111): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3111): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 3111): VFY: replacing opcode 0x6e at 0x0013
,D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/ActivityManager( 1019): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3555 uid=10058 gids={50058}
,V/BackupManagerService( 1019): removePackageParticipantsLocked: uid=10436 #1
D/gH_CompatibleDatabase( 1382): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1382): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1382): 0 metrics were deleted when clearing package com.example.hello.
D/gH_CompatibleDatabase( 1382): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,I/PeopleContactsSync( 1382): CP2 sync disabled
,I/Icing   ( 1382): doRemovePackageData com.example.hello
,D/gH_CompatibleDatabase( 1382): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1382): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1382): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/dalvikvm( 1199): GC_EXPLICIT freed 1955K, 41% free 10257K/17224K, paused 3ms+9ms, total 64ms
D/gH_CompatibleDatabase( 1382): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1382): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1382): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1382): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1382): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1382): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,W/InputMethodManagerService( 1019): Got RemoteException sending setActive(false) notification to pid 3438 uid 10436
W/Binder  ( 1184): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1184): java.lang.NullPointerException
W/Binder  ( 1184): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1184): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1184): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1184): 	at dalvik.system.NativeStart.run(Native Method)
E/DataBuffer( 1199): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42168e68)
,I/InternalIcingCorporaPro( 2169): UpdateCorporaTask done [took 173 ms] updated apps [took 173 ms] 
,I/ActivityManager( 1019): Killing 3169:com.android.providers.calendar/u0a8 (adj 15): empty #9
,W/ContextImpl( 1245): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Documents( 3555): Loading roots for com.android.providers.downloads.documents
,I/ActivityManager( 1019): Killing 3317:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1245): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=3574 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
,I/ActivityManager( 1019): Killing 3287:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1245): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/dalvikvm( 1019): GC_EXPLICIT freed 499K, 15% free 17753K/20784K, paused 11ms+16ms, total 281ms
,D/AndroidRuntime( 3504): Shutting down VM
,D/dalvikvm( 3504): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+1ms, total 2ms
,D/Documents( 3555): Loading roots for com.android.externalstorage.documents
,D/dalvikvm( 3574): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f5b690, skipping init
I/openssl ( 3574): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3574): Crypto mode 0 already enabled
,I/ActivityManager( 1019): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3590 uid=10020 gids={50020, 1028, 1015, 1023}
,I/ActivityManager( 1019): Killing 3031:android.process.acore/u0a10 (adj 15): empty #9
,W/ContextImpl( 1245): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/ExternalStorage( 3590): After updating volumes, found 1 active roots
,D/Documents( 3555): Updating roots due to change at content://com.android.externalstorage.documents/root
,D/Documents( 3555): Loading roots for com.android.providers.media.documents
,D/Documents( 3555): Loading roots for com.google.android.apps.docs.storage
,D/Documents( 3555): Update found 7 roots in 194ms
,D/Documents( 3555): Used cached roots for com.android.providers.downloads.documents
,D/Documents( 3555): Loading roots for com.android.externalstorage.documents
,D/Documents( 3555): Used cached roots for com.android.providers.media.documents
D/Documents( 3555): Used cached roots for com.google.android.apps.docs.storage
,D/Documents( 3555): Update found 7 roots in 7ms

```
