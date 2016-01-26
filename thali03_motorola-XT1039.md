#### Test 5667282762e056f_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1017): sending alarm Alarm{43400d88 type 3 android}
,--------- beginning of /dev/log/main
D/AndroidRuntime( 3755): 
D/AndroidRuntime( 3755): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3755): CheckJNI is OFF
D/dalvikvm( 3755): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3755): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3755): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3755): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3755): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3755): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3755): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3755): failed to load memtrack module: -2
D/AndroidRuntime( 3755): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1017): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3755
W/WindowManager( 1017): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1017): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3771 uid=10138 gids={50138, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3755): Shutting down VM
D/dalvikvm( 3755): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+0ms, total 3ms
W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3771): Binding Chromium to main looper Looper (main, tid 1) {41f1e840}
I/LibraryLoader( 3771): Expected native library version number "",actual native library version number ""
I/chromium( 3771): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3771): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1017): Message: 20
D/BluetoothManagerService( 1017): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42139fe8:true
D/BluetoothAdapter( 3771): 1106458040: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3771): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3771): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3771): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3771): Local Branch: 
I/Adreno-EGL( 3771): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3771): Local Patches: NONE
I/Adreno-EGL( 3771): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 3771): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 3771): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 3771): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3771): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3771): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3771): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 3771): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 3771): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3771): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,I/dalvikvm( 3771): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3771): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3771): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3771): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3771): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3771): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 3771): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3771): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3771): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3771): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3771): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3771): Enabling debug mode 0
,W/AwContents( 3771): nativeOnDraw failed; clearing to background color.
,I/Keyboard.Facilitator( 1196): onFinishInput()
,W/IInputConnectionWrapper( 3771): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1017): Displayed com.test.thalitest/.MainActivity,cp,ca,439
I/ActivityManager( 1017): Displayed com.test.thalitest/.MainActivity: +411ms (total +439ms)
,D/JsMessageQueue( 3771): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3771): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f23458
,D/dalvikvm( 3771): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f23458
,D/jxcore_app_log( 3771): JniHelper::setJavaVM(0x41571fa8), pthread_self() = 1615148480
,I/chromium( 3771): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/dalvikvm( 3771): GC_CONCURRENT freed 2649K, 16% free 14540K/17224K, paused 3ms+3ms, total 40ms
,D/dalvikvm( 3771): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 3771): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 3771): GC_FOR_ALLOC freed 339K, 14% free 14830K/17224K, paused 28ms, total 28ms
,D/dalvikvm( 3771): GC_FOR_ALLOC freed 69K, 14% free 14834K/17224K, paused 26ms, total 27ms
,I/dalvikvm-heap( 3771): Grow heap (frag case) to 16.560MB for 42652-byte allocation
,D/dalvikvm( 3771): GC_FOR_ALLOC freed 92K, 14% free 14853K/17268K, paused 26ms, total 27ms
,D/dalvikvm( 3771): GC_FOR_ALLOC freed 127K, 14% free 14873K/17268K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3771): Grow heap (frag case) to 16.648MB for 95956-byte allocation
,D/dalvikvm( 3771): GC_FOR_ALLOC freed 179K, 15% free 14908K/17364K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3771): Grow heap (frag case) to 16.729MB for 143930-byte allocation
,D/dalvikvm( 3771): GC_FOR_ALLOC freed 254K, 15% free 14955K/17508K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3771): Grow heap (frag case) to 16.842MB for 215890-byte allocation
,D/dalvikvm( 3771): GC_FOR_ALLOC freed 366K, 16% free 15029K/17720K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3771): Grow heap (frag case) to 17.018MB for 323830-byte allocation
,D/dalvikvm( 3771): GC_FOR_ALLOC freed 567K, 17% free 15149K/18040K, paused 28ms, total 28ms
,I/dalvikvm-heap( 3771): Grow heap (frag case) to 17.291MB for 485740-byte allocation
,D/dalvikvm( 3771): GC_FOR_ALLOC freed 864K, 18% free 15326K/18516K, paused 28ms, total 28ms
,D/dalvikvm( 3771): GC_FOR_ALLOC freed 1232K, 16% free 15576K/18516K, paused 28ms, total 28ms
,D/dalvikvm( 3771): GC_FOR_ALLOC freed 75K, 16% free 15555K/18516K, paused 30ms, total 31ms
,I/dalvikvm-heap( 3771): Grow heap (frag case) to 18.266MB for 1092904-byte allocation
,D/dalvikvm( 3771): GC_CONCURRENT freed 1766K, 19% free 15967K/19584K, paused 3ms+3ms, total 34ms
,D/dalvikvm( 3771): GC_FOR_ALLOC freed 268K, 19% free 15894K/19584K, paused 27ms, total 28ms
,I/dalvikvm-heap( 3771): Grow heap (frag case) to 19.118MB for 1639352-byte allocation
,D/dalvikvm( 3771): GC_CONCURRENT freed 1744K, 23% free 16480K/21188K, paused 2ms+3ms, total 34ms
,D/dalvikvm( 3771): GC_FOR_ALLOC freed 1146K, 23% free 16486K/21188K, paused 29ms, total 30ms
,I/dalvikvm-heap( 3771): Grow heap (frag case) to 20.477MB for 2459024-byte allocation
,D/dalvikvm( 3771): GC_CONCURRENT freed 296K, 21% free 18844K/23592K, paused 4ms+3ms, total 47ms
,D/dalvikvm( 3771): GC_FOR_ALLOC freed 4236K, 26% free 17515K/23592K, paused 38ms, total 39ms
,I/dalvikvm-heap( 3771): Grow heap (frag case) to 22.655MB for 3688532-byte allocation
,D/dalvikvm( 3771): GC_CONCURRENT freed 403K, 24% free 20857K/27196K, paused 4ms+4ms, total 55ms
,D/dalvikvm( 3771): GC_FOR_ALLOC freed 4283K, 32% free 18620K/27196K, paused 33ms, total 33ms
,W/jxcore-log( 3771): Initializing JXcore engine
,W/jxcore-log( 3771): JXcore engine is ready
,D/dalvikvm( 3771): GC_CONCURRENT freed 420K, 22% free 21406K/27196K, paused 2ms+2ms, total 31ms
,D/dalvikvm( 3771): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 3771): WAIT_FOR_CONCURRENT_GC blocked 27ms
,W/jxcore-log( 3771): Starting JXcore engine
,W/jxcore-log( 3771): Platform android
W/jxcore-log( 3771): 
,W/jxcore-log( 3771): Process ARCH arm
W/jxcore-log( 3771): 
,I/jxcore-log( 3771): JXcore Cordova bridge is ready!
I/jxcore-log( 3771): 
,W/jxcore-log( 3771): JXcore engine is started
,E/jxcore  ( 3771): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 3771): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 3771): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager( 1017): Killing 3551:com.android.defcontainer/u0a13 (adj 15): empty #9
W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1653): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1653): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1653): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1653): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1653): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1653): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1653): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1653): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/Keyboard.Facilitator( 1196): onFinishInput()
,W/IInputConnectionWrapper( 3771): showStatusIcon on inactive InputConnection
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1017): sending alarm Alarm{44076cc0 type 3 android}
,I/Keyboard.Facilitator.LanguageModelFlusher( 1196): run()
,I/Keyboard.Facilitator( 1196): flushDynamicLanguageModels()
,I/ConfigService( 1213): onCreate
,I/ConfigService( 1213): onDestroy
,V/AlarmManager( 1017): sending alarm Alarm{43e2f888 type 3 android}
,I/MMApiBackOffService( 1653): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1653): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1653): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1653): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1653): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1653): doRequest(): polling manager says we're not connected, returning with an error: 
,D/MMApiWebService( 1653): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,E/MMApiProvisionService( 1653): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1653): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiWebService( 1653): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1653): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1653): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1653): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1653): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1653): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1653): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1653): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1653): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1653): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1653): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1653): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/Checkin ( 1653): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1653): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1653): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1653): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1653): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1653): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1653): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1653): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1017): sending alarm Alarm{43a1e108 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{430e18c0 type 2 com.google.android.gms}
,W/SocketClient(  273): write error (Broken pipe)
,D/ConnectivityService( 1017): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1017): sending alarm Alarm{434575c8 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{437e2308 type 3 android}
,D/dalvikvm( 1017): GC_EXPLICIT freed 986K, 65% free 18439K/52616K, paused 11ms+10ms, total 118ms
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1017): sending alarm Alarm{44073740 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{43e775b8 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{4384db08 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{43570800 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{434fdc48 type 3 android}
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1017): sending alarm Alarm{43374228 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{42920ce0 type 3 android}
,I/MMApiBackOffService( 1653): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1653): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1653): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1653): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1653): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1653): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,D/MMApiWebService( 1653): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1653): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1653): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1653): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1653): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1653): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1653): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1653): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1653): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1653): publish the event [tag = MOT_CCE event name = LOG]
,D/dalvikvm( 1653): GC_CONCURRENT freed 6288K, 38% free 10774K/17224K, paused 4ms+5ms, total 55ms
,D/Checkin ( 1653): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1653): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1653): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1653): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1653): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/Checkin ( 1653): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1653): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1653): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1653): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1653): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1653): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1653): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1653): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1017): sending alarm Alarm{428f8908 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{44054c98 type 2 android}
,D/ConnectivityService( 1017): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1017): sending alarm Alarm{42839350 type 2 com.google.android.gms}
,D/ConnectivityService( 1017): Done.
,D/ConnectivityService( 1017): Setting timer for 720seconds
,D/ConnectivityService( 1017): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  273): write error (Broken pipe)
,V/AlarmManager( 1017): sending alarm Alarm{42885e00 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{4281f040 type 3 android}
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1017): sending alarm Alarm{4281bec8 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{41f3e358 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{421100b0 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{427c5560 type 3 android}
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
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{424e73d8 type 3 android}
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
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1337): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3888): 
D/AndroidRuntime( 3888): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3888): CheckJNI is OFF
D/dalvikvm( 3888): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3888): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3888): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3888): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3888): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3888): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3888): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3888): failed to load memtrack module: -2
D/AndroidRuntime( 3888): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10138 user=-1: uninstall pkg
I/ActivityManager( 1017): Killing 3771:com.test.thalitest/u0a138 (adj 9): stop com.test.thalitest
W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10138 user=0: pkg removed
D/dalvikvm( 2239): GC_EXPLICIT freed 4770K, 45% free 9603K/17224K, paused 4ms+5ms, total 46ms
I/Keyboard.Facilitator( 1196): resetDictionaries() : en_GB
W/GeofencerStateMachine( 1213): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator.DecoderInitializer( 1196): run()
I/Decoder ( 1196): createOrResetDecoder
D/VoicemailCleanupService( 1179): Cleaning up data for package: com.test.thalitest
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "sms"
I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "smsto"
D/dalvikvm( 2271): GC_EXPLICIT freed 2813K, 42% free 10046K/17224K, paused 2ms+7ms, total 110ms
D/dalvikvm( 1300): GC_EXPLICIT freed 3152K, 33% free 11596K/17224K, paused 2ms+6ms, total 128ms
D/dalvikvm( 1739): GC_EXPLICIT freed 1480K, 33% free 11699K/17224K, paused 19ms+8ms, total 140ms
I/Launcher( 1300): Deferring update until onResume
D/dalvikvm( 1017): GC_EXPLICIT freed 846K, 65% free 18487K/52616K, paused 3ms+11ms, total 125ms
D/dalvikvm( 1017): WAIT_FOR_CONCURRENT_GC blocked 55ms
D/dalvikvm( 1017): GC_EXPLICIT freed 115K, 66% free 18396K/52616K, paused 3ms+9ms, total 89ms
I/ConfigService( 1213): onCreate
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mms"
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mmsto"
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "sms"
I/InternalIcingCorporaPro( 2271): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "smsto"
I/ActivityManager( 1017): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3919 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mms"
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mmsto"
I/Launcher( 1300): Deferring update until onResume
D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1017): removePackageParticipantsLocked: uid=10138 #1
I/Keyboard.Facilitator.MainLanguageModelLoader( 1196): run()
W/ContextImpl( 3919): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/dalvikvm( 3251): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3251): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 3251): VFY: replacing opcode 0x6e at 0x0013
D/PackageBroadcastService( 1739): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1739): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1739): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1739): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1739): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1739): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1739): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1337): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1337): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/AndroidRuntime( 3888): Shutting down VM
I/Keyboard.Facilitator.MainLanguageModelLoader( 1196): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_GB/main%00003aen_gb (offset=0, length=3633960) with up to date LoudsLmContentVersion = 20150512
D/dalvikvm( 3888): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 3ms
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
I/ActivityManager( 1017): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3943 uid=10058 gids={50058}
D/gH_CompatibleDatabase( 1739): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1739): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1739): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1739): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1739): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1739): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1739): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1739): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/Documents( 3943): Loading roots for com.android.providers.downloads.documents
D/gH_CompatibleDatabase( 1739): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1739): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1739): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1739): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1739): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/Documents( 3943): Loading roots for com.android.externalstorage.documents
I/ActivityManager( 1017): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3962 uid=10020 gids={50020, 1028, 1015, 1023}
I/ActivityManager( 1017): Killing 3578:com.google.android.partnersetup/u0a25 (adj 15): empty #9
W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/dalvikvm( 1213): GC_EXPLICIT freed 951K, 32% free 11731K/17224K, paused 3ms+7ms, total 49ms
I/ActivityManager( 1017): Killing 3604:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/InternalIcingCorporaPro( 2271): UpdateCorporaTask done [took 232 ms] updated apps [took 232 ms] 
I/Icing   ( 1739): doRemovePackageData com.test.thalitest
E/DataBuffer( 1213): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@423469a8)
E/DataBuffer( 1213): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4231fbf8)
E/DataBuffer( 1213): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@41f23f48)
E/DataBuffer( 1213): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@421e4600)
E/DataBuffer( 1213): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4238f790)
E/DataBuffer( 1213): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42277590)
E/DataBuffer( 1213): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4222d6d0)
E/DataBuffer( 1213): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4231cfd0)
E/DataBuffer( 1213): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4213fdf8)
E/DataBuffer( 1213): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42350b60)
E/DataBuffer( 1213): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4215b3e8)
E/DataBuffer( 1213): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4224c870)
E/DataBuffer( 1213): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4223dba8)
E/DataBuffer( 1213): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@422da3a0)
E/DataBuffer( 1213): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@41fdd4c8)
E/DataBuffer( 1213): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42161ca8)
D/ExternalStorage( 3962): After updating volumes, found 1 active roots
D/Documents( 3943): Updating roots due to change at content://com.android.externalstorage.documents/root
D/Documents( 3943): Loading roots for com.android.providers.media.documents
D/Documents( 3943): Loading roots for com.google.android.apps.docs.storage
D/Documents( 3943): Update found 7 roots in 96ms
D/Documents( 3943): Used cached roots for com.android.providers.downloads.documents
D/Documents( 3943): Loading roots for com.android.externalstorage.documents
D/Documents( 3943): Used cached roots for com.android.providers.media.documents
D/Documents( 3943): Used cached roots for com.google.android.apps.docs.storage
D/Documents( 3943): Update found 7 roots in 5ms

```
