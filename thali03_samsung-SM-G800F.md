#### Test 5065027865f659b_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system,
D/AmoledAdjustTimer( 2381): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
--------- beginning of /dev/log/main
D/AndroidRuntime( 7039): 
D/AndroidRuntime( 7039): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7039): CheckJNI is OFF
D/AndroidRuntime( 7039): setted country_code = Poland
D/AndroidRuntime( 7039): setted countryiso_code = PL
D/AndroidRuntime( 7039): setted sales_code = PLS
D/AndroidRuntime( 7039): readGMSProperty: start
D/AndroidRuntime( 7039): readGMSProperty: already setted!!
D/AndroidRuntime( 7039): readGMSProperty: end
D/AndroidRuntime( 7039): addProductProperty: start
D/dalvikvm( 7039): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7039): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7039): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7039): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7039): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7039): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7039): failed to load memtrack module: -2
D/dalvikvm( 7039): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7039): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2381): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2381): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2381  pkgName : ACTIVITY_RESUME_BOOSTER@4
I/SurfaceFlinger( 1920): id=18 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger( 1920): id=19 createSurf (16x16),-1 flag=20004, EimLayer
W/ActivityManager( 2381): mDVFSHelper.acquire()
I/SELinux ( 7066): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7066):  
D/PointerIcon( 2381): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2381): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2381): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2381): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7039): Shutting down VM
D/dalvikvm( 7039): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+0ms, total 4ms
I/SELinux ( 7066): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7066):  
I/SELinux ( 7066):  
I/SELinux ( 7066): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7066): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7066): >>>>> Normal User
E/dalvikvm( 7066): >>>>> com.test.thalitest [ userId:0 | appId:10518 ]
E/SELinux ( 7066): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7066): in addTimaSignatureService
D/TimaKeyStoreProvider( 7066): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7066): Added TimaKesytore provider
V/WindowManager( 2381): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
I/SQLiteSecureOpenHelper( 4161): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4161): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1920): id=9 Removed Mauncher (8/10)
I/SurfaceFlinger( 1920): id=9 Removed Mauncher (-2/10)
D/Launcher( 2765): onTrimMemory. Level: 20
D/dalvikvm( 7066): GC_CONCURRENT freed 3005K, 29% free 9558K/13288K, paused 2ms+1ms, total 19ms
D/dalvikvm( 7066): WAIT_FOR_CONCURRENT_GC blocked 17ms
V/WebViewChromium( 7066): Binding Chromium to the background looper Looper (main, tid 1) {422051e0}
I/chromium( 7066): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7066): Initializing chromium process, renderers=0
W/chromium( 7066): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7066): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7066): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7066): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7066): Mali API Version : 401
,I/Mali    ( 7066): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7066): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 7066): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7066): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7066): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7066): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7066): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2580): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/StatusBarManagerService( 2381): tr p:7066,o:f
W/dalvikvm( 7066): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7066): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7066): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7066): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 7066): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 7066): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7066): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7066): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 7066): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7066): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7066): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 7066): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 7066): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2580): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2381): semi p:7066,o:f
,D/dalvikvm( 2381): GC_EXPLICIT freed 27453K, 71% free 25182K/86576K, paused 7ms+19ms, total 248ms
,I/SurfaceFlinger( 1920): id=20 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2381): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/STATUSBAR-StatusBarManagerService( 2381): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2381): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2381): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2381): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2381): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7066): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7066): Enabling debug mode 0
,W/ContextImpl( 2381): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/IInputConnectionWrapper( 7066): showStatusIcon on inactive InputConnection
D/CustomFrequencyManagerService( 2381): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2381  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2381): mDVFSHelper.release()
D/CustomFrequencyManagerService( 2381): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2381  pkgName : ACTIVITY_RESUME_BOOSTER@8
,W/ContextImpl( 2381): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/JsMessageQueue( 7066): Set native->JS mode to OnlineEventsBridgeMode,
,D/dalvikvm( 7066): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42205f68,
,D/dalvikvm( 7066): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42205f68,
D/jxcore_app_log( 7066): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2027490232
,D/JX-Cordova( 7066): jxcore cordova android initializing,
I/dalvikvm( 7066): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 7066): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 7066): VFY: replacing opcode 0x6e at 0x0045
,D/dalvikvm( 7066): GC_CONCURRENT freed 1288K, 16% free 11342K/13348K, paused 1ms+2ms, total 22ms,
,D/dalvikvm( 7066): WAIT_FOR_CONCURRENT_GC blocked 12ms,
,D/dalvikvm( 7066): GC_CONCURRENT freed 1930K, 16% free 14924K/17592K, paused 1ms+2ms, total 40ms,
,D/dalvikvm( 7066): WAIT_FOR_CONCURRENT_GC blocked 20ms,
,D/CustomFrequencyManagerService( 2381): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2381  tag : ACTIVITY_RESUME_BOOSTER@8,
,D/dalvikvm( 7066): GC_FOR_ALLOC freed 5292K, 28% free 16199K/22480K, paused 51ms, total 51ms,
,D/dalvikvm( 7066): GC_CONCURRENT freed 6702K, 30% free 17666K/25112K, paused 1ms+9ms, total 56ms
,D/dalvikvm( 7066): WAIT_FOR_CONCURRENT_GC blocked 41ms,
,D/dalvikvm( 7066): GC_FOR_ALLOC freed 1372K, 31% free 17340K/25112K, paused 52ms, total 52ms,
,I/dalvikvm-heap( 7066): Grow heap (frag case) to 21.151MB for 3688532-byte allocation,
,D/dalvikvm( 7066): GC_FOR_ALLOC freed 2409K, 36% free 18532K/28716K, paused 41ms, total 41ms
,W/jxcore-log( 7066): Initializing JXcore engine,
,W/jxcore-log( 7066): JXcore engine is ready,
,W/jxcore-log( 7066): Starting JXcore engine,
,W/jxcore-log( 7066): Platform android
W/jxcore-log( 7066): 
,W/jxcore-log( 7066): Process ARCH arm
W/jxcore-log( 7066): 
,V/AlarmManager( 2381): waitForAlarm result :8
,V/AlarmManager( 2381): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/jxcore-log( 7066): JXcore Cordova bridge is ready!
I/jxcore-log( 7066): 
,W/jxcore-log( 7066): JXcore engine is started
,I/chromium( 7066): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,E/jxcore  ( 7066): Error!: missing ) after argument list,
E/jxcore  ( 7066): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 7066): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37),
,D/PointerIcon( 2381): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
D/PointerIcon( 2381): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2381): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2381): setHoveringSpenCustomIcon IconType is same.1,
I/ActivityManager( 2381): Killing 6153:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,W/PluginManager( 7066): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 22ms. Plugin should use CordovaInterface.getThreadPool().,
,I/SurfaceFlinger( 1920): id=20 Removed NainActivit (8/10),
,I/SurfaceFlinger( 1920): id=20 Removed NainActivit (-2/10)
,I/SurfaceFlinger( 1920): id=19 Removed EimLayer (6/9)
I/SurfaceFlinger( 1920): id=19 Removed EimLayer (-2/9)
I/SurfaceFlinger( 1920): id=18 Removed EimLayer (5/8)
,I/SurfaceFlinger( 1920): id=18 Removed EimLayer (-2/8),
,V/WindowManager( 2381): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false,
,D/Launcher( 2765): onRestart, Launcher: 1109627408
D/Launcher( 2765): onStart, Launcher: 1109627408
,D/Launcher.HomeView( 2765): onStart
,I/SurfaceFlinger( 1920): id=21 createSurf (720x1280),1 flag=4, Mauncher
,D/STATUSBAR-StatusBarManagerService( 2381): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2381): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2381): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2381): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2381): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2381): setHoveringSpenCustomIcon IconType is same.1
,D/PhoneStatusBar( 2580): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/PhoneStatusBar( 2580): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2381): tr p:2765,o:f
D/StatusBarManagerService( 2381): semi p:2765,o:f
,W/ContextImpl( 2381): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/IInputConnectionWrapper( 7066): showStatusIcon on inactive InputConnection
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 330, Delta = 10,
,D/AmoledAdjustTimer( 2381): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,D/PackageManager( 2381): [MSG] WRITE_PACKAGE_RESTRICTIONS,
,D/BatteryService( 2381): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2381): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2381): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate,
D/BatteryService( 2381): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4001): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 320, Delta = -10,
,D/AmoledAdjustTimer( 2381): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4,
,W/ContextImpl( 2381): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 2381): !@Sync 9,
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2381): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2381): [PWL] Off : 225s ago,
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2381): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,W/ContextImpl( 2381): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2381): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,D/TimaService( 2381): TIMA: TimaService scheduler is intialized. ,
,D/TimaService( 2381): TimaServiceHandler.handleMessage what =1
,D/TimaService( 2381): TIMA: checkEvent, operation: 50000 subject: 10000,
,I/TLC_TIMA_PKM_initialize( 2381): initializing...,
I/TLC_TIMA_PKM_initialize( 2381): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2381): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2381): input max_sendmsg_size = 262196,
I/TZ: mc_tlc_communication( 2381): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 2381): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2381): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2381): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2381): aligned max_recvmsg_size = 262208
,I/TZ: mc_tlc_communication( 2381): device_id = 0x0
I/TZ: mc_tlc_communication( 2381): tlc_open() was called
,I/TZ: mc_tlc_communication( 2381): Opening MobiCore device
,I/TZ: mc_tlc_communication( 2381): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 2381): Opening the session
,I/TZ: mc_tlc_communication( 2381): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 2381): Trustlet response is completed,
,D/BatteryService( 2381): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2381): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2381): stay LED for fully charged
,D/UiModeManager( 2381): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2381): !@Sync 10,
,I/TLC_TIMA_PKM_measure_kernel( 2381): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2381): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;,
,D/TimaService( 2381): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/TimaService( 2381): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2381): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4,
,W/ContextImpl( 2381): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2381): waitForAlarm result :8,
,V/AlarmManager( 2381): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2381): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2381): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4,
,W/ContextImpl( 2381): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2381): [PWL] Off : 275s ago,
,E/Watchdog( 2381): !@Sync 11,
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2381): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4,
,V/AlarmManager( 2381): waitForAlarm result :4,
,V/AlarmManager( 2381): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 7377): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7377):  
,I/SELinux ( 7377): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7377):  
I/SELinux ( 7377):  
,I/SELinux ( 7377): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7377): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7377): >>>>> Normal User
,E/dalvikvm( 7377): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
,E/SELinux ( 7377): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 7377): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7377): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7377): Added TimaKesytore provider
,D/dalvikvm( 7377): GC_CONCURRENT freed 3009K, 29% free 9564K/13292K, paused 3ms+2ms, total 26ms
,D/dalvikvm( 7377): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/ActivityManager( 2381): Killing 6222:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,D/BatteryService( 2381): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2381): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2381): stay LED for fully charged
,D/UiModeManager( 2381): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4,
,W/ContextImpl( 2381): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 12
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,W/ContextImpl( 2381): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2381): waitForAlarm result :8
,V/AlarmManager( 2381): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2381): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2381): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2381): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2381): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,I/PowerManagerService( 2381): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2381): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2381): !@Sync 13
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2381): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2381): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2381): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2381): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2381): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 14
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,W/ContextImpl( 2381): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2381): waitForAlarm result :8
,V/AlarmManager( 2381): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,I/PowerManagerService( 2381): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,W/ContextImpl( 2381): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2381): !@Sync 15
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/BatteryService( 2381): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2381): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2381): mCoverManager.getCoverState() : true
,D/BatteryService( 2381): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2381): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 16
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2381): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2381): waitForAlarm result :8
,V/AlarmManager( 2381): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/BatteryService( 2381): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2381): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2381): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2381): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2381): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2381): [PWL] Off : 455s ago
,E/Watchdog( 2381): !@Sync 17
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2381): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 18
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2381): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2381): waitForAlarm result :8
,V/AlarmManager( 2381): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/BatteryService( 2381): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2381): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2381): mCoverManager.getCoverState() : true
,D/BatteryService( 2381): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2381): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2381): !@Sync 19
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,I/PowerManagerService( 2381): [PWL] Off : 525s ago
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2381): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2381): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/TimaService( 2381): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2381): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2381): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2381): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2381): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2381): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2381): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2381): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 320, Delta = 10
,D/AmoledAdjustTimer( 2381): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2381): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2381): waitForAlarm result :8
,V/AlarmManager( 2381): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2381): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2381): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2381): !@Sync 21
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/BatteryService( 2381): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2381): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2381): mCoverManager.getCoverState() : true
D/BatteryService( 2381): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,D/dalvikvm( 2381): GC_CONCURRENT freed 4202K, 72% free 24814K/86576K, paused 19ms+19ms, total 261ms
,I/PowerManagerService( 2381): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/GAV2    ( 5613): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5613): Thread[disconnect check,5,main]: Disconnected from service
,E/Watchdog( 2381): !@Sync 22
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2381): waitForAlarm result :8
,V/AlarmManager( 2381): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2381): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2381): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,V/AlarmManager( 2381): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 23
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 24
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2381): waitForAlarm result :8
,V/AlarmManager( 2381): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2381): [PWL] Off : 680s ago
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 25
,D/BatteryService( 2381): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2381): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2381): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2381): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 26
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2381): waitForAlarm result :8
,V/AlarmManager( 2381): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4068): GC_CONCURRENT freed 2891K, 28% free 9725K/13336K, paused 18ms+3ms, total 66ms
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2381): waitForAlarm result :4
,I/SensorManagerA( 2381): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2381): LightSensor setDelay = 200000000
,D/LightsService( 2381): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2381): LightSensor setSensorDelay = 200000000
D/Sensors ( 2381): Light sensor flush: not enabled 0
D/Sensors ( 2381): LightSensor enable = 1
D/Sensors ( 2381): LightSensor enableSensor = 1
D/SensorManager( 2381): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2381): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5523): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,I/EventLogService( 3275): Aggregate from 1449596987047 (log), 1449596987047 (data)
,D/Sensors ( 2381): LightSensor enable = 0
,D/Sensors ( 2381): LightSensor enableSensor = 0
,D/SensorManager( 2381): unregisterListener ::   
D/LightsService( 2381): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2381): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/AmoledAdjustTimer( 2381): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 27
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2381): [PWL] Off : 765s ago
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 28
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2381): waitForAlarm result :8
,V/AlarmManager( 2381): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 29
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2381): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2381): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2381): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2381): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/TimaService( 2381): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2381): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2381): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2381): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2381): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2381): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2381): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2381): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2381): [PWL] Off : 855s ago
,V/AlarmManager( 2381): waitForAlarm result :8
,V/AlarmManager( 2381): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2580): GC_CONCURRENT freed 15796K, 33% free 33807K/50320K, paused 24ms+10ms, total 141ms
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 31
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2381): waitForAlarm result :4
,V/AlarmManager( 2381): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/UdcCache:FPQuery( 3275): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 2848): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2848): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GetConfigurationSnapshotOperation( 2848): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 2848): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 2848): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 2848): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/dalvikvm( 2848): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 2848): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 2848): VFY: replacing opcode 0x6e at 0x0033
,I/System.out( 2848): Thread-133(HTTPLog):isShipBuild true
,I/System.out( 2848): Thread-133(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 2848): GC_CONCURRENT freed 1695K, 18% free 11342K/13828K, paused 6ms+8ms, total 62ms
,D/ConnectivityService( 2381): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
,D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,W/Uploader( 2848):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 2848): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 2848): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 2848): no corresponding serverToken: com.google.android.gms.playlog.uploader
,E/Watchdog( 2381): !@Sync 32
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,W/ProcessCpuTracker( 2381): Skipping unknown process pid 8886
,W/ProcessCpuTracker( 2381): Skipping unknown process pid 8888
,W/ProcessCpuTracker( 2381): Skipping unknown process pid 8889
,W/ProcessCpuTracker( 2381): Skipping unknown process pid 8891
,W/ProcessCpuTracker( 2381): Skipping unknown process pid 8893
,W/ProcessCpuTracker( 2381): Skipping unknown process pid 8894
,W/ProcessCpuTracker( 2381): Skipping unknown process pid 8900
,W/ProcessCpuTracker( 2381): Skipping unknown process pid 8902
,D/AmoledAdjustTimer( 2381): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2381): waitForAlarm result :8
,V/AlarmManager( 2381): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 33
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2381): [PWL] Off : 950s ago
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 34
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2381): waitForAlarm result :8
,V/AlarmManager( 2381): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2381): GC_CONCURRENT freed 3828K, 72% free 24829K/86576K, paused 10ms+16ms, total 219ms
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 35
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2381): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2381): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2381): stay LED for fully charged
,D/UiModeManager( 2381): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2381): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2381): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2381): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2381): mCoverManager.getCoverState() : true
,D/BatteryService( 2381): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2381): prevTemp = 287, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 36
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2381): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2381): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2381): stay LED for fully charged
,D/UiModeManager( 2381): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2381): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2381): waitForAlarm result :8
,V/AlarmManager( 2381): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2381): waitForAlarm result :4
,V/AlarmManager( 2381): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/AmoledAdjustTimer( 2381): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/SPPClientService( 5523): [b] __PingReply__
,I/PowerManagerService( 2381): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 37
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 38
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2381): waitForAlarm result :8
,V/AlarmManager( 2381): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 39
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2381): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2381): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2381): stay LED for fully charged
,D/UiModeManager( 2381): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2381): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/TimaService( 2381): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2381): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2381): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2381): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 2381): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2381): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2381): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2381): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2381): [PWL] Off : 1155s ago
,V/AlarmManager( 2381): waitForAlarm result :8
,V/AlarmManager( 2381): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 41
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 42
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2381): waitForAlarm result :8
,V/AlarmManager( 2381): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2381): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2381): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,V/AlarmManager( 2381): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 43
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2381): [PWL] Off : 1265s ago
,E/Watchdog( 2381): !@Sync 44
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2381): waitForAlarm result :8
,V/AlarmManager( 2381): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 45
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 46
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2381): waitForAlarm result :8
,V/AlarmManager( 2381): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2381): waitForAlarm result :4
,D/LightsService( 2381): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2381): getReportingMode :: sensor.mType = 5
D/Sensors ( 2381): LightSensor setDelay = 200000000
D/Sensors ( 2381): LightSensor setSensorDelay = 200000000
D/Sensors ( 2381): Light sensor flush: not enabled 0
D/Sensors ( 2381): LightSensor enable = 1
D/Sensors ( 2381): LightSensor enableSensor = 1
D/SensorManager( 2381): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2381): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/dalvikvm( 2734): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 2734): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 2734): VFY: replacing opcode 0x6e at 0x0033
,D/Sensors ( 2381): LightSensor enable = 0
,D/Sensors ( 2381): LightSensor enableSensor = 0
,D/LightsService( 2381): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 2381): unregisterListener ::   
D/LightsService( 2381): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/Watchdog( 2381): !@Sync 47
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2381): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/dalvikvm( 2381): GC_CONCURRENT freed 3772K, 72% free 24816K/86576K, paused 20ms+19ms, total 258ms
,V/AlarmManager( 2381): waitForAlarm result :4
,V/AlarmManager( 2381): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/Watchdog( 2381): !@Sync 48
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2381): waitForAlarm result :8
,V/AlarmManager( 2381): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2381): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2381): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2381): mCoverManager.getCoverState() : true
,D/BatteryService( 2381): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 49
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/TimaService( 2381): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2381): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2381): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel( 2381): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2381): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2381): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2381): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2381): waitForAlarm result :8
,V/AlarmManager( 2381): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4068): GC_CONCURRENT freed 2050K, 28% free 9722K/13336K, paused 12ms+2ms, total 47ms
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 51
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2381): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 52
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/dalvikvm( 5523): GC_CONCURRENT freed 1921K, 22% free 10419K/13280K, paused 6ms+3ms, total 59ms
,V/AlarmManager( 2381): waitForAlarm result :8
,V/AlarmManager( 2381): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 53
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 54
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2381): waitForAlarm result :8
,V/AlarmManager( 2381): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 55
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2381): [PWL] Off : 1625s ago
,E/Watchdog( 2381): !@Sync 56
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2381): waitForAlarm result :8
,V/AlarmManager( 2381): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2381): waitForAlarm result :8
,E/SPPClientService( 5523): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 57
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 58
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2381): waitForAlarm result :8
,V/AlarmManager( 2381): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 59
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/TimaService( 2381): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2381): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2381): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel( 2381): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2381): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2381): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
D/TimaService( 2381): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2381): [PWL] Off : 1755s ago
,V/AlarmManager( 2381): waitForAlarm result :8
,V/AlarmManager( 2381): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2381): Prepared write state in 50ms
,I/ProcessStatsService( 2381): Pruning old procstats: /data/system/procstats/state-2015-12-08-01-13-59.bin
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 61
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/dalvikvm( 2381): GC_CONCURRENT freed 3723K, 72% free 24828K/86576K, paused 19ms+19ms, total 244ms
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 62
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2381): waitForAlarm result :8
,V/AlarmManager( 2381): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2381): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2381): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
V/AlarmManager( 2381): (AppSync) ### 0 added ###
,I/ActivityManager( 2381): Killing 6299:com.android.providers.calendar/u0a45 (adj 15): empty for 1800s
,I/ActivityManager( 2381): Killing 6310:com.sec.android.app.voicenote/1000 (adj 15): empty for 1801s
,I/ActivityManager( 2381): Killing 6271:com.sec.android.app.videoplayer/u0a53 (adj 15): empty for 1801s
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 63
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 64
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2381): waitForAlarm result :8
,V/AlarmManager( 2381): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,I/ActivityManager( 2381): Killing 6665:com.samsung.helphub/1000 (adj 15): empty for 1803s
,I/ActivityManager( 2381): Killing 6653:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1803s
,I/ActivityManager( 2381): Killing 6640:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty for 1803s
,I/ActivityManager( 2381): Killing 6627:com.sec.android.service.cm/u0a82 (adj 15): empty for 1803s
,I/ActivityManager( 2381): Killing 6342:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1803s
I/ActivityManager( 2381): Killing 5678:com.android.mms/u0a49 (adj 15): empty for 1803s
,I/ActivityManager( 2381): Killing 5785:com.osp.app.signin/u0a44 (adj 15): empty for 1804s
,I/ActivityManager( 2381): Killing 6601:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty for 1804s
,I/ActivityManager( 2381): Killing 6585:com.policydm/1000 (adj 15): empty for 1804s
,I/ActivityManager( 2381): Killing 5986:com.sec.android.app.shealth/u0a36 (adj 15): empty for 1804s
,I/ActivityManager( 2381): Killing 6571:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty for 1804s
,I/ActivityManager( 2381): Killing 6558:com.sec.pcw.device/1000 (adj 15): empty for 1805s
,I/ActivityManager( 2381): Killing 6545:com.android.musicfx/u0a24 (adj 15): empty for 1805s
,I/ActivityManager( 2381): Killing 6531:com.samsung.groupcast/u0a15 (adj 15): empty for 1805s
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/ActivityManager( 2381): Killing 6428:com.google.android.partnersetup/u0a14 (adj 15): empty for 1805s
,I/ActivityManager( 2381): Killing 6500:com.android.defcontainer/u0a6 (adj 15): empty for 1806s
,I/ActivityManager( 2381): Killing 6175:com.google.android.music:main/u0a125 (adj 15): empty for 1857s
,I/ActivityManager( 2381): Killing 6140:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty for 1857s
,I/ActivityManager( 2381): Killing 5972:com.android.calendar/u0a144 (adj 15): empty for 1857s
,I/ActivityManager( 2381): Killing 6328:com.sec.providers.settingsearch/u0a162 (adj 15): empty for 1857s
,I/ActivityManager( 2381): Killing 5384:com.google.android.talk/u0a109 (adj 15): empty for 1857s
,I/ActivityManager( 2381): Killing 6260:com.sec.phone/1001 (adj 15): empty for 1858s
,I/ActivityManager( 2381): Killing 5727:com.sec.android.diagmonagent/1000 (adj 15): empty for 1858s
,I/ActivityManager( 2381): Killing 5570:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty for 1858s
,D/CountryDetector( 2381): No listener is left
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2381): [PWL] Off : 1890s ago
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 65
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 66
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2381): waitForAlarm result :8
,V/AlarmManager( 2381): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2381): waitForAlarm result :4
,D/NtpTrustedTime( 2381): currentTimeMillis() cache hit
V/NetworkStats( 2381): performPollLocked(flags=0x3)
,V/AlarmManager( 2381): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager( 2381): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime( 2381): currentTimeMillis() cache hit
V/NetworkStats( 2381): performPollLocked() took 65ms
,D/NtpTrustedTime( 2381): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2381): currentTimeMillis() cache hit
,I/SELinux (11267): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (11267):  
,I/SELinux (11267): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (11267):  
I/SELinux (11267):  
,I/SELinux (11267): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (11267): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm(11267): >>>>> Normal User
,E/dalvikvm(11267): >>>>> com.n7mobile.muzodajnia:main [ userId:0 | appId:10184 ]
,E/SELinux (11267): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/TimaKeyStoreProvider(11267): in addTimaSignatureService
,D/TimaKeyStoreProvider(11267): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(11267): Added TimaKesytore provider
,D/dalvikvm(11267): GC_CONCURRENT freed 2996K, 28% free 9568K/13288K, paused 3ms+2ms, total 27ms
,D/dalvikvm(11267): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/@ WidgetProvider(11267): onReceive = android.appwidget.action.APPWIDGET_UPDATE
,D/@ WidgetProvider(11267): onUpdate called for widgetId : 0
,D/@ WidgetProvider(11267): Widget random data : 1
,D/@ WidgetProvider(11267): onUpdate called for widgetId : 5
,D/@ WidgetProvider(11267): Widget random data : 9
,I/ActivityManager( 2381): Killing 6679:com.sec.kidsplat.installer/u0a160 (adj 15): empty for 1880s
E/dalvikvm(11267): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJson
W/dalvikvm(11267): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(11267): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(11267): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(11267): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(11267): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(11267): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(11267): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(11267): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(11267): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPUT
W/dalvikvm(11267): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(11267): VFY: replacing opcode 0x22 at 0x0038
,D/dalvikvm(11267): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJson
,D/dalvikvm(11267): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(11267): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(11267): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPUT
,I/SensorManagerA( 2381): getReportingMode :: sensor.mType = 5
D/Sensors ( 2381): LightSensor setDelay = 200000000
D/Sensors ( 2381): LightSensor setSensorDelay = 200000000
D/Sensors ( 2381): Light sensor flush: not enabled 0
D/Sensors ( 2381): LightSensor enable = 1
,D/Sensors ( 2381): LightSensor enableSensor = 1
,D/LightsService( 2381): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/SensorManager( 2381): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/GLSActivity( 2848): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2848): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(11267): Thread-627(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(11267): Thread-627(ApacheHTTPLog):isShipBuild true
,I/System.out(11267): Thread-627(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/Sensors ( 2381): LightSensor enable = 0
,D/Sensors ( 2381): LightSensor enableSensor = 0
,D/SensorManager( 2381): unregisterListener ::   
D/LightsService( 2381): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2381): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/System.out(11267): AsyncNetworking-1-thread-1 calls detatch()
,I/System.out(11267): AsyncNetworking-1-thread-1 calls detatch()
,D/dalvikvm( 2848): GC_CONCURRENT freed 1733K, 18% free 11562K/14060K, paused 4ms+8ms, total 54ms
,V/ImageManager(11267): Max ALLOWED memory (MB): 128
V/ImageManager(11267): Max SHOULD USE memory (MB): 128
,V/ImageManager(11267): Max Image Cache memory (MB): 32
,D/skia    (11267): getTotalSize : Do not get file length
,D/@ WidgetProvider(11267): Building widget : 5
,D/ConnectivityService( 2381): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
,D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,D/dalvikvm( 2765): GC_CONCURRENT freed 8656K, 34% free 18356K/27728K, paused 8ms+11ms, total 75ms
,D/dalvikvm( 2765): WAIT_FOR_CONCURRENT_GC blocked 58ms
,D/dalvikvm( 2765): GC_FOR_ALLOC freed 167K, 33% free 18824K/27728K, paused 49ms, total 49ms
,D/BatteryService( 2381): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2381): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2381): mCoverManager.getCoverState() : true
,D/BatteryService( 2381): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2381): !@Sync 67
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2381): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2381): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2381): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2381): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 284, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2381): !@Sync 68
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2381): waitForAlarm result :8
,V/AlarmManager( 2381): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2381): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2381): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1800000ms)
```
