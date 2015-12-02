#### Test 52383621d5a0cb8_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
,V/AlarmManager( 1020): sending alarm Alarm{4311ba58 type 3 android}
--------- beginning of /dev/log/main
D/AndroidRuntime( 4070): 
D/AndroidRuntime( 4070): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4070): CheckJNI is OFF
D/dalvikvm( 4070): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4070): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4070): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4070): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4070): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4070): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4070): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4070): failed to load memtrack module: -2
D/AndroidRuntime( 4070): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1020): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4070
W/WindowManager( 1020): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1020): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4086 uid=10422 gids={50422, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4070): Shutting down VM
D/dalvikvm( 4070): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 1ms+0ms, total 3ms
W/ContextImpl( 1263): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1263): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4086): Binding Chromium to main looper Looper (main, tid 1) {41f1aa48}
I/LibraryLoader( 4086): Expected native library version number "",actual native library version number ""
I/chromium( 4086): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4086): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1020): Message: 20
D/BluetoothManagerService( 1020): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4277d4e8:true
I/Adreno-EGL( 4086): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4086): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4086): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4086): Local Branch: 
I/Adreno-EGL( 4086): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4086): Local Patches: NONE
I/Adreno-EGL( 4086): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
W/chromium( 4086): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 4086): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4086): VFY: unable to resolve virtual method 217: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4086): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4086): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4086): VFY: unable to resolve virtual method 212: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4086): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4086): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4086): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4086): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4086): VFY: unable to resolve virtual method 270: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4086): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4086): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4086): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4086): VFY: unable to resolve virtual method 228: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4086): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4086): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4086): VFY: unable to resolve virtual method 233: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4086): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4086): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4086): Enabling debug mode 0
,W/AwContents( 4086): nativeOnDraw failed; clearing to background color.
,V/AlarmManager( 1020): sending alarm Alarm{4406bf28 type 1 com.android.deskclock}
,I/ActivityManager( 1020): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4127 uid=10015 gids={50015, 1028}
,W/IInputConnectionWrapper( 4086): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1020): Displayed com.test.thalitest/.MainActivity,cp,ca,349
I/ActivityManager( 1020): Displayed com.test.thalitest/.MainActivity: +326ms (total +349ms)
,I/SFPerfTracer(  276):      triggers: (rate: 1:30) (compose: 0:4) (post: 0:1) (render: 0:6) (0:107 frames) (1:555)
,D/SFPerfTracer(  276):        layers: (0:12) (FocusedStackFrame: 0:9)* (StatusBar: 0:211)* (NavigationBar: 0:36)* (com.android.systemui.ImageWallpaper: 0:8)* (Starting com.motorola.ccc.ota: 0:34)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.InstallationActivity: 0:18)* (ElectronBeam: 0:27)* (com.test.thalitest/com.test.thalitest.MainActivity: 1:3)* 
,I/ActivityManager( 1020): Killing 3787:com.android.calendar/u0a7 (adj 15): empty #9
,W/ContextImpl( 1263): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,D/JsMessageQueue( 4086): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4086): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f1f158
,D/dalvikvm( 4086): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x41f1f158
,D/jxcore_app_log( 4086): JniHelper::setJavaVM(0x4156cfa8), pthread_self() = 1613824672
,D/JX-Cordova( 4086): jxcore cordova android initializing
I/dalvikvm( 4086): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.BtConnectorHelper.isBLEAdvertisingSupported
W/dalvikvm( 4086): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4086): VFY: replacing opcode 0x6e at 0x0045
,D/dalvikvm( 4086): GC_CONCURRENT freed 2789K, 17% free 14388K/17224K, paused 3ms+3ms, total 54ms
,D/dalvikvm( 4086): GC_FOR_ALLOC freed 212K, 17% free 14368K/17224K, paused 24ms, total 24ms
,D/dalvikvm( 4086): GC_FOR_ALLOC freed 189K, 17% free 14397K/17224K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4086): Grow heap (frag case) to 16.232MB for 146998-byte allocation
,D/dalvikvm( 4086): GC_FOR_ALLOC freed 258K, 17% free 14445K/17368K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4086): Grow heap (frag case) to 16.349MB for 220492-byte allocation
,D/dalvikvm( 4086): GC_FOR_ALLOC freed 374K, 18% free 14520K/17584K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4086): Grow heap (frag case) to 16.528MB for 330734-byte allocation
,D/dalvikvm( 4086): GC_FOR_ALLOC freed 576K, 19% free 14643K/17908K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4086): Grow heap (frag case) to 16.806MB for 496096-byte allocation
,D/dalvikvm( 4086): GC_FOR_ALLOC freed 879K, 20% free 14823K/18396K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4086): Grow heap (frag case) to 17.218MB for 744140-byte allocation
,D/dalvikvm( 4086): GC_FOR_ALLOC freed 1302K, 22% free 15085K/19124K, paused 26ms, total 26ms
,D/dalvikvm( 4086): GC_CONCURRENT freed 1672K, 20% free 15461K/19124K, paused 2ms+3ms, total 31ms
,D/dalvikvm( 4086): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 4086): GC_FOR_ALLOC freed 402K, 20% free 15422K/19124K, paused 25ms, total 26ms
,I/dalvikvm-heap( 4086): Grow heap (frag case) to 18.690MB for 1674304-byte allocation
,D/dalvikvm( 4086): GC_CONCURRENT freed 1676K, 23% free 15991K/20760K, paused 3ms+3ms, total 32ms
,D/dalvikvm( 4086): GC_FOR_ALLOC freed 1421K, 23% free 16086K/20760K, paused 29ms, total 30ms
,I/dalvikvm-heap( 4086): Grow heap (frag case) to 20.137MB for 2511452-byte allocation
,D/dalvikvm( 4086): GC_CONCURRENT freed 1915K, 28% free 16809K/23216K, paused 5ms+5ms, total 57ms
,D/dalvikvm( 4086): GC_CONCURRENT freed 2388K, 27% free 17024K/23216K, paused 1ms+6ms, total 41ms
,D/dalvikvm( 4086): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/dalvikvm( 4086): GC_FOR_ALLOC freed 605K, 28% free 16827K/23216K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4086): Grow heap (frag case) to 22.057MB for 3767174-byte allocation
,D/dalvikvm( 4086): GC_CONCURRENT freed 2702K, 33% free 18066K/26896K, paused 4ms+4ms, total 45ms
,W/jxcore-log( 4086): Initializing JXcore engine
,W/jxcore-log( 4086): JXcore engine is ready
,D/dalvikvm( 4086): GC_CONCURRENT freed 439K, 24% free 20656K/26896K, paused 5ms+2ms, total 34ms
,W/jxcore-log( 4086): Starting JXcore engine
,W/jxcore-log( 4086): Platform android
W/jxcore-log( 4086): 
,W/jxcore-log( 4086): Process ARCH arm
W/jxcore-log( 4086): 
,I/jxcore-log( 4086): JXcore Cordova bridge is ready!
I/jxcore-log( 4086): 
,W/jxcore-log( 4086): JXcore engine is started
,I/chromium( 4086): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 4086): Error!: Cannot find module '../server-address.js'
,E/jxcore  ( 4086): Stack: [{"_fileName":"module.js","_functionName":"Module._oldRes","_lineNumber":"776","_columnNumber":"15","_msg":"    at Module._oldRes@module.js:776:15"},{"_fileName":"module.js","_functionName":"Module._resolveFilename","_lineNumber":"1608","_columnNumber":"1","_msg":"    at Module._resolveFilename@module.js:1608:1"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"337","_columnNumber":"18","_msg":"    at Module._load@module.js:337:18"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"11","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:11:21"},{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"597","_columnNumber":"10","_msg":"    at Module.prototype._compile@module.js:597:10"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"}]
,I/chromium( 4086): [INFO:CONSOLE(37)] "App.js file failed to load : "Cannot find module '../server-address.js'\nError: Cannot find module '../server-address.js'\n    at Module._oldRes@module.js:776:15\n    at Module._resolveFilename@module.js:1608:1\n    at Module._load@module.js:337:18\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:11:21\n    at Module.prototype._compile@module.js:597:10\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager( 1020): Killing 3915:com.android.defcontainer/u0a13 (adj 15): empty #9
W/ContextImpl( 1263): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1263): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1263): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/OtaApp  ( 1554): [info] > Updatetime from metadata: 10
,D/Checkin ( 1554): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1554): [debug] > cancelling the previous pending intent set for install later
,I/OtaApp  ( 1554): [info] > next automatic install prompt (serverAnnoy) is scheduled in : 60 mins.
,D/Checkin ( 1554): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 1554): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,D/OtaApp  ( 1554): [debug] > Exception while retrieving software update alert statusjava.lang.NoSuchFieldException: SOFTWARE_UPDATE_ALERT_ENABLED
,W/IInputConnectionWrapper( 4086): showStatusIcon on inactive InputConnection
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
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{4245feb0 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{4213d8c0 type 3 android}
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
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{43db9ca8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{4406bc10 type 2 android}
,D/ChimeraCfgMgr( 1423): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1423): Module APK com.google.android.play.games already loaded
,I/dalvikvm( 1423): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.GmsNetworkTrafficStats.setThreadStatsTag
,W/dalvikvm( 1423): VFY: unable to resolve virtual method 1311: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1423): VFY: replacing opcode 0x6e at 0x0033
,I/dalvikvm( 1423): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.isUninstalledAppPossiblyUpdating
,W/dalvikvm( 1423): VFY: unable to resolve virtual method 499: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 1423): VFY: replacing opcode 0x6e at 0x000d
,V/AccountUtils( 1423): 0 accounts found with uca feature
,I/GamesSyncAdapter( 1423): Starting sync for 3a3529a
,W/GamesSyncAdapter( 1423): User is not G+ enabled. Aborting sync
,I/GamesSyncAdapter( 1423): Sync duration for 3a3529a: 17
,D/ChimeraCfgMgr( 1423): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1423): Module APK com.google.android.play.games already loaded
,D/dalvikvm( 1423): GC_CONCURRENT freed 1952K, 32% free 11875K/17224K, paused 4ms+6ms, total 44ms
I/dalvikvm( 1423): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.permission.PermissionUtils.getMissingPermissionGroups
W/dalvikvm( 1423): VFY: unable to resolve virtual method 349: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 1423): VFY: replacing opcode 0x6e at 0x0036
,D/ChimeraCfgMgr( 1423): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1423): Module APK com.google.android.play.games already loaded
,E/dalvikvm( 1423): Could not find class 'android.graphics.drawable.RippleDrawable', referenced from method com.google.android.gms.games.ui.util.UiUtils.constructButtonBackground
W/dalvikvm( 1423): VFY: unable to resolve new-instance 177 (Landroid/graphics/drawable/RippleDrawable;) in Lcom/google/android/gms/games/ui/util/UiUtils;
,D/dalvikvm( 1423): VFY: replacing opcode 0x22 at 0x0013
,D/dalvikvm( 1423): DexOpt: unable to opt direct call 0x0397 at 0x1a in Lcom/google/android/gms/games/ui/util/UiUtils;.constructButtonBackground
,D/dalvikvm( 1423): Note: class Lcom/google/android/gms/games/internal/IGamesService$Stub; has 207 unimplemented (abstract) methods
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{43284d30 type 2 android}
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
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{42051a18 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{424390d0 type 2 android}
,V/AlarmManager( 1020): sending alarm Alarm{43dc10a8 type 3 android}
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
,V/AlarmManager( 1020): sending alarm Alarm{44066b10 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{4312ece8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{43daa878 type 3 android}
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1020): sending alarm Alarm{4213e768 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{442c4ff0 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{43ab0398 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{44091708 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{43c466c8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{44061930 type 2 android}
,V/AlarmManager( 1020): sending alarm Alarm{44061a08 type 0 com.google.android.gms}
,D/ConnectivityService( 1020): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1020): Done.
,D/ConnectivityService( 1020): Setting timer for 720seconds
,I/EventLogService( 1423): Aggregate from 1449056392300 (log), 1449055281357 (data)
,D/ConnectivityService( 1020): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/ModemStatsDSDetect( 1202): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1202): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/ModemStatsDSDetect( 1202): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,V/AlarmManager( 1020): sending alarm Alarm{4275b378 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{431c3b60 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{430b2b08 type 1 com.android.deskclock}
,V/AlarmManager( 1020): sending alarm Alarm{44072400 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{41fd3178 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{4314cb60 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{440a3660 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{43337388 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{43d2dc78 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{428866b8 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{43ce3078 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{4311ac40 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{43d53b48 type 3 android}
,I/ProcessStatsService( 1020): Prepared write state in 26ms
,I/ProcessStatsService( 1020): Prepared write state in 23ms
,I/ProcessStatsService( 1020): Pruning old procstats: /data/system/procstats/state-2015-12-01-12-15-54.bin
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
,V/AlarmManager( 1020): sending alarm Alarm{43abfb50 type 3 android}
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
,V/AlarmManager( 1020): sending alarm Alarm{43ac15c0 type 3 android}
,I/ActivityManager( 1020): Killing 3503:com.motorola.MotGallery2/u0a33 (adj 15): empty for 1843s
,W/ContextImpl( 1263): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1020): Killing 3970:com.google.android.partnersetup/u0a25 (adj 15): empty for 1843s
,I/ActivityManager( 1020): Killing 3487:android.process.acore/u0a10 (adj 15): empty for 1843s
,W/ContextImpl( 1263): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,W/ContextImpl( 1263): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/AlarmManager( 1020): sending alarm Alarm{43d45440 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{43abcdb0 type 3 android}
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1020): sending alarm Alarm{432850d0 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{430b2be0 type 3 android}
,V/AlarmManager( 1020): sending alarm Alarm{430b2cb8 type 2 com.motorola.ccc.cce}
,V/AlarmManager( 1020): sending alarm Alarm{430b2d08 type 3 com.google.android.gms}
,V/AlarmManager( 1020): sending alarm Alarm{430b2d58 type 2 android}
,V/AlarmManager( 1020): sending alarm Alarm{430b2da8 type 2 com.google.android.gms}
,V/AlarmManager( 1020): sending alarm Alarm{43ab8e38 type 1 com.android.deskclock}
,D/CCE     ( 1554): Registering with Alarm Manager to restart CCE
,D/ConnectivityService( 1020): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService( 1020): Done.
,D/ConnectivityService( 1020): Setting timer for 720seconds
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService( 1020): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/SBar.NetworkController( 1083): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/ModemStatsDSDetect( 1202): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/SBar.NetworkController( 1083): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1202): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
,I/ModemStatsDSDetect( 1202): onReceive() - done, currentInetCondition=100
,I/SBar.NetworkController( 1083): updateTelephonySignalStrength:  No service
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
,I/MDMCTBK (  275): NetlinkHandler, power_supply subsys
I/MDMCTBK (  275): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  275): checkDefaultInst, current pid is = 275
I/MDMCTBK (  275): checkDefaultInst, pid match
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  275): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  275): MdmCutbackHndler,Could not open ''
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 4281): 
D/AndroidRuntime( 4281): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4281): CheckJNI is OFF
D/dalvikvm( 4281): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4281): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4281): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4281): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4281): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4281): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4281): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4281): failed to load memtrack module: -2
D/AndroidRuntime( 4281): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10422 user=-1: uninstall pkg
I/ActivityManager( 1020): Killing 4086:com.test.thalitest/u0a422 (adj 15): stop com.test.thalitest
W/ContextImpl( 1263): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
W/PackageSettings( 1020): Skipping PackageSetting{421dc628 com.example.hello/10416} due to missing metadata
I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10422 user=0: pkg removed
D/dalvikvm( 2284): GC_EXPLICIT freed 5235K, 45% free 9645K/17224K, paused 1ms+5ms, total 53ms
D/dalvikvm( 1020): GC_CONCURRENT freed 2109K, 65% free 18131K/50480K, paused 3ms+21ms, total 102ms
D/dalvikvm( 2316): GC_EXPLICIT freed 6475K, 40% free 10480K/17224K, paused 2ms+5ms, total 105ms
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
I/LatinIME:LogUtils( 1215): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/LatinIME:LogUtils( 1215): Dictionary info: dictionary = main:en_gb ; version = 45 ; date = 1400750568
I/ActivityManager( 1020): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4307 uid=10010 gids={50010, 3003, 1028, 1015, 1023}
W/GeofencerStateMachine( 1236): Ignoring removeGeofence because network location is disabled.
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
I/LatinIME:LogUtils( 1215): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449058511
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
D/dalvikvm( 1305): GC_EXPLICIT freed 3237K, 33% free 11594K/17224K, paused 2ms+6ms, total 91ms
I/Launcher( 1305): Deferring update until onResume
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "sms"
I/LatinIME:LogUtils( 1215): Dictionary info: dictionary = PersonalizationDictionary.en_GB ; version = 1447271973 ; date = 1449058511
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "smsto"
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mms"
I/PackageManager( 1020): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1020):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1020):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1020):   Scheme: "mmsto"
I/Launcher( 1305): Deferring update until onResume
D/dalvikvm( 1347): GC_EXPLICIT freed 1933K, 38% free 10844K/17224K, paused 2ms+6ms, total 43ms
D/BackupManagerService( 1020): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1020): removePackageParticipantsLocked: uid=10422 #1
D/VoicemailCleanupService( 4307): Cleaning up data for package: com.test.thalitest
I/ActivityManager( 1020): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4323 uid=10033 gids={50033, 3003, 1028, 1015}
D/dalvikvm( 1020): GC_EXPLICIT freed 914K, 65% free 17983K/50480K, paused 9ms+15ms, total 199ms
I/InternalIcingCorporaPro( 2316): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager( 1020): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4340 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
I/ActivityManager( 1020): Killing 3519:com.google.android.apps.plus/u0a90 (adj 15): empty for 2035s
W/ContextImpl( 1263): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
W/ContextImpl( 4340): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/ActivityManager( 1020): Killing 3552:com.android.vending/u0a38 (adj 15): empty for 2020s
W/ContextImpl( 1263): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ContactLocale( 4307): AddressBook Labels [en_GB]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
D/PackageBroadcastService( 1423): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1423): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1423): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1423): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1423): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1423): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1423): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1347): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1347): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager( 1020): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4360 uid=10038 gids={50038, 3003, 1028, 1015}
I/PeopleContactsSync( 1423): CP2 sync disabled
I/Icing   ( 1423): doRemovePackageData com.test.thalitest
D/gH_CompatibleDatabase( 1423): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1423): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1423): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1423): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1423): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1423): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1423): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1423): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1423): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1423): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1423): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1423): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1423): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/AndroidRuntime( 4281): Shutting down VM
D/dalvikvm( 4281): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+1ms, total 3ms
I/InternalIcingCorporaPro( 2316): UpdateCorporaTask done [took 191 ms] updated apps [took 191 ms] 
I/dalvikvm( 4360): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzi
W/dalvikvm( 4360): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 4360): VFY: replacing opcode 0x6e at 0x000e
D/Finsky  ( 4360): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/dalvikvm( 4360): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulInstallMessage
W/dalvikvm( 4360): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 4360): VFY: replacing opcode 0x6e at 0x01d3
I/dalvikvm( 4360): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method com.google.android.finsky.appstate.PackageManagerRepository.canLaunch
W/dalvikvm( 4360): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/dalvikvm( 4360): VFY: replacing opcode 0x6e at 0x000a
D/Finsky  ( 4360): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dalvikvm( 4360): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.utils.DeviceManagementHelper.updateCachedValues
W/dalvikvm( 4360): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
D/dalvikvm( 4360): VFY: replacing opcode 0x6e at 0x0032
W/Settings( 4360): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4360): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/dalvikvm( 4360): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4360): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4360): VFY: replacing opcode 0x6e at 0x013c
I/dalvikvm( 4360): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4360): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4360): VFY: replacing opcode 0x6e at 0x037f
I/dalvikvm( 4360): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4360): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4360): VFY: replacing opcode 0x6e at 0x0385
I/ActivityManager( 1020): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=4398 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
D/dalvikvm(  277): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 1ms+2ms, total 19ms
I/dalvikvm( 4360): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4360): VFY: unable to resolve virtual method 9030: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
D/dalvikvm( 4360): VFY: replacing opcode 0x6e at 0x0019
D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 17ms
D/dalvikvm(  277): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 18ms
D/Ads     ( 4360): Skipping gmscore version check
I/ActivityManager( 1020): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4413 uid=10058 gids={50058}
D/Finsky  ( 4360): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4360): [1] Libraries$2.run: Finished loading 1 libraries.
I/dalvikvm( 4360): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4360): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 4360): VFY: replacing opcode 0x6e at 0x0013
E/SQLiteDatabase( 4398): Failed to open database '/data/data/com.android.providers.media/databases/external.db'.
E/SQLiteDatabase( 4398): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4398): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4398): 	at com.android.providers.media.MediaProvider$DatabaseHelper.getWritableDatabase(MediaProvider.java:441)
E/SQLiteDatabase( 4398): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:5400)
E/SQLiteDatabase( 4398): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:645)
E/SQLiteDatabase( 4398): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 4398): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 4398): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4855)
E/SQLiteDatabase( 4398): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4450)
E/SQLiteDatabase( 4398): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4390)
E/SQLiteDatabase( 4398): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4398): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/SQLiteDatabase( 4398): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4398): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4398): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 4398): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4398): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4398): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 4398): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 4398): 	at dalvik.system.NativeStart.main(Native Method)
E/SharedPreferencesImpl( 4360): Couldn't rename file /data/data/com.android.vending/shared_prefs/finsky.xml to backup file /data/data/com.android.vending/shared_prefs/finsky.xml.bak
E/MediaProvider( 4398): failed to open database external.db
E/MediaProvider( 4398): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/MediaProvider( 4398): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/MediaProvider( 4398): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/MediaProvider( 4398): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/MediaProvider( 4398): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/MediaProvider( 4398): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/MediaProvider( 4398): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/MediaProvider( 4398): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/MediaProvider( 4398): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/MediaProvider( 4398): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/MediaProvider( 4398): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/MediaProvider( 4398): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/MediaProvider( 4398): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/MediaProvider( 4398): 	at com.android.providers.media.MediaProvider$DatabaseHelper.getWritableDatabase(MediaProvider.java:441)
E/MediaProvider( 4398): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:5400)
E/MediaProvider( 4398): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:645)
E/MediaProvider( 4398): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/MediaProvider( 4398): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/MediaProvider( 4398): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4855)
E/MediaProvider( 4398): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4450)
E/MediaProvider( 4398): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4390)
E/MediaProvider( 4398): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/MediaProvider( 4398): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/MediaProvider( 4398): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/MediaProvider( 4398): 	at android.os.Looper.loop(Looper.java:136)
E/MediaProvider( 4398): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/MediaProvider( 4398): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/MediaProvider( 4398): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/MediaProvider( 4398): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/MediaProvider( 4398): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/MediaProvider( 4398): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteDatabase( 4398): Failed to open database '/data/data/com.android.providers.media/databases/external.db'.
E/SQLiteDatabase( 4398): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4398): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4398): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4398): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2337)
E/SQLiteDatabase( 4398): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:5409)
E/SQLiteDatabase( 4398): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:645)
E/SQLiteDatabase( 4398): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 4398): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 4398): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4855)
E/SQLiteDatabase( 4398): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4450)
E/SQLiteDatabase( 4398): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4390)
E/SQLiteDatabase( 4398): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteDatabase( 4398): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/SQLiteDatabase( 4398): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4398): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4398): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 4398): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4398): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4398): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 4398): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 4398): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4398): Couldn't open external.db for writing (will try read-only):
E/SQLiteOpenHelper( 4398): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4398): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4398): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4398): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4398): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4398): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4398): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4398): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteOpenHelper( 4398): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteOpenHelper( 4398): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 4398): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteOpenHelper( 4398): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4398): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4398): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2337)
E/SQLiteOpenHelper( 4398): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:5409)
E/SQLiteOpenHelper( 4398): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:645)
E/SQLiteOpenHelper( 4398): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteOpenHelper( 4398): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteOpenHelper( 4398): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4855)
E/SQLiteOpenHelper( 4398): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4450)
E/SQLiteOpenHelper( 4398): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4390)
E/SQLiteOpenHelper( 4398): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/SQLiteOpenHelper( 4398): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/SQLiteOpenHelper( 4398): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4398): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteOpenHelper( 4398): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteOpenHelper( 4398): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4398): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4398): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteOpenHelper( 4398): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteOpenHelper( 4398): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteLog( 4398): (14) cannot open file at line 28970 of [00bb9c9ce4]
E/SQLiteLog( 4398): (14) os_unix.c:28970: (30) open(/data/data/com.android.providers.media/databases/external.db-shm) - 
E/SQLiteLog( 4398): (14) statement aborts at 0: [PRAGMA user_version;] unable to open database file
D/AndroidRuntime( 4398): Shutting down VM
W/dalvikvm( 4398): threadid=1: thread exiting with uncaught exception (group=0x4164bd40)
E/AndroidRuntime( 4398): FATAL EXCEPTION: main
E/AndroidRuntime( 4398): Process: android.process.media, PID: 4398
E/AndroidRuntime( 4398): java.lang.RuntimeException: Unable to get provider com.android.providers.media.MediaProvider: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
E/AndroidRuntime( 4398): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4858)
E/AndroidRuntime( 4398): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4450)
E/AndroidRuntime( 4398): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4390)
E/AndroidRuntime( 4398): 	at android.app.ActivityThread.access$1500(ActivityThread.java:139)
E/AndroidRuntime( 4398): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1270)
E/AndroidRuntime( 4398): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4398): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4398): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4398): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4398): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4398): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4398): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4398): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4398): Caused by: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
E/AndroidRuntime( 4398): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLong(Native Method)
E/AndroidRuntime( 4398): 	at android.database.sqlite.SQLiteConnection.executeForLong(SQLiteConnection.java:598)
E/AndroidRuntime( 4398): 	at android.database.sqlite.SQLiteSession.executeForLong(SQLiteSession.java:652)
E/AndroidRuntime( 4398): 	at android.database.sqlite.SQLiteStatement.simpleQueryForLong(SQLiteStatement.java:107)
E/AndroidRuntime( 4398): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:825)
E/AndroidRuntime( 4398): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:813)
E/AndroidRuntime( 4398): 	at android.database.sqlite.SQLiteDatabase.getVersion(SQLiteDatabase.java:862)
E/AndroidRuntime( 4398): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:242)
E/AndroidRuntime( 4398): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/AndroidRuntime( 4398): 	at com.android.providers.media.MediaProvider.query(MediaProvider.java:2337)
E/AndroidRuntime( 4398): 	at com.android.providers.media.MediaProvider.attachVolume(MediaProvider.java:5409)
E/AndroidRuntime( 4398): 	at com.android.providers.media.MediaProvider.onCreate(MediaProvider.java:645)
E/AndroidRuntime( 4398): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 4398): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 4398): 	at android.app.ActivityThread.installProvider(ActivityThread.java:4855)
E/AndroidRuntime( 4398): 	... 12 more
D/Documents( 4413): Loading roots for com.android.providers.downloads.documents
I/Process ( 4398): Sending signal. PID: 4398 SIG: 9
E/DropBoxManagerService( 1020): Can't write: system_app_crash
E/DropBoxManagerService( 1020): java.io.FileNotFoundException: /data/system/dropbox/drop94.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1020): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1020): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1020): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1020): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1020): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1020): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1020): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1020): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1020): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1020): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1020): 	... 5 more
E/SQLiteDatabase( 4413): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4413): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4413): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4413): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4413): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4413): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4413): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4413): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4413): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4413): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4413): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4413): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/SQLiteDatabase( 4413): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4413): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4413): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4413): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4413): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4413): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 4413): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/SQLiteDatabase( 4413): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4413): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/SQLiteDatabase( 4413): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/SQLiteDatabase( 4413): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/SQLiteDatabase( 4413): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4413): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4413): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/SQLiteDatabase( 4413): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4413): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4413): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/SQLiteDatabase( 4413): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/SQLiteDatabase( 4413): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 4413): Shutting down VM
W/dalvikvm( 4413): threadid=1: thread exiting with uncaught exception (group=0x4164bd40)
E/AndroidRuntime( 4413): FATAL EXCEPTION: main
E/AndroidRuntime( 4413): Process: com.android.documentsui, PID: 4413
E/AndroidRuntime( 4413): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4413): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2441)
E/AndroidRuntime( 4413): 	at android.app.ActivityThread.access$1700(ActivityThread.java:139)
E/AndroidRuntime( 4413): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1286)
E/AndroidRuntime( 4413): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4413): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4413): 	at android.app.ActivityThread.main(ActivityThread.java:5086)
E/AndroidRuntime( 4413): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4413): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4413): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:785)
E/AndroidRuntime( 4413): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:601)
E/AndroidRuntime( 4413): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4413): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4413): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4413): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4413): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4413): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4413): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4413): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4413): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/AndroidRuntime( 4413): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/AndroidRuntime( 4413): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4413): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1073)
E/AndroidRuntime( 4413): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4413): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4413): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4413): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4413): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4413): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/AndroidRuntime( 4413): 	at android.content.ContentResolver.call(ContentResolver.java:1355)
E/AndroidRuntime( 4413): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4413): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2434)
E/AndroidRuntime( 4413): 	... 10 more
I/ActivityManager( 1020): Process android.process.media (pid 4398) has died.
W/ActivityManager( 1020): Scheduling restart of crashed service com.android.providers.downloads/.DownloadService in 1000ms
I/ActivityManager( 1020): Start proc android.process.media for restart android.process.media: pid=4429 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
I/Process ( 4413): Sending signal. PID: 4413 SIG: 9
E/DropBoxManagerService( 1020): Can't write: system_app_crash
E/DropBoxManagerService( 1020): java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1020): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 1020): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 1020): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 1020): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1020): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 1020): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10223)
E/DropBoxManagerService( 1020): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1020): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1020): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 1020): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 1020): 	... 5 more
I/ActivityManager( 1020): Process com.android.documentsui (pid 4413) has died.

```
