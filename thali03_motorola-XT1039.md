#### Test 573480784751f5c_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
--------- beginning of /dev/log/system
W/SocketClient(  273): write error (Broken pipe)
D/AndroidRuntime( 3882): 
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
D/AndroidRuntime( 3882): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3882
W/WindowManager( 1019): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3898 uid=10144 gids={50144, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3882): Shutting down VM
D/dalvikvm( 3882): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+1ms, total 3ms
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3898): Binding Chromium to main looper Looper (main, tid 1) {422dbdc8}
I/LibraryLoader( 3898): Expected native library version number "",actual native library version number ""
I/chromium( 3898): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3898): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43dbbd10:true
D/BluetoothAdapter( 3898): 1110377432: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3898): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3898): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3898): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3898): Local Branch: 
I/Adreno-EGL( 3898): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3898): Local Patches: NONE
I/Adreno-EGL( 3898): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 3898): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 3898): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 3898): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3898): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3898): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
,W/dalvikvm( 3898): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 3898): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 3898): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 3898): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3898): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3898): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3898): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3898): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3898): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
,W/dalvikvm( 3898): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 3898): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3898): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3898): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3898): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3898): CordovaWebView is running on device made by: motorola
,I/SFPerfTracer(  277):      triggers: (rate: 1:30) (compose: 0:5) (post: 0:1) (render: 0:6) (0:133 frames) (1:607)
,D/SFPerfTracer(  277):        layers: (0:11) (FocusedStackFrame: 1:8)* (StatusBar: 0:217)* (NavigationBar: 0:39)* (com.android.systemui.ImageWallpaper: 0:6)* (Starting com.motorola.ccc.ota: 0:33)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity: 0:13)* (ElectronBeam: 0:27)* 
,D/OpenGLRenderer( 3898): Enabling debug mode 0
,W/AwContents( 3898): nativeOnDraw failed; clearing to background color.
,I/Keyboard.Facilitator( 1192): onFinishInput()
,W/IInputConnectionWrapper( 3898): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1019): Displayed com.test.thalitest/.MainActivity,cp,ca,439
I/ActivityManager( 1019): Displayed com.test.thalitest/.MainActivity: +413ms (total +439ms)
,D/JsMessageQueue( 3898): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3898): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422e0278
,D/dalvikvm( 3898): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422e0278
,D/jxcore_app_log( 3898): JniHelper::setJavaVM(0x419f8f78), pthread_self() = 1614907304
,I/chromium( 3898): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/dalvikvm( 3898): GC_CONCURRENT freed 2659K, 16% free 14530K/17224K, paused 3ms+3ms, total 43ms
,D/dalvikvm( 3898): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 3898): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 3898): GC_FOR_ALLOC freed 424K, 14% free 14894K/17224K, paused 28ms, total 29ms
,D/dalvikvm( 3898): GC_FOR_ALLOC freed 104K, 14% free 14900K/17224K, paused 28ms, total 29ms
,I/dalvikvm-heap( 3898): Grow heap (frag case) to 16.645MB for 63974-byte allocation
,D/dalvikvm( 3898): GC_FOR_ALLOC freed 126K, 14% free 14921K/17288K, paused 27ms, total 28ms
,I/dalvikvm-heap( 3898): Grow heap (frag case) to 16.695MB for 95956-byte allocation
,D/dalvikvm( 3898): GC_FOR_ALLOC freed 179K, 14% free 14955K/17384K, paused 27ms, total 28ms
,I/dalvikvm-heap( 3898): Grow heap (frag case) to 16.775MB for 143930-byte allocation
,D/dalvikvm( 3898): GC_FOR_ALLOC freed 254K, 15% free 15002K/17528K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3898): Grow heap (frag case) to 16.889MB for 215890-byte allocation
,D/dalvikvm( 3898): GC_FOR_ALLOC freed 367K, 16% free 15076K/17740K, paused 26ms, total 27ms
,I/dalvikvm-heap( 3898): Grow heap (frag case) to 17.064MB for 323830-byte allocation
,D/dalvikvm( 3898): GC_FOR_ALLOC freed 568K, 16% free 15197K/18060K, paused 27ms, total 28ms
,D/dalvikvm( 3898): GC_FOR_ALLOC freed 864K, 15% free 15373K/18060K, paused 28ms, total 29ms
,I/dalvikvm-heap( 3898): Grow heap (frag case) to 17.740MB for 728606-byte allocation
,D/dalvikvm( 3898): GC_FOR_ALLOC freed 1281K, 17% free 15629K/18772K, paused 29ms, total 30ms
,I/dalvikvm-heap( 3898): Grow heap (frag case) to 18.337MB for 1092904-byte allocation
,D/dalvikvm( 3898): GC_CONCURRENT freed 1818K, 20% free 16018K/19840K, paused 2ms+3ms, total 40ms
,D/dalvikvm( 3898): GC_FOR_ALLOC freed 247K, 20% free 15938K/19840K, paused 28ms, total 28ms
,I/dalvikvm-heap( 3898): Grow heap (frag case) to 19.161MB for 1639352-byte allocation
,D/dalvikvm( 3898): GC_CONCURRENT freed 1846K, 23% free 16544K/21444K, paused 1ms+5ms, total 44ms
,D/dalvikvm( 3898): GC_FOR_ALLOC freed 1053K, 23% free 16522K/21444K, paused 29ms, total 29ms
,I/dalvikvm-heap( 3898): Grow heap (frag case) to 20.512MB for 2459024-byte allocation
,D/dalvikvm( 3898): GC_CONCURRENT freed 263K, 21% free 18872K/23848K, paused 4ms+4ms, total 39ms
,D/dalvikvm( 3898): GC_FOR_ALLOC freed 4257K, 27% free 17568K/23848K, paused 37ms, total 37ms
,I/dalvikvm-heap( 3898): Grow heap (frag case) to 22.706MB for 3688532-byte allocation
,D/dalvikvm( 3898): GC_CONCURRENT freed 401K, 24% free 20930K/27452K, paused 4ms+5ms, total 57ms
,D/dalvikvm( 3898): GC_FOR_ALLOC freed 4363K, 32% free 18678K/27452K, paused 33ms, total 35ms
,W/jxcore-log( 3898): Initializing JXcore engine
,W/jxcore-log( 3898): JXcore engine is ready
,D/dalvikvm( 3898): GC_CONCURRENT freed 431K, 22% free 21472K/27452K, paused 2ms+2ms, total 33ms
,D/dalvikvm( 3898): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 3898): WAIT_FOR_CONCURRENT_GC blocked 26ms
,W/jxcore-log( 3898): Starting JXcore engine
,W/jxcore-log( 3898): Platform android
W/jxcore-log( 3898): 
,W/jxcore-log( 3898): Process ARCH arm
W/jxcore-log( 3898): 
,I/jxcore-log( 3898): JXcore Cordova bridge is ready!
I/jxcore-log( 3898): 
,W/jxcore-log( 3898): JXcore engine is started
,E/jxcore  ( 3898): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 3898): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 3898): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager( 1019): Killing 3671:com.android.defcontainer/u0a13 (adj 15): empty #9
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1586): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1586): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1586): publish the event [tag = MOT_OTA event name = LOG]
,D/dalvikvm( 1019): GC_EXPLICIT freed 24601K, 66% free 18455K/53296K, paused 4ms+10ms, total 146ms
,D/OtaApp  ( 1586): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1586): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1586): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1586): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1586): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/Keyboard.Facilitator( 1192): onFinishInput()
,W/IInputConnectionWrapper( 3898): showStatusIcon on inactive InputConnection
,V/AlarmManager( 1019): sending alarm Alarm{442b7ec8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{442d8020 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,I/Keyboard.Facilitator.LanguageModelFlusher( 1192): run()
,I/Keyboard.Facilitator( 1192): flushDynamicLanguageModels()
,I/ConfigService( 1209): onCreate
,I/ConfigService( 1209): onDestroy
,V/AlarmManager( 1019): sending alarm Alarm{44c10dd8 type 3 android}
,I/MMApiBackOffService( 1586): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1586): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1586): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1586): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1586): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,D/MMApiWebService( 1586): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1586): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,I/MMApiWebService( 1586): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,E/MMApiProvisionService( 1586): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1586): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1586): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1586): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1586): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1586): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/MMApiWebService( 1586): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1586): MMApiWebService told us not to continue at the moment with this request: devices.json
,I/MMApiWebService( 1586): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1586): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1586): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{442600c8 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{4425f5a0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4400ce98 type 3 android}
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{43e31400 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{442b7858 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1019): sending alarm Alarm{42ce92d8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42cb0ab0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{442d6580 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1019): sending alarm Alarm{442d5b50 type 0 com.google.android.gms}
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
,I/EventLogService( 1657): Aggregate from 1453984201506 (log), 1453984201506 (data)
,V/AlarmManager( 1019): sending alarm Alarm{42c07400 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42b485c0 type 3 android}
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{42b44088 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42b228d8 type 3 android}
,I/MMApiBackOffService( 1586): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1586): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1586): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1586): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1586): doRequest(): polling manager says we're not connected, returning with an error: devices.json
D/MMApiWebService( 1586): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1586): ProvisionWS.Response: Missing mandatory message data in response from DM server...
E/MMApiProvisionService( 1586): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiWebService( 1586): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1586): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1586): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1586): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1586): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1586): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1586): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1586): doRequest(): polling manager says we're not connected, returning with an error: 
D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1586): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1586): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1586): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1586): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{42b05458 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42b01be8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42afa408 type 3 android}
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{42af4bf8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42ada2c0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42ac9518 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42bf8230 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): handleInetConditionChange: no active default network - ignore,
,V/AlarmManager( 1019): sending alarm Alarm{42930de0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{428d62a0 type 3 android}
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2067): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 4012): 
D/AndroidRuntime( 4012): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4012): CheckJNI is OFF
D/dalvikvm( 4012): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4012): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4012): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4012): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4012): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4012): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4012): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4012): failed to load memtrack module: -2
D/AndroidRuntime( 4012): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10144 user=-1: uninstall pkg
I/ActivityManager( 1019): Killing 3898:com.test.thalitest/u0a144 (adj 9): stop com.test.thalitest
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10144 user=0: pkg removed
D/dalvikvm( 1657): GC_EXPLICIT freed 1479K, 32% free 11857K/17224K, paused 4ms+7ms, total 62ms
D/dalvikvm( 2212): GC_EXPLICIT freed 4750K, 45% free 9603K/17224K, paused 2ms+12ms, total 70ms
I/Keyboard.Facilitator( 1192): resetDictionaries() : en_GB
I/Keyboard.Facilitator.DecoderInitializer( 1192): run()
W/GeofencerStateMachine( 1209): Ignoring removeGeofence because network location is disabled.
I/Decoder ( 1192): createOrResetDecoder
I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
D/dalvikvm( 2249): GC_EXPLICIT freed 3073K, 42% free 10067K/17224K, paused 3ms+4ms, total 122ms
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
D/VoicemailCleanupService( 1179): Cleaning up data for package: com.test.thalitest
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
I/ConfigService( 1209): onCreate
D/dalvikvm( 1300): GC_EXPLICIT freed 3152K, 33% free 11597K/17224K, paused 2ms+9ms, total 155ms
I/Launcher( 1300): Deferring update until onResume
D/dalvikvm( 1019): GC_EXPLICIT freed 1230K, 66% free 18463K/53296K, paused 3ms+11ms, total 147ms
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
D/dalvikvm( 1019): WAIT_FOR_CONCURRENT_GC blocked 37ms
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
I/InternalIcingCorporaPro( 2249): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager( 1019): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4043 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
D/dalvikvm( 1209): GC_EXPLICIT freed 1244K, 36% free 11124K/17224K, paused 3ms+8ms, total 46ms
E/DataBuffer( 1209): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@424c0038)
E/DataBuffer( 1209): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@424c22a0)
E/DataBuffer( 1209): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@423f6210)
E/DataBuffer( 1209): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4241abc0)
E/DataBuffer( 1209): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@423cda48)
E/DataBuffer( 1209): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@424af8e0)
E/DataBuffer( 1209): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@424967c8)
E/DataBuffer( 1209): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@426d0f48)
E/DataBuffer( 1209): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4248d898)
E/DataBuffer( 1209): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@426852c0)
W/ContextImpl( 4043): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/Launcher( 1300): Deferring update until onResume
I/Keyboard.Facilitator.MainLanguageModelLoader( 1192): run()
D/PackageBroadcastService( 1657): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/dalvikvm( 3365): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3365): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 3365): VFY: replacing opcode 0x6e at 0x0013
D/AccountUtils( 1657): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1657): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1657): Module APK com.google.android.play.games already loaded
D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1019): removePackageParticipantsLocked: uid=10144 #1
I/LocationSettingsChecker( 1657): Removing dialog suppression flag for package com.test.thalitest
I/Keyboard.Facilitator.MainLanguageModelLoader( 1192): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_GB/main%00003aen_gb (offset=0, length=3633960) with up to date LoudsLmContentVersion = 20150512
E/NetworkScheduler.SchedulerReceiver( 2067): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 2067): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1192): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1192): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1192): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1192): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1192): run() : Loaded File = UserHistory.en_GB.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1192): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1192): run() : Missing File = Personal.en_GB.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1192): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1192): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1192): run()
I/StatsUtilsManager( 1192): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1192): shouldRecordStats() = Too Soon
V/AlarmManager( 1019): sending alarm Alarm{42954ae8 type 2 android}
D/ChimeraCfgMgr( 1657): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1657): Module APK com.google.android.play.games already loaded
I/ActivityManager( 1019): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4063 uid=10058 gids={50058}
D/gH_CompatibleDatabase( 1657): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1657): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1657): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1657): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1657): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1657): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1657): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/InternalIcingCorporaPro( 2249): UpdateCorporaTask done [took 179 ms] updated apps [took 179 ms] 
I/Icing   ( 1657): doRemovePackageData com.test.thalitest
D/Documents( 4063): Loading roots for com.android.providers.downloads.documents
D/gH_CompatibleDatabase( 1657): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1657): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1657): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1657): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1657): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1657): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager( 1019): Killing 3700:com.google.android.partnersetup/u0a25 (adj 15): empty #9
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
D/ConnectivityService( 1019): Done.
D/ConnectivityService( 1019): Setting timer for 720seconds
D/Documents( 4063): Loading roots for com.android.externalstorage.documents
I/ActivityManager( 1019): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4087 uid=10020 gids={50020, 1028, 1015, 1023}
I/ActivityManager( 1019): Killing 3757:android.process.media/u0a18 (adj 15): empty #9
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/dalvikvm( 1019): GC_EXPLICIT freed 584K, 66% free 18485K/53296K, paused 20ms+14ms, total 294ms
D/ExternalStorage( 4087): After updating volumes, found 1 active roots
D/Documents( 4063): Updating roots due to change at content://com.android.externalstorage.documents/root
D/Documents( 4063): Loading roots for com.android.providers.media.documents
I/ActivityManager( 1019): Start proc android.process.media for content provider com.android.providers.media/.MediaDocumentsProvider: pid=4100 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
I/ActivityManager( 1019): Killing 3348:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1250): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/dalvikvm(  278): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 2ms+3ms, total 20ms
D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 17ms
D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 17ms
D/AndroidRuntime( 4012): Shutting down VM
D/dalvikvm( 4012): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
D/dalvikvm( 4100): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x422e7ec8, skipping init
I/openssl ( 4100): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4100): Crypto mode 0 already enabled
D/Documents( 4063): Loading roots for com.google.android.apps.docs.storage
D/Documents( 4063): Update found 7 roots in 257ms
D/Documents( 4063): Used cached roots for com.android.providers.downloads.documents
D/Documents( 4063): Loading roots for com.android.externalstorage.documents
D/Documents( 4063): Used cached roots for com.android.providers.media.documents
D/Documents( 4063): Used cached roots for com.google.android.apps.docs.storage
D/Documents( 4063): Update found 7 roots in 6ms

```
