#### Test 568182548138a64_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged,
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 4087): 
D/AndroidRuntime( 4087): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4087): CheckJNI is OFF
D/dalvikvm( 4087): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4087): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4087): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4087): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4087): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4087): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4087): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4087): failed to load memtrack module: -2
D/AndroidRuntime( 4087): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4087
W/WindowManager( 1019): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4104 uid=10135 gids={50135, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4087): Shutting down VM
D/dalvikvm( 4087): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 2ms
W/ContextImpl( 1237): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1237): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4104): Binding Chromium to main looper Looper (main, tid 1) {41fcfcb8}
I/LibraryLoader( 4104): Expected native library version number "",actual native library version number ""
I/chromium( 4104): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4104): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42981310:true
I/Adreno-EGL( 4104): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4104): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4104): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4104): Local Branch: 
I/Adreno-EGL( 4104): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4104): Local Patches: NONE
I/Adreno-EGL( 4104): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4104): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4104): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4104): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4104): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4104): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4104): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4104): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4104): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4104): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4104): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4104): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4104): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4104): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4104): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4104): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4104): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4104): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4104): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4104): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4104): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4104): Enabling debug mode 0
,W/AwContents( 4104): nativeOnDraw failed; clearing to background color.
,I/Keyboard.Facilitator( 1210): onFinishInput()
,W/IInputConnectionWrapper( 4104): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1019): Displayed com.test.thalitest/.MainActivity,cp,ca,410
I/ActivityManager( 1019): Displayed com.test.thalitest/.MainActivity: +387ms (total +411ms)
,D/JsMessageQueue( 4104): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4104): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fd3f88
,D/dalvikvm( 4104): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fd3f88
,D/jxcore_app_log( 4104): JniHelper::setJavaVM(0x4161dfa8), pthread_self() = 1615150464
,I/chromium( 4104): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/dalvikvm( 4104): GC_CONCURRENT freed 2660K, 16% free 14529K/17224K, paused 2ms+4ms, total 41ms
,D/dalvikvm( 4104): WAIT_FOR_CONCURRENT_GC blocked 24ms
,W/PluginManager( 4104): THREAD WARNING: exec() call to JXcore.isReady blocked the main thread for 25ms. Plugin should use CordovaInterface.getThreadPool().
D/dalvikvm( 4104): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/dalvikvm( 4104): GC_FOR_ALLOC freed 423K, 14% free 14892K/17224K, paused 27ms, total 27ms
,D/dalvikvm( 4104): GC_FOR_ALLOC freed 94K, 14% free 14908K/17224K, paused 27ms, total 28ms
,I/dalvikvm-heap( 4104): Grow heap (frag case) to 16.653MB for 63974-byte allocation
,D/dalvikvm( 4104): GC_FOR_ALLOC freed 136K, 14% free 14919K/17288K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4104): Grow heap (frag case) to 16.693MB for 95956-byte allocation
,D/dalvikvm( 4104): GC_FOR_ALLOC freed 178K, 14% free 14954K/17384K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4104): Grow heap (frag case) to 16.773MB for 143930-byte allocation
,D/dalvikvm( 4104): GC_FOR_ALLOC freed 254K, 15% free 15001K/17528K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4104): Grow heap (frag case) to 16.887MB for 215890-byte allocation
,D/dalvikvm( 4104): GC_FOR_ALLOC freed 366K, 16% free 15075K/17740K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4104): Grow heap (frag case) to 17.063MB for 323830-byte allocation
,D/dalvikvm( 4104): GC_FOR_ALLOC freed 569K, 16% free 15195K/18060K, paused 27ms, total 27ms
,D/dalvikvm( 4104): GC_FOR_ALLOC freed 863K, 15% free 15372K/18060K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4104): Grow heap (frag case) to 17.739MB for 728606-byte allocation
,D/dalvikvm( 4104): GC_FOR_ALLOC freed 1283K, 17% free 15627K/18772K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4104): Grow heap (frag case) to 18.335MB for 1092904-byte allocation
,D/dalvikvm( 4104): GC_CONCURRENT freed 1883K, 20% free 16031K/19840K, paused 1ms+5ms, total 46ms
,D/dalvikvm( 4104): GC_FOR_ALLOC freed 189K, 20% free 15926K/19840K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4104): Grow heap (frag case) to 19.148MB for 1639352-byte allocation
,D/dalvikvm( 4104): GC_CONCURRENT freed 1779K, 23% free 16534K/21444K, paused 2ms+4ms, total 47ms
,D/dalvikvm( 4104): GC_FOR_ALLOC freed 1117K, 23% free 16531K/21444K, paused 30ms, total 30ms
,I/dalvikvm-heap( 4104): Grow heap (frag case) to 20.521MB for 2459024-byte allocation
,D/dalvikvm( 4104): GC_CONCURRENT freed 286K, 21% free 18872K/23848K, paused 4ms+3ms, total 39ms
,D/dalvikvm( 4104): GC_FOR_ALLOC freed 4233K, 27% free 17562K/23848K, paused 37ms, total 39ms
,I/dalvikvm-heap( 4104): Grow heap (frag case) to 22.701MB for 3688532-byte allocation
,D/dalvikvm( 4104): GC_CONCURRENT freed 402K, 24% free 20883K/27452K, paused 5ms+5ms, total 53ms
,D/dalvikvm( 4104): GC_FOR_ALLOC freed 4358K, 32% free 18678K/27452K, paused 33ms, total 33ms
,W/jxcore-log( 4104): Initializing JXcore engine
,W/jxcore-log( 4104): JXcore engine is ready
,D/dalvikvm( 4104): GC_CONCURRENT freed 419K, 22% free 21485K/27452K, paused 2ms+2ms, total 33ms
D/dalvikvm( 4104): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/dalvikvm( 4104): WAIT_FOR_CONCURRENT_GC blocked 24ms
,W/jxcore-log( 4104): Starting JXcore engine
,W/jxcore-log( 4104): Platform android
W/jxcore-log( 4104): 
,W/jxcore-log( 4104): Process ARCH arm
W/jxcore-log( 4104): 
,I/jxcore-log( 4104): JXcore Cordova bridge is ready!
I/jxcore-log( 4104): 
,W/jxcore-log( 4104): JXcore engine is started
,E/jxcore  ( 4104): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4104): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4104): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager( 1019): Killing 3032:com.android.providers.calendar/u0a8 (adj 15): empty #9
W/ContextImpl( 1237): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1237): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1237): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1594): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1594): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1594): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1594): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1594): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1594): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1594): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1594): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/Keyboard.Facilitator( 1210): onFinishInput()
,W/IInputConnectionWrapper( 4104): showStatusIcon on inactive InputConnection
,V/AlarmManager( 1019): sending alarm Alarm{4292aac0 type 2 android}
,V/AlarmManager( 1019): sending alarm Alarm{429d7568 type 3 android}
,I/Keyboard.Facilitator.LanguageModelFlusher( 1210): run()
,I/Keyboard.Facilitator( 1210): flushDynamicLanguageModels()
,I/ConfigService( 1225): onCreate
,I/ConfigService( 1225): onDestroy
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
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
,V/AlarmManager( 1019): sending alarm Alarm{429ee898 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4292ab98 type 1 com.android.deskclock}
,I/ActivityManager( 1019): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4167 uid=10015 gids={50015, 1028}
,D/dalvikvm( 1019): GC_EXPLICIT freed 1232K, 66% free 18718K/53832K, paused 4ms+14ms, total 102ms
I/ActivityManager( 1019): Killing 3900:com.android.defcontainer/u0a13 (adj 15): empty #9
W/ContextImpl( 1237): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{428bfee8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{444844d8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4447ab50 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{44463f90 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{44060038 type 3 android}
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
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
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
,V/AlarmManager( 1019): sending alarm Alarm{43f8dea0 type 3 android}
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
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
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
,V/AlarmManager( 1019): sending alarm Alarm{43f86220 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{43797948 type 3 android}
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
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
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
,V/AlarmManager( 1019): sending alarm Alarm{429585f8 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1019): sending alarm Alarm{429586d0 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
,D/ConnectivityService( 1019): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/SBar.NetworkController( 1093): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/SBar.NetworkController( 1093): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1275): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1275): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1275): onReceive() - done, currentInetCondition=100
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
,V/AlarmManager( 1019): sending alarm Alarm{429de920 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{42802a38 type 3 android}
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
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{4292a260 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
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
,V/AlarmManager( 1019): sending alarm Alarm{428b10c8 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{422f6f10 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
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
,V/AlarmManager( 1019): sending alarm Alarm{4220ce00 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
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
,V/AlarmManager( 1019): sending alarm Alarm{427fe250 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4297dbb0 type 0 com.google.android.gms}
,V/AlarmManager( 1019): sending alarm Alarm{429784d8 type 1 com.android.calendar}
,V/AlarmManager( 1019): sending alarm Alarm{4297ec78 type 1 com.motorola.motocare}
,V/AlarmManager( 1019): sending alarm Alarm{429cdba0 type 1 com.motorola.context}
,I/ActivityManager( 1019): Start proc com.motorola.context for service com.motorola.context/com.motorola.analytics.DailyCheckinService: pid=4242 uid=10011 gids={50011, 3003, 3002, 3001}
,D/dalvikvm(  276): GC_EXPLICIT freed 42K, 48% free 9012K/17224K, paused 2ms+10ms, total 42ms
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+11ms, total 30ms
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+3ms, total 18ms
,I/ActivityManager( 1019): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory: pid=4264 uid=10007 gids={50007, 3003}
,I/ActivityManager( 1019): Killing 3933:com.google.android.partnersetup/u0a25 (adj 15): empty #9
,W/ContextImpl( 1237): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Checkin ( 4242): publish the event [tag = CONTEXT_ENGINE event name = INTERNAL]
,D/ExtensionsFactory( 4264): No custom extensions.
,I/ActivityManager( 1019): Killing 3724:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
,W/ContextImpl( 1237): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4286 uid=10008 gids={50008, 3003, 1028, 1015}
,I/ActivityManager( 1019): Killing 3338:com.google.android.apps.plus/u0a90 (adj 15): empty #9
,W/ContextImpl( 1237): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Checkin ( 4242): publish the event [tag = CONTEXT_ENGINE event name = CE_USAGE_STATS]
,D/Checkin ( 4242): publish the event [tag = CONTEXT_ENGINE event name = CE_USAGE_STATS]
,D/Checkin ( 4242): publish the event [tag = CONTEXT_ENGINE event name = CE_USAGE_STATS]
,D/Checkin ( 4242): publish the event [tag = CONTEXT_ENGINE event name = CE_USAGE_STATS]
,D/Checkin ( 4242): publish the event [tag = CONTEXT_ENGINE event name = CE_USAGE_STATS]
,D/Checkin ( 4242): publish the event [tag = CONTEXT_ENGINE event name = CE_USAGE_STATS]
,D/Checkin ( 4242): publish the event [tag = CONTEXT_ENGINE event name = CE_USAGE_STATS]
,D/Checkin ( 4242): publish the event [tag = CONTEXT_ENGINE event name = CE_USAGE_STATS]
,D/Checkin ( 4242): publish the event [tag = CONTEXT_ENGINE event name = CE_USAGE_STATS]
,D/Checkin ( 4242): publish the event [tag = CONTEXT_ENGINE event name = CE_USAGE_STATS]
,D/Checkin ( 4242): publish the event [tag = CONTEXT_ENGINE event name = CE_USAGE_STATS]
,I/CalendarProvider2( 4286): Created com.android.providers.calendar.CalendarAlarmManager@41fe1ff8(com.android.providers.calendar.CalendarProvider2@41fd9bb0)
,D/Checkin ( 4242): publish the event [tag = CONTEXT_ENGINE event name = CE_USAGE_STATS]
,D/Checkin ( 4242): publish the event [tag = CONTEXT_ENGINE event name = CE_USAGE_STATS]
,I/ActivityManager( 1019): Start proc com.google.android.gm for content provider com.google.android.gm/.provider.MailProvider: pid=4301 uid=10064 gids={50064, 3003, 1028, 1015}
D/Checkin ( 4242): publish the event [tag = CONTEXT_ENGINE event name = CE_USAGE_STATS]
D/Checkin ( 4242): publish the event [tag = CONTEXT_ENGINE event name = CE_USAGE_STATS]
,D/ActivityThread( 4301): Loading provider com.android.gmail.ui: com.google.android.gm.provider.GmailProvider
,W/ContextImpl( 1237): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2434 
,E/MC_LineReader( 2264): Error opening /sys/module/pm8921_bms/parameters/bms_chrg_capacity
E/MC_LineReader( 2264): java.io.FileNotFoundException: /sys/module/pm8921_bms/parameters/bms_chrg_capacity: open failed: ENOENT (No such file or directory)
E/MC_LineReader( 2264): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/MC_LineReader( 2264): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
E/MC_LineReader( 2264): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
E/MC_LineReader( 2264): 	at java.io.FileReader.<init>(FileReader.java:66)
E/MC_LineReader( 2264): 	at com.motorola.motocare.util.LineReader.<init>(LineReader.java:20)
E/MC_LineReader( 2264): 	at com.motorola.motocare.util.LineReader$1.<init>(LineReader.java:53)
E/MC_LineReader( 2264): 	at com.motorola.motocare.util.LineReader.firstLineReader(LineReader.java:53)
E/MC_LineReader( 2264): 	at com.motorola.motocare.action.BatteryHealthAction.appendBatteryHealthReport(BatteryHealthAction.java:77)
E/MC_LineReader( 2264): 	at com.motorola.motocare.action.BatteryHealthAction.onReceiveImpl(BatteryHealthAction.java:57)
E/MC_LineReader( 2264): 	at com.motorola.motocare.util.BackgroundReceiver$1.run(BackgroundReceiver.java:14)
E/MC_LineReader( 2264): 	at android.os.Handler.handleCallback(Handler.java:733)
E/MC_LineReader( 2264): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/MC_LineReader( 2264): 	at android.os.Looper.loop(Looper.java:136)
E/MC_LineReader( 2264): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/MC_LineReader( 2264): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
E/MC_LineReader( 2264): 	at libcore.io.Posix.open(Native Method)
E/MC_LineReader( 2264): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/MC_LineReader( 2264): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/MC_LineReader( 2264): 	... 13 more
,E/MC_BatteryHealthAction( 2264): Invalid cycle_count 0
,E/MC_MmcStatsAction( 2264): Unable to find mmc block stat files.
W/System.err( 2264): java.io.FileNotFoundException: /sys/block/mmcblk1/stat: open failed: ENOENT (No such file or directory)
W/System.err( 2264): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 2264): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err( 2264): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err( 2264): 	at java.io.FileReader.<init>(FileReader.java:66)
,W/System.err( 2264): 	at com.motorola.motocare.action.MmcStatsAction.readMmcSectorWrites(MmcStatsAction.java:87)
W/System.err( 2264): 	at com.motorola.motocare.action.MmcStatsAction.appendMmcStatsReport(MmcStatsAction.java:70)
W/System.err( 2264): 	at com.motorola.motocare.action.MmcStatsAction.onReceiveImpl(MmcStatsAction.java:49)
W/System.err( 2264): 	at com.motorola.motocare.util.BackgroundReceiver$1.run(BackgroundReceiver.java:14)
W/System.err( 2264): 	at android.os.Handler.handleCallback(Handler.java:733)
,W/System.err( 2264): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2264): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 2264): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/System.err( 2264): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
,W/System.err( 2264): 	at libcore.io.Posix.open(Native Method)
W/System.err( 2264): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 2264): 	at libcore.io.IoBridge.open(IoBridge.java:393)
,W/System.err( 2264): 	... 11 more
,W/GAV2    ( 4301): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager( 1019): Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=4334 uid=10013 gids={50013, 1028, 1015, 1023, 2001, 1035}
,I/Gmail   ( 4301): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4301): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4301): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4301): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/ActivityManager( 1019): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4354 uid=10019 gids={50019, 3003, 1028, 1015}
,D/ActivityThread( 4354): Loading provider com.android.email.provider;com.android.email.notifier: com.android.email.provider.EmailProvider
,D/dalvikvm( 4354): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41fd2908, skipping init
,I/com.android.email.cryptography.CryptographicModeHelper( 4354): Cryptographic modes supported!
I/openssl ( 4354): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4354): Crypto mode 0 already enabled
,W/ActivityManager( 1019): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/ContextImpl( 1237): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.internal.SmsCallsAction.onReceiveImpl:64 com.motorola.motocare.internal.SmsCallsAction.access$000:21 
,I/ActivityManager( 1019): Killing 3962:com.google.android.apps.docs/u0a59 (adj 15): empty #9
I/Email   ( 4354): Observing account changes for notifications
,W/ContextImpl( 1237): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ActivityManager( 1019): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/dalvikvm( 2264): GC_CONCURRENT freed 7148K, 43% free 9981K/17224K, paused 2ms+5ms, total 33ms
,V/AlarmManager( 1019): sending alarm Alarm{437fd3f8 type 1 com.android.deskclock}
,I/CalendarProvider2( 4286): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 4286): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/AlertReceiver( 4264): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/AlertService( 4264): 0 Action = android.intent.action.PROVIDER_CHANGED
,D/dalvikvm( 1019): GC_CONCURRENT freed 2504K, 66% free 18644K/53832K, paused 4ms+8ms, total 107ms
,D/dalvikvm( 1019): GC_CONCURRENT freed 2559K, 66% free 18507K/53832K, paused 5ms+7ms, total 95ms
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_L1 event name = EventLogs]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L2 event name = DC_SDCARD]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L5 event name = DC_UNLOCK]
,D/dalvikvm( 2264): GC_CONCURRENT freed 2334K, 45% free 9615K/17224K, paused 3ms+4ms, total 25ms
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOff]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOff]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOff]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOff]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOff]
,D/dalvikvm( 2264): GC_CONCURRENT freed 1739K, 43% free 9894K/17224K, paused 2ms+3ms, total 27ms
,I/GAV2    ( 4301): Thread[GAThread,5,main]: No campaign data found.
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/dalvikvm( 2264): GC_CONCURRENT freed 2025K, 43% free 9819K/17224K, paused 2ms+6ms, total 35ms
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOff]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOff]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOff]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOff]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOff]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/dalvikvm( 2264): GC_CONCURRENT freed 2116K, 44% free 9690K/17224K, paused 2ms+4ms, total 29ms
,I/GlobalDismissManager( 4264): no sender configured
,D/AlertService( 4264): Beginning updateAlertNotification
,D/AlertService( 4264): No fired or scheduled alerts
,D/AlertService( 4264): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 4264): No events found starting within 1 week.
,I/ActivityManager( 1019): Killing 3997:com.quickoffice.android/u0a95 (adj 15): empty #9
,W/ContextImpl( 1237): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/dalvikvm( 2264): GC_CONCURRENT freed 1752K, 43% free 9985K/17224K, paused 3ms+5ms, total 30ms
,D/dalvikvm( 2264): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOff]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOff]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOff]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOff]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOff]
,D/dalvikvm( 2264): GC_CONCURRENT freed 2193K, 44% free 9781K/17224K, paused 1ms+5ms, total 28ms
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOff]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOff]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOff]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOff]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOff]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/dalvikvm( 2264): GC_CONCURRENT freed 2050K, 44% free 9731K/17224K, paused 1ms+4ms, total 28ms
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/dalvikvm( 2264): GC_CONCURRENT freed 2034K, 44% free 9673K/17224K, paused 1ms+4ms, total 28ms
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/dalvikvm( 2264): GC_CONCURRENT freed 1759K, 43% free 9962K/17224K, paused 1ms+6ms, total 25ms
,D/dalvikvm( 2264): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOff]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOff]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOff]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOff]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOff]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/dalvikvm( 2264): GC_CONCURRENT freed 2265K, 44% free 9656K/17224K, paused 2ms+3ms, total 28ms
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS event name = DataSizes]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS event name = RadioTypes]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS event name = SignalStrengths]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS event name = PhoneTimeStats]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS event name = PerUidStats]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOff]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOff]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOff]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOff]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOff]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS event name = AppUsage]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L1 event name = DC_ACCOUNT]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L1 event name = DC_SIGNALSTRENGTH]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L3 event name = DC_NETWORK]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L1 event name = DC_BATTERY]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS event name = EventLogs]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_L1 event name = EventLogs]
,D/dalvikvm( 2264): GC_CONCURRENT freed 1982K, 44% free 9658K/17224K, paused 3ms+4ms, total 31ms
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_L3 event name = EventLogs]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_L3 event name = EventLogs]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L2 event name = DC_PKG]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L2 event name = DC_PKG]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L2 event name = DC_PKG]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L2 event name = DC_PKG]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L2 event name = DC_PKG]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L2 event name = DC_PKG]
,D/dalvikvm( 2264): GC_CONCURRENT freed 2140K, 45% free 9567K/17224K, paused 2ms+3ms, total 22ms
,D/dalvikvm( 2264): GC_CONCURRENT freed 2040K, 45% free 9547K/17224K, paused 3ms+1ms, total 23ms
,D/dalvikvm( 2264): GC_CONCURRENT freed 1967K, 45% free 9607K/17224K, paused 2ms+2ms, total 20ms
,D/dalvikvm( 2264): GC_CONCURRENT freed 2029K, 45% free 9577K/17224K, paused 2ms+2ms, total 20ms
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2264): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS event name = MMCStats]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_L1 event name = EventLogs]
,D/dalvikvm( 2264): GC_CONCURRENT freed 1656K, 43% free 9885K/17224K, paused 1ms+5ms, total 27ms
,D/dalvikvm( 2264): GC_CONCURRENT freed 1894K, 43% free 9943K/17224K, paused 2ms+6ms, total 30ms
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_MM event name = DC_MM]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_MM event name = DC_MM]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_MM event name = DC_MM]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_MM event name = DC_MM]
,D/dalvikvm( 2264): GC_CONCURRENT freed 2118K, 43% free 9818K/17224K, paused 2ms+4ms, total 32ms
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_MM event name = DC_MM]
,D/dalvikvm( 2264): GC_CONCURRENT freed 1824K, 43% free 9984K/17224K, paused 3ms+5ms, total 30ms
,I/ActivityManager( 1019): Killing 3658:com.android.vending/u0a38 (adj 15): empty #9
,W/ContextImpl( 1237): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/dalvikvm( 2264): GC_CONCURRENT freed 1958K, 42% free 10014K/17224K, paused 1ms+5ms, total 29ms
,D/Checkin ( 1019): publish the event [tag = MOT_APP_STATS event name = APPLAUNCH]
,D/Checkin ( 1019): publish the event [tag = MOT_APP_STATS event name = APPLAUNCH]
,D/Checkin ( 1019): publish the event [tag = MOT_APP_STATS event name = APPLAUNCH]
,D/dalvikvm( 2264): GC_CONCURRENT freed 1979K, 42% free 10011K/17224K, paused 3ms+5ms, total 31ms
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_MEM_S event name = Summary]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_MEM_S event name = Summary]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_MEM_S event name = Summary]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_MEM_S event name = Summary]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_MEM_S event name = Summary]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_MEM_S event name = Summary]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_MEM_E event name = AMK_E]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_MEM_E event name = AMK_E]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_MEM_S event name = Summary]
,D/dalvikvm( 2264): GC_CONCURRENT freed 2032K, 43% free 9974K/17224K, paused 1ms+6ms, total 31ms
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_MEM_E event name = AMK_E]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_MEM_E event name = AMK_E]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_MEM_S event name = Summary]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_MEM_S event name = Summary]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_MEM_E event name = AMK_E]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_MEM_S event name = Summary]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_MEM_E event name = AMK_E]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_MEM_S event name = Summary]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_MEM_E event name = AMK_E]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_MEM_E event name = AMK_E]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_MEM_E event name = AMK_E]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_MEM_S event name = Summary]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_MEM_S event name = Summary]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_MEM_S event name = Summary]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_MEM_E event name = AMK_E]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_MEM_S event name = Summary]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS_MEM_E event name = AMK_E]
,D/Checkin ( 2264): publish the event [tag = MOT_DEVICE_STATS event name = STORAGESTATS]
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
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{437bcfc8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4479f628 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{44958b38 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 4406): 
D/AndroidRuntime( 4406): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4406): CheckJNI is OFF
D/dalvikvm( 4406): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4406): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4406): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4406): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4406): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4406): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4406): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4406): failed to load memtrack module: -2
D/AndroidRuntime( 4406): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10135 user=-1: uninstall pkg
I/ActivityManager( 1019): Killing 4104:com.test.thalitest/u0a135 (adj 15): stop com.test.thalitest
W/ContextImpl( 1237): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10135 user=0: pkg removed
I/Keyboard.Facilitator( 1210): resetDictionaries() : en_GB
W/GeofencerStateMachine( 1225): Ignoring removeGeofence because network location is disabled.
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
I/Keyboard.Facilitator.DecoderInitializer( 1210): run()
D/VoicemailCleanupService( 1185): Cleaning up data for package: com.test.thalitest
I/dalvikvm( 2264): Jit: resizing JitTable from 4096 to 8192
D/dalvikvm( 2264): GC_EXPLICIT freed 2306K, 45% free 9588K/17224K, paused 6ms+5ms, total 57ms
D/dalvikvm( 1296): GC_EXPLICIT freed 3248K, 33% free 11595K/17224K, paused 2ms+11ms, total 105ms
D/dalvikvm( 2296): GC_EXPLICIT freed 3282K, 42% free 10053K/17224K, paused 2ms+79ms, total 123ms
I/Launcher( 1296): Deferring update until onResume
I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
D/dalvikvm( 1715): GC_EXPLICIT freed 872K, 31% free 11916K/17224K, paused 6ms+8ms, total 146ms
I/Decoder ( 1210): createOrResetDecoder
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
D/dalvikvm( 1019): GC_EXPLICIT freed 2250K, 66% free 18582K/53832K, paused 4ms+10ms, total 160ms
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
I/Launcher( 1296): Deferring update until onResume
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
I/ActivityManager( 1019): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4433 uid=10033 gids={50033, 3003, 1028, 1015}
I/ConfigService( 1225): onCreate
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1019): removePackageParticipantsLocked: uid=10135 #1
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
I/InternalIcingCorporaPro( 2296): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/Keyboard.Facilitator.MainLanguageModelLoader( 1210): run()
I/ActivityManager( 1019): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4451 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
I/Keyboard.Facilitator.MainLanguageModelLoader( 1210): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1.apk (offset=5018356, length=4014912) with up to date LoudsLmContentVersion = 20150512
W/ContextImpl( 4451): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1210): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1210): run() : Loading LM = contacts
D/dalvikvm( 1019): GC_EXPLICIT freed 566K, 66% free 18609K/53832K, paused 4ms+15ms, total 171ms
I/ActivityManager( 1019): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4464 uid=10038 gids={50038, 3003, 1028, 1015}
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1210): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1210): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1210): run() : Loaded File = UserHistory.en_GB.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1210): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1210): run() : Missing File = Personal.en_GB.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1210): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1210): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1210): run()
I/StatsUtilsManager( 1210): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1210): shouldRecordStats() = Too Soon
I/InternalIcingCorporaPro( 2296): UpdateCorporaTask done [took 93 ms] updated apps [took 93 ms] 
I/ActivityManager( 1019): Killing 4242:com.motorola.context/u0a11 (adj 15): empty #9
W/ContextImpl( 1237): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/dalvikvm( 4464): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4464): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 4464): VFY: replacing opcode 0x6e at 0x000e
D/AndroidRuntime( 4406): Shutting down VM
D/dalvikvm( 4406): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 2ms
D/Finsky  ( 4464): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/dalvikvm( 4464): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4464): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 4464): VFY: replacing opcode 0x6e at 0x01d3
I/dalvikvm( 4464): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4464): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/dalvikvm( 4464): VFY: replacing opcode 0x6e at 0x000a
D/Finsky  ( 4464): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4464): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4464): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
D/dalvikvm( 4464): VFY: replacing opcode 0x6e at 0x0032
W/Settings( 4464): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4464): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/dalvikvm( 4464): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4464): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4464): VFY: replacing opcode 0x6e at 0x013c
I/dalvikvm( 4464): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4464): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4464): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4464): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4464): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4464): VFY: replacing opcode 0x6e at 0x0385
I/ActivityManager( 1019): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4500 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
I/dalvikvm( 4464): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4464): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
D/dalvikvm( 4464): VFY: replacing opcode 0x6e at 0x0019
I/ActivityManager( 1019): Killing 4301:com.google.android.gm/u0a64 (adj 15): empty #9
I/ActivityManager( 1019): Killing 4286:com.android.providers.calendar/u0a8 (adj 15): empty #10
D/Ads     ( 4464): Skipping gmscore version check
W/ContextImpl( 1237): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/Finsky  ( 4464): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4464): [1] Libraries$2.run: Finished loading 1 libraries.
W/ContextImpl( 1237): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/PackageBroadcastService( 1715): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1715): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1715): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1715): Module APK com.google.android.play.games already loaded
I/dalvikvm( 4464): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4464): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 4464): VFY: replacing opcode 0x6e at 0x0013
I/LocationSettingsChecker( 1715): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1715): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1715): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1361): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1361): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager( 1019): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4519 uid=10090 gids={50090, 3003, 3002, 1028, 1015}
D/gH_CompatibleDatabase( 1715): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1715): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1715): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1715): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1715): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1715): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1715): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/Icing   ( 1715): doRemovePackageData com.test.thalitest
D/gH_CompatibleDatabase( 1715): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1715): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1715): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1715): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1715): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1715): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
W/SharedPreferencesImpl( 4464): writeToFile: Got exception:
W/SharedPreferencesImpl( 4464): java.io.IOException: write failed: EBADF (Bad file number)
W/SharedPreferencesImpl( 4464): 	at libcore.io.IoBridge.write(IoBridge.java:455)
W/SharedPreferencesImpl( 4464): 	at java.io.FileOutputStream.write(FileOutputStream.java:187)
W/SharedPreferencesImpl( 4464): 	at com.android.internal.util.FastXmlSerializer.flushBytes(FastXmlSerializer.java:232)
W/SharedPreferencesImpl( 4464): 	at com.android.internal.util.FastXmlSerializer.flush(FastXmlSerializer.java:253)
W/SharedPreferencesImpl( 4464): 	at com.android.internal.util.FastXmlSerializer.endDocument(FastXmlSerializer.java:198)
W/SharedPreferencesImpl( 4464): 	at com.android.internal.util.XmlUtils.writeMapXml(XmlUtils.java:182)
W/SharedPreferencesImpl( 4464): 	at android.app.SharedPreferencesImpl.writeToFile(SharedPreferencesImpl.java:596)
W/SharedPreferencesImpl( 4464): 	at android.app.SharedPreferencesImpl.access$800(SharedPreferencesImpl.java:52)
W/SharedPreferencesImpl( 4464): 	at android.app.SharedPreferencesImpl$2.run(SharedPreferencesImpl.java:511)
W/SharedPreferencesImpl( 4464): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/SharedPreferencesImpl( 4464): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/SharedPreferencesImpl( 4464): 	at java.lang.Thread.run(Thread.java:841)
W/SharedPreferencesImpl( 4464): Caused by: libcore.io.ErrnoException: write failed: EBADF (Bad file number)
W/SharedPreferencesImpl( 4464): 	at libcore.io.Posix.writeBytes(Native Method)
W/SharedPreferencesImpl( 4464): 	at libcore.io.Posix.write(Posix.java:202)
W/SharedPreferencesImpl( 4464): 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:197)
W/SharedPreferencesImpl( 4464): 	at libcore.io.IoBridge.write(IoBridge.java:450)
W/SharedPreferencesImpl( 4464): 	... 11 more
E/SharedPreferencesImpl( 4464): Couldn't clean up partially-written file /data/data/com.android.vending/shared_prefs/finsky.xml
E/dalvikvm( 4519): Could not find class 'android.app.Notification$Action$Builder', referenced from method efj.a
W/dalvikvm( 4519): VFY: unable to resolve new-instance 412 (Landroid/app/Notification$Action$Builder;) in Lefj;
D/dalvikvm( 4519): VFY: replacing opcode 0x22 at 0x0000
E/dalvikvm( 4519): Could not find class 'android.graphics.drawable.RippleDrawable', referenced from method efj.a
W/dalvikvm( 4519): VFY: unable to resolve new-instance 575 (Landroid/graphics/drawable/RippleDrawable;) in Lefj;
D/dalvikvm( 4519): VFY: replacing opcode 0x22 at 0x000b

```
