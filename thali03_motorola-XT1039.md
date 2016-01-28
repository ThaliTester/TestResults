#### Test 573480789efee08_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
,V/AlarmManager( 1021): sending alarm Alarm{44003570 type 3 android}
--------- beginning of /dev/log/main
D/AndroidRuntime( 3768): 
D/AndroidRuntime( 3768): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3768): CheckJNI is OFF
D/dalvikvm( 3768): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3768): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3768): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3768): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3768): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3768): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3768): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3768): failed to load memtrack module: -2
D/AndroidRuntime( 3768): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1021): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 3768
W/WindowManager( 1021): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1021): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3784 uid=10143 gids={50143, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 3768): Shutting down VM
D/dalvikvm( 3768): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+1ms, total 2ms
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 3784): Binding Chromium to main looper Looper (main, tid 1) {41f38c10}
I/LibraryLoader( 3784): Expected native library version number "",actual native library version number ""
I/chromium( 3784): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3784): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1021): Message: 20
D/BluetoothManagerService( 1021): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43fb2f30:true
D/BluetoothAdapter( 3784): 1106564224: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 3784): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 3784): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 3784): Build Date: 03/07/14 Fri
I/Adreno-EGL( 3784): Local Branch: 
I/Adreno-EGL( 3784): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 3784): Local Patches: NONE
I/Adreno-EGL( 3784): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 3784): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 3784): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 3784): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 3784): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 3784): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 3784): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 3784): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 3784): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 3784): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 3784): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 3784): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 3784): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 3784): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 3784): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 3784): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 3784): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 3784): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 3784): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 3784): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 3784): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 3784): Enabling debug mode 0
,W/AwContents( 3784): nativeOnDraw failed; clearing to background color.
,I/Keyboard.Facilitator( 1197): onFinishInput()
,W/AwContents( 3784): nativeOnDraw failed; clearing to background color.
,I/LaunchCheckinHandler( 1021): Displayed com.test.thalitest/.MainActivity,cp,ca,449
I/ActivityManager( 1021): Displayed com.test.thalitest/.MainActivity: +423ms (total +450ms)
W/IInputConnectionWrapper( 3784): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 3784): Set native->JS mode to OnlineEventsBridgeMode
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,D/dalvikvm( 3784): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f3d320
,D/dalvikvm( 3784): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f3d320
,D/jxcore_app_log( 3784): JniHelper::setJavaVM(0x41589fa8), pthread_self() = 1614525496
I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/chromium( 3784): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/dalvikvm( 3784): GC_CONCURRENT freed 2716K, 16% free 14473K/17224K, paused 2ms+3ms, total 44ms
,D/dalvikvm( 3784): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/dalvikvm( 3784): WAIT_FOR_CONCURRENT_GC blocked 32ms
,D/dalvikvm( 3784): GC_FOR_ALLOC freed 442K, 14% free 14918K/17224K, paused 27ms, total 28ms
,I/dalvikvm-heap( 3784): Grow heap (frag case) to 16.662MB for 63974-byte allocation
,D/dalvikvm( 3784): GC_FOR_ALLOC freed 144K, 14% free 14921K/17288K, paused 26ms, total 27ms
,I/dalvikvm-heap( 3784): Grow heap (frag case) to 16.695MB for 95956-byte allocation
,D/dalvikvm( 3784): GC_FOR_ALLOC freed 180K, 14% free 14955K/17384K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3784): Grow heap (frag case) to 16.774MB for 143930-byte allocation
,D/dalvikvm( 3784): GC_FOR_ALLOC freed 254K, 15% free 15003K/17528K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3784): Grow heap (frag case) to 16.889MB for 215890-byte allocation
,D/dalvikvm( 3784): GC_FOR_ALLOC freed 367K, 16% free 15076K/17740K, paused 26ms, total 26ms
,I/dalvikvm-heap( 3784): Grow heap (frag case) to 17.064MB for 323830-byte allocation
,D/dalvikvm( 3784): GC_FOR_ALLOC freed 568K, 16% free 15197K/18060K, paused 26ms, total 27ms
,D/dalvikvm( 3784): GC_FOR_ALLOC freed 864K, 15% free 15373K/18060K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3784): Grow heap (frag case) to 17.740MB for 728606-byte allocation
,D/dalvikvm( 3784): GC_FOR_ALLOC freed 1283K, 17% free 15629K/18772K, paused 28ms, total 29ms
,I/dalvikvm-heap( 3784): Grow heap (frag case) to 18.337MB for 1092904-byte allocation
,D/dalvikvm( 3784): GC_CONCURRENT freed 1814K, 20% free 16017K/19840K, paused 3ms+4ms, total 38ms
,D/dalvikvm( 3784): GC_FOR_ALLOC freed 250K, 20% free 15939K/19840K, paused 27ms, total 27ms
,I/dalvikvm-heap( 3784): Grow heap (frag case) to 19.161MB for 1639352-byte allocation
,D/dalvikvm( 3784): GC_CONCURRENT freed 1819K, 23% free 16552K/21444K, paused 1ms+4ms, total 42ms
,D/dalvikvm( 3784): GC_FOR_ALLOC freed 1077K, 23% free 16525K/21444K, paused 28ms, total 29ms
,I/dalvikvm-heap( 3784): Grow heap (frag case) to 20.515MB for 2459024-byte allocation
,D/dalvikvm( 3784): GC_CONCURRENT freed 360K, 21% free 18960K/23848K, paused 5ms+4ms, total 54ms
,D/dalvikvm( 3784): GC_FOR_ALLOC freed 4165K, 27% free 17558K/23848K, paused 36ms, total 37ms
,I/dalvikvm-heap( 3784): Grow heap (frag case) to 22.696MB for 3688532-byte allocation
,D/dalvikvm( 3784): GC_CONCURRENT freed 239K, 24% free 20976K/27452K, paused 4ms+4ms, total 44ms
,D/dalvikvm( 3784): GC_FOR_ALLOC freed 4514K, 32% free 18689K/27452K, paused 34ms, total 35ms
,W/jxcore-log( 3784): Initializing JXcore engine
,W/jxcore-log( 3784): JXcore engine is ready
,D/dalvikvm( 3784): GC_CONCURRENT freed 446K, 22% free 21472K/27452K, paused 3ms+2ms, total 32ms
,D/dalvikvm( 3784): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 3784): WAIT_FOR_CONCURRENT_GC blocked 26ms
,W/jxcore-log( 3784): Starting JXcore engine
,W/jxcore-log( 3784): Platform android
W/jxcore-log( 3784): 
,W/jxcore-log( 3784): Process ARCH arm
W/jxcore-log( 3784): 
,I/jxcore-log( 3784): JXcore Cordova bridge is ready!
I/jxcore-log( 3784): 
,W/jxcore-log( 3784): JXcore engine is started
,E/jxcore  ( 3784): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 3784): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 3784): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager( 1021): Killing 3547:com.android.defcontainer/u0a13 (adj 15): empty #9
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1584): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1584): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1584): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1584): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1584): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1584): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1584): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1584): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/Keyboard.Facilitator( 1197): onFinishInput()
,W/IInputConnectionWrapper( 3784): showStatusIcon on inactive InputConnection
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/GLSActivity( 1331): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1331): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1021): sending alarm Alarm{440010f8 type 3 android}
,I/Keyboard.Facilitator.LanguageModelFlusher( 1197): run()
,I/Keyboard.Facilitator( 1197): flushDynamicLanguageModels()
,D/dalvikvm( 1021): GC_EXPLICIT freed 24671K, 66% free 18470K/53336K, paused 4ms+11ms, total 164ms
,I/ConfigService( 1210): onCreate
,D/dalvikvm( 1210): GC_EXPLICIT freed 1142K, 36% free 11113K/17224K, paused 3ms+6ms, total 36ms
,E/DataBuffer( 1210): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4209fd58)
,E/DataBuffer( 1210): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4211b000)
E/DataBuffer( 1210): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@422dcaa8)
,E/DataBuffer( 1210): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42196698)
,E/DataBuffer( 1210): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@420661a0)
,I/ConfigService( 1210): onDestroy
,V/AlarmManager( 1021): sending alarm Alarm{44005d20 type 2 com.google.android.gms}
,D/ConnectivityService( 1021): handleInetConditionChange: no active default network - ignore
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  276): NetlinkHandler, power_supply subsys
I/MDMCTBK (  276): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  276): checkDefaultInst, current pid is = 276
I/MDMCTBK (  276): checkDefaultInst, pid match
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  276): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  276): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1021): sending alarm Alarm{43fd5160 type 3 android}
,I/MMApiBackOffService( 1584): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1584): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1584): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1584): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1584): doRequest(): polling manager says we're not connected, returning with an error: 
,D/MMApiWebService( 1584): doRequest(): polling manager says we're not connected, returning with an error: devices.json
E/MMApiProvisionService( 1584): ProvisionWS.Response: Missing mandatory message data in response from DM server...
I/MMApiWebService( 1584): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
E/MMApiProvisionService( 1584): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1584): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1584): MMApiWebService told us not to continue at the moment with this request: 
,I/MMApiWebService( 1584): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1584): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1584): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
I/MMApiWebService( 1584): MMApiWebService told us not to continue at the moment with this request: devices.json
D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1584): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1584): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1584): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1584): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1021): sending alarm Alarm{445b53c0 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{440eb758 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{43fe5378 type 3 android}
,V/GLSActivity( 1331): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1331): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1021): sending alarm Alarm{43fc91e8 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{43f2f510 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{4462dee8 type 2 com.google.android.gms}
,D/ConnectivityService( 1021): handleInetConditionChange: no active default network - ignore
,V/AlarmManager( 1021): sending alarm Alarm{43eca298 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{43ec1a50 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{43ccb1c8 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{440238d0 type 2 android}
,D/ConnectivityService( 1021): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1021): sending alarm Alarm{44022d50 type 0 com.google.android.gms}
,D/ConnectivityService( 1021): Done.
,D/ConnectivityService( 1021): Setting timer for 720seconds
,I/EventLogService( 1699): Aggregate from 1453980601080 (log), 1453980601080 (data)
,V/GLSActivity( 1331): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1331): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1021): sending alarm Alarm{42e4c790 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{424c8f30 type 3 android}
,I/MMApiBackOffService( 1584): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 1584): MMApiBackOffService told us it's okay to retry the waiting requests: 3
,D/MMApiWebService( 1584): doRequest() with req : MMApiWSRequest(/v1/dp/devices.json)
,D/MMApiWebService( 1584): doRequest() with req : MMApiWSRequest(v1/ns/list/messages)
,D/MMApiWebService( 1584): doRequest(): polling manager says we're not connected, returning with an error: devices.json
,D/MMApiWebService( 1584): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 1584): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,E/MMApiProvisionService( 1584): ProvisionWS.Response: Missing mandatory message data in response from DM server...
,E/MMApiProvisionService( 1584): ProvisionWS.Response.setError: error RadioDownError
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1584): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 1584): MMApiWebService told us not to continue at the moment with this request: 
I/MMApiWebService( 1584): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: devices.json
D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 1584): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1584): MMApiWebService told us not to continue at the moment with this request: devices.json
D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiWebService( 1584): doRequest() with req : MMApiWSRequest(v1/us/devices/check)
,D/MMApiWebService( 1584): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 1584): _inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 1584): connectStatus(): app: MMAPIWebServiceRequest already backing off for interval: 600000
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 1584): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 1584): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager( 1021): sending alarm Alarm{424a5a20 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{420eed30 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{427c8ed0 type 3 android}
,V/GLSActivity( 1331): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1331): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1021): sending alarm Alarm{424eacf0 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{4277e7e0 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{42201580 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{427b6470 type 3 android}
,V/AlarmManager( 1021): sending alarm Alarm{42249328 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 3918): 
D/AndroidRuntime( 3918): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3918): CheckJNI is OFF
D/dalvikvm( 3918): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3918): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3918): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3918): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3918): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3918): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 3918): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 3918): failed to load memtrack module: -2
D/AndroidRuntime( 3918): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1021): Force stopping com.test.thalitest appid=10143 user=-1: uninstall pkg
I/ActivityManager( 1021): Killing 3784:com.test.thalitest/u0a143 (adj 9): stop com.test.thalitest
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1021): Force stopping com.test.thalitest appid=10143 user=0: pkg removed
D/dalvikvm( 2186): GC_EXPLICIT freed 4848K, 45% free 9605K/17224K, paused 2ms+5ms, total 37ms
I/InputReader( 1021): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1197): resetDictionaries() : en_GB
W/GeofencerStateMachine( 1210): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator.DecoderInitializer( 1197): run()
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "sms"
I/Decoder ( 1197): createOrResetDecoder
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "smsto"
D/VoicemailCleanupService( 1178): Cleaning up data for package: com.test.thalitest
D/dalvikvm( 1296): GC_EXPLICIT freed 3152K, 33% free 11597K/17224K, paused 2ms+5ms, total 119ms
D/dalvikvm( 2216): GC_EXPLICIT freed 3996K, 42% free 10103K/17224K, paused 2ms+7ms, total 151ms
I/Launcher( 1296): Deferring update until onResume
D/dalvikvm( 1699): GC_EXPLICIT freed 1602K, 32% free 11847K/17224K, paused 15ms+7ms, total 170ms
D/dalvikvm( 1021): GC_EXPLICIT freed 971K, 66% free 18407K/53336K, paused 5ms+22ms, total 127ms
I/ConfigService( 1210): onCreate
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mms"
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "mmsto"
I/Launcher( 1296): Deferring update until onResume
I/PackageManager( 1021): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1021):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1021):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1021):   Scheme: "sms"
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
I/InternalIcingCorporaPro( 2216): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager( 1021): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3950 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
D/BackupManagerService( 1021): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1021): removePackageParticipantsLocked: uid=10143 #1
I/Keyboard.Facilitator.MainLanguageModelLoader( 1197): run()
W/ContextImpl( 3950): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/dalvikvm( 3224): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3224): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 3224): VFY: replacing opcode 0x6e at 0x0013
I/Keyboard.Facilitator.MainLanguageModelLoader( 1197): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_GB/main%00003aen_gb (offset=0, length=3633960) with up to date LoudsLmContentVersion = 20150512
D/PackageBroadcastService( 1699): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1699): Clearing selected account for com.test.thalitest
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1197): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1197): run() : Loading LM = contacts
D/ChimeraCfgMgr( 1699): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1699): Module APK com.google.android.play.games already loaded
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
I/LocationSettingsChecker( 1699): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1699): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1699): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1331): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1331): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager( 1021): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3975 uid=10058 gids={50058}
D/gH_CompatibleDatabase( 1699): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1699): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1699): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1699): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1699): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1699): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
I/Icing   ( 1699): doRemovePackageData com.test.thalitest
I/InternalIcingCorporaPro( 2216): UpdateCorporaTask done [took 176 ms] updated apps [took 176 ms] 
D/gH_CompatibleDatabase( 1699): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1699): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1699): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1699): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1699): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1699): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1699): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/dalvikvm( 1021): GC_EXPLICIT freed 716K, 66% free 18443K/53336K, paused 8ms+14ms, total 256ms
D/Documents( 3975): Loading roots for com.android.providers.downloads.documents
I/ActivityManager( 1021): Killing 3575:com.google.android.partnersetup/u0a25 (adj 15): empty #9
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/Documents( 3975): Loading roots for com.android.externalstorage.documents
I/ActivityManager( 1021): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3994 uid=10020 gids={50020, 1028, 1015, 1023}
I/ActivityManager( 1021): Killing 3644:android.process.media/u0a18 (adj 15): empty #9
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/ExternalStorage( 3994): After updating volumes, found 1 active roots
D/Documents( 3975): Updating roots due to change at content://com.android.externalstorage.documents/root
D/Documents( 3975): Loading roots for com.android.providers.media.documents
I/ActivityManager( 1021): Start proc android.process.media for content provider com.android.providers.media/.MediaDocumentsProvider: pid=4006 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
I/ActivityManager( 1021): Killing 3598:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1252): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/AndroidRuntime( 3918): Shutting down VM
D/dalvikvm( 3918): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+1ms, total 2ms
D/dalvikvm( 4006): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41f44f70, skipping init
I/openssl ( 4006): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4006): Crypto mode 0 already enabled
D/Documents( 3975): Loading roots for com.google.android.apps.docs.storage
D/Documents( 3975): Update found 7 roots in 185ms
D/Documents( 3975): Used cached roots for com.android.providers.downloads.documents
D/Documents( 3975): Loading roots for com.android.externalstorage.documents
D/Documents( 3975): Used cached roots for com.android.providers.media.documents
D/Documents( 3975): Used cached roots for com.google.android.apps.docs.storage
D/Documents( 3975): Update found 7 roots in 6ms

```
