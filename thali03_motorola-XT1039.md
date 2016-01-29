#### Test 575312430087a60_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
,V/AlarmManager( 1016): sending alarm Alarm{43f065f0 type 3 android}
--------- beginning of /dev/log/main
D/AndroidRuntime( 3803): 
D/AndroidRuntime( 3803): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3803): CheckJNI is OFF
D/dalvikvm( 3803): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3803): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3803): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3803): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3803): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3803): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3803): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3803): failed to load memtrack module: -2
D/AndroidRuntime( 3803): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1016): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3803
W/WindowManager( 1016): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1016): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3819 uid=10106 gids={50106, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3803): Shutting down VM
D/dalvikvm( 3803): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
W/ContextImpl( 1253): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1253): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3819): Binding Chromium to main looper Looper (main, tid 1) {41fbfc40}
I/LibraryLoader( 3819): Expected native library version number "",actual native library version number ""
I/chromium( 3819): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3819): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1016): Message: 20
D/BluetoothManagerService( 1016): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@432d14f8:true
D/BluetoothAdapter( 3819): 1107117224: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3819): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3819): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3819): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3819): Local Branch: 
I/Adreno-EGL( 3819): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3819): Local Patches: NONE
I/Adreno-EGL( 3819): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 3819): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 3819): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3819): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3819): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3819): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3819): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3819): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3819): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3819): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3819): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3819): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 3819): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3819): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3819): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3819): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3819): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3819): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3819): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 3819): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 3819): CordovaWebView is running on device made by: motorola
D/OpenGLRenderer( 3819): Enabling debug mode 0
W/AwContents( 3819): nativeOnDraw failed; clearing to background color.
I/Keyboard.Facilitator( 1196): onFinishInput()
I/LaunchCheckinHandler( 1016): Displayed com.test.thalitest/.MainActivity,cp,ca,437
I/ActivityManager( 1016): Displayed com.test.thalitest/.MainActivity: +410ms (total +438ms)
W/AwContents( 3819): nativeOnDraw failed; clearing to background color.
W/IInputConnectionWrapper( 3819): showStatusIcon on inactive InputConnection
D/JsMessageQueue( 3819): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 3819): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fc4348
D/dalvikvm( 3819): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fc4348
D/jxcore_app_log( 3819): JniHelper::setJavaVM(0x41612fa8), pthread_self() = 1612685688
I/chromium( 3819): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/dalvikvm( 3819): GC_CONCURRENT freed 3357K, 20% free 13831K/17224K, paused 1ms+3ms, total 44ms
D/dalvikvm( 3819): WAIT_FOR_CONCURRENT_GC blocked 12ms
D/dalvikvm( 3819): WAIT_FOR_CONCURRENT_GC blocked 16ms
D/dalvikvm( 3819): GC_FOR_ALLOC freed 124K, 21% free 13760K/17224K, paused 26ms, total 26ms
I/dalvikvm-heap( 3819): Grow heap (frag case) to 15.779MB for 323830-byte allocation
D/dalvikvm( 3819): GC_FOR_ALLOC freed 561K, 21% free 13888K/17544K, paused 23ms, total 23ms
I/dalvikvm-heap( 3819): Grow heap (frag case) to 16.058MB for 485740-byte allocation
,D/dalvikvm( 3819): GC_FOR_ALLOC freed 865K, 22% free 14064K/18020K, paused 24ms, total 25ms
,I/dalvikvm-heap( 3819): Grow heap (frag case) to 16.461MB for 728606-byte allocation
,D/dalvikvm( 3819): GC_FOR_ALLOC freed 1285K, 24% free 14320K/18732K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3819): Grow heap (frag case) to 17.059MB for 1092904-byte allocation
,D/dalvikvm( 3819): GC_CONCURRENT freed 1722K, 26% free 14739K/19800K, paused 2ms+3ms, total 52ms
,D/dalvikvm( 3819): GC_FOR_ALLOC freed 330K, 27% free 14642K/19800K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3819): Grow heap (frag case) to 17.895MB for 1639352-byte allocation
,D/dalvikvm( 3819): GC_CONCURRENT freed 1453K, 30% free 15188K/21404K, paused 3ms+2ms, total 31ms
,D/dalvikvm( 3819): GC_FOR_ALLOC freed 1619K, 29% free 15336K/21404K, paused 30ms, total 30ms
,I/dalvikvm-heap( 3819): Grow heap (frag case) to 19.354MB for 2459024-byte allocation
,D/dalvikvm( 3819): GC_CONCURRENT freed 213K, 18% free 17614K/21404K, paused 4ms+5ms, total 40ms
,D/dalvikvm( 3819): GC_FOR_ALLOC freed 3871K, 25% free 16207K/21404K, paused 32ms, total 33ms
,I/dalvikvm-heap( 3819): Grow heap (frag case) to 20.042MB for 2288606-byte allocation
,W/jxcore-log( 3819): Initializing JXcore engine
,W/jxcore-log( 3819): JXcore engine is ready
,D/dalvikvm( 3819): GC_CONCURRENT freed 531K, 23% free 18241K/23640K, paused 2ms+3ms, total 32ms
,W/jxcore-log( 3819): Starting JXcore engine
,W/jxcore-log( 3819): Platform android
W/jxcore-log( 3819): 
,W/jxcore-log( 3819): Process ARCH arm
W/jxcore-log( 3819): 
,I/jxcore-log( 3819): JXcore Cordova bridge is ready!
I/jxcore-log( 3819): 
,W/jxcore-log( 3819): JXcore engine is started
,E/jxcore  ( 3819): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 3819): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 3819): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager( 1016): Killing 3588:com.android.defcontainer/u0a13 (adj 15): empty #9
W/ContextImpl( 1253): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1253): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1253): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1592): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1592): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1592): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1592): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1592): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1592): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1592): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1592): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/Keyboard.Facilitator( 1196): onFinishInput()
,W/IInputConnectionWrapper( 3819): showStatusIcon on inactive InputConnection
,I/SFPerfTracer(  275):      triggers: (rate: 1:26) (compose: 0:4) (post: 0:1) (render: 0:5) (0:116 frames) (1:598)
,D/SFPerfTracer(  275):        layers: (0:13) (FocusedStackFrame: 0:10)* (StatusBar: 0:206)* (NavigationBar: 0:34)* (com.android.systemui.ImageWallpaper: 0:8)* (Starting com.motorola.ccc.ota: 0:34)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity: 0:12)* (ElectronBeam: 0:27)* (com.test.thalitest/com.test.thalitest.MainActivity: 0:5)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity: 1:1)* 
,W/ProcessCpuTracker( 1016): Skipping unknown process pid 3868
,W/ProcessCpuTracker( 1016): Skipping unknown process pid 3869
,W/ProcessCpuTracker( 1016): Skipping unknown process pid 3879
,V/AlarmManager( 1016): sending alarm Alarm{43f16638 type 2 com.motorola.ccc.cce}
,I/PollingManager( 1592): alarm fired!
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1016): sending alarm Alarm{43f02980 type 3 android}
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
,I/Keyboard.Facilitator.LanguageModelFlusher( 1196): run()
,I/Keyboard.Facilitator( 1196): flushDynamicLanguageModels()
,I/ConfigService( 1215): onCreate
,D/dalvikvm( 1215): GC_EXPLICIT freed 1111K, 36% free 11110K/17224K, paused 4ms+6ms, total 42ms
,E/DataBuffer( 1215): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@41fff138)
,E/DataBuffer( 1215): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@421d30b8)
E/DataBuffer( 1215): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@421801a0)
,E/DataBuffer( 1215): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4220ea60)
,E/DataBuffer( 1215): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@423c96f8)
,E/DataBuffer( 1215): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@421da570)
,I/ConfigService( 1215): onDestroy
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1016): GC_EXPLICIT freed 19336K, 58% free 18433K/43588K, paused 3ms+10ms, total 143ms
,V/AlarmManager( 1016): sending alarm Alarm{43ee0a88 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{4404a010 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{43f04088 type 2 com.google.android.gms}
,D/ConnectivityService( 1016): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  271): write error (Broken pipe)
,I/MMApiBackOffService( 1592): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1592): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1592): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1592): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1592): doRequest(): polling manager says we're not connected, returning with an error: 
,D/MMApiWebService( 1592): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,E/MMApiProvisionService( 1592): ProvisionWS.Response: Missing mandatory message data in response from DM server...
I/MMApiWebService( 1592): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,E/MMApiProvisionService( 1592): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1592): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1592): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1592): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1592): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1592): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1592): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1592): doRequest(): polling manager says we're not connected, returning with an error: 
D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1592): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1592): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1592): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1016): sending alarm Alarm{4362bf20 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{43574680 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{43573b10 type 3 android}
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  271): write error (Broken pipe)
,V/AlarmManager( 1016): sending alarm Alarm{43572e50 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{435530c8 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{435513d0 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{43550060 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{43f15c18 type 2 android}
,D/ConnectivityService( 1016): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1016): sending alarm Alarm{4357bf00 type 2 com.google.android.gms}
,D/ConnectivityService( 1016): Done.
,D/ConnectivityService( 1016): Setting timer for 720seconds
,D/ConnectivityService( 1016): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  271): write error (Broken pipe)
,V/AlarmManager( 1016): sending alarm Alarm{43542ad8 type 3 android}
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1016): sending alarm Alarm{429a7f40 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{428ee2f0 type 3 android}
,I/MMApiBackOffService( 1592): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1592): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1592): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1592): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1592): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/MMApiWebService( 1592): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1592): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1592): ProvisionWS.Response: Missing mandatory message data in response from DM server...
D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,E/MMApiProvisionService( 1592): ProvisionWS.Response.setError: error RadioDownError
I/MMApiBackOffService( 1592): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1592): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1592): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1592): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1592): MMApiWebService told us not to continue at the moment with this request: devices.json
D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1592): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
D/MMApiWebService( 1592): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1592): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1592): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1592): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1592): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1016): sending alarm Alarm{428cd2f0 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{428c81e0 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{428c7ae8 type 3 android}
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1340): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1016): sending alarm Alarm{428bd620 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{428a81d0 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{4289a5f0 type 3 android}
,V/AlarmManager( 1016): sending alarm Alarm{4288d188 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms)
```
