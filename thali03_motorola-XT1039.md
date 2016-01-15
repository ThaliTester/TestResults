#### Test 561517803567b2a_thali03_motorola-XT1039 Logs


```
--------- beginning of /dev/log/system
,V/AlarmManager( 1019): sending alarm Alarm{43d39948 type 3 android}
--------- beginning of /dev/log/main
D/AndroidRuntime( 4606): 
D/AndroidRuntime( 4606): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4606): CheckJNI is OFF
D/dalvikvm( 4606): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4606): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4606): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4606): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4606): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4606): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4606): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4606): failed to load memtrack module: -2
D/AndroidRuntime( 4606): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1019): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4606
W/WindowManager( 1019): Not okToDisplay, so not showing Starting Window
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4622 uid=10111 gids={50111, 3003, 3001, 3002, 1028, 1015}
D/AndroidRuntime( 4606): Shutting down VM
D/dalvikvm( 4606): GC_CONCURRENT freed 95K, 14% free 602K/700K, paused 0ms+0ms, total 3ms
W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/WebViewChromiumFactoryProvider( 4622): Binding Chromium to main looper Looper (main, tid 1) {42905f10}
I/LibraryLoader( 4622): Expected native library version number "",actual native library version number ""
I/chromium( 4622): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4622): Initializing chromium process, renderers=0
D/BluetoothManagerService( 1019): Message: 20
D/BluetoothManagerService( 1019): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44a1ccb8:true
I/Adreno-EGL( 4622): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018_msm8226_LNX.LA.3.5.1_RB1__release_AU ()
I/Adreno-EGL( 4622): OpenGL ES Shader Compiler Version: E031.24.00.08
I/Adreno-EGL( 4622): Build Date: 03/07/14 Fri
I/Adreno-EGL( 4622): Local Branch: 
I/Adreno-EGL( 4622): Remote Branch: quic/LNX.LA.3.5.1_RB1.1
I/Adreno-EGL( 4622): Local Patches: NONE
I/Adreno-EGL( 4622): Reconstruct Branch: AU_LINUX_ANDROID_LNX.LA.3.5.1_RB1.04.04.02.048.018 + f2fd134 +  NOTHING
,W/chromium( 4622): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,I/dalvikvm( 4622): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 4622): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4622): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4622): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4622): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 4622): VFY: replacing opcode 0x6e at 0x0008
,W/dalvikvm( 4622): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 4622): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4622): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4622): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 4622): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 4622): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4622): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4622): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 4622): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4622): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4622): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 4622): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 4622): CordovaWebView is running on device made by: motorola
,D/OpenGLRenderer( 4622): Enabling debug mode 0
,W/AwContents( 4622): nativeOnDraw failed; clearing to background color.
,I/Keyboard.Facilitator( 1221): onFinishInput()
,W/IInputConnectionWrapper( 4622): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler( 1019): Displayed com.test.thalitest/.MainActivity,cp,ca,461
I/ActivityManager( 1019): Displayed com.test.thalitest/.MainActivity: +431ms (total +461ms)
,D/JsMessageQueue( 4622): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4622): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4290a1e0
,D/dalvikvm( 4622): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4290a1e0
,D/jxcore_app_log( 4622): JniHelper::setJavaVM(0x42022f78), pthread_self() = 1615737432
,I/chromium( 4622): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/dalvikvm( 4622): GC_CONCURRENT freed 2657K, 16% free 14532K/17224K, paused 3ms+4ms, total 40ms
,D/dalvikvm( 4622): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 4622): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 4622): GC_FOR_ALLOC freed 401K, 14% free 14848K/17224K, paused 27ms, total 27ms
,D/dalvikvm( 4622): GC_FOR_ALLOC freed 104K, 14% free 14855K/17224K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4622): Grow heap (frag case) to 16.600MB for 63974-byte allocation
,D/dalvikvm( 4622): GC_FOR_ALLOC freed 126K, 14% free 14875K/17288K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4622): Grow heap (frag case) to 16.650MB for 95956-byte allocation
,D/dalvikvm( 4622): GC_FOR_ALLOC freed 180K, 15% free 14910K/17384K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4622): Grow heap (frag case) to 16.730MB for 143930-byte allocation
,D/dalvikvm( 4622): GC_FOR_ALLOC freed 254K, 15% free 14957K/17528K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4622): Grow heap (frag case) to 16.844MB for 215890-byte allocation
,D/dalvikvm( 4622): GC_FOR_ALLOC freed 368K, 16% free 15031K/17740K, paused 26ms, total 26ms
,I/dalvikvm-heap( 4622): Grow heap (frag case) to 17.020MB for 323830-byte allocation
,D/dalvikvm( 4622): GC_FOR_ALLOC freed 567K, 17% free 15151K/18060K, paused 27ms, total 27ms
,D/dalvikvm( 4622): GC_FOR_ALLOC freed 864K, 16% free 15328K/18060K, paused 27ms, total 28ms
,I/dalvikvm-heap( 4622): Grow heap (frag case) to 17.696MB for 728606-byte allocation
,D/dalvikvm( 4622): GC_FOR_ALLOC freed 1283K, 17% free 15583K/18772K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4622): Grow heap (frag case) to 18.292MB for 1092904-byte allocation
,D/dalvikvm( 4622): GC_CONCURRENT freed 1804K, 20% free 15987K/19840K, paused 2ms+3ms, total 42ms
,D/dalvikvm( 4622): GC_FOR_ALLOC freed 231K, 20% free 15921K/19840K, paused 26ms, total 27ms
,I/dalvikvm-heap( 4622): Grow heap (frag case) to 19.143MB for 1639352-byte allocation
,D/dalvikvm( 4622): GC_CONCURRENT freed 1932K, 23% free 16524K/21444K, paused 4ms+7ms, total 51ms
,D/dalvikvm( 4622): GC_FOR_ALLOC freed 1010K, 24% free 16474K/21444K, paused 29ms, total 30ms
,I/dalvikvm-heap( 4622): Grow heap (frag case) to 20.465MB for 2459024-byte allocation
,D/dalvikvm( 4622): GC_CONCURRENT freed 305K, 22% free 18837K/23848K, paused 5ms+5ms, total 44ms
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,D/dalvikvm( 4622): GC_FOR_ALLOC freed 4202K, 27% free 17515K/23848K, paused 40ms, total 40ms
,I/dalvikvm-heap( 4622): Grow heap (frag case) to 22.655MB for 3688532-byte allocation
,D/dalvikvm( 4622): GC_CONCURRENT freed 274K, 24% free 20946K/27452K, paused 4ms+4ms, total 43ms
,D/dalvikvm( 4622): GC_FOR_ALLOC freed 4414K, 33% free 18627K/27452K, paused 34ms, total 34ms
,W/jxcore-log( 4622): Initializing JXcore engine
,W/jxcore-log( 4622): JXcore engine is ready
,D/dalvikvm( 4622): GC_CONCURRENT freed 425K, 23% free 21411K/27452K, paused 2ms+2ms, total 32ms
,D/dalvikvm( 4622): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 4622): WAIT_FOR_CONCURRENT_GC blocked 26ms
,W/jxcore-log( 4622): Starting JXcore engine
,W/jxcore-log( 4622): Platform android
W/jxcore-log( 4622): 
,W/jxcore-log( 4622): Process ARCH arm
W/jxcore-log( 4622): 
,I/jxcore-log( 4622): JXcore Cordova bridge is ready!
I/jxcore-log( 4622): 
,W/jxcore-log( 4622): JXcore engine is started
,E/jxcore  ( 4622): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4622): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4622): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager( 1019): Killing 4286:com.google.android.gms.unstable/u0a22 (adj 15): empty #9
W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{43d1e6c0 type 3 android}
,I/Keyboard.Facilitator.LanguageModelFlusher( 1221): run()
,I/Keyboard.Facilitator( 1221): flushDynamicLanguageModels()
,I/ConfigService( 1252): onCreate
,I/ConfigService( 1252): onDestroy
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{43c93f00 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43c83528 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{43c7e9c0 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{43c6ac70 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43c4d990 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43c49590 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43c419d8 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43c3b880 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{43c37ac0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{44a74fa0 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1019): sending alarm Alarm{44a73800 type 2 com.google.android.gms}
,V/AlarmManager( 1019): sending alarm Alarm{44a72d18 type 0 com.google.android.gms}
,D/ConnectivityService( 1019): Done.
,D/ConnectivityService( 1019): Setting timer for 720seconds
,I/EventLogService( 1732): Aggregate from 1452855618723 (log), 1452854303100 (data)
,D/ConnectivityService( 1019): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/SBar.NetworkController( 1094): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
,I/SBar.NetworkController( 1094): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
,I/ModemStatsDSDetect( 1209): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1209): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/ModemStatsDSDetect( 1209): onReceive() - done, currentInetCondition=100
,V/AlarmManager( 1019): sending alarm Alarm{4495c9c0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4495c098 type 1 com.android.deskclock}
,I/ActivityManager( 1019): Start proc com.android.deskclock for broadcast com.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4712 uid=10015 gids={50015, 1028}
,I/Keyboard.Facilitator( 1221): onFinishInput()
,W/IInputConnectionWrapper( 4622): showStatusIcon on inactive InputConnection
,I/ActivityManager( 1019): Killing 4393:com.android.defcontainer/u0a13 (adj 15): empty #9
,W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,V/AlarmManager( 1019): sending alarm Alarm{44931398 type 3 android}
,I/Keyboard.Facilitator.LanguageModelFlusher( 1221): run()
,I/Keyboard.Facilitator( 1221): flushDynamicLanguageModels()
,I/ConfigService( 1252): onCreate
,D/dalvikvm( 1252): GC_CONCURRENT freed 1613K, 33% free 11659K/17224K, paused 4ms+5ms, total 77ms
,E/DataBuffer( 1252): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42affbb0)
E/DataBuffer( 1252): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42aae6b0)
,E/DataBuffer( 1252): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42aab4c0)
,E/DataBuffer( 1252): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42aa82c8)
,E/DataBuffer( 1252): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42b02eb0)
,E/DataBuffer( 1252): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42c7d610)
,E/DataBuffer( 1252): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42a9d040)
E/DataBuffer( 1252): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42ca2758)
E/DataBuffer( 1252): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42d4dd80)
,E/DataBuffer( 1252): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42ae3f88)
,E/DataBuffer( 1252): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42952a58)
E/DataBuffer( 1252): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42bb97d0)
E/DataBuffer( 1252): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42bbc9c0)
E/DataBuffer( 1252): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42bbfbb0)
,E/DataBuffer( 1252): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@42baad40)
,I/ConfigService( 1252): onDestroy
,V/AlarmManager( 1019): sending alarm Alarm{44926c98 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4491f4c8 type 3 android}
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{4491cc20 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{44915c90 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{44912a98 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{44910118 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4490e078 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4495b6f8 type 2 android}
,D/dalvikvm( 1019): GC_EXPLICIT freed 25376K, 66% free 18397K/52992K, paused 3ms+11ms, total 166ms
,V/AlarmManager( 1019): sending alarm Alarm{4490b738 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{448e95f0 type 2 android}
,V/AlarmManager( 1019): sending alarm Alarm{4527b638 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4494cca0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{44947d78 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{44947460 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{448f2d68 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{44959808 type 2 android}
,D/ConnectivityService( 1019): Sampling interval elapsed, updating statistics ..
,V/AlarmManager( 1019): sending alarm Alarm{44958778 type 3 android}
,I/ProcessStatsService( 1019): Prepared write state in 33ms
,D/ConnectivityService( 1019): Done.
,V/AlarmManager( 1019): sending alarm Alarm{44957840 type 2 com.motorola.ccc.cce}
,V/AlarmManager( 1019): sending alarm Alarm{44957590 type 3 com.google.android.gms}
,V/AlarmManager( 1019): sending alarm Alarm{4495a148 type 2 com.google.android.gms}
,D/ConnectivityService( 1019): Setting timer for 720seconds
,I/ProcessStatsService( 1019): Pruning old procstats: /data/system/procstats/state-2016-01-14-10-36-56.bin
,D/CCE     ( 1591): Registering with Alarm Manager to restart CCE
,V/GLSActivity( 1333): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1333): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService( 1019): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
I/ModemStatsDSDetect( 1209): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.NetworkController( 1094): onReceive: ConnectivityManager.INET_CONDITION_ACTION Received
I/SBar.NetworkController( 1094): updateConnectivity: NetworkInfo: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, inetCondition= 1
I/ModemStatsDSDetect( 1209): INET_CONDITION=100 ,activeNet=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
I/ModemStatsDSDetect( 1209): onReceive() - done, currentInetCondition=100
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{430f5f70 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42e25468 type 0 com.motorola.contextual.fw}
,E/ActivityThread( 1265): Failed to find provider info for com.motorola.blur.setupprovider
,V/AlarmManager( 1019): sending alarm Alarm{42f11830 type 1 com.android.deskclock}
,E/PluginServerService( 1265): null XML String nothing to parse
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{42a050a0 type 3 android}
,I/ActivityManager( 1019): Killing 4074:com.google.android.apps.plus/u0a90 (adj 15): empty for 1810s
,W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/ActivityManager( 1019): Killing 4477:com.motorola.MotGallery2/u0a33 (adj 15): empty for 1810s
,I/ActivityManager( 1019): Killing 4501:com.google.android.partnersetup/u0a25 (adj 15): empty for 1810s
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  277): NetlinkHandler, power_supply subsys
I/MDMCTBK (  277): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  277): checkDefaultInst, current pid is = 277
I/MDMCTBK (  277): checkDefaultInst, pid match
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  277): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  277): MdmCutbackHndler,Could not open ''
,V/AlarmManager( 1019): sending alarm Alarm{4314e140 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{4315e8e0 type 3 android}
,V/AlarmManager( 1019): sending alarm Alarm{42a9fd58 type 3 android}
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 4848): 
D/AndroidRuntime( 4848): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4848): CheckJNI is OFF
D/dalvikvm( 4848): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4848): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4848): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4848): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4848): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4848): Note: class Landroid/app/ActivityManagerNative; has 181 unimplemented (abstract) methods
E/memtrack( 4848): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4848): failed to load memtrack module: -2
D/AndroidRuntime( 4848): Calling main entry com.android.commands.pm.Pm
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10111 user=-1: uninstall pkg
I/ActivityManager( 1019): Killing 4622:com.test.thalitest/u0a111 (adj 15): stop com.test.thalitest
W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10111 user=0: pkg removed
D/dalvikvm( 2313): GC_EXPLICIT freed 5266K, 44% free 9646K/17224K, paused 2ms+6ms, total 39ms
I/Keyboard.Facilitator( 1221): resetDictionaries() : en_GB
I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1252): Ignoring removeGeofence because network location is disabled.
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
I/Keyboard.Facilitator.DecoderInitializer( 1221): run()
D/VoicemailCleanupService( 1194): Cleaning up data for package: com.test.thalitest
I/Decoder ( 1221): createOrResetDecoder
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
D/dalvikvm( 1307): GC_EXPLICIT freed 3540K, 32% free 11721K/17224K, paused 2ms+4ms, total 64ms
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
I/Launcher( 1307): Deferring update until onResume
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
I/ActivityManager( 1019): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4876 uid=10033 gids={50033, 3003, 1028, 1015}
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "sms"
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "smsto"
I/ConfigService( 1252): onCreate
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mms"
D/dalvikvm( 1732): GC_EXPLICIT freed 1141K, 31% free 12010K/17224K, paused 15ms+14ms, total 192ms
D/dalvikvm( 1019): GC_EXPLICIT freed 1536K, 66% free 18340K/52992K, paused 6ms+12ms, total 163ms
D/dalvikvm( 1019): WAIT_FOR_CONCURRENT_GC blocked 7ms
D/dalvikvm( 2346): GC_EXPLICIT freed 4766K, 42% free 10125K/17224K, paused 2ms+15ms, total 211ms
I/PackageManager( 1019): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager( 1019):   Action: "android.intent.action.SENDTO"
I/PackageManager( 1019):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 1019):   Scheme: "mmsto"
I/Launcher( 1307): Deferring update until onResume
I/Keyboard.Facilitator.MainLanguageModelLoader( 1221): run()
I/InternalIcingCorporaPro( 2346): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager( 1019): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4895 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003, 1021, 3004, 3005, 1000, 3009, 1023, 1010, 1004, 2002, 3006}
I/Keyboard.Facilitator.MainLanguageModelLoader( 1221): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1.apk (offset=5018356, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1221): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1221): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1221): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1221): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1221): run() : Loaded File = UserHistory.en_GB.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1221): run() : Loading LM = user
D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 1019): removePackageParticipantsLocked: uid=10111 #1
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1221): run() : Missing File = Personal.en_GB.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1221): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1221): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1221): run()
I/StatsUtilsManager( 1221): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1221): shouldRecordStats() = Too Soon
W/ContextImpl( 4895): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1608 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2434 
I/dalvikvm( 3983): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 3983): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/dalvikvm( 3983): VFY: replacing opcode 0x6e at 0x0013
D/PackageBroadcastService( 1732): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1732): Clearing selected account for com.test.thalitest
I/LocationSettingsChecker( 1732): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1732): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1732): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1333): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1333): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 1732): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1732): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1732): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1732): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1732): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1732): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1732): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/dalvikvm(  279): GC_EXPLICIT freed 43K, 48% free 9012K/17224K, paused 1ms+3ms, total 23ms
D/gH_CompatibleDatabase( 1732): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1732): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1732): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1732): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1732): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1732): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager( 1019): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4914 uid=10090 gids={50090, 3003, 3002, 1028, 1015}
D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 3ms+2ms, total 20ms
D/dalvikvm( 1019): GC_EXPLICIT freed 362K, 66% free 18344K/52992K, paused 8ms+33ms, total 208ms
I/ActivityManager( 1019): Killing 4531:com.google.android.apps.docs/u0a59 (adj 15): empty for 2002s
D/ChimeraCfgMgr( 1732): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1732): Module APK com.google.android.play.games already loaded
D/dalvikvm(  279): GC_EXPLICIT freed <1K, 48% free 9012K/17224K, paused 1ms+2ms, total 19ms
W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
I/Icing   ( 1732): doRemovePackageData com.test.thalitest
I/InternalIcingCorporaPro( 2346): UpdateCorporaTask done [took 213 ms] updated apps [took 213 ms] 
E/dalvikvm( 4914): Could not find class 'android.app.Notification$Action$Builder', referenced from method efj.a
W/dalvikvm( 4914): VFY: unable to resolve new-instance 412 (Landroid/app/Notification$Action$Builder;) in Lefj;
D/dalvikvm( 4914): VFY: replacing opcode 0x22 at 0x0000
E/dalvikvm( 4914): Could not find class 'android.graphics.drawable.RippleDrawable', referenced from method efj.a
W/dalvikvm( 4914): VFY: unable to resolve new-instance 575 (Landroid/graphics/drawable/RippleDrawable;) in Lefj;
D/dalvikvm( 4914): VFY: replacing opcode 0x22 at 0x000b
D/AndroidRuntime( 4848): Shutting down VM
D/dalvikvm( 4848): GC_CONCURRENT freed 94K, 15% free 564K/660K, paused 1ms+0ms, total 3ms
E/dalvikvm( 4914): Could not find class 'android.app.Notification$Action$Builder', referenced from method efj.a
W/dalvikvm( 4914): VFY: unable to resolve new-instance 412 (Landroid/app/Notification$Action$Builder;) in Lefj;
D/dalvikvm( 4914): VFY: replacing opcode 0x22 at 0x0000
W/dalvikvm( 4914): Unable to resolve superclass of Lcm; (800)
W/dalvikvm( 4914): Link of class 'Lcm;' failed
E/dalvikvm( 4914): Could not find class 'cm', referenced from method efj.a
W/dalvikvm( 4914): VFY: unable to resolve new-instance 2378 (Lcm;) in Lefj;
D/dalvikvm( 4914): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 4914): Unable to resolve superclass of Lco; (800)
W/dalvikvm( 4914): Link of class 'Lco;' failed
E/dalvikvm( 4914): Could not find class 'co', referenced from method efj.a
W/dalvikvm( 4914): VFY: unable to resolve new-instance 2432 (Lco;) in Lefj;
D/dalvikvm( 4914): VFY: replacing opcode 0x22 at 0x002c
I/dalvikvm( 4914): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method efj.a
W/dalvikvm( 4914): VFY: unable to resolve virtual method 5224: Landroid/transition/TransitionSet;.getTransitionCount ()I
D/dalvikvm( 4914): VFY: replacing opcode 0x6e at 0x0008
I/dalvikvm( 4914): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method efj.a
W/dalvikvm( 4914): VFY: unable to resolve virtual method 5756: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm( 4914): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 4914): Could not find method android.view.View.getTransitionName, referenced from method efj.a
W/dalvikvm( 4914): VFY: unable to resolve virtual method 5560: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
D/dalvikvm( 4914): VFY: replacing opcode 0x6e at 0x0006
W/dalvikvm( 4914): VFY: unable to find class referenced in signature (Lx;)
I/dalvikvm( 4914): Could not find method android.transition.Transition.getTargetNames, referenced from method efj.a
W/dalvikvm( 4914): VFY: unable to resolve virtual method 5213: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
D/dalvikvm( 4914): VFY: replacing opcode 0x6e at 0x000a
I/dalvikvm( 4914): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method efj.a
W/dalvikvm( 4914): VFY: unable to resolve interface method 5806: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
D/dalvikvm( 4914): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 4914): Could not find method android.view.ViewParent.onNestedFling, referenced from method efj.a
W/dalvikvm( 4914): VFY: unable to resolve interface method 5805: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
D/dalvikvm( 4914): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 4914): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method efj.a
W/dalvikvm( 4914): VFY: unable to resolve interface method 5807: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
D/dalvikvm( 4914): VFY: replacing opcode 0x72 at 0x0000
W/dalvikvm( 4914): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 4914): Could not find class 'android.app.RemoteInput[]', referenced from method efj.a
W/dalvikvm( 4914): VFY: unable to resolve new-array 13337 ([Landroid/app/RemoteInput;) in Lefj;
D/dalvikvm( 4914): VFY: replacing opcode 0x23 at 0x0005
I/dalvikvm( 4914): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method efj.b
W/dalvikvm( 4914): VFY: unable to resolve virtual method 5224: Landroid/transition/TransitionSet;.getTransitionCount ()I
D/dalvikvm( 4914): VFY: replacing opcode 0x6e at 0x0009
W/dalvikvm( 4914): VFY: unable to find class referenced in signature (Lx;)
D/dalvikvm( 4914): DexOpt: unable to opt direct call 0x09c0 at 0x0e in Lefj;.a
D/dalvikvm( 4914): DexOpt: unable to opt direct call 0x0d49 at 0x0e in Lefj;.a
D/dalvikvm( 4914): DexOpt: unable to opt direct call 0x09c0 at 0x0e in Lefj;.a
W/dalvikvm( 4914): Unable to resolve superclass of Lcm; (800)
W/dalvikvm( 4914): Link of class 'Lcm;' failed
D/dalvikvm( 4914): DexOpt: unable to opt direct call 0x39db at 0x08 in Lefj;.a
W/dalvikvm( 4914): Unable to resolve superclass of Lco; (800)
W/dalvikvm( 4914): Link of class 'Lco;' failed
D/dalvikvm( 4914): DexOpt: unable to opt direct call 0x3b51 at 0x30 in Lefj;.a
D/dalvikvm( 4914): DexOpt: unable to opt direct call 0x0a18 at 0x13 in Lefj;.a
I/ActivityManager( 1019): Start proc android.process.media for content provider com.android.providers.media/.MediaProvider: pid=4938 uid=10018 gids={50018, 1028, 1015, 1023, 1024, 2001, 3003, 3007}
D/dalvikvm( 4938): No JNI_OnLoad found in /system/lib/libcryptomodes-jni.so 0x429080d0, skipping init
I/openssl ( 4938): Crypto mode not selected, openssl will run on its regular mode.
I/openssl ( 4938): Crypto mode 0 already enabled
I/dalvikvm( 4914): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method eer.a
W/dalvikvm( 4914): VFY: unable to resolve virtual method 2532: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
D/dalvikvm( 4914): VFY: replacing opcode 0x6e at 0x023c
I/dalvikvm( 4914): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eer.a
W/dalvikvm( 4914): VFY: unable to resolve virtual method 2906: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 4914): VFY: replacing opcode 0x6e at 0x000f
I/dalvikvm( 4914): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method eer.c
W/dalvikvm( 4914): VFY: unable to resolve virtual method 2532: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
D/dalvikvm( 4914): VFY: replacing opcode 0x6e at 0x0207
D/dalvikvm( 4914): Trying to load lib /data/app-lib/com.google.android.apps.plus-1/libcrashreporterer.so 0x42912b20
D/dalvikvm( 4914): Added shared lib /data/app-lib/com.google.android.apps.plus-1/libcrashreporterer.so 0x42912b20
I/ActivityManager( 1019): Killing 4558:com.quickoffice.android/u0a95 (adj 15): empty for 2002s
W/ContextImpl( 1265): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1252 android.content.ContextWrapper.sendBroadcast:365 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.sendTrigger:147 com.motorola.motocare.internal.frameworkevents.ProcessKillTrigger.handleFrameworkEvent:164 
E/SQLiteLog( 2313): (3850) statement aborts at 44: [INSERT INTO Trigger(state,timestamp,timezone,name) VALUES (?,?,?,?)] disk I/O error
E/SQLiteDatabase( 2313): Error inserting state=event=am_kill pid=4558 process=com.quickoffice.android reason=empty+for+2002s selectadj=15 timestamp=1452857652940 timezone=3600 name=ProcessKillTrigger
E/SQLiteDatabase( 2313): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 2313): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2313): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:782)
E/SQLiteDatabase( 2313): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 2313): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2313): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1469)
E/SQLiteDatabase( 2313): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1339)
E/SQLiteDatabase( 2313): 	at com.motorola.motocare.data.MotoCareSqliteDb.insertTrigger(MotoCareSqliteDb.java:139)
E/SQLiteDatabase( 2313): 	at com.motorola.motocare.TriggerManager.manageTrigger(TriggerManager.java:200)
E/SQLiteDatabase( 2313): 	at com.motorola.motocare.MotoCareService.handleTrigger(MotoCareService.java:321)
E/SQLiteDatabase( 2313): 	at com.motorola.motocare.MotoCareService.access$200(MotoCareService.java:63)
E/SQLiteDatabase( 2313): 	at com.motorola.motocare.MotoCareService$3.run(MotoCareService.java:206)
E/SQLiteDatabase( 2313): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 2313): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 2313): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2313): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager( 1019): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4965 uid=10059 gids={50059, 1028, 3003, 1015}

```
