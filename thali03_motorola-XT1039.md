#### Test 5065027873d6a28_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
,V/AlarmManager(  989): sending alarm Alarm{44640358 type 3 android}
--------- beginning of /dev/log/main
D/AndroidRuntime( 3481): 
D/AndroidRuntime( 3481): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3481): CheckJNI is OFF
D/dalvikvm( 3481): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3481): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3481): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3481): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3481): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3481): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3481): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3481): failed to load memtrack module: -2
D/AndroidRuntime( 3481): Calling main entry com.android.commands.am.Am
I/ActivityManager(  989): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3481
W/WindowManager(  989): Not okToDisplay, so not showing Starting Window
I/ActivityManager(  989): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3497 uid=10450 gids={50450, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3481): Shutting down VM
D/dalvikvm( 3481): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+0ms, total 4ms
D/dalvikvm(  278): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+3ms, total 23ms
W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 21ms
D/dalvikvm(  278): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 18ms
V/WebViewChromiumFactoryProvider( 3497): Binding Chromium to main looper Looper (main, tid 1) {427a9940}
I/LibraryLoader( 3497): Expected native library version number "",actual native library version number ""
I/chromium( 3497): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3497): Initializing chromium process, renderers=0
D/BluetoothManagerService(  989): Message: 20
D/BluetoothManagerService(  989): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44557600:true
D/BluetoothAdapter( 3497): 1115414352: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3497): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3497): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3497): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3497): Local Branch: 
I/Adreno-EGL( 3497): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3497): Local Patches: NONE
I/Adreno-EGL( 3497): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 3497): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 3497): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 3497): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3497): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3497): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3497): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 3497): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 3497): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3497): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3497): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3497): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3497): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3497): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3497): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3497): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3497): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 3497): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3497): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3497): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3497): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3497): Enabling debug mode 0
,W/AwContents( 3497): nativeOnDraw failed; clearing to background color.
,V/AlarmManager(  989): sending alarm Alarm{4463f6a0 type 3 android}
,I/LaunchCheckinHandler(  989): Displayed com.test.thalitest/.MainActivity,cp,ca,423
I/ActivityManager(  989): Displayed com.test.thalitest/.MainActivity: +388ms (total +424ms)
W/AwContents( 3497): nativeOnDraw failed; clearing to background color.
W/IInputConnectionWrapper( 3497): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 3497): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3497): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x427addf0
,D/dalvikvm( 3497): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x427addf0
,D/jxcore_app_log( 3497): JniHelper::setJavaVM(0x41ec2f78), pthread_self() = 1615283768
,D/JX-Cordova( 3497): jxcore cordova android initializing
,I/dalvikvm( 3497): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 3497): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 3497): VFY: replacing opcode 0x6e at 0x0045
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
I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,D/dalvikvm( 3497): GC_CONCURRENT freed 2795K, 17% free 14394K/17224K, paused 3ms+2ms, total 77ms
,D/dalvikvm( 3497): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 3497): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 3497): GC_FOR_ALLOC freed 157K, 17% free 14368K/17224K, paused 28ms, total 28ms
,D/dalvikvm( 3497): GC_FOR_ALLOC freed 305K, 17% free 14431K/17224K, paused 25ms, total 26ms
,I/dalvikvm-heap( 3497): Grow heap (frag case) to 16.262MB for 143930-byte allocation
,D/dalvikvm( 3497): GC_FOR_ALLOC freed 255K, 17% free 14479K/17368K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3497): Grow heap (frag case) to 16.377MB for 215890-byte allocation
,D/dalvikvm( 3497): GC_FOR_ALLOC freed 379K, 18% free 14541K/17580K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3497): Grow heap (frag case) to 16.541MB for 323830-byte allocation
,D/dalvikvm( 3497): GC_FOR_ALLOC freed 567K, 19% free 14662K/17900K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3497): Grow heap (frag case) to 16.814MB for 485740-byte allocation
,D/dalvikvm( 3497): GC_FOR_ALLOC freed 863K, 20% free 14837K/18376K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3497): Grow heap (frag case) to 17.217MB for 728606-byte allocation
,D/dalvikvm( 3497): GC_FOR_ALLOC freed 1282K, 21% free 15093K/19088K, paused 27ms, total 27ms
,D/dalvikvm( 3497): GC_CONCURRENT freed 1677K, 19% free 15463K/19088K, paused 1ms+3ms, total 33ms
,D/dalvikvm( 3497): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 3497): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 3497): GC_FOR_ALLOC freed 352K, 20% free 15431K/19088K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3497): Grow heap (frag case) to 18.666MB for 1639352-byte allocation
,D/dalvikvm( 3497): GC_CONCURRENT freed 1681K, 23% free 16018K/20692K, paused 2ms+3ms, total 43ms
,D/dalvikvm( 3497): GC_FOR_ALLOC freed 1382K, 23% free 16068K/20692K, paused 29ms, total 29ms
,I/dalvikvm-heap( 3497): Grow heap (frag case) to 20.069MB for 2459024-byte allocation
,D/dalvikvm( 3497): GC_CONCURRENT freed 1902K, 28% free 16737K/23096K, paused 5ms+4ms, total 50ms
,D/dalvikvm( 3497): GC_CONCURRENT freed 2325K, 27% free 16990K/23096K, paused 3ms+6ms, total 44ms
,D/dalvikvm( 3497): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 3497): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 3497): GC_FOR_ALLOC freed 537K, 27% free 16899K/23096K, paused 29ms, total 30ms
,I/dalvikvm-heap( 3497): Grow heap (frag case) to 22.052MB for 3688532-byte allocation
,D/dalvikvm( 3497): GC_CONCURRENT freed 265K, 24% free 20352K/26700K, paused 5ms+3ms, total 39ms
,D/dalvikvm( 3497): GC_FOR_ALLOC freed 3134K, 33% free 17995K/26700K, paused 27ms, total 27ms
,W/jxcore-log( 3497): Initializing JXcore engine
,W/jxcore-log( 3497): JXcore engine is ready
,D/dalvikvm( 3497): GC_CONCURRENT freed 377K, 23% free 20596K/26700K, paused 3ms+3ms, total 36ms
,D/dalvikvm( 3497): WAIT_FOR_CONCURRENT_GC blocked 30ms
,W/jxcore-log( 3497): Starting JXcore engine
,W/jxcore-log( 3497): Platform android
W/jxcore-log( 3497): 
,W/jxcore-log( 3497): Process ARCH arm
W/jxcore-log( 3497): 
,I/jxcore-log( 3497): JXcore Cordova bridge is ready!
I/jxcore-log( 3497): 
,W/jxcore-log( 3497): JXcore engine is started
,I/chromium( 3497): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 3497): Error!: missing ) after argument list
E/jxcore  ( 3497): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 3497): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager(  989): Killing 3261:com.android.calendar/u0a7 (adj 15): empty #9
W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1539): [info] > Updatetime from metadata: 10
,D/Checkin ( 1539): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1539): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1539): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1539): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1539): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1539): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,W/IInputConnectionWrapper( 3497): showStatusIcon on inactive InputConnection
,I/MDMCTBK (  274): NetlinkHandler, power_supply subsys
I/MDMCTBK (  274): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  274): checkDefaultInst, current pid is = 274
I/MDMCTBK (  274): checkDefaultInst, pid match
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  274): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  274): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  989): sending alarm Alarm{4462c438 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{44551320 type 3 android}
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  989): sending alarm Alarm{445451e0 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{44514c98 type 3 android}
,I/MMApiBackOffService( 1539): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1539): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1539): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1539): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1539): doRequest(): polling manager says we're not connected, returning with an error: 
,D/MMApiWebService( 1539): doRequest(): polling manager says we're not connected, returning with an error: devices.json
I/MMApiWebService( 1539): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,E/MMApiProvisionService( 1539): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1539): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1539): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1539): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1539): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1539): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1539): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,I/MMApiWebService( 1539): MMApiWebService told us not to continue at the moment with this request: devices.json
D/MMApiWebService( 1539): doRequest(): polling manager says we're not connected, returning with an error: 
D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1539): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1539): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1539): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager(  989): sending alarm Alarm{44508e78 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{444fffe0 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{444f7b68 type 3 android}
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  989): sending alarm Alarm{444f1d30 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{444bfb20 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{4317c170 type 2 android}
,D/ConnectivityService(  989): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  989): Done.
,D/ConnectivityService(  989): Setting timer for 720seconds
,V/AlarmManager(  989): sending alarm Alarm{444b45f0 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{4446c220 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{43aae4b0 type 3 android}
,D/dalvikvm( 1313): GC_EXPLICIT freed 1033K, 39% free 10573K/17224K, paused 3ms+6ms, total 38ms
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  989): sending alarm Alarm{43aa3f48 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{43a7e960 type 3 android}
,I/MMApiBackOffService( 1539): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1539): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1539): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1539): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1539): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,E/MMApiProvisionService( 1539): ProvisionWS.Response: Missing mandatory message data in response from DM server...
D/MMApiWebService( 1539): doRequest(): polling manager says we're not connected, returning with an error: 
E/MMApiProvisionService( 1539): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiWebService( 1539): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1539): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1539): MMApiWebService told us not to continue at the moment with this request: devices.json
I/MMApiWebService( 1539): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1539): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1539): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
I/MMApiWebService( 1539): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1539): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1539): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1539): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1539): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1539): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager(  989): sending alarm Alarm{43a77d30 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{43a6f068 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{43a6a2b8 type 3 android}
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  989): sending alarm Alarm{43a615b0 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{43a477a0 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{43a3e8f0 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{43a39c90 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{43a33b68 type 3 android}
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  989): sending alarm Alarm{43a2e188 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{43a14160 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{43a0f998 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{43a07c80 type 3 android}
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
,V/AlarmManager(  989): sending alarm Alarm{43a03928 type 3 android}
,I/ProcessStatsService(  989): Prepared write state in 43ms
,I/ProcessStatsService(  989): Prepared write state in 16ms
,I/ProcessStatsService(  989): Pruning old procstats: /data/system/procstats/state-2015-12-08-10-19-38.bin
,V/AlarmManager(  989): sending alarm Alarm{44473680 type 2 android}
,D/ConnectivityService(  989): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  989): sending alarm Alarm{43199200 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{43199718 type 2 com.motorola.ccc.cce}
,V/AlarmManager(  989): sending alarm Alarm{43199768 type 3 com.google.android.gms}
,V/AlarmManager(  989): sending alarm Alarm{431997b8 type 3 com.google.android.gms}
,V/AlarmManager(  989): sending alarm Alarm{43199808 type 0 com.google.android.gms}
,D/CCE     ( 1539): Registering with Alarm Manager to restart CCE
,D/ConnectivityService(  989): Done.
,D/ConnectivityService(  989): Setting timer for 720seconds
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1313): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1387): Aggregate from 1449625615346 (log), 1449625615346 (data)
,W/SocketClient(  272): write error (Broken pipe)
,D/dalvikvm(  989): GC_EXPLICIT freed 22970K, 65% free 17835K/50244K, paused 3ms+10ms, total 139ms
,V/AlarmManager(  989): sending alarm Alarm{44f2dc70 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{4312d3a0 type 3 android}
,I/ActivityManager(  989): Killing 3384:com.google.android.partnersetup/u0a25 (adj 15): empty for 1835s
,I/ActivityManager(  989): Killing 3032:android.process.acore/u0a10 (adj 15): empty for 1836s
,I/ActivityManager(  989): Killing 3357:com.android.defcontainer/u0a13 (adj 15): empty for 1836s
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/AlarmManager(  989): sending alarm Alarm{430ac508 type 3 android}
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 3636): 
D/AndroidRuntime( 3636): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3636): CheckJNI is OFF
D/dalvikvm( 3636): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3636): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3636): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3636): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3636): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3636): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3636): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3636): failed to load memtrack module: -2
D/AndroidRuntime( 3636): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  989): Force stopping com.test.thalitest appid=10450 user=-1: uninstall pkg
I/ActivityManager(  989): Killing 3497:com.test.thalitest/u0a450 (adj 13): stop com.test.thalitest
W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
W/PackageSettings(  989): Skipping PackageSetting{42a63e10 com.example.hello/10442} due to missing metadata
I/ActivityManager(  989): Force stopping com.test.thalitest appid=10450 user=0: pkg removed
I/InputReader(  989): Reconfiguring input devices.  changes=0x00000010
I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "sms"
I/ActivityManager(  989): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=3653 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "smsto"
I/LatinIME:LogUtils( 1183): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449628511
I/LatinIME:LogUtils( 1183): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
D/dalvikvm( 2122): GC_EXPLICIT freed 4786K, 45% free 9605K/17224K, paused 2ms+5ms, total 86ms
I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "mms"
I/LatinIME:LogUtils( 1183): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "mmsto"
I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "sms"
I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "smsto"
D/dalvikvm( 1285): GC_EXPLICIT freed 2792K, 33% free 11591K/17224K, paused 3ms+4ms, total 144ms
I/Launcher( 1285): Deferring update until onResume
D/dalvikvm( 2152): GC_EXPLICIT freed 3234K, 42% free 10060K/17224K, paused 3ms+6ms, total 158ms
I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "mms"
D/dalvikvm(  989): GC_EXPLICIT freed 1014K, 65% free 17689K/50244K, paused 4ms+13ms, total 146ms
D/dalvikvm( 1201): GC_EXPLICIT freed 1952K, 41% free 10257K/17224K, paused 11ms+6ms, total 85ms
E/DataBuffer( 1201): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4296d188)
I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "mmsto"
W/GeofencerStateMachine( 1201): Ignoring removeGeofence because network location is disabled.
I/LatinIME:LogUtils( 1183): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449628512
I/Launcher( 1285): Deferring update until onResume
D/VoicemailCleanupService( 3653): Cleaning up data for package: com.test.thalitest
I/InternalIcingCorporaPro( 2152): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  989): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3682 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
W/ContextImpl( 3682): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
D/BackupManagerService(  989): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  989): removePackageParticipantsLocked: uid=10450 #1
I/dalvikvm( 3119): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3119): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 3119): VFY: replacing opcode 0x6e at 0x0013
D/PackageBroadcastService( 1387): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1387): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1387): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1387): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1387): Removing dialog suppression flag for package com.test.thalitest
E/NetworkScheduler.SchedulerReceiver( 1313): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1313): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager(  989): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3701 uid=10058 gids={50058}
D/gH_CompatibleDatabase( 1387): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1387): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1387): 0 metrics were deleted when clearing package com.test.thalitest.
D/ChimeraCfgMgr( 1387): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1387): Module APK com.google.android.play.games already loaded
D/gH_CompatibleDatabase( 1387): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1387): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1387): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1387): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1387): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1387): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1387): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1387): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1387): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1387): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/PeopleContactsSync( 1387): CP2 sync disabled
I/InternalIcingCorporaPro( 2152): UpdateCorporaTask done [took 155 ms] updated apps [took 155 ms] 
I/Icing   ( 1387): doRemovePackageData com.test.thalitest
D/dalvikvm(  989): GC_EXPLICIT freed 376K, 65% free 17784K/50244K, paused 9ms+16ms, total 259ms
D/Documents( 3701): Loading roots for com.android.providers.downloads.documents
I/ActivityManager(  989): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=3719 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
I/ContactLocale( 3653): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
D/AndroidRuntime( 3636): Shutting down VM
D/dalvikvm( 3636): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
D/dalvikvm( 3719): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x427a95c8, skipping init
I/openssl ( 3719): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3719): Crypto mode 0 already enabled
D/Documents( 3701): Loading roots for com.android.externalstorage.documents
I/ActivityManager(  989): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3735 uid=10020 gids={50020, 1028, 1015, 1023}
I/ActivityManager(  989): Killing 3653:android.process.acore/u0a10 (adj 15): empty #9
W/ContextImpl( 1244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/ExternalStorage( 3735): After updating volumes, found 1 active roots
D/Documents( 3701): Updating roots due to change at content://com.android.externalstorage.documents/root
D/Documents( 3701): Loading roots for com.android.providers.media.documents
D/Documents( 3701): Loading roots for com.google.android.apps.docs.storage
D/Documents( 3701): Update found 7 roots in 184ms
D/Documents( 3701): Used cached roots for com.android.providers.downloads.documents
D/Documents( 3701): Loading roots for com.android.externalstorage.documents
D/Documents( 3701): Used cached roots for com.android.providers.media.documents
D/Documents( 3701): Used cached roots for com.google.android.apps.docs.storage
D/Documents( 3701): Update found 7 roots in 7ms

```
