#### Test 57348078846ce9d_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
,V/AlarmManager( 1016): sending alarm Alarm{43ffb100 type 3 android}
--------- beginning of /dev/log/main
D/AndroidRuntime( 3799): 
D/AndroidRuntime( 3799): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3799): CheckJNI is OFF
D/dalvikvm( 3799): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3799): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3799): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3799): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3799): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3799): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3799): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3799): failed to load memtrack module: -2
D/AndroidRuntime( 3799): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1016): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3799
W/WindowManager( 1016): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1016): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3816 uid=10142 gids={50142, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3799): Shutting down VM
D/dalvikvm( 3799): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+0ms, total 3ms
W/ContextImpl( 1246): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1246): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3816): Binding Chromium to main looper Looper (main, tid 1) {41fd7620}
I/LibraryLoader( 3816): Expected native library version number "",actual native library version number ""
I/chromium( 3816): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3816): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1016): Message: 20
D/BluetoothManagerService( 1016): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@439e5dd8:true
D/BluetoothAdapter( 3816): 1107215280: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3816): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3816): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3816): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3816): Local Branch: 
I/Adreno-EGL( 3816): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3816): Local Patches: NONE
I/Adreno-EGL( 3816): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 3816): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 3816): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3816): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3816): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3816): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3816): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 3816): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 3816): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3816): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3816): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3816): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3816): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3816): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3816): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3816): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 3816): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3816): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3816): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3816): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3816): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3816): Enabling debug mode 0
,W/AwContents( 3816): nativeOnDraw failed; clearing to background color.
,I/Keyboard.Facilitator( 1192): onFinishInput()
,I/LaunchCheckinHandler( 1016): Displayed com.test.thalitest/.MainActivity,cp,ca,432
I/ActivityManager( 1016): Displayed com.test.thalitest/.MainActivity: +408ms (total +433ms)
W/AwContents( 3816): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 3816): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 3816): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3816): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fdc250
,D/dalvikvm( 3816): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fdc250
,D/jxcore_app_log( 3816): JniHelper::setJavaVM(0x41628fa8), pthread_self() = 1615174232
,I/chromium( 3816): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/dalvikvm( 3816): GC_CONCURRENT freed 2658K, 16% free 14530K/17224K, paused 3ms+3ms, total 43ms
,D/dalvikvm( 3816): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 3816): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/dalvikvm( 3816): GC_FOR_ALLOC freed 354K, 14% free 14854K/17224K, paused 27ms, total 29ms
,D/dalvikvm( 3816): GC_FOR_ALLOC freed 69K, 14% free 14858K/17224K, paused 26ms, total 27ms
,I/dalvikvm-heap( 3816): Grow heap (frag case) to 16.583MB for 42652-byte allocation
,D/dalvikvm( 3816): GC_FOR_ALLOC freed 92K, 14% free 14877K/17268K, paused 27ms, total 27ms
,D/dalvikvm( 3816): GC_FOR_ALLOC freed 126K, 14% free 14896K/17268K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3816): Grow heap (frag case) to 16.671MB for 95956-byte allocation
,D/dalvikvm( 3816): GC_FOR_ALLOC freed 178K, 15% free 14932K/17364K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3816): Grow heap (frag case) to 16.751MB for 143930-byte allocation
,D/dalvikvm( 3816): GC_FOR_ALLOC freed 255K, 15% free 14978K/17508K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3816): Grow heap (frag case) to 16.866MB for 215890-byte allocation
,D/dalvikvm( 3816): GC_FOR_ALLOC freed 366K, 16% free 15053K/17720K, paused 26ms, total 27ms
,I/dalvikvm-heap( 3816): Grow heap (frag case) to 17.041MB for 323830-byte allocation
,D/dalvikvm( 3816): GC_FOR_ALLOC freed 568K, 16% free 15172K/18040K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3816): Grow heap (frag case) to 17.313MB for 485740-byte allocation
,D/dalvikvm( 3816): GC_FOR_ALLOC freed 865K, 18% free 15350K/18516K, paused 28ms, total 28ms
,D/dalvikvm( 3816): GC_FOR_ALLOC freed 1225K, 16% free 15599K/18516K, paused 28ms, total 29ms
,D/dalvikvm( 3816): GC_FOR_ALLOC freed 120K, 17% free 15544K/18516K, paused 29ms, total 29ms
,I/dalvikvm-heap( 3816): Grow heap (frag case) to 18.254MB for 1092904-byte allocation
,D/dalvikvm( 3816): GC_CONCURRENT freed 1786K, 19% free 16058K/19584K, paused 1ms+15ms, total 56ms
,D/dalvikvm( 3816): GC_FOR_ALLOC freed 220K, 19% free 15910K/19584K, paused 27ms, total 28ms
,I/dalvikvm-heap( 3816): Grow heap (frag case) to 19.133MB for 1639352-byte allocation
,D/dalvikvm( 3816): GC_CONCURRENT freed 1733K, 23% free 16503K/21188K, paused 2ms+5ms, total 36ms
,D/dalvikvm( 3816): GC_FOR_ALLOC freed 1150K, 23% free 16510K/21188K, paused 30ms, total 30ms
,I/dalvikvm-heap( 3816): Grow heap (frag case) to 20.501MB for 2459024-byte allocation
,D/dalvikvm( 3816): GC_CONCURRENT freed 282K, 20% free 18899K/23592K, paused 5ms+4ms, total 47ms
,D/dalvikvm( 3816): GC_FOR_ALLOC freed 4242K, 26% free 17543K/23592K, paused 37ms, total 38ms
,I/dalvikvm-heap( 3816): Grow heap (frag case) to 22.682MB for 3688532-byte allocation
,D/dalvikvm( 3816): GC_CONCURRENT freed 2705K, 32% free 18610K/27196K, paused 4ms+6ms, total 59ms
,D/dalvikvm( 3816): GC_FOR_ALLOC freed 2020K, 32% free 18654K/27196K, paused 34ms, total 35ms
,W/jxcore-log( 3816): Initializing JXcore engine
,W/jxcore-log( 3816): JXcore engine is ready
,D/dalvikvm( 3816): GC_CONCURRENT freed 424K, 22% free 21448K/27196K, paused 3ms+2ms, total 33ms
,D/dalvikvm( 3816): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 3816): WAIT_FOR_CONCURRENT_GC blocked 23ms
,W/jxcore-log( 3816): Starting JXcore engine
,W/jxcore-log( 3816): Platform android
W/jxcore-log( 3816): 
,W/jxcore-log( 3816): Process ARCH arm
W/jxcore-log( 3816): 
,I/jxcore-log( 3816): JXcore Cordova bridge is ready!
I/jxcore-log( 3816): 
,W/jxcore-log( 3816): JXcore engine is started
,E/jxcore  ( 3816): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 3816): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 3816): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager( 1016): Killing 3570:com.android.defcontainer/u0a13 (adj 15): empty #9
W/ContextImpl( 1246): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1246): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1246): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1581): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1581): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1581): publish the event [tag = MOT_OTA event name = LOG]
,D/dalvikvm( 1016): GC_EXPLICIT freed 24685K, 66% free 18505K/53304K, paused 4ms+10ms, total 146ms
,D/OtaApp  ( 1581): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 1581): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 1581): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 1581): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
D/OtaApp  ( 1581): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
I/Keyboard.Facilitator( 1192): onFinishInput()
W/IInputConnectionWrapper( 3816): showStatusIcon on inactive InputConnection
,V/AlarmManager( 1016): sending alarm Alarm{4401b6c0 type 2 com.google.android.gms}
,D/ConnectivityService( 1016): handleInetConditionChange: no active default network - ignore
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1016): sending alarm Alarm{43ff88b8 type 3 android}
,I/Keyboard.Facilitator.LanguageModelFlusher( 1192): run()
,I/Keyboard.Facilitator( 1192): flushDynamicLanguageModels()
,I/ConfigService( 1208): onCreate
,I/ConfigService( 1208): onDestroy
,V/AlarmManager( 1016): sending alarm Alarm{44045b98 type 3 android}
,I/MMApiBackOffService( 1581): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1581): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1581): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1581): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1581): doRequest(): polling manager says we're not connected, returning with an error: 
,D/MMApiWebService( 1581): doRequest(): polling manager says we're not connected, returning with an error: devices.json
I/MMApiWebService( 1581): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,E/MMApiProvisionService( 1581): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1581): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1581): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1581): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1581): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1581): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1581): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1581): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/MMApiWebService( 1581): doRequest(): polling manager says we're not connected, returning with an error: 
D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1581): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1581): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1581): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1016): sending alarm Alarm{43f5ceb0 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{43f55230 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{43f54708 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{44974ce0 type 2 com.google.android.gms}
,D/ConnectivityService( 1016): handleInetConditionChange: no active default network - ignore
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1016): sending alarm Alarm{43ad7ab8 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{429e41c0 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{429c9048 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{4401a810 type 2 android}
,D/ConnectivityService( 1016): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1016): sending alarm Alarm{4401a108 type 0 com.android.vending}
,D/Finsky  ( 3230): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ConnectivityService( 1016): Done.
,D/ConnectivityService( 1016): Setting timer for 720seconds
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3230): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3230): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3230): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 3230): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 1016): sending alarm Alarm{42657910 type 0 com.android.vending}
D/Finsky  ( 3230): [1] DailyHygiene.reschedule: Scheduling new run in 30 minutes (failures=2)
,D/WearableService( 1208): callingUid 10022, callindPid: 1208
,D/DeviceConnectionService( 1208): client connected with version: 8296000
,D/Finsky  ( 3230): [290] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3230): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
,D/Finsky  ( 3230): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 3230): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1016): sending alarm Alarm{428a3dc0 type 0 com.android.vending}
,D/Finsky  ( 3230): [276] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3230): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/AlarmManager( 1016): sending alarm Alarm{42924d28 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{4298e530 type 3 android}
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1016): sending alarm Alarm{443c1a08 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{42803560 type 3 android}
,I/MMApiBackOffService( 1581): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1581): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1581): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1581): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1581): doRequest(): polling manager says we're not connected, returning with an error: 
,D/MMApiWebService( 1581): doRequest(): polling manager says we're not connected, returning with an error: devices.json
I/MMApiWebService( 1581): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,E/MMApiProvisionService( 1581): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1581): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1581): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1581): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1581): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1581): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1581): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1581): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1581): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1581): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1581): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1581): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1581): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1016): sending alarm Alarm{429fdb08 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{428d6e20 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{425ce448 type 3 android}
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2084): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1016): sending alarm Alarm{430dd498 type 2 com.google.android.gms}
,D/ConnectivityService( 1016): handleInetConditionChange: no active default network - ignore
,D/dalvikvm( 2084): GC_CONCURRENT freed 1880K, 41% free 10332K/17224K, paused 11ms+6ms, total 100ms
,V/AlarmManager( 1016): sending alarm Alarm{43f5e260 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{44079750 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{4414ce80 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{42a0e380 type 3 android}
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  271): NetlinkHandler, power_supply subsys
I/MDMCTBK (  271): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  271): checkDefaultInst, current pid is = 271
I/MDMCTBK (  271): checkDefaultInst, pid match
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  271): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  271): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1016): sending alarm Alarm{42105ca0 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3945): 
D/AndroidRuntime( 3945): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3945): CheckJNI is OFF
D/dalvikvm( 3945): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3945): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3945): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3945): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3945): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3945): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3945): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3945): failed to load memtrack module: -2
D/AndroidRuntime( 3945): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1016): Force stopping com.test.thalitest appid=10142 user=-1: uninstall pkg
I/ActivityManager( 1016): Killing 3816:com.test.thalitest/u0a142 (adj 11): stop com.test.thalitest
W/ContextImpl( 1246): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1016): Force stopping com.test.thalitest appid=10142 user=0: pkg removed
D/dalvikvm( 2222): GC_EXPLICIT freed 4782K, 45% free 9603K/17224K, paused 4ms+5ms, total 52ms
D/dalvikvm( 1296): GC_EXPLICIT freed 3152K, 33% free 11593K/17224K, paused 16ms+4ms, total 118ms
D/dalvikvm( 2254): GC_EXPLICIT freed 3420K, 42% free 10058K/17224K, paused 2ms+4ms, total 110ms
D/dalvikvm( 1016): GC_EXPLICIT freed 1170K, 66% free 18441K/53304K, paused 5ms+12ms, total 131ms
I/Keyboard.Facilitator( 1192): resetDictionaries() : en_GB
I/Keyboard.Facilitator.DecoderInitializer( 1192): run()
I/Decoder ( 1192): createOrResetDecoder
I/Launcher( 1296): Deferring update until onResume
W/GeofencerStateMachine( 1208): Ignoring removeGeofence because network location is disabled.
I/InputReader( 1016): Reconfiguring input devices.  changes=0x00000010
D/VoicemailCleanupService( 1177): Cleaning up data for package: com.test.thalitest
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "sms"
D/dalvikvm( 1682): GC_EXPLICIT freed 1559K, 33% free 11695K/17224K, paused 63ms+6ms, total 187ms
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "smsto"
I/ConfigService( 1208): onCreate
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "mms"
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "mmsto"
D/BackupManagerService( 1016): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1016): removePackageParticipantsLocked: uid=10142 #1
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "sms"
I/InternalIcingCorporaPro( 2254): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "smsto"
I/ActivityManager( 1016): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3977 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "mms"
I/PackageManager( 1016): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1016):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1016):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1016):   Scheme: "mmsto"
I/Launcher( 1296): Deferring update until onResume
W/ContextImpl( 3977): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
D/dalvikvm( 1016): GC_EXPLICIT freed 679K, 66% free 18456K/53304K, paused 3ms+17ms, total 193ms
I/Keyboard.Facilitator.MainLanguageModelLoader( 1192): run()
I/dalvikvm( 3230): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3230): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 3230): VFY: replacing opcode 0x6e at 0x0013
D/PackageBroadcastService( 1682): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1682): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1682): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1682): Module APK com.google.android.play.games already loaded
I/Keyboard.Facilitator.MainLanguageModelLoader( 1192): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_GB/main%00003aen_gb (offset=0, length=3633960) with up to date LoudsLmContentVersion = 20150512
D/ChimeraCfgMgr( 1682): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1682): Module APK com.google.android.play.games already loaded
I/InternalIcingCorporaPro( 2254): UpdateCorporaTask done [took 109 ms] updated apps [took 109 ms] 
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1192): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1192): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1192): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1192): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1192): run() : Loaded File = UserHistory.en_GB.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1192): run() : Loading LM = user
I/LocationSettingsChecker( 1682): Removing dialog suppression flag for package com.test.thalitest
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1192): run() : Missing File = Personal.en_GB.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1192): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1192): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1192): run()
I/StatsUtilsManager( 1192): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1192): shouldRecordStats() = Too Soon
E/NetworkScheduler.SchedulerReceiver( 2084): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 2084): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
V/AlarmManager( 1016): sending alarm Alarm{429249d8 type 2 android}
I/ActivityManager( 1016): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4001 uid=10058 gids={50058}
D/gH_CompatibleDatabase( 1682): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1682): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1682): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1682): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/Icing   ( 1682): doRemovePackageData com.test.thalitest
D/gH_CompatibleDatabase( 1682): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1682): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1682): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1682): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1682): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1682): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1682): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1682): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1682): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/Documents( 4001): Loading roots for com.android.providers.downloads.documents
D/Documents( 4001): Loading roots for com.android.externalstorage.documents
I/ActivityManager( 1016): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4018 uid=10020 gids={50020, 1028, 1015, 1023}
I/ActivityManager( 1016): Killing 3600:com.google.android.partnersetup/u0a25 (adj 15): empty #9
W/ContextImpl( 1246): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/AndroidRuntime( 3945): Shutting down VM
D/ConnectivityService( 1016): Sampling interval elapsed, updating statistics ..
D/dalvikvm( 3945): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+1ms, total 3ms
I/ActivityManager( 1016): Killing 3624:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1246): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/ConnectivityService( 1016): Done.
D/ConnectivityService( 1016): Setting timer for 720seconds
D/ExternalStorage( 4018): After updating volumes, found 1 active roots
D/Documents( 4001): Updating roots due to change at content://com.android.externalstorage.documents/root
D/Documents( 4001): Loading roots for com.android.providers.media.documents
D/Documents( 4001): Loading roots for com.google.android.apps.docs.storage
D/Documents( 4001): Update found 7 roots in 135ms
D/Documents( 4001): Used cached roots for com.android.providers.downloads.documents
D/Documents( 4001): Loading roots for com.android.externalstorage.documents
D/Documents( 4001): Used cached roots for com.android.providers.media.documents
D/Documents( 4001): Used cached roots for com.google.android.apps.docs.storage
D/Documents( 4001): Update found 7 roots in 6ms

```
