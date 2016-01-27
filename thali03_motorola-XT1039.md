#### Test 568182540458528_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
,V/AlarmManager( 1020): sending alarm Alarm{4409b728 type 3 android}
--------- beginning of /dev/log/main
D/AndroidRuntime( 3751): 
D/AndroidRuntime( 3751): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3751): CheckJNI is OFF
D/dalvikvm( 3751): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3751): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3751): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3751): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3751): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3751): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3751): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3751): failed to load memtrack module: -2
D/AndroidRuntime( 3751): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1020): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3751
W/WindowManager( 1020): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1020): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3767 uid=10139 gids={50139, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3751): Shutting down VM
D/dalvikvm( 3751): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+1ms, total 3ms
W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3767): Binding Chromium to main looper Looper (main, tid 1) {41f89f48}
I/LibraryLoader( 3767): Expected native library version number "",actual native library version number ""
I/chromium( 3767): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3767): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1020): Message: 20
D/BluetoothManagerService( 1020): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43ce0410:true
D/BluetoothAdapter( 3767): 1106895736: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3767): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3767): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3767): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3767): Local Branch: 
I/Adreno-EGL( 3767): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3767): Local Patches: NONE
I/Adreno-EGL( 3767): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 3767): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 3767): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3767): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3767): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3767): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3767): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 3767): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 3767): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3767): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3767): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3767): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3767): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3767): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3767): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3767): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3767): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3767): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3767): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3767): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3767): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3767): Enabling debug mode 0
,W/AwContents( 3767): nativeOnDraw failed; clearing to background color.
,I/Keyboard.Facilitator( 1193): onFinishInput()
,W/IInputConnectionWrapper( 3767): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1020): Displayed com.test.thalitest/.MainActivity,cp,ca,421
I/ActivityManager( 1020): Displayed com.test.thalitest/.MainActivity: +396ms (total +421ms)
,D/JsMessageQueue( 3767): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3767): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f8e218
,D/dalvikvm( 3767): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f8e218
,D/jxcore_app_log( 3767): JniHelper::setJavaVM(0x415d9fa8), pthread_self() = 1614817648
,I/chromium( 3767): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/dalvikvm( 3767): GC_CONCURRENT freed 2655K, 16% free 14534K/17224K, paused 2ms+3ms, total 41ms
,D/dalvikvm( 3767): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 3767): GC_FOR_ALLOC freed 400K, 14% free 14849K/17224K, paused 27ms, total 27ms
,D/dalvikvm( 3767): GC_FOR_ALLOC freed 104K, 14% free 14855K/17224K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3767): Grow heap (frag case) to 16.601MB for 63974-byte allocation
,D/dalvikvm( 3767): GC_FOR_ALLOC freed 126K, 14% free 14875K/17288K, paused 26ms, total 27ms
,I/dalvikvm-heap( 3767): Grow heap (frag case) to 16.651MB for 95956-byte allocation
,D/dalvikvm( 3767): GC_FOR_ALLOC freed 179K, 15% free 14910K/17384K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3767): Grow heap (frag case) to 16.731MB for 143930-byte allocation
,D/dalvikvm( 3767): GC_FOR_ALLOC freed 254K, 15% free 14957K/17528K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3767): Grow heap (frag case) to 16.845MB for 215890-byte allocation
,D/dalvikvm( 3767): GC_FOR_ALLOC freed 367K, 16% free 15031K/17740K, paused 26ms, total 27ms
,I/dalvikvm-heap( 3767): Grow heap (frag case) to 17.021MB for 323830-byte allocation
,D/dalvikvm( 3767): GC_FOR_ALLOC freed 568K, 17% free 15151K/18060K, paused 28ms, total 29ms
,D/dalvikvm( 3767): GC_FOR_ALLOC freed 864K, 16% free 15328K/18060K, paused 27ms, total 28ms
,I/dalvikvm-heap( 3767): Grow heap (frag case) to 17.696MB for 728606-byte allocation
,D/dalvikvm( 3767): GC_FOR_ALLOC freed 1283K, 17% free 15584K/18772K, paused 28ms, total 28ms
,I/dalvikvm-heap( 3767): Grow heap (frag case) to 18.293MB for 1092904-byte allocation
,D/dalvikvm( 3767): GC_CONCURRENT freed 1819K, 20% free 16004K/19840K, paused 1ms+3ms, total 43ms
,D/dalvikvm( 3767): GC_FOR_ALLOC freed 245K, 20% free 15893K/19840K, paused 27ms, total 28ms
,I/dalvikvm-heap( 3767): Grow heap (frag case) to 19.117MB for 1639352-byte allocation
,D/dalvikvm( 3767): GC_CONCURRENT freed 1767K, 23% free 16535K/21444K, paused 2ms+4ms, total 48ms
,D/dalvikvm( 3767): GC_FOR_ALLOC freed 1122K, 24% free 16485K/21444K, paused 29ms, total 29ms
,I/dalvikvm-heap( 3767): Grow heap (frag case) to 20.477MB for 2459024-byte allocation
,D/dalvikvm( 3767): GC_CONCURRENT freed 1888K, 28% free 17233K/23848K, paused 4ms+4ms, total 42ms
,D/dalvikvm( 3767): GC_CONCURRENT freed 2475K, 27% free 17501K/23848K, paused 2ms+8ms, total 47ms
,D/dalvikvm( 3767): GC_FOR_ALLOC freed 191K, 27% free 17493K/23848K, paused 29ms, total 29ms
,I/dalvikvm-heap( 3767): Grow heap (frag case) to 22.633MB for 3688532-byte allocation
,D/dalvikvm( 3767): GC_CONCURRENT freed 158K, 12% free 21116K/23848K, paused 5ms+4ms, total 50ms
,D/dalvikvm( 3767): GC_FOR_ALLOC freed 4521K, 11% free 18621K/20828K, paused 34ms, total 34ms
,I/dalvikvm-heap( 3767): Grow heap (frag case) to 23.104MB for 3026370-byte allocation
,W/jxcore-log( 3767): Initializing JXcore engine
,W/jxcore-log( 3767): JXcore engine is ready
,W/jxcore-log( 3767): Starting JXcore engine
,D/dalvikvm( 3767): GC_CONCURRENT freed 499K, 10% free 21486K/23784K, paused 3ms+4ms, total 41ms
,W/jxcore-log( 3767): Platform android
W/jxcore-log( 3767): 
,W/jxcore-log( 3767): Process ARCH arm
W/jxcore-log( 3767): 
,I/jxcore-log( 3767): JXcore Cordova bridge is ready!
I/jxcore-log( 3767): 
,W/jxcore-log( 3767): JXcore engine is started
,E/jxcore  ( 3767): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 3767): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 3767): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager( 1020): Killing 3545:com.android.defcontainer/u0a13 (adj 15): empty #9
W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1597): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1597): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1597): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1597): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1597): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1597): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1597): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1597): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/Keyboard.Facilitator( 1193): onFinishInput()
,W/IInputConnectionWrapper( 3767): showStatusIcon on inactive InputConnection
,D/dalvikvm( 1597): GC_CONCURRENT freed 6286K, 38% free 10783K/17224K, paused 2ms+4ms, total 45ms
,D/dalvikvm( 1020): GC_EXPLICIT freed 24598K, 66% free 18475K/53208K, paused 5ms+10ms, total 158ms
,V/GLSActivity( 2099): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2099): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1020): sending alarm Alarm{44092898 type 3 android}
,I/Keyboard.Facilitator.LanguageModelFlusher( 1193): run()
,I/Keyboard.Facilitator( 1193): flushDynamicLanguageModels()
,I/ConfigService( 1209): onCreate
,I/ConfigService( 1209): onDestroy
,V/AlarmManager( 1020): sending alarm Alarm{4468b9c0 type 3 android}
,I/MMApiBackOffService( 1597): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1597): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1597): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1597): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1597): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,D/MMApiWebService( 1597): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1597): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1597): ProvisionWS.Response.setError: error RadioDownError
I/MMApiWebService( 1597): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1597): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1597): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1597): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1597): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1597): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1597): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1597): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1597): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1597): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1597): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1020): sending alarm Alarm{4406d380 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{44095190 type 2 com.google.android.gms}
,D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1020): sending alarm Alarm{43faded8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{43eeebe8 type 3 android}
,V/GLSActivity( 2099): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2099): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1020): sending alarm Alarm{43ee6f68 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{43964210 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{43818350 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{4297d010 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{4297c0f0 type 3 android}
,V/GLSActivity( 2099): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2099): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1020): sending alarm Alarm{42966b00 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{440bc5e8 type 2 android}
,D/ConnectivityService( 1020): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1020): sending alarm Alarm{43ef0968 type 2 com.google.android.gms}
,D/ConnectivityService( 1020): Done.
,D/ConnectivityService( 1020): Setting timer for 720seconds
,D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1020): sending alarm Alarm{428b1f10 type 3 android}
,I/MMApiBackOffService( 1597): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1597): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1597): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1597): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1597): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,E/MMApiProvisionService( 1597): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,D/MMApiWebService( 1597): doRequest(): polling manager says we're not connected, returning with an error: 
,E/MMApiProvisionService( 1597): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiWebService( 1597): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1597): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1597): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1597): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1597): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1597): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1597): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/MMApiWebService( 1597): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1597): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1597): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1597): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1597): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1020): sending alarm Alarm{4278d3e0 type 3 android}
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{420d0260 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42298858 type 3 android}
,V/GLSActivity( 2099): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2099): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1020): sending alarm Alarm{424ce9f0 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42800ce8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{421d53c8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42850c70 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42784ab8 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3882): 
D/AndroidRuntime( 3882): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3882): CheckJNI is OFF
D/dalvikvm( 3882): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3882): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3882): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3882): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3882): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3882): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3882): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3882): failed to load memtrack module: -2
D/AndroidRuntime( 3882): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10139 user=-1: uninstall pkg
I/ActivityManager( 1020): Killing 3767:com.test.thalitest/u0a139 (adj 9): stop com.test.thalitest
W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10139 user=0: pkg removed
D/dalvikvm( 2241): GC_EXPLICIT freed 4914K, 45% free 9611K/17224K, paused 2ms+5ms, total 45ms
I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1193): resetDictionaries() : en_GB
W/GeofencerStateMachine( 1209): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator.DecoderInitializer( 1193): run()
I/Decoder ( 1193): createOrResetDecoder
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
D/dalvikvm( 1298): GC_EXPLICIT freed 3152K, 33% free 11594K/17224K, paused 2ms+5ms, total 101ms
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
I/Launcher( 1298): Deferring update until onResume
D/VoicemailCleanupService( 1180): Cleaning up data for package: com.test.thalitest
D/dalvikvm( 2273): GC_EXPLICIT freed 3856K, 42% free 10124K/17224K, paused 3ms+21ms, total 149ms
D/dalvikvm( 1020): GC_EXPLICIT freed 1014K, 66% free 18433K/53208K, paused 5ms+10ms, total 130ms
D/dalvikvm( 1020): WAIT_FOR_CONCURRENT_GC blocked 59ms
D/dalvikvm( 1693): GC_EXPLICIT freed 1183K, 33% free 11681K/17224K, paused 34ms+6ms, total 178ms
D/dalvikvm( 1209): GC_EXPLICIT freed 1038K, 36% free 11092K/17224K, paused 3ms+8ms, total 49ms
E/DataBuffer( 1209): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@421535c8)
E/DataBuffer( 1209): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4207e738)
I/ConfigService( 1209): onCreate
E/DataBuffer( 1209): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4211be80)
E/DataBuffer( 1209): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42291e30)
E/DataBuffer( 1209): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4216c5c8)
E/DataBuffer( 1209): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42256288)
E/DataBuffer( 1209): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4234bb30)
E/DataBuffer( 1209): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4220d390)
E/DataBuffer( 1209): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4211e9c8)
E/DataBuffer( 1209): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4230e640)
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
I/Launcher( 1298): Deferring update until onResume
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
I/InternalIcingCorporaPro( 2273): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
I/ActivityManager( 1020): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3916 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
D/BackupManagerService( 1020): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1020): removePackageParticipantsLocked: uid=10139 #1
W/ContextImpl( 3916): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
D/PackageBroadcastService( 1693): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/Keyboard.Facilitator.MainLanguageModelLoader( 1193): run()
D/AccountUtils( 1693): Clearing selected account for com.test.thalitest
I/dalvikvm( 3270): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3270): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 3270): VFY: replacing opcode 0x6e at 0x0013
D/ChimeraCfgMgr( 1693): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1693): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1693): Removing dialog suppression flag for package com.test.thalitest
E/NetworkScheduler.SchedulerReceiver( 2099): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 2099): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/ChimeraCfgMgr( 1693): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1693): Module APK com.google.android.play.games already loaded
I/Keyboard.Facilitator.MainLanguageModelLoader( 1193): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_GB/main%00003aen_gb (offset=0, length=3633960) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1193): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1193): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1193): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1193): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1193): run() : Loaded File = UserHistory.en_GB.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1193): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1193): run() : Missing File = Personal.en_GB.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1193): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1193): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1193): run()
I/StatsUtilsManager( 1193): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1193): shouldRecordStats() = Too Soon
I/ActivityManager( 1020): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3942 uid=10058 gids={50058}
D/gH_CompatibleDatabase( 1693): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1693): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1693): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1693): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1693): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1693): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1693): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1693): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1693): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1693): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1693): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1693): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1693): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/Icing   ( 1693): doRemovePackageData com.test.thalitest
D/dalvikvm( 1020): GC_EXPLICIT freed 582K, 66% free 18489K/53208K, paused 22ms+27ms, total 270ms
I/InternalIcingCorporaPro( 2273): UpdateCorporaTask done [took 206 ms] updated apps [took 206 ms] 
D/Documents( 3942): Loading roots for com.android.providers.downloads.documents
I/ActivityManager( 1020): Killing 3574:com.google.android.partnersetup/u0a25 (adj 15): empty #9
W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/Documents( 3942): Loading roots for com.android.externalstorage.documents
I/ActivityManager( 1020): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3961 uid=10020 gids={50020, 1028, 1015, 1023}
I/ActivityManager( 1020): Killing 3594:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1257): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/ExternalStorage( 3961): After updating volumes, found 1 active roots
D/Documents( 3942): Updating roots due to change at content://com.android.externalstorage.documents/root
D/Documents( 3942): Loading roots for com.android.providers.media.documents
D/Documents( 3942): Loading roots for com.google.android.apps.docs.storage
D/Documents( 3942): Update found 7 roots in 112ms
D/Documents( 3942): Used cached roots for com.android.providers.downloads.documents
D/Documents( 3942): Loading roots for com.android.externalstorage.documents
D/Documents( 3942): Used cached roots for com.android.providers.media.documents
D/Documents( 3942): Used cached roots for com.google.android.apps.docs.storage
D/Documents( 3942): Update found 7 roots in 7ms
D/AndroidRuntime( 3882): Shutting down VM
D/dalvikvm( 3882): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+1ms, total 3ms

```
