#### Test 5065027865f659b_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
,V/AlarmManager( 1019): sending alarm Alarm{43d7ad40 type 3 android}
--------- beginning of /dev/log/main
D/AndroidRuntime( 3477): 
D/AndroidRuntime( 3477): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3477): CheckJNI is OFF
D/dalvikvm( 3477): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3477): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3477): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3477): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3477): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3477): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3477): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3477): failed to load memtrack module: -2
D/AndroidRuntime( 3477): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3477
W/WindowManager( 1019): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3493 uid=10449 gids={50449, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3477): Shutting down VM
D/dalvikvm( 3477): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 2ms
W/ContextImpl( 1241): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1241): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3493): Binding Chromium to main looper Looper (main, tid 1) {41f59ab0}
I/LibraryLoader( 3493): Expected native library version number "",actual native library version number ""
I/chromium( 3493): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3493): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43cff950:true
D/BluetoothAdapter( 3493): 1106698248: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3493): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3493): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3493): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3493): Local Branch: 
I/Adreno-EGL( 3493): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3493): Local Patches: NONE
I/Adreno-EGL( 3493): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 3493): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 3493): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 3493): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3493): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3493): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3493): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 3493): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 3493): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3493): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3493): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3493): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3493): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 3493): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3493): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3493): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 3493): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3493): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3493): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3493): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3493): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3493): Enabling debug mode 0
,W/AwContents( 3493): nativeOnDraw failed; clearing to background color.
,I/LaunchCheckinHandler( 1019): Displayed com.test.thalitest/.MainActivity,cp,ca,384
I/ActivityManager( 1019): Displayed com.test.thalitest/.MainActivity: +358ms (total +384ms)
W/AwContents( 3493): nativeOnDraw failed; clearing to background color.
W/IInputConnectionWrapper( 3493): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 3493): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 3493): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f5dea8
,D/dalvikvm( 3493): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f5dea8
D/jxcore_app_log( 3493): JniHelper::setJavaVM(0x415a6fa8), pthread_self() = 1614858672
,D/JX-Cordova( 3493): jxcore cordova android initializing
I/dalvikvm( 3493): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 3493): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 3493): VFY: replacing opcode 0x6e at 0x0045
,D/dalvikvm( 3493): GC_CONCURRENT freed 2813K, 17% free 14376K/17224K, paused 2ms+2ms, total 57ms
D/dalvikvm( 3493): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 3493): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 3493): GC_FOR_ALLOC freed 135K, 17% free 14367K/17224K, paused 25ms, total 25ms
,D/dalvikvm( 3493): GC_FOR_ALLOC freed 304K, 17% free 14431K/17224K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3493): Grow heap (frag case) to 16.262MB for 143930-byte allocation
,D/dalvikvm( 3493): GC_FOR_ALLOC freed 266K, 17% free 14468K/17368K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3493): Grow heap (frag case) to 16.367MB for 215890-byte allocation
,D/dalvikvm( 3493): GC_FOR_ALLOC freed 368K, 18% free 14541K/17580K, paused 24ms, total 24ms
,I/dalvikvm-heap( 3493): Grow heap (frag case) to 16.541MB for 323830-byte allocation
,D/dalvikvm( 3493): GC_FOR_ALLOC freed 567K, 19% free 14662K/17900K, paused 25ms, total 25ms
,I/dalvikvm-heap( 3493): Grow heap (frag case) to 16.815MB for 485740-byte allocation
,W/PluginManager( 3493): THREAD WARNING: exec() call to JXcore.isReady blocked the main thread for 26ms. Plugin should use CordovaInterface.getThreadPool().
,D/dalvikvm( 3493): GC_FOR_ALLOC freed 866K, 20% free 14837K/18376K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3493): Grow heap (frag case) to 17.217MB for 728606-byte allocation
,D/dalvikvm( 3493): GC_FOR_ALLOC freed 1282K, 21% free 15094K/19088K, paused 26ms, total 26ms
,D/dalvikvm( 3493): GC_CONCURRENT freed 1677K, 19% free 15465K/19088K, paused 2ms+3ms, total 38ms
D/dalvikvm( 3493): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 3493): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/dalvikvm( 3493): GC_FOR_ALLOC freed 370K, 20% free 15420K/19088K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3493): Grow heap (frag case) to 18.655MB for 1639352-byte allocation
,D/dalvikvm( 3493): GC_CONCURRENT freed 1808K, 23% free 16006K/20692K, paused 1ms+4ms, total 55ms
,D/dalvikvm( 3493): GC_FOR_ALLOC freed 1260K, 23% free 16055K/20692K, paused 29ms, total 29ms
,I/dalvikvm-heap( 3493): Grow heap (frag case) to 20.057MB for 2459024-byte allocation
,D/dalvikvm( 3493): GC_CONCURRENT freed 1802K, 28% free 16771K/23096K, paused 1ms+4ms, total 35ms
,D/dalvikvm( 3493): GC_CONCURRENT freed 2367K, 27% free 16995K/23096K, paused 2ms+6ms, total 49ms
,D/dalvikvm( 3493): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 3493): GC_FOR_ALLOC freed 625K, 28% free 16851K/23096K, paused 28ms, total 28ms
,I/dalvikvm-heap( 3493): Grow heap (frag case) to 22.006MB for 3688532-byte allocation
,D/dalvikvm( 3493): GC_CONCURRENT freed 350K, 24% free 20348K/26700K, paused 4ms+3ms, total 55ms
,D/dalvikvm( 3493): GC_FOR_ALLOC freed 3013K, 33% free 17985K/26700K, paused 27ms, total 27ms
,W/jxcore-log( 3493): Initializing JXcore engine
,W/jxcore-log( 3493): JXcore engine is ready
,D/dalvikvm( 3493): GC_CONCURRENT freed 366K, 23% free 20595K/26700K, paused 2ms+2ms, total 33ms
,D/dalvikvm( 3493): WAIT_FOR_CONCURRENT_GC blocked 29ms
,W/jxcore-log( 3493): Starting JXcore engine
,W/jxcore-log( 3493): Platform android
W/jxcore-log( 3493): 
,W/jxcore-log( 3493): Process ARCH arm
W/jxcore-log( 3493): 
,I/jxcore-log( 3493): JXcore Cordova bridge is ready!
I/jxcore-log( 3493): 
,W/jxcore-log( 3493): JXcore engine is started
,I/chromium( 3493): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 3493): Error!: missing ) after argument list
E/jxcore  ( 3493): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 3493): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager( 1019): Killing 3233:com.android.calendar/u0a7 (adj 15): empty #9
W/ContextImpl( 1241): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1241): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1241): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1538): [info] > Updatetime from metadata: 10
,D/Checkin ( 1538): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1538): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1538): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1538): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1538): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1538): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,W/IInputConnectionWrapper( 3493): showStatusIcon on inactive InputConnection
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{43d71510 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43cb23e8 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,I/MMApiBackOffService( 1538): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1538): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1538): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1538): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1538): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1538): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1538): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/MMApiWebService( 1538): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,E/MMApiProvisionService( 1538): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,D/Checkin ( 1538): publish the event [tag = MOT_CCE event name = LOG]
,E/MMApiProvisionService( 1538): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiBackOffService( 1538): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1538): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1538): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1538): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
,D/Checkin ( 1538): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1538): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1538): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1538): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1538): MMApiWebService told us not to continue at the moment with this request: devices.json
,D/Checkin ( 1538): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1538): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/MMApiWebService( 1538): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1538): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1538): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1538): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1538): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1538): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1538): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{43ca9010 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43c95190 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4285b148 type 2 com.motorola.ccc.cce}
I/PollingManager( 1538): alarm fired!
D/Checkin ( 1538): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{43c8cc70 type 3 android}
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  272): write error (Broken pipe)
,V/AlarmManager( 1019): sending alarm Alarm{43c1ef90 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43252b50 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4324e018 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42838b98 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
,V/AlarmManager( 1019): sending alarm Alarm{43247208 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43216b58 type 3 android}
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  272): write error (Broken pipe)
,V/AlarmManager( 1019): sending alarm Alarm{43211e58 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{431fa9d8 type 3 android}
,I/MMApiBackOffService( 1538): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1538): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1538): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1538): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1538): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1538): ProvisionWS.Response: Missing mandatory message data in response from DM server...
D/MMApiWebService( 1538): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
E/MMApiProvisionService( 1538): ProvisionWS.Response.setError: error RadioDownError
,I/MMApiWebService( 1538): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1538): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1538): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiBackOffService( 1538): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 1538): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1538): MMApiWebService told us not to continue at the moment with this request: devices.json
,I/MMApiWebService( 1538): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1538): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1538): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
D/Checkin ( 1538): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1538): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1538): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1538): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1538): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/MMApiWebService( 1538): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1538): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1538): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1538): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1538): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1538): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1538): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1019): sending alarm Alarm{431f5e88 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{431ed3b0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{431e8948 type 3 android}
,D/dalvikvm( 1328): GC_EXPLICIT freed 1003K, 39% free 10516K/17224K, paused 3ms+5ms, total 38ms
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1019): sending alarm Alarm{431e1e88 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{431c4100 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{431ba9d8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{431b1680 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{431a8218 type 3 android}
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/SocketClient(  272): write error (Broken pipe)
,V/AlarmManager( 1019): sending alarm Alarm{431a02c8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43183ab0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4317b368 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{431760b0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4316e820 type 3 android}
,I/ProcessStatsService( 1019): Prepared write state in 43ms
,I/ProcessStatsService( 1019): Prepared write state in 20ms
,I/ProcessStatsService( 1019): Pruning old procstats: /data/system/procstats/state-2015-12-07-22-16-49.bin
,V/AlarmManager( 1019): sending alarm Alarm{4321bf88 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1019): sending alarm Alarm{4285b220 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42911730 type 2 com.motorola.ccc.cce}
,V/AlarmManager( 1019): sending alarm Alarm{42911780 type 3 com.google.android.gms}
,V/AlarmManager( 1019): sending alarm Alarm{429117d0 type 3 com.google.android.gms}
,V/AlarmManager( 1019): sending alarm Alarm{42926a40 type 0 com.google.android.gms}
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
,D/CCE     ( 1538): Registering with Alarm Manager to restart CCE
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1328): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1376): Aggregate from 1449597363490 (log), 1449597363490 (data)
,I/dalvikvm( 1328): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 1328): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1328): VFY: replacing opcode 0x6e at 0x0033
,W/SocketClient(  272): write error (Broken pipe)
,D/dalvikvm( 1019): GC_EXPLICIT freed 22979K, 65% free 17786K/50124K, paused 4ms+11ms, total 142ms
,V/AlarmManager( 1019): sending alarm Alarm{4474d520 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{428d76d0 type 3 android}
,I/ActivityManager( 1019): Killing 3372:com.google.android.partnersetup/u0a25 (adj 15): empty for 1817s
,I/ActivityManager( 1019): Killing 3010:android.process.acore/u0a10 (adj 15): empty for 1817s
,I/ActivityManager( 1019): Killing 3345:com.android.defcontainer/u0a13 (adj 15): empty for 1817s
,W/ContextImpl( 1241): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1241): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1241): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/AlarmManager( 1019): sending alarm Alarm{428ce238 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4285cd60 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4284fc48 type 3 android}
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 3637): 
D/AndroidRuntime( 3637): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3637): CheckJNI is OFF
D/dalvikvm( 3637): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3637): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3637): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3637): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3637): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3637): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3637): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3637): failed to load memtrack module: -2
D/AndroidRuntime( 3637): Calling main entry com.android.commands.pm.Pm
I/dalvikvm( 1019): Jit: resizing JitTable from 8192 to 16384
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10449 user=-1: uninstall pkg
I/ActivityManager( 1019): Killing 3493:com.test.thalitest/u0a449 (adj 13): stop com.test.thalitest
W/ContextImpl( 1241): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
W/PackageSettings( 1019): Skipping PackageSetting{42215e00 com.example.hello/10442} due to missing metadata
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10449 user=0: pkg removed
D/dalvikvm( 2138): GC_EXPLICIT freed 4774K, 45% free 9604K/17224K, paused 3ms+5ms, total 54ms
D/dalvikvm( 2170): GC_EXPLICIT freed 2403K, 44% free 9770K/17224K, paused 3ms+30ms, total 73ms
I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager( 1019): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=3660 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
D/dalvikvm(  277): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 1ms+3ms, total 22ms
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 24ms
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
I/LatinIME:LogUtils( 1184): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1184): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
W/GeofencerStateMachine( 1200): Ignoring removeGeofence because network location is disabled.
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 20ms
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
D/dalvikvm( 1299): GC_EXPLICIT freed 2792K, 33% free 11591K/17224K, paused 2ms+4ms, total 163ms
I/Launcher( 1299): Deferring update until onResume
D/dalvikvm( 1019): GC_EXPLICIT freed 905K, 65% free 17638K/50124K, paused 3ms+11ms, total 178ms
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
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
I/Launcher( 1299): Deferring update until onResume
I/LatinIME:LogUtils( 1184): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449600372
I/LatinIME:LogUtils( 1184): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449600372
D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1019): removePackageParticipantsLocked: uid=10449 #1
D/VoicemailCleanupService( 3660): Cleaning up data for package: com.test.thalitest
I/InternalIcingCorporaPro( 2170): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager( 1019): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3689 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
W/ContextImpl( 3689): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
D/PackageBroadcastService( 1376): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1376): Clearing selected account for com.test.thalitest
I/dalvikvm( 3085): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3085): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 3085): VFY: replacing opcode 0x6e at 0x0013
D/ChimeraCfgMgr( 1376): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1376): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1376): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1376): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1376): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1328): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1328): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 1376): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1376): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
I/ActivityManager( 1019): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3708 uid=10058 gids={50058}
D/gH_MetricsDatabase( 1376): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1376): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1376): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1376): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1376): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1376): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1376): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
I/PeopleContactsSync( 1376): CP2 sync disabled
D/gH_CompatibleDatabase( 1376): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1376): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1376): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1376): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/dalvikvm( 1019): GC_EXPLICIT freed 469K, 65% free 17739K/50124K, paused 10ms+15ms, total 251ms
I/Icing   ( 1376): doRemovePackageData com.test.thalitest
D/dalvikvm( 1376): GC_CONCURRENT freed 1679K, 33% free 11676K/17224K, paused 3ms+7ms, total 49ms
D/Documents( 3708): Loading roots for com.android.providers.downloads.documents
I/InternalIcingCorporaPro( 2170): UpdateCorporaTask done [took 168 ms] updated apps [took 168 ms] 
I/ActivityManager( 1019): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=3726 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
I/ContactLocale( 3660): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
D/AndroidRuntime( 3637): Shutting down VM
D/dalvikvm( 3637): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+1ms, total 2ms
D/dalvikvm( 3726): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f59730, skipping init
I/openssl ( 3726): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 3726): Crypto mode 0 already enabled
D/Documents( 3708): Loading roots for com.android.externalstorage.documents
I/ActivityManager( 1019): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3742 uid=10020 gids={50020, 1028, 1015, 1023}
I/ActivityManager( 1019): Killing 3660:android.process.acore/u0a10 (adj 15): empty #9
W/ContextImpl( 1241): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/ExternalStorage( 3742): After updating volumes, found 1 active roots
D/Documents( 3708): Updating roots due to change at content://com.android.externalstorage.documents/root
D/Documents( 3708): Loading roots for com.android.providers.media.documents
D/Documents( 3708): Loading roots for com.google.android.apps.docs.storage
D/Documents( 3708): Update found 7 roots in 185ms
D/Documents( 3708): Used cached roots for com.android.providers.downloads.documents
D/Documents( 3708): Loading roots for com.android.externalstorage.documents
D/Documents( 3708): Used cached roots for com.android.providers.media.documents
D/Documents( 3708): Used cached roots for com.google.android.apps.docs.storage
D/Documents( 3708): Update found 7 roots in 7ms

```
