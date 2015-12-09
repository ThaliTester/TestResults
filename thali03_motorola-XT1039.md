#### Test 50650278eab32a5_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
,V/AlarmManager( 1022): sending alarm Alarm{43d1aff0 type 3 android}
--------- beginning of /dev/log/main
D/AndroidRuntime( 3494): 
D/AndroidRuntime( 3494): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3494): CheckJNI is OFF
D/dalvikvm( 3494): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3494): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3494): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3494): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3494): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3494): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3494): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3494): failed to load memtrack module: -2
D/AndroidRuntime( 3494): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1022): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3494
W/WindowManager( 1022): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1022): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3510 uid=10451 gids={50451, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3494): Shutting down VM
D/dalvikvm( 3494): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+1ms, total 3ms
W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3510): Binding Chromium to main looper Looper (main, tid 1) {41f0fc80}
I/LibraryLoader( 3510): Expected native library version number "",actual native library version number ""
I/chromium( 3510): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3510): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1022): Message: 20
D/BluetoothManagerService( 1022): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43c2c320:true
D/BluetoothAdapter( 3510): 1106395312: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3510): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3510): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3510): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3510): Local Branch: 
I/Adreno-EGL( 3510): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3510): Local Patches: NONE
I/Adreno-EGL( 3510): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3510): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 3510): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3510): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3510): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3510): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3510): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 3510): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 3510): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3510): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3510): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3510): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3510): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3510): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3510): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3510): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 3510): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 3510): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3510): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3510): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3510): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3510): Enabling debug mode 0
,W/AwContents( 3510): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3510): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1022): Displayed com.test.thalitest/.MainActivity,cp,ca,400
I/ActivityManager( 1022): Displayed com.test.thalitest/.MainActivity: +375ms (total +400ms)
,D/JsMessageQueue( 3510): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3510): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f13f50
,D/dalvikvm( 3510): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f13f50
,D/jxcore_app_log( 3510): JniHelper::setJavaVM(0x4155cfa8), pthread_self() = 1614530776
,D/JX-Cordova( 3510): jxcore cordova android initializing
,I/dalvikvm( 3510): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 3510): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 3510): VFY: replacing opcode 0x6e at 0x0045
,D/dalvikvm( 3510): GC_CONCURRENT freed 2825K, 17% free 14364K/17224K, paused 2ms+2ms, total 64ms
,D/dalvikvm( 3510): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 3510): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/dalvikvm( 3510): GC_FOR_ALLOC freed 118K, 17% free 14367K/17224K, paused 25ms, total 25ms
,D/dalvikvm( 3510): GC_FOR_ALLOC freed 303K, 17% free 14431K/17224K, paused 25ms, total 26ms
,I/dalvikvm-heap( 3510): Grow heap (frag case) to 16.263MB for 143930-byte allocation
,D/dalvikvm( 3510): GC_FOR_ALLOC freed 266K, 17% free 14468K/17368K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3510): Grow heap (frag case) to 16.368MB for 215890-byte allocation
,D/dalvikvm( 3510): GC_FOR_ALLOC freed 368K, 18% free 14541K/17580K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3510): Grow heap (frag case) to 16.541MB for 323830-byte allocation
,D/dalvikvm( 3510): GC_FOR_ALLOC freed 567K, 19% free 14662K/17900K, paused 25ms, total 26ms
,I/dalvikvm-heap( 3510): Grow heap (frag case) to 16.814MB for 485740-byte allocation
,D/dalvikvm( 3510): GC_FOR_ALLOC freed 865K, 20% free 14837K/18376K, paused 28ms, total 28ms
,I/dalvikvm-heap( 3510): Grow heap (frag case) to 17.217MB for 728606-byte allocation
,D/dalvikvm( 3510): GC_FOR_ALLOC freed 1283K, 21% free 15094K/19088K, paused 28ms, total 28ms
,D/dalvikvm( 3510): GC_CONCURRENT freed 1677K, 19% free 15464K/19088K, paused 3ms+3ms, total 43ms
,D/dalvikvm( 3510): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/dalvikvm( 3510): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 3510): GC_FOR_ALLOC freed 372K, 20% free 15419K/19088K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3510): Grow heap (frag case) to 18.654MB for 1639352-byte allocation
,D/dalvikvm( 3510): GC_CONCURRENT freed 1641K, 23% free 15991K/20692K, paused 2ms+3ms, total 37ms
,D/dalvikvm( 3510): GC_FOR_ALLOC freed 1412K, 23% free 16070K/20692K, paused 30ms, total 30ms
,I/dalvikvm-heap( 3510): Grow heap (frag case) to 20.072MB for 2459024-byte allocation
,D/dalvikvm( 3510): GC_CONCURRENT freed 388K, 21% free 18346K/23096K, paused 5ms+3ms, total 63ms
,D/dalvikvm( 3510): GC_FOR_ALLOC freed 4241K, 27% free 17028K/23096K, paused 38ms, total 38ms
,I/dalvikvm-heap( 3510): Grow heap (frag case) to 22.179MB for 3688532-byte allocation
,D/dalvikvm( 3510): GC_CONCURRENT freed 450K, 24% free 20525K/26700K, paused 5ms+7ms, total 71ms
,D/dalvikvm( 3510): GC_FOR_ALLOC freed 3103K, 33% free 17977K/26700K, paused 29ms, total 29ms
,W/jxcore-log( 3510): Initializing JXcore engine
,W/jxcore-log( 3510): JXcore engine is ready
,D/dalvikvm( 3510): GC_CONCURRENT freed 359K, 23% free 20595K/26700K, paused 1ms+2ms, total 29ms
,D/dalvikvm( 3510): WAIT_FOR_CONCURRENT_GC blocked 24ms
,W/jxcore-log( 3510): Starting JXcore engine
,W/jxcore-log( 3510): Platform android
W/jxcore-log( 3510): 
,W/jxcore-log( 3510): Process ARCH arm
W/jxcore-log( 3510): 
,I/jxcore-log( 3510): JXcore Cordova bridge is ready!
I/jxcore-log( 3510): 
,W/jxcore-log( 3510): JXcore engine is started
,I/chromium( 3510): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 3510): Error!: missing ) after argument list
E/jxcore  ( 3510): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 3510): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager( 1022): Killing 3275:com.android.calendar/u0a7 (adj 15): empty #9
W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1532): [info] > Updatetime from metadata: 10
,D/Checkin ( 1532): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1532): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1532): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1532): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1532): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1532): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,W/IInputConnectionWrapper( 3510): showStatusIcon on inactive InputConnection
,V/AlarmManager( 1022): sending alarm Alarm{43cd6b60 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{43c26e28 type 3 android}
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1022): sending alarm Alarm{43c1ef80 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{43bdeba8 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{43bd37d0 type 3 android}
,I/MMApiBackOffService( 1532): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1532): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1532): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1532): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1532): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1532): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/MMApiWebService( 1532): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1532): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1532): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1532): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1532): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1532): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1532): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1532): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1532): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1532): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1532): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1532): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1532): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1532): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/MMApiWebService( 1532): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/MMApiWebService( 1532): doRequest(): polling manager says we're not connected, returning with an error: 
,D/Checkin ( 1532): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1532): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1532): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1532): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1532): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1532): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1532): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1022): sending alarm Alarm{4321d888 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{4320ff58 type 3 android}
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1022): sending alarm Alarm{43204da8 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{431da140 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{431d5a28 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{4202cc08 type 2 android}
,D/ConnectivityService( 1022): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1022): sending alarm Alarm{42502368 type 0 com.android.vending}
,D/Finsky  ( 3106): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ConnectivityService( 1022): Done.
,D/ConnectivityService( 1022): Setting timer for 720seconds
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3106): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3106): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3106): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 3106): [1] WearSupportService.startHygiene: disabled
,D/Finsky  ( 3106): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 1022): sending alarm Alarm{430da600 type 0 com.android.vending}
D/Finsky  ( 3106): [1] DailyHygiene.reschedule: Scheduling new run in 31 minutes (failures=2)
D/DeviceConnectionService( 1213): client connected with version: 8296000
,D/dalvikvm( 1213): GC_EXPLICIT freed 1354K, 41% free 10256K/17224K, paused 2ms+6ms, total 34ms
,D/Finsky  ( 3106): [285] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,E/DataBuffer( 1213): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42241308)
,D/dalvikvm( 1022): GC_EXPLICIT freed 22601K, 65% free 17820K/50236K, paused 3ms+10ms, total 137ms
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1022): sending alarm Alarm{43138ab0 type 0 com.android.vending}
,D/Finsky  ( 3106): [270] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3106): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/AlarmManager( 1022): sending alarm Alarm{431cb548 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{431379a0 type 3 android}
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1022): sending alarm Alarm{428a7be0 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{42870be8 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{4285f7b0 type 3 android}
,I/MMApiBackOffService( 1532): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1532): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1532): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1532): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1532): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1532): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/MMApiWebService( 1532): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1532): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,E/MMApiProvisionService( 1532): ProvisionWS.Response: Missing mandatory message data in response from DM server...
D/Checkin ( 1532): publish the event [tag = MOT_CCE event name = LOG]
,E/MMApiProvisionService( 1532): ProvisionWS.Response.setError: error RadioDownError
I/MMApiBackOffService( 1532): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1532): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1532): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1532): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1532): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1532): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1532): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1532): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1532): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1532): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1532): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1532): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1532): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1532): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
D/Checkin ( 1532): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1532): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1532): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1532): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1022): sending alarm Alarm{42859030 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{42857af8 type 3 android}
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1340): GC_EXPLICIT freed 1335K, 39% free 10560K/17224K, paused 2ms+5ms, total 37ms
,V/AlarmManager( 1022): sending alarm Alarm{4284fb98 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{4278fe08 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{4278bb40 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{42760260 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{4275e468 type 3 android}
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1022): sending alarm Alarm{42733860 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{427233d8 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{425037a0 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{42228ff8 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{42044920 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{43191058 type 2 android}
,D/ConnectivityService( 1022): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1022): sending alarm Alarm{42502440 type 3 android}
,I/ProcessStatsService( 1022): Prepared write state in 28ms
,D/ConnectivityService( 1022): Done.
,V/AlarmManager( 1022): sending alarm Alarm{4289b2b8 type 2 com.motorola.ccc.cce}
,V/AlarmManager( 1022): sending alarm Alarm{4289b308 type 3 com.google.android.gms}
,V/AlarmManager( 1022): sending alarm Alarm{4289b358 type 3 com.google.android.gms}
,V/AlarmManager( 1022): sending alarm Alarm{4289b3a8 type 0 com.google.android.gms}
,D/ConnectivityService( 1022): Setting timer for 720seconds
,I/ProcessStatsService( 1022): Pruning old procstats: /data/system/procstats/state-2015-12-08-19-10-57.bin
D/CCE     ( 1532): Registering with Alarm Manager to restart CCE
,I/EventLogService( 1328): Aggregate from 1449668620591 (log), 1449668620591 (data)
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1022): sending alarm Alarm{42031f50 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{41fc6460 type 3 android}
,V/AlarmManager( 1022): sending alarm Alarm{440550d0 type 3 android}
,I/ActivityManager( 1022): Killing 3389:com.google.android.partnersetup/u0a25 (adj 15): empty for 1853s
,I/ActivityManager( 1022): Killing 3039:android.process.acore/u0a10 (adj 15): empty for 1853s
,I/ActivityManager( 1022): Killing 3362:com.android.defcontainer/u0a13 (adj 15): empty for 1854s
,W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 3654): 
D/AndroidRuntime( 3654): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3654): CheckJNI is OFF
D/dalvikvm( 3654): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3654): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3654): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3654): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3654): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3654): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3654): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3654): failed to load memtrack module: -2
D/AndroidRuntime( 3654): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1022): Force stopping com.test.thalitest appid=10451 user=-1: uninstall pkg
I/ActivityManager( 1022): Killing 3510:com.test.thalitest/u0a451 (adj 15): stop com.test.thalitest
W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
W/PackageSettings( 1022): Skipping PackageSetting{421cc7c0 com.example.hello/10442} due to missing metadata
I/ActivityManager( 1022): Force stopping com.test.thalitest appid=10451 user=0: pkg removed
D/dalvikvm( 2127): GC_EXPLICIT freed 4804K, 45% free 9603K/17224K, paused 3ms+7ms, total 40ms
I/InputReader( 1022): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager( 1022): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=3675 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "sms"
D/dalvikvm(  281): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 1ms+2ms, total 20ms
I/LatinIME:LogUtils( 1189): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449670616
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "smsto"
D/dalvikvm(  281): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 20ms
I/LatinIME:LogUtils( 1189): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
D/dalvikvm( 1301): GC_EXPLICIT freed 2788K, 33% free 11591K/17224K, paused 13ms+4ms, total 148ms
I/LatinIME:LogUtils( 1189): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
W/GeofencerStateMachine( 1213): Ignoring removeGeofence because network location is disabled.
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mms"
D/dalvikvm(  281): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 19ms
D/dalvikvm( 2160): GC_EXPLICIT freed 3587K, 42% free 10076K/17224K, paused 2ms+4ms, total 159ms
I/Launcher( 1301): Deferring update until onResume
D/dalvikvm( 1022): GC_EXPLICIT freed 1345K, 65% free 17794K/50236K, paused 11ms+14ms, total 152ms
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mmsto"
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "sms"
I/Launcher( 1301): Deferring update until onResume
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "smsto"
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mms"
I/LatinIME:LogUtils( 1189): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449670616
I/PackageManager( 1022): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1022):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1022):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1022):   Scheme: "mmsto"
D/BackupManagerService( 1022): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1022): removePackageParticipantsLocked: uid=10451 #1
D/VoicemailCleanupService( 3675): Cleaning up data for package: com.test.thalitest
I/InternalIcingCorporaPro( 2160): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager( 1022): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3703 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
D/dalvikvm( 1022): GC_EXPLICIT freed 562K, 65% free 17772K/50236K, paused 5ms+15ms, total 164ms
W/ContextImpl( 3703): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/dalvikvm( 3106): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3106): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 3106): VFY: replacing opcode 0x6e at 0x0013
D/PackageBroadcastService( 1328): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1328): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1328): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1328): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1328): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1328): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1328): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1340): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1340): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager( 1022): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3721 uid=10058 gids={50058}
D/gH_CompatibleDatabase( 1328): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1328): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1328): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1328): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1328): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1328): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1328): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/PeopleContactsSync( 1328): CP2 sync disabled
D/gH_CompatibleDatabase( 1328): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1328): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1328): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1328): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1328): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1328): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/dalvikvm( 1328): GC_CONCURRENT freed 1875K, 33% free 11637K/17224K, paused 4ms+6ms, total 60ms
I/Icing   ( 1328): doRemovePackageData com.test.thalitest
I/InternalIcingCorporaPro( 2160): UpdateCorporaTask done [took 167 ms] updated apps [took 167 ms] 
D/Documents( 3721): Loading roots for com.android.providers.downloads.documents
I/ActivityManager( 1022): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=3741 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
D/AndroidRuntime( 3654): Shutting down VM
D/dalvikvm( 3654): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 3ms
I/ContactLocale( 3675): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
D/Documents( 3721): Loading roots for com.android.externalstorage.documents
D/dalvikvm( 3741): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f0f670, skipping init
I/openssl ( 3741): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3741): Crypto mode 0 already enabled
I/ActivityManager( 1022): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3757 uid=10020 gids={50020, 1028, 1015, 1023}
I/ActivityManager( 1022): Killing 3675:android.process.acore/u0a10 (adj 15): empty #9
W/ContextImpl( 1230): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/ExternalStorage( 3757): After updating volumes, found 1 active roots
D/Documents( 3721): Updating roots due to change at content://com.android.externalstorage.documents/root
D/Documents( 3721): Loading roots for com.android.providers.media.documents
D/Documents( 3721): Loading roots for com.google.android.apps.docs.storage
D/Documents( 3721): Update found 7 roots in 170ms
D/Documents( 3721): Used cached roots for com.android.providers.downloads.documents
D/Documents( 3721): Loading roots for com.android.externalstorage.documents
D/Documents( 3721): Used cached roots for com.android.providers.media.documents
D/Documents( 3721): Used cached roots for com.google.android.apps.docs.storage
D/Documents( 3721): Update found 7 roots in 5ms

```
