#### Test 57531243c766d4e_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
,V/AlarmManager( 1018): sending alarm Alarm{443bf0e0 type 2 com.google.android.gms}
D/ConnectivityService( 1018): handleInetConditionChange: no active default network - ignore
--------- beginning of /dev/log/main
D/AndroidRuntime( 3856): 
D/AndroidRuntime( 3856): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3856): CheckJNI is OFF
D/dalvikvm( 3856): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3856): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3856): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3856): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3856): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3856): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3856): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3856): failed to load memtrack module: -2
D/AndroidRuntime( 3856): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1018): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3856
W/WindowManager( 1018): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1018): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3872 uid=10105 gids={50105, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3856): Shutting down VM
D/dalvikvm( 3856): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 2ms
W/ContextImpl( 1261): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1261): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3872): Binding Chromium to main looper Looper (main, tid 1) {4247fd80}
I/LibraryLoader( 3872): Expected native library version number "",actual native library version number ""
I/chromium( 3872): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3872): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1018): Message: 20
D/BluetoothManagerService( 1018): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@444b3548:true
D/BluetoothAdapter( 3872): 1112097200: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3872): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3872): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3872): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3872): Local Branch: 
I/Adreno-EGL( 3872): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3872): Local Patches: NONE
I/Adreno-EGL( 3872): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3872): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 3872): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 3872): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3872): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3872): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3872): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 3872): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 3872): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 3872): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3872): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3872): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3872): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3872): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3872): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3872): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 3872): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3872): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3872): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3872): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3872): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3872): Enabling debug mode 0
,W/AwContents( 3872): nativeOnDraw failed; clearing to background color.
,I/Keyboard.Facilitator( 1195): onFinishInput()
,I/LaunchCheckinHandler( 1018): Displayed com.test.thalitest/.MainActivity,cp,ca,409
I/ActivityManager( 1018): Displayed com.test.thalitest/.MainActivity: +379ms (total +409ms)
W/AwContents( 3872): nativeOnDraw failed; clearing to background color.
W/IInputConnectionWrapper( 3872): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 3872): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3872): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42484050
,D/dalvikvm( 3872): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42484050
,D/jxcore_app_log( 3872): JniHelper::setJavaVM(0x41b9bf78), pthread_self() = 1614305304
,I/chromium( 3872): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/dalvikvm( 3872): GC_CONCURRENT freed 3357K, 20% free 13832K/17224K, paused 3ms+3ms, total 45ms
,D/dalvikvm( 3872): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 3872): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 3872): GC_FOR_ALLOC freed 98K, 20% free 13802K/17224K, paused 24ms, total 24ms
,I/dalvikvm-heap( 3872): Grow heap (frag case) to 15.819MB for 323830-byte allocation
,D/dalvikvm( 3872): GC_FOR_ALLOC freed 602K, 21% free 13888K/17544K, paused 23ms, total 24ms
,I/dalvikvm-heap( 3872): Grow heap (frag case) to 16.058MB for 485740-byte allocation
,D/dalvikvm( 3872): GC_FOR_ALLOC freed 865K, 22% free 14064K/18020K, paused 24ms, total 24ms
,I/dalvikvm-heap( 3872): Grow heap (frag case) to 16.461MB for 728606-byte allocation
,D/dalvikvm( 3872): GC_FOR_ALLOC freed 1285K, 24% free 14320K/18732K, paused 25ms, total 26ms
,I/dalvikvm-heap( 3872): Grow heap (frag case) to 17.059MB for 1092904-byte allocation
,D/dalvikvm( 3872): GC_CONCURRENT freed 1730K, 26% free 14732K/19800K, paused 2ms+3ms, total 39ms
,D/dalvikvm( 3872): GC_FOR_ALLOC freed 323K, 27% free 14642K/19800K, paused 25ms, total 26ms
,I/dalvikvm-heap( 3872): Grow heap (frag case) to 17.895MB for 1639352-byte allocation
,D/dalvikvm( 3872): GC_CONCURRENT freed 1505K, 30% free 15192K/21404K, paused 2ms+3ms, total 29ms
,D/dalvikvm( 3872): GC_FOR_ALLOC freed 1568K, 29% free 15331K/21404K, paused 29ms, total 31ms
,I/dalvikvm-heap( 3872): Grow heap (frag case) to 19.349MB for 2459024-byte allocation
,D/dalvikvm( 3872): GC_CONCURRENT freed 152K, 18% free 17619K/21404K, paused 4ms+4ms, total 33ms
,D/dalvikvm( 3872): GC_FOR_ALLOC freed 3914K, 25% free 16213K/21404K, paused 32ms, total 34ms
,I/dalvikvm-heap( 3872): Grow heap (frag case) to 20.048MB for 2288606-byte allocation
,W/jxcore-log( 3872): Initializing JXcore engine
,W/jxcore-log( 3872): JXcore engine is ready
,W/jxcore-log( 3872): Starting JXcore engine
,D/dalvikvm( 3872): GC_CONCURRENT freed 555K, 23% free 18302K/23640K, paused 2ms+3ms, total 34ms
,W/jxcore-log( 3872): Platform android
W/jxcore-log( 3872): 
,W/jxcore-log( 3872): Process ARCH arm
W/jxcore-log( 3872): 
,I/jxcore-log( 3872): JXcore Cordova bridge is ready!
I/jxcore-log( 3872): 
,W/jxcore-log( 3872): JXcore engine is started
,E/jxcore  ( 3872): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 3872): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 3872): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager( 1018): Killing 3655:com.android.defcontainer/u0a13 (adj 15): empty #9
W/ContextImpl( 1261): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1261): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1261): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1575): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1575): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1575): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1575): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1575): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 1575): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1575): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
D/OtaApp  ( 1575): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/Keyboard.Facilitator( 1195): onFinishInput()
W/IInputConnectionWrapper( 3872): showStatusIcon on inactive InputConnection
,V/AlarmManager( 1018): sending alarm Alarm{436c9208 type 3 android}
,V/GLSActivity( 2100): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2100): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Keyboard.Facilitator.LanguageModelFlusher( 1195): run()
,I/Keyboard.Facilitator( 1195): flushDynamicLanguageModels()
,I/ConfigService( 1214): onCreate
,I/ConfigService( 1214): onDestroy
,V/AlarmManager( 1018): sending alarm Alarm{4406b990 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{44487ab8 type 3 android}
,I/MMApiBackOffService( 1575): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1575): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1575): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1575): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1575): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1575): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1575): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
,D/dalvikvm( 1018): GC_EXPLICIT freed 951K, 61% free 18408K/47012K, paused 9ms+9ms, total 111ms
,D/MMApiWebService( 1575): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/MMApiWebService( 1575): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1575): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/MMApiWebService( 1575): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1575): ProvisionWS.Response: Missing mandatory message data in response from DM server...
I/MMApiWebService( 1575): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1575): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1575): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1575): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1575): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1575): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1575): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1018): sending alarm Alarm{436c6028 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{42df00c0 type 2 com.google.android.gms}
,D/ConnectivityService( 1018): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1018): sending alarm Alarm{44495530 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{43f20f98 type 3 android}
,V/GLSActivity( 2100): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2100): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1018): sending alarm Alarm{43d4ace8 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{436d8cd8 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{436d3860 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{436d25b8 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{436d17d0 type 3 android}
,V/GLSActivity( 2100): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2100): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1018): sending alarm Alarm{436cf708 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{436c76a8 type 3 android}
,I/MMApiBackOffService( 1575): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1575): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1575): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/MMApiWebService( 1575): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1575): doRequest(): polling manager says we're not connected, returning with an error: 
D/MMApiWebService( 1575): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1575): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1575): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1575): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1575): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1575): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1575): MMApiWebService told us not to continue at the moment with this request: 
D/MMApiWebService( 1575): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1575): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1575): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1575): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1575): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1575): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1575): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1018): sending alarm Alarm{436c17f0 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{448c6598 type 2 android}
,D/ConnectivityService( 1018): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1018): sending alarm Alarm{43fb1480 type 2 com.google.android.gms}
,D/ConnectivityService( 1018): Done.
,D/ConnectivityService( 1018): Setting timer for 720seconds
,D/ConnectivityService( 1018): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1018): sending alarm Alarm{436b8bb0 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{42ca8b30 type 3 android}
,V/GLSActivity( 2100): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2100): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1018): sending alarm Alarm{425ee528 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{424ef458 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{42cdd288 type 3 android}
,V/AlarmManager( 1018): sending alarm Alarm{42801ad0 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3983): 
D/AndroidRuntime( 3983): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3983): CheckJNI is OFF
D/dalvikvm( 3983): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3983): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3983): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3983): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3983): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3983): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3983): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3983): failed to load memtrack module: -2
D/AndroidRuntime( 3983): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10105 user=-1: uninstall pkg
I/ActivityManager( 1018): Killing 3872:com.test.thalitest/u0a105 (adj 9): stop com.test.thalitest
W/ContextImpl( 1261): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/dalvikvm( 1018): Total arena pages for JIT: 15
I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10105 user=0: pkg removed
D/dalvikvm( 2238): GC_EXPLICIT freed 4761K, 45% free 9604K/17224K, paused 2ms+5ms, total 36ms
D/dalvikvm( 1655): GC_EXPLICIT freed 428K, 33% free 11701K/17224K, paused 4ms+4ms, total 134ms
D/dalvikvm( 2270): GC_EXPLICIT freed 2784K, 43% free 9833K/17224K, paused 2ms+4ms, total 123ms
D/dalvikvm( 1018): GC_EXPLICIT freed 790K, 62% free 18309K/47012K, paused 5ms+11ms, total 96ms
I/Keyboard.Facilitator( 1195): resetDictionaries() : en_GB
W/GeofencerStateMachine( 1214): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator.DecoderInitializer( 1195): run()
I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
I/Decoder ( 1195): createOrResetDecoder
D/VoicemailCleanupService( 1174): Cleaning up data for package: com.test.thalitest
D/dalvikvm( 1305): GC_EXPLICIT freed 3152K, 33% free 11595K/17224K, paused 2ms+20ms, total 125ms
I/Launcher( 1305): Deferring update until onResume
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
I/ConfigService( 1214): onCreate
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
I/InternalIcingCorporaPro( 2270): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager( 1018): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4014 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "sms"
D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1018): removePackageParticipantsLocked: uid=10105 #1
W/dalvikvm( 1214): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "smsto"
I/Launcher( 1305): Deferring update until onResume
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mms"
E/dalvikvm( 1214): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 1214): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
D/dalvikvm( 1214): VFY: replacing opcode 0x1f at 0x00f6
W/dalvikvm( 1214): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
I/dalvikvm( 1214): Could not find method android.telephony.SubscriptionManager.getActiveSubscriptionInfoList, referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 1214): VFY: unable to resolve virtual method 6547: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
D/dalvikvm( 1214): VFY: replacing opcode 0x6e at 0x0004
D/dalvikvm( 1214): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
I/PackageManager( 1018): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1018):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1018):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1018):   Scheme: "mmsto"
W/dalvikvm( 1214): VFY: unable to resolve static field 229 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 1214): VFY: replacing opcode 0x62 at 0x0008
W/ContextImpl( 4014): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
D/dalvikvm( 1214): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
I/dalvikvm( 1214): DexOpt: unable to optimize static field ref 0x00e5 at 0x0c in Lcom/google/android/gms/checkin/d;.a
I/CheckinRequestBuilder( 1214): Classify the device as Phone.
E/dalvikvm( 1214): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
W/dalvikvm( 1214): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
D/dalvikvm( 1214): VFY: replacing opcode 0x1f at 0x000e
D/PackageBroadcastService( 1655): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1655): Clearing selected account for com.test.thalitest
I/dalvikvm( 3346): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3346): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 3346): VFY: replacing opcode 0x6e at 0x0013
I/LocationSettingsChecker( 1655): Removing dialog suppression flag for package com.test.thalitest
W/dalvikvm( 1214): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1214): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1214): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1214): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1214): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
D/dalvikvm( 1214): VFY: replacing opcode 0x6e at 0x00bb
I/dalvikvm( 1214): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1214): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
D/dalvikvm( 1214): VFY: replacing opcode 0x6e at 0x003d
D/ChimeraCfgMgr( 1655): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1655): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 2100): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 2100): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/ChimeraCfgMgr( 1655): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1655): Module APK com.google.android.play.games already loaded
W/FetchTask( 1214): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/gH_CompatibleDatabase( 1655): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1655): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
I/ActivityManager( 1018): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4047 uid=10058 gids={50058}
D/gH_MetricsDatabase( 1655): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1655): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/Icing   ( 1655): doRemovePackageData com.test.thalitest
I/InternalIcingCorporaPro( 2270): UpdateCorporaTask done [took 191 ms] updated apps [took 190 ms] 
I/CheckinRequestBuilder( 1214): Classify the device as Phone.
D/gH_CompatibleDatabase( 1655): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1655): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1655): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
W/FetchTask( 1214): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/gH_CompatibleDatabase( 1655): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1655): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1655): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1655): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1655): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1655): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/CheckinRequestBuilder( 1214): Classify the device as Phone.
D/dalvikvm( 1018): GC_EXPLICIT freed 765K, 61% free 18433K/47012K, paused 8ms+16ms, total 322ms
W/FetchTask( 1214): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/Documents( 4047): Loading roots for com.android.providers.downloads.documents
D/Documents( 4047): Loading roots for com.android.externalstorage.documents
I/CheckinRequestBuilder( 1214): Classify the device as Phone.
I/ActivityManager( 1018): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4064 uid=10020 gids={50020, 1028, 1015, 1023}
I/ActivityManager( 1018): Killing 3677:com.google.android.partnersetup/u0a25 (adj 15): empty #9
W/ContextImpl( 1261): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
W/FetchTask( 1214): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/dalvikvm(  275): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+3ms, total 22ms
I/ActivityManager( 1018): Killing 3701:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1261): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/dalvikvm(  275): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 17ms
D/ExternalStorage( 4064): After updating volumes, found 1 active roots
D/Documents( 4047): Updating roots due to change at content://com.android.externalstorage.documents/root
D/Documents( 4047): Loading roots for com.android.providers.media.documents
D/dalvikvm(  275): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 18ms
D/Documents( 4047): Loading roots for com.google.android.apps.docs.storage
I/CheckinRequestBuilder( 1214): Classify the device as Phone.
W/FetchTask( 1214): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/Documents( 4047): Update found 7 roots in 112ms
D/Documents( 4047): Used cached roots for com.android.providers.downloads.documents
D/Documents( 4047): Loading roots for com.android.externalstorage.documents
D/Documents( 4047): Used cached roots for com.android.providers.media.documents
D/Documents( 4047): Used cached roots for com.google.android.apps.docs.storage
D/Documents( 4047): Update found 7 roots in 7ms
D/AndroidRuntime( 3983): Shutting down VM
D/dalvikvm( 3983): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
I/Keyboard.Facilitator.MainLanguageModelLoader( 1195): run()
D/dalvikvm( 1214): GC_EXPLICIT freed 1644K, 36% free 11173K/17224K, paused 3ms+6ms, total 38ms
E/DataBuffer( 1214): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@428f52e8)
E/DataBuffer( 1214): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4256dd70)
E/DataBuffer( 1214): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@428a9a98)
E/DataBuffer( 1214): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42635bc8)
E/DataBuffer( 1214): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42895ed8)
E/DataBuffer( 1214): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4266f020)
E/DataBuffer( 1214): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@425c7ed8)
E/DataBuffer( 1214): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42684c98)
E/DataBuffer( 1214): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42605968)
E/DataBuffer( 1214): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@428f9878)
E/DataBuffer( 1214): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@426f5250)
E/DataBuffer( 1214): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@426053b0)
E/DataBuffer( 1214): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4267c7f8)
E/DataBuffer( 1214): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42663c88)
E/DataBuffer( 1214): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42605db8)
I/Keyboard.Facilitator.MainLanguageModelLoader( 1195): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_GB/main%00003aen_gb (offset=0, length=3633960) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1195): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1195): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1195): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1195): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1195): run() : Loaded File = UserHistory.en_GB.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1195): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1195): run() : Missing File = Personal.en_GB.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1195): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1195): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1195): run()
I/StatsUtilsManager( 1195): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1195): shouldRecordStats() = Too Soon

```
