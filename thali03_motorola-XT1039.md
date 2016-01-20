#### Test 564496606be5677_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 1019): sending alarm Alarm{424dc788 type 3 android}
,--------- beginning of /dev/log/main
D/AndroidRuntime( 4225): 
D/AndroidRuntime( 4225): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4225): CheckJNI is OFF
D/dalvikvm( 4225): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4225): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4225): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4225): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4225): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4225): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4225): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4225): failed to load memtrack module: -2
D/AndroidRuntime( 4225): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4225
W/WindowManager( 1019): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4242 uid=10129 gids={50129, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4225): Shutting down VM
D/dalvikvm( 4225): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
W/ContextImpl( 1282): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1282): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4242): Binding Chromium to main looper Looper (main, tid 1) {4229d400}
I/LibraryLoader( 4242): Expected native library version number "",actual native library version number ""
I/chromium( 4242): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4242): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4257aab8:true
I/Adreno-EGL( 4242): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4242): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4242): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4242): Local Branch: 
I/Adreno-EGL( 4242): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4242): Local Patches: NONE
I/Adreno-EGL( 4242): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4242): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4242): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4242): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4242): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4242): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4242): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4242): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4242): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4242): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4242): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4242): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4242): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4242): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4242): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4242): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4242): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4242): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4242): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4242): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4242): CordovaWebView is running on device made by: motorola
I/SFPerfTracer(  274):      triggers: (rate: 2:62) (compose: 0:4) (post: 0:1) (render: 0:5) (1:152 frames) (2:649)
D/SFPerfTracer(  274):        layers: (0:12) (FocusedStackFrame: 0:8)* (StatusBar: 0:233)* (NavigationBar: 0:43)* (com.android.systemui.ImageWallpaper: 0:5)* (Starting com.motorola.ccc.ota: 0:37)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity: 0:13)* (ElectronBeam: 0:27)* (com.test.thalitest/com.test.thalitest.MainActivity: 2:2)* 
D/OpenGLRenderer( 4242): Enabling debug mode 0
I/Keyboard.Facilitator( 1208): onFinishInput()
W/AwContents( 4242): nativeOnDraw failed; clearing to background color.
W/IInputConnectionWrapper( 4242): showStatusIcon on inactive InputConnection
I/LaunchCheckinHandler( 1019): Displayed com.test.thalitest/.MainActivity,cp,ca,440
I/ActivityManager( 1019): Displayed com.test.thalitest/.MainActivity: +414ms (total +440ms)
D/JsMessageQueue( 4242): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4242): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422a16d0
D/dalvikvm( 4242): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422a16d0
D/jxcore_app_log( 4242): JniHelper::setJavaVM(0x419bff78), pthread_self() = 1614974952
,I/chromium( 4242): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/dalvikvm( 4242): GC_CONCURRENT freed 2642K, 16% free 14547K/17224K, paused 2ms+4ms, total 42ms
,D/dalvikvm( 4242): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 4242): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 4242): GC_FOR_ALLOC freed 355K, 14% free 14874K/17224K, paused 27ms, total 29ms
,D/dalvikvm( 4242): GC_FOR_ALLOC freed 69K, 14% free 14878K/17224K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4242): Grow heap (frag case) to 16.602MB for 42652-byte allocation
,D/dalvikvm( 4242): GC_FOR_ALLOC freed 92K, 14% free 14897K/17268K, paused 27ms, total 28ms
,D/dalvikvm( 4242): GC_FOR_ALLOC freed 126K, 14% free 14916K/17268K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4242): Grow heap (frag case) to 16.691MB for 95956-byte allocation
,D/dalvikvm( 4242): GC_FOR_ALLOC freed 178K, 14% free 14952K/17364K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4242): Grow heap (frag case) to 16.771MB for 143930-byte allocation
,D/dalvikvm( 4242): GC_FOR_ALLOC freed 241K, 15% free 15011K/17508K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4242): Grow heap (frag case) to 16.897MB for 215890-byte allocation
,D/dalvikvm( 4242): GC_FOR_ALLOC freed 380K, 15% free 15072K/17720K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4242): Grow heap (frag case) to 17.059MB for 323830-byte allocation
,D/dalvikvm( 4242): GC_FOR_ALLOC freed 568K, 16% free 15193K/18040K, paused 27ms, total 28ms
,I/dalvikvm-heap( 4242): Grow heap (frag case) to 17.333MB for 485740-byte allocation
,D/dalvikvm( 4242): GC_FOR_ALLOC freed 865K, 17% free 15368K/18516K, paused 28ms, total 28ms
,D/dalvikvm( 4242): GC_FOR_ALLOC freed 1172K, 16% free 15615K/18516K, paused 28ms, total 28ms
,D/dalvikvm( 4242): GC_FOR_ALLOC freed 167K, 16% free 15568K/18516K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4242): Grow heap (frag case) to 18.278MB for 1092904-byte allocation
,D/dalvikvm( 4242): GC_CONCURRENT freed 1837K, 19% free 16030K/19584K, paused 2ms+6ms, total 49ms
,D/dalvikvm( 4242): GC_FOR_ALLOC freed 180K, 19% free 15922K/19584K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4242): Grow heap (frag case) to 19.145MB for 1639352-byte allocation
,D/dalvikvm( 4242): GC_CONCURRENT freed 1807K, 22% free 16534K/21188K, paused 2ms+4ms, total 41ms
,D/dalvikvm( 4242): GC_FOR_ALLOC freed 1093K, 23% free 16525K/21188K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4242): Grow heap (frag case) to 20.515MB for 2459024-byte allocation
,D/dalvikvm( 4242): GC_CONCURRENT freed 329K, 20% free 18933K/23592K, paused 4ms+3ms, total 51ms
,D/dalvikvm( 4242): GC_FOR_ALLOC freed 4191K, 26% free 17555K/23592K, paused 37ms, total 37ms
,I/dalvikvm-heap( 4242): Grow heap (frag case) to 22.694MB for 3688532-byte allocation
,D/dalvikvm( 4242): GC_CONCURRENT freed 309K, 23% free 20952K/27196K, paused 5ms+5ms, total 64ms
,D/dalvikvm( 4242): GC_FOR_ALLOC freed 4439K, 32% free 18679K/27196K, paused 35ms, total 35ms
,W/jxcore-log( 4242): Initializing JXcore engine
,W/jxcore-log( 4242): JXcore engine is ready
,V/AlarmManager( 1019): sending alarm Alarm{42e98bb8 type 2 android}
,D/dalvikvm( 4242): GC_CONCURRENT freed 433K, 22% free 21472K/27196K, paused 3ms+2ms, total 39ms
D/dalvikvm( 4242): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/dalvikvm( 4242): WAIT_FOR_CONCURRENT_GC blocked 27ms
,W/jxcore-log( 4242): Starting JXcore engine
,W/jxcore-log( 4242): Platform android
W/jxcore-log( 4242): 
,W/jxcore-log( 4242): Process ARCH arm
W/jxcore-log( 4242): 
,I/jxcore-log( 4242): JXcore Cordova bridge is ready!
I/jxcore-log( 4242): 
,W/jxcore-log( 4242): JXcore engine is started
,E/jxcore  ( 4242): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4242): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4242): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager( 1019): Killing 3649:com.android.deskclock/u0a15 (adj 15): empty #9
W/ContextImpl( 1282): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1282): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1282): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1612): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1612): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1612): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1612): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1612): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1612): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1612): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1612): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/Keyboard.Facilitator( 1208): onFinishInput()
,W/IInputConnectionWrapper( 4242): showStatusIcon on inactive InputConnection
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
,V/AlarmManager( 1019): sending alarm Alarm{42307a40 type 3 android}
,I/Keyboard.Facilitator.LanguageModelFlusher( 1208): run()
,I/Keyboard.Facilitator( 1208): flushDynamicLanguageModels()
,I/ConfigService( 1237): onCreate
,I/ConfigService( 1237): onDestroy
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{42488028 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{42458950 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{4244aab0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42530a48 type 2 android}
,V/AlarmManager( 1019): sending alarm Alarm{42442b98 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{423eef70 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{423ed580 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{423b4b68 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{423a6300 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42372a38 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{42e98e98 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1019): sending alarm Alarm{42e99000 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
,D/dalvikvm( 1351): GC_EXPLICIT freed 1769K, 40% free 10366K/17224K, paused 2ms+5ms, total 33ms
,I/PhenotypeConfigurator( 1237): Scheduling Phenotype for one-off execution 4365 seconds from now (1453289351866)
,D/GetConfigurationSnapshotOperation( 1237): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1237): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1237): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1237): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1237): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 1237): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1237): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1237): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1237): Using platform SSLCertificateSocketFactory
,D/ConnectivityService( 1019): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
I/ModemStatsDSDetect( 1313): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1093): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1093): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1313): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1313): onReceive() - done, currentInetCondition=100
,D/dalvikvm( 1237): GC_CONCURRENT freed 1467K, 33% free 11577K/17224K, paused 3ms+7ms, total 32ms
,E/DataBuffer( 1237): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42388be8)
,E/DataBuffer( 1237): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42472d60)
E/DataBuffer( 1237): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4232a690)
E/DataBuffer( 1237): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@423f42c0)
E/DataBuffer( 1237): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42320660)
E/DataBuffer( 1237): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4243f1d8)
,E/DataBuffer( 1237): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4265b5a0)
E/DataBuffer( 1237): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@423a0690)
E/DataBuffer( 1237): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@426abdf8)
,E/DataBuffer( 1237): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4233f3d0)
,V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/AlarmManager( 1019): sending alarm Alarm{42d88d40 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42d88dd0 type 1 com.android.deskclock}
,I/ActivityManager( 1019): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4349 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1019): Killing 4055:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1282): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
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
,V/AlarmManager( 1019): sending alarm Alarm{42c7f340 type 3 android}
,I/ClearcutLoggerApiImpl( 1351): disconnect managed GoogleApiClient
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
,V/AlarmManager( 1019): sending alarm Alarm{43d3e440 type 3 android}
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
,V/AlarmManager( 1019): sending alarm Alarm{42ad2cb0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43bce360 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{434f7990 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{44485b90 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42b5bf10 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4435f2c8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42b7be58 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 4412): 
D/AndroidRuntime( 4412): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4412): CheckJNI is OFF
D/dalvikvm( 4412): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4412): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4412): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4412): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4412): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4412): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4412): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4412): failed to load memtrack module: -2
D/AndroidRuntime( 4412): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10129 user=-1: uninstall pkg
I/ActivityManager( 1019): Killing 4242:com.test.thalitest/u0a129 (adj 11): stop com.test.thalitest
W/ContextImpl( 1282): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/dalvikvm( 1019): Total arena pages for JIT: 15
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10129 user=0: pkg removed
D/dalvikvm( 2274): GC_EXPLICIT freed 6212K, 44% free 9753K/17224K, paused 2ms+6ms, total 39ms
I/Keyboard.Facilitator( 1208): resetDictionaries() : en_GB
W/GeofencerStateMachine( 1237): Ignoring removeGeofence because network location is disabled.
I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
I/Keyboard.Facilitator.DecoderInitializer( 1208): run()
D/VoicemailCleanupService( 1190): Cleaning up data for package: com.test.thalitest
D/dalvikvm( 1713): GC_EXPLICIT freed 1267K, 31% free 11914K/17224K, paused 5ms+5ms, total 117ms
I/Decoder ( 1208): createOrResetDecoder
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
D/dalvikvm( 2307): GC_EXPLICIT freed 3286K, 42% free 10054K/17224K, paused 2ms+26ms, total 137ms
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
D/dalvikvm( 1324): GC_EXPLICIT freed 3257K, 33% free 11599K/17224K, paused 2ms+6ms, total 117ms
I/Launcher( 1324): Deferring update until onResume
D/dalvikvm( 1019): GC_EXPLICIT freed 1821K, 66% free 18835K/53836K, paused 6ms+13ms, total 132ms
D/dalvikvm( 1019): WAIT_FOR_CONCURRENT_GC blocked 29ms
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
I/ConfigService( 1237): onCreate
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
I/InternalIcingCorporaPro( 2307): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
I/ActivityManager( 1019): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4447 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
I/Launcher( 1324): Deferring update until onResume
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
W/ContextImpl( 4447): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/Keyboard.Facilitator.MainLanguageModelLoader( 1208): run()
I/dalvikvm( 3791): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3791): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 3791): VFY: replacing opcode 0x6e at 0x0013
D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1019): removePackageParticipantsLocked: uid=10129 #1
D/PackageBroadcastService( 1713): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1713): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1713): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1713): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1713): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1713): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1713): Module APK com.google.android.play.games already loaded
I/Keyboard.Facilitator.MainLanguageModelLoader( 1208): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1.apk (offset=5018356, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1208): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1208): run() : Loading LM = contacts
E/NetworkScheduler.SchedulerReceiver( 1351): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1351): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1208): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1208): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1208): run() : Loaded File = UserHistory.en_GB.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1208): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1208): run() : Missing File = Personal.en_GB.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1208): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1208): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1208): run()
I/StatsUtilsManager( 1208): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1208): shouldRecordStats() = Too Soon
I/ActivityManager( 1019): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4468 uid=10058 gids={50058}
D/gH_CompatibleDatabase( 1713): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1713): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1713): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1713): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/Icing   ( 1713): doRemovePackageData com.test.thalitest
I/InternalIcingCorporaPro( 2307): UpdateCorporaTask done [took 171 ms] updated apps [took 171 ms] 
D/gH_CompatibleDatabase( 1713): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1713): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1713): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/Documents( 4468): Loading roots for com.android.providers.downloads.documents
D/gH_CompatibleDatabase( 1713): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1713): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1713): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1713): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1713): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1713): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager( 1019): Killing 4092:com.google.android.partnersetup/u0a25 (adj 15): empty #9
D/dalvikvm( 1019): GC_EXPLICIT freed 817K, 66% free 18698K/53836K, paused 5ms+17ms, total 283ms
W/ContextImpl( 1282): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1019): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=4490 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
I/ActivityManager( 1019): Killing 4349:com.android.deskclock/u0a15 (adj 15): empty #9
W/ContextImpl( 1282): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/AndroidRuntime( 4412): Shutting down VM
D/dalvikvm( 4412): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms
D/dalvikvm( 4490): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x422a84e8, skipping init
I/openssl ( 4490): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4490): Crypto mode 0 already enabled
D/Documents( 4468): Loading roots for com.android.externalstorage.documents
I/ActivityManager( 1019): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4507 uid=10020 gids={50020, 1028, 1015, 1023}
I/ActivityManager( 1019): Killing 3880:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1282): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/ExternalStorage( 4507): After updating volumes, found 1 active roots
D/Documents( 4468): Updating roots due to change at content://com.android.externalstorage.documents/root
D/Documents( 4468): Loading roots for com.android.providers.media.documents
D/Documents( 4468): Loading roots for com.google.android.apps.docs.storage
D/Documents( 4468): Update found 7 roots in 280ms
D/Documents( 4468): Used cached roots for com.android.providers.downloads.documents
D/Documents( 4468): Loading roots for com.android.externalstorage.documents
D/Documents( 4468): Used cached roots for com.android.providers.media.documents
D/Documents( 4468): Used cached roots for com.google.android.apps.docs.storage
D/Documents( 4468): Update found 7 roots in 7ms

```
