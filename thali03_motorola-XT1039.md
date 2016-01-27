#### Test 57321924b5e4f25_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1019): sending alarm Alarm{447288d8 type 3 android}
,--------- beginning of /dev/log/main
D/AndroidRuntime( 3769): 
D/AndroidRuntime( 3769): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3769): CheckJNI is OFF
D/dalvikvm( 3769): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3769): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3769): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3769): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3769): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3769): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3769): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3769): failed to load memtrack module: -2
D/AndroidRuntime( 3769): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3769
W/WindowManager( 1019): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3785 uid=10140 gids={50140, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3769): Shutting down VM
D/dalvikvm( 3769): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+0ms, total 3ms
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3785): Binding Chromium to main looper Looper (main, tid 1) {42843940}
I/LibraryLoader( 3785): Expected native library version number "",actual native library version number ""
I/chromium( 3785): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3785): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4443c010:true
D/BluetoothAdapter( 3785): 1116046216: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3785): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3785): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3785): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3785): Local Branch: 
I/Adreno-EGL( 3785): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3785): Local Patches: NONE
I/Adreno-EGL( 3785): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 3785): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 3785): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 3785): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3785): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3785): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3785): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 3785): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 3785): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 3785): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3785): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3785): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3785): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3785): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3785): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3785): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 3785): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3785): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3785): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3785): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3785): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3785): Enabling debug mode 0
,W/AwContents( 3785): nativeOnDraw failed; clearing to background color.
,I/LaunchCheckinHandler( 1019): Displayed com.test.thalitest/.MainActivity,cp,ca,433
I/ActivityManager( 1019): Displayed com.test.thalitest/.MainActivity: +410ms (total +434ms)
W/AwContents( 3785): nativeOnDraw failed; clearing to background color.
,D/dalvikvm( 1019): GC_EXPLICIT freed 19000K, 58% free 18403K/43296K, paused 5ms+11ms, total 159ms
,W/IInputConnectionWrapper( 3785): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1201): onFinishInput()
,D/JsMessageQueue( 3785): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3785): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42848228
,D/dalvikvm( 3785): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42848228
,D/jxcore_app_log( 3785): JniHelper::setJavaVM(0x41f61f78), pthread_self() = 1613712056
,I/chromium( 3785): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/dalvikvm( 3785): GC_CONCURRENT freed 3387K, 20% free 13788K/17224K, paused 3ms+2ms, total 47ms
,D/dalvikvm( 3785): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/dalvikvm-heap( 3785): Grow heap (frag case) to 15.806MB for 323830-byte allocation
,D/dalvikvm( 3785): GC_FOR_ALLOC freed 560K, 21% free 13916K/17544K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3785): Grow heap (frag case) to 16.085MB for 485740-byte allocation
,D/dalvikvm( 3785): GC_FOR_ALLOC freed 943K, 23% free 14016K/18020K, paused 24ms, total 25ms
,I/dalvikvm-heap( 3785): Grow heap (frag case) to 16.415MB for 728606-byte allocation
,D/dalvikvm( 3785): GC_FOR_ALLOC freed 1282K, 24% free 14271K/18732K, paused 24ms, total 25ms
,I/dalvikvm-heap( 3785): Grow heap (frag case) to 17.011MB for 1092904-byte allocation
,D/dalvikvm( 3785): GC_CONCURRENT freed 1784K, 26% free 14661K/19800K, paused 1ms+4ms, total 45ms
,D/dalvikvm( 3785): GC_FOR_ALLOC freed 275K, 27% free 14586K/19800K, paused 24ms, total 24ms
,I/dalvikvm-heap( 3785): Grow heap (frag case) to 17.839MB for 1639352-byte allocation
,D/dalvikvm( 3785): GC_CONCURRENT freed 1558K, 30% free 15165K/21404K, paused 3ms+4ms, total 41ms
,D/dalvikvm( 3785): GC_FOR_ALLOC freed 1517K, 29% free 15276K/21404K, paused 29ms, total 30ms
,I/dalvikvm-heap( 3785): Grow heap (frag case) to 19.295MB for 2459024-byte allocation
,D/dalvikvm( 3785): GC_CONCURRENT freed 231K, 18% free 17582K/21404K, paused 4ms+5ms, total 45ms
,D/dalvikvm( 3785): GC_FOR_ALLOC freed 3763K, 25% free 16140K/21404K, paused 32ms, total 32ms
,I/dalvikvm-heap( 3785): Grow heap (frag case) to 19.958MB for 2269390-byte allocation
,W/jxcore-log( 3785): Initializing JXcore engine
,W/jxcore-log( 3785): JXcore engine is ready
,W/jxcore-log( 3785): Starting JXcore engine
,D/dalvikvm( 3785): GC_CONCURRENT freed 532K, 23% free 18234K/23624K, paused 2ms+4ms, total 33ms
,W/jxcore-log( 3785): Platform android
W/jxcore-log( 3785): 
,W/jxcore-log( 3785): Process ARCH arm
W/jxcore-log( 3785): 
,I/jxcore-log( 3785): JXcore Cordova bridge is ready!
I/jxcore-log( 3785): 
,W/jxcore-log( 3785): JXcore engine is started
,E/jxcore  ( 3785): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 3785): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 3785): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager( 1019): Killing 3553:com.android.defcontainer/u0a13 (adj 15): empty #9
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1584): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1584): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1584): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1584): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1584): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1584): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1584): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1584): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/Keyboard.Facilitator( 1201): onFinishInput()
,W/IInputConnectionWrapper( 3785): showStatusIcon on inactive InputConnection
,D/dalvikvm( 1584): GC_CONCURRENT freed 6326K, 38% free 10791K/17224K, paused 3ms+4ms, total 52ms
,V/GLSActivity( 2053): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2053): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{44727470 type 3 android}
,I/Keyboard.Facilitator.LanguageModelFlusher( 1201): run()
,I/Keyboard.Facilitator( 1201): flushDynamicLanguageModels()
,I/ConfigService( 1216): onCreate
,I/ConfigService( 1216): onDestroy
,V/AlarmManager( 1019): sending alarm Alarm{4472ac88 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  275): write error (Broken pipe)
,V/AlarmManager( 1019): sending alarm Alarm{43e27ab0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43e083b8 type 3 android}
,I/MMApiBackOffService( 1584): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1584): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1584): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1584): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1584): doRequest(): polling manager says we're not connected, returning with an error: 
,D/MMApiWebService( 1584): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,E/MMApiProvisionService( 1584): ProvisionWS.Response: Missing mandatory message data in response from DM server...
I/MMApiWebService( 1584): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,E/MMApiProvisionService( 1584): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1584): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1584): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1584): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1584): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1584): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1584): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1584): doRequest(): polling manager says we're not connected, returning with an error: 
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1584): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1584): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1584): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{43df2e38 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{436d5d50 type 3 android}
,V/GLSActivity( 2053): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2053): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  275): write error (Broken pipe)
,V/AlarmManager( 1019): sending alarm Alarm{43232150 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{431881e0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4316d018 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4473bff8 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1019): sending alarm Alarm{43e1ce40 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  275): write error (Broken pipe)
,V/AlarmManager( 1019): sending alarm Alarm{4316a0a0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42f312e8 type 3 android}
,V/GLSActivity( 2053): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2053): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{4298c550 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{44277618 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{430dd928 type 3 android}
,I/MMApiBackOffService( 1584): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1584): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1584): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1584): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1584): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,D/MMApiWebService( 1584): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1584): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,I/MMApiWebService( 1584): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,E/MMApiProvisionService( 1584): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1584): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1584): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1584): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1584): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1584): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1584): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/MMApiWebService( 1584): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1584): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1584): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1584): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{42b40f48 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4303d760 type 3 android}
,V/GLSActivity( 2053): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2053): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  275): write error (Broken pipe)
,V/AlarmManager( 1019): sending alarm Alarm{42aa1f70 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42a30b10 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4322cb28 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43054970 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42aa75f0 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3897): 
D/AndroidRuntime( 3897): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3897): CheckJNI is OFF
D/dalvikvm( 3897): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3897): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3897): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3897): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3897): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3897): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3897): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3897): failed to load memtrack module: -2
D/AndroidRuntime( 3897): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10140 user=-1: uninstall pkg
I/ActivityManager( 1019): Killing 3785:com.test.thalitest/u0a140 (adj 9): stop com.test.thalitest
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10140 user=0: pkg removed
D/dalvikvm( 2190): GC_EXPLICIT freed 4761K, 45% free 9604K/17224K, paused 2ms+5ms, total 34ms
D/dalvikvm( 2222): GC_EXPLICIT freed 2811K, 42% free 10046K/17224K, paused 2ms+6ms, total 94ms
D/dalvikvm( 1652): GC_EXPLICIT freed 1388K, 32% free 11841K/17224K, paused 4ms+11ms, total 100ms
I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1201): resetDictionaries() : en_GB
W/GeofencerStateMachine( 1216): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator.DecoderInitializer( 1201): run()
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
I/Decoder ( 1201): createOrResetDecoder
D/VoicemailCleanupService( 1177): Cleaning up data for package: com.test.thalitest
D/dalvikvm( 1301): GC_EXPLICIT freed 3152K, 33% free 11597K/17224K, paused 2ms+31ms, total 123ms
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/Launcher( 1301): Deferring update until onResume
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
I/ConfigService( 1216): onCreate
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
I/Launcher( 1301): Deferring update until onResume
I/InternalIcingCorporaPro( 2222): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
D/dalvikvm( 1019): GC_EXPLICIT freed 1152K, 58% free 18498K/43296K, paused 24ms+10ms, total 163ms
D/dalvikvm( 1019): WAIT_FOR_CONCURRENT_GC blocked 73ms
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
I/ActivityManager( 1019): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3928 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
W/ContextImpl( 3928): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/Keyboard.Facilitator.MainLanguageModelLoader( 1201): run()
D/ChimeraCfgMgr( 1652): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1652): Module APK com.google.android.play.games already loaded
I/dalvikvm( 3225): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3225): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 3225): VFY: replacing opcode 0x6e at 0x0013
D/ChimeraCfgMgr( 1652): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1652): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1652): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1652): Clearing selected account for com.test.thalitest
D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1019): removePackageParticipantsLocked: uid=10140 #1
I/LocationSettingsChecker( 1652): Removing dialog suppression flag for package com.test.thalitest
I/Keyboard.Facilitator.MainLanguageModelLoader( 1201): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_GB/main%00003aen_gb (offset=0, length=3633960) with up to date LoudsLmContentVersion = 20150512
E/NetworkScheduler.SchedulerReceiver( 2053): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 2053): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1201): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1201): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1201): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1201): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1201): run() : Loaded File = UserHistory.en_GB.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1201): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1201): run() : Missing File = Personal.en_GB.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1201): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1201): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1201): run()
I/StatsUtilsManager( 1201): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1201): shouldRecordStats() = Too Soon
I/ActivityManager( 1019): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3951 uid=10058 gids={50058}
D/dalvikvm( 1216): GC_EXPLICIT freed 1080K, 36% free 11104K/17224K, paused 3ms+6ms, total 44ms
E/DataBuffer( 1216): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@429a34e8)
E/DataBuffer( 1216): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42ba41e8)
E/DataBuffer( 1216): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42890de0)
E/DataBuffer( 1216): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42b5b950)
E/DataBuffer( 1216): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42a29028)
E/DataBuffer( 1216): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4295bf08)
E/DataBuffer( 1216): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42bb6ce0)
E/DataBuffer( 1216): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42ba2658)
E/DataBuffer( 1216): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@429d39f8)
E/DataBuffer( 1216): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42936900)
E/DataBuffer( 1216): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4295de40)
E/DataBuffer( 1216): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42c69558)
E/DataBuffer( 1216): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@429e3e78)
E/DataBuffer( 1216): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@429bb100)
E/DataBuffer( 1216): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42bee6d0)
D/gH_CompatibleDatabase( 1652): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
E/DataBuffer( 1216): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42873918)
D/gH_CompatibleDatabase( 1652): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1652): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1652): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1652): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1652): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1652): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/Icing   ( 1652): doRemovePackageData com.test.thalitest
D/Documents( 3951): Loading roots for com.android.providers.downloads.documents
I/InternalIcingCorporaPro( 2222): UpdateCorporaTask done [took 215 ms] updated apps [took 213 ms] 
D/gH_CompatibleDatabase( 1652): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1652): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1652): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1652): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1652): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1652): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager( 1019): Killing 3581:com.google.android.partnersetup/u0a25 (adj 15): empty #9
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/Documents( 3951): Loading roots for com.android.externalstorage.documents
I/ActivityManager( 1019): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3972 uid=10020 gids={50020, 1028, 1015, 1023}
D/dalvikvm( 1019): GC_EXPLICIT freed 490K, 58% free 18489K/43296K, paused 4ms+16ms, total 261ms
I/ActivityManager( 1019): Killing 3605:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/ExternalStorage( 3972): After updating volumes, found 1 active roots
D/Documents( 3951): Updating roots due to change at content://com.android.externalstorage.documents/root
D/Documents( 3951): Loading roots for com.android.providers.media.documents
D/Documents( 3951): Loading roots for com.google.android.apps.docs.storage
D/Documents( 3951): Update found 7 roots in 123ms
D/AndroidRuntime( 3897): Shutting down VM
D/Documents( 3951): Used cached roots for com.android.providers.downloads.documents
D/Documents( 3951): Loading roots for com.android.externalstorage.documents
D/dalvikvm( 3897): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+1ms, total 2ms
D/Documents( 3951): Used cached roots for com.android.providers.media.documents
D/Documents( 3951): Used cached roots for com.google.android.apps.docs.storage
D/Documents( 3951): Update found 7 roots in 8ms

```
