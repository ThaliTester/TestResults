#### Test 50650278b1aec71_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1018): sending alarm Alarm{420fb598 type 3 android}
,--------- beginning of /dev/log/main
D/AndroidRuntime( 3461): 
D/AndroidRuntime( 3461): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3461): CheckJNI is OFF
D/dalvikvm( 3461): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3461): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3461): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3461): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3461): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3461): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3461): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3461): failed to load memtrack module: -2
D/AndroidRuntime( 3461): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1018): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3461
W/WindowManager( 1018): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1018): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3477 uid=10448 gids={50448, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3461): Shutting down VM
D/dalvikvm( 3461): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 2ms
W/ContextImpl( 1262): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1262): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3477): Binding Chromium to main looper Looper (main, tid 1) {41f1ed98}
I/LibraryLoader( 3477): Expected native library version number "",actual native library version number ""
I/chromium( 3477): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3477): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1018): Message: 20
D/BluetoothManagerService( 1018): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4346abd0:true
D/BluetoothAdapter( 3477): 1106457032: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3477): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3477): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3477): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3477): Local Branch: 
I/Adreno-EGL( 3477): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3477): Local Patches: NONE
I/Adreno-EGL( 3477): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 3477): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 3477): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 3477): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3477): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3477): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3477): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 3477): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 3477): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 3477): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3477): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3477): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3477): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3477): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3477): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3477): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 3477): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3477): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3477): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3477): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3477): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3477): Enabling debug mode 0
,W/AwContents( 3477): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3477): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1018): Displayed com.test.thalitest/.MainActivity,cp,ca,428
I/ActivityManager( 1018): Displayed com.test.thalitest/.MainActivity: +391ms (total +428ms)
,D/JsMessageQueue( 3477): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3477): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f23068
,D/dalvikvm( 3477): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f23068
,D/jxcore_app_log( 3477): JniHelper::setJavaVM(0x4156bfa8), pthread_self() = 1613855344
,D/JX-Cordova( 3477): jxcore cordova android initializing
,I/dalvikvm( 3477): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 3477): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 3477): VFY: replacing opcode 0x6e at 0x0045
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
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
,D/dalvikvm( 3477): GC_CONCURRENT freed 2770K, 17% free 14383K/17224K, paused 3ms+2ms, total 40ms
,D/dalvikvm( 3477): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/dalvikvm( 3477): GC_FOR_ALLOC freed 128K, 17% free 14367K/17224K, paused 25ms, total 25ms
,D/dalvikvm( 3477): GC_FOR_ALLOC freed 130K, 17% free 14386K/17224K, paused 25ms, total 27ms
,D/dalvikvm( 3477): GC_FOR_ALLOC freed 181K, 17% free 14420K/17224K, paused 25ms, total 26ms
,I/dalvikvm-heap( 3477): Grow heap (frag case) to 16.252MB for 143930-byte allocation
,D/dalvikvm( 3477): GC_FOR_ALLOC freed 253K, 17% free 14467K/17368K, paused 25ms, total 26ms
,I/dalvikvm-heap( 3477): Grow heap (frag case) to 16.367MB for 215890-byte allocation
,D/dalvikvm( 3477): GC_FOR_ALLOC freed 366K, 18% free 14540K/17580K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3477): Grow heap (frag case) to 16.541MB for 323830-byte allocation
,D/dalvikvm( 3477): GC_FOR_ALLOC freed 563K, 19% free 14662K/17900K, paused 25ms, total 26ms
,I/dalvikvm-heap( 3477): Grow heap (frag case) to 16.814MB for 485740-byte allocation
,D/dalvikvm( 3477): GC_FOR_ALLOC freed 859K, 20% free 14837K/18376K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3477): Grow heap (frag case) to 17.216MB for 728606-byte allocation
,D/dalvikvm( 3477): GC_FOR_ALLOC freed 1275K, 21% free 15093K/19088K, paused 28ms, total 28ms
,D/dalvikvm( 3477): GC_CONCURRENT freed 1676K, 19% free 15464K/19088K, paused 2ms+3ms, total 44ms
,D/dalvikvm( 3477): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/dalvikvm( 3477): GC_FOR_ALLOC freed 356K, 20% free 15419K/19088K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3477): Grow heap (frag case) to 18.653MB for 1639352-byte allocation
,D/dalvikvm( 3477): GC_CONCURRENT freed 1664K, 23% free 15989K/20692K, paused 1ms+3ms, total 32ms
,D/dalvikvm( 3477): GC_FOR_ALLOC freed 1363K, 23% free 16068K/20692K, paused 30ms, total 30ms
,I/dalvikvm-heap( 3477): Grow heap (frag case) to 20.069MB for 2459024-byte allocation
,D/dalvikvm( 3477): GC_CONCURRENT freed 242K, 21% free 18363K/23096K, paused 5ms+4ms, total 35ms
,D/dalvikvm( 3477): GC_CONCURRENT freed 4335K, 27% free 17040K/23096K, paused 2ms+7ms, total 41ms
,D/dalvikvm( 3477): WAIT_FOR_CONCURRENT_GC blocked 38ms
,I/dalvikvm-heap( 3477): Grow heap (frag case) to 22.191MB for 3688532-byte allocation
,D/dalvikvm( 3477): GC_CONCURRENT freed 444K, 23% free 20669K/26700K, paused 4ms+21ms, total 74ms
,D/dalvikvm( 3477): GC_FOR_ALLOC freed 3113K, 33% free 17973K/26700K, paused 28ms, total 28ms
,W/jxcore-log( 3477): Initializing JXcore engine
,W/jxcore-log( 3477): JXcore engine is ready
,D/dalvikvm( 3477): GC_CONCURRENT freed 350K, 23% free 20595K/26700K, paused 2ms+2ms, total 29ms
,D/dalvikvm( 3477): WAIT_FOR_CONCURRENT_GC blocked 23ms
,W/jxcore-log( 3477): Starting JXcore engine
,W/jxcore-log( 3477): Platform android
W/jxcore-log( 3477): 
,W/jxcore-log( 3477): Process ARCH arm
W/jxcore-log( 3477): 
,I/jxcore-log( 3477): JXcore Cordova bridge is ready!
I/jxcore-log( 3477): 
,W/jxcore-log( 3477): JXcore engine is started
,I/chromium( 3477): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 3477): Error!: missing ) after argument list
E/jxcore  ( 3477): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 3477): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager( 1018): Killing 3121:com.android.providers.calendar/u0a8 (adj 15): empty #9
W/ContextImpl( 1262): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1262): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1262): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1548): [info] > Updatetime from metadata: 10
,D/Checkin ( 1548): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1548): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1548): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1548): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1548): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1548): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,W/IInputConnectionWrapper( 3477): showStatusIcon on inactive InputConnection
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  273): write error (Broken pipe)
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1018): sending alarm Alarm{43fbdea8 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{43d95dc8 type 3 android}
,I/MMApiBackOffService( 1548): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1548): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1548): MMApiBackOffService told us it's okay to retry the waiting requests: 2
,D/MMApiWebService( 1548): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1548): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1548): doRequest(): polling manager says we're not connected, returning with an error: 
,D/MMApiWebService( 1548): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1548): ProvisionWS.Response: Missing mandatory message data in response from DM server...
I/MMApiWebService( 1548): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1548): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1548): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1548): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1548): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1548): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1548): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1548): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1548): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1548): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1548): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1548): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/Checkin ( 1548): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1018): sending alarm Alarm{43d94bd8 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{43d91f18 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{43d904b8 type 3 android}
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  273): write error (Broken pipe)
,V/AlarmManager( 1018): sending alarm Alarm{43d8de08 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{43d84450 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{42767728 type 2 android}
,D/ConnectivityService( 1018): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1018): sending alarm Alarm{427d1b78 type 0 com.android.vending}
,D/Finsky  ( 3094): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ConnectivityService( 1018): Done.
,D/ConnectivityService( 1018): Setting timer for 720seconds
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3094): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
W/SocketClient(  273): write error (Broken pipe)
,D/dalvikvm( 1381): GC_EXPLICIT freed 988K, 39% free 10514K/17224K, paused 11ms+5ms, total 39ms
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3094): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3094): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 3094): [1] WearSupportService.startHygiene: disabled
,D/Finsky  ( 3094): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 1018): sending alarm Alarm{43cb3c78 type 0 com.android.vending}
D/Finsky  ( 3094): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
,D/dalvikvm( 1207): GC_EXPLICIT freed 1370K, 41% free 10255K/17224K, paused 3ms+5ms, total 38ms
,D/DeviceConnectionService( 1207): client connected with version: 8296000
,D/Finsky  ( 3094): [287] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,E/DataBuffer( 1207): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42011cc8)
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1018): sending alarm Alarm{43d81970 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{43d4a0e8 type 0 com.android.vending}
,D/Finsky  ( 3094): [273] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3094): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
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
,V/AlarmManager( 1018): sending alarm Alarm{43c596a0 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{431e8b20 type 3 android}
,D/dalvikvm( 1018): GC_EXPLICIT freed 22510K, 65% free 17789K/50220K, paused 3ms+10ms, total 146ms
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1018): sending alarm Alarm{431e0d00 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{44663dd8 type 3 android}
,I/MMApiBackOffService( 1548): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1548): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1548): MMApiBackOffService told us it's okay to retry the waiting requests: 2
,D/MMApiWebService( 1548): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1548): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1548): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/MMApiWebService( 1548): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1548): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1548): publish the event [tag = MOT_CCE event name = LOG]
E/MMApiProvisionService( 1548): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1548): ProvisionWS.Response.setError: error RadioDownError
I/MMApiBackOffService( 1548): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1548): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1548): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1548): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1548): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1548): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
D/Checkin ( 1548): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1548): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1548): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/Checkin ( 1548): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1018): sending alarm Alarm{4461db68 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{4460c288 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{445ee108 type 3 android}
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1018): sending alarm Alarm{4458ec48 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{4453ba80 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{43d6ccb0 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{43cf41d0 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{43cbf360 type 3 android}
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1018): sending alarm Alarm{43caa678 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{43bd7860 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{43bcf248 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{43b7fa30 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{432698f0 type 3 android}
,I/ProcessStatsService( 1018): Prepared write state in 34ms
,I/ProcessStatsService( 1018): Prepared write state in 24ms
,I/ProcessStatsService( 1018): Pruning old procstats: /data/system/procstats/state-2015-12-07-19-14-00.bin
,V/AlarmManager( 1018): sending alarm Alarm{43d758b0 type 2 android}
,D/ConnectivityService( 1018): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1018): sending alarm Alarm{423b8658 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{423b2350 type 2 com.motorola.ccc.cce}
,V/AlarmManager( 1018): sending alarm Alarm{42347498 type 3 com.google.android.gms}
,V/AlarmManager( 1018): sending alarm Alarm{423474e8 type 3 com.google.android.gms}
,V/AlarmManager( 1018): sending alarm Alarm{42167830 type 0 com.google.android.gms}
,D/ConnectivityService( 1018): Done.
,D/ConnectivityService( 1018): Setting timer for 720seconds
,D/CCE     ( 1548): Registering with Alarm Manager to restart CCE
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1365): Aggregate from 1449594774879 (log), 1449594774879 (data)
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm( 1381): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 1381): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1381): VFY: replacing opcode 0x6e at 0x0033
,W/SocketClient(  273): write error (Broken pipe)
,V/AlarmManager( 1018): sending alarm Alarm{42808a70 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{4466d870 type 3 android}
,I/ActivityManager( 1018): Killing 3355:com.google.android.partnersetup/u0a25 (adj 15): empty for 1833s
,I/ActivityManager( 1018): Killing 3018:android.process.acore/u0a10 (adj 15): empty for 1833s
,W/ContextImpl( 1262): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1018): Killing 3323:com.android.defcontainer/u0a13 (adj 15): empty for 1833s
,W/ContextImpl( 1262): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1262): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ClearcutLoggerApiImpl( 1381): disconnect managed GoogleApiClient
,V/AlarmManager( 1018): sending alarm Alarm{43c57eb0 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{4281da58 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{422aecb8 type 3 android}
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1381): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 3645): 
D/AndroidRuntime( 3645): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3645): CheckJNI is OFF
D/dalvikvm( 3645): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3645): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3645): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3645): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3645): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3645): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3645): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3645): failed to load memtrack module: -2
D/AndroidRuntime( 3645): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10448 user=-1: uninstall pkg
I/ActivityManager( 1018): Killing 3477:com.test.thalitest/u0a448 (adj 15): stop com.test.thalitest
W/ContextImpl( 1262): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
W/PackageSettings( 1018): Skipping PackageSetting{421db530 com.example.hello/10442} due to missing metadata
I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10448 user=0: pkg removed
D/dalvikvm( 2138): GC_EXPLICIT freed 4779K, 45% free 9604K/17224K, paused 2ms+6ms, total 38ms
I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
I/ActivityManager( 1018): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=3662 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
I/LatinIME:LogUtils( 1188): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1188): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
D/dalvikvm(  277): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+6ms, total 36ms
W/GeofencerStateMachine( 1207): Ignoring removeGeofence because network location is disabled.
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
D/dalvikvm( 2170): GC_EXPLICIT freed 2403K, 44% free 9770K/17224K, paused 2ms+47ms, total 125ms
D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 19ms
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
I/LatinIME:LogUtils( 1188): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449597671
D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 20ms
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
D/dalvikvm( 1310): GC_EXPLICIT freed 2792K, 33% free 11591K/17224K, paused 2ms+17ms, total 183ms
I/Launcher( 1310): Deferring update until onResume
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
D/dalvikvm( 1018): GC_EXPLICIT freed 1557K, 65% free 17763K/50220K, paused 3ms+12ms, total 180ms
D/dalvikvm( 1018): WAIT_FOR_CONCURRENT_GC blocked 50ms
I/Launcher( 1310): Deferring update until onResume
I/dalvikvm( 1018): Jit: resizing JitTable from 8192 to 16384
I/LatinIME:LogUtils( 1188): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449597671
I/ContactLocale( 3662): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
D/dalvikvm( 1018): GC_EXPLICIT freed 209K, 65% free 17691K/50220K, paused 3ms+73ms, total 183ms
D/VoicemailCleanupService( 3662): Cleaning up data for package: com.test.thalitest
I/InternalIcingCorporaPro( 2170): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager( 1018): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3692 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
W/ContextImpl( 3692): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
D/PackageBroadcastService( 1365): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1365): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1365): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1365): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1365): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1365): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1365): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1381): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1381): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/dalvikvm( 3094): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3094): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 3094): VFY: replacing opcode 0x6e at 0x0013
D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1018): removePackageParticipantsLocked: uid=10448 #1
D/gH_CompatibleDatabase( 1365): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1365): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1365): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1365): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/ActivityManager( 1018): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3712 uid=10058 gids={50058}
D/gH_CompatibleDatabase( 1365): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1365): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1365): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1365): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1365): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1365): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1365): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
I/PeopleContactsSync( 1365): CP2 sync disabled
D/gH_CompatibleDatabase( 1365): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1365): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/Icing   ( 1365): doRemovePackageData com.test.thalitest
I/InternalIcingCorporaPro( 2170): UpdateCorporaTask done [took 134 ms] updated apps [took 134 ms] 
D/Documents( 3712): Loading roots for com.android.providers.downloads.documents
I/ActivityManager( 1018): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=3728 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
D/AndroidRuntime( 3645): Shutting down VM
D/dalvikvm( 3645): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms
D/Documents( 3712): Loading roots for com.android.externalstorage.documents
D/dalvikvm( 3728): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f1e728, skipping init
I/openssl ( 3728): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3728): Crypto mode 0 already enabled
I/ActivityManager( 1018): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3744 uid=10020 gids={50020, 1028, 1015, 1023}
I/ActivityManager( 1018): Killing 3662:android.process.acore/u0a10 (adj 15): empty #9
W/ContextImpl( 1262): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/ExternalStorage( 3744): After updating volumes, found 1 active roots
D/Documents( 3712): Updating roots due to change at content://com.android.externalstorage.documents/root
D/Documents( 3712): Loading roots for com.android.providers.media.documents
D/Documents( 3712): Loading roots for com.google.android.apps.docs.storage
D/Documents( 3712): Update found 7 roots in 179ms
D/Documents( 3712): Used cached roots for com.android.providers.downloads.documents
D/Documents( 3712): Loading roots for com.android.externalstorage.documents
D/Documents( 3712): Used cached roots for com.android.providers.media.documents
D/Documents( 3712): Used cached roots for com.google.android.apps.docs.storage
D/Documents( 3712): Update found 7 roots in 6ms

```
