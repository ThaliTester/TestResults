#### Test 563583788793eb6_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/main,
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 4296): 
D/AndroidRuntime( 4296): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4296): CheckJNI is OFF
D/dalvikvm( 4296): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4296): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4296): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4296): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4296): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4296): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4296): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4296): failed to load memtrack module: -2
D/AndroidRuntime( 4296): Calling main entry com.android.commands.am.Am
--------- beginning of /dev/log/system
I/ActivityManager( 1017): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4296
W/WindowManager( 1017): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1017): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4320 uid=10124 gids={50124, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4296): Shutting down VM
D/dalvikvm( 4296): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+1ms, total 3ms
W/ContextImpl( 1290): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1290): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4320): Binding Chromium to main looper Looper (main, tid 1) {41fdeab0}
I/LibraryLoader( 4320): Expected native library version number "",actual native library version number ""
I/chromium( 4320): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4320): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1017): Message: 20
D/BluetoothManagerService( 1017): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4419a1a0:true
I/Adreno-EGL( 4320): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4320): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4320): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4320): Local Branch: 
I/Adreno-EGL( 4320): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4320): Local Patches: NONE
I/Adreno-EGL( 4320): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4320): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4320): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4320): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4320): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4320): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4320): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4320): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4320): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4320): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4320): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4320): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4320): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4320): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4320): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4320): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4320): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4320): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4320): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4320): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4320): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4320): Enabling debug mode 0
I/Keyboard.Facilitator( 1219): onFinishInput()
W/AwContents( 4320): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 4320): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1017): Displayed com.test.thalitest/.MainActivity,cp,ca,392
I/ActivityManager( 1017): Displayed com.test.thalitest/.MainActivity: +368ms (total +392ms)
,D/JsMessageQueue( 4320): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4320): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fe2f60
,D/dalvikvm( 4320): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41fe2f60
,D/jxcore_app_log( 4320): JniHelper::setJavaVM(0x4162cfa8), pthread_self() = 1615946864
,I/chromium( 4320): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/dalvikvm( 4320): GC_CONCURRENT freed 2660K, 16% free 14529K/17224K, paused 3ms+4ms, total 42ms
,D/dalvikvm( 4320): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/dalvikvm( 4320): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/dalvikvm( 4320): GC_FOR_ALLOC freed 422K, 14% free 14893K/17224K, paused 28ms, total 28ms
,D/dalvikvm( 4320): GC_FOR_ALLOC freed 104K, 14% free 14900K/17224K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4320): Grow heap (frag case) to 16.644MB for 63974-byte allocation
,D/dalvikvm( 4320): GC_FOR_ALLOC freed 126K, 14% free 14919K/17288K, paused 28ms, total 29ms
,I/dalvikvm-heap( 4320): Grow heap (frag case) to 16.694MB for 95956-byte allocation
,D/dalvikvm( 4320): GC_FOR_ALLOC freed 179K, 14% free 14955K/17384K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4320): Grow heap (frag case) to 16.774MB for 143930-byte allocation
,D/dalvikvm( 4320): GC_FOR_ALLOC freed 253K, 15% free 15001K/17528K, paused 27ms, total 28ms
,I/dalvikvm-heap( 4320): Grow heap (frag case) to 16.888MB for 215890-byte allocation
,D/dalvikvm( 4320): GC_FOR_ALLOC freed 367K, 16% free 15076K/17740K, paused 27ms, total 27ms
,I/dalvikvm-heap( 4320): Grow heap (frag case) to 17.064MB for 323830-byte allocation
,D/dalvikvm( 4320): GC_FOR_ALLOC freed 568K, 16% free 15196K/18060K, paused 27ms, total 27ms
,D/dalvikvm( 4320): GC_FOR_ALLOC freed 862K, 15% free 15372K/18060K, paused 27ms, total 28ms
,I/dalvikvm-heap( 4320): Grow heap (frag case) to 17.739MB for 728606-byte allocation
,D/dalvikvm( 4320): GC_FOR_ALLOC freed 1282K, 17% free 15627K/18772K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4320): Grow heap (frag case) to 18.335MB for 1092904-byte allocation
,D/dalvikvm( 4320): GC_CONCURRENT freed 1888K, 20% free 16029K/19840K, paused 2ms+5ms, total 43ms
,D/dalvikvm( 4320): GC_FOR_ALLOC freed 162K, 20% free 15946K/19840K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4320): Grow heap (frag case) to 19.168MB for 1639352-byte allocation
,D/dalvikvm( 4320): GC_CONCURRENT freed 1844K, 23% free 16549K/21444K, paused 3ms+4ms, total 46ms
,D/dalvikvm( 4320): GC_FOR_ALLOC freed 1076K, 23% free 16526K/21444K, paused 30ms, total 31ms
,I/dalvikvm-heap( 4320): Grow heap (frag case) to 20.516MB for 2459024-byte allocation
,D/dalvikvm( 4320): GC_CONCURRENT freed 377K, 21% free 18899K/23848K, paused 4ms+7ms, total 56ms
,D/dalvikvm( 4320): GC_FOR_ALLOC freed 4139K, 27% free 17553K/23848K, paused 37ms, total 38ms
,I/dalvikvm-heap( 4320): Grow heap (frag case) to 22.692MB for 3688532-byte allocation
,D/dalvikvm( 4320): GC_CONCURRENT freed 294K, 24% free 20983K/27452K, paused 5ms+5ms, total 51ms
,D/dalvikvm( 4320): GC_FOR_ALLOC freed 4460K, 32% free 18679K/27452K, paused 35ms, total 40ms
,W/jxcore-log( 4320): Initializing JXcore engine
,W/jxcore-log( 4320): JXcore engine is ready
,D/dalvikvm( 4320): GC_CONCURRENT freed 427K, 22% free 21477K/27452K, paused 2ms+3ms, total 33ms
,D/dalvikvm( 4320): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 4320): WAIT_FOR_CONCURRENT_GC blocked 26ms
,W/jxcore-log( 4320): Starting JXcore engine
,W/jxcore-log( 4320): Platform android
W/jxcore-log( 4320): 
,W/jxcore-log( 4320): Process ARCH arm
W/jxcore-log( 4320): 
,I/jxcore-log( 4320): JXcore Cordova bridge is ready!
I/jxcore-log( 4320): 
,W/jxcore-log( 4320): JXcore engine is started
,E/jxcore  ( 4320): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4320): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4320): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager( 1017): Killing 4025:com.android.calendar/u0a7 (adj 15): empty #9
W/ContextImpl( 1290): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1290): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1290): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 1589): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 1589): [info] > DownloadActivity, handling (Blur_Version.21.11.56.peregrine_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 1589): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1589): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 1589): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 1589): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1589): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1589): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,I/Keyboard.Facilitator( 1219): onFinishInput()
,W/IInputConnectionWrapper( 4320): showStatusIcon on inactive InputConnection
,V/AlarmManager( 1017): sending alarm Alarm{441d8ca0 type 3 android}
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
,I/Keyboard.Facilitator.LanguageModelFlusher( 1219): run()
,I/Keyboard.Facilitator( 1219): flushDynamicLanguageModels()
,I/ConfigService( 1232): onCreate
,I/ConfigService( 1232): onDestroy
,V/AlarmManager( 1017): sending alarm Alarm{440deb40 type 3 android}
,I/MDMCTBK (  273): NetlinkHandler, power_supply subsys
I/MDMCTBK (  273): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  273): checkDefaultInst, current pid is = 273
I/MDMCTBK (  273): checkDefaultInst, pid match
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  273): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  273): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1017): sending alarm Alarm{440b1818 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{43cc2bf8 type 1 com.android.deskclock}
,I/ActivityManager( 1017): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4387 uid=10015 gids={50015, 1028}
,I/ActivityManager( 1017): Killing 4136:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1290): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
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
,V/AlarmManager( 1017): sending alarm Alarm{440a8540 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{440733c8 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{44042cd8 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{440014a0 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{43fbe238 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{437168f8 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{436f02c0 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{43cc2b38 type 2 android}
,D/ConnectivityService( 1017): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1017): sending alarm Alarm{43cc26e0 type 2 com.google.android.gms}
,D/ConnectivityService( 1017): Done.
,D/ConnectivityService( 1017): Setting timer for 720seconds
,I/PhenotypeConfigurator( 1232): Scheduling Phenotype for one-off execution 7194 seconds from now (1453135057784)
,D/GetConfigurationSnapshotOperation( 1232): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1232): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1232): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1232): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1232): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 1232): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 1232): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 1232): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 1232): Using platform SSLCertificateSocketFactory
,D/ConnectivityService( 1017): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
I/SBar.NetworkController( 1091): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/ModemStatsDSDetect( 1207): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1091): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1207): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1207): onReceive() - done, currentInetCondition=100
,V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1351): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 1351): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,E/dalvikvm( 1351): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
W/dalvikvm( 1351): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
,D/dalvikvm( 1351): VFY: replacing opcode 0x1f at 0x0011
,I/dalvikvm( 1351): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1351): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1351): VFY: replacing opcode 0x6e at 0x003d
,D/dalvikvm( 1232): GC_CONCURRENT freed 1625K, 34% free 11474K/17224K, paused 3ms+14ms, total 57ms
,E/DataBuffer( 1232): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@421cabd0)
E/DataBuffer( 1232): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@420c63d0)
E/DataBuffer( 1232): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@421ccc20)
E/DataBuffer( 1232): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@420bb538)
,E/DataBuffer( 1232): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42362678)
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
,V/AlarmManager( 1017): sending alarm Alarm{4409ed90 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{44076f80 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{4406b230 type 3 android}
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
,I/MDMCTBK (  273): checkDefaultInst, pid match
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
,V/AlarmManager( 1017): sending alarm Alarm{44061b08 type 3 android}
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
,V/AlarmManager( 1017): sending alarm Alarm{4405c008 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{4404cf48 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{44049e08 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{44048d18 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{4409e4c0 type 1 com.android.deskclock}
,V/AlarmManager( 1017): sending alarm Alarm{4409dec8 type 2 com.motorola.ccc.cce}
I/PollingManager( 1589): alarm fired!
D/Checkin ( 1589): publish the event [tag = MOT_CCE event name = LOG]
D/PollingManager( 1589): now: 1396772 ,futureTime: 38869646
,D/PollingManager( 1589): Polling alarm set to expire at: 38869646 Current Time: 1396773
V/AlarmManager( 1017): sending alarm Alarm{4409d988 type 0 com.google.android.gms}
,I/EventLogService( 1722): Aggregate from 1453134162185 (log), 1453133701069 (data)
,V/AlarmManager( 1017): sending alarm Alarm{4402aec0 type 3 android}
,V/AlarmManager( 1017): sending alarm Alarm{4400f4d8 type 3 android}
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 4473): 
D/AndroidRuntime( 4473): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4473): CheckJNI is OFF
D/dalvikvm( 4473): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4473): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4473): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4473): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4473): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4473): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4473): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4473): failed to load memtrack module: -2
D/AndroidRuntime( 4473): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10124 user=-1: uninstall pkg
I/ActivityManager( 1017): Killing 4320:com.test.thalitest/u0a124 (adj 11): stop com.test.thalitest
W/ContextImpl( 1290): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10124 user=0: pkg removed
D/dalvikvm( 2349): GC_EXPLICIT freed 5362K, 44% free 9647K/17224K, paused 2ms+5ms, total 53ms
I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1219): resetDictionaries() : en_GB
W/GeofencerStateMachine( 1232): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator.DecoderInitializer( 1219): run()
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "sms"
D/VoicemailCleanupService( 1171): Cleaning up data for package: com.test.thalitest
I/Decoder ( 1219): createOrResetDecoder
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "smsto"
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mms"
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mmsto"
D/dalvikvm( 2382): GC_EXPLICIT freed 2776K, 43% free 9818K/17224K, paused 2ms+3ms, total 149ms
D/dalvikvm( 1316): GC_EXPLICIT freed 3258K, 33% free 11598K/17224K, paused 2ms+4ms, total 139ms
I/Launcher( 1316): Deferring update until onResume
D/dalvikvm( 1722): GC_EXPLICIT freed 1309K, 31% free 11983K/17224K, paused 3ms+6ms, total 215ms
D/dalvikvm( 1017): GC_EXPLICIT freed 25773K, 65% free 18884K/53644K, paused 4ms+14ms, total 232ms
D/dalvikvm( 1017): WAIT_FOR_CONCURRENT_GC blocked 35ms
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "sms"
I/ConfigService( 1232): onCreate
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "smsto"
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mms"
I/PackageManager( 1017): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1017):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1017):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1017):   Scheme: "mmsto"
I/Launcher( 1316): Deferring update until onResume
I/InternalIcingCorporaPro( 2382): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager( 1017): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4504 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
D/dalvikvm(  276): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 1ms+2ms, total 22ms
D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+2ms, total 19ms
D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1017): removePackageParticipantsLocked: uid=10124 #1
I/Keyboard.Facilitator.MainLanguageModelLoader( 1219): run()
W/ContextImpl( 4504): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
D/dalvikvm(  276): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 2ms+3ms, total 20ms
I/dalvikvm( 3662): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3662): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 3662): VFY: replacing opcode 0x6e at 0x0013
I/Keyboard.Facilitator.MainLanguageModelLoader( 1219): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1.apk (offset=5018356, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1219): run()
D/ChimeraCfgMgr( 1722): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1722): Module APK com.google.android.play.games already loaded
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1219): run() : Loading LM = contacts
D/PackageBroadcastService( 1722): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1722): Clearing selected account for com.test.thalitest
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1219): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1219): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1219): run() : Loaded File = UserHistory.en_GB.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1219): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1219): run() : Missing File = Personal.en_GB.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1219): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1219): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1219): run()
I/StatsUtilsManager( 1219): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1219): shouldRecordStats() = Too Soon
I/LocationSettingsChecker( 1722): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1722): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1722): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1351): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1351): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 1722): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1722): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1722): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1722): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1722): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1722): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1722): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1722): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1722): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1722): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1722): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1722): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1722): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/Icing   ( 1722): doRemovePackageData com.test.thalitest
I/InternalIcingCorporaPro( 2382): UpdateCorporaTask done [took 188 ms] updated apps [took 188 ms] 
D/dalvikvm( 1017): GC_EXPLICIT freed 684K, 66% free 18739K/53644K, paused 6ms+17ms, total 255ms
I/ActivityManager( 1017): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4532 uid=10058 gids={50058}
D/Documents( 4532): Loading roots for com.android.providers.downloads.documents
D/AndroidRuntime( 4473): Shutting down VM
D/dalvikvm( 4473): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 0ms+0ms, total 3ms
I/ActivityManager( 1017): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=4547 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
I/ActivityManager( 1017): Killing 4173:com.google.android.partnersetup/u0a25 (adj 15): empty #9
W/ContextImpl( 1290): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1017): Killing 4387:com.android.deskclock/u0a15 (adj 15): empty #9
W/ContextImpl( 1290): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/Documents( 4532): Loading roots for com.android.externalstorage.documents
D/dalvikvm( 4547): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x41fde4a0, skipping init
I/openssl ( 4547): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4547): Crypto mode 0 already enabled
I/ActivityManager( 1017): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4564 uid=10020 gids={50020, 1028, 1015, 1023}
I/ActivityManager( 1017): Killing 3630:com.motorola.MotGallery2/u0a33 (adj 15): empty #9
W/ContextImpl( 1290): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
D/ExternalStorage( 4564): After updating volumes, found 1 active roots
D/Documents( 4532): Updating roots due to change at content://com.android.externalstorage.documents/root
D/Documents( 4532): Loading roots for com.android.providers.media.documents
D/Documents( 4532): Loading roots for com.google.android.apps.docs.storage
D/Documents( 4532): Update found 7 roots in 216ms
D/Documents( 4532): Used cached roots for com.android.providers.downloads.documents
D/Documents( 4532): Loading roots for com.android.externalstorage.documents
D/Documents( 4532): Used cached roots for com.android.providers.media.documents
D/Documents( 4532): Used cached roots for com.google.android.apps.docs.storage
D/Documents( 4532): Update found 7 roots in 8ms

```
