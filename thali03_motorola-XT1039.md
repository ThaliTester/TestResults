#### Test 50650278352fc1f_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1019): sending alarm Alarm{43ce79d0 type 3 android}
,--------- beginning of /dev/log/main
D/AndroidRuntime( 3508): 
D/AndroidRuntime( 3508): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3508): CheckJNI is OFF
D/dalvikvm( 3508): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3508): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3508): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3508): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3508): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3508): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3508): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3508): failed to load memtrack module: -2
D/AndroidRuntime( 3508): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3508
W/WindowManager( 1019): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3525 uid=10445 gids={50445, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3508): Shutting down VM
D/dalvikvm( 3508): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 2ms
D/dalvikvm(  277): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 1ms+3ms, total 24ms
W/ContextImpl( 1241): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1241): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 19ms
D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
V/WebViewChromiumFactoryProvider( 3525): Binding Chromium to main looper Looper (main, tid 1) {41f82930}
I/LibraryLoader( 3525): Expected native library version number "",actual native library version number ""
I/chromium( 3525): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3525): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43d16a20:true
D/BluetoothAdapter( 3525): 1106865984: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3525): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3525): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3525): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3525): Local Branch: 
I/Adreno-EGL( 3525): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3525): Local Patches: NONE
I/Adreno-EGL( 3525): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3525): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 3525): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3525): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3525): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3525): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3525): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 3525): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 3525): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3525): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3525): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3525): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3525): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3525): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3525): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3525): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 3525): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3525): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3525): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3525): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3525): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3525): Enabling debug mode 0
,W/AwContents( 3525): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3525): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1019): Displayed com.test.thalitest/.MainActivity,cp,ca,416
I/ActivityManager( 1019): Displayed com.test.thalitest/.MainActivity: +382ms (total +416ms)
,D/JsMessageQueue( 3525): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3525): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f86de0
,D/dalvikvm( 3525): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f86de0
D/jxcore_app_log( 3525): JniHelper::setJavaVM(0x415cefa8), pthread_self() = 1615037208
,D/JX-Cordova( 3525): jxcore cordova android initializing
I/dalvikvm( 3525): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 3525): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 3525): VFY: replacing opcode 0x6e at 0x0045
,D/dalvikvm( 3525): GC_CONCURRENT freed 2774K, 17% free 14384K/17224K, paused 3ms+2ms, total 53ms
,D/dalvikvm( 3525): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/dalvikvm( 3525): GC_FOR_ALLOC freed 130K, 17% free 14366K/17224K, paused 26ms, total 26ms
,D/dalvikvm( 3525): GC_FOR_ALLOC freed 299K, 17% free 14432K/17224K, paused 25ms, total 26ms
,I/dalvikvm-heap( 3525): Grow heap (frag case) to 16.263MB for 143930-byte allocation
,D/dalvikvm( 3525): GC_FOR_ALLOC freed 264K, 17% free 14468K/17368K, paused 25ms, total 26ms
,I/dalvikvm-heap( 3525): Grow heap (frag case) to 16.368MB for 215890-byte allocation
,D/dalvikvm( 3525): GC_FOR_ALLOC freed 366K, 18% free 14541K/17580K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3525): Grow heap (frag case) to 16.541MB for 323830-byte allocation
,D/dalvikvm( 3525): GC_FOR_ALLOC freed 564K, 19% free 14662K/17900K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3525): Grow heap (frag case) to 16.814MB for 485740-byte allocation
,D/dalvikvm( 3525): GC_FOR_ALLOC freed 859K, 20% free 14838K/18376K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3525): Grow heap (frag case) to 17.217MB for 728606-byte allocation
,D/dalvikvm( 3525): GC_FOR_ALLOC freed 1275K, 21% free 15094K/19088K, paused 28ms, total 29ms
,D/dalvikvm( 3525): GC_CONCURRENT freed 1677K, 19% free 15464K/19088K, paused 2ms+4ms, total 34ms
,D/dalvikvm( 3525): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 3525): GC_FOR_ALLOC freed 359K, 20% free 15420K/19088K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3525): Grow heap (frag case) to 18.654MB for 1639352-byte allocation
,D/dalvikvm( 3525): GC_CONCURRENT freed 1658K, 23% free 15990K/20692K, paused 2ms+4ms, total 34ms
,D/dalvikvm( 3525): GC_FOR_ALLOC freed 1371K, 23% free 16069K/20692K, paused 30ms, total 30ms
,I/dalvikvm-heap( 3525): Grow heap (frag case) to 20.070MB for 2459024-byte allocation
,D/dalvikvm( 3525): GC_CONCURRENT freed 248K, 21% free 18400K/23096K, paused 4ms+3ms, total 42ms
,D/dalvikvm( 3525): GC_FOR_ALLOC freed 4328K, 27% free 17045K/23096K, paused 35ms, total 35ms
,I/dalvikvm-heap( 3525): Grow heap (frag case) to 22.195MB for 3688532-byte allocation
,D/dalvikvm( 3525): GC_CONCURRENT freed 324K, 24% free 20548K/26700K, paused 5ms+6ms, total 49ms
,D/dalvikvm( 3525): GC_FOR_ALLOC freed 3226K, 33% free 17986K/26700K, paused 28ms, total 29ms
,W/jxcore-log( 3525): Initializing JXcore engine
,W/jxcore-log( 3525): JXcore engine is ready
,D/dalvikvm( 3525): GC_CONCURRENT freed 324K, 23% free 20633K/26700K, paused 1ms+2ms, total 28ms
,D/dalvikvm( 3525): WAIT_FOR_CONCURRENT_GC blocked 24ms
,W/jxcore-log( 3525): Starting JXcore engine
,W/jxcore-log( 3525): Platform android
W/jxcore-log( 3525): 
,W/jxcore-log( 3525): Process ARCH arm
W/jxcore-log( 3525): 
,I/jxcore-log( 3525): JXcore Cordova bridge is ready!
I/jxcore-log( 3525): 
,W/jxcore-log( 3525): JXcore engine is started
,I/chromium( 3525): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 3525): Error!: missing ) after argument list
E/jxcore  ( 3525): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 3525): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager( 1019): Killing 3262:com.android.calendar/u0a7 (adj 15): empty #9
W/ContextImpl( 1241): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1241): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1241): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1539): [info] > Updatetime from metadata: 10
,D/Checkin ( 1539): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1539): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1539): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1539): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1539): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1539): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,W/IInputConnectionWrapper( 3525): showStatusIcon on inactive InputConnection
,V/AlarmManager( 1019): sending alarm Alarm{43cd01d0 type 3 android}
,I/MMApiBackOffService( 1539): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1539): MMApiBackOffService told us it's okay to retry the waiting requests: 2
,D/MMApiWebService( 1539): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1539): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1539): doRequest(): polling manager says we're not connected, returning with an error: 
,D/MMApiWebService( 1539): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,I/MMApiWebService( 1539): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,E/MMApiProvisionService( 1539): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1539): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1539): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1539): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1539): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1539): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1539): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{43c4a5c0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43c3fa68 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43276f78 type 3 android}
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{4326e888 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43258340 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43251fe0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42869a60 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
,V/AlarmManager( 1019): sending alarm Alarm{4324b890 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4322aa38 type 3 android}
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{43226648 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43210470 type 3 android}
,I/MMApiBackOffService( 1539): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1539): MMApiBackOffService told us it's okay to retry the waiting requests: 2
,D/MMApiWebService( 1539): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1539): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1539): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,D/MMApiWebService( 1539): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1539): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1539): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1539): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1539): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1539): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1539): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1539): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1539): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{4320b038 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43205090 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43201f70 type 3 android}
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{431f9fa0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{431da030 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{431d58c0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{431d0710 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{431cabc0 type 3 android}
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{431c58d8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{431b2840 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{431aee20 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{431a1e78 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43195ff0 type 3 android}
,I/ProcessStatsService( 1019): Prepared write state in 35ms
,I/ProcessStatsService( 1019): Prepared write state in 10ms
,I/ProcessStatsService( 1019): Pruning old procstats: /data/system/procstats/state-2015-12-07-16-13-00.bin
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{43125d80 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43de8298 type 3 android}
,I/ActivityManager( 1019): Killing 3416:com.google.android.partnersetup/u0a25 (adj 15): empty for 1806s
,I/ActivityManager( 1019): Killing 3019:android.process.acore/u0a10 (adj 15): empty for 1806s
,I/ActivityManager( 1019): Killing 3378:com.android.defcontainer/u0a13 (adj 15): empty for 1806s
,W/ContextImpl( 1241): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1241): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1241): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/AlarmManager( 1019): sending alarm Alarm{432316f0 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1019): sending alarm Alarm{427dcfb8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{427dd068 type 2 com.motorola.ccc.cce}
,V/AlarmManager( 1019): sending alarm Alarm{427dd0b8 type 3 com.google.android.gms}
,V/AlarmManager( 1019): sending alarm Alarm{42890e98 type 3 com.google.android.gms}
,V/AlarmManager( 1019): sending alarm Alarm{42890ee8 type 2 com.motorola.ccc.cce}
,V/AlarmManager( 1019): sending alarm Alarm{42890f38 type 0 com.google.android.gms}
,D/CCE     ( 1539): Registering with Alarm Manager to restart CCE
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
,I/PollingManager( 1539): alarm fired!
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1385): Aggregate from 1449588315364 (log), 1449588315364 (data)
,D/dalvikvm( 1369): GC_EXPLICIT freed 1215K, 39% free 10515K/17224K, paused 2ms+4ms, total 34ms
,I/dalvikvm( 1369): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
,W/dalvikvm( 1369): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1369): VFY: replacing opcode 0x6e at 0x0033
,D/dalvikvm( 1019): GC_EXPLICIT freed 23058K, 65% free 17821K/50216K, paused 4ms+10ms, total 137ms
,V/AlarmManager( 1019): sending alarm Alarm{44792c50 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42d50a30 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4294ce00 type 3 android}
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1369): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{4291c478 type 3 android}
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 3664): 
D/AndroidRuntime( 3664): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3664): CheckJNI is OFF
D/dalvikvm( 3664): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3664): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3664): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3664): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3664): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3664): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3664): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3664): failed to load memtrack module: -2
D/AndroidRuntime( 3664): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10445 user=-1: uninstall pkg
I/ActivityManager( 1019): Killing 3525:com.test.thalitest/u0a445 (adj 13): stop com.test.thalitest
W/ContextImpl( 1241): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
W/PackageSettings( 1019): Skipping PackageSetting{422451c0 com.example.hello/10442} due to missing metadata
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10445 user=0: pkg removed
D/dalvikvm( 2137): GC_EXPLICIT freed 4773K, 45% free 9604K/17224K, paused 2ms+5ms, total 37ms
I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
I/ActivityManager( 1019): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=3689 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
I/LatinIME:LogUtils( 1184): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1184): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
W/GeofencerStateMachine( 1198): Ignoring removeGeofence because network location is disabled.
D/dalvikvm( 2170): GC_EXPLICIT freed 2616K, 43% free 9824K/17224K, paused 2ms+5ms, total 107ms
D/dalvikvm( 1293): GC_EXPLICIT freed 2792K, 33% free 11592K/17224K, paused 2ms+15ms, total 124ms
I/Launcher( 1293): Deferring update until onResume
D/dalvikvm( 1019): GC_EXPLICIT freed 752K, 65% free 17680K/50216K, paused 5ms+11ms, total 127ms
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
I/Launcher( 1293): Deferring update until onResume
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
I/LatinIME:LogUtils( 1184): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449590592
I/LatinIME:LogUtils( 1184): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449590592
D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1019): removePackageParticipantsLocked: uid=10445 #1
I/dalvikvm( 1019): Jit: resizing JitTable from 8192 to 16384
D/VoicemailCleanupService( 3689): Cleaning up data for package: com.test.thalitest
I/InternalIcingCorporaPro( 2170): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/dalvikvm( 1019): GC_EXPLICIT freed 528K, 65% free 17761K/50216K, paused 13ms+19ms, total 168ms
I/ActivityManager( 1019): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3710 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
W/ContextImpl( 3710): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/dalvikvm( 3093): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3093): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 3093): VFY: replacing opcode 0x6e at 0x0013
D/PackageBroadcastService( 1385): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1385): Clearing selected account for com.test.thalitest
I/LocationSettingsChecker( 1385): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1385): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1385): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1369): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1369): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 1385): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1385): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/ChimeraCfgMgr( 1385): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1385): Module APK com.google.android.play.games already loaded
D/gH_MetricsDatabase( 1385): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1385): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/ActivityManager( 1019): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3731 uid=10058 gids={50058}
I/PeopleContactsSync( 1385): CP2 sync disabled
D/gH_CompatibleDatabase( 1385): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1385): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1385): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/dalvikvm( 1385): GC_CONCURRENT freed 1692K, 32% free 11765K/17224K, paused 4ms+9ms, total 59ms
D/gH_CompatibleDatabase( 1385): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1385): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1385): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1385): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1385): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1385): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/Icing   ( 1385): doRemovePackageData com.test.thalitest
D/AndroidRuntime( 3664): Shutting down VM
I/InternalIcingCorporaPro( 2170): UpdateCorporaTask done [took 153 ms] updated apps [took 152 ms] 
D/dalvikvm( 3664): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 3ms
D/Documents( 3731): Loading roots for com.android.providers.downloads.documents
I/ActivityManager( 1019): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=3747 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
I/ContactLocale( 3689): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
D/Documents( 3731): Loading roots for com.android.externalstorage.documents
I/ActivityManager( 1019): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3761 uid=10020 gids={50020, 1028, 1015, 1023}
D/dalvikvm( 3747): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f825d8, skipping init
I/openssl ( 3747): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3747): Crypto mode 0 already enabled
I/ActivityManager( 1019): Killing 3689:android.process.acore/u0a10 (adj 15): empty #9
W/ContextImpl( 1241): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/ExternalStorage( 3761): After updating volumes, found 1 active roots
D/Documents( 3731): Updating roots due to change at content://com.android.externalstorage.documents/root
D/Documents( 3731): Loading roots for com.android.providers.media.documents
D/Documents( 3731): Loading roots for com.google.android.apps.docs.storage
D/Documents( 3731): Update found 7 roots in 163ms
D/Documents( 3731): Used cached roots for com.android.providers.downloads.documents
D/Documents( 3731): Loading roots for com.android.externalstorage.documents
D/Documents( 3731): Used cached roots for com.android.providers.media.documents
D/Documents( 3731): Used cached roots for com.google.android.apps.docs.storage
D/Documents( 3731): Update found 7 roots in 7ms
E/MP-Decision( 1487): Error(-22) changing core 2 status to offline

```
