#### Test 5761781115ba656_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
,V/AlarmManager( 1020): sending alarm Alarm{4417d298 type 3 android}
--------- beginning of /dev/log/main
D/AndroidRuntime( 3813): 
D/AndroidRuntime( 3813): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3813): CheckJNI is OFF
D/dalvikvm( 3813): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3813): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3813): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3813): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3813): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3813): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3813): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3813): failed to load memtrack module: -2
D/AndroidRuntime( 3813): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1020): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3813
W/WindowManager( 1020): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1020): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3829 uid=10145 gids={50145, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3813): Shutting down VM
D/dalvikvm( 3813): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+0ms, total 5ms
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3829): Binding Chromium to main looper Looper (main, tid 1) {4222b6f0}
I/LibraryLoader( 3829): Expected native library version number "",actual native library version number ""
I/chromium( 3829): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3829): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1020): Message: 20
D/BluetoothManagerService( 1020): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43a10668:true
D/BluetoothAdapter( 3829): 1109656664: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3829): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3829): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3829): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3829): Local Branch: 
I/Adreno-EGL( 3829): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3829): Local Patches: NONE
I/Adreno-EGL( 3829): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 3829): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 3829): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 3829): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3829): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3829): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3829): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 3829): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 3829): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3829): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,I/dalvikvm( 3829): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3829): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3829): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3829): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3829): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3829): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 3829): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3829): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3829): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3829): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3829): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3829): Enabling debug mode 0
,W/AwContents( 3829): nativeOnDraw failed; clearing to background color.
,I/Keyboard.Facilitator( 1196): onFinishInput()
,I/LaunchCheckinHandler( 1020): Displayed com.test.thalitest/.MainActivity,cp,ca,472
I/ActivityManager( 1020): Displayed com.test.thalitest/.MainActivity: +430ms (total +472ms)
W/AwContents( 3829): nativeOnDraw failed; clearing to background color.
W/IInputConnectionWrapper( 3829): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 3829): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3829): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422302f8
,D/dalvikvm( 3829): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422302f8
,D/jxcore_app_log( 3829): JniHelper::setJavaVM(0x41949f78), pthread_self() = 1613160296
,I/chromium( 3829): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/dalvikvm( 3829): GC_CONCURRENT freed 3360K, 20% free 13829K/17224K, paused 1ms+3ms, total 48ms
,D/dalvikvm( 3829): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/dalvikvm( 3829): GC_FOR_ALLOC freed 57K, 20% free 13827K/17224K, paused 25ms, total 26ms
,I/dalvikvm-heap( 3829): Grow heap (frag case) to 15.844MB for 323830-byte allocation
,D/dalvikvm( 3829): GC_FOR_ALLOC freed 631K, 21% free 13885K/17544K, paused 24ms, total 25ms
,I/dalvikvm-heap( 3829): Grow heap (frag case) to 16.055MB for 485740-byte allocation
,D/dalvikvm( 3829): GC_FOR_ALLOC freed 867K, 22% free 14061K/18020K, paused 24ms, total 25ms
,I/dalvikvm-heap( 3829): Grow heap (frag case) to 16.459MB for 728606-byte allocation
,D/dalvikvm( 3829): GC_FOR_ALLOC freed 1285K, 24% free 14317K/18732K, paused 25ms, total 26ms
,I/dalvikvm-heap( 3829): Grow heap (frag case) to 17.056MB for 1092904-byte allocation
,D/dalvikvm( 3829): GC_CONCURRENT freed 1778K, 26% free 14704K/19800K, paused 2ms+4ms, total 46ms
,D/dalvikvm( 3829): GC_FOR_ALLOC freed 283K, 27% free 14633K/19800K, paused 24ms, total 25ms
,I/dalvikvm-heap( 3829): Grow heap (frag case) to 17.886MB for 1639352-byte allocation
,D/dalvikvm( 3829): GC_CONCURRENT freed 1503K, 30% free 15190K/21404K, paused 1ms+3ms, total 36ms
,D/dalvikvm( 3829): GC_FOR_ALLOC freed 1564K, 29% free 15327K/21404K, paused 29ms, total 30ms
,I/dalvikvm-heap( 3829): Grow heap (frag case) to 19.346MB for 2459024-byte allocation
,D/dalvikvm( 3829): GC_CONCURRENT freed 248K, 18% free 17618K/21404K, paused 4ms+3ms, total 46ms
,D/dalvikvm( 3829): GC_FOR_ALLOC freed 3823K, 25% free 16200K/21404K, paused 31ms, total 32ms
,I/dalvikvm-heap( 3829): Grow heap (frag case) to 20.035MB for 2287544-byte allocation
,W/jxcore-log( 3829): Initializing JXcore engine
,W/jxcore-log( 3829): JXcore engine is ready
,W/jxcore-log( 3829): Starting JXcore engine
,D/dalvikvm( 3829): GC_CONCURRENT freed 572K, 23% free 18272K/23640K, paused 1ms+8ms, total 50ms
,W/jxcore-log( 3829): Platform android
W/jxcore-log( 3829): 
,W/jxcore-log( 3829): Process ARCH arm
W/jxcore-log( 3829): 
,I/jxcore-log( 3829): JXcore Cordova bridge is ready!
I/jxcore-log( 3829): 
,W/jxcore-log( 3829): JXcore engine is started
,E/jxcore  ( 3829): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 3829): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 3829): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager( 1020): Killing 3613:com.android.defcontainer/u0a13 (adj 15): empty #9
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1594): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1594): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1594): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1594): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1594): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1594): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1594): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1594): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/Keyboard.Facilitator( 1196): onFinishInput()
,W/IInputConnectionWrapper( 3829): showStatusIcon on inactive InputConnection
,V/AlarmManager( 1020): sending alarm Alarm{44199b78 type 2 com.google.android.gms}
,W/SocketClient(  271): write error (Broken pipe)
,D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1020): sending alarm Alarm{4417c958 type 3 android}
,I/Keyboard.Facilitator.LanguageModelFlusher( 1196): run()
,I/Keyboard.Facilitator( 1196): flushDynamicLanguageModels()
,I/ConfigService( 1218): onCreate
,I/ConfigService( 1218): onDestroy
,V/AlarmManager( 1020): sending alarm Alarm{44165380 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{436398a8 type 3 android}
,I/MMApiBackOffService( 1594): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1594): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/dalvikvm( 1020): GC_EXPLICIT freed 19266K, 58% free 18419K/43600K, paused 12ms+9ms, total 159ms
,D/MMApiWebService( 1594): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1594): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1594): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1594): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1594): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1594): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1594): ProvisionWS.Response: Missing mandatory message data in response from DM server...
I/MMApiWebService( 1594): MMApiWebService told us not to continue at the moment with this request: 
,E/MMApiProvisionService( 1594): ProvisionWS.Response.setError: error RadioDownError
D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1594): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1594): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
I/MMApiBackOffService( 1594): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1594): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1594): MMApiWebService told us not to continue at the moment with this request: devices.json
I/MMApiWebService( 1594): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1594): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1594): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1020): sending alarm Alarm{44161f90 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{4416bb10 type 2 com.google.android.gms}
,D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1020): sending alarm Alarm{442c2d38 type 3 android}
,D/dalvikvm( 1342): GC_EXPLICIT freed 1470K, 41% free 10315K/17224K, paused 2ms+4ms, total 84ms
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1020): sending alarm Alarm{4425f9f8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{439f1588 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{43849e00 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{437f93c0 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{437e4d80 type 3 android}
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1020): sending alarm Alarm{437dea88 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{437dc790 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{437db408 type 3 android}
,I/MMApiBackOffService( 1594): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1594): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1594): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1594): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1594): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1594): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/MMApiWebService( 1594): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
,E/MMApiProvisionService( 1594): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1594): ProvisionWS.Response.setError: error RadioDownError
I/MMApiBackOffService( 1594): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1594): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1594): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1594): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1594): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1594): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1594): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1594): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1594): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1594): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1594): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1020): sending alarm Alarm{441995a8 type 2 android}
,D/ConnectivityService( 1020): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1020): sending alarm Alarm{442a5b10 type 2 com.google.android.gms}
,D/ConnectivityService( 1020): Done.
,D/ConnectivityService( 1020): Setting timer for 720seconds
,D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1020): sending alarm Alarm{437d6f50 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{422c85f8 type 3 android}
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1342): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1020): sending alarm Alarm{42a307d8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{422bfe50 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{44178fb8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42b4c440 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42a328e8 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3949): 
D/AndroidRuntime( 3949): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3949): CheckJNI is OFF
D/dalvikvm( 3949): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3949): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3949): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3949): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3949): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3949): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3949): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3949): failed to load memtrack module: -2
D/AndroidRuntime( 3949): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10145 user=-1: uninstall pkg
I/ActivityManager( 1020): Killing 3829:com.test.thalitest/u0a145 (adj 9): stop com.test.thalitest
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10145 user=0: pkg removed
D/dalvikvm( 2217): GC_EXPLICIT freed 4782K, 45% free 9604K/17224K, paused 2ms+5ms, total 54ms
D/dalvikvm( 1299): GC_EXPLICIT freed 3152K, 33% free 11594K/17224K, paused 2ms+4ms, total 103ms
D/dalvikvm( 1020): GC_EXPLICIT freed 747K, 58% free 18347K/43600K, paused 5ms+25ms, total 122ms
I/Keyboard.Facilitator( 1196): resetDictionaries() : en_GB
I/Keyboard.Facilitator.DecoderInitializer( 1196): run()
D/dalvikvm( 2252): GC_EXPLICIT freed 3418K, 42% free 10059K/17224K, paused 2ms+10ms, total 137ms
I/Decoder ( 1196): createOrResetDecoder
I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
D/dalvikvm( 1725): GC_EXPLICIT freed 1431K, 32% free 11759K/17224K, paused 25ms+7ms, total 144ms
I/Launcher( 1299): Deferring update until onResume
W/GeofencerStateMachine( 1218): Ignoring removeGeofence because network location is disabled.
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
D/VoicemailCleanupService( 1178): Cleaning up data for package: com.test.thalitest
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
I/ConfigService( 1218): onCreate
I/Launcher( 1299): Deferring update until onResume
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
I/InternalIcingCorporaPro( 2252): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/BackupManagerService( 1020): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1020): removePackageParticipantsLocked: uid=10145 #1
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
I/ActivityManager( 1020): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3987 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
W/ContextImpl( 3987): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/Keyboard.Facilitator.MainLanguageModelLoader( 1196): run()
I/dalvikvm( 3279): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3279): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 3279): VFY: replacing opcode 0x6e at 0x0013
D/dalvikvm( 1020): GC_EXPLICIT freed 645K, 58% free 18438K/43600K, paused 4ms+17ms, total 191ms
D/dalvikvm( 1218): GC_EXPLICIT freed 1093K, 36% free 11128K/17224K, paused 3ms+7ms, total 40ms
E/DataBuffer( 1218): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42364b18)
E/DataBuffer( 1218): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4269e260)
E/DataBuffer( 1218): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42386c80)
E/DataBuffer( 1218): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42546568)
E/DataBuffer( 1218): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42337b88)
E/DataBuffer( 1218): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42359790)
E/DataBuffer( 1218): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@424b7518)
D/PackageBroadcastService( 1725): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
E/DataBuffer( 1218): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@425add50)
D/AccountUtils( 1725): Clearing selected account for com.test.thalitest
E/DataBuffer( 1218): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4233b7c8)
E/DataBuffer( 1218): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@423322e8)
E/DataBuffer( 1218): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4236de00)
E/DataBuffer( 1218): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4236b548)
D/ChimeraCfgMgr( 1725): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1725): Module APK com.google.android.play.games already loaded
E/DataBuffer( 1218): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@422e6848)
E/DataBuffer( 1218): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@423e1950)
E/DataBuffer( 1218): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@423786a0)
I/InternalIcingCorporaPro( 2252): UpdateCorporaTask done [took 147 ms] updated apps [took 147 ms] 
I/LocationSettingsChecker( 1725): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1725): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1725): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1342): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1342): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/Keyboard.Facilitator.MainLanguageModelLoader( 1196): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_GB/main%00003aen_gb (offset=0, length=3633960) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1196): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1196): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1196): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1196): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1196): run() : Loaded File = UserHistory.en_GB.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1196): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1196): run() : Missing File = Personal.en_GB.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1196): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1196): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1196): run()
I/StatsUtilsManager( 1196): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1196): shouldRecordStats() = Too Soon
I/Icing   ( 1725): doRemovePackageData com.test.thalitest
D/gH_CompatibleDatabase( 1725): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1725): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
I/ActivityManager( 1020): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4016 uid=10058 gids={50058}
D/gH_MetricsDatabase( 1725): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1725): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1725): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1725): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1725): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1725): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1725): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1725): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1725): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1725): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1725): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/AndroidRuntime( 3949): Shutting down VM
D/dalvikvm( 3949): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+1ms, total 2ms
D/Documents( 4016): Loading roots for com.android.providers.downloads.documents
D/Documents( 4016): Loading roots for com.android.externalstorage.documents
I/ActivityManager( 1020): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4032 uid=10020 gids={50020, 1028, 1015, 1023}
I/ActivityManager( 1020): Killing 3650:com.google.android.partnersetup/u0a25 (adj 15): empty #9
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1020): Killing 3675:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/ExternalStorage( 4032): After updating volumes, found 1 active roots
D/Documents( 4016): Updating roots due to change at content://com.android.externalstorage.documents/root
D/Documents( 4016): Loading roots for com.android.providers.media.documents
D/Documents( 4016): Loading roots for com.google.android.apps.docs.storage
D/Documents( 4016): Update found 7 roots in 111ms
D/Documents( 4016): Used cached roots for com.android.providers.downloads.documents
D/Documents( 4016): Loading roots for com.android.externalstorage.documents
D/Documents( 4016): Used cached roots for com.android.providers.media.documents
D/Documents( 4016): Used cached roots for com.google.android.apps.docs.storage
D/Documents( 4016): Update found 7 roots in 8ms

```
