#### Test 50242285feafdeb_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1016): sending alarm Alarm{42890798 type 3 android}
,--------- beginning of /dev/log/main
D/AndroidRuntime( 3511): 
D/AndroidRuntime( 3511): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3511): CheckJNI is OFF
D/dalvikvm( 3511): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3511): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3511): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3511): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3511): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3511): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3511): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3511): failed to load memtrack module: -2
D/AndroidRuntime( 3511): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1016): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3511
W/WindowManager( 1016): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1016): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3527 uid=10543 gids={50543, 3003, 3001, 3002}
D/AndroidRuntime( 3511): Shutting down VM
D/dalvikvm( 3511): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+1ms, total 3ms
W/ContextImpl( 1245): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1245): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3527): Binding Chromium to main looper Looper (main, tid 1) {41f41590}
I/LibraryLoader( 3527): Expected native library version number "",actual native library version number ""
I/chromium( 3527): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3527): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1016): Message: 20
D/BluetoothManagerService( 1016): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@420e1440:true
D/BluetoothAdapter( 3527): 1106601136: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3527): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3527): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3527): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3527): Local Branch: 
I/Adreno-EGL( 3527): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3527): Local Patches: NONE
I/Adreno-EGL( 3527): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3527): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 3527): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3527): VFY: unable to resolve virtual method 172: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3527): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3527): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3527): VFY: unable to resolve virtual method 167: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3527): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3527): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3527): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3527): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3527): VFY: unable to resolve virtual method 225: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 3527): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3527): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3527): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3527): VFY: unable to resolve virtual method 183: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3527): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3527): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3527): VFY: unable to resolve virtual method 188: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 3527): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 3527): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3527): Enabling debug mode 0
,W/AwContents( 3527): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3527): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1016): Displayed com.example.hello/.MainActivity,cp,ca,340
I/ActivityManager( 1016): Displayed com.example.hello/.MainActivity: +316ms (total +340ms)
,I/chromium( 3527): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 3527): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 3527): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/dalvikvm( 3527): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x41f45a18
,D/dalvikvm( 3527): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x41f45a18
,D/jxcore_app_log( 3527): JniHelper::setJavaVM(0x41596fa8), pthread_self() = 1610597744
,W/jxcore-log( 3527): Initializing JXcore engine
,W/jxcore-log( 3527): JXcore engine is ready
,W/jxcore-log( 3527): Starting JXcore engine
,W/jxcore-log( 3527): Platform android
W/jxcore-log( 3527): 
,W/jxcore-log( 3527): Process ARCH arm
W/jxcore-log( 3527): 
,I/jxcore-log( 3527): JXcore Cordova bridge is ready!
I/jxcore-log( 3527): 
,W/jxcore-log( 3527): JXcore engine is started
,E/jxcore  ( 3527): Error!: No such native module /data/data/com.example.hello/files/www/jxcore/app.js
E/jxcore  ( 3527): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/MDMCTBK (  284): NetlinkHandler, power_supply subsys
I/MDMCTBK (  284): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  284): checkDefaultInst, current pid is = 284
I/MDMCTBK (  284): checkDefaultInst, pid match
I/MDMCTBK (  284): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  284): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  284): MdmCutbackHndler,Could not open ''
,I/MMApiBackOffService( 1537): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1537): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1537): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1537): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1537): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1537): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,D/MMApiWebService( 1537): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1537): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 1537): publish the event [tag = MOT_CCE event name = LOG]
,E/MMApiProvisionService( 1537): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1537): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiBackOffService( 1537): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 1537): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1537): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1537): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1537): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1537): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1537): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 60000
,D/Checkin ( 1537): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1537): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/MMApiWebService( 1537): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/Checkin ( 1537): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1537): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1537): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1537): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1537): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 60000
,D/Checkin ( 1537): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1537): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1537): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1016): sending alarm Alarm{4285aa50 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{42a099a8 type 2 com.google.android.gms}
,E/global frequency( 1537): no tags to log
,D/Checkin ( 1537): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1537): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 1537): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 1537): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 1537): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 1537): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/dalvikvm( 1537): GC_CONCURRENT freed 6302K, 37% free 10885K/17224K, paused 4ms+7ms, total 112ms
,I/global frequency( 1537): BcsDSCheckin.events found events 303
,D/Checkin ( 1537): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 1537): BcsDSDropBox.events found events 36
,D/Checkin ( 1537): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 1537): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 1537): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 1537): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1537): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1537): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 1537): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 1537): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 1537): unknown error code mapping for: 0
I/global frequency( 1537): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 1537): publish the event [tag = MOT_CHECKIN event name = LOG]
,V/AlarmManager( 1016): sending alarm Alarm{429ccdc0 type 3 android}
,I/MMApiBackOffService( 1537): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1537): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1537): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1537): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1537): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1537): doRequest(): polling manager says we're not connected, returning with an error: 
D/MMApiWebService( 1537): doRequest(): polling manager says we're not connected, returning with an error: devices.json
I/MMApiWebService( 1537): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,E/MMApiProvisionService( 1537): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1537): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1537): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1537): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 1537): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1537): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1537): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1537): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1537): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1537): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1537): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1537): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1537): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1537): doRequest(): polling manager says we're not connected, returning with an error: 
D/Checkin ( 1537): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1537): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1537): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1537): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 300000
,D/Checkin ( 1537): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1537): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1537): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1016): sending alarm Alarm{42a06890 type 2 com.google.android.gms}
,I/VacuumService( 1198): Vacuum at: now=1452552614645 tag=VacuumService
,V/AlarmManager( 1016): sending alarm Alarm{429aa118 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{429aa1f0 type 3 android}
,TIME-OUT KILL (timeout was 150000ms),D/AndroidRuntime( 3612): 
D/AndroidRuntime( 3612): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3612): CheckJNI is OFF
D/dalvikvm( 3612): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3612): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3612): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3612): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3612): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3612): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3612): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3612): failed to load memtrack module: -2
D/AndroidRuntime( 3612): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1016): Force stopping com.example.hello appid=10543 user=-1: uninstall pkg
I/ActivityManager( 1016): Killing 3527:com.example.hello/u0a543 (adj 0): stop com.example.hello
W/ContextImpl( 1245): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/WindowState( 1016): WIN DEATH: Window{429c2728 u0 com.example.hello/com.example.hello.MainActivity}
I/ActivityManager( 1016):   Force finishing activity ActivityRecord{42981450 u0 com.example.hello/.MainActivity t3}
W/InputDispatcher( 1016): channel '42989160 com.example.hello/com.example.hello.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher( 1016): channel '42989160 com.example.hello/com.example.hello.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
I/WindowState( 1016): WIN DEATH: Window{42989160 u0 com.example.hello/com.example.hello.MainActivity}
W/InputDispatcher( 1016): Attempted to unregister already unregistered input channel '42989160 com.example.hello/com.example.hello.MainActivity (server)'
W/PackageSettings( 1016): Skipping PackageSetting{4220b600 com.test.thalitest/10540} due to missing metadata
I/SFPerfTracer(  286):      triggers: (rate: 2:33) (compose: 0:4) (post: 0:1) (render: 0:5) (0:109 frames) (1:546)
D/SFPerfTracer(  286):        layers: (0:13) (FocusedStackFrame: 0:10)* (StatusBar: 0:200)* (NavigationBar: 0:36)* (com.android.systemui.ImageWallpaper: 0:6)* (DimLayer: 0:1)* (Starting com.motorola.ccc.ota: 0:34)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.InstallationActivity: 0:18)* (ElectronBeam: 0:27)* (com.example.hello/com.example.hello.MainActivity: 0:4)* (com.example.hello/com.example.hello.MainActivity: 0:4)* 
W/ContextImpl( 1245): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/ActivityManager( 1016): Force stopping com.example.hello appid=10543 user=0: pkg removed
I/ActivityManager( 1016):   Force finishing activity ActivityRecord{42981450 u0 com.example.hello/.MainActivity t3 f}
W/ActivityManager( 1016): Duplicate finish request for ActivityRecord{42981450 u0 com.example.hello/.MainActivity t3 f}
W/ContextImpl( 1245): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/InputReader( 1016): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "sms"
I/OtaApp  ( 1537): [info] > Updatetime from metadata: 10
D/Checkin ( 1537): publish the event [tag = MOT_OTA event name = LOG]
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "smsto"
I/LatinIME:LogUtils( 1183): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452552701
D/OtaApp  ( 1537): [debug] > cancelling the previous pending intent set for install later
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "mms"
I/OtaApp  ( 1537): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
D/Checkin ( 1537): publish the event [tag = MOT_OTA event name = LOG]
I/LatinIME:LogUtils( 1183): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "mmsto"
D/dalvikvm( 2154): GC_EXPLICIT freed 4690K, 45% free 9624K/17224K, paused 3ms+12ms, total 97ms
I/LatinIME:LogUtils( 1183): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
D/OtaApp  ( 1537): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "sms"
I/Launcher( 1297): Deferring update until onResume
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "smsto"
D/OtaApp  ( 1537): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
W/GeofencerStateMachine( 1198): Ignoring removeGeofence because network location is disabled.
D/dalvikvm( 1016): GC_EXPLICIT freed 2535K, 13% free 17825K/20408K, paused 2ms+11ms, total 165ms
D/dalvikvm( 2185): GC_EXPLICIT freed 2739K, 42% free 10045K/17224K, paused 3ms+5ms, total 67ms
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
D/dalvikvm( 1380): GC_EXPLICIT freed 568K, 33% free 11708K/17224K, paused 106ms+6ms, total 176ms
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "mms"
D/dalvikvm( 1297): GC_EXPLICIT freed 2797K, 33% free 11628K/17224K, paused 22ms+5ms, total 69ms
I/Launcher( 1297): Deferring update until onResume
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "mmsto"
D/VoicemailCleanupService( 3081): Cleaning up data for package: com.example.hello
I/InternalIcingCorporaPro( 2185): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/ActivityManager( 1016): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3644 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
I/LatinIME:LogUtils( 1183): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1452552702
W/ContextImpl( 3644): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/dalvikvm( 3162): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3162): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 3162): VFY: replacing opcode 0x6e at 0x0013
D/PackageBroadcastService( 1380): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1380): Clearing selected account for com.example.hello
D/ChimeraCfgMgr( 1380): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1380): Module APK com.google.android.play.games already loaded
W/InputMethodManagerService( 1016): Got RemoteException sending setActive(false) notification to pid 3527 uid 10543
W/Binder  ( 1183): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1183): java.lang.NullPointerException
W/Binder  ( 1183): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1183): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1183): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 1183): 	at dalvik.system.NativeStart.run(Native Method)
I/LocationSettingsChecker( 1380): Removing dialog suppression flag for package com.example.hello
D/ChimeraCfgMgr( 1380): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1380): Module APK com.google.android.play.games already loaded
D/BackupManagerService( 1016): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
V/BackupManagerService( 1016): removePackageParticipantsLocked: uid=10543 #1
E/NetworkScheduler.SchedulerReceiver( 2015): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 2015): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 1380): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1380): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1380): 0 metrics were deleted when clearing package com.example.hello.
D/gH_CompatibleDatabase( 1380): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1380): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1380): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
I/ActivityManager( 1016): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3666 uid=10058 gids={50058}
D/gH_CompatibleDatabase( 1380): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1380): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1380): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1380): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1380): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1380): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1380): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager( 1016): Killing 3315:com.android.calendar/u0a7 (adj 15): empty #9
W/ContextImpl( 1245): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/InternalIcingCorporaPro( 2185): UpdateCorporaTask done [took 207 ms] updated apps [took 207 ms] 
D/dalvikvm( 1016): GC_EXPLICIT freed 510K, 14% free 17751K/20408K, paused 8ms+16ms, total 262ms
I/Icing   ( 1380): doRemovePackageData com.example.hello
D/Documents( 3666): Loading roots for com.android.providers.downloads.documents
I/ActivityManager( 1016): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=3684 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
I/ActivityManager( 1016): Killing 3392:com.google.android.partnersetup/u0a25 (adj 15): empty #9
W/ContextImpl( 1245): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1016): Killing 3354:com.android.defcontainer/u0a13 (adj 15): empty #9
W/ContextImpl( 1245): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/AndroidRuntime( 3612): Shutting down VM
D/dalvikvm( 3612): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
D/Documents( 3666): Loading roots for com.android.externalstorage.documents
D/dalvikvm( 3684): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f4b5f8, skipping init
I/openssl ( 3684): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3684): Crypto mode 0 already enabled
I/ActivityManager( 1016): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3702 uid=10020 gids={50020, 1028, 1015, 1023}
I/ActivityManager( 1016): Killing 3081:android.process.acore/u0a10 (adj 15): empty #9
W/ContextImpl( 1245): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/ExternalStorage( 3702): After updating volumes, found 1 active roots
D/Documents( 3666): Updating roots due to change at content://com.android.externalstorage.documents/root
D/Documents( 3666): Loading roots for com.android.providers.media.documents
D/Documents( 3666): Loading roots for com.google.android.apps.docs.storage
D/Documents( 3666): Update found 7 roots in 199ms
D/Documents( 3666): Used cached roots for com.android.providers.downloads.documents
D/Documents( 3666): Loading roots for com.android.externalstorage.documents
D/Documents( 3666): Used cached roots for com.android.providers.media.documents
D/Documents( 3666): Used cached roots for com.google.android.apps.docs.storage
D/Documents( 3666): Update found 7 roots in 7ms

```
