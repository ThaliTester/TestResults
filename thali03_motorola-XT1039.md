#### Test 56449660311ec66_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 4642): 
D/AndroidRuntime( 4642): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4642): CheckJNI is OFF
D/dalvikvm( 4642): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4642): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4642): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4642): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4642): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4642): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4642): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4642): failed to load memtrack module: -2
D/AndroidRuntime( 4642): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager(  989): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4642
W/WindowManager(  989): Not okToDisplay, so not showing Starting Window
I/ActivityManager(  989): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4658 uid=10130 gids={50130, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4642): Shutting down VM
D/dalvikvm( 4642): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+1ms, total 2ms
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4658): Binding Chromium to main looper Looper (main, tid 1) {4252aca8}
I/LibraryLoader( 4658): Expected native library version number "",actual native library version number ""
I/chromium( 4658): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4658): Initializing chromium process, renderers=0
D/BluetoothManagerService(  989): Message: 20
D/BluetoothManagerService(  989): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4459eb30:true
I/Adreno-EGL( 4658): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4658): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4658): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4658): Local Branch: 
I/Adreno-EGL( 4658): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4658): Local Patches: NONE
I/Adreno-EGL( 4658): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4658): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 4658): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4658): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4658): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4658): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4658): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 4658): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4658): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4658): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4658): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4658): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 4658): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 4658): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4658): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4658): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 4658): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4658): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4658): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 4658): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 4658): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4658): Enabling debug mode 0
,I/Keyboard.Facilitator( 1207): onFinishInput()
,W/AwContents( 4658): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 4658): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler(  989): Displayed com.test.thalitest/.MainActivity,cp,ca,449
I/ActivityManager(  989): Displayed com.test.thalitest/.MainActivity: +420ms (total +450ms)
,D/MDMCTBK (  273): reply_len: 49 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1 38:f8:89
,D/MDMCTBK (  273): Event received = CTRL-EVENT-BSS-REMOVED 1 38:f8:89
,D/JsMessageQueue( 4658): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4658): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4252ef78
,D/dalvikvm( 4658): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4252ef78
,D/jxcore_app_log( 4658): JniHelper::setJavaVM(0x41c46f78), pthread_self() = 1614665184
,I/chromium( 4658): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/dalvikvm( 4658): GC_CONCURRENT freed 2663K, 16% free 14526K/17224K, paused 3ms+3ms, total 40ms
,D/dalvikvm( 4658): WAIT_FOR_CONCURRENT_GC blocked 20ms
W/PluginManager( 4658): THREAD WARNING: exec() call to JXcore.isReady blocked the main thread for 21ms. Plugin should use CordovaInterface.getThreadPool().
,D/dalvikvm( 4658): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/dalvikvm( 4658): GC_FOR_ALLOC freed 424K, 14% free 14889K/17224K, paused 27ms, total 28ms
,D/dalvikvm( 4658): GC_FOR_ALLOC freed 105K, 14% free 14896K/17224K, paused 30ms, total 31ms
,I/dalvikvm-heap( 4658): Grow heap (frag case) to 16.640MB for 63974-byte allocation
,D/dalvikvm( 4658): GC_FOR_ALLOC freed 127K, 14% free 14916K/17288K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4658): Grow heap (frag case) to 16.690MB for 95956-byte allocation
,D/dalvikvm( 4658): GC_FOR_ALLOC freed 178K, 14% free 14951K/17384K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4658): Grow heap (frag case) to 16.770MB for 143930-byte allocation
,D/dalvikvm( 4658): GC_FOR_ALLOC freed 255K, 15% free 14997K/17528K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4658): Grow heap (frag case) to 16.884MB for 215890-byte allocation
,D/dalvikvm( 4658): GC_FOR_ALLOC freed 366K, 16% free 15072K/17740K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4658): Grow heap (frag case) to 17.060MB for 323830-byte allocation
,D/dalvikvm( 4658): GC_FOR_ALLOC freed 569K, 16% free 15192K/18060K, paused 27ms, total 27ms
,D/dalvikvm( 4658): GC_FOR_ALLOC freed 864K, 15% free 15369K/18060K, paused 27ms, total 28ms
,I/dalvikvm-heap( 4658): Grow heap (frag case) to 17.736MB for 728606-byte allocation
,D/dalvikvm( 4658): GC_FOR_ALLOC freed 1282K, 17% free 15624K/18772K, paused 28ms, total 29ms
,I/dalvikvm-heap( 4658): Grow heap (frag case) to 18.333MB for 1092904-byte allocation
,D/dalvikvm( 4658): GC_CONCURRENT freed 1854K, 20% free 16021K/19840K, paused 1ms+5ms, total 42ms
,D/dalvikvm( 4658): GC_FOR_ALLOC freed 171K, 20% free 15971K/19840K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4658): Grow heap (frag case) to 19.193MB for 1639352-byte allocation
,D/dalvikvm( 4658): GC_CONCURRENT freed 1921K, 23% free 16541K/21444K, paused 1ms+4ms, total 43ms
,D/dalvikvm( 4658): GC_FOR_ALLOC freed 1033K, 23% free 16517K/21444K, paused 30ms, total 30ms
,I/dalvikvm-heap( 4658): Grow heap (frag case) to 20.507MB for 2459024-byte allocation
,D/dalvikvm( 4658): GC_CONCURRENT freed 1934K, 28% free 17270K/23848K, paused 1ms+4ms, total 39ms
,D/dalvikvm( 4658): GC_CONCURRENT freed 2485K, 27% free 17541K/23848K, paused 2ms+6ms, total 47ms
D/dalvikvm( 4658): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 4658): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 4658): GC_FOR_ALLOC freed 200K, 27% free 17450K/23848K, paused 30ms, total 30ms
,I/dalvikvm-heap( 4658): Grow heap (frag case) to 22.591MB for 3688532-byte allocation
,D/dalvikvm( 4658): GC_CONCURRENT freed 2641K, 33% free 18523K/27452K, paused 5ms+6ms, total 48ms
,D/dalvikvm( 4658): GC_FOR_ALLOC freed 2005K, 32% free 18675K/27452K, paused 33ms, total 35ms
,W/jxcore-log( 4658): Initializing JXcore engine
,W/jxcore-log( 4658): JXcore engine is ready
,D/dalvikvm( 4658): GC_CONCURRENT freed 413K, 22% free 21486K/27452K, paused 3ms+2ms, total 36ms
,D/dalvikvm( 4658): WAIT_FOR_CONCURRENT_GC blocked 18ms
,W/jxcore-log( 4658): Starting JXcore engine
,D/dalvikvm( 4658): WAIT_FOR_CONCURRENT_GC blocked 24ms
,W/jxcore-log( 4658): Platform android
W/jxcore-log( 4658): 
,W/jxcore-log( 4658): Process ARCH arm
W/jxcore-log( 4658): 
,I/jxcore-log( 4658): JXcore Cordova bridge is ready!
I/jxcore-log( 4658): 
,W/jxcore-log( 4658): JXcore engine is started
,E/jxcore  ( 4658): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4658): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4658): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  989): Killing 4376:com.google.android.youtube/u0a102 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ActivityManager(  989): Service ServiceRecord{43a75548 u0 com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService} in process ProcessRecord{444fb3d8 4376:com.google.android.youtube/u0a102} not same as in map: null
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1606): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1606): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1606): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1606): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1606): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1606): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1606): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1606): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,W/IInputConnectionWrapper( 4658): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1207): onFinishInput()
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
,V/AlarmManager(  989): sending alarm Alarm{43af5bc0 type 3 android}
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
,I/Keyboard.Facilitator.LanguageModelFlusher( 1207): run()
,I/Keyboard.Facilitator( 1207): flushDynamicLanguageModels()
,I/ConfigService( 1222): onCreate
,I/ConfigService( 1222): onDestroy
,V/AlarmManager(  989): sending alarm Alarm{44984a68 type 3 android}
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
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  989): sending alarm Alarm{4478bd80 type 3 android}
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
,V/AlarmManager(  989): sending alarm Alarm{44786c38 type 3 android}
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
,V/AlarmManager(  989): sending alarm Alarm{449c78a0 type 2 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  989): sending alarm Alarm{4477a6e0 type 3 android}
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
,V/AlarmManager(  989): sending alarm Alarm{446c5e40 type 2 android}
,V/AlarmManager(  989): sending alarm Alarm{446591c8 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{44636068 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{44633648 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{44630cb0 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{446300b8 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{4462cf68 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{449c6148 type 2 android}
,D/ConnectivityService(  989): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  989): sending alarm Alarm{449c4b28 type 1 com.android.deskclock}
,D/ConnectivityService(  989): Done.
,D/ConnectivityService(  989): Setting timer for 720seconds
,I/ActivityManager(  989): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4732 uid=10015 gids={50015, 1028}
,I/ActivityManager(  989): Killing 4340:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/AlarmManager(  989): sending alarm Alarm{4462b770 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{449c3f60 type 2 com.google.android.gms}
,D/ConnectivityService(  989): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/SBar.NetworkController( 1092): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/SBar.NetworkController( 1092): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1295): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1295): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1295): onReceive() - done, currentInetCondition=100
,V/AlarmManager(  989): sending alarm Alarm{446108d8 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{445eaf30 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{445e6c58 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{445e5438 type 3 android}
,V/AlarmManager(  989): sending alarm Alarm{445e2d10 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  989): sending alarm Alarm{445e0818 type 3 android}
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
,V/AlarmManager(  989): sending alarm Alarm{445dc2c8 type 3 android}
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
,V/AlarmManager(  989): sending alarm Alarm{445d55e8 type 3 android}
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
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 4775): 
D/AndroidRuntime( 4775): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4775): CheckJNI is OFF
D/dalvikvm( 4775): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4775): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4775): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4775): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4775): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4775): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4775): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4775): failed to load memtrack module: -2
D/AndroidRuntime( 4775): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  989): Force stopping com.test.thalitest appid=10130 user=-1: uninstall pkg
I/ActivityManager(  989): Killing 4658:com.test.thalitest/u0a130 (adj 11): stop com.test.thalitest
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager(  989): Force stopping com.test.thalitest appid=10130 user=0: pkg removed
I/Keyboard.Facilitator( 1207): resetDictionaries() : en_GB
W/GeofencerStateMachine( 1222): Ignoring removeGeofence because network location is disabled.
I/InputReader(  989): Reconfiguring input devices.  changes=0x00000010
I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "sms"
I/Keyboard.Facilitator.DecoderInitializer( 1207): run()
D/VoicemailCleanupService( 1186): Cleaning up data for package: com.test.thalitest
D/dalvikvm( 2343): GC_EXPLICIT freed 5286K, 44% free 9648K/17224K, paused 2ms+5ms, total 61ms
D/dalvikvm( 1309): GC_EXPLICIT freed 3253K, 33% free 11598K/17224K, paused 2ms+5ms, total 126ms
D/dalvikvm( 1698): GC_EXPLICIT freed 1206K, 31% free 11974K/17224K, paused 3ms+6ms, total 63ms
I/Launcher( 1309): Deferring update until onResume
D/dalvikvm( 2373): GC_EXPLICIT freed 4211K, 42% free 10099K/17224K, paused 63ms+6ms, total 117ms
W/SQLiteConnectionPool( 1698): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/Decoder ( 1207): createOrResetDecoder
D/dalvikvm(  989): GC_EXPLICIT freed 25665K, 65% free 18871K/53628K, paused 6ms+26ms, total 230ms
D/dalvikvm(  989): WAIT_FOR_CONCURRENT_GC blocked 2ms
I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "smsto"
I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "mms"
I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "mmsto"
I/InternalIcingCorporaPro( 2373): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "sms"
I/ConfigService( 1222): onCreate
I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "smsto"
I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "mms"
I/PackageManager(  989): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  989):   Action: "android.intent.action.SENDTO"
I/PackageManager(  989):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  989):   Scheme: "mmsto"
D/BackupManagerService(  989): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  989): removePackageParticipantsLocked: uid=10130 #1
I/ActivityManager(  989): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4805 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
I/Launcher( 1309): Deferring update until onResume
I/Keyboard.Facilitator.MainLanguageModelLoader( 1207): run()
W/ContextImpl( 4805): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
D/PackageBroadcastService( 1698): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1698): Clearing selected account for com.test.thalitest
I/dalvikvm( 4031): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4031): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 4031): VFY: replacing opcode 0x6e at 0x0013
I/LocationSettingsChecker( 1698): Removing dialog suppression flag for package com.test.thalitest
I/Keyboard.Facilitator.MainLanguageModelLoader( 1207): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1.apk (offset=5018356, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1207): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1207): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1207): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1207): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1207): run() : Loaded File = UserHistory.en_GB.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1207): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1207): run() : Missing File = Personal.en_GB.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1207): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1207): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1207): run()
I/StatsUtilsManager( 1207): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1207): shouldRecordStats() = Too Soon
D/ChimeraCfgMgr( 1698): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1698): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1346): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1346): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 1698): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1698): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/ChimeraCfgMgr( 1698): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1698): Module APK com.google.android.play.games already loaded
D/gH_MetricsDatabase( 1698): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1698): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1698): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1698): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1698): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1698): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1698): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1698): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1698): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1698): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1698): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  989): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4834 uid=10058 gids={50058}
D/dalvikvm(  275): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+3ms, total 22ms
I/Icing   ( 1698): doRemovePackageData com.test.thalitest
I/InternalIcingCorporaPro( 2373): UpdateCorporaTask done [took 210 ms] updated apps [took 210 ms] 
D/dalvikvm(  275): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 18ms
D/dalvikvm(  275): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 18ms
D/dalvikvm(  989): GC_EXPLICIT freed 950K, 66% free 18656K/53628K, paused 5ms+17ms, total 310ms
D/Documents( 4834): Loading roots for com.android.providers.downloads.documents
I/ActivityManager(  989): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=4849 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
I/ActivityManager(  989): Killing 4508:com.google.android.partnersetup/u0a25 (adj 15): empty #9
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager(  989): Killing 4732:com.android.deskclock/u0a15 (adj 15): empty #9
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/AndroidRuntime( 4775): Shutting down VM
D/dalvikvm( 4775): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
D/Documents( 4834): Loading roots for com.android.externalstorage.documents
D/dalvikvm( 4849): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x4252a5e0, skipping init
I/openssl ( 4849): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4849): Crypto mode 0 already enabled
I/ActivityManager(  989): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4868 uid=10020 gids={50020, 1028, 1015, 1023}
I/ActivityManager(  989): Killing 4108:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1259): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/ExternalStorage( 4868): After updating volumes, found 1 active roots
D/Documents( 4834): Updating roots due to change at content://com.android.externalstorage.documents/root
D/Documents( 4834): Loading roots for com.android.providers.media.documents
D/Documents( 4834): Loading roots for com.google.android.apps.docs.storage
D/Documents( 4834): Update found 7 roots in 246ms
D/Documents( 4834): Used cached roots for com.android.providers.downloads.documents
D/Documents( 4834): Loading roots for com.android.externalstorage.documents
D/Documents( 4834): Used cached roots for com.android.providers.media.documents
D/Documents( 4834): Used cached roots for com.google.android.apps.docs.storage
D/Documents( 4834): Update found 7 roots in 6ms

```
