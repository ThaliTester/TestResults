#### Test 56818254e6f5c3b_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
,V/AlarmManager( 1019): sending alarm Alarm{43f20148 type 3 android}
--------- beginning of /dev/log/main
D/AndroidRuntime( 3506): 
D/AndroidRuntime( 3506): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3506): CheckJNI is OFF
D/dalvikvm( 3506): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3506): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3506): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3506): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3506): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3506): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3506): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3506): failed to load memtrack module: -2
D/AndroidRuntime( 3506): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3506
W/WindowManager( 1019): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3523 uid=10104 gids={50104, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3506): Shutting down VM
D/dalvikvm( 3506): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+1ms, total 3ms
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3523): Binding Chromium to main looper Looper (main, tid 1) {41fe6a80}
I/LibraryLoader( 3523): Expected native library version number "",actual native library version number ""
I/chromium( 3523): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3523): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43b92150:true
D/BluetoothAdapter( 3523): 1107276520: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3523): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3523): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3523): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3523): Local Branch: 
I/Adreno-EGL( 3523): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3523): Local Patches: NONE
I/Adreno-EGL( 3523): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 3523): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 3523): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 3523): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3523): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3523): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3523): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 3523): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 3523): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 3523): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3523): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3523): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3523): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3523): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3523): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3523): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 3523): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3523): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
,W/dalvikvm( 3523): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3523): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3523): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3523): Enabling debug mode 0
,W/AwContents( 3523): nativeOnDraw failed; clearing to background color.
,I/Keyboard.Facilitator( 1197): onFinishInput()
,W/IInputConnectionWrapper( 3523): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1019): Displayed com.test.thalitest/.MainActivity,cp,ca,418
I/ActivityManager( 1019): Displayed com.test.thalitest/.MainActivity: +386ms (total +418ms)
,D/JsMessageQueue( 3523): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3523): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41feb188
,D/dalvikvm( 3523): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41feb188
,D/jxcore_app_log( 3523): JniHelper::setJavaVM(0x41637fa8), pthread_self() = 1614658584
,I/chromium( 3523): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/dalvikvm( 3523): GC_CONCURRENT freed 3357K, 20% free 13832K/17224K, paused 2ms+3ms, total 48ms
,D/dalvikvm( 3523): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 3523): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/dalvikvm( 3523): GC_FOR_ALLOC freed 65K, 20% free 13822K/17224K, paused 25ms, total 26ms
,I/dalvikvm-heap( 3523): Grow heap (frag case) to 15.839MB for 323830-byte allocation
,D/dalvikvm( 3523): GC_FOR_ALLOC freed 623K, 21% free 13888K/17544K, paused 25ms, total 26ms
,I/dalvikvm-heap( 3523): Grow heap (frag case) to 16.058MB for 485740-byte allocation
,D/dalvikvm( 3523): GC_FOR_ALLOC freed 866K, 22% free 14064K/18020K, paused 25ms, total 26ms
,I/dalvikvm-heap( 3523): Grow heap (frag case) to 16.461MB for 728606-byte allocation
,D/dalvikvm( 3523): GC_FOR_ALLOC freed 1284K, 24% free 14319K/18732K, paused 25ms, total 26ms
,I/dalvikvm-heap( 3523): Grow heap (frag case) to 17.058MB for 1092904-byte allocation
,D/dalvikvm( 3523): GC_CONCURRENT freed 1752K, 26% free 14746K/19800K, paused 1ms+10ms, total 39ms
,D/dalvikvm( 3523): GC_FOR_ALLOC freed 305K, 27% free 14639K/19800K, paused 25ms, total 26ms
,I/dalvikvm-heap( 3523): Grow heap (frag case) to 17.892MB for 1639352-byte allocation
,D/dalvikvm( 3523): GC_CONCURRENT freed 1546K, 30% free 15196K/21404K, paused 1ms+3ms, total 35ms
,D/dalvikvm( 3523): GC_FOR_ALLOC freed 1527K, 29% free 15326K/21404K, paused 29ms, total 31ms
,I/dalvikvm-heap( 3523): Grow heap (frag case) to 19.344MB for 2459024-byte allocation
,D/dalvikvm( 3523): GC_CONCURRENT freed 272K, 18% free 17568K/21404K, paused 4ms+3ms, total 43ms
,D/dalvikvm( 3523): GC_FOR_ALLOC freed 3794K, 25% free 16204K/21404K, paused 31ms, total 33ms
,I/dalvikvm-heap( 3523): Grow heap (frag case) to 20.039MB for 2288418-byte allocation
,W/jxcore-log( 3523): Initializing JXcore engine
,W/jxcore-log( 3523): JXcore engine is ready
,W/jxcore-log( 3523): Starting JXcore engine
,D/dalvikvm( 3523): GC_CONCURRENT freed 551K, 23% free 18296K/23640K, paused 2ms+3ms, total 36ms
,W/jxcore-log( 3523): Platform android
W/jxcore-log( 3523): 
,W/jxcore-log( 3523): Process ARCH arm
W/jxcore-log( 3523): 
,I/jxcore-log( 3523): JXcore Cordova bridge is ready!
I/jxcore-log( 3523): 
,W/jxcore-log( 3523): JXcore engine is started
,E/jxcore  ( 3523): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 3523): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 3523): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager( 1019): Killing 3273:com.android.calendar/u0a7 (adj 15): empty #9
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1583): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1583): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1583): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1583): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1583): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1583): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1583): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1583): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/Keyboard.Facilitator( 1197): onFinishInput()
,W/IInputConnectionWrapper( 3523): showStatusIcon on inactive InputConnection
,V/GLSActivity( 2056): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2056): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{43f1f498 type 3 android}
,I/Keyboard.Facilitator.LanguageModelFlusher( 1197): run()
,I/Keyboard.Facilitator( 1197): flushDynamicLanguageModels()
,I/ConfigService( 1214): onCreate
,I/ConfigService( 1214): onDestroy
,V/AlarmManager( 1019): sending alarm Alarm{43f21330 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  271): write error (Broken pipe)
,V/AlarmManager( 1019): sending alarm Alarm{43f0d218 type 3 android}
,I/MMApiBackOffService( 1583): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1583): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1583): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1583): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1583): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1583): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/MMApiWebService( 1583): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,E/MMApiProvisionService( 1583): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1583): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1583): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1583): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1583): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1583): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1583): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1583): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1583): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1583): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1583): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1583): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{43f0ac40 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43f097c8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43f083f8 type 3 android}
,V/GLSActivity( 2056): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2056): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  271): write error (Broken pipe)
,V/AlarmManager( 1019): sending alarm Alarm{43f07510 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43f02478 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43f01988 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43f31e18 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1019): sending alarm Alarm{43f0b908 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  271): write error (Broken pipe)
,V/AlarmManager( 1019): sending alarm Alarm{43f005b0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43ef94b0 type 3 android}
,V/GLSActivity( 2056): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2056): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1019): GC_EXPLICIT freed 19425K, 58% free 18459K/43560K, paused 3ms+9ms, total 145ms
,V/AlarmManager( 1019): sending alarm Alarm{43ef8388 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43bdb8c8 type 3 android}
,I/MMApiBackOffService( 1583): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1583): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1583): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1583): doRequest() with req : MMApiWSRequest(v1/ns/list/messages),
D/MMApiWebService( 1583): doRequest(): polling manager says we're not connected, returning with an error: 
D/MMApiWebService( 1583): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1583): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1583): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiWebService( 1583): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1583): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1583): MMApiWebService told us not to continue at the moment with this request: devices.json
I/MMApiWebService( 1583): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1583): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1583): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1583): MMApiWebService told us not to continue at the moment with this request: 
D/MMApiWebService( 1583): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1583): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1583): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1583): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1583): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{43843c80 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43600de0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4359d078 type 3 android}
,V/GLSActivity( 2056): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2056): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{43594fc0 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{43589100 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{43573978 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{435714f8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{433f90b8 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3626): 
D/AndroidRuntime( 3626): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3626): CheckJNI is OFF
D/dalvikvm( 3626): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3626): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3626): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3626): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3626): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3626): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3626): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3626): failed to load memtrack module: -2
D/AndroidRuntime( 3626): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10104 user=-1: uninstall pkg
I/ActivityManager( 1019): Killing 3523:com.test.thalitest/u0a104 (adj 9): stop com.test.thalitest
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10104 user=0: pkg removed
D/dalvikvm( 2192): GC_EXPLICIT freed 4773K, 45% free 9603K/17224K, paused 1ms+6ms, total 42ms
D/dalvikvm( 1302): GC_EXPLICIT freed 2567K, 33% free 11589K/17224K, paused 2ms+4ms, total 38ms
D/dalvikvm( 2232): GC_EXPLICIT freed 2242K, 44% free 9805K/17224K, paused 3ms+17ms, total 87ms
D/dalvikvm( 1643): GC_EXPLICIT freed 996K, 35% free 11309K/17224K, paused 4ms+37ms, total 120ms
I/Keyboard.Facilitator( 1197): resetDictionaries() : en_GB
W/GeofencerStateMachine( 1214): Ignoring removeGeofence because network location is disabled.
I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator.DecoderInitializer( 1197): run()
D/VoicemailCleanupService( 1180): Cleaning up data for package: com.test.thalitest
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
I/Decoder ( 1197): createOrResetDecoder
I/Launcher( 1302): Deferring update until onResume
D/dalvikvm( 1019): GC_EXPLICIT freed 735K, 58% free 18326K/43560K, paused 4ms+9ms, total 108ms
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
I/InternalIcingCorporaPro( 2232): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
I/ActivityManager( 1019): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3667 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
I/Launcher( 1302): Deferring update until onResume
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/ConfigService( 1214): onCreate
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
W/dalvikvm( 1214): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1019): removePackageParticipantsLocked: uid=10104 #1
E/dalvikvm( 1214): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 1214): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
D/dalvikvm( 1214): VFY: replacing opcode 0x1f at 0x00f6
W/ContextImpl( 3667): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
W/dalvikvm( 1214): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
I/dalvikvm( 1214): Could not find method android.telephony.SubscriptionManager.getActiveSubscriptionInfoList, referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 1214): VFY: unable to resolve virtual method 6547: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
D/dalvikvm( 1214): VFY: replacing opcode 0x6e at 0x0004
D/dalvikvm( 1214): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 1214): VFY: unable to resolve static field 229 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 1214): VFY: replacing opcode 0x62 at 0x0008
D/dalvikvm( 1214): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
I/dalvikvm( 1214): DexOpt: unable to optimize static field ref 0x00e5 at 0x0c in Lcom/google/android/gms/checkin/d;.a
I/CheckinRequestBuilder( 1214): Classify the device as Phone.
I/dalvikvm( 3071): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3071): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 3071): VFY: replacing opcode 0x6e at 0x0013
D/PackageBroadcastService( 1643): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1643): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1643): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1643): Module APK com.google.android.play.games already loaded
E/dalvikvm( 1214): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
W/dalvikvm( 1214): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
D/dalvikvm( 1214): VFY: replacing opcode 0x1f at 0x000e
D/ChimeraCfgMgr( 1643): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1643): Module APK com.google.android.play.games already loaded
W/dalvikvm( 1214): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1214): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1214): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 1214): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1214): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
D/dalvikvm( 1214): VFY: replacing opcode 0x6e at 0x00bb
E/NetworkScheduler.SchedulerReceiver( 2056): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 2056): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/dalvikvm( 1214): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1214): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
D/dalvikvm( 1214): VFY: replacing opcode 0x6e at 0x003d
I/InternalIcingCorporaPro( 2232): UpdateCorporaTask done [took 165 ms] updated apps [took 165 ms] 
I/ActivityManager( 1019): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3697 uid=10058 gids={50058}
I/LocationSettingsChecker( 1643): Removing dialog suppression flag for package com.test.thalitest
W/FetchTask( 1214): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/gH_CompatibleDatabase( 1643): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1643): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1643): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1643): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1643): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1643): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1643): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1643): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1643): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1643): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
I/CheckinRequestBuilder( 1214): Classify the device as Phone.
D/gH_CompatibleDatabase( 1643): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/Documents( 3697): Loading roots for com.android.providers.downloads.documents
D/gH_CompatibleDatabase( 1643): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1643): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
W/FetchTask( 1214): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/dalvikvm( 1019): GC_EXPLICIT freed 708K, 58% free 18443K/43560K, paused 6ms+20ms, total 333ms
I/ActivityManager( 1019): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=3718 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
I/CheckinRequestBuilder( 1214): Classify the device as Phone.
W/BaseAppContext( 1643): Using Auth Proxy for data requests.
W/FetchTask( 1214): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
W/BaseAppContext( 1643): Using Auth Proxy for data requests.
I/ActivityManager( 1019): Killing 3364:com.google.android.partnersetup/u0a25 (adj 15): empty #9
I/ActivityManager( 1019): Killing 3338:com.android.defcontainer/u0a13 (adj 15): empty #10
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/GMPM-SVC( 1643): App measurement is starting up, version: 8489
I/CheckinRequestBuilder( 1214): Classify the device as Phone.
I/GMPM-SVC( 1643): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
W/FetchTask( 1214): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/Icing   ( 1643): doRemovePackageData com.test.thalitest
I/CheckinRequestBuilder( 1214): Classify the device as Phone.
D/AndroidRuntime( 3626): Shutting down VM
D/dalvikvm( 3626): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 3ms
W/FetchTask( 1214): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/Documents( 3697): Loading roots for com.android.externalstorage.documents
D/dalvikvm( 3718): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41ff0470, skipping init
I/openssl ( 3718): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3718): Crypto mode 0 already enabled
I/ActivityManager( 1019): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3747 uid=10020 gids={50020, 1028, 1015, 1023}
I/Keyboard.Facilitator.MainLanguageModelLoader( 1197): run()
I/ActivityManager( 1019): Killing 3052:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/ExternalStorage( 3747): After updating volumes, found 1 active roots
D/Documents( 3697): Updating roots due to change at content://com.android.externalstorage.documents/root
I/Keyboard.Facilitator.MainLanguageModelLoader( 1197): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_GB/main%00003aen_gb (offset=0, length=3633960) with up to date LoudsLmContentVersion = 20150512
D/Documents( 3697): Loading roots for com.android.providers.media.documents
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1197): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1197): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1197): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1197): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1197): run() : Loaded File = UserHistory.en_GB.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1197): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1197): run() : Missing File = Personal.en_GB.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1197): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1197): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1197): run()
I/StatsUtilsManager( 1197): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1197): shouldRecordStats() = Too Soon
D/Documents( 3697): Loading roots for com.google.android.apps.docs.storage
D/dalvikvm( 2056): GC_EXPLICIT freed 1368K, 41% free 10274K/17224K, paused 2ms+4ms, total 33ms
D/Documents( 3697): Update found 7 roots in 332ms
D/Documents( 3697): Used cached roots for com.android.providers.downloads.documents
D/Documents( 3697): Loading roots for com.android.externalstorage.documents
D/Documents( 3697): Used cached roots for com.android.providers.media.documents
D/Documents( 3697): Used cached roots for com.google.android.apps.docs.storage
D/Documents( 3697): Update found 7 roots in 7ms
W/DriveInitializer( 1643): Awaiting to be initialized
W/DriveInitializer( 1643): Background init thread started
E/cutils  (  261): Failed to mkdirat(/storage/sdcard1/Android): Read-only file system
W/Vold    (  261): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 1643): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.gms/files
W/DriveInitializer( 1643): Background init thread ended

```
