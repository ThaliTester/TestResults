#### Test 564496605d11e75_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1021): sending alarm Alarm{440e46d8 type 3 android}
,--------- beginning of /dev/log/main
D/AndroidRuntime( 3739): 
D/AndroidRuntime( 3739): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3739): CheckJNI is OFF
D/dalvikvm( 3739): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3739): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3739): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3739): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3739): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3739): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3739): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3739): failed to load memtrack module: -2
D/AndroidRuntime( 3739): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1021): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3739
W/WindowManager( 1021): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1021): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3755 uid=10137 gids={50137, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3739): Shutting down VM
D/dalvikvm( 3739): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+0ms, total 3ms
W/ContextImpl( 1237): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1237): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3755): Binding Chromium to main looper Looper (main, tid 1) {41fab9c0}
I/LibraryLoader( 3755): Expected native library version number "",actual native library version number ""
I/chromium( 3755): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3755): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1021): Message: 20
D/BluetoothManagerService( 1021): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43ccf0d0:true
D/BluetoothAdapter( 3755): 1107031096: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3755): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3755): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3755): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3755): Local Branch: 
I/Adreno-EGL( 3755): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3755): Local Patches: NONE
I/Adreno-EGL( 3755): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 3755): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 3755): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3755): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3755): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3755): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3755): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 3755): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 3755): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3755): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3755): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3755): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3755): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3755): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3755): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3755): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 3755): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3755): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3755): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3755): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3755): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3755): Enabling debug mode 0
,W/AwContents( 3755): nativeOnDraw failed; clearing to background color.
,I/Keyboard.Facilitator( 1199): onFinishInput()
,W/IInputConnectionWrapper( 3755): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1021): Displayed com.test.thalitest/.MainActivity,cp,ca,451
I/ActivityManager( 1021): Displayed com.test.thalitest/.MainActivity: +423ms (total +451ms)
,D/JsMessageQueue( 3755): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3755): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41faf2d8
,D/dalvikvm( 3755): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41faf2d8
,D/jxcore_app_log( 3755): JniHelper::setJavaVM(0x415fcfa8), pthread_self() = 1614960280
,I/chromium( 3755): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/dalvikvm( 3755): GC_CONCURRENT freed 2650K, 16% free 14539K/17224K, paused 3ms+3ms, total 43ms
,D/dalvikvm( 3755): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 3755): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/dalvikvm( 3755): GC_FOR_ALLOC freed 340K, 14% free 14829K/17224K, paused 30ms, total 31ms
,D/dalvikvm( 3755): GC_FOR_ALLOC freed 69K, 14% free 14833K/17224K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3755): Grow heap (frag case) to 16.558MB for 42652-byte allocation
,D/dalvikvm( 3755): GC_FOR_ALLOC freed 92K, 14% free 14852K/17268K, paused 28ms, total 28ms
,D/dalvikvm( 3755): GC_FOR_ALLOC freed 127K, 14% free 14871K/17268K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3755): Grow heap (frag case) to 16.647MB for 95956-byte allocation
,D/dalvikvm( 3755): GC_FOR_ALLOC freed 180K, 15% free 14907K/17364K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3755): Grow heap (frag case) to 16.727MB for 143930-byte allocation
,D/dalvikvm( 3755): GC_FOR_ALLOC freed 255K, 15% free 14953K/17508K, paused 26ms, total 27ms
,I/dalvikvm-heap( 3755): Grow heap (frag case) to 16.841MB for 215890-byte allocation
,D/dalvikvm( 3755): GC_FOR_ALLOC freed 366K, 16% free 15028K/17720K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3755): Grow heap (frag case) to 17.017MB for 323830-byte allocation
,D/dalvikvm( 3755): GC_FOR_ALLOC freed 570K, 17% free 15147K/18040K, paused 29ms, total 29ms
,I/dalvikvm-heap( 3755): Grow heap (frag case) to 17.288MB for 485740-byte allocation
,D/dalvikvm( 3755): GC_FOR_ALLOC freed 863K, 18% free 15324K/18516K, paused 27ms, total 27ms
,D/dalvikvm( 3755): GC_FOR_ALLOC freed 1230K, 16% free 15574K/18516K, paused 27ms, total 28ms
,D/dalvikvm( 3755): GC_FOR_ALLOC freed 115K, 17% free 15518K/18516K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3755): Grow heap (frag case) to 18.229MB for 1092904-byte allocation
,D/dalvikvm( 3755): GC_CONCURRENT freed 1736K, 19% free 15966K/19584K, paused 2ms+4ms, total 37ms
,D/dalvikvm( 3755): GC_FOR_ALLOC freed 264K, 19% free 15892K/19584K, paused 28ms, total 28ms
,I/dalvikvm-heap( 3755): Grow heap (frag case) to 19.116MB for 1639352-byte allocation
,D/dalvikvm( 3755): GC_CONCURRENT freed 1749K, 23% free 16479K/21188K, paused 3ms+3ms, total 39ms
,D/dalvikvm( 3755): GC_FOR_ALLOC freed 1143K, 23% free 16484K/21188K, paused 28ms, total 29ms
,I/dalvikvm-heap( 3755): Grow heap (frag case) to 20.475MB for 2459024-byte allocation
,D/dalvikvm( 3755): GC_CONCURRENT freed 273K, 21% free 18824K/23592K, paused 4ms+5ms, total 35ms
,D/dalvikvm( 3755): GC_FOR_ALLOC freed 4253K, 26% free 17518K/23592K, paused 36ms, total 37ms
,I/dalvikvm-heap( 3755): Grow heap (frag case) to 22.658MB for 3688532-byte allocation
,D/dalvikvm( 3755): GC_CONCURRENT freed 204K, 23% free 20993K/27196K, paused 4ms+5ms, total 48ms
,D/dalvikvm( 3755): GC_FOR_ALLOC freed 4480K, 32% free 18625K/27196K, paused 33ms, total 33ms
,W/jxcore-log( 3755): Initializing JXcore engine
,W/jxcore-log( 3755): JXcore engine is ready
,D/dalvikvm( 3755): GC_CONCURRENT freed 430K, 22% free 21404K/27196K, paused 3ms+2ms, total 31ms
,D/dalvikvm( 3755): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 3755): WAIT_FOR_CONCURRENT_GC blocked 25ms
,W/jxcore-log( 3755): Starting JXcore engine
,W/jxcore-log( 3755): Platform android
W/jxcore-log( 3755): 
,W/jxcore-log( 3755): Process ARCH arm
W/jxcore-log( 3755): 
,I/jxcore-log( 3755): JXcore Cordova bridge is ready!
I/jxcore-log( 3755): 
,W/jxcore-log( 3755): JXcore engine is started
,E/jxcore  ( 3755): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 3755): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 3755): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager( 1021): Killing 3536:com.android.defcontainer/u0a13 (adj 15): empty #9
W/ContextImpl( 1237): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1237): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1237): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1566): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1566): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1566): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1566): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1566): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1566): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1566): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1566): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/Keyboard.Facilitator( 1199): onFinishInput()
,W/IInputConnectionWrapper( 3755): showStatusIcon on inactive InputConnection
,V/GLSActivity( 1323): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1323): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1021): GC_EXPLICIT freed 24332K, 66% free 18418K/53136K, paused 4ms+9ms, total 153ms
,V/AlarmManager( 1021): sending alarm Alarm{440e2ad0 type 3 android}
,I/Keyboard.Facilitator.LanguageModelFlusher( 1199): run()
,I/Keyboard.Facilitator( 1199): flushDynamicLanguageModels()
,I/ConfigService( 1219): onCreate
,I/ConfigService( 1219): onDestroy
,V/AlarmManager( 1021): sending alarm Alarm{44741090 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{440e6e98 type 2 com.google.android.gms}
,W/SocketClient(  272): write error (Broken pipe)
,D/ConnectivityService( 1021): handleInetConditionChange: no active default network - ignore
,I/MMApiBackOffService( 1566): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1566): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1566): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1566): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1566): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1566): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,E/MMApiProvisionService( 1566): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1566): ProvisionWS.Response.setError: error RadioDownError
D/MMApiWebService( 1566): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1566): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1566): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1566): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1566): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1566): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1566): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1566): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1566): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1566): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1566): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1566): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1566): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1566): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1566): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1566): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1566): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1566): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1566): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1566): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1566): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1021): sending alarm Alarm{440cb560 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{44018d88 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{43efa448 type 3 android}
,V/GLSActivity( 1323): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1323): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1021): sending alarm Alarm{43ef27c8 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{434244c0 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{433b72a8 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{432792b0 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{43286400 type 2 android}
,D/ConnectivityService( 1021): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1021): sending alarm Alarm{44093350 type 2 com.google.android.gms}
,V/AlarmManager( 1021): sending alarm Alarm{43284f18 type 0 com.android.vending}
,D/Finsky  ( 3208): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ConnectivityService( 1021): Done.
,D/ConnectivityService( 1021): Setting timer for 720seconds
,V/GLSActivity( 1323): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1323): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService( 1021): handleInetConditionChange: no active default network - ignore
,W/Finsky  ( 3208): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1323): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1323): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1323): GC_EXPLICIT freed 1571K, 41% free 10324K/17224K, paused 2ms+4ms, total 30ms
,V/GLSActivity( 1323): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1323): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3208): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1323): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1323): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3208): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 3208): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 1021): sending alarm Alarm{429ebbd8 type 0 com.android.vending}
D/Finsky  ( 3208): [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2)
,D/WearableService( 1219): callingUid 10022, callindPid: 1219
,D/DeviceConnectionService( 1219): client connected with version: 8296000
,D/Finsky  ( 3208): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
,D/Finsky  ( 3208): [285] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3208): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 3208): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1323): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1323): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1021): sending alarm Alarm{424a2750 type 0 com.android.vending}
,D/Finsky  ( 3208): [270] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3208): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/AlarmManager( 1021): sending alarm Alarm{42990078 type 3 android}
,V/GLSActivity( 1323): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1323): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1021): sending alarm Alarm{4292fa80 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{429872c0 type 3 android}
,I/MMApiBackOffService( 1566): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1566): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1566): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1566): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1566): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1566): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/MMApiWebService( 1566): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1566): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 1566): publish the event [tag = MOT_CCE event name = LOG]
,E/MMApiProvisionService( 1566): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1566): ProvisionWS.Response.setError: error RadioDownError
I/MMApiBackOffService( 1566): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1566): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1566): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1566): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1566): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1566): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1566): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1566): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1566): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1566): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/Checkin ( 1566): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1566): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1566): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1566): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1566): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1566): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1566): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1566): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1021): sending alarm Alarm{441480d0 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{4292c638 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{4282b2a8 type 3 android}
,V/GLSActivity( 1323): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1323): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1021): sending alarm Alarm{4286e7d8 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{427e3b78 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{42140b10 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{43c6c198 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{4288b4a8 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3871): 
D/AndroidRuntime( 3871): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3871): CheckJNI is OFF
D/dalvikvm( 3871): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3871): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3871): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3871): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3871): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3871): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3871): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3871): failed to load memtrack module: -2
D/AndroidRuntime( 3871): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1021): Force stopping com.test.thalitest appid=10137 user=-1: uninstall pkg
I/ActivityManager( 1021): Killing 3755:com.test.thalitest/u0a137 (adj 11): stop com.test.thalitest
W/ContextImpl( 1237): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1021): Force stopping com.test.thalitest appid=10137 user=0: pkg removed
D/dalvikvm( 2185): GC_EXPLICIT freed 4772K, 45% free 9604K/17224K, paused 2ms+7ms, total 42ms
I/Keyboard.Facilitator( 1199): resetDictionaries() : en_GB
I/InputReader( 1021): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator.DecoderInitializer( 1199): run()
W/GeofencerStateMachine( 1219): Ignoring removeGeofence because network location is disabled.
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "sms"
D/VoicemailCleanupService( 1169): Cleaning up data for package: com.test.thalitest
I/Decoder ( 1199): createOrResetDecoder
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "smsto"
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mms"
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mmsto"
D/dalvikvm( 1294): GC_EXPLICIT freed 3148K, 33% free 11597K/17224K, paused 2ms+9ms, total 114ms
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "sms"
D/dalvikvm( 1663): GC_EXPLICIT freed 1033K, 33% free 11699K/17224K, paused 4ms+6ms, total 158ms
D/dalvikvm( 2217): GC_EXPLICIT freed 3379K, 42% free 10060K/17224K, paused 3ms+4ms, total 171ms
I/Launcher( 1294): Deferring update until onResume
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "smsto"
I/ConfigService( 1219): onCreate
D/dalvikvm( 1021): GC_EXPLICIT freed 1270K, 66% free 18494K/53136K, paused 5ms+13ms, total 145ms
D/dalvikvm( 1021): WAIT_FOR_CONCURRENT_GC blocked 38ms
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mms"
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mmsto"
I/InternalIcingCorporaPro( 2217): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/Launcher( 1294): Deferring update until onResume
I/ActivityManager( 1021): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3904 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
I/Keyboard.Facilitator.MainLanguageModelLoader( 1199): run()
W/ContextImpl( 3904): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
D/PackageBroadcastService( 1663): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1663): Clearing selected account for com.test.thalitest
I/dalvikvm( 3208): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3208): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 3208): VFY: replacing opcode 0x6e at 0x0013
I/Keyboard.Facilitator.MainLanguageModelLoader( 1199): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_GB/main%00003aen_gb (offset=0, length=3633960) with up to date LoudsLmContentVersion = 20150512
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
I/LocationSettingsChecker( 1663): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1663): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1663): Module APK com.google.android.play.games already loaded
D/BackupManagerService( 1021): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1021): removePackageParticipantsLocked: uid=10137 #1
E/NetworkScheduler.SchedulerReceiver( 1323): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1323): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/ChimeraCfgMgr( 1663): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1663): Module APK com.google.android.play.games already loaded
D/gH_CompatibleDatabase( 1663): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1663): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1663): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1663): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/ActivityManager( 1021): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3927 uid=10058 gids={50058}
D/gH_CompatibleDatabase( 1663): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1663): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1663): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
V/GLSActivity( 1323): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1323): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/gH_CompatibleDatabase( 1663): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1663): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1663): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1663): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1663): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1663): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/dalvikvm( 1219): GC_EXPLICIT freed 1009K, 36% free 11109K/17224K, paused 3ms+7ms, total 53ms
E/DataBuffer( 1219): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42158970)
E/DataBuffer( 1219): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@420a15e0)
E/DataBuffer( 1219): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@422307b8)
E/DataBuffer( 1219): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@423cf288)
E/DataBuffer( 1219): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@422cc458)
E/DataBuffer( 1219): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4209fd38)
E/DataBuffer( 1219): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@420e96e8)
E/DataBuffer( 1219): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42256260)
E/DataBuffer( 1219): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@421853b0)
E/DataBuffer( 1219): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42361b58)
E/DataBuffer( 1219): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42368a98)
E/DataBuffer( 1219): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42199838)
E/DataBuffer( 1219): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@41ff9608)
E/DataBuffer( 1219): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42205558)
E/DataBuffer( 1219): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4213afd8)
E/DataBuffer( 1219): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@424095b0)
I/Icing   ( 1663): doRemovePackageData com.test.thalitest
I/InternalIcingCorporaPro( 2217): UpdateCorporaTask done [took 228 ms] updated apps [took 228 ms] 
D/Documents( 3927): Loading roots for com.android.providers.downloads.documents
D/dalvikvm( 1021): GC_EXPLICIT freed 463K, 66% free 18538K/53136K, paused 7ms+17ms, total 273ms
D/Documents( 3927): Loading roots for com.android.externalstorage.documents
I/ActivityManager( 1021): Killing 3563:com.google.android.partnersetup/u0a25 (adj 15): empty #9
W/ContextImpl( 1237): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1021): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3950 uid=10020 gids={50020, 1028, 1015, 1023}
I/ActivityManager( 1021): Killing 3587:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1237): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/ExternalStorage( 3950): After updating volumes, found 1 active roots
D/Documents( 3927): Updating roots due to change at content://com.android.externalstorage.documents/root
D/Documents( 3927): Loading roots for com.android.providers.media.documents
D/Documents( 3927): Loading roots for com.google.android.apps.docs.storage
D/Documents( 3927): Update found 7 roots in 113ms
D/Documents( 3927): Used cached roots for com.android.providers.downloads.documents
D/Documents( 3927): Loading roots for com.android.externalstorage.documents
D/Documents( 3927): Used cached roots for com.android.providers.media.documents
D/Documents( 3927): Used cached roots for com.google.android.apps.docs.storage
D/Documents( 3927): Update found 7 roots in 7ms
D/AndroidRuntime( 3871): Shutting down VM
D/dalvikvm( 3871): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms

```
