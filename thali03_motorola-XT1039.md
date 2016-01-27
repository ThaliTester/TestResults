#### Test 564496604206eac_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1016): sending alarm Alarm{4409fe98 type 3 android}
,--------- beginning of /dev/log/main
D/AndroidRuntime( 3722): 
D/AndroidRuntime( 3722): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3722): CheckJNI is OFF
D/dalvikvm( 3722): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3722): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3722): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3722): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3722): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3722): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3722): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3722): failed to load memtrack module: -2
D/AndroidRuntime( 3722): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1016): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3722
W/WindowManager( 1016): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1016): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3738 uid=10141 gids={50141, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3722): Shutting down VM
D/dalvikvm( 3722): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 2ms
W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3738): Binding Chromium to main looper Looper (main, tid 1) {41fa0d88}
I/LibraryLoader( 3738): Expected native library version number "",actual native library version number ""
I/chromium( 3738): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3738): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1016): Message: 20
D/BluetoothManagerService( 1016): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43fa7518:true
D/BluetoothAdapter( 3738): 1106994296: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3738): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3738): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3738): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3738): Local Branch: 
I/Adreno-EGL( 3738): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3738): Local Patches: NONE
I/Adreno-EGL( 3738): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 3738): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 3738): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 3738): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3738): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3738): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3738): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 3738): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 3738): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 3738): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3738): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3738): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3738): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3738): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3738): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3738): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 3738): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3738): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
,W/dalvikvm( 3738): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3738): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3738): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3738): Enabling debug mode 0
,W/AwContents( 3738): nativeOnDraw failed; clearing to background color.
,I/Keyboard.Facilitator( 1199): onFinishInput()
,W/AwContents( 3738): nativeOnDraw failed; clearing to background color.
,I/LaunchCheckinHandler( 1016): Displayed com.test.thalitest/.MainActivity,cp,ca,439
I/ActivityManager( 1016): Displayed com.test.thalitest/.MainActivity: +410ms (total +439ms)
W/IInputConnectionWrapper( 3738): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 3738): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3738): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fa6318
,D/dalvikvm( 3738): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fa6318
,D/jxcore_app_log( 3738): JniHelper::setJavaVM(0x415f3fa8), pthread_self() = 1614927112
,I/chromium( 3738): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/dalvikvm( 3738): GC_CONCURRENT freed 2651K, 16% free 14537K/17224K, paused 3ms+3ms, total 43ms
,D/dalvikvm( 3738): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 3738): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/dalvikvm( 3738): GC_FOR_ALLOC freed 339K, 14% free 14829K/17224K, paused 26ms, total 26ms
,D/dalvikvm( 3738): GC_FOR_ALLOC freed 69K, 14% free 14833K/17224K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3738): Grow heap (frag case) to 16.558MB for 42652-byte allocation
,D/dalvikvm( 3738): GC_FOR_ALLOC freed 92K, 14% free 14852K/17268K, paused 27ms, total 27ms
,D/dalvikvm( 3738): GC_FOR_ALLOC freed 126K, 14% free 14871K/17268K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3738): Grow heap (frag case) to 16.647MB for 95956-byte allocation
,D/dalvikvm( 3738): GC_FOR_ALLOC freed 178K, 15% free 14907K/17364K, paused 27ms, total 28ms
,I/dalvikvm-heap( 3738): Grow heap (frag case) to 16.727MB for 143930-byte allocation
,D/dalvikvm( 3738): GC_FOR_ALLOC freed 255K, 15% free 14953K/17508K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3738): Grow heap (frag case) to 16.841MB for 215890-byte allocation
,D/dalvikvm( 3738): GC_FOR_ALLOC freed 367K, 16% free 15028K/17720K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3738): Grow heap (frag case) to 17.017MB for 323830-byte allocation
,D/dalvikvm( 3738): GC_FOR_ALLOC freed 569K, 17% free 15147K/18040K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3738): Grow heap (frag case) to 17.289MB for 485740-byte allocation
,D/dalvikvm( 3738): GC_FOR_ALLOC freed 864K, 18% free 15324K/18516K, paused 28ms, total 28ms
,D/dalvikvm( 3738): GC_FOR_ALLOC freed 1232K, 16% free 15574K/18516K, paused 28ms, total 29ms
,D/dalvikvm( 3738): GC_FOR_ALLOC freed 112K, 17% free 15517K/18516K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3738): Grow heap (frag case) to 18.229MB for 1092904-byte allocation
,D/dalvikvm( 3738): GC_CONCURRENT freed 1807K, 19% free 15976K/19584K, paused 1ms+4ms, total 47ms
,D/dalvikvm( 3738): GC_FOR_ALLOC freed 154K, 19% free 15929K/19584K, paused 28ms, total 29ms
,I/dalvikvm-heap( 3738): Grow heap (frag case) to 19.152MB for 1639352-byte allocation
,D/dalvikvm( 3738): GC_CONCURRENT freed 1852K, 23% free 16487K/21188K, paused 1ms+4ms, total 47ms
,D/dalvikvm( 3738): GC_FOR_ALLOC freed 1085K, 23% free 16476K/21188K, paused 28ms, total 29ms
,I/dalvikvm-heap( 3738): Grow heap (frag case) to 20.468MB for 2459024-byte allocation
,D/dalvikvm( 3738): GC_CONCURRENT freed 334K, 21% free 18872K/23592K, paused 4ms+4ms, total 51ms
,D/dalvikvm( 3738): GC_FOR_ALLOC freed 4194K, 26% free 17511K/23592K, paused 36ms, total 37ms
,I/dalvikvm-heap( 3738): Grow heap (frag case) to 22.651MB for 3688532-byte allocation
,D/dalvikvm( 3738): GC_CONCURRENT freed 248K, 24% free 20924K/27196K, paused 5ms+6ms, total 46ms
,D/dalvikvm( 3738): GC_FOR_ALLOC freed 4425K, 32% free 18628K/27196K, paused 34ms, total 34ms
,W/jxcore-log( 3738): Initializing JXcore engine
,W/jxcore-log( 3738): JXcore engine is ready
,D/dalvikvm( 3738): GC_CONCURRENT freed 433K, 22% free 21404K/27196K, paused 2ms+2ms, total 32ms
,D/dalvikvm( 3738): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 3738): WAIT_FOR_CONCURRENT_GC blocked 25ms
,W/jxcore-log( 3738): Starting JXcore engine
,W/jxcore-log( 3738): Platform android
W/jxcore-log( 3738): 
,W/jxcore-log( 3738): Process ARCH arm
W/jxcore-log( 3738): 
,I/jxcore-log( 3738): JXcore Cordova bridge is ready!
I/jxcore-log( 3738): 
,W/jxcore-log( 3738): JXcore engine is started
,E/jxcore  ( 3738): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 3738): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 3738): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager( 1016): Killing 3511:com.android.defcontainer/u0a13 (adj 15): empty #9
W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1581): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1581): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1581): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1581): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1581): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1581): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1581): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1581): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/Keyboard.Facilitator( 1199): onFinishInput()
,W/IInputConnectionWrapper( 3738): showStatusIcon on inactive InputConnection
D/dalvikvm( 1581): GC_CONCURRENT freed 6380K, 38% free 10780K/17224K, paused 2ms+4ms, total 61ms
,V/GLSActivity( 1997): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1997): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1016): sending alarm Alarm{4409e5f8 type 3 android}
,I/Keyboard.Facilitator.LanguageModelFlusher( 1199): run()
,I/Keyboard.Facilitator( 1199): flushDynamicLanguageModels()
,I/ConfigService( 1214): onCreate
,I/ConfigService( 1214): onDestroy
,V/AlarmManager( 1016): sending alarm Alarm{440743c0 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{440a1fd8 type 2 com.google.android.gms}
,D/ConnectivityService( 1016): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  271): write error (Broken pipe)
,I/MMApiBackOffService( 1581): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1581): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/dalvikvm( 1016): GC_EXPLICIT freed 24408K, 66% free 18396K/53148K, paused 9ms+9ms, total 162ms
,D/MMApiWebService( 1581): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1581): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
D/MMApiWebService( 1581): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/MMApiWebService( 1581): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1581): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,I/MMApiWebService( 1581): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1581): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1581): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1581): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1581): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1581): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1581): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1581): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/MMApiWebService( 1581): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1581): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1581): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1581): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1016): sending alarm Alarm{4406f0e0 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{44109908 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{440c12b8 type 3 android}
,V/GLSActivity( 1997): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1997): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1016): sending alarm Alarm{440176d8 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{43ef6828 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{43eeeba8 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{43eee080 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{44a5e7e0 type 2 com.google.android.gms}
,W/SocketClient(  271): write error (Broken pipe)
,D/ConnectivityService( 1016): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1016): sending alarm Alarm{43a22798 type 3 android}
,V/GLSActivity( 1997): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1997): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1016): sending alarm Alarm{4318ac40 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{429ac170 type 3 android}
,I/MMApiBackOffService( 1581): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1581): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1581): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1581): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1581): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/MMApiWebService( 1581): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1581): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,I/MMApiWebService( 1581): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,E/MMApiProvisionService( 1581): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1581): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1581): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1581): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1581): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1581): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1581): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1581): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1581): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1581): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1581): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1016): sending alarm Alarm{4299c498 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{42998a38 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{43516650 type 2 android}
,D/ConnectivityService( 1016): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1016): sending alarm Alarm{435152f8 type 0 com.google.android.gms}
,D/ConnectivityService( 1016): Done.
,D/ConnectivityService( 1016): Setting timer for 720seconds
,I/EventLogService( 2226): Aggregate from 1453884829281 (log), 1453884829281 (data)
,V/AlarmManager( 1016): sending alarm Alarm{42174c48 type 3 android}
,V/GLSActivity( 1997): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1997): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1016): sending alarm Alarm{4242e668 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{421c5d18 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{4208a8a0 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{428e4f78 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{4279c0b0 type 3 android}
,V/GLSActivity( 1997): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1997): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3852): 
D/AndroidRuntime( 3852): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3852): CheckJNI is OFF
D/dalvikvm( 3852): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3852): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3852): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3852): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3852): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3852): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3852): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3852): failed to load memtrack module: -2
D/AndroidRuntime( 3852): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1016): Force stopping com.test.thalitest appid=10141 user=-1: uninstall pkg
I/ActivityManager( 1016): Killing 3738:com.test.thalitest/u0a141 (adj 9): stop com.test.thalitest
W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1016): Force stopping com.test.thalitest appid=10141 user=0: pkg removed
D/dalvikvm( 2143): GC_EXPLICIT freed 4771K, 45% free 9603K/17224K, paused 2ms+6ms, total 37ms
D/dalvikvm( 2174): GC_EXPLICIT freed 2833K, 42% free 10047K/17224K, paused 2ms+6ms, total 85ms
D/dalvikvm( 1297): GC_EXPLICIT freed 3152K, 33% free 11594K/17224K, paused 2ms+4ms, total 70ms
I/InputReader( 1016): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1199): resetDictionaries() : en_GB
I/Keyboard.Facilitator.DecoderInitializer( 1199): run()
I/Launcher( 1297): Deferring update until onResume
W/GeofencerStateMachine( 1214): Ignoring removeGeofence because network location is disabled.
I/Decoder ( 1199): createOrResetDecoder
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "sms"
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "smsto"
D/VoicemailCleanupService( 1180): Cleaning up data for package: com.test.thalitest
D/dalvikvm( 2226): GC_EXPLICIT freed 541K, 32% free 11750K/17224K, paused 4ms+10ms, total 146ms
I/Launcher( 1297): Deferring update until onResume
I/ConfigService( 1214): onCreate
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "mms"
D/dalvikvm( 1016): GC_EXPLICIT freed 998K, 66% free 18387K/53148K, paused 5ms+12ms, total 123ms
D/dalvikvm( 1016): WAIT_FOR_CONCURRENT_GC blocked 61ms
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "mmsto"
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "sms"
I/InternalIcingCorporaPro( 2174): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "smsto"
I/ActivityManager( 1016): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3883 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "mms"
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "mmsto"
W/ContextImpl( 3883): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
D/BackupManagerService( 1016): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1016): removePackageParticipantsLocked: uid=10141 #1
I/Keyboard.Facilitator.MainLanguageModelLoader( 1199): run()
D/PackageBroadcastService( 2226): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 2226): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2226): Module APK com.google.android.play.games already loaded
I/dalvikvm( 3148): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3148): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 3148): VFY: replacing opcode 0x6e at 0x0013
D/AccountUtils( 2226): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2226): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2226): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1997): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1997): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/Keyboard.Facilitator.MainLanguageModelLoader( 1199): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_GB/main%00003aen_gb (offset=0, length=3633960) with up to date LoudsLmContentVersion = 20150512
I/LocationSettingsChecker( 2226): Removing dialog suppression flag for package com.test.thalitest
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1199): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1199): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1199): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1199): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1199): run() : Loaded File = UserHistory.en_GB.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1199): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1199): run() : Missing File = Personal.en_GB.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1199): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1199): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1199): run()
I/StatsUtilsManager( 1199): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1199): shouldRecordStats() = Too Soon
I/ActivityManager( 1016): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3904 uid=10058 gids={50058}
I/InternalIcingCorporaPro( 2174): UpdateCorporaTask done [took 139 ms] updated apps [took 139 ms] 
I/Icing   ( 2226): doRemovePackageData com.test.thalitest
D/gH_CompatibleDatabase( 2226): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 2226): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 2226): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 2226): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 2226): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 2226): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 2226): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 2226): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 2226): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 2226): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 2226): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 2226): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 2226): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/Documents( 3904): Loading roots for com.android.providers.downloads.documents
D/dalvikvm( 1016): GC_EXPLICIT freed 636K, 66% free 18425K/53148K, paused 6ms+14ms, total 259ms
D/Documents( 3904): Loading roots for com.android.externalstorage.documents
I/ActivityManager( 1016): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3925 uid=10020 gids={50020, 1028, 1015, 1023}
I/ActivityManager( 1016): Killing 3538:com.google.android.partnersetup/u0a25 (adj 15): empty #9
W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1016): Killing 3562:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1256): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/ExternalStorage( 3925): After updating volumes, found 1 active roots
D/Documents( 3904): Updating roots due to change at content://com.android.externalstorage.documents/root
D/Documents( 3904): Loading roots for com.android.providers.media.documents
D/Documents( 3904): Loading roots for com.google.android.apps.docs.storage
D/AndroidRuntime( 3852): Shutting down VM
D/dalvikvm( 3852): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
D/Documents( 3904): Update found 7 roots in 117ms
D/Documents( 3904): Used cached roots for com.android.providers.downloads.documents
D/Documents( 3904): Loading roots for com.android.externalstorage.documents
D/Documents( 3904): Used cached roots for com.android.providers.media.documents
D/Documents( 3904): Used cached roots for com.google.android.apps.docs.storage
D/Documents( 3904): Update found 7 roots in 6ms

```
