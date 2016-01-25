#### Test 57132760f6ec045_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/VacuumService( 1208): Vacuum at: now=1453758245499 tag=VacuumService
,D/AndroidRuntime( 3782): 
D/AndroidRuntime( 3782): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3782): CheckJNI is OFF
D/dalvikvm( 3782): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3782): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3782): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3782): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3782): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3782): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3782): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3782): failed to load memtrack module: -2
D/AndroidRuntime( 3782): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager(  987): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3782
W/WindowManager(  987): Not okToDisplay, so not showing Starting Window
I/ActivityManager(  987): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3794 uid=10136 gids={50136, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3782): Shutting down VM
D/dalvikvm( 3782): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+1ms, total 3ms
W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3794): Binding Chromium to main looper Looper (main, tid 1) {41f59940}
I/LibraryLoader( 3794): Expected native library version number "",actual native library version number ""
I/chromium( 3794): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3794): Initializing chromium process, renderers=0
D/BluetoothManagerService(  987): Message: 20
D/BluetoothManagerService(  987): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43ee84d0:true
D/BluetoothAdapter( 3794): 1106699144: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3794): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3794): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3794): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3794): Local Branch: 
I/Adreno-EGL( 3794): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3794): Local Patches: NONE
I/Adreno-EGL( 3794): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3794): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 3794): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3794): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3794): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3794): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3794): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3794): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3794): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3794): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3794): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3794): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 3794): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3794): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3794): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3794): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3794): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3794): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3794): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 3794): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 3794): CordovaWebView is running on device made by: motorola
D/OpenGLRenderer( 3794): Enabling debug mode 0
W/AwContents( 3794): nativeOnDraw failed; clearing to background color.
I/Keyboard.Facilitator( 1194): onFinishInput()
W/IInputConnectionWrapper( 3794): showStatusIcon on inactive InputConnection
I/LaunchCheckinHandler(  987): Displayed com.test.thalitest/.MainActivity,cp,ca,393
I/ActivityManager(  987): Displayed com.test.thalitest/.MainActivity: +371ms (total +393ms)
D/JsMessageQueue( 3794): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 3794): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f5e228
D/dalvikvm( 3794): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f5e228
D/jxcore_app_log( 3794): JniHelper::setJavaVM(0x415aafa8), pthread_self() = 1614641456
I/chromium( 3794): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/dalvikvm( 3794): GC_CONCURRENT freed 2653K, 16% free 14536K/17224K, paused 2ms+3ms, total 42ms
D/dalvikvm( 3794): WAIT_FOR_CONCURRENT_GC blocked 30ms
D/dalvikvm( 3794): WAIT_FOR_CONCURRENT_GC blocked 25ms
W/PluginManager( 3794): THREAD WARNING: exec() call to JXcore.isReady blocked the main thread for 26ms. Plugin should use CordovaInterface.getThreadPool().
D/dalvikvm( 3794): GC_FOR_ALLOC freed 401K, 14% free 14850K/17224K, paused 27ms, total 30ms
D/dalvikvm( 3794): GC_FOR_ALLOC freed 104K, 14% free 14857K/17224K, paused 26ms, total 26ms
I/dalvikvm-heap( 3794): Grow heap (frag case) to 16.602MB for 63974-byte allocation
D/dalvikvm( 3794): GC_FOR_ALLOC freed 126K, 14% free 14877K/17288K, paused 27ms, total 27ms
I/dalvikvm-heap( 3794): Grow heap (frag case) to 16.653MB for 95956-byte allocation
D/dalvikvm( 3794): GC_FOR_ALLOC freed 179K, 15% free 14912K/17384K, paused 26ms, total 26ms
I/dalvikvm-heap( 3794): Grow heap (frag case) to 16.732MB for 143930-byte allocation
D/dalvikvm( 3794): GC_FOR_ALLOC freed 254K, 15% free 14959K/17528K, paused 26ms, total 27ms
I/dalvikvm-heap( 3794): Grow heap (frag case) to 16.847MB for 215890-byte allocation
D/dalvikvm( 3794): GC_FOR_ALLOC freed 367K, 16% free 15033K/17740K, paused 26ms, total 27ms
I/dalvikvm-heap( 3794): Grow heap (frag case) to 17.022MB for 323830-byte allocation
D/dalvikvm( 3794): GC_FOR_ALLOC freed 569K, 17% free 15153K/18060K, paused 27ms, total 28ms
D/dalvikvm( 3794): GC_FOR_ALLOC freed 865K, 16% free 15330K/18060K, paused 30ms, total 30ms
I/dalvikvm-heap( 3794): Grow heap (frag case) to 17.698MB for 728606-byte allocation
D/dalvikvm( 3794): GC_FOR_ALLOC freed 1284K, 17% free 15585K/18772K, paused 30ms, total 30ms
I/dalvikvm-heap( 3794): Grow heap (frag case) to 18.294MB for 1092904-byte allocation
,D/dalvikvm( 3794): GC_CONCURRENT freed 1842K, 20% free 15982K/19840K, paused 2ms+4ms, total 40ms
,D/dalvikvm( 3794): GC_FOR_ALLOC freed 210K, 20% free 15910K/19840K, paused 27ms, total 28ms
,I/dalvikvm-heap( 3794): Grow heap (frag case) to 19.133MB for 1639352-byte allocation
,D/dalvikvm( 3794): GC_CONCURRENT freed 1824K, 24% free 16491K/21444K, paused 2ms+3ms, total 43ms
,D/dalvikvm( 3794): GC_FOR_ALLOC freed 1086K, 24% free 16483K/21444K, paused 28ms, total 28ms
,I/dalvikvm-heap( 3794): Grow heap (frag case) to 20.474MB for 2459024-byte allocation
,D/dalvikvm( 3794): GC_CONCURRENT freed 427K, 21% free 18866K/23848K, paused 4ms+7ms, total 53ms
,D/dalvikvm( 3794): GC_FOR_ALLOC freed 4103K, 27% free 17508K/23848K, paused 37ms, total 37ms
,I/dalvikvm-heap( 3794): Grow heap (frag case) to 22.648MB for 3688532-byte allocation
,D/dalvikvm( 3794): GC_CONCURRENT freed 380K, 24% free 20899K/27452K, paused 4ms+5ms, total 57ms
,D/dalvikvm( 3794): GC_FOR_ALLOC freed 4305K, 33% free 18624K/27452K, paused 33ms, total 33ms
,W/jxcore-log( 3794): Initializing JXcore engine
,W/jxcore-log( 3794): JXcore engine is ready
,D/dalvikvm( 3794): GC_CONCURRENT freed 419K, 22% free 21412K/27452K, paused 3ms+2ms, total 35ms
,D/dalvikvm( 3794): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 3794): WAIT_FOR_CONCURRENT_GC blocked 25ms
,W/jxcore-log( 3794): Starting JXcore engine
,W/jxcore-log( 3794): Platform android
W/jxcore-log( 3794): 
,W/jxcore-log( 3794): Process ARCH arm
W/jxcore-log( 3794): 
,I/jxcore-log( 3794): JXcore Cordova bridge is ready!
I/jxcore-log( 3794): 
,W/jxcore-log( 3794): JXcore engine is started
,E/jxcore  ( 3794): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 3794): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 3794): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager(  987): Killing 3578:com.android.defcontainer/u0a13 (adj 15): empty #9
W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1575): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1575): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1575): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1575): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1575): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1575): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1575): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1575): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/Keyboard.Facilitator( 1194): onFinishInput()
,W/IInputConnectionWrapper( 3794): showStatusIcon on inactive InputConnection
,V/AlarmManager(  987): sending alarm Alarm{4407f3f8 type 3 android}
,V/AlarmManager(  987): sending alarm Alarm{4407e798 type 3 android}
,I/Keyboard.Facilitator.LanguageModelFlusher( 1194): run()
,I/Keyboard.Facilitator( 1194): flushDynamicLanguageModels()
,I/ConfigService( 1208): onCreate
,I/ConfigService( 1208): onDestroy
,V/AlarmManager(  987): sending alarm Alarm{4407d510 type 2 com.google.android.gms}
,D/ConnectivityService(  987): handleInetConditionChange: no active default network - ignore
,V/AlarmManager(  987): sending alarm Alarm{44049180 type 3 android}
,V/GLSActivity( 2078): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2078): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  987): sending alarm Alarm{440431b8 type 3 android}
,V/AlarmManager(  987): sending alarm Alarm{44039c08 type 3 android}
,I/MMApiBackOffService( 1575): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1575): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1575): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1575): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1575): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1575): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1575): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
,D/dalvikvm(  987): GC_EXPLICIT freed 24446K, 66% free 18434K/53200K, paused 9ms+10ms, total 165ms
,D/MMApiWebService( 1575): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
D/MMApiWebService( 1575): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1575): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1575): ProvisionWS.Response.setError: error RadioDownError
I/MMApiWebService( 1575): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1575): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1575): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1575): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/MMApiWebService( 1575): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1575): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1575): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1575): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager(  987): sending alarm Alarm{44035678 type 3 android}
,V/AlarmManager(  987): sending alarm Alarm{4432db60 type 3 android}
,V/AlarmManager(  987): sending alarm Alarm{44045700 type 2 com.google.android.gms}
,D/ConnectivityService(  987): handleInetConditionChange: no active default network - ignore
,V/AlarmManager(  987): sending alarm Alarm{4430efd0 type 3 android}
,V/GLSActivity( 2078): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2078): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  987): sending alarm Alarm{44009748 type 3 android}
,V/AlarmManager(  987): sending alarm Alarm{43eb7b18 type 3 android}
,V/AlarmManager(  987): sending alarm Alarm{43eaf500 type 3 android}
,V/AlarmManager(  987): sending alarm Alarm{43c4ec78 type 3 android}
,V/AlarmManager(  987): sending alarm Alarm{43781ae0 type 3 android}
,V/GLSActivity( 2078): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2078): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  987): sending alarm Alarm{43205f78 type 3 android}
,V/AlarmManager(  987): sending alarm Alarm{4292fcc8 type 3 android}
,I/MMApiBackOffService( 1575): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1575): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1575): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1575): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1575): doRequest(): polling manager says we're not connected, returning with an error: 
,D/MMApiWebService( 1575): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,I/MMApiWebService( 1575): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,E/MMApiProvisionService( 1575): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1575): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1575): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1575): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1575): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1575): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1575): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/MMApiWebService( 1575): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1575): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1575): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1575): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1575): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1575): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager(  987): sending alarm Alarm{4407cf30 type 2 android}
,D/ConnectivityService(  987): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  987): sending alarm Alarm{440bdff8 type 2 com.google.android.gms}
,D/ConnectivityService(  987): Done.
,D/ConnectivityService(  987): Setting timer for 720seconds
,D/ConnectivityService(  987): handleInetConditionChange: no active default network - ignore
,V/AlarmManager(  987): sending alarm Alarm{42891b18 type 3 android}
,V/AlarmManager(  987): sending alarm Alarm{4286dcb0 type 3 android}
,V/AlarmManager(  987): sending alarm Alarm{4286a708 type 3 android}
,V/GLSActivity( 2078): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2078): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  987): sending alarm Alarm{427ac850 type 3 android}
,V/AlarmManager(  987): sending alarm Alarm{42779e40 type 3 android}
,V/AlarmManager(  987): sending alarm Alarm{42288968 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3909): 
D/AndroidRuntime( 3909): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3909): CheckJNI is OFF
D/dalvikvm( 3909): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3909): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3909): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3909): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3909): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3909): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3909): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3909): failed to load memtrack module: -2
D/AndroidRuntime( 3909): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  987): Force stopping com.test.thalitest appid=10136 user=-1: uninstall pkg
I/ActivityManager(  987): Killing 3794:com.test.thalitest/u0a136 (adj 9): stop com.test.thalitest
W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager(  987): Force stopping com.test.thalitest appid=10136 user=0: pkg removed
D/dalvikvm( 2232): GC_EXPLICIT freed 4771K, 45% free 9604K/17224K, paused 2ms+5ms, total 46ms
D/dalvikvm( 2264): GC_EXPLICIT freed 3542K, 42% free 10095K/17224K, paused 3ms+4ms, total 58ms
I/Keyboard.Facilitator( 1194): resetDictionaries() : en_GB
I/Keyboard.Facilitator.DecoderInitializer( 1194): run()
W/GeofencerStateMachine( 1208): Ignoring removeGeofence because network location is disabled.
I/InputReader(  987): Reconfiguring input devices.  changes=0x00000010
I/Decoder ( 1194): createOrResetDecoder
I/PackageManager(  987): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  987):   Action: "android.intent.action.SENDTO"
I/PackageManager(  987):   Category: "android.intent.category.DEFAULT"
D/dalvikvm( 1660): GC_EXPLICIT freed 968K, 33% free 11691K/17224K, paused 4ms+7ms, total 132ms
I/PackageManager(  987):   Scheme: "sms"
D/dalvikvm( 1296): GC_EXPLICIT freed 3152K, 33% free 11594K/17224K, paused 2ms+4ms, total 102ms
I/PackageManager(  987): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  987):   Action: "android.intent.action.SENDTO"
I/PackageManager(  987):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  987):   Scheme: "smsto"
D/VoicemailCleanupService( 1179): Cleaning up data for package: com.test.thalitest
I/Launcher( 1296): Deferring update until onResume
I/PackageManager(  987): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  987):   Action: "android.intent.action.SENDTO"
I/PackageManager(  987):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  987):   Scheme: "mms"
I/PackageManager(  987): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  987):   Action: "android.intent.action.SENDTO"
I/PackageManager(  987):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  987):   Scheme: "mmsto"
D/dalvikvm(  987): GC_EXPLICIT freed 966K, 66% free 18416K/53200K, paused 4ms+11ms, total 128ms
D/dalvikvm(  987): WAIT_FOR_CONCURRENT_GC blocked 72ms
I/ConfigService( 1208): onCreate
I/PackageManager(  987): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  987):   Action: "android.intent.action.SENDTO"
I/PackageManager(  987):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  987):   Scheme: "sms"
I/Launcher( 1296): Deferring update until onResume
I/PackageManager(  987): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  987):   Action: "android.intent.action.SENDTO"
I/PackageManager(  987):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  987):   Scheme: "smsto"
I/InternalIcingCorporaPro( 2264): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  987): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  987):   Action: "android.intent.action.SENDTO"
I/PackageManager(  987):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  987):   Scheme: "mms"
I/ActivityManager(  987): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3941 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
I/PackageManager(  987): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  987):   Action: "android.intent.action.SENDTO"
I/PackageManager(  987):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  987):   Scheme: "mmsto"
W/ContextImpl( 3941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/Keyboard.Facilitator.MainLanguageModelLoader( 1194): run()
I/dalvikvm( 3242): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3242): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 3242): VFY: replacing opcode 0x6e at 0x0013
D/BackupManagerService(  987): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  987): removePackageParticipantsLocked: uid=10136 #1
D/PackageBroadcastService( 1660): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1660): Clearing selected account for com.test.thalitest
I/LocationSettingsChecker( 1660): Removing dialog suppression flag for package com.test.thalitest
I/Keyboard.Facilitator.MainLanguageModelLoader( 1194): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_GB/main%00003aen_gb (offset=0, length=3633960) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1194): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1194): run() : Loading LM = contacts
D/ChimeraCfgMgr( 1660): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1660): Module APK com.google.android.play.games already loaded
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1194): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1194): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1194): run() : Loaded File = UserHistory.en_GB.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1194): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1194): run() : Missing File = Personal.en_GB.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1194): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1194): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1194): run()
I/StatsUtilsManager( 1194): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1194): shouldRecordStats() = Too Soon
E/NetworkScheduler.SchedulerReceiver( 2078): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 2078): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/ChimeraCfgMgr( 1660): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1660): Module APK com.google.android.play.games already loaded
I/ActivityManager(  987): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3969 uid=10058 gids={50058}
D/gH_CompatibleDatabase( 1660): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1660): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1660): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1660): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1660): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1660): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1660): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/Icing   ( 1660): doRemovePackageData com.test.thalitest
I/InternalIcingCorporaPro( 2264): UpdateCorporaTask done [took 187 ms] updated apps [took 187 ms] 
D/gH_CompatibleDatabase( 1660): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1660): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1660): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1660): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1660): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1660): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/Documents( 3969): Loading roots for com.android.providers.downloads.documents
D/dalvikvm(  987): GC_EXPLICIT freed 560K, 66% free 18479K/53200K, paused 5ms+17ms, total 263ms
D/Documents( 3969): Loading roots for com.android.externalstorage.documents
D/dalvikvm( 1208): GC_EXPLICIT freed 997K, 36% free 11111K/17224K, paused 3ms+7ms, total 40ms
E/DataBuffer( 1208): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42078028)
I/ActivityManager(  987): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3983 uid=10020 gids={50020, 1028, 1015, 1023}
I/ActivityManager(  987): Killing 3612:com.google.android.partnersetup/u0a25 (adj 15): empty #9
W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
E/DataBuffer( 1208): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@421f2388)
E/DataBuffer( 1208): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@420f25a0)
E/DataBuffer( 1208): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@420cdda8)
E/DataBuffer( 1208): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42352228)
E/DataBuffer( 1208): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42094f30)
E/DataBuffer( 1208): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@41f80610)
E/DataBuffer( 1208): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@420f6010)
E/DataBuffer( 1208): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@41f4c420)
E/DataBuffer( 1208): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42179bf0)
E/DataBuffer( 1208): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@420eaa10)
E/DataBuffer( 1208): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@423a7c30)
E/DataBuffer( 1208): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42207e00)
E/DataBuffer( 1208): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42195e10)
E/DataBuffer( 1208): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4206e948)
E/DataBuffer( 1208): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@423025d8)
I/ActivityManager(  987): Killing 3637:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1255): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/ExternalStorage( 3983): After updating volumes, found 1 active roots
D/Documents( 3969): Updating roots due to change at content://com.android.externalstorage.documents/root
D/Documents( 3969): Loading roots for com.android.providers.media.documents
D/Documents( 3969): Loading roots for com.google.android.apps.docs.storage
D/AndroidRuntime( 3909): Shutting down VM
D/dalvikvm( 3909): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
D/Documents( 3969): Update found 7 roots in 146ms
D/Documents( 3969): Used cached roots for com.android.providers.downloads.documents
D/Documents( 3969): Loading roots for com.android.externalstorage.documents
D/Documents( 3969): Used cached roots for com.android.providers.media.documents
D/Documents( 3969): Used cached roots for com.google.android.apps.docs.storage
D/Documents( 3969): Update found 7 roots in 6ms

```
