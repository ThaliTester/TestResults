#### Test 50650278654db8c_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
D/ChimeraCfgMgr( 1892): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1892): Module APK com.google.android.play.games already loaded
,--------- beginning of /dev/log/system
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Icing   ( 1892): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1892): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1892): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
D/AndroidRuntime( 4190): 
D/AndroidRuntime( 4190): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4190): CheckJNI is OFF
D/dalvikvm( 4190): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4190): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4190): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4190): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4190): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4190): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 4190): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4190): failed to load memtrack module: -2
D/AndroidRuntime( 4190): Calling main entry com.android.commands.am.Am
I/ActivityManager(  965): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4190
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327ac48 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (187 us)
V/ActivityManager(  965): Moving to PAUSING: ActivityRecord{42cb44a0 u0 com.android.settings/.UsbSettings t2}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
D/dalvikvm(  965): GC_FOR_ALLOC freed 494K, 15% free 48702K/56808K, paused 175ms, total 175ms
I/dalvikvm-heap(  965): Grow heap (frag case) to 50.556MB for 856096-byte allocation
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm(  965): GC_FOR_ALLOC freed 21551K, 52% free 27988K/57648K, paused 120ms, total 120ms
D/ActivityManager(  965): resumeTopActivityLocked: Pausing null
V/ActivityManager(  965): resumeTopActivityLocked: Skip resume: need to start pausing
D/ActivityManager(  965): setFocusedStack: mFocusedStack=ActivityStack{4327ac48 stackId=1, 2 tasks}
D/AndroidRuntime( 4190): Shutting down VM
D/UsbSettingsControl( 2558): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2558): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/dalvikvm( 4190): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
D/ActivityManager(  965): allPausedActivitiesComplete: r=ActivityRecord{42cb44a0 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  965): Moving to PAUSED: ActivityRecord{42cb44a0 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327ac48 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Restarting ActivityRecord{43a035a0 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  965): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4201 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/ActivityManager(  965): startService SlideAside
W/ContextImpl(  965): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
I/SlideAside( 3574): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
V/ActivityManager(  965): Moving to RESUMED: ActivityRecord{43a035a0 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4201): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4201): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4201): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/SlideAside( 3574): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3574): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
V/WebViewChromium( 4201): Binding Chromium to the background looper Looper (main, tid 1) {42861f48}
I/chromium( 4201): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4201): Initializing chromium process, renderers=0
W/chromium( 4201): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4201): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4201): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4201): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4201): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4201): Remote Branch: 
I/Adreno-EGL( 4201): Local Patches: 
I/Adreno-EGL( 4201): Reconstruct Branch: 
I/dalvikvm( 4201): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4201): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4201): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4201): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4201): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4201): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4201): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4201): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4201): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4201): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4201): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4201): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4201): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4201): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4201): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4201): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4201): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4201): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4201): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4201): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  965): battery changed pluggedType: 2
W/BaseRuntimeLoader( 4201): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4201): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4201): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4201): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/OpenGLRenderer( 4201): Enabling debug mode 0
W/AwContents( 4201): nativeOnDraw failed; clearing to background color.
W/AwContents( 4201): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  965): IME STATUS OFF
I/dalvikvm(  965): Jit: resizing JitTable from 8192 to 16384
I/ActivityManager(  965): Displayed com.test.thalitest/.MainActivity: +505ms
I/ActivityManager( 4201): Timeline: Activity_idle id: android.os.BinderProxy@42863718 time:108158
D/JsMessageQueue( 4201): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4201): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42869860
D/dalvikvm( 4201): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42869860
D/jxcore_app_log( 4201): JniHelper::setJavaVM(0x4172f838), pthread_self() = 1639159856
D/JX-Cordova( 4201): jxcore cordova android initializing
D/ActivityManager(  965): no-history finish of ActivityRecord{42cb44a0 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  965): Finishing activity token=Token{4330f4e8 ActivityRecord{42cb44a0 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  965): Moving to FINISHING: ActivityRecord{42cb44a0 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a035a0 u0 com.test.thalitest/.MainActivity t3}
D/UsbSettings( 2558): [AUTORUN] onStop()
I/ActivityManager(  965): Timeline: Activity_windows_visible id: ActivityRecord{43a035a0 u0 com.test.thalitest/.MainActivity t3} time:108408
V/ActivityManager(  965): Moving to STOPPING: ActivityRecord{42cb44a0 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  965): Moving to STOPPED: ActivityRecord{42cb44a0 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiController(  965): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm( 4201): GC_CONCURRENT freed 2742K, 12% free 21911K/24832K, paused 1ms+9ms, total 47ms
D/dalvikvm( 4201): WAIT_FOR_CONCURRENT_GC blocked 7ms
D/dalvikvm( 4201): GC_FOR_ALLOC freed 225K, 12% free 21867K/24832K, paused 22ms, total 22ms
D/dalvikvm( 4201): GC_FOR_ALLOC freed 199K, 12% free 21884K/24832K, paused 22ms, total 22ms
I/dalvikvm-heap( 4201): Grow heap (frag case) to 23.683MB for 144892-byte allocation
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
D/dalvikvm( 4201): GC_FOR_ALLOC freed 256K, 13% free 21931K/24976K, paused 24ms, total 24ms
I/dalvikvm-heap( 4201): Grow heap (frag case) to 23.798MB for 217334-byte allocation
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 4201): GC_FOR_ALLOC freed 367K, 13% free 22005K/25192K, paused 39ms, total 40ms
I/dalvikvm-heap( 4201): Grow heap (frag case) to 23.973MB for 325996-byte allocation
D/dalvikvm( 4201): GC_FOR_ALLOC freed 568K, 14% free 22127K/25512K, paused 33ms, total 34ms
I/dalvikvm-heap( 4201): Grow heap (frag case) to 24.249MB for 488990-byte allocation
D/dalvikvm( 4201): GC_FOR_ALLOC freed 865K, 15% free 22304K/25992K, paused 33ms, total 34ms
I/dalvikvm-heap( 4201): Grow heap (frag case) to 24.654MB for 733480-byte allocation
D/dalvikvm( 4201): GC_FOR_ALLOC freed 1285K, 16% free 22561K/26712K, paused 28ms, total 29ms
D/dalvikvm( 4201): GC_CONCURRENT freed 1675K, 15% free 22933K/26712K, paused 1ms+1ms, total 26ms
D/dalvikvm( 4201): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 4201): GC_FOR_ALLOC freed 369K, 15% free 22891K/26712K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4201): Grow heap (frag case) to 26.101MB for 1650320-byte allocation
,D/dalvikvm( 4201): GC_CONCURRENT freed 1893K, 18% free 23485K/28324K, paused 2ms+4ms, total 48ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4201): GC_FOR_ALLOC freed 1177K, 17% free 23521K/28324K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4201): Grow heap (frag case) to 27.503MB for 2475476-byte allocation
,D/dalvikvm( 4201): GC_CONCURRENT freed 2003K, 22% free 24263K/30744K, paused 2ms+2ms, total 46ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4201): GC_CONCURRENT freed 2386K, 21% free 24476K/30744K, paused 1ms+4ms, total 34ms
,D/dalvikvm( 4201): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/dalvikvm( 4201): GC_FOR_ALLOC freed 317K, 21% free 24400K/30744K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4201): Grow heap (frag case) to 29.542MB for 3713210-byte allocation
,D/dalvikvm( 4201): GC_CONCURRENT freed 2751K, 26% free 25627K/34372K, paused 2ms+2ms, total 46ms
,D/dalvikvm( 4201): GC_FOR_ALLOC freed 650K, 26% free 25454K/34372K, paused 25ms, total 25ms
,W/jxcore-log( 4201): Initializing JXcore engine
,W/jxcore-log( 4201): JXcore engine is ready
,D/dalvikvm( 4201): GC_CONCURRENT freed 306K, 19% free 28120K/34372K, paused 2ms+1ms, total 25ms
,D/dalvikvm( 4201): WAIT_FOR_CONCURRENT_GC blocked 21ms
,W/jxcore-log( 4201): Starting JXcore engine
,W/jxcore-log( 4201): Platform android
W/jxcore-log( 4201): 
,W/jxcore-log( 4201): Process ARCH arm
W/jxcore-log( 4201): 
,I/jxcore-log( 4201): JXcore Cordova bridge is ready!
I/jxcore-log( 4201): 
,W/jxcore-log( 4201): JXcore engine is started
,I/chromium( 4201): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 4201): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/chromium( 4201): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  965): battery changed pluggedType: 2
,I/GAV2    ( 4142): Thread[GAThread,5,main]: No campaign data found.
,I/ConfigService( 1558): onDestroy
,I/jxcore-log( 4201): Toggling radios to true
I/jxcore-log( 4201): 
,D/BluetoothManagerService(  965): Message: 20
D/BluetoothManagerService(  965): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4317a238:true
D/BluetoothManagerService(  965): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  965): enable():  mBluetooth =null mBinding = false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
,D/BluetoothManagerService(  965): Message: 1
,D/BluetoothManagerService(  965): MESSAGE_ENABLE: mBluetooth = null
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiService(  965): New client listening to asynchronous messages
D/WifiService(  965): setWifiEnabled: true pid=4201, uid=10304
E/WifiService(  965): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  965): setWifiEnabled startWifiDelaySendMsg true
,D/BluetoothAdapterService( 1226): REFCOUNT: CREATED. INSTANCE_COUNT1
,D/BluetoothAdapterService(1116287648)( 1226): onCreate
,D/BluetoothManagerService(  965): Message: 20
D/BluetoothManagerService(  965): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43156d50:true
,D/BluetoothAdapterState( 1226): make
,I/bluedroid( 1226): init ready=0
D/bt-btif ( 1226): in initialized:0
D/bt-btif ( 1226): root, p->name:Bluedroid, child/value:0x6066caa8, bytes:160
D/bt-btif ( 1226): p->used:0, type:0, p->flag:0
D/WifiStateMachine(  965): setting operational mode to 1
I/BluetoothAdapterState( 1226): Entering OffState
D/WifiStateMachine(  965): handleMessage: E msg.what=131083
D/WifiStateMachine(  965): processMsg: InitialState
,E/WifiHW  (  965): Wifi MAC Address = 34:fc:ef:de:0a:e2
,I/jxcore-log( 4201): Radios toggled
I/jxcore-log( 4201): 
E/WifiHW  (  965): wifi_check_config compare "cur_etheraddr=34:fc:ef:de:0a:e2
E/WifiHW  (  965): ": cur_etheraddr=34:fc:ef:de:0a:e2
D/BluetoothManagerService(  965): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/bte_conf( 1226): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/jxcore-log( 4201): Got Device Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 4201): 
D/WifiService(  965): disconnect pid=4201, uid=10304
,D/WifiService(  965): reconnect pid=4201, uid=10304
D/SoftapController(  264): Softap fwReload - Ok
W/BT_PROF ( 1226): set profile trace flags 0x0
I/jxcore-log( 4201): Perf Test app loaded loaded
I/jxcore-log( 4201): 
D/CommandListener(  264): Setting iface cfg
D/CommandListener(  264): Trying to bring down wlan0
D/BTIF_CORE( 1226): [BTUI] lge_load_bluetooth_address
D/bt-btif ( 1226):  [BTUI] Load_abtddress
D/bt-btif ( 1226): PERSIST_BDADDR_PROPERTY is  34:FC:EF:9D:93:0B
D/bt-btif ( 1226): Got prior random BDA 34:FC:EF:9D:93:0B
I/bluedroid( 1226): get_profile_interface socket
I/bt-btif ( 1226): btif_get_adapter_property 2
I/bt-btif ( 1226): btif_get_adapter_property 1
D/BluetoothAdapterService(1116287648)( 1226): onBind
D/BluetoothManagerService(  965): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  965): Message: 40
D/BluetoothManagerService(  965): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
I/bluedroid( 1226): config_hci_snoop_log
D/btif_config_util( 1226): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
D/lge_bdaddr_loader( 4262): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 4262): [BTUI] bluetooth_load_bdaddress
I/GKI_LINUX( 1226): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
D/bt-btif ( 1226): btif task starting
D/BluetoothManagerService(  965): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  965): Broadcasting onBluetoothServiceUp() to 8 receivers.
D/lge_bdaddr_loader( 4262): [BTUI] bdaddr to set in property : 34:FC:EF:9D:93:0B
E/lge_bdaddr_loader( 4262): [BTUI] bluetooth_load_bdaddress : OK => 34:FC:EF:9D:93:0B
D/lge_bdaddr_loader( 4262): [BTUI] bdaddr_loader ::: END
I/Choreographer( 4201): Skipped 66 frames!  The application may be doing too much work on its main thread.
D/WifiMonitor(  965): WifiMonitorSingleton gotten
D/bt-btif ( 1226): btif_associate_evt: notify ASSOCIATE_JVM
I/bt-btif ( 1226): HAL bt_hal_cbacks->thread_evt_cb
I/bt-btif ( 1226): execute storage request event : 3
D/bt-btif ( 1226): btif_storage_get_adapter_property property->type:2 
I/bt-btif ( 1226): HAL bt_hal_cbacks->adapter_properties_cb
I/bt-btif ( 1226): execute storage request event : 3
D/bt-btif ( 1226): btif_storage_get_adapter_property property->type:1 
D/bt-btif ( 1226): in, bd addr:, prop type:1, len:512
D/dalvikvm( 1226): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,D/BluetoothAdapterService(1116287648)( 1226): Enable called with quiet mode status =  false
,D/BluetoothAdapterState( 1226): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
I/BluetoothAdapterState( 1226): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 1226): Broadcasting updateAdapterState() to 1 receivers.
,I/chromium( 4201): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/BluetoothManagerService(  965): Message: 60
D/BluetoothManagerService(  965): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  965): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothAdapterService(1116287648)( 1226): processStart()
,D/LGBluetoothAPIService( 1157): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothAdapterService(1116287648)( 1226): processStart(): Make Bond State Machine
,D/BluetoothBondStateMachine( 1226): make
,I/jxcore-log( 4201): check test folder
I/jxcore-log( 4201): 
,I/jxcore-log( 4201): found test : ./testFindPeers.js
I/jxcore-log( 4201): 
,D/wpa_supplicant( 4265): wpa_supplicant v2.1-devel-4.4.2
,D/BluetoothAdapterService( 1226): setAdapterService(): set to: null
D/BluetoothAdapterService( 1226): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@428932a0
D/wpa_supplicant( 4265): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4265): random: Trying to read entropy from /dev/random
D/wpa_supplicant( 4265): Get randomness: len=20 entropy=1
D/LGBluetoothServiceAdapter( 1226): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 1226): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@428932a0
,D/LGBluetoothServiceAdapter( 1226): [BTUI] check adapter is available - true : set adapter available.
D/LGBluetoothSettingsDBObserver( 1226): [BTUI] register observer for LG device name DB
,I/BluetoothBondStateMachine( 1226): StableState(): Entering Off State
,D/LGBluetoothXmlHandler( 2558): dvice configuraion start
D/LGBluetoothXmlHandler( 2558): startDocument!
D/LGBluetoothXmlHandler( 2558): startElement - elet = Device
,D/LGBluetoothXmlHandler( 2558): startElement - elet = OLDHELP
D/LGBluetoothXmlHandler( 2558): startElement - elet = OLDHELP
D/LGBluetoothXmlHandler( 2558): startElement - elet = OPPDIRECTORYBLUETOOTH
D/LGBluetoothXmlHandler( 2558): startElement - elet = OPP_DIRECTORY_BLUETOOTH
,D/LGBluetoothXmlHandler( 2558): endDocument!
,I/jxcore-log( 4201): found test : ./testSendData.js
I/jxcore-log( 4201): 
,E/BluetoothAdapterService( 1226): File transfer profiels supported!!
,W/BluetoothAdapterService( 1226): Starting service com.broadcom.bt.service.hfp.BrcmHeadsetService
,V/BluetoothPbapReceiver( 1226): PbapReceiver onReceive 
,V/BluetoothPbapReceiver( 1226): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 1226): ***********state = 11
,D/BluetoothHeadset(  965): Proxy object connected
,D/BluetoothHeadset( 1451): Proxy object connected
D/BluetoothHeadset( 1451): Proxy object connected
,D/BluetoothHeadset( 1451): Proxy object connected
,D/BrcmHeadsetService( 1226): Received start request. Starting profile...
I/Brcm_BluetoothHeadsetServiceJni( 1226): classInitNative: succeeds
,D/HeadsetStateMachine( 1226): make
,E/BluetoothAdapterService( 1226): File transfer profiels supported!!
,W/BluetoothAdapterService( 1226): Starting service com.android.bluetooth.a2dp.A2dpService
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/BluetoothPermissionRequest( 2558): onReceive
E/BluetoothAdapterService( 1226): File transfer profiels supported!!
I/LGBluetoothHeadsetServiceJni( 1226): classInitNative: succeeds
D/LGBluetoothHfpAdapter( 1226): Version 1.5
W/BluetoothAdapterService( 1226): Starting service com.android.bluetooth.hid.HidService
I/bluedroid( 1226): get_profile_interface handsfree
I/bt-btif ( 1226): btif_hf_get_interface
I/bt-btif ( 1226): init
D/bt-btif ( 1226): btif_enable_service: current services:0x40
D/BluetoothManagerService(  965): Message: 20
D/BluetoothManagerService(  965): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43113f58:true
E/BluetoothAdapterService( 1226): File transfer profiels supported!!
V/AudioPolicyService(  271): getOutput()
V/AudioPolicyManagerBase(  271): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerBase(  271): getOutput() returns output 2
V/AudioSystem( 1226): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  271): registerClient() client 0xb74c1348, pid 1226
V/AudioFlinger(  271): sendIoConfigEvent() num events 1 event 0, param 0
V/AudioFlinger(  271): sendIoConfigEvent() num events 1 event 0, param 0
V/AudioFlinger(  271): thread 0xb2718008 type 0 TID 906 waking up
V/AudioFlinger(  271): thread 0xb25ad008 type 0 TID 1000 waking up
V/AudioFlinger(  271): acquireWakeLock_l() AudioOut_3 status 0
V/AudioFlinger(  271): processConfigEvents() remaining events 1
V/AudioFlinger(  271): acquireWakeLock_l() AudioOut_2 status 0
V/AudioFlinger(  271): PlaybackThread::audioConfigChanged_l, thread 0xb25ad008, event 0, param 0
V/AudioSystem(  271): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem(  271): ioConfigChanged() opening already existing output! 3
V/AudioFlinger(  271): processConfigEvents() remaining events 1
W/BluetoothAdapterService( 1226): Starting service com.android.bluetooth.hdp.HealthService
V/AudioSystem(  965): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem(  965): ioConfigChanged() opening already existing output! 3
V/AudioFlinger(  271): acquireWakeLock_l() AudioOut_3 status 0
V/AudioFlinger(  271): PlaybackThread::audioConfigChanged_l, thread 0xb2718008, event 0, param 0
V/AudioSystem(  271): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  271): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1226): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem( 1226): ioConfigChanged() new output samplingRate 48000, format 1 channel mask 0x3 frameCount 960 latency 50
V/AudioSystem( 1226): getSamplingRate() streamType 8, output 2, sampling rate 48000
V/AudioTrack( 1226): sampleRate 0, channelMask 0x1, format 1
V/AudioTrack( 1226): streamType 8
V/AudioTrack( 1226): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioSystem( 1605): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem( 1605): ioConfigChanged() opening already existing output! 3
V/AudioPolicyService(  271): checkPlayCondition().. streamType = 8
V/AudioSystem( 1605): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1605): ioConfigChanged() opening already existing output! 2
V/AudioPolicyManagerBase(  271): checkPlayCondition()... stream = 8, bResult = 0
V/AudioSystem(  965): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  965): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1226): ioConfigChanged() event 0, ioHandle 2
V/AudioFlinger(  271): acquireWakeLock_l() AudioOut_2 status 0
V/AudioSystem( 1226): ioConfigChanged() new output samplingRate 48000, format 1 channel mask 0x3 frameCount 960 latency 160
V/AudioSystem( 1451): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem( 1451): ioConfigChanged() opening already existing output! 3
V/AudioTrack( 1226): set() checkPlaycondition!!!! streamType 8 return NO_INIT.
V/AudioSystem( 1451): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1451): ioConfigChanged() o,pening already existing output! 2
D/BluetoothAdapterService( 1226): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@428932a0
D/HeadsetStateMachine( 1226): Enter Disconnected: -2
D/HeadsetPhoneState( 1226): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 1226): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 1226): [BTUI] change sampling rate to 8000 when device is disconnected
E/AudioSystem( 1226): AudioSystem::setParameters()...keyValue bt_samplerate=8000
V/AudioFlinger(  271): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 1226
V/SRS_Proc(  271): ParamSet string: bt_samplerate=8000
D/audio_hw_primary(  271): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  271): voice_set_parameters: enter: bt_samplerate=8000
V/voice   (  271): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  271): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
D/wpa_supplicant( 4265): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4265): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 4265): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 4265): Successfully initialized wpa_supplicant
D/wpa_supplicant( 4265): Override interface parameter: ctrl_interface ('(null)' -> '/data/misc/wifi/sockets')
D/wpa_supplicant( 4265): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface '/data/misc/wifi/sockets' bridge 'N/A'
D/wpa_supplicant( 4265): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4265): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4265): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4265): disable_scan_offload=1
D/wpa_supplicant( 4265): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4265): update_config=1
D/wpa_supplicant( 4265): device_name='g2_open_com'
D/wpa_supplicant( 4265): manufacturer='LGE'
D/wpa_supplicant( 4265): model_name='LG-D802'
D/wpa_supplicant( 4265): model_number='LG-D802'
D/wpa_supplicant( 4265): serial_number='022678fb504e29b0'
D/wpa_supplicant( 4265): config_methods='physical_display virtual_push_button keypad'
D/wpa_supplicant( 4265): p2p_disabled=1
D/wpa_supplicant( 4265): p2p_no_group_iface=1
D/wpa_supplicant( 4265): Line: 15 - start of a new network block
D/wpa_supplicant( 4265): ssid - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 4265): PSK (ASCII passphrase) - hexdump(len=10): [REMOVED]
D/wpa_supplicant( 4265): key_mgmt: 0x2
D/wpa_supplicant( 4265): priority=1 (0x1)
D/BluetoothAdapterService( 1226): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@428932a0
D/LGBluetoothResetSettingReceiver( 2558): [BTUI] Loading JNI Library
D/BluetoothA2dp(  965): Proxy object connected
D/A2dpService( 1226): Received start request. Starting profile...
I/BluetoothA2dpServiceJni( 1226): classInitNative: succeeds
D/A2dpStateMachine( 1226): make
I/bluedroid( 1226): get_profile_interface a2dp
I/bt-btif ( 1226): btif_av_get_interface
I/bt-btif ( 1226): init
I/bt-btif ( 1226): ## A2DP START MEDIA TASK ##
I/GKI_LINUX( 1226): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
D/bt-btif ( 1226): UIPC_Init
I/bt-btif ( 1226): ### uipc_main_init ###
D/bt-btif ( 1226): UIPC_Open : ch_id 0, p_cback 60b05b25
I/bt-btif ( 1226): SETUP CHANNEL SERVER 0
I/bt-btif ( 1226): create_server_socket /data/misc/bluedroid/.a2dp_ctrl
I/bt-btif ( 1226): created socket fd 69
I/bt-btif ( 1226): ADD SERVER FD TO ACTIVE SET 69
I/bt-btif ( 1226): UIPC SEND WAKE UP
I/bt-btif ( 1226): ## A2DP MEDIA TASK STARTED ##
E/bt-btif ( 1226): warning : media task started media_task_refcnt 1 
D/bt-btif ( 1226,): btif_enable_service: current services:0x48
D/bt-btif ( 1226): btif_av_state_idle_handler event:BTIF_SM_ENTER_EVT flags 0
I/bt-btif ( 1226): ## ON A2DP IDLE ##
D/bt-btif ( 1226): UIPC_Close : ch_id 1
I/bt-btif ( 1226): CHANNEL 1 ALREADY CLOSED
I/LGBluetoothA2dpServiceJni( 1226): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 1226): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
E/BluetoothAdapterService( 1226): File transfer profiels supported!!
D/A2dpStateMachine( 1226): Enter Disconnected: -2
I/BluetoothAVRCP1.3ServiceJni( 1226): classInitNativeAVRCP
V/Avrcp   ( 1226): make
W/BluetoothAdapterService( 1226): Starting service com.android.bluetooth.pan.PanService
D/LGBluetoothAvrcpManager( 1226): [BTUI] initAvcrpManager
E/BluetoothAdapterService( 1226): File transfer profiels supported!!
D/LGBluetoothAvrcpManager( 1226): [BTUI] initPlayStatus() : isMusicActive = false
D/LGBluetoothAvrcpAdapter( 1226): [BTUI] Use LG AVRCP : init jni
I/BluetoothAVRCP1.3ServiceJni( 1226): initNativeAVRCP
I/bluedroid( 1226): get_profile_interface avrcp
I/bt-btif ( 1226): btif_rc_get_interface
I/bt-btif ( 1226): ## init ##
D/BluetoothAdapterService( 1226): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@428932a0
I/BluetoothHidServiceJni( 1226): classInitNative: succeeds
D/HidService( 1226): Received start request. Starting profile...
I/bluedroid( 1226): get_profile_interface hidhost
I/bt-btif ( 1226): btif_hh_get_interface
I/bt-btif ( 1226): init
D/bt-btif ( 1226): btif_enable_service: current services:0x100048
D/BluetoothAdapterService( 1226): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@428932a0
W/BluetoothAdapterService( 1226): Starting service com.android.bluetooth.map.BluetoothMapService
D/HeadsetStateMachine( 1226): Proxy object connected
I/BluetoothHealthServiceJni( 1226): classInitNative: succeeds
D/HealthService( 1226): Received start request. Starting profile...
I/bluedroid( 1226): get_profile_interface health
I/bt-btif ( 1226): btif_hl_get_interface
I/bt-btif ( 1226): init
D/bt-btif ( 1226): Process name (droid.bluetooth)
D/bt-btif ( 1226): btif_hl_soc_thread_init
D/bt-btif ( 1226): create_thread: entered
D/bt-btif ( 1226): create_thread: thread created successfully
D/bt-btif ( 1226): entered btif_hl_select_thread
D/bt-btif ( 1226): btif_hl_select_wakeup_init
I/LGBluetoothHealthServiceJni( 1226): classInitNative: succeeds
D/bt-btif ( 1226): btif_hl_select_wakeup_init signal_fds[0]=79 signal_fds[1]=80
D/bt-btif ( 1226): max_s=79 
D/bt-btif ( 1226): set curr_set = org_set 
D/BluetoothAdapterService( 1226): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@428932a0
D/BluetoothAdapterService(1116287648)( 1226): Message: 1
D/BluetoothAdapterService(1116287648)( 1226): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1226): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.hfp.BrcmHeadsetService, state = 12, doUpdate = true
E/BluetoothAdapterService( 1226): File transfer profiels supported!!
D/WifiStateMachine(  965): setWifiState: enabling
E/WifiStateMachine(  965): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine(  965): useWiFiOffloading() : false
E/WifiStateMachine(  965): CONFIG_LGE_WLAN_PATH : true
D/WifiStateMachine(  965): Supplicant start successful
D/WifiMonitor(  965): WifiMonitorSingleton gotten
D/WifiMonitor(  965): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor(  965): connecting to supplicant
V/WfdStateTracker( 1157): WfdStateTracker handleDirectStateChangedEvent: 1
I/WifiServiceExtension(  965): WIFI_STATE_CHANGED_ACTION [2]
E/Parcel  (  411): Reading a NULL string not supported here.
E/Parcel  (  411): Reading a NULL string not supported here.
E/Parcel  (  411): Reading a NULL string not supported here.
E/Parcel  (  411): Reading a NULL string not supported here.
E/Parcel  (  411): Reading a NULL string not supported here.
E/Parcel  (  411): Reading a NULL string not supported here.
E/Parcel  (  411): ,Reading a NULL string not supported here.
W/BluetoothAdapterService( 1226): Starting service com.android.bluetooth.gatt.GattService
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/BluetoothAdapterService( 1226): Profile still not running:com.broadcom.bt.service.sap.SapService
I/BluetoothPanServiceJni( 1226): classInitNative(L105): succeeds
E/BluetoothAdapterService( 1226): File transfer profiels supported!!
D/HeadsetStateMachine( 1226): Disconnected process message: 10
D/HeadsetPhoneState( 1226): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 1226): Disconnected process message: 11
D/BluetoothPan(  965): BluetoothPAN Proxy object connected
E/BluetoothSettings_JNI( 2558): [BTUI] JNI_OnLoad : ### LGBT_USE_BDT : TRUE ###
W/BluetoothAdapterService( 1226): Starting service com.broadcom.bt.service.sap.SapService
D/PanService( 1226): Received start request. Starting profile...
D/BluetoothPanServiceJni( 1226): initializeNative(L110): pan
I/bluedroid( 1226): get_profile_interface pan
D/bt-btif ( 1226): stack_initialized = 0, btpan_cb.enabled:0
D/BluetoothTethering(  965): got CMD_CHANNEL_HALF_CONNECTED
D/BluetoothAdapterService( 1226): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@428932a0
D/BluetoothAdapterService(1116287648)( 1226): Message: 1
D/BluetoothAdapterService(1116287648)( 1226): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1226): onProfileServiceStateChange: serviceName=com.android.bluetooth.a2dp.A2dpService, state = 12, doUpdate = true
E/BluetoothAdapterService( 1226): File transfer profiels supported!!
W/BluetoothAdapterService( 1226): Starting service com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService( 1226): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1116287648)( 1226): Message: 1
D/BluetoothAdapterService(1116287648)( 1226): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1226): onProfileServiceStateChange: serviceName=com.android.bluetooth.hid.HidService, state = 12, doUpdate = true
D/dalvikvm( 1226): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
I/BluetoothAdapterState( 1226): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/BluetoothAdapterService( 1226): Profile still not running:com.broadcom.bt.service.sap.SapService
D/wpa_supplicant( 4265): PSK (from passphrase) - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 4265): Priority group 1
D/wpa_supplicant( 4265):    id=0 ssid='NG700'
D/wpa_supplicant( 4265): Reading configuration file '/system/etc/wifi/wpa_supplicant_overlay.conf'
D/BluetoothAdapterService( 1226): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@428932a0
I/LGBluetoothMapAdapter( 1226): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 1226): BluetoothMapBinder()
D/BluetoothMapService( 1226): Received start request. Starting profile...
D/LGBluetoothResetSettingReceiver( 2558): return without doing reset settings.
D/BluetoothMapService( 1226): start()
D/BluetoothAdapterService( 1226): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@428932a0
D/BluetoothAdapterService(1116287648)( 1226): Message: 1
D/BluetoothAdapterService(1116287648)( 1226): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1226): onProfileServiceStateChange: serviceName=com.android.bluetooth.hdp.HealthService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1226): Profile still not running:com.broadcom.bt.service.sap.SapService
I/BtGatt.JNI( 1226): classInitNative(L685): classInitNative: Success!
D/BtGatt.DebugUtils( 1226): handleDebugAction() action=null
D/BtGatt.GattService( 1226): Received start request. Starting profile...
D/BtGatt.GattService( 1226): start()
I/bluedroid( 1226): get_profile_interface gatt
D/BluetoothAdapterService( 1226): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@428932a0
D/BluetoothAdapterService(1116287648)( 1226): Message: 1
D/BluetoothAdapterService(1116287648)( 1226): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1226): onProfileServiceStateChange: serviceName=com.android.bluetooth.pan.PanService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1226): Profile still not running:com.broadcom.bt.service.sap.SapService
D/wpa_supplicant( 4265): disable_scan_offload=1
D/wpa_supplicant( 4265): Priority group 1
D/wpa_supplicant( 4265):    id=0 ssid='NG700'
I/wpa_supplicant( 4265): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 4265): nl80211: RFKILL status not available
D/wpa_supplicant( 4265): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 4265): nl80211: TDLS supported
D/wpa_supplicant( 4265): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4265): nl80211: Enable multi-channel concurrent (driver advertised support)
I/wpa_supplicant( 4265): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
D/wpa_supplicant( 4265): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4265): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 4265): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 4265): nl80211: Subscribe to mgmt frames with non-AP handle 0xb81b8590
D/wpa_supplicant( 4265): nl80211: Register frame type=0xd0 nl_handle=0xb81b8590
D/wpa_supplicant( 4265): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 4265): nl80211: Register frame type=0xd0 nl_handle=0xb81b8590
D/wpa_supplicant( 4265): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 4265): nl80211: Register frame type=0xd0 nl_handle=0xb81b8590
D/wpa_supplicant( 4265): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 4265): nl80211: Register frame type=0xd0 nl_handle=0xb81b8590
D/wpa_supplicant( 4265): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 4265): nl80211: Register frame type=0xd0 nl_handle=0xb81b8590
D/wpa_supplicant( 4265): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 4265): nl80211: Register frame type=0xd0 nl_handle=0xb81b8590
D/wpa_supplicant( 4265): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 4265): nl80211: Register frame type=0xd0 nl_handle=0xb81b8590
D/wpa_supplicant( 4265): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 4265): nl80211: Register frame type=0xd0 nl_handle=0xb81b8590
D/wpa_supplicant( 4265): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 4265): nl80211: Register frame type=0xd0 nl_handle=0xb81b8590
D/wpa_supplicant( 4265): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 4265): nl80211: Register frame type=0xd0 nl_handle=0xb81b8590
D/wpa_supplicant( 4265): nl80211: Register frame match - hexdump(len=2): 0a 11
I/BluetoothSAPServiceJni( 1226): classInitNative(L170): succeeds
D/SapService( 1226): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 1226): initializeNative(L175): sap
I/bluedroid( 1226): get_profile_interface sap
I/bt-btif ( 1226): btif_sc_get_interface
I/bt-btif ( 1226): init
D/bt-btif ( 1226): btif_enable_service: current services:0x120048
I/LGBluetoothSapAdapter( 1226): [BTUI] getInstance : create [LGBluetoothSapAdapter]
I/LGBluetoothSapAdapter( 1226): [BTUI] Create LGBluetoothSapManager Instance
D/LGBluetoothSapManager( 1226): [BTUI] initSapManager
D/LgeBluetoothSimManager( 1451): [BTUI] SAP_ENABLE_EVT
D/BluetoothAdapterService( 1226): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@428932a0
V/BluetoothFTPServiceJni( 1226): classInitNative
I/BluetoothFTPServiceJni( 1226): classInitNative(L271): succeeds
D/BluetoothAdapterService( 1226): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@428932a0
D/BluetoothFTPService( 1226): BluetoothFtpBinder()
D/**BluetoothFTPService( 1226): Received start request. Starting profile...
V/BluetoothFTPService( 1226): FTP-Server Service start
D/BluetoothFTPServiceJni( 1226): initFtpNativeDataNative(L275): FTP
I/bluedroid( 1226): get_profile_interface ftp
I/bt-btif ( 1226): btif_fts_get_interface
I/bt-btif ( 1226): init
D/bt-btif ( 1226): btif_enable_service: current services:0x120148
D/BluetoothFTPServiceJni( 1226): initFtpNativeDataNative(L317): FTP init done
D/BluetoothAdapterService( 1226): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@428932a0
I/bt-btif ( 1226): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothManagerService(  965): Bluetooth Adapter name changed to Thali Test's G2
D/BluetoothManagerService(  965): Stored Bluetooth name: Thali Test's G2
V/BluetoothMapService( 1226): Handler(): got msg=1
D/BluetoothAdapterService(1116287648)( 1226): Message: 1
D/BluetoothAdapterService(1116287648)( 1226): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1226): onProfileServiceStateChange: serviceName=com.android.bluetooth.map.BluetoothMapService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1226): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1116287648)( 1226): Message: 1
D/BluetoothAdapterService(1116287648)( 1226): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1226): onProfileServiceStateChange: serviceName=com.android.bluetooth.gatt.GattService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1226): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1116287648)( 1226): Message: 1
D/BluetoothAdapterService(1116287648)( 1226): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1226): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.sap.SapService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1226): Profile still not running:com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(1116287648)( 1226): Message: 1
D/BluetoothAdapterService(1116287648)( 1226): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1226): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.ftp.FTPService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1226): All profile services started.
D/BluetoothAdapterState( 1226): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 1226): enable 1
I/bt-btif ( 1226): BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
E/bt-btu  ( 1226): VERSION G2-AFBT-440-21_MI_00.02_OPP10 (BTE: BCM1200_PI_10.3.20.55)
I/bt_hci_bdroid( 1226): init
I/bt_vendor( 1226): init
I/bt_vnd_conf( 1226): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 1226): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
I/bt-btif ( 1226): libbt-hci init returns 0
I/bt_hci_bdroid( 1226): bt_hc_worker_thread started
I/GKI_LINUX( 1226): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
I/ActivityManager(  965): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=4292 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/HyLog   ( 4292): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4292): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4292): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  965): Killing 3389:com.google.android.music:main/u0a107 (adj 15): empty #17
D/AuthorizationBluetoothService( 1558): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager(  965): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4305 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
F/ActivityManager(  965): Service ServiceRecord{4322a390 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{432c8b98 3389:com.google.android.music:main/u0a107} not same as in map: null
F/ActivityManager(  965): Service ServiceRecord{43211db0 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{432c8b98 3389:com.google.android.music:main/u0a107} not same as in map: null
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327ac48 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a035a0 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4305): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4305): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4305): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/PCSuite ( 4305): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  965): Killing 3059:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327ac48 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a035a0 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:rfkill, action:3
,I/bt_userial_vendor( 1226): userial vendor open: opening /dev/ttyHS99
D/bt_userial_vendor( 1226): userial_vendor_open():UART is setup
,I/bt_userial_vendor( 1226): device fd = 84 open
,D/bt_hwcfg( 1226): Chipset BCM4335A0
,D/bt_hwcfg( 1226): Target name = [BCM4335A0]
D/bt_hwcfg( 1226): Target name = [BCM4335]
I/bt_hwcfg( 1226): Found patchfile: /system/bin//BCM4335B0_002.001.006.0191.0201_ORC.hcd
,I/bt_hwcfg( 1226): Applying 4335 AXI BRIDGE patch...
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.451385 Y: -0.405136 Z: 9.755493 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.451385 .y:-0.405136 .z:9.755493
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,I/bt_hwcfg( 1226): bt vendor lib: set UART baud 4000000
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.456573 Y: -0.404465 Z: 9.760574 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.456573 .y:-0.404465 .z:9.760574
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,D/wpa_supplicant( 4265): netlink: Operstate: linkmode=1, operstate=5
D/wpa_supplicant( 4265): nl80211: driver param='use_multi_chan_concurrent=1'
,D/wpa_supplicant( 4265): nl80211: Use Multi channel concurrency
D/wpa_supplicant( 4265): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4265): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4265): nl80211: 2457-2482 @ 20 MHz
D/wpa_supplicant( 4265): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4265): nl80211: 5170-5250 @ 40 MHz
D/wpa_supplicant( 4265): nl80211: 5735-5835 @ 40 MHz
,D/wpa_supplicant( 4265): nl80211: Added 802.11b mode based on 802.11g information
,D/Tethering(  965): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/Tethering(  965): sendTetherStateChangedBroadcast 1, 0, 0
,I/bt_hwcfg( 1226): Releasing 4335 AXI BRIDGE lock
D/wpa_supplicant( 4265): wlan0: Own MAC address: 34:fc:ef:de:0a:e2
D/wpa_supplicant( 4265): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4265): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4265): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4265): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4265): wlan0: RSN: flushing PMKID list in the driver
,D/wpa_supplicant( 4265): nl80211: Flush PMKIDs
,D/wpa_supplicant( 4265): wlan0: Setting scan request: 0 sec 100000 usec
,D/UsbSettingsReceiver( 2558): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,D/UsbSettingsReceiver( 2558): [AUTORUN] sys.usb.config = boot,adb
D/UsbSettingsReceiver( 2558): [AUTORUN] sys.usb.state = boot,adb
,D/UsbSettingsReceiver( 2558): [AUTORUN] persist.sys.usb.config = boot,adb
,D/UsbSettingsReceiver( 2558): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,I/Config  ( 2558): getOperator() : OPEN
,D/UsbSettingsControl( 2558): [AUTORUN] getUsbConnected() : connected=true
D/wpa_supplicant( 4265): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4265): TDLS: Driver uses internal link setup
D/UsbSettingsReceiver( 2558): [AUTORUN] onReceive() : availableList=[wlan0]
D/wpa_supplicant( 4265): WPS: Set UUID for interface wlan0
D/UsbSettingsReceiver( 2558): [AUTORUN] onReceive() : activeList=[]
D/wpa_supplicant( 4265): WPS: UUID based on MAC address - hexdump(len=16): 4d 54 bb 4b f9 ab 59 64 88 e9 60 e7 bf 13 d1 db
D/UsbSettingsReceiver( 2558): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 2558): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 2558): [AUTORUN] onReceive() : TetherState Changed=wlan0
,D/UsbSettingsControl( 2558): [AUTORUN] setTetherStatus() : status=false
D/wpa_supplicant( 4265): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4265): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4265): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4265): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4265): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4265): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4265): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4265): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4265): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4265): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 4265): Using existing control interface directory.
I/wpa_supplicant( 4265): 0xb81b7cc8 HY init priv-sock 18 p2p_disabled: 0 path: /data/misc/wifi/sockets/wlan0 name:/data/misc/wifi/sockets/wlan0 ctrl_interface: /data/misc/wifi/sockets, ifname: wlan0
I/wpa_supplicant( 4265): [ITEC] ASSIGN CALL BACK A4 5
I/wpa_supplicant( 4265): [ITEC] ASSIGN CALL BACK A1 6
D/wpa_supplicant( 4265): lge_eap_carrier_var_init
D/wpa_supplicant( 4265): realm format : @wlan.mnc<MNC>.mcc<MCC>.3gppnetwork.org 
D/wpa_supplicant( 4265): wlan0: Added interface wlan0
D/wpa_supplicant( 4265): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 4265): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4265): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4265): Override interface parameter: ctrl_interface ('(null)' -> '/data/misc/wifi/sockets')
D/wpa_supplicant( 4265): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface '/data/misc/wifi/sockets' bridge 'N/A'
D/wpa_supplicant( 4265): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4265): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4265): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4265): driver_param='use_p2p_group_interface=1use_multi_chan_concurrent=1'
D/wpa_supplicant( 4265): update_config=1
D/wpa_supplicant( 4265): device_name='Thali Test's G2'
D/wpa_supplicant( 4265): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4265): p2p_ssid_postfix='-Thali Test's G2'
D/wpa_supplicant( 4265): persistent_reconnect=1
,D/wpa_supplicant( 4265): Reading configuration file '/system/etc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4265): update_config=1
D/wpa_supplicant( 4265): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4265): driver_param='use_p2p_group_interface=1 use_multi_chan_concurrent=1'
D/wpa_supplicant( 4265): eapol_version=1
D/wpa_supplicant( 4265): ap_scan=1
,D/wpa_supplicant( 4265): fast_reauth=1
,D/wpa_supplicant( 4265): p2p_disabled=0
D/wpa_supplicant( 4265): p2p_no_group_iface=0
I/wpa_supplicant( 4265): rfkill: Cannot open RFKILL control device
,D/wpa_supplicant( 4265): nl80211: RFKILL status not available
D/wpa_supplicant( 4265): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 4265): nl80211: TDLS supported
D/wpa_supplicant( 4265): nl80211: Use separate P2P group interface (driver advertised support)
,D/wpa_supplicant( 4265): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 4265): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4265): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 4265): nl80211: Set mode ifindex 22 iftype 2 (STATION)
D/wpa_supplicant( 4265): nl80211: Subscribe to mgmt frames with non-AP handle 0xb81c7c28
,D/wpa_supplicant( 4265): nl80211: Register frame type=0xd0 nl_handle=0xb81c7c28
D/wpa_supplicant( 4265): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 4265): nl80211: Register frame type=0xd0 nl_handle=0xb81c7c28
D/wpa_supplicant( 4265): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 4265): nl80211: Register frame type=0xd0 nl_handle=0xb81c7c28
,D/wpa_supplicant( 4265): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 4265): nl80211: Register frame type=0xd0 nl_handle=0xb81c7c28
D/wpa_supplicant( 4265): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 4265): nl80211: Register frame type=0xd0 nl_handle=0xb81c7c28
,D/wpa_supplicant( 4265): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 4265): nl80211: Register frame type=0xd0 nl_handle=0xb81c7c28
D/wpa_supplicant( 4265): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 4265): nl80211: Register frame type=0xd0 nl_handle=0xb81c7c28
,D/wpa_supplicant( 4265): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 4265): nl80211: Register frame type=0xd0 nl_handle=0xb81c7c28
D/wpa_supplicant( 4265): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 4265): nl80211: Register frame type=0xd0 nl_handle=0xb81c7c28
D/wpa_supplicant( 4265): nl80211: Register frame match - hexdump(len=2): 0a 07
,D/wpa_supplicant( 4265): nl80211: Register frame type=0xd0 nl_handle=0xb81c7c28
,D/wpa_supplicant( 4265): nl80211: Register frame match - hexdump(len=2): 0a 11
,D/wpa_supplicant( 4265): netlink: Operstate: linkmode=1, operstate=5
,D/wpa_supplicant( 4265): nl80211: driver param='use_p2p_group_interface=1use_multi_chan_concurrent=1'
D/wpa_supplicant( 4265): nl80211: Use separate P2P group interface
D/wpa_supplicant( 4265): nl80211: Use Multi channel concurrency
,D/wpa_supplicant( 4265): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4265): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4265): nl80211: 2457-2482 @ 20 MHz
D/wpa_supplicant( 4265): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4265): nl80211: 5170-5250 @ 40 MHz
D/wpa_supplicant( 4265): nl80211: 5735-5835 @ 40 MHz
,D/wpa_supplicant( 4265): nl80211: Added 802.11b mode based on 802.11g information
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/wpa_supplicant( 4265): p2p0: Own MAC address: 36:fc:ef:de:0a:e2
D/wpa_supplicant( 4265): wpa_driver_nl80211_set_key: ifindex=22 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4265): wpa_driver_nl80211_set_key: ifindex=22 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4265): wpa_driver_nl80211_set_key: ifindex=22 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4265): wpa_driver_nl80211_set_key: ifindex=22 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4265): p2p0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 4265): nl80211: Flush PMKIDs
D/wpa_supplicant( 4265): p2p0: State: DISCONNECTED -> INACTIVE
,D/wpa_supplicant( 4265): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4265): TDLS: Driver uses internal link setup
D/wpa_supplicant( 4265): WPS: Set UUID for interface p2p0
,D/wpa_supplicant( 4265): WPS: UUID from the first interface - hexdump(len=16): 4d 54 bb 4b f9 ab 59 64 88 e9 60 e7 bf 13 d1 db
D/wpa_supplicant( 4265): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4265): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4265): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4265): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4265): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4265): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4265): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4265): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4265): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4265): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4265): Using existing control interface directory.
I/wpa_supplicant( 4265): 0xb81c7098 HY init priv-sock 23 p2p_disabled: 0 path: /data/misc/wifi/sockets/p2p0 name:/data/misc/wifi/sockets/p2p0 ctrl_interface: /data/misc/wifi/sockets, ifname: p2p0
I/wpa_supplicant( 4265): [ITEC] ASSIGN CALL BACK A4 5
I/wpa_supplicant( 4265): [ITEC] ASSIGN CALL BACK A1 6
I/wpa_supplicant( 4265): [ITEC] sizeof wpa_ssid: 544 / wpa_config: 504 / wpa_supplicant: 1456 / wpa_global: 208 in module
I/wpa_supplicant( 4265): [ITEC] Open WIFLUS socket interface - START
I/wpa_supplicant( 4265): [ITEC] SHARED LIBRARY INITIALIZED Ver: ITEC-LIB-VER-0.98 Tested @: JB44 Build Date Oct 16 2013 19:28:22
I/wpa_supplicant( 4265): [ITEC] USE NON-INET
I/wpa_supplicant( 4265): [ITEC] Open WIFLUS socket interface - DONE 24
I/wpa_supplicant( 4265): HY wiflus comm channel initialized
D/wpa_supplicant( 4265): P2P: Own listen channel: 11
I/wpa_supplicant( 4265): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
D/wpa_supplicant( 4265): P2P: Random operating channel: 81:6
D/wpa_supplicant( 4265): P2P: Add operating class 81
D/wpa_supplicant( 4265): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 4265): P2P: Add operating class 115
,D/wpa_supplicant( 4265): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 4265): P2P: wpas_p2p_pre_check_prefered_channel() - Invalid parameter. Just Initialized
D/wpa_supplicant( 4265): p2p0: Added interface p2p0
D/wpa_supplicant( 4265): p2p0: State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 4265): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4265): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4265): random: Got 20/20 bytes from /dev/random
,D/wpa_supplicant( 4265): Get randomness: len=20 entropy=0
,D/wpa_supplicant( 4265): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4265): CTRL_IFACE monitor attached - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4265): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4265): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4265): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4265): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
,D/wpa_supplicant( 4265): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4265): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4265): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4265): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4265): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4265): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4265): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
,D/wpa_supplicant( 4265): nl80211: if_removed already cleared - ignore event
,D/WifiStateMachine(  965): transitionTo: destState=SupplicantStartingState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine(  965): invokeExitMethods: InitialState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
D/WifiStateMachine(  965): invokeEnterMethods: SupplicantStartingState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131144
,D/WifiStateMachine(  965): processMsg: SupplicantStartingState
D/WifiStateMachine(  965): deferMessage: msg=131144
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131085
D/WifiStateMachine(  965): processMsg: SupplicantStartingState
D/WifiStateMachine(  965): deferMessage: msg=131085
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131149
D/WifiStateMachine(  965): processMsg: SupplicantStartingState
D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): setSuspendOptimizations: 2 true
D/WifiStateMachine(  965): mSuspendOptNeedsDisabled 0
,D/WifiStateMachine(  965): handleMessage: X
,D/WifiStateMachine(  965): handleMessage: E msg.what=131145
D/WifiStateMachine(  965): processMsg: SupplicantStartingState
D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131146
D/WifiStateMachine(  965): processMsg: SupplicantStartingState
D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131101
D/WifiStateMachine(  965): processMsg: SupplicantStartingState
D/WifiStateMachine(  965): processMsg: DefaultState
,D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147457
D/WifiStateMachine(  965): processMsg: SupplicantStartingState
D/WifiStateMachine(  965): Supplicant connection established
D/WifiNative-wlan0(  965): doString: DRIVER MACADDR
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=14): 44 52 49 56 45 52 20 4d 41 43 41 44 44 52
,D/wpa_supplicant( 4265): wlan0: Control interface command 'DRIVER MACADDR'
D/WifiNative-wlan0(  965):    returned Macaddr = 34:fc:ef:de:0a:e2
D/WifiStateMachine(  965): MAC Addr from driver = 34:fc:ef:de:0a:e2
D/WifiStateMachine(  965): setWifiState: enabled
,D/WifiOffDelayIfNotUsed(  965): setPowerSaveActivated(false)
D/WifiActivationWhileCharging(  965): unregister : we don't need to unregister
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/WifiStateMachine(  965): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine(  965): useWiFiOffloading() : false
E/WifiStateMachine(  965): CONFIG_LGE_WLAN_PATH : true
,D/WfdService( 1157): Waiting for WifiP2p enabling
D/WifiConfigStore(  965): Loading config and enabling all networks
,D/WifiNative-wlan0(  965): doString: LIST_NETWORKS
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=13): 4c 49 53 54 5f 4e 45 54 57 4f 52 4b 53
D/wpa_supplicant( 4265): wlan0: Control interface command 'LIST_NETWORKS'
D/PCSuite ( 4305): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/WifiServiceExtension(  965): WIFI_STATE_CHANGED_ACTION [3]
D/WifiNative-wlan0(  965):    returned network id / ssid / bssid / flags
D/WifiNative-wlan0(  965): 0	NG700	any	
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 ssid
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=18): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 73 73 69 64
D/wpa_supplicant( 4265): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 4265): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
,D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 bssid
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=19): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 62 73 73 69 64
D/wpa_supplicant( 4265): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 4265): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 4265): CTRL_IFACE: Failed to get network variable 'bssid'
I/WifiServiceExtension(  965): batteryPsActivateMsgHandler : state:0 event:3
,D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 priority
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 72 69 6f 72 69 74 79
D/wpa_supplicant( 4265): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 4265): CTRL_IFACE: GET_NETWORK id=0 name='priority'
,D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 scan_ssid
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=23): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 73 63 61 6e 5f 73 73 69 64
D/wpa_supplicant( 4265): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 4265): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 wep_tx_keyidx
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=27): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 74 78 5f 6b 65 79 69 64 78
D/wpa_supplicant( 4265): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
,D/wpa_supplicant( 4265): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 wep_key0
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 6b 65 79 30
D/wpa_supplicant( 4265): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 4265): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
,D/wpa_supplicant( 4265): CTRL_IFACE: Failed to get network variable 'wep_key0'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 wep_key1
E/Parcel  (  411): Reading a NULL string not supported here.
E/Parcel  (  411): Reading a NULL string not supported here.
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 6b 65 79 31
E/Parcel  (  411): Reading a NULL string not supported here.
E/Parcel  (  411): Reading a NULL string not supported here.
D/wpa_supplicant( 4265): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
E/Parcel  (  411): Reading a NULL string not supported here.
D/wpa_supplicant( 4265): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
D/wpa_supplicant( 4265): CTRL_IFACE: Failed to get network variable 'wep_key1'
E/Parcel  (  411): Reading a NULL string not supported here.
,E/Parcel  (  411): Reading a NULL string not supported here.
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 wep_key2
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 6b 65 79 32
D/wpa_supplicant( 4265): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 4265): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
,D/wpa_supplicant( 4265): CTRL_IFACE: Failed to get network variable 'wep_key2'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 wep_key3
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 6b 65 79 33
D/wpa_supplicant( 4265): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 4265): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
,D/wpa_supplicant( 4265): CTRL_IFACE: Failed to get network variable 'wep_key3'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 psk
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=17): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 73 6b
D/wpa_supplicant( 4265): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 4265): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 4265): Do not allow key_data field to be exposed
,D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 proto
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=19): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 72 6f 74 6f
D/wpa_supplicant( 4265): wlan0: Control interface command 'GET_NETWORK 0 proto'
,D/wpa_supplicant( 4265): CTRL_IFACE: GET_NETWORK id=0 name='proto'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 key_mgmt
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 6b 65 79 5f 6d 67 6d 74
D/wpa_supplicant( 4265): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
D/wpa_supplicant( 4265): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
,D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 auth_alg
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 61 75 74 68 5f 61 6c 67
D/wpa_supplicant( 4265): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
,D/wpa_supplicant( 4265): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 pairwise
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 61 69 72 77 69 73 65
D/wpa_supplicant( 4265): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
,D/wpa_supplicant( 4265): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 group
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=19): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 67 72 6f 75 70
D/wpa_supplicant( 4265): wlan0: Control interface command 'GET_NETWORK 0 group'
,D/wpa_supplicant( 4265): CTRL_IFACE: GET_NETWORK id=0 name='group'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 eap
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=17): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 65 61 70
D/wpa_supplicant( 4265): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 4265): CTRL_IFACE: GET_NETWORK id=0 name='eap'
,D/wpa_supplicant( 4265): CTRL_IFACE: Failed to get network variable 'eap'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 phase2
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=20): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 68 61 73 65 32
D/wpa_supplicant( 4265): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 4265): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
,D/wpa_supplicant( 4265): CTRL_IFACE: Failed to get network variable 'phase2'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 identity
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 69 64 65 6e 74 69 74 79
D/wpa_supplicant( 4265): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 4265): CTRL_IFACE: GET_NETWORK id=0 name='identity'
,D/wpa_supplicant( 4265): CTRL_IFACE: Failed to get network variable 'identity'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 anonymous_identity
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=32): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 61 6e 6f 6e 79 6d 6f 75 73 5f 69 64 65 6e 74 69 74 79
D/wpa_supplicant( 4265): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 4265): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
,D/wpa_supplicant( 4265): CTRL_IFACE: Failed to get network variable 'anonymous_identity'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 password
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 61 73 73 77 6f 72 64
D/wpa_supplicant( 4265): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 4265): CTRL_IFACE: GET_NETWORK id=0 name='password'
,D/wpa_supplicant( 4265): CTRL_IFACE: Failed to get network variable 'password'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 client_cert
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=25): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 63 6c 69 65 6e 74 5f 63 65 72 74
D/wpa_supplicant( 4265): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 4265): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
,D/wpa_supplicant( 4265): CTRL_IFACE: Failed to get network variable 'client_cert'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 ca_cert
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=21): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 63 61 5f 63 65 72 74
D/wpa_supplicant( 4265): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 4265): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
D/wpa_supplicant( 4265): CTRL_IFACE: Failed to get network variable 'ca_cert'
,D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 subject_match
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=27): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 73 75 62 6a 65 63 74 5f 6d 61 74 63 68
D/wpa_supplicant( 4265): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 4265): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
D/wpa_supplicant( 4265): CTRL_IFACE: Failed to get network variable 'subject_match'
,D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 engine
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=20): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 65 6e 67 69 6e 65
D/wpa_supplicant( 4265): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 4265): CTRL_IFACE: GET_NETWORK id=0 name='engine'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 engine_id
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=23): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 65 6e 67 69 6e 65 5f 69 64
D/wpa_supplicant( 4265): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 4265): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
,D/wpa_supplicant( 4265): CTRL_IFACE: Failed to get network variable 'engine_id'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 key_id
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=20): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 6b 65 79 5f 69 64
D/wpa_supplicant( 4265): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 4265): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
,D/wpa_supplicant( 4265): CTRL_IFACE: Failed to get network variable 'key_id'
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 phase1
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=20): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 68 61 73 65 31
D/wpa_supplicant( 4265): wlan0: Control interface command 'GET_NETWORK 0 phase1'
D/wpa_supplicant( 4265): CTRL_IFACE: GET_NETWORK id=0 name='phase1'
,D/wpa_supplicant( 4265): CTRL_IFACE: Failed to get network variable 'phase1'
D/WifiConfigStore(  965): ***WAPI : not WAPI
D/WifiNative-wlan0(  965): doString: GET_NETWORK 0 private_key
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=25): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 72 69 76 61 74 65 5f 6b 65 79
D/wpa_supplicant( 4265): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 4265): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
,D/wpa_supplicant( 4265): CTRL_IFACE: Failed to get network variable 'private_key'
E/WifiConfigStore(  965): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-wlan0(  965): doBoolean: SET device_name g2_open_com
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=27): 53 45 54 20 64 65 76 69 63 65 5f 6e 61 6d 65 20 67 32 5f 6f 70 65 6e 5f 63 6f 6d
D/wpa_supplicant( 4265): wlan0: Control interface command 'SET device_name g2_open_com'
D/wpa_supplicant( 4265): CTRL_IFACE SET 'device_name'='g2_open_com'
D/wpa_supplicant( 4265): device_name='g2_open_com'
I/bt_hwcfg( 1226): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 1226): Settlement delay -- 100 ms
D/WifiNative-wlan0(  965):    returned true
,D/WifiNative-wlan0(  965): doBoolean: SET manufacturer LGE
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=20): 53 45 54 20 6d 61 6e 75 66 61 63 74 75 72 65 72 20 4c 47 45
D/wpa_supplicant( 4265): wlan0: Control interface command 'SET manufacturer LGE'
D/wpa_supplicant( 4265): CTRL_IFACE SET 'manufacturer'='LGE'
D/wpa_supplicant( 4265): manufacturer='LGE'
,D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: SET model_name LG-D802
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=22): 53 45 54 20 6d 6f 64 65 6c 5f 6e 61 6d 65 20 4c 47 2d 44 38 30 32
D/wpa_supplicant( 4265): wlan0: Control interface command 'SET model_name LG-D802'
D/wpa_supplicant( 4265): CTRL_IFACE SET 'model_name'='LG-D802'
,D/wpa_supplicant( 4265): model_name='LG-D802'
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: SET model_number LG-D802
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=24): 53 45 54 20 6d 6f 64 65 6c 5f 6e 75 6d 62 65 72 20 4c 47 2d 44 38 30 32
D/wpa_supplicant( 4265): wlan0: Control interface command 'SET model_number LG-D802'
D/wpa_supplicant( 4265): CTRL_IFACE SET 'model_number'='LG-D802'
,D/wpa_supplicant( 4265): model_number='LG-D802'
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: SET serial_number 022678fb504e29b0
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=34): 53 45 54 20 73 65 72 69 61 6c 5f 6e 75 6d 62 65 72 20 30 32 32 36 37 38 66 62 35 30 34 65 32 39 ...
D/wpa_supplicant( 4265): wlan0: Control interface command 'SET serial_number 022678fb504e29b0'
D/wpa_supplicant( 4265): CTRL_IFACE SET 'serial_number'='022678fb504e29b0'
,D/wpa_supplicant( 4265): serial_number='022678fb504e29b0'
D/wpa_supplicant( 4265): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 4265): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4265): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 4265): wlan0: nl80211: scan request
D/wpa_supplicant( 4265): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/WifiNative-wlan0(  965):    returned true
,D/WifiNative-wlan0(  965): doBoolean: SET config_methods physical_display virtual_push_button keypad
D/wpa_supplicant( 4265): Scan requested (ret=0) - scan timeout 10 seconds
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=62): 53 45 54 20 63 6f 6e 66 69 67 5f 6d 65 74 68 6f 64 73 20 70 68 79 73 69 63 61 6c 5f 64 69 73 70 ...
D/wpa_supplicant( 4265): wlan0: Control interface command 'SET config_methods physical_display virtual_push_button keypad'
D/wpa_supplicant( 4265): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button keypad'
D/wpa_supplicant( 4265): config_methods='physical_display virtual_push_button keypad'
D/wpa_supplicant( 4265): nl80211: Event message available
D/wpa_supplicant( 4265): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 4265): wlan0: nl80211: Scan trigger
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: SET device_type 10-0050F204-5
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=29): 53 45 54 20 64 65 76 69 63 65 5f 74 79 70 65 20 31 30 2d 30 30 35 30 46 32 30 34 2d 35
D/wpa_supplicant( 4265): wlan0: Control interface command 'SET device_type 10-0050F204-5'
,D/wpa_supplicant( 4265): CTRL_IFACE SET 'device_type'='10-0050F204-5'
,D/WifiNative-wlan0(  965):    returned true
,W/Settings( 3308): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  965): transitionTo: destState=DriverStartedState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=3,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine(  965): invokeExitMethods: SupplicantStartingState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=2,j=1
D/WifiStateMachine(  965): moveTempStackToStateStack: i=1,j=2
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=3
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=3,startingIndex=1,Top=DriverStartedState
D/WifiStateMachine(  965): invokeEnterMethods: SupplicantStartedState
D/WifiNative-wlan0(  965): doBoolean: SCAN_INTERVAL 15
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=16): 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c 20 31 35
D/wpa_supplicant( 4265): wlan0: Control interface command 'SCAN_INTERVAL 15'
,D/wpa_supplicant( 4265): wlan0: Setting scan interval: 15 sec
D/WifiNative-wlan0(  965):    returned true
D/WifiStateMachine(  965): invokeEnterMethods: DriverStartedStateExt
D/WifiStateMachine(  965): invokeEnterMethods: DriverStartedState
D/WifiNative-wlan0(  965): doBoolean: DRIVER BTCOEXSCAN-STOP
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=22): 44 52 49 56 45 52 20 42 54 43 4f 45 58 53 43 41 4e 2d 53 54 4f 50
D/wpa_supplicant( 4265): wlan0: Control interface command 'DRIVER BTCOEXSCAN-STOP'
,D/wpa_supplicant( 4265): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  965):    returned true
D/WifiStateMachine(  965): setDetailed state, old =IDLE and new state=DISCONNECTED
,D/WifiNative-wlan0(  965): doBoolean: DRIVER RXFILTER-STOP
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=20): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 53 54 4f 50
D/wpa_supplicant( 4265): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 4265): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doBoolean: DRIVER RXFILTER-REMOVE 3
,D/LGDMClient( 2831): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 52 45 4d 4f 56 45 20 33
D/wpa_supplicant( 4265): wlan0: Control interface command 'DRIVER RXFILTER-REMOVE 3'
D/wpa_supplicant( 4265): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  965):    returned true
,D/WifiNative-wlan0(  965): doBoolean: DRIVER RXFILTER-START
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=21): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 53 54 41 52 54
D/wpa_supplicant( 4265): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 4265): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  965):    returned true
,D/WifiNative-wlan0(  965): doBoolean: DRIVER RXFILTER-STOP
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=20): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 53 54 4f 50
D/wpa_supplicant( 4265): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 4265): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  965):    returned true
,D/WifiNative-wlan0(  965): doBoolean: DRIVER RXFILTER-REMOVE 2
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 52 45 4d 4f 56 45 20 32
D/wpa_supplicant( 4265): wlan0: Control interface command 'DRIVER RXFILTER-REMOVE 2'
D/wpa_supplicant( 4265): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  965):    returned true
,D/WifiNative-wlan0(  965): doBoolean: DRIVER RXFILTER-START
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=21): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 53 54 41 52 54
D/wpa_supplicant( 4265): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 4265): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  965):    returned true
,D/WifiStateMachine(  965): Attempting to reconnect to wifi network ..
D/WifiNative-wlan0(  965): doBoolean: RECONNECT
D/LGDMClient( 2831): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
,D/wpa_supplicant( 4265): wlan0: Control interface command 'RECONNECT'
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doString: STATUS
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 4265): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 4265): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/WifiNative-wlan0(  965):    returned wpa_state=SCANNING
D/WifiNative-wlan0(  965): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  965): address=34:fc:ef:de:0a:e2
D/WifiStateMachine(  965): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  965): handleScreenStateChanged: true
,D/WifiNative-wlan0(  965): doBoolean: SET ps 1
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 4265): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 4265): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 4265): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  965):    returned true
,D/WifiP2pService(  965): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  264): Setting iface cfg
D/CommandListener(  264): Trying to bring up p2p0
D/WifiMonitor(  965): WifiMonitorSingleton gotten
,D/WifiMonitor(  965): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService(  965): P2pEnablingState
D/WifiP2pService(  965): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  965): P2p socket connection successful
D/WifiP2pService(  965): P2pEnabledState
,D/WifiStateMachine(  965): moveDeferredMessageAtFrontOfQueue; what=131085
D/WifiStateMachine(  965): moveDeferredMessageAtFrontOfQueue; what=131144
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=DriverStartedStateExt
D/WifiStateMachine(  965): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=DisconnectedState
,D/WifiStateMachine(  965): invokeEnterMethods: ConnectModeState
,D/WifiStateMachine(  965): invokeEnterMethods: DisconnectedState
,V/WfdStateTracker( 1157): WfdStateTracker handleDirectStateChangedEvent: 2
D/WifiNative-p2p0(  965): doBoolean: SET persistent_reconnect 1
D/WifiStateMachine(  965): handleMessage: X
,D/WifiStateMachine(  965): handleMessage: E msg.what=131144
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=26): 53 45 54 20 70 65 72 73 69 73 74 65 6e 74 5f 72 65 63 6f 6e 6e 65 63 74 20 31
D/wpa_supplicant( 4265): p2p0: Control interface command 'SET persistent_reconnect 1'
D/wpa_supplicant( 4265): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 4265): persistent_reconnect=1
D/wpa_supplicant( 4265): P2P: New SSID postfix: -Thali Test's G2
,D/WifiNative-p2p0(  965):    returned true
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131085
D/WifiStateMachine(  965): processMsg: DisconnectedState
,D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiNative-p2p0(  965): doBoolean: SET device_name Thali Test's G2
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): handleMessage: X
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=31): 53 45 54 20 64 65 76 69 63 65 5f 6e 61 6d 65 20 54 68 61 6c 69 20 54 65 73 74 27 73 20 47 32
D/wpa_supplicant( 4265): p2p0: Control interface command 'SET device_name Thali Test's G2'
D/wpa_supplicant( 4265): CTRL_IFACE SET 'device_name'='Thali Test's G2'
D/wpa_supplicant( 4265): device_name='Thali Test's G2'
D/WifiStateMachine(  965): handleMessage: E msg.what=132106
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  965): setWifiDualbandAPConnection band : 1
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=21): 44 55 41 4c 42 41 4e 44 5f 41 50 5f 43 4f 4e 4e 45 43 54 20 31
D/wpa_supplicant( 4265): wlan0: Control interface command 'DUALBAND_AP_CONNECT 1'
E/wpa_supplicant( 4265): nWIFIDualbandAPConnection: 1
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=132096
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  965): set CMD_DISCONNECT_RSSI_LVL : -100
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=24): 44 49 53 43 4f 4e 4e 45 43 54 5f 52 53 53 49 5f 4c 56 4c 20 2d 31 30 30
D/wpa_supplicant( 4265): wlan0: Control interface command 'DISCONNECT_RSSI_LVL -100'
E/wpa_supplicant( 4265): disconnect_rssi_lvl: -100
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
,D/WifiStateMachine(  965): setDetailed state, old =SCANNING and new state=SCANNING
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiNative-p2p0(  965):    returned true
D/WifiServiceExtension(  965): postfix byte check : 15
D/WifiStateMachine(  965): handleMessage: X
D/WifiNative-p2p0(  965): doBoolean: SET p2p_ssid_postfix -Thali Test's G2
D/WifiStateMachine(  965): handleMessage: E msg.what=131154
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=37): 53 45 54 20 70 32 70 5f 73 73 69 64 5f 70 6f 73 74 66 69 78 20 2d 54 68 61 6c 69 20 54 65 73 74 ...
D/wpa_supplicant( 4265): p2p0: Control interface command 'SET p2p_ssid_postfix -Thali Test's G2'
D/wpa_supplicant( 4265): CTRL_IFACE SET 'p2p_ssid_postfix'='-Thali Test's G2'
D/wpa_supplicant( 4265): p2p_ssid_postfix='-Thali Test's G2'
,D/wpa_supplicant( 4265): P2P: New SSID postfix: -Thali Test's G2
I/ActivityManager(  965): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4347 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/WifiP2pService(  965): sending p2p connection changed broadcast
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
D/WifiP2pService(  965): [LGE_P2P] initializeP2pSettings() check postfix
D/WifiP2pService(  965): before postfix = Thali Test's G2
,D/WifiP2pService(  965): after postfix = Thali Test's G2
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiNative-p2p0(  965):    returned true
D/WifiNative-p2p0(  965): doBoolean: SET device_type 10-0050F204-5
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=29): 53 45 54 20 64 65 76 69 63 65 5f 74 79 70 65 20 31 30 2d 30 30 35 30 46 32 30 34 2d 35
D/wpa_supplicant( 4265): p2p0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 4265): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): handleMessage: X
D/WifiNative-p2p0(  965):    returned true
D/WifiNative-p2p0(  965): doBoolean: SET config_methods virtual_push_button physical_display keypad
D/WifiStateMachine(  965): handleMessage: E msg.what=131127
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=62): 53 45 54 20 63 6f 6e 66 69 67 5f 6d 65 74 68 6f 64 73 20 76 69 72 74 75 61 6c 5f 70 75 73 68 5f ...
D/wpa_supplicant( 4265): p2p0: Control interface command 'SET config_methods virtual_push_button physical_display keypad'
D/wpa_supplicant( 4265): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4265): config_methods='virtual_push_button physical_display keypad'
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131158
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiNative-p2p0(  965):    returned true
D/WifiNative-p2p0(  965): doBoolean: P2P_SET conc_pref sta
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=143371
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=21): 50 32 50 5f 53 45 54 20 63 6f 6e 63 5f 70 72 65 66 20 73 74 61
D/wpa_supplicant( 4265): p2p0: Control interface command 'P2P_SET conc_pref sta'
D/wpa_supplicant( 4265): Single channel concurrency preference: sta
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiNative-p2p0(  965):    returned true
D/WifiNative-p2p0(  965): doString: STATUS
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiStateMachine(  965): processMsg: DefaultState
D/wpa_supplicant( 4265): RX global ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/WifiStateMachine(  965): handleMessage: X
D/WifiNative-p2p0(  965):    returned p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-p2p0(  965): p2p_state=IDLE
D/WifiNative-p2p0(  965): wifi_display=1
D/WifiNative-p2p0(  965): ifname=p2p0
D/WifiNative-p2p0(  965): address=36:fc:ef:de:0a:e2
D/WifiNative-p2p0(  965): ifname=wlan0
D/WifiNative-p2p0(  965): address=34:fc:ef:de:0a:e2
D/WifiNative-p2p0(  965): doBoolean: P2P_FLUSH
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=9): 50 32 50 5f 46 4c 55 53 48
D/wpa_supplicant( 4265): p2p0: Control interface command 'P2P_FLUSH'
D/wpa_supplicant( 4265): P2P: Stopping find
D/wpa_supplicant( 4265): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 4265): P2P: State IDLE -> IDLE
D/wpa_supplicant( 4265): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiNative-p2p0(  965):    returned true
D/WifiNative-p2p0(  965): doBoolean: P2P_SERVICE_FLUSH
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=17): 50 32 50 5f 53 45 52 56 49 43 45 5f 46 4c 55 53 48
D/wpa_supplicant( 4265): p2p0: Control interface command ,'P2P_SERVICE_FLUSH'
D/WifiNative-p2p0(  965):    returned true
D/WifiNative-p2p0(  965): doString: LIST_NETWORKS
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=13): 4c 49 53 54 5f 4e 45 54 57 4f 52 4b 53
D/wpa_supplicant( 4265): p2p0: Control interface command 'LIST_NETWORKS'
D/WifiNative-p2p0(  965):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0(  965): doBoolean: SAVE_CONFIG
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=11): 53 41 56 45 5f 43 4f 4e 46 49 47
D/wpa_supplicant( 4265): p2p0: Control interface command 'SAVE_CONFIG'
,D/wpa_supplicant( 4265): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf.tmp'
,I/WfdStateTracker( 1157): handleP2pThisDeviceChanged
,D/WifiP2pService(  965): DeviceAddress: 36:fc:ef:de:0a:e2
D/HyLog   ( 4347): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4347): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4347): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/wpa_supplicant( 4265): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
,D/wpa_supplicant( 4265): CTRL_IFACE: SAVE_CONFIG - Configuration updated
,D/WifiNative-p2p0(  965):    returned true
,E/WifiServiceExtension(  965): No p2p device connected
,D/LGDMSGCM( 4347): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.wifi.supplicant.CONNECTION_CHANGE
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiP2pService(  965): sending p2p persistent groups changed broadcast
D/WifiP2pService(  965): InactiveState
D/WifiP2pService(  965): InactiveState{ when=-10ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  965): P2pEnabledState{ when=-10ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  965): DefaultState{ when=-10ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  965): InactiveState{ when=-10ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  965): P2pEnabledState{ when=-10ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  965): DefaultState{ when=-10ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl( 4347): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  965): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4361 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  965): Killing 3852:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327ac48 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a035a0 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4361): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4361): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4361): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/bt_hwcfg( 1226): bt vendor lib: set UART baud 4000000
,I/bt_hwcfg( 1226): Setting local bd addr to 34:FC:EF:9D:93:0B
,I/Wireless_Storage( 4361): CONNECT : WIFI_P2P_STATE_CHANGED_ACTION
,V/[BNRBootReceiver]( 4110): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/BNRAndroBeam( 4110): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,I/ActivityManager(  965): Killing 3308:com.google.android.talk/u0a77 (adj 15): empty #17
,I/bt_hwcfg( 1226): vendor lib fwcfg completed
I/bt-btif ( 1226): HC preload_cb 0 [0:SUCCESS 1:FAIL]
I/        ( 1226): BTE_InitTraceLevels -- TRC_HCI
I/        ( 1226): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 1226): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 1226): BTE_InitTraceLevels -- TRC_OBEX
I/        ( 1226): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 1226): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 1226): BTE_InitTraceLevels -- TRC_A2D
I/        ( 1226): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 1226): BTE_InitTraceLevels -- TRC_BTM
I/        ( 1226): BTE_InitTraceLevels -- TRC_GAP
I/        ( 1226): BTE_InitTraceLevels -- TRC_PAN
I/        ( 1226): BTE_InitTraceLevels -- TRC_SAP
I/        ( 1226): BTE_InitTraceLevels -- TRC_SDP
I/        ( 1226): BTE_InitTraceLevels -- TRC_GATT
I/        ( 1226): BTE_InitTraceLevels -- TRC_SMP
I/        ( 1226): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 1226): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 1226): BTE_InitTraceLevels -- TRC_PROTOCOL
D/bt-btif ( 1226): btif_task(): received trigger stack init event, state: 1, radio_ref_count: 1, is_radio_req 0, dut_mode: 0
D/bt-btif ( 1226): btif_dm_load_ble_local_keys BLE ER key loaded
D/bt-btif ( 1226): btif_dm_load_ble_local_keys BLE ID keys loaded
I/bt-btif ( 1226): bta_dm_sm_execute event:0x0
I/bt-btif ( 1226): bta_sys_sm_execute state:0, event:0x0
I/bt-btif ( 1226): bta_sys_hw_api_enable for 0, active modules 0x0001
I/bt-btif ( 1226): bta_sys_sm_execute state:1, event:0x1
,I/bt-btif ( 1226): bta_sys_hw_evt_enabled for 0
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327ac48 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a035a0 u0 com.test.thalitest/.MainActivity t3}
,D/bt-btif ( 1226):  bta_sys_hw_btm_cback was called with parameter: 0
I/bt-btif ( 1226): bta_sys_sm_execute state:1, event:0x2
D/bt-btif ( 1226):  bta_sys_hw_evt_stack_enabled!notify the callers
D/bt-btif ( 1226):  bta_dm_sys_hw_cback with event: 1
D/bt-btif ( 1226): ##################################
D/bt-btif ( 1226): bta_dm_co_ble_load_local_keys:  Load local keys if any are persisted
D/bt-btif ( 1226): ##################################
D/bt-btif ( 1226): btif_dm_get_ble_local_keys  *p_key_mask=0x03
E/bt-btm  ( 1226): BTM_SecRegister:p_cb_info->p_le_callback == 0x60b5a4c5 
I/bt-smp  ( 1226): SMP_Register state=0
E/bt-btm  ( 1226): BTM_SecRegister: btm_cb.api.p_le_callback = 0x60b5a4c5 
D/bt-btif ( 1226): bta_gattc_register state 0
D/bt-btif ( 1226): bta_gattc_enable
I/bt-att  ( 1226): GATT_Register
D/bt-att  ( 1226): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 1226): allocated gatt_if=3
D/bt-btif ( 1226): bta_dm_gattc_callback event = 0
D/bt-btif ( 1226): BTA_GATTC_REG_EVT client_if = 3
I/bt-att  ( 1226): GATT_StartIf gatt_if=3
D/bt-att  ( 1226): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 1226): gatt_find_the_connected_bda found=0 found_idx=7
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/bt-btif ( 1226): btif_dm_upstreams_cback  ev: BTA_DM_ENABLE_EVT
D/bt-btif ( 1226): btif_storage_get_adapter_property property->type:1 
D/bt-btif ( 1226): in, bd addr:, prop type:1, len:249
,I/bt-btif ( 1226): bta_dm_sm_execute event:0x2
D/bt-btif ( 1226): BTA is generating EIR
D/bt-sdp  ( 1226): SDP_CreateRecord ok, num_records:3
I/bt-btif ( 1226): Adding UUID=0x110C into EIR
D/bt-btif ( 1226): BTA is generating EIR
I/bt-btif ( 1226): bta_dm_eir_update_uuid UUID bit mask=0x00000000 00001000
D/bt-btif ( 1226): nsc_mask: 0x6
D/bt-btif ( 1226): bta_av_co_audio_init
D/bt-btif ( 1226): bta_av_co_audio_init: 0
D/bt-btif ( 1226): audio[0] av_handle: 1 codec_type: 0
D/bt-btif ( 1226): bta_av_co_audio_init
D/bt-btif ( 1226): bta_av_co_audio_init: 1
D/bt-btif ( 1226): BTIF_APTX_CODEC_ID:6
D/bt-btif ( 1226): audio[1] av_handle: 2 codec_type: 255
D/bt-sdp  ( 1226): SDP_CreateRecord ok, num_records:4
I/bt-a2d  ( 1226): A2D_AddRecord uuid: 110a
I/bt-btif ( 1226): Adding UUID=0x110A into EIR
D/bt-btif ( 1226): BTA is generating EIR
I/bt-btif ( 1226): bta_dm_eir_update_uuid UUID bit mask=0x00000000 00001400
D/bt-btif ( 1226): rc_acp_handle:0 idx:1
D/bt-btif ( 1226): create 0, role: 1, shdl:0, rc_handle:0, lidx:3, status:0x10
D/bt-btif ( 1226): reg_audio: 0x1
D/bt-btif ( 1226): bta_ag_scb_alloc 1
I/bt-btif ( 1226): AG evt (hdl 0x0001): State 0, Event 0x0500
D/bt-sdp  ( 1226): SDP_CreateRecord ok, num_records:5
D/bt-btif ( 1226): bta_ag_add_record uuid: 1112
I/bt-btif ( 1226): Adding UUID=0x1112 into EIR
D/bt-btif ( 1226): BTA is generating EIR
I/bt-btif ( 1226): bta_dm_eir_update_uuid UUID bit mask=0x00000000 00011400
D/bt-sdp  ( 1226): SDP_CreateRecord ok, num_records:6
D/bt-btif ( 1226): bta_ag_add_record uuid: 111f
I/bt-btif ( 1226): Adding UUID=0x111F into EIR
D/bt-btif ( 1226): BTA is generating EIR
I/bt-btif ( 1226): bta_dm_eir_update_uuid UUID bit mask=0x00000000 04011400
D/bt-btif ( 1226): getAccess buffer->st_uid:1000 buffer->st_gid:1028
,D/bt-btif ( 1226): bta_fts_api_enable srm:1
D/bt-sdp  ( 1226): SDP_CreateRecord ok, num_records:7
I/bt-btif ( 1226): Adding UUID=0x1106 into EIR
D/bt-btif ( 1226): BTA is generating EIR
I/bt-btif ( 1226): bta_dm_eir_update_uuid UUID bit mask=0x00000000 04011440
D/bt-btif ( 1226): FTS:  SDP Registered (handle 0x00010006)
I/bt-btif ( 1226): bta_fts_ci_resume status:1
I/bt-btif ( 1226): FTP SERVER enabled with Root Path [/storage]
D/bt-sdp  ( 1226): SDP_CreateRecord ok, num_records:8
I/bt-btif ( 1226): Adding UUID=0x112D into EIR
D/bt-btif ( 1226): BTA is generating EIR
I/bt-btif ( 1226): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04011440
D/bt-btif ( 1226): bte_sap_evt: event=0
E/bt-btif ( 1226): Calling BTA_HhEnable
D/bt-btif ( 1226): bta_gattc_register state 2
I/bt-att  ( 1226): GATT_Register
D/bt-att  ( 1226): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 1226): allocated gatt_if=4
D/bt-btif ( 1226): bta_hh_gattc_callback event = 0
,I/bt-att  ( 1226): GATT_StartIf gatt_if=4
D/bt-att  ( 1226): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 1226): gatt_find_the_connected_bda found=0 found_idx=7
D/bt-btif ( 1226): in add:1
D/bt-btif ( 1226): Remote device:00:f4:6f:30:e0:6c, size:18
D/bt-btif ( 1226): Remote device:f8:95:c7:87:3c:51, size:18
D/bt-btif ( 1226): Remote device:e0:db:10:1f:c9:5e, size:18
D/bt-btif ( 1226): Remote device:b0:c5:59:3f:75:69, size:18
D/bt-btif ( 1226): Remote device:14:b4:84:21:3b:49, size:18
D/bt-btif ( 1226): Remote device:80:01:84:8a:b3:68, size:18
D/bt-btif ( 1226): Remote device:58:3f:54:73:64:c0, size:18
D/bt-btif ( 1226): Remote device:10:d3:8a:fb:85:d4, size:18
D/bt-btif ( 1226): Remote device:b4:ce:f6:ab:a4:6a, size:18
D/bt-btif ( 1226): Remote device:08:ec:a9:50:75:41, size:18
D/bt-btif ( 1226): Remote device:f8:cf:c5:d9:e5:61, size:18
D/bt-btif ( 1226): Remote device:08:ec:a9:50:76:27, size:18
D/bt-btif ( 1226): Remote device:7c:f9:0e:51:18:22, size:18
D/bt-btif ( 1226): Remote device:44:80:eb:7b:5a:05, size:18
D/bt-btif ( 1226): Remote device:50:2e:6c:ac:21:50, size:18
D/bt-btif ( 1226): Remote device:7c:f9:0e:37:96:ab, size:18
D/bt-btif ( 1226): Remote device:f4:f1:e1:5c:3b:e2, size:18
D/bt-btif ( 1226): Remote device:34:fc:ef:11:ae:67, size:18
D/bt-btif ( 1226): Remote device:f8:95:c7:87:85:54, size:18
D/bt-btif ( 1226): Remote device:7c:f9:0e:34:8a:a0, size:18
D/bt-btif ( 1226): Remote device:e0:db:10:14:e2:c0, size:18
I/bt-btif ( 1226): bta_dm_sm_execute event:0x9
D/bt-btif ( 1226): Remote device:34:fc:ef:11:b1:66, size:18
D/bt-btif ( 1226): Remote device:90:e7:c4:f6:69:77, size:18
D/bt-btif ( 1226): Remote device:90:e7:c4:3c:62:6a, size:18
D/bt-btif ( 1226): Remote device:58:2a:f7:ed:96:be, size:18
D/bt-btif ( 1226): Remote device:38:94:96:b5:06:dc, size:18
I/bt-btif ( 1226): bta_dm_sm_execute event:0x9
D/bt-btif ( 1226): Remote device:, size:128
E/bt-btif ( 1226): ## btif_config_get assert section && *section && key && *key && name && *name && bytes && type failed at line:211 ##
E/bt-btif ( 1226): ## btif_config_get assert section && *section && key && *key && name && *name && bytes && type failed at line:211 ##
D/bt-btif ( 1226): out
D/bt-btif ( 1226): btif_storage_get_adapter_property property->type:2 
D/bt-btif ( 1226): btif_storage_get_adapter_property property->type:1 
,D/bt-btif ( 1226): in, bd addr:, prop type:1, len:249
I/bt-btif ( 1226): btif_storage_load_bonded_devices  BT_PROPERTY_DEVICE_MODE
D/bt-btif ( 1226): btif_storage_get_adapter_property property->type:16 
D/bt-btif ( 1226): in, bd addr:, prop type:16, len:4
E/bt-btif ( 1226): Unknow prop type:16
I/bt-btif ( 1226): btif_dm_get_adapter_property: type=0x10
D/bt-btif ( 1226): btif_dm_get_adapter_property btif_device_mode 0
D/bt-btif ( 1226): btif_storage_get_adapter_property property->type:9 
D/bt-btif ( 1226): in, bd addr:, prop type:9, len:4
D/bt-btif ( 1226): btif_storage_get_adapter_property property->type:3 
E/bt-btif ( 1226): btif_storage_get_adapter_property service_mask:0x120148
D/bt-btif ( 1226): btif_storage_get_adapter_property property->type:3 devicemode 0
D/bt-btif ( 1226): btif_storage_get_adapter_property property->type:3 devicemode 0
D/bt-btif ( 1226): btif_storage_get_adapter_property property->type:3 devicemode 0
D/bt-btif ( 1226): btif_storage_get_adapter_property property->type:3 devicemode 0
D/bt-btif ( 1226): btif_storage_get_adapter_property property->type:3 devicemode 0
,I/bt-btif ( 1226): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothManagerService(  965): Bluetooth Adapter name changed to Thali Test's G2
,D/BluetoothManagerService(  965): Stored Bluetooth name: Thali Test's G2
,E/BluetoothAdapterProperties( 1226): Property change not handled in Java land:16
I/bt-btif ( 1226): btif_storage_load_bonded_devices: 2 bonded devices found
D/bt-btif ( 1226): in, bd addr:e0:db:10:14:e2:c0, prop type:1, len:249
D/bt-btif ( 1226): in, bd addr:e0:db:10:14:e2:c0, prop type:10, len:249
D/bt-btif ( 1226): in, bd addr:e0:db:10:14:e2:c0, prop type:4, len:4
D/bt-btif ( 1226): in, bd addr:e0:db:10:14:e2:c0, prop type:5, len:4
D/bt-btif ( 1226): in, bd addr:e0:db:10:14:e2:c0, prop type:3, len:512
,I/bt-btif ( 1226): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 1226): devicePropertyChangedCallback: bdDevice: E0:DB:10:14:E2:C0, value is empty for type: 10
I/LGRemoteDevicePropertySetting( 1226): [BTUI] remoteDeviceSetProperties
,I/LGRemoteDevicePropertySetting( 1226): [BTUI] Get BRCM HeadsetService
D/bt-btif ( 1226): in, bd addr:38:94:96:b5:06:dc, prop type:1, len:249
D/bt-btif ( 1226): in, bd addr:38:94:96:b5:06:dc, prop type:10, len:249
D/bt-btif ( 1226): in, bd addr:38:94:96:b5:06:dc, prop type:4, len:4
D/bt-btif ( 1226): in, bd addr:38:94:96:b5:06:dc, prop type:5, len:4
D/bt-btif ( 1226): in, bd addr:38:94:96:b5:06:dc, prop type:3, len:512
,I/bt-btif ( 1226): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 1226): devicePropertyChangedCallback: bdDevice: 38:94:96:B5:06:DC, value is empty for type: 10
I/LGRemoteDevicePropertySetting( 1226): [BTUI] remoteDeviceSetProperties
,I/LGRemoteDevicePropertySetting( 1226): [BTUI] Get BRCM HeadsetService
D/bt-btif ( 1226): btif_enable_bluetooth_evt: status 0, local bd [34:fc:ef:9d:93:0b]
E/bt_hwcfg( 1226): hw_sco_config...
,E/bt_hwcfg( 1226): SCO PCM configure {0, 4, 0, 0, 0}
I/bt-btif ( 1226): HC lib lpm enable=1 return 0
I/bt-btif ( 1226): BTA_BrcmInit
E/bt-gki  ( 1226): ### ERROR: incorrect Process context BTIF called function btu_start_timer() ###
,D/IOP_DB_BT( 1226): db_open: file /etc/bluetooth/iop_bt.db
,I/bt-btif ( 1226): HC lpm_result_cb 1
D/IOP_DB_BT( 1226): db_open: db_open : handle 1623489068l, read 7547 bytes onto local cache
D/IOP_DB_BT( 1226): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 1226): db_query: result 1
,I/        ( 1226): iop_db_open: iop_db_open status 0
D/bt-btif ( 1226): btsock initializing...
D/bt-btif ( 1226): in initialized:1
D/bt-btif ( 1226): ts[7].used:1
D/bt-btif ( 1226): ts[6].used:0
D/bt-btif ( 1226): alloc_thread_slot ret:6
D/bt-btif ( 1226): h:6, cmd_fdr:87, cmd_fdw:88
D/bt-btif ( 1226): h:6, thread id:1621810928
I/bt-btif ( 1226): BTA_JvEnable
,D/bt-btif ( 1226): btsock successfully initialized
D/bt-btif ( 1226): jni_initialized = 1, btpan_cb.enabled:0
D/bt-btif ( 1226): Enabling PAN....
D/bt-btif ( 1226): jv_dm_cback: event:0, slot id:0
D/bt-btif ( 1226): unhandled event:0, slot id:0
D/bt-btif ( 1226): local_role:3
I/bt-btif ( 1226): bta_pan_co_init
D/bt-btif ( 1226): btpan_role:0x3
I/bte_conf( 1226): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/bt-sdp  ( 1226): SDP_CreateRecord ok, num_records:9
I/bt-btif ( 1226): Adding UUID=0x1116 into EIR
D/bt-btif ( 1226): BTA is generating EIR
I/bt-btif ( 1226): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04051440
I/bt-btif ( 1226): Adding UUID=0x1115 into EIR
D/bt-btif ( 1226): BTA is generating EIR
I/bt-btif ( 1226): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
I/bt-btif ( 1226): Adding UUID=0x1116 into EIR
D/bt-btif ( 1226): BTA is generating EIR
I/bt-btif ( 1226): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
I/bt-btif ( 1226): Removing UUID=0x1117 from EIR
D/bt-btif ( 1226): BTA is generating EIR
I/bt-btif ( 1226): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
I/bt-btif ( 1226): Adding UUID=0x1115 into EIR
D/bt-btif ( 1226): BTA is generating EIR
,I/bt-btif ( 1226): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
I/bte_conf( 1226): [1] primary_record=1 vendor_id=0x00C4 vendor_id_source=0x0001 product_id=0x13A1 version=0x1000
I/bte_conf( 1226): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bt-btif ( 1226): bta_dm_sm_execute event:0x31
D/bt-sdp  ( 1226): SDP_CreateRecord ok, num_records:10
I/bt-btif ( 1226): Adding UUID=0x1200 into EIR
D/bt-btif ( 1226): BTA is generating EIR
I/bt-btif ( 1226): bta_dm_eir_update_uuid UUID bit mask=0x00000084 04071440
I/bt-btif ( 1226): bte did registered::handle: 0x10009, bta status: 0 (0==OK)
I/bte_conf( 1226): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,D/bt-btif ( 1226): btif_dm_load_local_oob prop_oob = 3
I/bt-btif ( 1226): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothServiceJni( 1226): adapter_state_change_callback: Status is: 1
D/bt-btif ( 1226): btif_av_state_idle_handler event:BTA_AV_ENABLE_EVT flags 0
,D/BluetoothAdapterState( 1226): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 1226): ScanMode =  20
D/bt-btif ( 1226): btif_av_state_idle_handler event:BTA_AV_REGISTER_EVT flags 0
D/bt-btif ( 1226): btif_av_state_idle_handler devicemode: 0
D/bt-btif ( 1226): btif_hf_upstreams_evt: event=BTA_AG_ENABLE_EVT
D/bt-btif ( 1226): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/bt-btif ( 1226): btif_fts_upstreams_evt: event=BTA_FTS_ENABLE_EVT
I/bt-btif ( 1226): File Transfer: Enable Complete
I/bt-btif ( 1226): HAL bt_fts_callbacks->operation_cmpl_cb
D/BluetoothFTPServiceJni( 1226): operation_cmpl_callback(L192):  oper:3 status:0
I/BluetoothFTPService( 1226): onFtpServerEnabled: /storage
D/bt-btif ( 1226): btif_sc_upstreams_evt: event=BTA_SC_ENABLE_EVT
D/bt-btif ( 1226): btif_hh_upstreams_evt: event=BTA_HH_ENABLE_EVT
D/bt-btif ( 1226): btif_hh_upstreams_evt: BTA_HH_ENABLE_EVT: status =0
D/bt-btif ( 1226): btif_hh_upstreams_evt--Loading added devices
D/bt-btif ( 1226): Remote device:00:f4:6f:30:e0:6c, size:18
D/bt-btif ( 1226): Remote device:f8:95:c7:87:3c:51, size:18
D/bt-btif ( 1226): Remote device:e0:db:10:1f:c9:5e, size:18
D/bt-btif ( 1226): Remote device:b0:c5:59:3f:75:69, size:18
D/bt-btif ( 1226): Remote device:14:b4:84:21:3b:49, size:18
D/bt-btif ( 1226): Remote device:80:01:84:8a:b3:68, size:18
D/bt-btif ( 1226): Remote device:58:3f:54:73:64:c0, size:18
,D/bt-btif ( 1226): Remote device:10:d3:8a:fb:85:d4, size:18
D/BluetoothAdapterProperties( 1226): State =  11
D/bt-btif ( 1226): Remote device:b4:ce:f6:ab:a4:6a, size:18
D/bt-btif ( 1226): Remote device:08:ec:a9:50:75:41, size:18
D/bt-btif ( 1226): Remote device:f8:cf:c5:d9:e5:61, size:18
D/bt-btif ( 1226): Remote device:08:ec:a9:50:76:27, size:18
D/bt-btif ( 1226): Remote device:7c:f9:0e:51:18:22, size:18
D/bt-btif ( 1226): Remote device:44:80:eb:7b:5a:05, size:18
D/bt-btif ( 1226): Remote device:50:2e:6c:ac:21:50, size:18
D/bt-btif ( 1226): Remote device:7c:f9:0e:37:96:ab, size:18
,D/bt-btif ( 1226): Remote device:f4:f1:e1:5c:3b:e2, size:18
D/bt-btif ( 1226): Remote device:34:fc:ef:11:ae:67, size:18
D/bt-btif ( 1226): Remote device:f8:95:c7:87:85:54, size:18
D/bt-btif ( 1226): Remote device:7c:f9:0e:34:8a:a0, size:18
D/bt-btif ( 1226): Remote device:e0:db:10:14:e2:c0, size:18
D/bt-btif ( 1226): Remote device:34:fc:ef:11:b1:66, size:18
D/bt-btif ( 1226): Remote device:90:e7:c4:f6:69:77, size:18
D/bt-btif ( 1226): Remote device:90:e7:c4:3c:62:6a, size:18
D/bt-btif ( 1226): Remote device:58:2a:f7:ed:96:be, size:18
D/bt-btif ( 1226): Remote device:38:94:96:b5:06:dc, size:18
D/bt-btif ( 1226): Remote device:, size:18
E/bt-btif ( 1226): ## btif_config_get assert section && *section && key && *key && name && *name && bytes && type failed at line:211 ##
D/bt-btif ( 1226): BTA_PAN_ENABLE_EVT
D/bt-btif ( 1226): bta_pan_role:0x5
D/BluetoothPanServiceJni( 1226): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
D/BluetoothAdapterProperties( 1226): mDiscoverableTimeout =  120
,I/bt-btif ( 1226): btif_set_adapter_property type: 7, len 4, 0x428fba68
I/bt-btif ( 1226): set property scan mode : 1
I/bt-btif ( 1226): bta_dm_sm_execute event:0x3
I/bt-btif ( 1226): btif_in_storage_request_copy_cb
I/bt-btif ( 1226): execute storage request event : 2
I/bt-btif ( 1226): type: 7, len 4, 0x60671032
I/bt-btif ( 1226): btif_in_storage_request_co
D/bt-btif ( 1226): in, bd addr:, prop type:7, len:4
I/bt-btif ( 1226): HAL bt_hal_cbacks->adapter_properties_cb
I/bt-btif ( 1226): HAL bt_hal_cbacks->adapter_prop
I/BluetoothAdapterState( 1226): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterService( 1226): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  965): Message: 60
D/BluetoothManagerService(  965): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  965): Broadcasting onBluetoothStateChange(true) to 6 receivers.
,D/BluetoothPan(  965): onBluetoothStateChange(on) call bindService
I/bt-btif ( 1226): execute storage request event : 2
I/bt-btif ( 1226): type: 9, len 4, 0x606710ca
D/bt-btif ( 1226): in, bd addr:, prop type:9, len:4
,I/bt-btif ( 1226): HAL bt_hal_cbacks->adapter_properties_cb
V/BluetoothAdapterService( 1226): startPbapService
,D/BluetoothHeadset(  965): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1451): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1451): onBluetoothStateChange: up=true
D/BluetoothA2dp(  965): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1451): onBluetoothStateChange: up=true
,I/BluetoothAdapterState( 1226): Entering On State
D/LGBluetoothServiceAdapter( 1226): [BTUI] OnState
D/LGBluetoothServiceAdapter( 1226): [BTUI]         global_name: Thali Test's G2
D/LGBluetoothServiceAdapter( 1226): [BTUI]         local_name: Thali Test's G2
,D/BluetoothManagerService(  965): Bluetooth State Change Intent: 11 -> 12
D/BluetoothAdapterService(1116287648)( 1226): Quiet mode Enabled = false
D/BluetoothAdapterService(1116287648)( 1226): Initiate auto connection on BT on...
,D/BluetoothAdapterService( 1226): [BTUI] autoConnect() : not allowed
D/LGBluetoothAPIService( 1157): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1157): Message: 1
,D/LGBluetoothAPIService( 1157): MESSAGE_BOOT_COMPLETED
D/bt_h4   ( 1226): vendor lib postload completed
,I/bt-btif ( 1226): HC postload_cb 0
,D/BluetoothAdapterService(1116287648)( 1226): Get Bonded Devices being called
,W/ContextImpl(  965): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:192 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:510 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1164 
D/BluetoothAdapterService( 1226): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@428932a0
V/BluetoothPbapService( 1226): Pbap Service onCreate
V/BluetoothPbapService( 1226): Starting PBAP service
I/LGBluetoothAPIService( 1157): [BTUI] LGBluetoothAPIService Binding Success
D/LGBluetoothPbapAdapter( 1226): [BTUI] getInstance : create
V/BluetoothPbapService( 1226): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 1226): state: 12
D/BluetoothManagerService(  965): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  965): Message: 40
D/BluetoothManagerService(  965): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothMapService( 1226): onReceive
D/BluetoothMapService( 1226): STATE_ON
V/BluetoothPbapService( 1226): Handler(): got msg=1
,V/BluetoothPbapService( 1226): Pbap Service startRfcommSocketListener
,V/BluetoothPbapService( 1226): Pbap Service initSocket
,W/ContextImpl( 2558): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:156 com.android.settings.bluetooth.DockEventReceiver.onReceive:123 
D/LGBluetoothAPIServer( 1226): [BTUI] onCreate()
D/LGBluetoothAPIServer( 1226): [BTUI] onBind()
V/BluetoothMapService( 1226): Handler(): got msg=1
D/LGBluetoothAPIService( 1157): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1157): Message: 100
D/LGBluetoothAPIService( 1157): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,D/BluetoothManagerService(  965): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothMapService( 1226): Map Service startRfcommSocketListener
W/BluetoothAdapter( 1226): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 1226): SOCK FLAG = 1 ***********************
D/bt-btif ( 1226): btsock_rfc_listen, service_name:OBEX Phonebook Access Server
D/bt-btif ( 1226): BTA_JvCreateRecordByUser:OBEX Phonebook Access Server
I/bt-btif ( 1226): BTA_JvCreateRecordByUser
D/bt-btif ( 1226): jv_dm_cback: event:11, slot id:1
D/bt-btif ( 1226): name:OBEX Phonebook Access Server, scn:19
D/bt-btif ( 1226): add_pbap_sdd:scn 19, service name OBEX Phonebook Access Server
D/bt-sdp  ( 1226): SDP_CreateRecord ok, num_records:11
I/bt-btif ( 1226): Adding UUID=0x112F into EIR
D/bt-btif ( 1226): BTA is generating EIR
I/bt-btif ( 1226): bta_dm_eir_update_uuid UUID bit mask=0x00000094 04071440
D/bt-btif ( 1226): PBS:  SDP Registered (handle 0x0001000a)
I/bt-btif ( 1226): BTA_JvRfcommStartServer
D/bt-btif ( 1226): bta_jv_rfcomm_start_server: sec id in use:0, rfc_cb in use:0
D/bt-btif ( 1226): bta_jv_alloc_rfc_cb port_handle:6 handle:0x81
D/LGBluetoothServiceAdapter( 1226): [BTUI] createSocketChannel FD=90 mFd=0
V/BluetoothPbapService( 1226): Succeed to create listening socket 
V/BluetoothPbapService( 1226): Accepting socket connection...
D/BluetoothMapService( 1226): Map Service initSocket
D/BluetoothManagerService(  965): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 1226): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 1226): SOCK FLAG = 1 ***********************
D/bt-btif ( 1226): btsock_rfc_listen, service_name:MAP SMS/MMS
D/bt-btif ( 1226): BTA_JvCreateRecordByUser:MAP SMS/MMS
I/bt-btif ( 1226): BTA_JvCreateRecordByUser
D/bt-btif ( 1226): jv_dm_cback: event:11, slot id:2
D/bt-btif ( 1226): name:MAP SMS/MMS, scn:6
D/bt-btif ( 1226): add_maps_sdd:scn 6, service name MAP SMS/MMS
D/bt-sdp  ( 1226): SDP_CreateRecord ok, num_records:12
I/bt-btif ( 1226): Adding UUID=0x1132 into EIR
D/bt-btif ( 1226): BTA is generating EIR
I/bt-btif ( 1226): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04071440
D/bt-btif ( 1226): MAPSS:  SDP Registered (handle 0x0001000b)
I/bt-btif ( 1226): BTA_JvRfcommStartServer
D/bt-btif ( 1226): bta_jv_rfcomm_start_server: sec id in use:1, rfc_cb in use:1
D/bt-btif ( 1226): bta_jv_alloc_rfc_cb port_handle:7 handle:0x82
D/LGBluetoothServiceAdapter( 1226): [BTUI] createSocketChannel FD=92 mFd=90
V/BluetoothMapService( 1226): Succeed to create listening socket 
D/BluetoothMapService( 1226): Accepting socket connection...
V/BluetoothPbapReceiver( 1226): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1226): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1226): ***********state = 12
D/LocalBluetoothProfileManager( 2558): Adding local A2DP profile
,D/BluetoothManagerService(  965): Message: 30
,D/LocalBluetoothProfileManager( 2558): Adding local HEADSET profile
,D/BluetoothManagerService(  965): Message: 30
W/ContextImpl( 2558): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1207 
,W/ContextImpl( 2558): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1204 
,D/BluetoothManagerService(  965): Message: 30
,D/BluetoothManagerService(  965): Message: 30
,D/LocalBluetoothProfileManager( 2558): Adding local MAP profile
,D/BluetoothMap( 2558): Create BluetoothMap proxy object
,D/BluetoothManagerService(  965): Message: 30
W/ContextImpl( 2558): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1210 
W/ContextImpl( 2558): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1213 
W/ContextImpl( 2558): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1219 
,D/BluetoothManagerService(  965): Message: 30
,D/LocalBluetoothProfileManager( 2558): LocalBluetoothProfileManager construction complete
,V/BluetoothPbapService( 1226): Pbap Service onBind
,D/LGBluetoothUserBindClient( 2558): [BTUI] initUserBindClient
,D/DockEventReceiver( 2558): finishStartingService: stopping service
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/ContextImpl( 2558): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:72 
,W/ContextImpl( 2558): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/BluetoothA2dp( 2558): Proxy object connected
D/A2dpProfile( 2558): Bluetooth service connected
D/BluetoothHeadset( 2558): Proxy object connected
D/HeadsetProfile( 2558): Bluetooth service connected
D/BluetoothInputDevice( 2558): Proxy object connected
D/HidProfile( 2558): Bluetooth service connected
D/BluetoothPan( 2558): BluetoothPAN Proxy object connected
D/PanProfile( 2558): Bluetooth service connected
D/BluetoothMap( 2558): Proxy object connected
D/MapProfile( 2558): Bluetooth service connected
D/BluetoothMap( 2558): getConnectedDevices()
V/BluetoothMapService( 1226): getConnectedDevices()
D/BluetoothPbap( 2558): Proxy object connected
D/PbapServerProfile( 2558): Bluetooth service connected
D/LGBluetoothUserBindClient( 2558): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 2558): onReceive
D/LGBluetoothFeatureConfig( 2558): isPrivacyLogsEnabled : true
E/LGBluetoothUtils( 2558): [BTUI] FileNotFoundException: readPropertyjava.io.FileNotFoundException: /data/misc/bluedroid/bluetooth_property.conf: open failed: ENOENT (No such file or directory)
D/LGBluetoothResetSettingReceiver( 2558): return without doing reset settings.
V/BluetoothOppReceiver( 1226): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
I/LGBluetoothOppAdapter( 1226): [BTUI] startOppService()
,V/BluetoothOppManager( 1226): restoreApplicationData! falsefalsenullnull
,D/LGBluetoothFeatureConfig( 1226): isPrivacyLogsEnabled : true
V/BtOppService( 1226): onCreate
,D/LGBluetoothOppAdapter( 1226): [BTUI] getInstance : create [LGBluetoothOppAdapter]
,V/BluetoothOppNotification( 1226): send message
,V/BtOppService( 1226): Starting RfcommListener
,D/BluetoothOppPreference( 1226): Dumping Names:  
D/BluetoothOppPreference( 1226): {}
D/BluetoothOppPreference( 1226): Dumping Channels:  
,D/BluetoothOppPreference( 1226): {}
,V/BtOppService( 1226): pendingUpdate is true keepUpdateThread is false sListenStarted is true
,V/BtOppService( 1226): onStartCommand
,V/BluetoothOppNotification( 1226): new notify threadi!
V/BluetoothOppNotification( 1226): send delay message
,V/BtOppService( 1226): start RfcommListener
V/BtOppService( 1226): RfcommListener started
,V/BtOppRfcommListener( 1226): Starting RFCOMM listener....
V/BluetoothOppProvider( 1226): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BtOppService( 1226): ContentObserver received notification
V/BluetoothOppProvider( 1226): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,V/BtOppService( 1226): Deleted complete outbound shares, number =  0
,D/BluetoothManagerService(  965): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,V/BluetoothOppProvider( 1226): created cursor android.database.sqlite.SQLiteCursor@4292da90 on behalf of 
,D/AuthorizationBluetoothService( 1558): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
V/BtOppService( 1226): ContentObserver received notification
,V/BluetoothOppProvider( 1226): created cursor android.database.sqlite.SQLiteCursor@4292e2d0 on behalf of 
,E/AuthorizationBluetoothService( 1558): Proximity feature is not enabled.
V/BtOppService( 1226): Deleted complete inbound failed shares, number = 0
,V/BluetoothOppProvider( 1226): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,W/BluetoothAdapter( 1226): getBluetoothService() called with no BluetoothManagerCallback
,V/BluetoothOppNotification( 1226): mUpdateCompleteNotification = true
V/BtOppService( 1226): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 1226): created cursor android.database.sqlite.SQLiteCursor@42930d30 on behalf of 
,V/BluetoothOppProvider( 1226): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
E/BluetoothServiceJni( 1226): SOCK FLAG = 0 ***********************
D/bt-btif ( 1226): btsock_rfc_listen, service_name:OBEX Object Push
D/bt-btif ( 1226): BTA_JvCreateRecordByUser:OBEX Object Push
I/bt-btif ( 1226): BTA_JvCreateRecordByUser
D/bt-btif ( 1226): jv_dm_cback: event:11, slot id:3
D/bt-btif ( 1226): name:OBEX Object Push, scn:12
D/bt-btif ( 1226): scn 12, service name OBEX Object Push
D/LGBluetoothServiceAdapter( 1226): [BTUI] createSocketChannel FD=97 mFd=92
D/bt-sdp  ( 1226): SDP_CreateRecord ok, num_records:13
I/bt-btif ( 1226): Adding UUID=0x1105 into EIR
D/bt-btif ( 1226): BTA is generating EIR
I/bt-btif ( 1226): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04071460
I/bt-btif ( 1226): BTA_JvRfcommStartServer
D/bt-btif ( 1226): bta_jv_rfcomm_start_server: sec id in use:2, rfc_cb in use:2
D/bt-btif ( 1226): bta_jv_alloc_rfc_cb port_handle:8 handle:0x83
,V/BluetoothOppProvider( 1226): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BtOppRfcommListener( 1226): Started RFCOMM listener....
I/BtOppRfcommListener( 1226): Accept thread started.
V/BtOppRfcommListener( 1226): Accepting connection...
,V/BluetoothOppProvider( 1226): created cursor android.database.sqlite.SQLiteCursor@42932728 on behalf of 
V/BluetoothOppNotification( 1226): update too frequent, put in queue
V/BluetoothOppProvider( 1226): created cursor android.database.sqlite.SQLiteCursor@429344e0 on behalf of 
,V/BtOppService( 1226): pendingUpdate is false keepUpdateThread is false sListenStarted is true
V/BluetoothOppNotification( 1226): outbound: succ-0  fail-0
,V/BluetoothOppNotification( 1226): outbound notification was removed.
,V/BluetoothOppProvider( 1226): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1226): created cursor android.database.sqlite.SQLiteCursor@429368f8 on behalf of 
,V/BluetoothOppNotification( 1226): inbound: succ-0  fail-0
V/BluetoothOppNotification( 1226): inbound notification was removed.
,V/BluetoothOppProvider( 1226): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 1226): created cursor android.database.sqlite.SQLiteCursor@42937fe0 on behalf of 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/wpa_supplicant( 4265): EAPOL: disable timer tick
D/wpa_supplicant( 4265): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4265): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 4265): EAPOL: disable timer tick
D/wpa_supplicant( 4265): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4265): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/BluetoothOppNotification( 1226): new notify threadi!
,V/BluetoothOppNotification( 1226): send delay message
,V/BluetoothOppProvider( 1226): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 1226): created cursor android.database.sqlite.SQLiteCursor@42939a70 on behalf of 
,V/BluetoothOppNotification( 1226): mUpdateCompleteNotification = true
,V/BluetoothOppProvider( 1226): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 1226): created cursor android.database.sqlite.SQLiteCursor@4293b6a8 on behalf of 
,V/BluetoothOppNotification( 1226): outbound: succ-0  fail-0
,V/BluetoothOppNotification( 1226): outbound notification was removed.
,V/BluetoothOppProvider( 1226): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1226): created cursor android.database.sqlite.SQLiteCursor@4293d238 on behalf of 
,V/BluetoothOppNotification( 1226): inbound: succ-0  fail-0
,V/BluetoothOppNotification( 1226): inbound notification was removed.
,V/BluetoothOppProvider( 1226): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 1226): created cursor android.database.sqlite.SQLiteCursor@4293e7e0 on behalf of 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/AudioFlinger(  271): releaseWakeLock_l() AudioOut_3
,V/AudioFlinger(  271): releaseWakeLock_l() AudioOut_2
,V/AudioFlinger(  271): thread 0xb25ad008 type 0 TID 1000 going to sleep
,V/AudioFlinger(  271): thread 0xb2718008 type 0 TID 906 going to sleep
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/wpa_supplicant( 4265): nl80211: Event message available
D/wpa_supplicant( 4265): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 4265): wlan0: nl80211: New scan results available
D/wpa_supplicant( 4265): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 4265): nl80211: Received scan results (8 BSSes)
D/wpa_supplicant( 4265): nl80211: Survey data missing
D/wpa_supplicant( 4265): wlan0: BSS: Start scan result update 1
D/wpa_supplicant( 4265): wlan0: BSS: Add new id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
,D/wpa_supplicant( 4265): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4265): wlan0: BSS: Add new id 1 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 4265): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4265): wlan0: BSS: Add new id 2 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700'
D/wpa_supplicant( 4265): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4265): wlan0: BSS: Add new id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos'
D/wpa_supplicant( 4265): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4265): wlan0: BSS: Add new id 4 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 4265): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4265): wlan0: BSS: Add new id 5 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025'
D/wpa_supplicant( 4265): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4265): wlan0: BSS: Add new id 6 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free'
D/wpa_supplicant( 4265): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4265): wlan0: BSS: Add new id 7 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698'
D/wpa_supplicant( 4265): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4265): BSS: last_scan_res_used=8/32 last_scan_full=0
D/wpa_supplicant( 4265): wlan0: New scan results available
D/wpa_supplicant( 4265): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4265): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4265): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 4265): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 4265): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 4265): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 4265): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 4265): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4265): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4265): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4265): WPS: AP[3] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4265): WPS: AP[4] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4265): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 4265): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-48 wps
D/wpa_supplicant( 4265): wlan0:    skip - SSID mismatch
,D/wpa_supplicant( 4265): wlan0: 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-58,
D/wpa_supplicant( 4265): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 4265): wlan0: 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-58 wps
D/wpa_supplicant( 4265): wlan0:    selected based on RSN IE
D/wpa_supplicant( 4265): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 4265): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 4265): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 4265): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 4265): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 4265): wpa_supplicant_check_mdm_ac_policy policy: 0
,D/wpa_supplicant( 4265): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 4265): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb81b95a8  current_ssid=0x0,
,D/wpa_supplicant( 4265): wlan0: Selected network is configured to use SIM (sim=1 aka=1) - initialize PCSC
E/wpa_supplicant( 4265): USIM:  scard_init function
D/wpa_supplicant( 4265): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 4265): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 4265): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 4265): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 4265): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 4265): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 4265): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4265): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 4265): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4265): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 4265): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 4265): wlan0: Cancelling scan request
D/wpa_supplicant( 4265): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 4265): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 4265): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 4265): RSN: PMKSA cache search - network_ctx=0xb81b95a8 try_opportunistic=0
D/wpa_supplicant( 4265): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4265): RSN: No PMKSA cache entry found
D/wpa_supplicant( 4265): wlan0: RSN: using IEEE 802.11i/D9.0
D/wpa_supplicant( 4265): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 4265): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 4265): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4265): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 4265): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 4265): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 4265): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4265): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 4265): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 4265): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 4265): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 4265): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4265): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4265): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4265): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 4265): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 4265): nl80211: Unsubscribe mgmt frames handle 0xb81b8590 (mode change)
D/wpa_supplicant( 4265): nl80211: Subscribe to mgmt frames with non-AP handle 0xb81b8590
D/wpa_supplicant( 4265): nl80211: Register frame type=0xd0 nl_handle=0xb81b8590
D/wpa_supplicant( 4265): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 4265): nl80211: Register frame type=0xd0 nl_handle=0xb81b8590
D/wpa_supplicant( 4265): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 4265): nl80211: Register frame type=0xd0 nl_handle=0xb81b8590
D/wpa_supplicant( 4265): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 4265): nl,80211: Register frame type=0xd0 nl_handle=0xb81b8590
D/wpa_supplicant( 4265): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 4265): nl80211: Register frame type=0xd0 nl_handle=0xb81b8590
D/wpa_supplicant( 4265): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 4265): nl80211: Register frame type=0xd0 nl_handle=0xb81b8590
D/wpa_supplicant( 4265): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 4265): nl80211: Register frame type=0xd0 nl_handle=0xb81b8590
D/wpa_supplicant( 4265): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 4265): nl80211: Register frame type=0xd0 nl_handle=0xb81b8590
D/wpa_supplicant( 4265): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 4265): nl80211: Register frame type=0xd0 nl_handle=0xb81b8590
D/wpa_supplicant( 4265): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 4265): nl80211: Register frame type=0xd0 nl_handle=0xb81b8590
D/wpa_supplicant( 4265): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 4265): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 4265):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4265):   * freq=2412
D/wpa_supplicant( 4265):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 4265):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4265):   * Auth Type 0
D/wpa_supplicant( 4265):   * WPA Versions 0x2
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 1 c2:ff:d4:d3:aa:48]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 2 c0:ff:d4:d3:aa:48]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 3 38:f8:89:11:e9:11]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 4 a0:c5:62:7a:49:97]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 9e:93:4e:3e:ba:c5]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 06:7c:34:12:7f:81]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 64:7c:34:12:7f:81]
D/wpa_supplicant( 4265): nl80211: Connect request send successfully
D/wpa_supplicant( 4265): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 4265): EAPOL: External notification - EAP success=0,
D/wpa_supplicant( 4265): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4265): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4265): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 4265): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4265): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4265): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 4265): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4265): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4265): RSN: Ignored PMKID candidate without preauth flag
D/wpa_supplicant( 4265): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4265): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4265): nl80211: if_removed already cleared - ignore event
,D/WifiStateMachine(  965): handleMessage: E msg.what=147461
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  965): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 4265): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/WifiMonitor(  965): Event [IFNAME=wlan0 WPS-AP-AVAILABLE-AUTH ]
W/WifiMonitor(  965): couldn't identify event type - WPS-AP-AVAILABLE-AUTH ,
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): handleMessage: X
,D/wpa_supplicant( 4265): nl80211: Event message available
D/wpa_supplicant( 4265): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 4265): nl80211: Connect event
D/wpa_supplicant( 4265): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 4265): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4265): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 4265): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 4265): wlan0: Association info event
D/wpa_supplicant( 4265): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 4265): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 4265): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4265): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 4265): wlan0: freq=2412 MHz
D/wpa_supplicant( 4265): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4265): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 4265): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4265): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4265): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4265): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4265): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 4265): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 4265): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 4265): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4265): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4265): scard is not null..
D/wpa_supplicant( 4265): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 4265): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 4265): TDLS: Remove peers on association
D/wpa_supplicant( 4265): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4265): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4265): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4265): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4265): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4265): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4265): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4265): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4265): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4265): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 4265): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 4265): EAPOL: enable timer tick
D/wpa_supplicant( 4265): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 4265): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 4265): wlan0: Cancelling scan request
,D/wpa_supplicant( 4265): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 4265): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4265): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4265): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4265): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4265): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4265): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4265): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4265): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 4265): nl80211: if_removed already cleared - ignore event,
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
,D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): handleMessage: X
,W/WifiMonitor(  965): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
,D/wpa_supplicant( 4265): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4265): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 76 a3 b9 67 88 a7 43 c8 cc 41 64 83 ee 13 09 ...
D/wpa_supplicant( 4265): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 4265): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 4265): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 4265): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 4265): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 4265):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 4265):   key_nonce - hexdump(len=32): 76 a3 b9 67 88 a7 43 c8 cc 41 64 83 ee 13 09 7f 8a a9 c3 87 28 d8 ab 1b 60 b5 3d e0 2a 00 c8 45
D/wpa_supplicant( 4265):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4265):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4265):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4265):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4265): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 76 a3 b9 67 88 a7 43 c8 cc 41 64 83 ee 13 09 ...
D/wpa_supplicant( 4265): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4265): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4265): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 4265): RSN: msg 1/4 key data - hexdump(len=0):
,D/wpa_supplicant( 4265): Get randomness: len=32 entropy=9
D/wpa_supplicant( 4265): WPA: Renewed SNonce - hexdump(len=32): 33 2f fc a3 88 d3 c5 89 4b 8c fd b9 59 a8 77 7d a0 b1 cf b1 c3 b8 26 43 5e 82 27 b8 8f 83 ea 97
,D/wpa_supplicant( 4265): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4265): WPA: Nonce1 - hexdump(len=32): 33 2f fc a3 88 d3 c5 89 4b 8c fd b9 59 a8 77 7d a0 b1 cf b1 c3 b8 26 43 5e 82 27 b8 8f 83 ea 97
D/wpa_supplicant( 4265): WPA: Nonce2 - hexdump(len=32): 76 a3 b9 67 88 a7 43 c8 cc 41 64 83 ee 13 09 7f 8a a9 c3 87 28 d8 ab 1b 60 b5 3d e0 2a 00 c8 45
D/wpa_supplicant( 4265): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 4265): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 4265): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4265): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 4265): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 4265): WPA: KCK - hexdump(len=16): [REMOVED]
,D/wpa_supplicant( 4265): WPA: Derived Key MIC - hexdump(len=16): d7 c9 75 64 a7 8a 92 cc 4f 90 7e cb 03 9e 37 d2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/wpa_supplicant( 4265): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 33 2f fc a3 88 d3 c5 89 4b 8c fd b9 59 a8 77 ...
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
,D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/wpa_supplicant( 4265): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4265): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 76 a3 b9 67 88 a7 43 c8 cc 41 64 83 ee 13 09 ...
D/wpa_supplicant( 4265): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 4265): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 4265): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 4265): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 4265):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 4265):   key_nonce - hexdump(len=32): 76 a3 b9 67 88 a7 43 c8 cc 41 64 83 ee 13 09 7f 8a a9 c3 87 28 d8 ab 1b 60 b5 3d e0 2a 00 c8 45
D/wpa_supplicant( 4265):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4265):   key_rsc - hexdump(len=8): 68 42 00 00 00 00 00 00
D/wpa_supplicant( 4265):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4265):   key_mic - hexdump(len=16): 3b 6e 4c de 9e 82 3c e2 38 a0 ae 40 e2 aa 81 e6
D/wpa_supplicant( 4265): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 76 a3 b9 67 88 a7 43 c8 cc 41 64 83 ee 13 09 ...
D/wpa_supplicant( 4265): RSN: encrypted key data - hexdump(len=56): da 95 8a b9 88 ec a8 74 65 a5 48 f0 c9 31 42 40 1d f0 4f 22 1b 28 2a 6c f9 6a 6f db 3c 7f cb 69 ...
D/wpa_supplicant( 4265): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 4265): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4265): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 4265): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 e6 70 ...
D/wpa_supplicant( 4265): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4265): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 4265): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 4265): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 4265): WPA: Derived Key MIC - hexdump(len=16): 4c f2 63 72 a5 a8 a4 74 72 d0 28 ca 6a b6 2b 86
D/wpa_supplicant( 4265): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 4265): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 4265): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb81b8c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 4265):    addr=c0:ff:d4:d3:aa:48
D/WifiStateMachine(  965): handleMessage: X
D/wpa_supplicant( 4265): EAPOL: External notification - portValid=1
D/wpa_supplicant( 4265): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 4265): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4265): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 4265): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 4265): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 4265): WPA: RSC - hexdump(len=6): 68 42 00 00 00 00
D/wpa_supplicant( 4265): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f6603a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 4265):    broadcast key
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
I/wpa_supplicant( 4265): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 4265): CTRL_IFACE monito,r send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4265): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 4265): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 4265): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 4265): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4265): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 4265): netlink: Operstate: linkmode=-1, operstate=6
D/wpa_supplicant( 4265): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 4265): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 4265): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4265): EAPOL: External notification - portValid=1
D/wpa_supplicant( 4265): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 4265): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 4265): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 4265): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4265): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 4265): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 4265): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4265): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 4265): EAPOL authentication completed successfully
D/wpa_supplicant( 4265): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4265): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4265): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  965): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
W/WifiMonitor(  965): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147459
D/WifiStateMachine(  965): processMsg: DisconnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): Network connection established
D/WifiNative-wlan0(  965): doString: STATUS
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 4265): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 4265): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4265): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiNative-wlan0(  965):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  965): ssid=NG700
D/WifiNative-wlan0(  965): id=0
D/WifiNative-wlan0(  965): mode=station
D/WifiNative-wlan0(  965): pairwise_cipher=CCMP
D/WifiNative-wlan0(  965): group_cipher=CCM,P
D/WifiNative-wlan0(  965): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  965): wpa_state=COMPLETED
D/WifiNative-wlan0(  965): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  965): address=34:fc:ef:de:0a:e2
I/WifiServiceExtension(  965): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServiceExtension(  965): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
D/WifiStateMachine(  965): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
E/Parcel  (  411): Reading a NULL string not supported here.
E/Parcel  (  411): Reading a NULL string not supported here.
E/Parcel  (  411): Reading a NULL string not supported here.
E/Parcel  (  411): Reading a NULL string not supported here.
E/Parcel  (  411): Reading a NULL string not supported here.
E/Parcel  (  411): Reading a NULL string not supported here.
D/WifiStateMachine(  965): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
D/WifiStateMachine(  965): invokeExitMethods: DisconnectedState
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/WifiStateMachine(  965): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  965): invokeEnterMethods: L2ConnectedState
D/WifiStateMachine(  965): invokeEnterMethods: ObtainingIpState
D/WifiService(  965): New client listening to asynchronous messages
I/ActivityManager(  965): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4442 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
D/WifiStateMachine(  965): handleMessage: X
D/DhcpStateMachine(  965): StoppedState
D/DhcpStateMachine(  965): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  965): WaitBeforeStartState
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-49ms what=147462 obj=android.net.wifi.StateChangeResult@439a9ba8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147462
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-44ms what=147462 obj=android.net.wifi.StateChangeResult@439ab518 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=147459
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-44ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131155
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-20ms what=131155 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 4265): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 4265): nl80211: survey data missing!
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=196612
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-3ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 4265): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
E/Parcel  (  411): Reading a NULL string not supported here.
E/Parcel  (  411): Reading a NULL string not supported here.
E/Parcel  (  411): Reading a NULL string not supported here.
E/Parcel  (  411): Reading a NULL string not supported here.
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/HyLog   ( 4442): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4442): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4442): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/QRemote ( 4442): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
D/QRemote ( 4442): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4442): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 4442): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 4442): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 4442): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 4442): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 4442): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4442): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/ActivityManager(  965): Killing 4029:com.android.defcontainer/u0a4 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327ac48 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a035a0 u0 com.test.thalitest/.MainActivity t3}
,D/wpa_supplicant( 4265): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  965):    returned true
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 1 false
D/WifiNative-wlan0(  965): doBoolean: SET ps 0
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 4265): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 4265): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 4265): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  965):    returned true
D/WifiNative-wlan0(  965): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 4265): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 4265): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  965):    returned null
E/WifiStateMachine(  965): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  965): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 4265): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 4265): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  965):    returned null
E/WifiStateMachine(  965): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  965): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  965): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper(  965): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/WifiStateMachine(  965): handleMessage: X
D/DhcpStateMachine(  965): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  965): DHCP Start wake lock is acquired.
D/WifiP2pService(  965): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43a0feb0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  965): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43a0feb0 target=com.android.internal.util.StateMachine$SmHandler }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/DhcpStateMachine(  965): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  965): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/wpa_supplicant( 4265): EAPOL: startWhen --> 0
,D/wpa_supplicant( 4265): EAPOL: disable timer tick
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  965): addressUpdated: 192.168.1.140/24 on wlan0 flags 128 scope 0
,E/BatteryObserver( 1157): usb Uevent not necessary.
D/WifiStateMachine(  965): handleMessage: E msg.what=131212
D/WifiStateMachine(  965): processMsg: ObtainingIpState
D/WifiStateMachine(  965): ObtainingIpState{ when=-1ms what=131212 obj=192.168.1.140/24 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
D/WifiStateMachine(  965): processMsg: SupplicantStartedState
D/WifiStateMachine(  965): processMsg: DefaultState
D/WifiStateMachine(  965): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  965): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/DhcpStateMachine(  965): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  965): CheckDhcpDirectory [Lease File Count] : 3
,V/LgDhcpStateMachineHelper(  965): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LgDhcpStateMachineHelper(  965): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.140
,V/LgDhcpStateMachineHelper(  965): Add DhcpResults: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine(  965): Current State is mWaitBeforeStartState.
,V/LgDhcpStateMachineHelper(  965): bShouldSendDhcpAction Result: true
D/WifiStateMachine(  965): handleMessage: E msg.what=196613
,D/WifiStateMachine(  965): processMsg: ObtainingIpState
,D/WifiStateMachine(  965): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  965): doBoolean: SET ps 1
,D/DhcpStateMachine(  965): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  965): RunningState
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 4265): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 4265): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 4265): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  965):    returned true
,D/WifiNative-wlan0(  965): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 4265): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 4265): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  965):    returned true
,D/WifiStateMachine(  965): DHCP successful
,D/WifiStateMachine(  965): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  965): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  965): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
,D/WifiStateMachine(  965): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  965): VerifyingLinkState enter
,D/WifiStateMachine(  965): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
D/WifiP2pService(  965): InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  965): P2pEnabledState{ when=-5ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  965): send additional Connectivity Action
,W/WifiStateTracker(  965): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  965): 
W/WifiStateTracker(  965):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  965):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
E/Parcel  (  411): Reading a NULL string not supported here.
E/Parcel  (  411): Reading a NULL string not supported here.
E/Parcel  (  411): Reading a NULL string not supported here.
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
,D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=135190
D/WifiStateMachine(  965): processMsg: VerifyingLinkState
,D/WifiStateMachine(  965): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  965): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
,D/WifiStateMachine(  965): invokeExitMethods: VerifyingLinkState
,D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  965): invokeEnterMethods: CaptivePortalCheckState
,D/WifiStateMachine(  965): CaptivePortalCheckState enter
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/WifiStateMachine(  965): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/QcConnectivityService(  965): handleConnectivityChange: preConnState=0 connState=2
D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=true
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/SocketClient(  264): write error (Broken pipe)
D/WifiStateMachine(  965): handleMessage: X
D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
,D/LocSvc_java(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
,D/GpsLocationProvider(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
,D/QRemote ( 4442): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4442): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  965): handleMessage: E msg.what=131092
D/WifiStateMachine(  965): processMsg: CaptivePortalCheckState
E/Parcel  (  411): Reading a NULL string not supported here.
D/WifiStateMachine(  965): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,E/Parcel  (  411): Reading a NULL string not supported here.
,E/Parcel  (  411): Reading a NULL string not supported here.
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiStateMachine(  965): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,D/QRemote ( 4442): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/WifiStateMachine(  965): transitionTo: destState=ConnectedState
D/WifiStateMachine(  965): handleMessage: new destination call exit/enter
D/WifiStateMachine(  965): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  965): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  965): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  965): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  965): invokeEnterMethods: ConnectedState
,D/WifiStateMachine(  965): handleMessage: X
D/QcConnectivityService(  965): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  965): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/QcConnectivityService(  965): handleInetConditionChange: no active default network - ignore
I/QRemote ( 4442): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  965): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
D/KeyguardUpdateMonitor( 1143): received broadcast android.net.wifi.STATE_CHANGE
E/Parcel  (  411): Reading a NULL string not supported here.
E/Parcel  (  411): Reading a NULL string not supported here.
E/Parcel  (  411): Reading a NULL string not supported here.
,V/WfdStateTracker( 1157): handleWifiStateChangedEvent: 1
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,I/PCSuite ( 4305): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
E/ActivityThread(  965): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  965): handleConnectivityChange:1 is conntected
,D/QcConnectivityService(  965): handleConnectivityChange: preConnState=2 connState=1
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1143): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/jxcore-log( 4201): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 4201): 
D/PCSuite ( 4305): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/QRemote ( 4442): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/QRemote ( 4442): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
I/QRemote ( 4442): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 4442): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
E/BatteryObserver( 1157): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/QCNEA   (  411): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  411): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  411): |CAC| updateNetCfgInfo
V/QCNEA   (  411): |CAC| *********************************************
V/QCNEA   (  411): |CAC|                   Netconfig               
V/QCNEA   (  411): |CAC| *********************************************
V/QCNEA   (  411): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  411): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  411): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  411): |CAC| 	NetConfig: ip4        =192.168.1.140
V/QCNEA   (  411): |CAC| 	NetConfig: ip6        =::
,V/QCNEA   (  411): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  411): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  411): |CAC| *********************************************
D/QCNEA   (  411): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  411): |CAC| net type = 1
V/QCNEA   (  411): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  411): |CAC| Received ssid= NG700
V/QCNEA   (  411): |CAC| 	ssid           =NG700
V/QCNEA   (  411): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  411): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  411): |CAC| *********************************************
D/QCNEA   (  411): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  411): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  411): |CAC| dispatchNetCfg: updating:0xb74f28dc
D/LocSvc_java(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
,D/GpsLocationProvider(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=true
D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/GpsLocationProvider(  965): NTP server returned: 1450201710565 (Tue Dec 15 18:48:30 CET 2015) reference: 117151 certainty: 23 system time offset: 96
E/LocSvc_afw(  965): V/Entering int loc_inject_time(GpsUtcTime, int64_t, int) line 446 
,E/LocSvc_eng(  965): I/===> int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int) line 1910 
E/LocSvc_eng(  965): V/time: 1450201710565
E/LocSvc_eng(  965):   timeReference: 117151
E/LocSvc_eng(  965):   uncertainty: 23
E/LocSvc_utils_q(  965): D/msg_q_snd: Sending message with handle = 0x6E5E1E60
E/LocSvc_utils_ll(  965): D/linked_list_add: Adding to list data_obj = 0x6E5E1E60
E/LocSvc_utils_q(  965): D/msg_q_snd: Finished Sending message with handle = 0x6E5E1E60
E/LocSvc_utils_ll(  965): D/linked_list_remove: Removing from list
E/LocSvc_utils_q(  965): D/msg_q_rcv: Received message 0x6E5E1E60 rv = 0
E/LocSvc_eng(  965): V/time: 1450201710565
E/LocSvc_eng(  965):   timeReference: 117151
E/LocSvc_eng(  965):   uncertainty: 23
E/LocSvc_ApiV02(  965): V/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):436]: uncertainty = 23
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 56, req_id 56 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 56
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=56, len = 16
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 56, len = 16
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_UTC_TIME_REQ_V02
E/LocSvc_eng(  965): V/Exiting int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int) line 1917 0
,E/LocSvc_afw(  965): V/Exiting int loc_inject_time(GpsUtcTime, int64_t, int) line 452 0
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 45, status = 0
,E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=56 buf_len=7 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 56 size = 4
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 56 is a resp size = 4
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_UTC_TIME_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 56, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 56 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 56 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 56 size = 4
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 4 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_MsgTask(  965): D/MsgTask::loop() 26 listening ...
,E/LocSvc_utils_q(  965): D/msg_q_rcv: Waiting on message
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GpsLocationProvider(  965): calling native_inject_xtra_data
,E/LocSvc_afw(  965): V/Entering int loc_xtra_inject_data(char*, int) line 858 
E/LocSvc_eng(  965): V/length: 58717
E/LocSvc_eng(  965):   data: 0x6967a008
E/LocSvc_utils_q(  965): D/msg_q_snd: Sending message with handle = 0x6ED017F0
E/LocSvc_utils_ll(  965): D/linked_list_add: Adding to list data_obj = 0x6ED017F0
E/LocSvc_utils_q(  965): D/msg_q_snd: Finished Sending message with handle = 0x6ED017F0
E/LocSvc_utils_ll(  965): D/linked_list_remove: Removing from list
E/LocSvc_utils_q(  965): D/msg_q_rcv: Received message 0x6ED017F0 rv = 0
,E/LocSvc_eng(  965): V/length: 58717
E/LocSvc_eng(  965):   data: 0x6967a008
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1018]: xtra size = 58717
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 1/58, len = 1024, total injected = 0
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_afw(  965): V/Exiting int loc_xtra_inject_data(char*, int) line 861 0
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 46, status = 0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
,E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 1024
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 2/58, len = 1024, total injected = 1024
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
,E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 47, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 2048
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 3/58, len = 1024, total injected = 2048
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 48, status = 0
,E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 3072
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 4/58, len = 1024, total injected = 3072
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02,
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
,E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 ,
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 49, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 4096
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 5/58, len = 1024, total injected = 4096
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02,
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
,E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 50, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 5120
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 6/58, len = 1024, total injected = 5120,
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 51, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 6144
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 7/58, len = 1024, total injected = 6144
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 52, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 7168
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 8/58, len = 1024, total injected = 7168
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 53, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 8192
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 9/58, len = 1024, total injected = 8192
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 54, status = 0
,E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 9216
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 10/58, len = 1024, total injected = 9216
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 55, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 10240
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 11/58, len = 1024, total injected = 10240
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 56, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 11264
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 12/58, len = 1024, total injected = 11264
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 57, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 12288
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 13/58, len = 1024, total injected = 12288
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 58, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 13312
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 14/58, len = 1024, total injected = 13312
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 59, status = 0
,E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 14336
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 15/58, len = 1024, total injected = 14336
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 60, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 15360
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 16/58, len = 1024, total injected = 15360
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 61, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 16384
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 17/58, len = 1024, total injected = 16384
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 62, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 17408
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 18/58, len = 1024, total injected = 17408
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 63, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 18432
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 19/58, len = 1024, total injected = 18432
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 64, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 19456
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 20/58, len = 1024, total injected = 19456
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 65, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 20480
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 21/58, len = 1024, total injected = 20480
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 66, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 21504
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 22/58, len = 1024, total injected = 21504
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 67, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 22528
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 23/58, len = 1024, total injected = 22528
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
,E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 68, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 23552
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 24/58, len = 1024, total injected = 23552
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 69, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 24576
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 25/58, len = 1024, total injected = 24576
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 70, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 25600
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 26/58, len = 1024, total injected = 25600
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 71, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 26624
,E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 27/58, len = 1024, total injected = 26624
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 72, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 27648
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 28/58, len = 1024, total injected = 27648
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 73, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 28672
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 29/58, len = 1024, total injected = 28672
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 74, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
,E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 29696
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 30/58, len = 1024, total injected = 29696
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 75, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 30720
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 31/58, len = 1024, total injected = 30720
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 76, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 31744
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 32/58, len = 1024, total injected = 31744
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 77, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 32768
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 33/58, len = 1024, total injected = 32768
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
,E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 78, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 33792
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 34/58, len = 1024, total injected = 33792
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 79, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 34816
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 35/58, len = 1024, total injected = 34816
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
,E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 80, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 35840
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 36/58, len = 1024, total injected = 35840
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
,E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 81, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 36864
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 37/58, len = 1024, total injected = 36864
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 82, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 37888
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 38/58, len = 1024, total injected = 37888
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 83, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 38912
,E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 39/58, len = 1024, total injected = 38912
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 84, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 39936
,E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 40/58, len = 1024, total injected = 39936
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 85, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 40960
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 41/58, len = 1024, total injected = 40960
,E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 86, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 41984
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 42/58, len = 1024, total injected = 41984
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
,E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 87, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 43008
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 43/58, len = 1024, total injected = 43008
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
,E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 88, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 44032
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 44/58, len = 1024, total injected = 44032
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 89, status = 0
,E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 45056
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 45/58, len = 1024, total injected = 45056
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02,
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 90, status = 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 46080
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 46/58, len = 1024, total injected = 46080
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02,
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 91, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 47104
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 47/58, len = 1024, total injected = 47104
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 92, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 48128
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 48/58, len = 1024, total injected = 48128
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 93, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 49152
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 49/58, len = 1024, total injected = 49152
,E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 94, status = 0
,E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 50176
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 50/58, len = 1024, total injected = 50176
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 95, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 51200
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 51/58, len = 1024, total injected = 51200
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 96, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 52224
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 52/58, len = 1024, total injected = 52224
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 97, status = 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 53248
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 53/58, len = 1024, total injected = 53248
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
,E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 98, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 54272
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 54/58, len = 1024, total injected = 54272
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 99, status = 0
,E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 55296
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 55/58, len = 1024, total injected = 55296
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 100, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
,E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 56320
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 56/58, len = 1024, total injected = 56320
,E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 101, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 57344
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 57/58, len = 1024, total injected = 57344
,E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
,E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 102, status = 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 58368
E/LocSvc_ApiV02(  965): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 58/58, len = 349, total injected = 58368
E/LocSvc_api_v02(  965): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  965): V/loc_sync_select_ind:356]: client handle 0x69e535e0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  965): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  965): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  965): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  965): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  965): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  965): V/convertQmiResponseToLocStatus:681]: result = 0, error = 103, status = 0
,E/LocSvc_api_v02(  965): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  965): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x69e535e0,
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  965): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  965): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x69e535e0, resp id = 53, client cookie ptr = 0x69e538c0
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:165]: received indication, handle = 0x69e535e0 ind_id = 53 
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  965): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  965): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  965): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  965): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  965): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 58717
E/LocSvc_MsgTask(  965): D/MsgTask::loop() 27 listening ...
,E/LocSvc_utils_q(  965): D/msg_q_rcv: Waiting on message
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0,
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4265): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4265): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
E/Parcel  (  411): Reading a NULL string not supported here.
,E/Parcel  (  411): Reading a NULL string not supported here.
,D/WifiStateMachine(  965): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  965): handleMessage: E msg.what=131212
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  965): processMsg: SupplicantStartedState
,D/WifiStateMachine(  965): processMsg: DefaultState
,D/WifiStateMachine(  965): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.140/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  965): send additional Connectivity Action
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  965): handleMessage: X
D/QcConnectivityService(  965): handleConnectivityChange:1 is conntected
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
,D/LocSvc_java(  965): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  965): ignore wifi update if we are not in OPENING or CLOSING
,D/QcConnectivityService(  965): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  965):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,E/QcConnectivityService(  965): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  965): requiresClat: netType=1, hasIPv4Address=true
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GpsLocationProvider(  965): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1451): getPreferredApnId: subscription=0
,D/dalvikvm(  965): GC_CONCURRENT freed 1789K, 50% free 29059K/57648K, paused 52ms+9ms, total 207ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  965): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  965): NoActiveNetworkState{ when=-4ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/        (  965): Setting time of day to sec=1450201713
,W/        (  965): Unable to set rtc to 1450201713: Invalid argument
,I/SecureClockService( 1157): Intent.ACTION_TIME_CHANGED 
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/QCNEA   (  411): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/Tethering(  965): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  965): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/MusicWidget( 2102): intentReceiver onReceive() action::android.intent.action.TIME_SET
,I/MusicWidget( 2102): beingMusicWidget_4x2() result::false
,I/MusicWidget( 2102): beingMusicWidget_Lock() result::false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/MusicWidget( 2102): beingMusicWidget_Quick() result::false
D/WeatherService( 1823): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 18:48:33
I/[LGHome]LGCalendarIcon( 1489): [LGCalendarIcon.java:188:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 15
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_SET
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_SET, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450201713481, nextTick: 26552, mDrawingTime: 0
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450201713482, nextTick: 26551, mDrawingTime: 0
,I/MusicWidget( 2102): beingMusicWidget_4x1() result::true
,D/WeatherService( 1823): 2 : requestRefreshAppWidget, isUpdateStart : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/MusicWidget( 2102): performViewUpdater handleMessage() msg.what::0
D/UpdateThreadPoolManager( 1823): 2 : This is isUpdating : false
D/WeatherService( 1823): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1823): 2 : buildUpdate, appWidgetId: 1
I/MusicWidget( 2102): beingMusicWidget_4x1() result::true
I/MusicWidget( 2102): performUpdate()_4x1
D/WeatherReflect( 1823): 2 : Map key string is -2
I/[LGHome]LGCalendarIcon( 1489): [LGCalendarIcon.java:188:makeCalendarBitmap()]Locale = en_US dayofweek= Tue date= 15
I/MusicWidget( 2102): status::mounted
I/MusicWidget( 2102): defaultAppWidget()_4x1
I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/MusicWidget( 2102): 4x1_currentTheme :: com.lge.launcher2.theme.optimus
I/MusicWidget( 2102): setDefaultViewLayoutId()_4x1
D/lim     ( 1823): 2 : time = 18:48
I/WeatherReflect( 1823): Model Name : LG-D802
D/WeatherTheme( 1823): 2 : Different view - status_min_formatted : 46 != 48
D/WeatherTheme( 1823): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1823): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1823): 2 : Fixed theme : optimus
D/WeatherTheme( 1823): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
D/WeatherService( 1823): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 18:48:33
I/MusicWidget( 2102): appWidgetViewUpdate()_4x1
I/MusicWidget( 2102): linkButtons()_4x1
I/MusicWidget( 2102): pushUpdate()_4x1
I/MusicWidget( 2102): performViewUpdater handleMessage() msg.what::3
I/MusicWidget( 2102): beingMusicWidget_Quick() result::false
,I/NetworkStateForAutoUpdateMonitor( 3678): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3678): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3678): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3678): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3678): onReceive
D/AppUp4:CustFacade( 3678): Context : android.app.ReceiverRestrictedContext@42879300
D/AppUp4:CustFacade( 3678): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 3678): isOpenOperator : true
,D/AppUp4:CustFacade( 3678): isPhone : true
I/LicenseContentProvider( 2945): start selecting data
,D/SIMObserver( 2945): simInfo1
,I/AppUp4:EulaManager( 3678): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3678): begin check event
I/AppUp4:CustModeStarterReceiver( 3678): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 3678): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 3678): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 3678): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 3678): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 3678): handleAsyncCustNotification do not startCustService
,I/ActivityManager(  965): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4591 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/ActivityManager(  965): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=4603 uid=10063 gids={50063, 3003, 1028, 1015}
,I/GoogleURLConnFactory( 1558): Using platform SSLCertificateSocketFactory
,D/HyLog   ( 4591): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4591): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4591): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4603): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4603): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4603): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/MusicWidget( 2102): performViewUpdater handleMessage() msg.what::1
,I/MusicWidget( 2102): beingMusicWidget_4x2() result::false
,I/MusicWidget( 2102): beingMusicWidget_Lock() result::false
,D/EAS     ( 4123): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4123): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4591): DownloadService onCreate
,D/eas_req ( 4123): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/DownloadManager( 4591): in removeSpuriousFiles
,V/DownloadManager( 4591): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4591): created cursor android.database.sqlite.SQLiteCursor@428ac9f0 on behalf of 4591
,I/DownloadManager( 4591): in trimDatabase
,V/DownloadManager( 4591): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/LgeMiscReceiver( 3879): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3879): action = android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 4591): DownloadService onStartCommand
,V/DownloadManager( 4591): DownloadService onStartCommand
,I/LgeMiscReceiver( 3879): networkInfo.isConnected() = false
,V/DownloadManager( 4591): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4591): created cursor android.database.sqlite.SQLiteCursor@428b0100 on behalf of 4591
,V/DownloadManager( 4591): created cursor android.database.sqlite.SQLiteCursor@428b2088 on behalf of 4591
,W/linker  ( 4123): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4123): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4123): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
,D/HtmlEditor( 4123): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,I/dalvikvm( 4123): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
,I/ActivityManager(  965): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4630 uid=10052 gids={50052, 3003}
D/HtmlEditor( 4123): register_HtmlEditor, Success
D/HtmlEditor( 4123): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4123): register_HtmlEditorTimer, Success
D/HtmlEditor( 4123): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4123): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4123): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4123): register_HtmlEditorFont, Success
V/DownloadManager( 4591): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/HtmlEditor( 4123): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4123): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4123): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4123): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4123): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4123): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4123): JNI_OnLoad Success
I/HubEmail( 4123): JNI_OnLoad()
I/HubEmail( 4123): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4123): registerNatives()
I/HubEmail( 4123): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4123): registerNativeMethods()
I/HubEmail( 4123): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
V/DownloadManager( 4591): created cursor android.database.sqlite.SQLiteCursor@428b6250 on behalf of 4591
W/Settings( 4123): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 4591): DownloadService onDestroy
D/HyLog   ( 4630): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4630): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4630): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/DelayedSyncController( 4603): Delaying sync.
,W/DriveInitializer( 1892): Background init thread started
I/ActivityManager(  965): Killing 4083:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327ac48 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a035a0 u0 com.test.thalitest/.MainActivity t3}
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
I/ActivityManager(  965): Killing 3696:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327ac48 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a035a0 u0 com.test.thalitest/.MainActivity t3}
V/LGRssiData( 4630): [loadRssi] File not exist 
V/LGRssiData( 4630): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4630): [loadFeatureFromXml] *** start feature loading from xml
W/BaseRuntimeLoader( 4630): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4630): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4630): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4630): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/TelephonyAutoProfiling( 4630): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4630): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4630): [getValue] FEATURE key : vzw_roaming_state, value : null
E/BatteryObserver( 1157): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/MobileConnectivityChangeReceiver( 4630): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4630): onReceive CONNECTIVITY_CHANGE networkType=1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  965): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4648 uid=10066 gids={50066, 4002, 3003, 1028}
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
I/ActivityManager(  965): Killing 4142:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,D/WifiController(  965): battery changed pluggedType: 2
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/PhoneMonitor( 4630): onOtaspChanged old =0, new =3
V/PhoneMonitor( 4630): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
D/HeadsetStateMachine( 1226): Disconnected process message: 10
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/dalvikvm(  268): GC_EXPLICIT freed 46K, 34% free 16472K/24832K, paused 1ms+1ms, total 17ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327ac48 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a035a0 u0 com.test.thalitest/.MainActivity t3}
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/WifiController(  965): battery changed pluggedType: 2
D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 14ms
,E/Auth.Api.Credentials( 1892): [CredentialSyncAdapter] Unknown sync event.
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 14ms
,D/HyLog   ( 4648): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4648): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4648): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/DrmBroadcastReceiver( 4648): Receive CONNECTIVITY_ACTION
,D/LGDMClient( 2831): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4347): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2831): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/ActivityManager(  965): Killing 3760:com.android.vending/u0a50 (adj 15): empty #17
,W/ContextImpl( 4347): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/LGDMClient( 2831): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4361): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4361): CONNECT : WIFI_CONNECT
I/CheckinService( 1892): Checking schedule, now: 1450201713880 next: 1450199037120
I/CheckinService( 1892): active receiver: enabled
,D/dalvikvm( 1558): GC_EXPLICIT freed 801K, 29% free 17875K/24832K, paused 1ms+4ms, total 34ms
I/ActivityManager(  965): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4673 uid=10104 gids={50104, 3003, 1028, 1015}
,W/DriveInitializer( 1892): Awaiting to be initialized
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327ac48 stackId=1, 2 tasks}
,E/LGDMClient( 2831): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2831): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a035a0 u0 com.test.thalitest/.MainActivity t3}
D/LGDMClient( 2831): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2831): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,I/CheckinService( 1892): Preparing to send checkin request
,I/EventLogService( 1892): Accumulating logs since 1450201617274
,D/HyLog   ( 4673): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4673): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4673): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/DriveInitializer( 1892): Background init thread ended
,D/dalvikvm( 1892): GC_CONCURRENT freed 1237K, 23% free 19235K/24832K, paused 3ms+4ms, total 37ms
,D/dalvikvm( 1892): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/dalvikvm( 1892): WAIT_FOR_CONCURRENT_GC blocked 10ms
D/dalvikvm( 1892): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 1892): WAIT_FOR_CONCURRENT_GC blocked 11ms
,W/GAV2    ( 4673): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/DelayedSyncController( 4603): Delaying sync.
,I/CheckinRequestBuilder( 1892): Checkin reason type: 8 attempt count: 1
,D/WifiService(  965): New client listening to asynchronous messages
,E/ActivityThread( 1892): Failed to find provider info for com.google.android.wearable.settings
,V/WebViewChromium( 4673): Binding Chromium to the main looper Looper (main, tid 1) {42862cc8}
,I/chromium( 4673): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4673): Initializing chromium process, renderers=0
,W/chromium( 4673): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/VacuumService( 1558): Vacuum at: now=1450201714139 tag=VacuumService
,I/Adreno-EGL( 4673): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4673): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4673): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4673): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4673): Remote Branch: 
I/Adreno-EGL( 4673): Local Patches: 
I/Adreno-EGL( 4673): Reconstruct Branch: 
,I/NSApplication( 4673): Starting up...
,I/ActivityManager(  965): Killing 1753:com.google.android.gms.wearable/u0a6 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327ac48 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a035a0 u0 com.test.thalitest/.MainActivity t3}
,D/dalvikvm( 3734): GC_FOR_ALLOC freed 734K, 16% free 20909K/24832K, paused 19ms, total 20ms
,I/dalvikvm-heap( 3734): Grow heap (frag case) to 26.501MB for 4099024-byte allocation
,D/dalvikvm( 3734): GC_CONCURRENT freed 38K, 14% free 24895K/28836K, paused 2ms+1ms, total 12ms
,D/dalvikvm(  965): GC_EXPLICIT freed 1607K, 50% free 29034K/57648K, paused 2ms+7ms, total 107ms
,I/GoogleURLConnFactory( 1558): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1558): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1558): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1558): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1558): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,E/ThermalEngine(  287): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,W/Uploader( 1558): No account for auth token provided
,W/BaseRuntimeLoader( 1892): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1892): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1892): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1892): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/iu.SyncManager( 1892): SYNC; picasa accounts
,D/NetworkLogImpl( 1892): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1892): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1892): num queued entries: 0
,I/iu.UploadsManager( 1892): num updated entries: 0
,I/iu.SyncManager( 1892): NEXT; no task
,I/ActivityManager(  965): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=4736 uid=10010 gids={50010, 3003, 1028, 4002}
,D/HyLog   ( 4736): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4736): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4736): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/GLSUser ( 1558): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1558): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1558): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1558): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1558): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/OpenGL ES Test( 4736): getCurrentLocale == en_US
,E/OpenGL ES Test( 4736): localeFound retString == en_US
E/OpenGL ES Test( 4736): getCurrentLocale == en_US
,E/OpenGL ES Test( 4736): localeFound retString == en_US
,D/ALBootInit( 4736): ====action==>android.intent.action.TIME_SET
,D/ALBootInit( 4736): Alarm ALBootInit: TIME_SET
,D/Alarms  ( 4736): [setNextAlert] start
,D/Alarms  ( 4736): [setNextAlert] (1)
,I/Auth    ( 1558): [DefaultAuthDelegateService] Use browser flow? false
,D/Alarms  ( 4736):  minTime  = 0
,D/Alarms  ( 4736):  -- OK multi -- 0
E/jeny.kim( 4736): [setNextAlert] setNextAlert  temp_Alarmlink + 
,E/jeny.kim( 4736): [setNextAlert]setNextAlert temp_AlarmLinkText + 
,D/Alarms  ( 4736): setStatusBarIcon : false
,D/Alarms  ( 4736): Enter formatDayAndTime(final Context context, long timeInMiliSec)
,D/WorldClockReceiver( 4736): ====action==>android.intent.action.TIME_SET
,E/OpenGL ES Test( 4736): getCurrentLocale == en_US
E/OpenGL ES Test( 4736): localeFound retString == en_US
E/OpenGL ES Test( 4736): getCurrentLocale == en_US
E/OpenGL ES Test( 4736): localeFound retString == en_US
E/OpenGL ES Test( 4736): getCurrentLocale == en_US
E/OpenGL ES Test( 4736): localeFound retString == en_US
,E/OpenGL ES Test( 4736): getCurrentLocale == en_US
,E/OpenGL ES Test( 4736): localeFound retString == en_US
,W/CheckinRequestBuilder( 1892): awaiting user notification for token
,E/OpenGL ES Test( 4736): isExistDatabase = false
D/NotificationService(  965): updateLightListLocked :r=null, action=2
,I/CommonUtil( 4736): BUILD Country: EU
E/OpenGL ES Test( 4736): loadMapCityData() -- S
E/OpenGL ES Test( 4736): getCurrentLocale == en_US
E/OpenGL ES Test( 4736): localeFound retString == en_US
E/OpenGL ES Test( 4736): getCurrentLocale == en_US
,E/OpenGL ES Test( 4736): localeFound retString == en_US
,E/OpenGL ES Test( 4736): loadMapCityData() - While S
,I/ActivityManager(  965): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4753 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 4753): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4753): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4753): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,E/OpenGL ES Test( 4736): loadMapCityData() - While E
E/OpenGL ES Test( 4736): loadMapCityData() -- E
,E/OpenGL ES Test( 4736): getCurrentLocale == en_US
E/OpenGL ES Test( 4736): localeFound retString == en_US
E/OpenGL ES Test( 4736): getCurrentLocale == en_US
E/OpenGL ES Test( 4736): localeFound retString == en_US
W/dalvikvm( 4753): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4753): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 4753): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4753): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4753): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 4753): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4753): install
,I/MultiDex( 4753): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4753): loading existing secondary dex files
,I/MultiDex( 4753): load found 3 secondary dex files
,I/MultiDex( 4753): install done
,E/OpenGL ES Test( 4736): [updateWidgetDST] backup_cityInfoList is null >>>>
,I/ActivityManager(  965): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory: pid=4767 uid=10015 gids={50015, 3003, 1028, 1015}
,I/ActivityManager(  965): Killing 4110:com.lge.bnr/1000 (adj 15): empty #17
,D/dalvikvm( 4753): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4753): VFY: unable to resolve instance field 61
,D/dalvikvm( 4753): VFY: replacing opcode 0x54 at 0x0054
,D/dalvikvm( 4753): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4753): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4753): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 4753): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4753): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4753): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4753): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4753): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 4753): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4286b300
D/dalvikvm( 4753): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4286b300
,D/dalvikvm( 4753): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4286b300, skipping init
,D/dalvikvm( 4753): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4286b300
D/dalvikvm( 4753): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4286b300
,V/JNIHelp ( 4753): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/HyLog   ( 4767): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4767): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4767): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327ac48 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a035a0 u0 com.test.thalitest/.MainActivity t3}
,W/Uploader( 1558): No account for auth token provided
,D/GCM     ( 1558): Connected
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
I/Config  ( 4767): LGCalendar ver.4.2.6
I/Config  ( 4767): start check model
,I/Config  ( 4767): start check native_ca
,E/Config  ( 4767): [setCountryAndOperator] Operator=OPEN, Country=EU
,D/dalvikvm( 4753): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4286b300
,D/dalvikvm( 4753): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x4286b300
D/dalvikvm( 4753): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4286b300
D/dalvikvm( 4753): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4286b300
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1558): Message class com.google.f.a.a.p
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/ProviderInstaller( 4753): Installed default security provider GmsCore_OpenSSL
,W/Uploader( 1558):  no longer exists, so no auth token.
,I/dalvikvm( 4753): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 4753): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4753): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4753): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4753): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4753): VFY: replacing opcode 0x6e at 0x0201
,I/ActivityManager(  965): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=4782 uid=10050 gids={50050, 3003, 1028, 1015}
,D/HyLog   ( 4782): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4782): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4782): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/CalendarWidget( 4767): Agenda AppWidgetService got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory }
,W/Uploader( 1558): No account for auth token provided
,I/InitNotificationRingtoneService( 4767): Start InitializeAlertRingtoneService.onHandleIntent
,I/dalvikvm( 4782): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
,W/dalvikvm( 4782): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4782): VFY: replacing opcode 0x6e at 0x000b
I/ActivityManager(  965): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4798 uid=10016 gids={50016, 3003, 1028, 1015}
,D/WVCdm   (  271): Instantiating CDM.
,I/WVCdm   (  271): Level3 Library Nov 20 2013 18:09:31
,W/Uploader( 1558): No account for auth token provided
,D/DrmWidevineDash(  271): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/QSEECOMAPI: (  271): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  271): App is not loaded in QSEE
,D/Finsky  ( 4782): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/InitNotificationRingtoneService( 4767): internal content query returns 1 results.
,I/InitNotificationRingtoneService( 4767): Found default schedule notification : Schedule.ogg(id:42)
,I/InitNotificationRingtoneService( 4767): set default noti to content://media/internal/audio/media/42
,I/InitNotificationRingtoneService( 4767): End InitializeAlertRingtoneService.onHandleIntent
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
,D/HyLog   ( 4798): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4798): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4798): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/QSEECOMAPI: (  271): Loaded image: APP id = 2
D/DrmWidevineDash(  271): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1f2a000
,E/DrmWidevineDash(  271): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1f2a000
,I/dalvikvm( 4782): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 4782): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4782): VFY: replacing opcode 0x6e at 0x004f
,D/DrmWidevineDash(  271): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  271): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  271): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  271): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  271): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  271): CdmEngine::OpenSession
,D/DrmWidevineDash(  271): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession returns 0
,W/BaseRuntimeLoader( 4782): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4782): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4782): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4782): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/WVCdm   (  271): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  271): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  271): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/Finsky  ( 4782): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.,
,D/DrmWidevineDash(  271): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GetDeviceID...
,I/CalendarProvider2( 4798): Created com.android.providers.calendar.CalendarAlarmManager@42885ba0(com.android.providers.calendar.CalendarProvider2@4287cb08)
,W/Settings( 4782): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/DrmWidevineDash(  271): OEMCrypto_GetDeviceID returns 0
D/DrmWidevineDash(  271): calling OEMCrypto_GenerateNonce. SID = 1
,W/Settings( 4782): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/DrmWidevineDash(  271): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  271): PrepareKeyRequest: nonce=3456588475
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/dalvikvm( 4782): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4782): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4782): VFY: replacing opcode 0x6e at 0x011e
I/dalvikvm( 4782): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
,W/dalvikvm( 4782): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4782): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 4782): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4782): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 4782): VFY: replacing opcode 0x6e at 0x029a
,I/ActivityManager(  965): Start proc com.lge.task for broadcast com.lge.task/.widget.TasksWidgetProvider: pid=4846 uid=10043 gids={50043, 3003, 1028, 1015}
I/dalvikvm( 4782): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4782): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
D/dalvikvm( 4782): VFY: replacing opcode 0x6e at 0x001a
,D/dalvikvm( 4753): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a8afa8
,I/ActivityManager(  965): Killing 4292:com.lge.settings.easy/1000 (adj 15): empty #17
D/dalvikvm( 4753): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a8afa8
D/dalvikvm( 4753): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a8afa8, skipping init
I/dalvikvm( 4782): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
W/dalvikvm( 4782): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
D/dalvikvm( 4782): VFY: replacing opcode 0x6e at 0x0049
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327ac48 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a035a0 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4846): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4846): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4846): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,V/DownloadManager( 4591): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,D/Finsky  ( 4782): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4782): [1] 2.run: Finished loading 1 libraries.
V/DownloadManager( 4591): created cursor android.database.sqlite.SQLiteCursor@428be608 on behalf of 4782
,E/TASKS   ( 4846): init() PortStorageManger PRIMARY_STORAGE_PATH :/storage/emulated/0
,D/TASKS_APP_WIDGET( 4846): onReceive() #################################################
,I/TASKS   ( 4846): getCurrentThemeInfo START #############################
,I/TASKS   ( 4846): com.lge.launcher2.theme.optimus
,I/TASKS   ( 4846): com.lge.task
I/TASKS   ( 4846): getCurrentThemeInfo END #############################
I/TASKS   ( 4846): loadThemeResources packageName : com.lge.task
,I/TASKS   ( 4846): loadLocalResId #############################
,D/TASKS_APP_WIDGET( 4846): intentAction : android.intent.action.TIME_SET
,I/ActivityManager(  965): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4863 uid=10122 gids={50122}
,D/Finsky  ( 4782): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  965): Killing 4305:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327ac48 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a035a0 u0 com.test.thalitest/.MainActivity t3}
D/HyLog   ( 4863): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4863): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4863): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/Finsky  ( 4782): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/dalvikvm( 4863): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x4286ee80, skipping init
D/TimeService( 4863): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1450201714978
D/        ( 4863): TimeServiceNative: User Time to be set is 1450201714978
D/QC-time-services( 4863): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 4863): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 4863): Lib:time_genoff_operation: pargs->ts_val = 1450201714978
D/QC-time-services( 4863): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  420): Daemon: Connection accepted:time_genoff
D/QC-time-services(  420): Daemon:Received base = 2, unit = 1, operation = 0,value = 1450201714978
D/QC-time-services(  420): Daemon:genoff_opr: Base = 2, val = 1450201714978, operation = 0
D/QC-time-services(  420): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/22/70 5:33:23
D/QC-time-services(  420): Daemon:Value read from RTC seconds = 9610403000
D/QC-time-services(  420): Daemon:new time 1450201714978 
D/QC-time-services(  420): Daemon: delta 1440591311978 genoff 1440591311978 
D/QC-time-services(  420): Daemon:genoff_persistent_update: Writing genoff = 1440591311978 to memory
D/QC-time-services(  420): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  420): Daemon:time_persistent_memory_opr:Genoff write operation 
,I/dalvikvm( 4782): Total arena pages for JIT: 11
,I/dalvikvm( 4782): Total arena pages for JIT: 12
I/dalvikvm( 4782): Total arena pages for JIT: 13
,I/dalvikvm( 4782): Total arena pages for JIT: 14
,D/QC-time-services(  420): Updating the TOD offset
D/QC-time-services(  420): Daemon:genoff_persistent_update: Writing genoff = 1440591311978 to memory
D/QC-time-services(  420): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  420): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  420): Daemon:Update to modem bit set
D/QC-time-services(  420): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  420): Daemon: Base = 2, Value being sent to MODEM = 1134236914978
,E/QC-time-services( 4863): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  420): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  420): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
I/ActivityManager(  965): Killing 4442:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327ac48 stackId=1, 2 tasks}
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a035a0 u0 com.test.thalitest/.MainActivity t3}
D/QcConnectivityService(  965): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/dalvikvm( 1558): GC_CONCURRENT freed 1706K, 28% free 18092K/24832K, paused 2ms+2ms, total 22ms
,I/NetworkStateForAutoUpdateMonitor( 3678): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 3678): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3678): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3678): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 3678): onReceive
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/AppUp4:CustFacade( 3678): Context : android.app.ReceiverRestrictedContext@42879300
D/AppUp4:CustFacade( 3678): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3678): isOpenOperator : true
,D/AppUp4:CustFacade( 3678): isPhone : true
,I/LicenseContentProvider( 2945): start selecting data
,D/SIMObserver( 2945): simInfo1
,I/AppUp4:EulaManager( 3678): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3678): begin check event
,I/AppUp4:CustModeStarterReceiver( 3678): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4591): DownloadService onCreate
,I/DownloadManager( 4591): in removeSpuriousFiles
,D/EAS     ( 4123): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4123): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4591): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4591): created cursor android.database.sqlite.SQLiteCursor@428c2410 on behalf of 4591
,V/DownloadManager( 4591): DownloadService onStartCommand
,V/DownloadManager( 4591): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/LgeMiscReceiver( 3879): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3879): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3879): networkInfo.isConnected() = true
,D/PhoneState( 3879): setPdpRejectCasuse : false
,I/DownloadManager( 4591): in trimDatabase
V/DownloadManager( 4591): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/MobileConnectivityChangeReceiver( 4630): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4630): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4591): created cursor android.database.sqlite.SQLiteCursor@428c53e0 on behalf of 4591
,V/DownloadManager( 4591): created cursor android.database.sqlite.SQLiteCursor@428c5ab0 on behalf of 4591
,W/Settings( 4123): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/DrmBroadcastReceiver( 4648): Receive CONNECTIVITY_ACTION
,D/DrmBroadcastReceiver( 4648): 1  network is available. Sync DRM Time with NTP
,V/DrmService( 4648): Service onCreate
,D/DrmService( 4648): Received new request = 2
,D/LGDMClient( 2831): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
I/DrmSntpClient( 4648): Start Sync process
,D/DrmSntpClient( 4648): Server : 0
D/LGDMClient( 2831): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,D/LGDMSGCM( 4347): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4591): DownloadService onDestroy
,E/DataScheduler( 4648): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/LGDMClient( 2831): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 4347): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 4361): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4361): CONNECT : WIFI_CONNECT
,E/LGDMClient( 2831): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2831): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2831): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2831): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
,D/dalvikvm( 3734): GC_FOR_ALLOC freed 8K, 14% free 24889K/28836K, paused 12ms, total 12ms
,I/dalvikvm-heap( 3734): Grow heap (frag case) to 30.388MB for 4099024-byte allocation
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4265): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4265): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
E/Parcel  (  411): Reading a NULL string not supported here.
,E/Parcel  (  411): Reading a NULL string not supported here.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 3734): GC_CONCURRENT freed 3K, 13% free 28893K/32840K, paused 2ms+1ms, total 17ms
,D/dalvikvm( 3734): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/dalvikvm-heap( 3734): Grow heap (frag case) to 34.298MB for 4099024-byte allocation
,D/WifiController(  965): battery changed pluggedType: 2
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1226): Disconnected process message: 10
I/LGDrmService( 4648): _DRM_ServiceGet() : Bind lgdrm service
I/LGDRM   (  276): [DRM] SET TIME : YR=2015, MON=12, DAY=15
I/LGDRM   (  276): [DRM] SET TIME : HR=17, MIN=48, SEC=35
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
I/DrmSntpClient( 4648): Synched
D/DrmService( 4648): Completed !! request = 2
D/DrmService( 4648): Request count = 0
V/DrmService( 4648): Service onDestroy
,D/WeatherAncestor( 1823): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 18:48:35
,D/UpdateThreadPoolManager( 1823): 2 : This is isUpdating : false
D/Weather_cast( 1823): 2 : Request from alarm is Canceled
,D/WeatherAncestor( 1823): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 18:48:35
D/WeatherService( 1823): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
,D/WeatherQuickCover( 1823): 2 : quick cover state : opened : 0
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/Weather.Utils( 1823): 2 : Utils getTopActivity com.lge.launcher2 / false
D/Weather.Utils( 1823): 2 : Utils getTopActivity com.lge.easyhome / false
,D/WeatherService( 1823): 2 : shouldTimeTickRegistered : false
I/ActivityManager(  965): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=4889 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,D/HyLog   ( 4889): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4889): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4889): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm( 4753): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/Finsky  ( 4782): [405] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4782): [1] 5.onFinished: Installation state replication succeeded.
I/ActivityManager(  965): Killing 3711:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327ac48 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a035a0 u0 com.test.thalitest/.MainActivity t3}
,I/Babel   ( 4889): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4889): MmsConfig.loadMmsSettings
,D/dalvikvm( 4901): DexOpt: load 2ms, verify+opt 3ms, 128132 bytes
,I/MediaCodecList( 4889): getNewMediaCodecItem [0][DTSDecode][audio/dts]
,I/Babel   ( 4889): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 4889): MmsConfig.loadFromDatabase
,I/MediaCodecList( 4889): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 4889): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 4889): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 4889): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4889): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4889): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4889): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 4889): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4889): MmsConfig.loadFromResources
,E/Babel   ( 4889): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4889): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 4889): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
D/dalvikvm( 4753): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4753): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 65ms
,V/LGRssiData( 4889): [loadRssi] File not exist 
V/LGRssiData( 4889): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4889): [loadFeatureFromXml] *** start feature loading from xml
,I/Adreno-EGL( 4753): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4753): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4753): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4753): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4753): Remote Branch: 
I/Adreno-EGL( 4753): Local Patches: 
I/Adreno-EGL( 4753): Reconstruct Branch: 
,V/TelephonyAutoProfiling( 4889): [getMatchedProfile] selected file : /cust/config/featureset.xml
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
V/TelephonyAutoProfiling( 4889): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4889): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/Tethering(  965): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  965): DelayedCaptiveCheckState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/GCM     ( 1558): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1558): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1558): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1892): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/ActivityManager(  965): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4918 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
D/LocationInitializer( 1892): Restart initialization of location
,D/CalendarWidget( 4767): Agenda AppWidgetService init broadcastReceiver
,D/CalendarWidget( 4767): Agenda AppWidgetProvider got the intent: Intent { act=com.lge.calendar.action.APPWIDGET_UPDATE flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetProvider }
D/TASKS_APP_WIDGET( 4846): onReceive() #################################################
,I/TASKS   ( 4846): getCurrentThemeInfo START #############################
,I/WifiServiceExtension(  965): MESSAGE_INTERNET_CHECK msg is received.
,I/Adreno-EGL( 4753): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4753): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4753): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4753): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4753): Remote Branch: 
I/Adreno-EGL( 4753): Local Patches: 
I/Adreno-EGL( 4753): Reconstruct Branch: 
,W/ActivityThread(  965): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/TASKS   ( 4846): com.lge.launcher2.theme.optimus
I/TASKS   ( 4846): com.lge.task
I/TASKS   ( 4846): getCurrentThemeInfo END #############################
I/TASKS   ( 4846): loadThemeResources packageName : com.lge.task
I/TASKS   ( 4846): loadLocalResId #############################
D/TASKS_APP_WIDGET( 4846): intentAction : com.lge.task.APPWIDGET_UPDATE
D/HyLog   ( 4918): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4918): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4918): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/NetworkStateForAutoUpdateMonitor( 3678): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 3678): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3678): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 3678): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 3678): onReceive
D/AppUp4:CustFacade( 3678): Context : android.app.ReceiverRestrictedContext@42879300
D/AppUp4:CustFacade( 3678): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3678): isOpenOperator : true
D/AppUp4:CustFacade( 3678): isPhone : true
I/LicenseContentProvider( 2945): start selecting data
D/SIMObserver( 2945): simInfo1
,I/AppUp4:EulaManager( 3678): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3678): begin check event
,I/AppUp4:CustModeStarterReceiver( 3678): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4591): DownloadService onCreate
D/EAS     ( 4123): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,I/DownloadManager( 4591): in removeSpuriousFiles
,V/DownloadManager( 4591): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/EAS     ( 4123): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4591): created cursor android.database.sqlite.SQLiteCursor@428c9cd0 on behalf of 4591
,I/DownloadManager( 4591): in trimDatabase
,V/DownloadManager( 4591): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/WVCdm   (  271): CdmEngine::OpenSession
,D/DrmWidevineDash(  271): calling OEMCrypto_OpenSession...
W/dalvikvm( 4918): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4918): VFY: replacing opcode 0x60 at 0x000b
D/dalvikvm( 4918): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4918): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4918): VFY: replacing opcode 0x62 at 0x005e
D/DrmWidevineDash(  271): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  271): CdmEngine::QueryKeyControlInfo
D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/MultiDex( 4918): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4918): install
I/WVCdm   (  271): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  271): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,I/MultiDex( 4918): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4918): loading existing secondary dex files
D/DrmWidevineDash(  271): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GetDeviceID...
,I/MultiDex( 4918): load found 3 secondary dex files
,I/MultiDex( 4918): install done
,D/DrmWidevineDash(  271): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  271): PrepareKeyRequest: nonce=2990963413
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,V/WifiServiceExtension(  965): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  965): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/WifiController(  965): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1226): Disconnected process message: 10
D/dalvikvm(  965): GC_EXPLICIT freed 1267K, 49% free 29521K/57648K, paused 2ms+7ms, total 104ms
,V/DownloadManager( 4591): created cursor android.database.sqlite.SQLiteCursor@428cb378 on behalf of 4591
,I/LgeMiscReceiver( 3879): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3879): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3879): networkInfo.isConnected() = true
,D/PhoneState( 3879): setPdpRejectCasuse : false
,V/DownloadManager( 4591): DownloadService onStartCommand
,V/DownloadManager( 4591): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/MobileConnectivityChangeReceiver( 4630): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
W/Settings( 4123): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 4630): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4591): created cursor android.database.sqlite.SQLiteCursor@428cd878 on behalf of 4591
,D/dalvikvm( 4918): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4918): VFY: unable to resolve instance field 61
,D/dalvikvm( 4918): VFY: replacing opcode 0x54 at 0x0054
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
D/dalvikvm( 4918): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4918): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4918): VFY: replacing opcode 0x62 at 0x0067
V/DownloadManager( 4591): DownloadService onDestroy
D/LGDMClient( 2831): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
D/dalvikvm( 4918): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 4918): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/LGDMSGCM( 4347): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/dalvikvm( 4918): VFY: replacing opcode 0x62 at 0x000a
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
D/dalvikvm( 4918): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4918): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
I/NFS     ( 4361): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4361): CONNECT : WIFI_CONNECT
,D/dalvikvm( 4918): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42871f10
,I/GLSUser ( 1558): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1558): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1558): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1558): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/dalvikvm( 4918): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42871f10
,D/dalvikvm( 4918): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42871f10, skipping init
,W/ContextImpl( 4347): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
D/LGDMClient( 2831): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
V/GLSActivity( 1558): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/dalvikvm( 4918): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42871f10
D/dalvikvm( 4918): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42871f10
V/JNIHelp ( 4918): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/LGDMClient( 2831): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,E/LGDMClient( 2831): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,I/Auth    ( 1558): [DefaultAuthDelegateService] Use browser flow? false
,D/LGDMClient( 2831): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2831): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2831): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/dalvikvm( 3734): GC_CONCURRENT freed 7K, 10% free 33211K/36844K, paused 1ms+1ms, total 23ms
,E/Babel   ( 4889): UserRecoverableAuthException.
,E/Babel   ( 4889): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/Babel   ( 4889): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4889): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:190)
E/Babel   ( 4889): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4889): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4889): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4889): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4889): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4889): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4889): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:880)
E/Babel   ( 4889): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1068)
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,E/Babel   ( 4889): Error getting auth token
,E/Babel   ( 4889): com.google.android.apps.babel.util.AccountsUtil$BabelAuthException
E/Babel   ( 4889): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:200)
E/Babel   ( 4889): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4889): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4889): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4889): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4889): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4889): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4889): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:880)
E/Babel   ( 4889): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1068)
,E/Babel   ( 4889): Account registration failedRedacted-21
,E/Babel   ( 4889): com.google.android.apps.babel.realtimechat.RequestWriter$BabelClientException: null -- null
E/Babel   ( 4889): 	at com.google.android.apps.babel.network.c.d(SourceFile:115)
E/Babel   ( 4889): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4889): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4889): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4889): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4889): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4889): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:880)
E/Babel   ( 4889): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1068)
I/Babel   ( 4889): Account setup failed with error state:106 account:Redacted-21
,I/Babel   ( 4889): Account sign in complete with state 106account: Redacted-21
,D/CalendarWidget( 4767): Agenda AppWidgetService init broadcastReceiver
,D/CalendarWidget( 4767): Agenda AppWidgetProvider got the intent: Intent { act=com.lge.calendar.action.APPWIDGET_UPDATE flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetProvider }
,I/GLSUser ( 1558): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1558): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1558): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1558): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/dalvikvm( 4918): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42871f10
D/dalvikvm( 4918): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42871f10
D/dalvikvm( 4918): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42871f10
,D/dalvikvm( 4918): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42871f10
,V/GLSActivity( 1558): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1558): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x4309ba20: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,E/Babel   ( 4889): Unexpected exception while authenticating.
,E/Babel   ( 4889): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/Babel   ( 4889): 	at com.google.android.gms.auth.a.b(Unknown Source)
E/Babel   ( 4889): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4889): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:187)
E/Babel   ( 4889): 	at com.google.android.apps.babel.network.c.cP(SourceFile:138)
E/Babel   ( 4889): 	at com.google.android.apps.babel.realtimechat.ca.run(SourceFile:5226)
E/Babel   ( 4889): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 4889): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 4889): 	at java.lang.Thread.run(Thread.java:841)
D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/ProviderInstaller( 4918): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1558): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1558): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1558): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1892): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  965): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/LocationInitializer( 1892): Restart initialization of location
,I/dalvikvm( 4918): Could not find method android.os.UserManager.getUserProfiles, referenced from method com.google.android.gms.wearable.service.n.a
,W/dalvikvm( 4918): VFY: unable to resolve virtual method 1402: Landroid/os/UserManager;.getUserProfiles ()Ljava/util/List;
,D/dalvikvm( 4918): VFY: replacing opcode 0x6e at 0x003f
,D/WearableService( 4918): callingUid 10006, callindPid: 4918
,E/dalvikvm( 4918): Could not find class 'android.telecom.TelecomManager', referenced from method com.google.android.gms.wearable.service.y.a
W/dalvikvm( 4918): VFY: unable to resolve check-cast 869 (Landroid/telecom/TelecomManager;) in Lcom/google/android/gms/wearable/service/y;
,D/dalvikvm( 4918): VFY: replacing opcode 0x1f at 0x0054
,W/dalvikvm( 4918): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,I/Adreno-EGL( 4753): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4753): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4753): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4753): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4753): Remote Branch: 
I/Adreno-EGL( 4753): Local Patches: 
I/Adreno-EGL( 4753): Reconstruct Branch: 
,I/dalvikvm( 4918): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 4918): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4918): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4918): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4918): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4918): VFY: replacing opcode 0x6e at 0x0201
,E/MDM     ( 1426): [88] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/MDM     ( 1426): [88] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/Settings( 4753): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 1892): Classify the device as Phone.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/Finsky  ( 4782): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/dalvikvm( 4782): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4782): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4782): VFY: replacing opcode 0x62 at 0x0037
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GLSUser ( 1558): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1558): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1558): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1558): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1558): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CalendarProvider2( 4798): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 4798): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/AlertReceiver( 4767): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/CalendarWidget( 4767): Agenda AppWidgetService got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory }
,D/AlertService( 4767): 0 Action = android.intent.action.PROVIDER_CHANGED
,D/AlertService( 4767): Beginning updateAlertNotification
,I/Auth    ( 1558): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 4782): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/AlertService( 4767): No fired or scheduled alerts
,D/CalendarWidget( 4767): Agenda AppWidgetService init broadcastReceiver
,D/CalendarWidget( 4767): Agenda AppWidgetProvider got the intent: Intent { act=com.lge.calendar.action.APPWIDGET_UPDATE flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetProvider }
,I/GLSUser ( 1558): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1558): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1558): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1558): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1558): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1558): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1558): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1558): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1558): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1558): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1558): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1558): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 4782): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/CheckinTask( 1892): Sending checkin request (11480 bytes)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
I/GLSUser ( 1558): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1558): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1558): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1558): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1558): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1558): [DefaultAuthDelegateService] Use browser flow? false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/Finsky  ( 4782): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4782): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 4782): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4782): [1] DailyHygiene.reschedule: Scheduling new run in 247 minutes (failures=4)
,D/DeviceConnectionService( 1426): client connected with version: 7571000
I/ActivityManager(  965): Killing 4736:com.lge.clock/u0a10 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327ac48 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a035a0 u0 com.test.thalitest/.MainActivity t3}
,I/CheckinRequestBuilder( 1892): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1892): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1892): GC_CONCURRENT freed 1764K, 22% free 19422K/24832K, paused 5ms+7ms, total 62ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/GLSUser ( 1558): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1558): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1558): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1558): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1558): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Auth    ( 1558): [DefaultAuthDelegateService] Use browser flow? false
,W/CheckinRequestBuilder( 1892): awaiting user notification for token
D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x42941808: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/CheckinRequestBuilder( 1892): Classify the device as Phone.
,I/CheckinTask( 1892): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1892): Checking schedule, now: 1450201716596 next: 1450779112592
,I/CheckinService( 1892): active receiver: disabled
,I/CheckinService( 1892): Checking schedule, now: 1450201716636 next: 1450779112592
,I/CheckinService( 1892): active receiver: disabled
,D/GCM     ( 1558): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  965): battery changed pluggedType: 2
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1226): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,D/WifiController(  965): battery changed pluggedType: 2
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4265): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4265): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
E/Parcel  (  411): Reading a NULL string not supported here.
,E/Parcel  (  411): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,D/WifiController(  965): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetStateMachine( 1226): Disconnected process message: 10
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
D/WifiController(  965): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1226): Disconnected process message: 10
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.463928 Y: -0.407516 Z: 9.747696 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.463928 .y:-0.407516 .z:9.747696
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.463730 Y: -0.406250 Z: 9.746735 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.463730 .y:-0.406250 .z:9.746735
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  965): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
D/WifiController(  965): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 4673): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  965): battery changed pluggedType: 2
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/WifiController(  965): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1226): Disconnected process message: 10
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/ActivityManager(  965): Killing 4863:com.qualcomm.timeservice/u0a122 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327ac48 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a035a0 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  965): Killing 4889:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  965): Killing 4846:com.lge.task/u0a43 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327ac48 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a035a0 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327ac48 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a035a0 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4265): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4265): nl80211: survey data missing!
,E/Parcel  (  411): Reading a NULL string not supported here.
,E/Parcel  (  411): Reading a NULL string not supported here.
,D/WifiStateMachine(  965): handleMessage: X
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/CaptivePortalTracker(  965): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/QcConnectivityService(  965): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker(  965): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  965): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  965): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  965): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  965): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  965): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/InputReader(  965): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "sms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
E/SlideAside( 3574): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3574): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.talk
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "smsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/administrator(  965): Handling package changes for user 0
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,E/SlideAside( 3574): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3574): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
D/AppUp4:Utils( 3678): [getPackageName] uri : package:com.google.android.talk
D/AppUp4  ( 3678): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
D/AppUp4  ( 3678): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.talk
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/InputReader(  965): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
D/WifiStateMachine(  965): handleMessage: E msg.what=131155
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4265): wlan0: Control interface command 'SIGNAL_POLL'
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mmsto"
,D/wpa_supplicant( 4265): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/AppUp4:CustModeStarterReceiver( 3678): onReceive
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,D/GlobalAccess( 1143): optimizeTargetDrawableItems(), newSize: 20
D/GlowPadView( 1143): changeTargets() succeeded. size: 20
D/AppUp4:CustFacade( 3678): Context : android.app.ReceiverRestrictedContext@42879300
D/AppUp4:CustFacade( 3678): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3678): isOpenOperator : true
D/AppUp4:CustFacade( 3678): isPhone : true
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "sms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/LicenseContentProvider( 2945): start selecting data
,D/SIMObserver( 2945): simInfo1
,I/AppUp4:EulaManager( 3678): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3678): begin check event
D/AppUp4:Utils( 3678): [getPackageName] uri : package:com.google.android.talk
,I/AppUp4:CustModeStarterReceiver( 3678): Event For Nothing, skip.
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "smsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  965): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5005 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,D/administrator(  965): Handling package changes for user 0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mmsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/dalvikvm(  268): GC_EXPLICIT freed 43K, 34% free 16472K/24832K, paused 2ms+2ms, total 24ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 19ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "sms"
D/HyLog   ( 5005): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5005): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5005): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 19ms
D/GlobalAccess( 1143): optimizeTargetDrawableItems(), newSize: 20
D/GlowPadView( 1143): changeTargets() succeeded. size: 20
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "smsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mmsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "sms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/SystemConfig( 5005): BUILD Country: EU
,I/SystemConfig( 5005): BUILD Operator: OPEN
I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  965):   Scheme: "smsto"
I/ActivityManager(  965): Killing 4591:android.process.media/u0a23 (adj 15): empty #17
,D/dalvikvm(  965): GC_CONCURRENT freed 3073K, 48% free 29715K/56852K, paused 4ms+7ms, total 100ms
,D/dalvikvm(  965): WAIT_FOR_CONCURRENT_GC blocked 67ms
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mms"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  965): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5021 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327ac48 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a035a0 u0 com.test.thalitest/.MainActivity t3}
,I/SystemConfig( 5005): systemFeature RCS result false
,D/SystemConfig( 5005): refreshRcsSupport() :false
,I/PackageManager(  965):   Action: "android.intent.action.SENDTO"
I/PackageManager(  965):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  965):   Scheme: "mmsto"
I/PackageManager(  965): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/HyLog   ( 5021): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5021): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5021): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/GmsNetworkLocationProvi( 1426): DISABLE
,I/IcingCorporaProvider( 2628): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,I/ActivityManager(  965): Killing 4123:com.lge.email/u0a24 (adj 15): empty #17
,I/GCoreNlp( 1426): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327ac48 stackId=1, 2 tasks}
D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a035a0 u0 com.test.thalitest/.MainActivity t3}
,D/PackageBroadcastService( 1892): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  965): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=5045 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/IcingCorporaProvider( 2628): UpdateCorporaTask done [took 54 ms] updated apps [took 54 ms] 
,I/PeopleContactsSync( 1892): CP2 sync disabled
,D/HyLog   ( 5045): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5045): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5045): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LocationProviderProxy(  965): applying state to connected service
,D/LocationProviderProxy(  965): applying state to connected service
,I/Babel   ( 5045): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 5045): MmsConfig.loadMmsSettings
,I/MediaCodecList( 5045): getNewMediaCodecItem [0][DTSDecode][audio/dts]
,I/MediaCodecList( 5045): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 5045): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 5045): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
I/Babel   ( 5045): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 5045): MmsConfig.loadFromDatabase
,W/BaseRuntimeLoader( 5045): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5045): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5045): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5045): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 5045): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 5045): MmsConfig.loadFromResources
,E/Babel   ( 5045): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 5045): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 5045): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/AppUp4:Utils( 3678): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 3678): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
D/AppUp4  ( 3678): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,V/LGRssiData( 5045): [loadRssi] File not exist 
V/LGRssiData( 5045): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5045): [loadFeatureFromXml] *** start feature loading from xml
,I/AppUp4:CustModeStarterReceiver( 3678): onReceive
V/TelephonyAutoProfiling( 5045): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5045): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5045): [getValue] FEATURE key : vzw_roaming_state, value : null
D/AppUp4:CustFacade( 3678): Context : android.app.ReceiverRestrictedContext@42879300
D/AppUp4:CustFacade( 3678): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3678): isOpenOperator : true
,D/AppUp4:CustFacade( 3678): isPhone : true
I/LicenseContentProvider( 2945): start selecting data
,D/SIMObserver( 2945): simInfo1
,I/AppUp4:EulaManager( 3678): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3678): begin check event
D/AppUp4:Utils( 3678): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 3678): Event For Nothing, skip.
,I/IcingCorporaProvider( 2628): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 1892): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1892): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  965): Delaying start of: ServiceRecord{432d1fe0 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1892): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  965): Killing 4630:com.google.android.setupwizard/u0a52 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327ac48 stackId=1, 2 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Top activity resumed ActivityRecord{43a035a0 u0 com.test.thalitest/.MainActivity t3}
,I/IcingCorporaProvider( 2628): UpdateCorporaTask done [took 202 ms] updated apps [took 202 ms] 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4265): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4265): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/GAV4    ( 5045): Thread[GAThread,5,main]: No campaign data found.
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4265): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4265): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X,
E/Parcel  (  411): Reading a NULL string not supported here.
,E/Parcel  (  411): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,I/PowerManagerService(  965): Going to sleep due to screen timeout...
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/KnockOnPowerController(  965): [updateScreenState] screen on = false
D/KnockOnPowerController(  965): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  965): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
I/qcom_sensors_hal(  965): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
I/qcom_sensors_hal(  965): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  965): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  965): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  965): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  965): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 9542 usec
D/KnockOnPowerController(  965): [setProximitySensorEnabled] enable = true
,D/qcom_sensors_hal(  965): hal_acquire_resources
I/qcom_sensors_hal(  965): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  965): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  965): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  965): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  965): hal_sam_algo_activate: Update freq 0 -> 20
I/qcom_sensors_hal(  965): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  965): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  965): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.451187 Y: -0.401337 Z: 9.777359 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.451187 .y:-0.401337 .z:9.777359
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,D/Finsky  ( 4782): [405] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4782): [1] 5.onFinished: Installation state replication succeeded.
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.438675 Y: -0.409012 Z: 9.767654 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.438675 .y:-0.409012 .z:9.767654
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,I/Sensors (  390): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  965): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  965): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  965): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  965): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  965): proximitySensorChanged  positive = true
I/KnockOnPowerController(  965): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.454315 Y: -0.387787 Z: 9.767853 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.454315 .y:-0.387787 .z:9.767853
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.449905 Y: -0.396622 Z: 9.750031 
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.447678 Y: -0.403290 Z: 9.790009 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.449905 .y:-0.396622 .z:9.750031
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
D/WifiController(  965): battery changed pluggedType: 2
V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.464249 Y: -0.388046 Z: 9.744385 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.464249 .y:-0.388046 .z:9.744385
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiController(  965): battery changed pluggedType: 2
D/HeadsetStateMachine( 1226): Disconnected process message: 10
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.463837 Y: -0.387650 Z: 9.757462 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.463837 .y:-0.387650 .z:9.757462
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  965): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@44d08bd8)
,D/KeyguardViewMediator( 1143): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 1143): notifyScreenOnLocked
,D/KeyguardViewMediator( 1143): handleNotifyScreenOn
,D/KeyguardViewManager( 1143): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  965): **** SHOWN CALLED ****
I/WindowManager(  965): No lock screen! windowToken=null
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
,D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb8cf7450
,D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
,E/SlideAside( 3574): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.465729 Y: -0.401199 Z: 9.755508 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.465729 .y:-0.401199 .z:9.755508
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
,D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=4
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WifiStateMachine(  965): handleScreenStateChanged: true
D/WifiStateMachine(  965): handleMessage: E msg.what=131154
D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiNative-wlan0(  965): doString: SIGNAL_POLL
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4265): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiServiceExtension(  965): sendKtScanInterval  mRtspPlay : false
,D/wpa_supplicant( 4265): nl80211: survey data missing!
,D/WifiStateMachine(  965): handleMessage: X
,D/WifiStateMachine(  965): handleMessage: E msg.what=131127
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131158
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
,D/WifiStateMachine(  965): processMsg: DriverStartedState
,D/WifiStateMachine(  965): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=132097
,D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): processMsg: DriverStartedStateExt
,I/WifiServiceExtension(  965): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 4265): wlan0: Control interface command 'KT_SCAN_INTERVAL'
,D/wpa_supplicant( 4265): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  965): handleMessage: X
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/WifiOffDelayIfNotUsed(  965): stopMonitoring
,E/AudioSystem(  965): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=on, calling pid 965
V/SRS_Proc(  271): ParamSet string: screen_state=on
D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=on
,V/voice   (  271): voice_set_parameters: enter: screen_state=on
V/voice   (  271): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
,D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1157): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{43368e80 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1157): enqueuing start. mLedList.size()=2
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1157): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1157): enqueuing end. mLedList.size()=3
,E/CliptrayService( 1157): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1823): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 18:48:51
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/SlideAside( 3574): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
D/UpdateThreadPoolManager( 1823): 2 : This is isUpdating : false
,D/WeatherAncestor( 1823): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 18:48:51
,D/WeatherService( 1823): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1823): 2 : shouldTimeTickRegistered : false
D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
,D/WeatherService( 1823): 2 : shouldTimeTickRegistered : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.450912 Y: -0.396149 Z: 9.769852 
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.450912 .y:-0.396149 .z:9.769852
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1157): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1157): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1157): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1157): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 225, B = 225
,V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  965): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  965): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  965): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  965): hal_process_report_ind: X: -0.444046 Y: -0.398315 Z: 9.759171 
,D/qcom_sensors_hal(  965): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.444046 .y:-0.398315 .z:9.759171
D/qcom_sensors_hal(  965): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=0
D/qdlights( 1157): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1157): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1157): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 207, B = 207
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  965): Excessive delay in blankDisplay() while turning screen off: 419ms
D/qdlights( 1157): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1157): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 195, B = 195
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GlobalAccess( 1143): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1143): changeTargets() succeeded. size: 20
D/qdlights( 1157): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 189, B = 189
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450201731995, nextTick: 8037, mDrawingTime: 0
,D/qdlights( 1157): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1157): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 177, B = 177
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450201732016, nextTick: 8016, mDrawingTime: 0
,D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=4
D/qdlights( 1157): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 171, B = 171
,D/WeatherService( 1823): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 18:48:52
,D/WeatherService( 1823): 2 : ACTION screen on
,D/WeatherService( 1823): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1823): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 18:48:52
D/qdlights( 1157): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 165, B = 165
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
E/Parcel  (  411): Reading a NULL string not supported here.
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
E/Parcel  (  411): Reading a NULL string not supported here.
E/Parcel  (  411): Reading a NULL string not supported here.
,E/Parcel  (  411): Reading a NULL string not supported here.
D/GsmSST  ( 1451): Emergency Service
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1451): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1451): [PhoneIntfMgr] sigLevel = 5
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/PhoneApp( 1451): Action intent recieved:android.intent.action.SCREEN_ON
D/qdlights( 1157): set_light_notifications: 2,ff009f9f,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 159, B = 159
,V/TelephonyAutoProfiling( 1451): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1451): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : support_assisted_dialing, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : vzw_gfit, value : null
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  965): ACTION_SCREEN_ON
,D/qdlights( 1157): set_light_notifications: 2,ff009999,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 153, B = 153
I/qcom_sensors_hal(  965): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  965): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  965): _hal_sensors_activate: handle=0, Initialized the timestamp 
D/qcom_sensors_hal(  965): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,D/KeyguardViewMediator( 1143): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1143): notifyScreenOffLocked
D/qcom_sensors_hal(  965): hal_acquire_resources
D/qcom_sensors_hal(  965): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  965): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  965): hal_wait_for_response: timeout=1000
,D/qdlights( 1157): set_light_notifications: 2,ff009393,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 147, B = 147
,D/KeyguardViewMediator( 1143): setting alarm to turn off keyguard, seq = 2, timeout = 5000
V/ActivityManager(  965): Moving to PAUSING: ActivityRecord{43a035a0 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  965): Moving to PAUSED: ActivityRecord{43a035a0 u0 com.test.thalitest/.MainActivity t3} (pause complete)
,V/ActivityManager(  965): Moving to STOPPING: ActivityRecord{43a035a0 u0 com.test.thalitest/.MainActivity t3} (stop requested)
V/qcom_sensors_hal(  965): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  965): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  965): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
D/KeyguardViewMediator( 1143): handleNotifyScreenOff
D/KeyguardViewManager( 1143): onScreenTurnedOff()
,D/qcom_sensors_hal(  965): hal_smgr_report_delete: Rcvd success response from request
D/qdlights( 1157): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 141, B = 141
,I/LGImmersionVibrator(  965): Vibrator off
,D/WifiStateMachine(  965): handleScreenStateChanged: false
D/WifiStateMachine(  965): handleMessage: E msg.what=131154
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): handleMessage: X
D/WifiStateMachine(  965): handleMessage: E msg.what=131158
D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
D/WifiStateMachine(  965): processMsg: ConnectModeState
V/ActivityManager(  965): Moving to DESTROYING: ActivityRecord{42cb44a0 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,V/ActivityManager(  965): Moving to STOPPED: ActivityRecord{43a035a0 u0 com.test.thalitest/.MainActivity t3} (stop complete)
D/WifiStateMachine(  965): processMsg: DriverStartedState
D/WifiStateMachine(  965): setSuspendOptimizationsNative: 4 true
D/WifiNative-wlan0(  965): doBoolean: DRIVER SETSUSPENDMODE 1
,D/UsbSettings( 2558): [AUTORUN] onDestroy() : getDefaultFunction =boot
D/wpa_supplicant( 4265): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
,D/wpa_supplicant( 4265): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
,V/UsbSettings( 2558): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2558): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2558): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
,E/AudioSystem(  965): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=off, calling pid 965
V/SRS_Proc(  271): ParamSet string: screen_state=off
D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
D/qdlights( 1157): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 135, B = 135
D/WifiController(  965): CMD_SCREEN_OFF 
D/WifiController(  965): shouldWifiStayAwake TRUE
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/VolumeVibrator( 1157): clear
,V/ActivityManager(  965): Moving to DESTROYED: ActivityRecord{42cb44a0 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327ac48 stackId=1, 1 tasks}
,E/CliptrayService( 1157): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/qdlights( 1157): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 129, B = 129
,D/wpa_supplicant( 4265): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  965):    returned true
,D/WifiStateMachine(  965): handleMessage: X
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
D/NativeNfcBrcmPowerMode( 1475): setPowerMode; state=2
I/[LGHome]EVENT( 1489): [Launcher.java:1567:onReceive()]Screen Off
D/qdlights( 1157): set_light_notifications: 2,ff007b7b,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 123, B = 123
,V/TelephonyAutoProfiling(  965): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
E/Parcel  (  411): Reading a NULL string not supported here.
E/Parcel  (  411): Reading a NULL string not supported here.
E/Parcel  (  411): Reading a NULL string not supported here.
,E/Parcel  (  411): Reading a NULL string not supported here.
D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/qdlights( 1157): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 117, B = 117
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1451): [PhoneIntfMgr] sigLevel = 5
D/WeatherService( 1823): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 18:48:52
,D/WeatherService( 1823): 2 : ACTION screen off
D/WeatherService( 1823): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 18:48:52
D/GsmSST  ( 1451): Emergency Service
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1451): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1451): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1451): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : support_assisted_dialing, value : null
D/qdlights( 1157): set_light_notifications: 2,ff006f6f,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 111, B = 111
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1451): [getValue] FEATURE key : vzw_gfit, value : null
D/BrcmNfcJni( 1475): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
D/BrcmNfcJni( 1475): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
V/PhoneApp( 1451): Action intent recieved:android.intent.action.SCREEN_OFF
D/NfcService( 1475): NFC-C OFF
D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
D/qdlights( 1157): set_light_notifications: 2,ff006969,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 105, B = 105
D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1464): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  965): ACTION_SCREEN_OFF
,D/qdlights( 1157): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 99, B = 99
,D/qdlights( 1157): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 93, B = 93
,D/qdlights( 1157): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 87, B = 87
,D/qdlights( 1157): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 81, B = 81
,D/qdlights( 1157): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 75, B = 75
,D/qdlights( 1157): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 69, B = 69
,D/qdlights( 1157): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 63, B = 63
,D/qdlights( 1157): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 57, B = 57
,D/qdlights( 1157): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 51, B = 51
,D/qdlights( 1157): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1157): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1157): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1157): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1157): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1157): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1157): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1157): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  390): sns_pwr.c(320):releasing wakelock
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
,D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): handleMessage: X
,E/ThermalEngine(  287): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  965): handleMessage: E msg.what=131155
,D/WifiStateMachine(  965): processMsg: ConnectedState
D/WifiStateMachine(  965): processMsg: L2ConnectedState
,D/WifiStateMachine(  965): handleMessage: X
,D/KeyguardViewMediator( 1143): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1451): getIsInUseVoLTE : false
,D/PhoneApp( 1451): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1143): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
,D/KeyguardViewMediator( 1143): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1143): doKeyguard is called, but is not locked.
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450201740053, nextTick: 59978, mDrawingTime: 0
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450201740055, nextTick: 59974, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450201750069532226; DSPS: 5272951; Offset: 1450201589151838135
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/WifiController(  965): battery changed pluggedType: 2
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450201770071127270; DSPS: 5928363; Offset: 1450201589151846265
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450201790072962159; DSPS: 6583783; Offset: 1450201589151850099
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450201800051, nextTick: 59979, mDrawingTime: 1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450201800054, nextTick: 59976, mDrawingTime: 1
,I/rmt_storage(  422): rmt_storage_connect_cb: clnt_h=0x7 conn_h=0xb8d55178
I/rmt_storage(  422): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xb msg_id=3: R/W request received
,I/rmt_storage(  422): wakelock acquired: 1, error no: 42
,I/rmt_storage(  422): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1193979336)
,I/rmt_storage(  422): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xb msg_id=3: Bytes written = 1572864
I/rmt_storage(  422): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xb msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  422): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1193979336) wakelock released: 1, error no: 0
I/rmt_storage(  422): 
I/rmt_storage(  422): rmt_storage_disconnect_cb: clnt_h=0x0x7 conn_h=0x0xb8d55178
,E/Diag_Lib(  700): [IMS_FATAL]| 2912 | 705 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450201810076691683; DSPS: 7239266; Offset: 1450201589151825961
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450201830078363445; DSPS: 7894680; Offset: 1450201589151849774
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  965): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450201850080028751; DSPS: 8550095; Offset: 1450201589151836613
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450201860048, nextTick: 59982, mDrawingTime: 1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450201860051, nextTick: 59973, mDrawingTime: 3
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450201870083655617; DSPS: 9205574; Offset: 1450201589151831887
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450201890085528787; DSPS: 9860995; Offset: 1450201589151843485
,D/wpa_supplicant( 4265): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4265): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4265): wlan0: BSS: Remove id 1 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4265): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4265): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4265): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4265): wlan0: BSS: Remove id 4 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4265): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4265): wlan0: BSS: Remove id 5 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4265): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4265): wlan0: BSS: Remove id 6 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4265): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4265): wlan0: BSS: Remove id 7 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 4265): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 a0:c5:62:7a:49:97]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 9e:93:4e:3e:ba:c5]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 06:7c:34:12:7f:81]
,D/WifiMonitor(  965): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 64:7c:34:12:7f:81]
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450201910087382634; DSPS: 10516416; Offset: 1450201589151835759
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 2616): GC_CONCURRENT freed 7842K, 33% free 16801K/24832K, paused 2ms+2ms, total 37ms
,D/dalvikvm( 2616): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  965): Killing 4603:com.android.chrome/u0a63 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327ac48 stackId=1, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450201920050, nextTick: 59970, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450201920060, nextTick: 59971, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450201930088563511; DSPS: 11171815; Offset: 1450201589151826451
,I/LocationManagerService(  965): remove 431c6ad8
,D/LocationManagerService(  965): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  965): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  965): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  965): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  965): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/dalvikvm( 2616): GC_CONCURRENT freed 1774K, 32% free 17061K/24832K, paused 3ms+2ms, total 31ms
,D/dalvikvm( 2616): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 2616): GC_CONCURRENT freed 1755K, 31% free 17273K/24832K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 2616): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/Mlt MonitorService( 2616): parseLastkmsg to dump
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450201950090203035; DSPS: 11827228; Offset: 1450201589151848543
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450201970092014694; DSPS: 12482648; Offset: 1450201589151829148
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450201980054, nextTick: 59969, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450201980060, nextTick: 59971, mDrawingTime: 1
,I/jxcore-log( 4201): Connected to the server!
I/jxcore-log( 4201): 
,I/chromium( 4201): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450201990093989374; DSPS: 13138072; Offset: 1450201589151850703
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202010095796137; DSPS: 13793492; Offset: 1450201589151826411
,D/dalvikvm( 1558): GC_EXPLICIT freed 1638K, 28% free 18004K/24832K, paused 2ms+7ms, total 54ms
,I/GLSUser ( 1558): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1558): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1558): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1558): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1558): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1558): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  965): updateLightListLocked :r=NotificationRecord(0x44d9ece0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  965): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1558): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1558): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1558): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1558): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1558): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1558): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1558): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1558): 	at dalvik.system.NativeStart.run(Native Method)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/PlayEventLogger( 4782): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4782): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4782): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4782): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4782): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4782): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4782): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4782): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 4782): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4782): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202030097671182; DSPS: 14448913; Offset: 1450201589151839884
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450202040042, nextTick: 59981, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450202040048, nextTick: 59983, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202050099864612; DSPS: 15104345; Offset: 1450201589151836048
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202070101681427; DSPS: 15759764; Offset: 1450201589151852326
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202090103517877; DSPS: 16415185; Offset: 1450201589151827204
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450202100040, nextTick: 59988, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450202100043, nextTick: 59984, mDrawingTime: 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202110105827453; DSPS: 17070621; Offset: 1450201589151817444
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202130108124425; DSPS: 17726056; Offset: 1450201589151825597
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202150109927802; DSPS: 18381475; Offset: 1450201589151828437
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450202160052, nextTick: 59972, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450202160057, nextTick: 59972, mDrawingTime: 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202170111098003; DSPS: 19036873; Offset: 1450201589151838970
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202190112724923; DSPS: 19692286; Offset: 1450201589151848459
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202210114435279; DSPS: 20347702; Offset: 1450201589151849830
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450202220047, nextTick: 59966, mDrawingTime: 8
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450202220060, nextTick: 59971, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202230115709699; DSPS: 21003104; Offset: 1450201589151842512
,I/jxcore-log( 4201): --- start :testFindPeers.js---
I/jxcore-log( 4201): 
,I/jxcore-log( 4201): testFindPeers created [object Object]
I/jxcore-log( 4201): 
,I/jxcore-log( 4201): serverPort is 8876
I/jxcore-log( 4201): 
,I/dalvikvm( 4201): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 4201): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4201): VFY: replacing opcode 0x6e at 0x0019
,I/dalvikvm( 4201): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 4201): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4201): VFY: replacing opcode 0x6e at 0x0020
,D/AndroidRuntime( 4201): Shutting down VM
,W/dalvikvm( 4201): threadid=1: thread exiting with uncaught exception (group=0x4182ae48)
E/AndroidRuntime( 4201): FATAL EXCEPTION: main
E/AndroidRuntime( 4201): Process: com.test.thalitest, PID: 4201
E/AndroidRuntime( 4201): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 4201): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:134)
E/AndroidRuntime( 4201): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:133)
E/AndroidRuntime( 4201): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:183)
E/AndroidRuntime( 4201): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:95)
E/AndroidRuntime( 4201): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:92)
E/AndroidRuntime( 4201): 	at io.jxcore.node.JXcoreExtension$5.Receiver(JXcoreExtension.java:155)
E/AndroidRuntime( 4201): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 4201): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 4201): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 4201): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4201): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4201): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4201): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
E/AndroidRuntime( 4201): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4201): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4201): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
E/AndroidRuntime( 4201): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
E/AndroidRuntime( 4201): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager(  965):   Force finishing activity com.test.thalitest/.MainActivity
,V/ActivityManager(  965): Moving to FINISHING: ActivityRecord{43a035a0 u0 com.test.thalitest/.MainActivity t3 f}
,I/ActivityManager(  965): Killing 4648:com.lge.drmservice/u0a66 (adj 15): empty #17
,V/ActivityManager(  965): Moving to DESTROYING: ActivityRecord{43a035a0 u0 com.test.thalitest/.MainActivity t3 f} (destroy requested),
,I/Process ( 4201): Sending signal. PID: 4201 SIG: 9
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{4327ac48 stackId=1, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: No more activities go home
,V/ActivityManager(  965): moveHomeStack:
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c64b10 stackId=0, 1 tasks}
,V/ActivityManager(  965): Moving to RESUMED: ActivityRecord{43075158 u0 com.lge.launcher2/.Launcher t1} (in existing)
,V/ActivityManager(  965): Moving to PAUSING: ActivityRecord{43075158 u0 com.lge.launcher2/.Launcher t1}
,D/ActivityManager(  965): resumeTopActivityLocked: Resumed ActivityRecord{43075158 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  965): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42c64b10 stackId=0, 1 tasks}
D/ActivityManager(  965): allPausedActivitiesComplete: r=ActivityRecord{43075158 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  965): allPausedActivitiesComplete: r=ActivityRecord{43075158 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
,V/ActivityManager(  965): resumeTopActivityLocked: Skip resume: some activity pausing.
,I/[LGHome]EVENT( 1489): [Launcher.java:4947:onStart()]onStart
,I/[LGHome]EVENT( 1489): [Launcher.java:717:onResume()]onResume
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,D/PhoneApp( 1451): getIsInUseVoLTE : false
,I/[LGHome]LGActivityUtil( 1489): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1489): [Launcher.java:868:onResume()]onResume end
,I/[LGHome]EVENT( 1489): [Launcher.java:894:onPause()]onPause
V/ActivityManager(  965): Moving to PAUSED: ActivityRecord{43075158 u0 com.lge.launcher2/.Launcher t1} (pause complete)
V/ActivityManager(  965): Moving to STOPPING: ActivityRecord{43075158 u0 com.lge.launcher2/.Launcher t1} (stop requested)
,D/WeatherAncestor( 1823): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 18:57:23
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/UpdateThreadPoolManager( 1823): 2 : This is isUpdating : false
,I/[LGHome]EVENT( 1489): [Launcher.java:4955:onStop()]onStop
D/WeatherService( 1823): 2 : shouldTimeTickRegistered : false
D/WeatherAncestor( 1823): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 18:57:23
D/WeatherService( 1823): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
,D/WeatherService( 1823): 2 : shouldTimeTickRegistered : false
,I/ActivityManager(  965): Process com.test.thalitest (pid 4201) has died.
,I/WindowState(  965): WIN DEATH: Window{439b6e08 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  965): Client connection lost with reason: 4
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/ActivityManager(  965): Moving to DESTROYED: ActivityRecord{43a035a0 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
V/ActivityManager(  965): Moving to DESTROYED: ActivityRecord{43a035a0 u0 com.test.thalitest/.MainActivity t3 f} (cleaning up)
I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c64b10 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/[LGHome]EVENT( 1489): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
V/ActivityManager(  965): Moving to STOPPED: ActivityRecord{43075158 u0 com.lge.launcher2/.Launcher t1} (stop complete)
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,W/Binder  ( 1297): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1297): java.lang.NullPointerException
W/Binder  ( 1297): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1297): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1297): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1297): 	at dalvik.system.NativeStart.run(Native Method)
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/InputMethodManagerService(  965): IME STATUS OFF
W/InputMethodManagerService(  965): Got RemoteException sending setActive(false) notification to pid 4201 uid 10304
,I/ActivityManager(  965): Timeline: Activity_windows_visible id: ActivityRecord{43075158 u0 com.lge.launcher2/.Launcher t1} time:649817
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
D/dalvikvm( 1143): GC_CONCURRENT freed 9445K, 13% free 68725K/78356K, paused 7ms+9ms, total 70ms
,D/dalvikvm( 1143): WAIT_FOR_CONCURRENT_GC blocked 64ms
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,D/dalvikvm( 1489): GC_CONCURRENT freed 5674K, 9% free 60774K/66632K, paused 2ms+4ms, total 29ms
,D/dalvikvm( 1489): WAIT_FOR_CONCURRENT_GC blocked 27ms
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/ActivityManager(  965): Start proc com.lge.email for content provider com.lge.email/.providers.LGEmailContentProvider: pid=5685 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,D/HyLog   ( 5685): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5685): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5685): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/LGEmail ( 5685): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
,D/LGEmail ( 5685): EmailContentProvider.query: uri=content://com.lge.providers.lgemail/account, projection=[accountID, userName, mailAddress, accountName, InboxID], selection=null, selectionArgs=null sortOrder=null, TABLE_NAMES=EAccountmatch is 0 (at LGEmailContentProvider.java query 492)[v:null]
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
E/LGEmail ( 5685): Email Not Started (at LGEmailContentProvider.java query 509)[v:null]
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,E/[LGHome]NumberBadge( 1489): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,I/ActivityManager( 1489): Timeline: Activity_idle id: android.os.BinderProxy@42867eb8 time:650067
,D/LGEmail ( 5685): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/BaseRuntimeLoader( 5685): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5685): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5685): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5685): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1489): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,E/[LGHome]NumberBadge( 1489): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202250124796781; DSPS: 21658762; Offset: 1450201589151835356
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202270126769068; DSPS: 22314187; Offset: 1450201589151824000
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450202280045, nextTick: 59980, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450202280048, nextTick: 59983, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202290136971224; DSPS: 22969881; Offset: 1450201589151833285
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202310137414865; DSPS: 23625255; Offset: 1450201589151849680
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  965): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1464): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1464): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1464): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1464): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1226): Disconnected process message: 10
,W/Settings(  965): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  965): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202330138781446; DSPS: 24280660; Offset: 1450201589151842970
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450202340047, nextTick: 59967, mDrawingTime: 8
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450202340058, nextTick: 59973, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202350139685522; DSPS: 24936050; Offset: 1450201589151831519
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202370140138253; DSPS: 25591425; Offset: 1450201589151826486
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202390141006412; DSPS: 26246813; Offset: 1450201589151840153
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450202400052, nextTick: 59974, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450202400054, nextTick: 59976, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202410146881369; DSPS: 26902366; Offset: 1450201589151825217
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202430147339982; DSPS: 27557740; Offset: 1450201589151856584
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  965): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  965): Done.
,D/QcConnectivityService(  965): Setting timer for 720seconds
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202450148222449; DSPS: 28213130; Offset: 1450201589151823524
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450202460036, nextTick: 59990, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450202460039, nextTick: 59992, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202470149130934; DSPS: 28868520; Offset: 1450201589151816481
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202490149577034; DSPS: 29523894; Offset: 1450201589151835335
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202510150506342; DSPS: 30179284; Offset: 1450201589151849116
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450202520040, nextTick: 59988, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450202520043, nextTick: 59988, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202530151427299; DSPS: 30834675; Offset: 1450201589151824028
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202550151864348; DSPS: 31490049; Offset: 1450201589151833831
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202570152753420; DSPS: 32145438; Offset: 1450201589151837893
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450202580041, nextTick: 59979, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450202580050, nextTick: 59981, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202590157219359; DSPS: 32800945; Offset: 1450201589151817748
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202610157650145; DSPS: 33456319; Offset: 1450201589151821288
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202630158092659; DSPS: 34111693; Offset: 1450201589151836556
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450202640028, nextTick: 60000, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450202640051, nextTick: 59980, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202650161245553; DSPS: 34767156; Offset: 1450201589151846139
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202670162114208; DSPS: 35422545; Offset: 1450201589151829785
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202690162990407; DSPS: 36077933; Offset: 1450201589151851491
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450202700038, nextTick: 59991, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450202700041, nextTick: 59990, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202710164175616; DSPS: 36733332; Offset: 1450201589151846515
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202730164616419; DSPS: 37388707; Offset: 1450201589151829554
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202750165487369; DSPS: 38044095; Offset: 1450201589151846012
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450202760038, nextTick: 59991, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450202760041, nextTick: 59990, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202770167047197; DSPS: 38699506; Offset: 1450201589151849444
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202790167505987; DSPS: 39354882; Offset: 1450201589151819952
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202810167957168; DSPS: 40010256; Offset: 1450201589151843887
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450202820038, nextTick: 59991, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450202820041, nextTick: 59990, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202830170241870; DSPS: 40665691; Offset: 1450201589151839771
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202850170694588; DSPS: 41321066; Offset: 1450201589151834725
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202870171583679; DSPS: 41976455; Offset: 1450201589151838806
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450202880037, nextTick: 59989, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450202880042, nextTick: 59989, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202890173545934; DSPS: 42631879; Offset: 1450201589151847936
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202910173976045; DSPS: 43287254; Offset: 1450201589151820284
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202930174435327; DSPS: 43942628; Offset: 1450201589151852320
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450202940038, nextTick: 59988, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450202940059, nextTick: 59972, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202950175791692; DSPS: 44598033; Offset: 1450201589151835394
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202970178070667; DSPS: 45253468; Offset: 1450201589151825550
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450202990178501305; DSPS: 45908842; Offset: 1450201589151828942
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450203000031, nextTick: 59987, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450203000040, nextTick: 59991, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450203010182290168; DSPS: 46564326; Offset: 1450201589151833626
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450203030182728464; DSPS: 47219700; Offset: 1450201589151844675
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450203050183611975; DSPS: 47875089; Offset: 1450201589151843177
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450203060036, nextTick: 59981, mDrawingTime: 7
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450203060046, nextTick: 59985, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450203070184515701; DSPS: 48530479; Offset: 1450201589151831375
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450203090184944393; DSPS: 49185853; Offset: 1450201589151832821
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450203110185803324; DSPS: 49841241; Offset: 1450201589151837260
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450203120032, nextTick: 59984, mDrawingTime: 8
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450203120055, nextTick: 59973, mDrawingTime: 2
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450203130186775127; DSPS: 50496633; Offset: 1450201589151832501
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450203150187203279; DSPS: 51152007; Offset: 1450201589151833406
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=115
D/QcConnectivityService(  965): Sampling interval elapsed, updating statistics ..
,D/QcConnectivityService(  965): Done.
,D/QcConnectivityService(  965): Setting timer for 720seconds
,D/GCM     ( 1558): Message class com.google.f.a.a.i
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  965): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  965): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450203170188089667; DSPS: 51807396; Offset: 1450201589151834785
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450203180037, nextTick: 59989, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450203180040, nextTick: 59991, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450203190189007555; DSPS: 52462786; Offset: 1450201589151837145
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450203210189909096; DSPS: 53118175; Offset: 1450201589151853677
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450203230190754136; DSPS: 53773563; Offset: 1450201589151844224
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450203240037, nextTick: 59991, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450203240039, nextTick: 59992, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450203250191668307; DSPS: 54428953; Offset: 1450201589151842868
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450203270192104580; DSPS: 55084328; Offset: 1450201589151821377
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450203290192979516; DSPS: 55739716; Offset: 1450201589151841821
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450203300038, nextTick: 59991, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450203300041, nextTick: 59990, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450203310193889475; DSPS: 56395106; Offset: 1450201589151836253
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450203330194325778; DSPS: 57050480; Offset: 1450201589151845310
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450203350195245774; DSPS: 57705870; Offset: 1450201589151849778
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450203360035, nextTick: 59987, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450203360043, nextTick: 59988, mDrawingTime: 1
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450203370196762099; DSPS: 58361280; Offset: 1450201589151840224
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450203390197198808; DSPS: 59016654; Offset: 1450201589151849687
,D/dalvikvm(  965): GC_CONCURRENT freed 3134K, 48% free 29895K/56852K, paused 5ms+12ms, total 158ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450203410198628912; DSPS: 59672061; Offset: 1450201589151845465
,I/ProcessStatsService(  965): Prepared write state in 21ms
,I/ProcessStatsService(  965): Prepared write state in 26ms
,D/LocationManagerService(  965): getAllProviders()=[passive, gps, network]
,I/ProcessStatsService(  965): Pruning old procstats: /data/system/procstats/state-2015-12-15-05-01-45.bin
,I/ActivityManager(  965): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadProvider: pid=6797 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/GLSUser ( 1558): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1558): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1558): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1558): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1558): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1892): Aggregate from 1450201714046 (log), 1450201617274 (data)
D/HyLog   ( 6797): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6797): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 6797): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Auth    ( 1558): [DefaultAuthDelegateService] Use browser flow? false
D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450203420029, nextTick: 60002, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450203420048, nextTick: 59985, mDrawingTime: 0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/DownloadManager( 6797): DownloadService onCreate
,I/DownloadManager( 6797): in removeSpuriousFiles
V/DownloadManager( 6797): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 6797): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 6797): DownloadService onStartCommand
,V/DownloadManager( 6797): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 6797): created cursor android.database.sqlite.SQLiteCursor@428ad6e8 on behalf of 1892
,V/DownloadManager( 6797): created cursor android.database.sqlite.SQLiteCursor@428ae188 on behalf of 6797
,V/DownloadManager( 6797): created cursor android.database.sqlite.SQLiteCursor@428affe0 on behalf of 6797
,I/DownloadManager( 6797): in trimDatabase
,V/DownloadManager( 6797): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 6797): created cursor android.database.sqlite.SQLiteCursor@428b2058 on behalf of 6797
,V/DownloadManager( 6797): DownloadService onDestroy
,V/DownloadManager( 6797): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 6797): created cursor android.database.sqlite.SQLiteCursor@428b7948 on behalf of 1892
,V/DownloadManager( 6797): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 6797): created cursor android.database.sqlite.SQLiteCursor@428bb090 on behalf of 1892
,I/ActivityManager(  965): Killing 4347:com.lge.lgdmsgcm/1000 (adj 15): empty #17
,I/ActivityManager(  965): resumeTopActivitiesLocked(): target Stack:ActivityStack{42c64b10 stackId=0, 1 tasks}
,D/ActivityManager(  965): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450203430199019498; DSPS: 60327434; Offset: 1450201589151839323
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450203450199467970; DSPS: 60982809; Offset: 1450201589151830031
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450203470199903756; DSPS: 61638183; Offset: 1450201589151838571
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450203480040, nextTick: 59989, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1450203480043, nextTick: 59989, mDrawingTime: 0
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450203490207042875; DSPS: 62293777; Offset: 1450201589151836577
,D/qcom_sensors_hal(  965): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  965): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  965): hal_ts_offset_is: Apps: 1450203510207469637; DSPS: 62949151; Offset: 1450201589151836093
,TIME-OUT KILL (timeout was 1800000ms)
```
