#### Test 57617811ecc172f_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1020): sending alarm Alarm{43eae328 type 3 android}
,--------- beginning of /dev/log/main
D/AndroidRuntime( 3771): 
D/AndroidRuntime( 3771): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3771): CheckJNI is OFF
D/dalvikvm( 3771): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3771): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3771): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3771): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3771): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3771): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3771): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3771): failed to load memtrack module: -2
D/AndroidRuntime( 3771): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1020): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3771
W/WindowManager( 1020): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1020): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3788 uid=10146 gids={50146, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3771): Shutting down VM
D/dalvikvm( 3771): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
W/ContextImpl( 1261): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1261): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3788): Binding Chromium to main looper Looper (main, tid 1) {41f6d410}
I/LibraryLoader( 3788): Expected native library version number "",actual native library version number ""
I/chromium( 3788): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3788): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1020): Message: 20
D/BluetoothAdapter( 3788): 1106785176: getState() :  mService = null. Returning STATE_OFF
D/BluetoothManagerService( 1020): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4325d3a0:true
I/Adreno-EGL( 3788): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3788): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3788): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3788): Local Branch: 
I/Adreno-EGL( 3788): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3788): Local Patches: NONE
I/Adreno-EGL( 3788): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 3788): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 3788): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 3788): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
,D/dalvikvm( 3788): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3788): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3788): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 3788): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 3788): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 3788): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3788): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3788): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3788): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3788): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3788): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3788): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 3788): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 3788): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3788): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3788): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3788): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3788): Enabling debug mode 0
,W/AwContents( 3788): nativeOnDraw failed; clearing to background color.
,I/Keyboard.Facilitator( 1202): onFinishInput()
,W/IInputConnectionWrapper( 3788): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1020): Displayed com.test.thalitest/.MainActivity,cp,ca,426
I/ActivityManager( 1020): Displayed com.test.thalitest/.MainActivity: +403ms (total +427ms)
,D/JsMessageQueue( 3788): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3788): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f73238
,D/dalvikvm( 3788): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f73238
,D/jxcore_app_log( 3788): JniHelper::setJavaVM(0x415c7f78), pthread_self() = 1614181656
,I/chromium( 3788): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/dalvikvm( 3788): GC_CONCURRENT freed 3361K, 20% free 13828K/17224K, paused 3ms+2ms, total 47ms
,D/dalvikvm( 3788): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 3788): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 3788): GC_FOR_ALLOC freed 73K, 20% free 13810K/17224K, paused 25ms, total 26ms
,I/dalvikvm-heap( 3788): Grow heap (frag case) to 15.828MB for 323830-byte allocation
,D/dalvikvm( 3788): GC_FOR_ALLOC freed 615K, 21% free 13885K/17544K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3788): Grow heap (frag case) to 16.055MB for 485740-byte allocation
,D/dalvikvm( 3788): GC_FOR_ALLOC freed 867K, 22% free 14061K/18020K, paused 24ms, total 24ms
,I/dalvikvm-heap( 3788): Grow heap (frag case) to 16.459MB for 728606-byte allocation
,D/dalvikvm( 3788): GC_FOR_ALLOC freed 1284K, 24% free 14316K/18732K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3788): Grow heap (frag case) to 17.056MB for 1092904-byte allocation
,D/dalvikvm( 3788): GC_CONCURRENT freed 1771K, 26% free 14745K/19800K, paused 2ms+5ms, total 48ms
,D/dalvikvm( 3788): GC_FOR_ALLOC freed 276K, 27% free 14642K/19800K, paused 24ms, total 24ms
,I/dalvikvm-heap( 3788): Grow heap (frag case) to 17.895MB for 1639352-byte allocation
,D/dalvikvm( 3788): GC_CONCURRENT freed 1494K, 30% free 15190K/21404K, paused 2ms+3ms, total 31ms
,D/dalvikvm( 3788): GC_FOR_ALLOC freed 1583K, 29% free 15330K/21404K, paused 29ms, total 30ms
,I/dalvikvm-heap( 3788): Grow heap (frag case) to 19.348MB for 2459024-byte allocation
,D/dalvikvm( 3788): GC_CONCURRENT freed 251K, 18% free 17609K/21404K, paused 4ms+5ms, total 46ms
,D/dalvikvm( 3788): GC_FOR_ALLOC freed 3819K, 25% free 16204K/21404K, paused 32ms, total 32ms
,I/dalvikvm-heap( 3788): Grow heap (frag case) to 20.039MB for 2287544-byte allocation
,W/jxcore-log( 3788): Initializing JXcore engine
,W/jxcore-log( 3788): JXcore engine is ready
,W/jxcore-log( 3788): Starting JXcore engine
,D/dalvikvm( 3788): GC_CONCURRENT freed 549K, 23% free 18297K/23640K, paused 3ms+3ms, total 35ms
,W/jxcore-log( 3788): Platform android
W/jxcore-log( 3788): 
,W/jxcore-log( 3788): Process ARCH arm
W/jxcore-log( 3788): 
,I/jxcore-log( 3788): JXcore Cordova bridge is ready!
I/jxcore-log( 3788): 
,W/jxcore-log( 3788): JXcore engine is started
,E/jxcore  ( 3788): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 3788): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 3788): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager( 1020): Killing 3559:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1261): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1261): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1261): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1591): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1591): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1591): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1591): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1591): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1591): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1591): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1591): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/Keyboard.Facilitator( 1202): onFinishInput()
,W/IInputConnectionWrapper( 3788): showStatusIcon on inactive InputConnection
,V/GLSActivity( 2089): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2089): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1020): sending alarm Alarm{43ead548 type 3 android}
,I/Keyboard.Facilitator.LanguageModelFlusher( 1202): run()
,I/Keyboard.Facilitator( 1202): flushDynamicLanguageModels()
,D/dalvikvm( 1020): GC_EXPLICIT freed 19259K, 58% free 18427K/43576K, paused 4ms+9ms, total 146ms
,I/ConfigService( 1220): onCreate
,D/dalvikvm( 1220): GC_EXPLICIT freed 1123K, 36% free 11103K/17224K, paused 3ms+5ms, total 38ms
,E/DataBuffer( 1220): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@423543c8)
,E/DataBuffer( 1220): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42100378)
,E/DataBuffer( 1220): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42360b98)
E/DataBuffer( 1220): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@420866e0)
,E/DataBuffer( 1220): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@422a58f8)
,E/DataBuffer( 1220): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4222d150)
,E/DataBuffer( 1220): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@422a9748)
,I/ConfigService( 1220): onDestroy
,V/AlarmManager( 1020): sending alarm Alarm{43eaf6a0 type 2 com.google.android.gms}
,D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1020): sending alarm Alarm{43e957f0 type 3 android}
,I/MMApiBackOffService( 1591): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1591): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1591): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1591): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1591): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,D/MMApiWebService( 1591): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1591): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1591): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1591): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1591): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1591): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1591): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1591): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1591): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/MMApiWebService( 1591): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1591): MMApiWebService told us not to continue at the moment with this request: devices.json
,I/MMApiWebService( 1591): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1591): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1591): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1020): sending alarm Alarm{437308f8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{4351f820 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{4351a550 type 3 android}
,V/GLSActivity( 2089): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2089): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1020): sending alarm Alarm{43517498 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{43514388 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{43511800 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{43ec3af0 type 2 android}
,D/ConnectivityService( 1020): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1020): sending alarm Alarm{440006b0 type 2 com.google.android.gms}
,D/ConnectivityService( 1020): Done.
,D/ConnectivityService( 1020): Setting timer for 720seconds
,D/ConnectivityService( 1020): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1020): sending alarm Alarm{4350f308 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{434f3900 type 3 android}
,V/GLSActivity( 2089): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2089): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1020): sending alarm Alarm{432464b8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42963c18 type 3 android}
,I/MMApiBackOffService( 1591): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1591): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1591): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1591): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1591): doRequest(): polling manager says we're not connected, returning with an error: 
,D/MMApiWebService( 1591): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1591): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1591): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiWebService( 1591): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1591): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1591): MMApiWebService told us not to continue at the moment with this request: devices.json
I/MMApiWebService( 1591): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1591): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1591): MMApiWebService told us not to continue at the moment with this request: 
D/MMApiWebService( 1591): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1591): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1591): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1591): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1591): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1591): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1020): sending alarm Alarm{428d7e08 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{428c9b90 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{4287ac58 type 3 android}
,V/GLSActivity( 2089): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2089): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1020): sending alarm Alarm{42860868 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{42816e40 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{4280f408 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{4280df28 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{4280d658 type 3 android}
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
I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10146 user=-1: uninstall pkg
I/ActivityManager( 1020): Killing 3788:com.test.thalitest/u0a146 (adj 9): stop com.test.thalitest
W/ContextImpl( 1261): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10146 user=0: pkg removed
D/dalvikvm( 2232): GC_EXPLICIT freed 4771K, 45% free 9604K/17224K, paused 2ms+6ms, total 37ms
I/Keyboard.Facilitator( 1202): resetDictionaries() : en_GB
W/GeofencerStateMachine( 1220): Ignoring removeGeofence because network location is disabled.
I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
I/Keyboard.Facilitator.DecoderInitializer( 1202): run()
I/Decoder ( 1202): createOrResetDecoder
D/VoicemailCleanupService( 1168): Cleaning up data for package: com.test.thalitest
D/dalvikvm( 2265): GC_EXPLICIT freed 2814K, 42% free 10046K/17224K, paused 3ms+3ms, total 113ms
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
D/dalvikvm( 1303): GC_EXPLICIT freed 3152K, 33% free 11597K/17224K, paused 2ms+5ms, total 119ms
I/Launcher( 1303): Deferring update until onResume
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
D/dalvikvm( 1713): GC_EXPLICIT freed 1426K, 33% free 11680K/17224K, paused 5ms+9ms, total 170ms
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
D/dalvikvm( 1020): GC_EXPLICIT freed 994K, 58% free 18415K/43576K, paused 11ms+11ms, total 144ms
D/dalvikvm( 1020): WAIT_FOR_CONCURRENT_GC blocked 43ms
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
I/ConfigService( 1220): onCreate
I/Launcher( 1303): Deferring update until onResume
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
I/InternalIcingCorporaPro( 2265): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager( 1020): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3928 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
W/ContextImpl( 3928): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
D/BackupManagerService( 1020): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1020): removePackageParticipantsLocked: uid=10146 #1
I/Keyboard.Facilitator.MainLanguageModelLoader( 1202): run()
D/PackageBroadcastService( 1713): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 1713): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1713): Module APK com.google.android.play.games already loaded
D/AccountUtils( 1713): Clearing selected account for com.test.thalitest
I/dalvikvm( 3260): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3260): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 3260): VFY: replacing opcode 0x6e at 0x0013
I/LocationSettingsChecker( 1713): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1713): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1713): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 2089): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 2089): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/Keyboard.Facilitator.MainLanguageModelLoader( 1202): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_GB/main%00003aen_gb (offset=0, length=3633960) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1202): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1202): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1202): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1202): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1202): run() : Loaded File = UserHistory.en_GB.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1202): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1202): run() : Missing File = Personal.en_GB.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1202): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1202): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1202): run()
I/StatsUtilsManager( 1202): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1202): shouldRecordStats() = Too Soon
D/gH_CompatibleDatabase( 1713): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1713): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1713): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1713): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/ActivityManager( 1020): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3955 uid=10058 gids={50058}
D/gH_CompatibleDatabase( 1713): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1713): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1713): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1713): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1713): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
I/InternalIcingCorporaPro( 2265): UpdateCorporaTask done [took 180 ms] updated apps [took 180 ms] 
I/Icing   ( 1713): doRemovePackageData com.test.thalitest
D/gH_CompatibleDatabase( 1713): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1713): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1713): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1713): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/dalvikvm( 1020): GC_EXPLICIT freed 530K, 58% free 18472K/43576K, paused 5ms+16ms, total 237ms
D/Documents( 3955): Loading roots for com.android.providers.downloads.documents
D/Documents( 3955): Loading roots for com.android.externalstorage.documents
I/ActivityManager( 1020): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3971 uid=10020 gids={50020, 1028, 1015, 1023}
I/ActivityManager( 1020): Killing 3586:com.google.android.partnersetup/u0a25 (adj 15): empty #9
W/ContextImpl( 1261): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1020): Killing 3607:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1261): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/ExternalStorage( 3971): After updating volumes, found 1 active roots
D/Documents( 3955): Updating roots due to change at content://com.android.externalstorage.documents/root
D/Documents( 3955): Loading roots for com.android.providers.media.documents
D/Documents( 3955): Loading roots for com.google.android.apps.docs.storage
D/AndroidRuntime( 3897): Shutting down VM
D/dalvikvm( 3897): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+1ms, total 2ms
D/Documents( 3955): Update found 7 roots in 99ms
D/Documents( 3955): Used cached roots for com.android.providers.downloads.documents
D/Documents( 3955): Loading roots for com.android.externalstorage.documents
D/Documents( 3955): Used cached roots for com.android.providers.media.documents
D/Documents( 3955): Used cached roots for com.google.android.apps.docs.storage
D/Documents( 3955): Update found 7 roots in 6ms

```
