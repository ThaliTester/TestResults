#### Test 50650278b1aec71_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system
E/Watchdog( 2390): !@Sync 8
,--------- beginning of /dev/log/main
D/AndroidRuntime( 7146): 
D/AndroidRuntime( 7146): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7146): CheckJNI is OFF
D/AndroidRuntime( 7146): setted country_code = Poland
D/AndroidRuntime( 7146): setted countryiso_code = PL
D/AndroidRuntime( 7146): setted sales_code = PLS
D/AndroidRuntime( 7146): readGMSProperty: start
D/AndroidRuntime( 7146): readGMSProperty: already setted!!
D/AndroidRuntime( 7146): readGMSProperty: end
D/AndroidRuntime( 7146): addProductProperty: start
D/dalvikvm( 7146): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7146): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7146): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7146): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7146): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7146): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7146): failed to load memtrack module: -2
D/dalvikvm( 7146): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7146): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2390): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2390): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2390  pkgName : ACTIVITY_RESUME_BOOSTER@4
I/SurfaceFlinger( 1921): id=18 createSurf (16x16),-1 flag=20004, EimLayer
W/ActivityManager( 2390): mDVFSHelper.acquire()
I/SurfaceFlinger( 1921): id=19 createSurf (16x16),-1 flag=20004, EimLayer
I/SELinux ( 7173): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7173):  
D/PointerIcon( 2390): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2390): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2390): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2390): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7146): Shutting down VM
D/dalvikvm( 7146): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+0ms, total 4ms
I/SELinux ( 7173): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7173):  
I/SELinux ( 7173):  
I/SELinux ( 7173): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7173): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7173): >>>>> Normal User
E/dalvikvm( 7173): >>>>> com.test.thalitest [ userId:0 | appId:10517 ]
E/SELinux ( 7173): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7173): in addTimaSignatureService
D/TimaKeyStoreProvider( 7173): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7173): Added TimaKesytore provider
V/WindowManager( 2390): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
I/SQLiteSecureOpenHelper( 4185): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4185): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1921): id=9 Removed Mauncher (8/10)
I/SurfaceFlinger( 1921): id=9 Removed Mauncher (-2/10)
D/Launcher( 2784): onTrimMemory. Level: 20
D/dalvikvm( 7173): GC_CONCURRENT freed 3003K, 31% free 9565K/13676K, paused 3ms+1ms, total 19ms
D/dalvikvm( 7173): WAIT_FOR_CONCURRENT_GC blocked 13ms
V/WebViewChromium( 7173): Binding Chromium to the background looper Looper (main, tid 1) {422672a0}
I/chromium( 7173): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7173): Initializing chromium process, renderers=0
W/chromium( 7173): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7173): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7173): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7173): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7173): Mali API Version : 401
,I/Mali    ( 7173): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7173): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7173): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
,D/dalvikvm( 7173): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7173): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7173): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7173): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2581): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2390): tr p:7173,o:f
,W/dalvikvm( 7173): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 7173): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7173): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7173): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 7173): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 7173): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7173): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7173): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 7173): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7173): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7173): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 7173): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 7173): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2581): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2390): semi p:7173,o:f
,I/SurfaceFlinger( 1921): id=20 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2390): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2390): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2390): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2390): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2390): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7173): EGLImpl-HWUI Protected EGL context created
D/STATUSBAR-StatusBarManagerService( 2390): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/OpenGLRenderer( 7173): Enabling debug mode 0
,W/AwContents( 7173): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2390): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 7173): showStatusIcon on inactive InputConnection
,D/CustomFrequencyManagerService( 2390): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2390  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2390): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2390): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2390  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/JsMessageQueue( 7173): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7173): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42257508
,D/dalvikvm( 7173): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42257508
D/jxcore_app_log( 7173): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2027483032
,D/JX-Cordova( 7173): jxcore cordova android initializing
I/dalvikvm( 7173): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 7173): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 7173): VFY: replacing opcode 0x6e at 0x0045
,D/dalvikvm( 7173): GC_CONCURRENT freed 1295K, 18% free 11343K/13744K, paused 2ms+2ms, total 22ms
,D/dalvikvm( 7173): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/dalvikvm( 7173): GC_CONCURRENT freed 1930K, 18% free 14925K/17984K, paused 1ms+2ms, total 40ms
,D/dalvikvm( 7173): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/CustomFrequencyManagerService( 2390): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2390  tag : ACTIVITY_RESUME_BOOSTER@8
,D/AmoledAdjustTimer( 2390): prevTemp = 309, currTemp = 308, prevStep = 4, currStep = 4
,D/dalvikvm( 7173): GC_FOR_ALLOC freed 5292K, 30% free 16201K/22864K, paused 51ms, total 55ms
,D/dalvikvm( 7173): GC_CONCURRENT freed 6699K, 31% free 17667K/25500K, paused 1ms+9ms, total 59ms
,D/dalvikvm( 7173): WAIT_FOR_CONCURRENT_GC blocked 38ms
,D/dalvikvm( 7173): GC_FOR_ALLOC freed 1163K, 32% free 17553K/25500K, paused 49ms, total 49ms
,I/dalvikvm-heap( 7173): Grow heap (frag case) to 21.737MB for 3688532-byte allocation
,D/dalvikvm( 7173): GC_FOR_ALLOC freed 2403K, 36% free 18751K/29104K, paused 49ms, total 49ms
,W/jxcore-log( 7173): Initializing JXcore engine
,W/jxcore-log( 7173): JXcore engine is ready
,W/jxcore-log( 7173): Starting JXcore engine
,W/jxcore-log( 7173): Platform android
W/jxcore-log( 7173): 
W/jxcore-log( 7173): Process ARCH arm
W/jxcore-log( 7173): 
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 340, Delta = 10
,I/jxcore-log( 7173): JXcore Cordova bridge is ready!
I/jxcore-log( 7173): 
,W/jxcore-log( 7173): JXcore engine is started
,I/chromium( 7173): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 7173): Error!: missing ) after argument list
E/jxcore  ( 7173): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 7173): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,D/PointerIcon( 2390): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2390): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2390): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2390): setHoveringSpenCustomIcon IconType is same.1
I/ActivityManager( 2390): Killing 6126:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,I/SurfaceFlinger( 1921): id=20 Removed NainActivit (8/10)
,I/SurfaceFlinger( 1921): id=20 Removed NainActivit (-2/10)
,I/SurfaceFlinger( 1921): id=19 Removed EimLayer (6/9)
I/SurfaceFlinger( 1921): id=19 Removed EimLayer (-2/9)
,I/SurfaceFlinger( 1921): id=18 Removed EimLayer (5/8)
,I/SurfaceFlinger( 1921): id=18 Removed EimLayer (-2/8)
,V/WindowManager( 2390): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
,D/Launcher( 2784): onRestart, Launcher: 1110000424
,D/Launcher( 2784): onStart, Launcher: 1110000424
,D/Launcher.HomeView( 2784): onStart
,I/SurfaceFlinger( 1921): id=21 createSurf (720x1280),1 flag=4, Mauncher
D/STATUSBAR-StatusBarManagerService( 2390): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/STATUSBAR-StatusBarManagerService( 2390): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2390): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2390): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2390): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2390): setHoveringSpenCustomIcon IconType is same.1
,D/PhoneStatusBar( 2581): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/PhoneStatusBar( 2581): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2390): tr p:2784,o:f
D/StatusBarManagerService( 2390): semi p:2784,o:f
,W/ContextImpl( 2390): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/IInputConnectionWrapper( 7173): showStatusIcon on inactive InputConnection
,W/ContextImpl( 2390): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/PackageManager( 2390): [MSG] WRITE_PACKAGE_RESTRICTIONS,
,D/AmoledAdjustTimer( 2390): prevTemp = 308, currTemp = 308, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 330, Delta = -10,
,D/BatteryService( 2390): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2390): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2390): stay LED for fully charged
,D/UiModeManager( 2390): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4019): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4019): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2390): prevTemp = 308, currTemp = 307, prevStep = 4, currStep = 4,
,V/AlarmManager( 2390): waitForAlarm result :8,
,V/AlarmManager( 2390): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,I/PowerManagerService( 2390): [PWL] Off : 180s ago,
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 330, Delta = 0,
,W/ContextImpl( 2390): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2390): level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2390): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2390): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
D/BatteryService( 2390): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4019): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4019): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2390): !@Sync 9,
,D/AmoledAdjustTimer( 2390): prevTemp = 307, currTemp = 307, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 330, Delta = 0,
,D/BatteryService( 2390): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2390): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2390): stay LED for fully charged
,D/UiModeManager( 2390): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4019): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4019): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2390): prevTemp = 307, currTemp = 306, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 330, Delta = 0,
,W/ContextImpl( 2390): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/AmoledAdjustTimer( 2390): prevTemp = 306, currTemp = 306, prevStep = 4, currStep = 4,
,D/TimaService( 2390): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 2390): TimaServiceHandler.handleMessage what =1
,D/TimaService( 2390): TIMA: checkEvent, operation: 50000 subject: 10000,
,I/TLC_TIMA_PKM_initialize( 2390): initializing...,
I/TLC_TIMA_PKM_initialize( 2390): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2390): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2390): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2390): input max_recvmsg_size = 262196,
I/TZ: mc_tlc_communication( 2390): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2390): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 2390): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2390): aligned max_recvmsg_size = 262208
,I/TZ: mc_tlc_communication( 2390): device_id = 0x0
I/TZ: mc_tlc_communication( 2390): tlc_open() was called
,I/TZ: mc_tlc_communication( 2390): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2390): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 2390): Opening the session,
,I/TZ: mc_tlc_communication( 2390): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 2390): Trustlet response is completed,
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 330, Delta = 0,
,D/BatteryService( 2390): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2390): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2390): mCoverManager.getCoverState() : true,
,D/BatteryService( 2390): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4019): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4019): Disconnected process message: 10,
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2390): !@Sync 10,
,I/TLC_TIMA_PKM_measure_kernel( 2390): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2390): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2390): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/TimaService( 2390): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/AmoledAdjustTimer( 2390): prevTemp = 306, currTemp = 305, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 330, Delta = 0,
,W/ContextImpl( 2390): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2390): [PWL] Off : 225s ago,
,D/AmoledAdjustTimer( 2390): prevTemp = 305, currTemp = 305, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2390): prevTemp = 305, currTemp = 305, prevStep = 4, currStep = 4,
,V/AlarmManager( 2390): waitForAlarm result :8,
,V/AlarmManager( 2390): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 330, Delta = 0,
,W/ContextImpl( 2390): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 2390): !@Sync 11,
,D/AmoledAdjustTimer( 2390): prevTemp = 305, currTemp = 305, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 330, Delta = 0,
,V/AlarmManager( 2390): waitForAlarm result :4,
,V/AlarmManager( 2390): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 7508): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7508):  
,I/SELinux ( 7508): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7508):  
I/SELinux ( 7508):  
,I/SELinux ( 7508): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7508): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7508): >>>>> Normal User
,E/dalvikvm( 7508): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ],
,E/SELinux ( 7508): [DEBUG] seapp_context_lookup: seinfoCategory = default,
,D/TimaKeyStoreProvider( 7508): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7508): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7508): Added TimaKesytore provider,
,D/dalvikvm( 7508): GC_CONCURRENT freed 3013K, 31% free 9558K/13680K, paused 4ms+2ms, total 31ms,
,D/dalvikvm( 7508): WAIT_FOR_CONCURRENT_GC blocked 26ms
,I/ActivityManager( 2390): Killing 6197:com.sec.android.app.music:service/u0a152 (adj 15): empty #43,
,D/BatteryService( 2390): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2390): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2390): stay LED for fully charged
,D/UiModeManager( 2390): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4019): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4019): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2390): prevTemp = 305, currTemp = 304, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 330, Delta = 0,
,W/ContextImpl( 2390): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/AmoledAdjustTimer( 2390): prevTemp = 304, currTemp = 304, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 330, Delta = 0,
,I/PowerManagerService( 2390): [PWL] Off : 275s ago,
,D/BatteryService( 2390): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2390): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2390): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED,
,D/UiModeManager( 2390): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4019): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4019): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2390): !@Sync 12,
,D/AmoledAdjustTimer( 2390): prevTemp = 304, currTemp = 303, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 330, Delta = 0,
,W/ContextImpl( 2390): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/AmoledAdjustTimer( 2390): prevTemp = 303, currTemp = 303, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 303, currTemp = 303, prevStep = 4, currStep = 4
,V/AlarmManager( 2390): waitForAlarm result :8
,V/AlarmManager( 2390): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 330, Delta = 0
,W/ContextImpl( 2390): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2390): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2390): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2390): mCoverManager.getCoverState() : true
,D/BatteryService( 2390): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4019): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4019): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2390): !@Sync 13
,D/AmoledAdjustTimer( 2390): prevTemp = 303, currTemp = 302, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = -10
,W/ContextImpl( 2390): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2390): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2390): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2390): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2390): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4019): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4019): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2390): prevTemp = 302, currTemp = 301, prevStep = 4, currStep = 4
,I/PowerManagerService( 2390): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2390): !@Sync 14
,D/AmoledAdjustTimer( 2390): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,W/ContextImpl( 2390): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/AmoledAdjustTimer( 2390): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2390): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2390): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2390): stay LED for fully charged
,D/UiModeManager( 2390): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4019): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4019): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2390): prevTemp = 301, currTemp = 300, prevStep = 4, currStep = 4
,V/AlarmManager( 2390): waitForAlarm result :8
,V/AlarmManager( 2390): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2390): GC_CONCURRENT freed 4222K, 69% free 24773K/79548K, paused 15ms+18ms, total 237ms
,D/dalvikvm( 2390): WAIT_FOR_CONCURRENT_GC blocked 201ms
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,W/ContextImpl( 2390): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2390): !@Sync 15
,D/AmoledAdjustTimer( 2390): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,W/ContextImpl( 2390): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2390): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2390): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2390): mCoverManager.getCoverState() : true
,D/BatteryService( 2390): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4019): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4019): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2390): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4
,I/PowerManagerService( 2390): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2390): !@Sync 16
,D/AmoledAdjustTimer( 2390): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,W/ContextImpl( 2390): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/AmoledAdjustTimer( 2390): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2390): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2390): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2390): mCoverManager.getCoverState() : true
D/BatteryService( 2390): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4019): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4019): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2390): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4
,V/AlarmManager( 2390): waitForAlarm result :8
,V/AlarmManager( 2390): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,W/ContextImpl( 2390): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2390): !@Sync 17
,D/AmoledAdjustTimer( 2390): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,V/AlarmManager( 2390): waitForAlarm result :4
,V/AlarmManager( 2390): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/AmoledAdjustTimer( 2390): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,W/ContextImpl( 2390): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/AmoledAdjustTimer( 2390): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,I/PowerManagerService( 2390): [PWL] Off : 455s ago
,E/Watchdog( 2390): !@Sync 18
,D/BatteryService( 2390): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2390): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2390): mCoverManager.getCoverState() : true
,D/BatteryService( 2390): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4019): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4019): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2390): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,W/ContextImpl( 2390): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/AmoledAdjustTimer( 2390): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,V/AlarmManager( 2390): waitForAlarm result :8
,V/AlarmManager( 2390): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,W/ContextImpl( 2390): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2390): !@Sync 19
,D/AmoledAdjustTimer( 2390): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,W/ContextImpl( 2390): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2390): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2390): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2390): stay LED for fully charged
,D/UiModeManager( 2390): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4019): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4019): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2390): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,D/TimaService( 2390): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2390): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2390): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2390): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2390): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2390): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2390): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2390): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/AmoledAdjustTimer( 2390): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,W/ContextImpl( 2390): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2390): [PWL] Off : 525s ago
,D/AmoledAdjustTimer( 2390): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,V/AlarmManager( 2390): waitForAlarm result :8
,V/AlarmManager( 2390): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,W/ContextImpl( 2390): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2390): !@Sync 21
,D/BatteryService( 2390): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2390): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2390): mCoverManager.getCoverState() : true
,D/BatteryService( 2390): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4019): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4019): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2390): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,I/GAV2    ( 5583): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5583): Thread[disconnect check,5,main]: Disconnected from service
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2390): !@Sync 22
,D/AmoledAdjustTimer( 2390): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2390): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2390): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager( 2390): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2390): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4019): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4019): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2390): waitForAlarm result :8
,V/AlarmManager( 2390): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2390): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,I/PowerManagerService( 2390): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2390): !@Sync 23
,D/AmoledAdjustTimer( 2390): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2390): !@Sync 24
,D/AmoledAdjustTimer( 2390): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,V/AlarmManager( 2390): waitForAlarm result :8
,V/AlarmManager( 2390): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2390): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2390): <AppSync3 Whitelist>
,V/AlarmManager( 2390): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2390): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2390): !@Sync 25
,D/BatteryService( 2390): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2390): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2390): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2390): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4019): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4019): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2390): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,I/PowerManagerService( 2390): [PWL] Off : 680s ago
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2390): !@Sync 26
,D/AmoledAdjustTimer( 2390): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,V/AlarmManager( 2390): waitForAlarm result :8
,I/SensorManagerA( 2390): getReportingMode :: sensor.mType = 5
,D/LightsService( 2390): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2390): LightSensor setDelay = 200000000
D/Sensors ( 2390): LightSensor setSensorDelay = 200000000
D/Sensors ( 2390): Light sensor flush: not enabled 0
D/Sensors ( 2390): LightSensor enable = 1
D/Sensors ( 2390): LightSensor enableSensor = 1
,D/SensorManager( 2390): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  ,
,E/SPPClientService( 5492): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/Sensors ( 2390): LightSensor enable = 0
,D/Sensors ( 2390): LightSensor enableSensor = 0
,D/LightsService( 2390): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 2390): unregisterListener ::   
D/LightsService( 2390): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/AmoledAdjustTimer( 2390): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2390): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2390): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2390): stay LED for fully charged
,D/UiModeManager( 2390): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 4019): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4019): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2390): waitForAlarm result :8
,V/AlarmManager( 2390): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4097): GC_CONCURRENT freed 2879K, 30% free 9690K/13708K, paused 3ms+2ms, total 48ms
,D/dalvikvm( 4097): WAIT_FOR_CONCURRENT_GC blocked 40ms
,D/AmoledAdjustTimer( 2390): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2390): !@Sync 27
,D/AmoledAdjustTimer( 2390): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2390): !@Sync 28
,D/AmoledAdjustTimer( 2390): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,I/PowerManagerService( 2390): [PWL] Off : 765s ago
,D/AmoledAdjustTimer( 2390): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,V/AlarmManager( 2390): waitForAlarm result :8
,V/AlarmManager( 2390): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2390): GC_CONCURRENT freed 3769K, 69% free 24754K/79144K, paused 13ms+17ms, total 213ms
,D/AmoledAdjustTimer( 2390): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2390): !@Sync 29
,D/BatteryService( 2390): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2390): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2390): mCoverManager.getCoverState() : true
,D/BatteryService( 2390): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4019): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4019): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2390): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,D/TimaService( 2390): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2390): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2390): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2390): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2390): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2390): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2390): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2390): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
D/TimaService( 2390): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/AmoledAdjustTimer( 2390): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,V/AlarmManager( 2390): waitForAlarm result :8
,V/AlarmManager( 2390): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2390): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2390): !@Sync 31
,D/AmoledAdjustTimer( 2390): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 320, Delta = 0
,I/PowerManagerService( 2390): [PWL] Off : 855s ago
,D/AmoledAdjustTimer( 2390): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2390): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2390): !@Sync 32
,D/BatteryService( 2390): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2390): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2390): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2390): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4019): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4019): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2390): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2390): waitForAlarm result :8
,V/AlarmManager( 2390): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2390): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2390): !@Sync 33
,D/AmoledAdjustTimer( 2390): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2390): !@Sync 34
,D/AmoledAdjustTimer( 2390): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,I/PowerManagerService( 2390): [PWL] Off : 950s ago
,D/AmoledAdjustTimer( 2390): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2390): waitForAlarm result :8
,V/AlarmManager( 2390): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2390): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2390): !@Sync 35
,D/AmoledAdjustTimer( 2390): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2390): !@Sync 36
,D/BatteryService( 2390): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2390): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2390): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2390): mCoverManager.getCoverState() : true
,V/HeadsetService( 4019): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4019): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2390): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2390): waitForAlarm result :4
,V/AlarmManager( 2390): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,E/SPPClientService( 5492): [b] __PingReply__
V/AlarmManager( 2390): waitForAlarm result :4
,V/AlarmManager( 2390): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/ConnectivityService( 2390): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
,D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2390): waitForAlarm result :8
,V/AlarmManager( 2390): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2390): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2390): !@Sync 37
,D/AmoledAdjustTimer( 2390): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,I/PowerManagerService( 2390): [PWL] Off : 1050s ago
,D/AmoledAdjustTimer( 2390): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2390): !@Sync 38
,D/AmoledAdjustTimer( 2390): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2390): waitForAlarm result :8
,V/AlarmManager( 2390): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2390): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2390): !@Sync 39
,D/AmoledAdjustTimer( 2390): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/TimaService( 2390): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2390): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2390): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2390): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2390): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 2390): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2390): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2390): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2390): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/AmoledAdjustTimer( 2390): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2390): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2390): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2390): mCoverManager.getCoverState() : true
,D/BatteryService( 2390): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4019): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4019): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2390): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2390): waitForAlarm result :8
,V/AlarmManager( 2390): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2390): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2390): !@Sync 41
,D/AmoledAdjustTimer( 2390): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,I/PowerManagerService( 2390): [PWL] Off : 1155s ago
,D/AmoledAdjustTimer( 2390): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2390): !@Sync 42
,D/AmoledAdjustTimer( 2390): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2390): waitForAlarm result :8
,V/AlarmManager( 2390): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2390): GC_CONCURRENT freed 3707K, 69% free 24774K/79144K, paused 17ms+16ms, total 218ms
,D/AmoledAdjustTimer( 2390): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2390): !@Sync 43
,D/AmoledAdjustTimer( 2390): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2390): !@Sync 44
,D/AmoledAdjustTimer( 2390): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2390): waitForAlarm result :8
,V/AlarmManager( 2390): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2390): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2390): <AppSync3 Whitelist>
,V/AlarmManager( 2390): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2390): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,I/PowerManagerService( 2390): [PWL] Off : 1265s ago
,E/Watchdog( 2390): !@Sync 45
,D/AmoledAdjustTimer( 2390): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2390): !@Sync 46
,D/BatteryService( 2390): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2390): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2390): mCoverManager.getCoverState() : true
D/BatteryService( 2390): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4019): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4019): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2390): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2390): waitForAlarm result :4
,I/SensorManagerA( 2390): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2390): LightSensor setDelay = 200000000
,D/LightsService( 2390): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2390): LightSensor setSensorDelay = 200000000
D/Sensors ( 2390): Light sensor flush: not enabled 0
D/Sensors ( 2390): LightSensor enable = 1
D/Sensors ( 2390): LightSensor enableSensor = 1
D/SensorManager( 2390): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2390): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/EventLogService( 3435): Aggregate from 1449595028453 (log), 1449595028453 (data)
,D/Sensors ( 2390): LightSensor enable = 0
,D/Sensors ( 2390): LightSensor enableSensor = 0
,D/LightsService( 2390): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 2390): unregisterListener ::   
D/LightsService( 2390): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/AmoledAdjustTimer( 2390): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2390): waitForAlarm result :8
,V/AlarmManager( 2390): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2390): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2390): !@Sync 47
,D/AmoledAdjustTimer( 2390): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2390): !@Sync 48
,D/AmoledAdjustTimer( 2390): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2390): waitForAlarm result :8
,V/AlarmManager( 2390): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4097): GC_CONCURRENT freed 1895K, 30% free 9722K/13704K, paused 7ms+2ms, total 44ms
,I/PowerManagerService( 2390): [PWL] Off : 1380s ago
,D/AmoledAdjustTimer( 2390): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2390): !@Sync 49
,D/AmoledAdjustTimer( 2390): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/TimaService( 2390): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2390): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2390): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2390): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2390): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel( 2390): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2390): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2390): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2390): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/AmoledAdjustTimer( 2390): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2390): waitForAlarm result :8
,V/AlarmManager( 2390): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2390): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2390): !@Sync 51
,D/BatteryService( 2390): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2390): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2390): stay LED for fully charged
,D/UiModeManager( 2390): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4019): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4019): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2390): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2390): !@Sync 52
,D/AmoledAdjustTimer( 2390): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/dalvikvm( 5492): GC_CONCURRENT freed 1915K, 24% free 10418K/13668K, paused 6ms+4ms, total 63ms
,D/AmoledAdjustTimer( 2390): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2390): waitForAlarm result :8
,V/AlarmManager( 2390): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2390): [PWL] Off : 1500s ago
,D/AmoledAdjustTimer( 2390): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2390): !@Sync 53
,D/AmoledAdjustTimer( 2390): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2390): !@Sync 54
,D/AmoledAdjustTimer( 2390): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2390): waitForAlarm result :8
,V/AlarmManager( 2390): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2390): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2390): !@Sync 55
,D/AmoledAdjustTimer( 2390): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2390): !@Sync 56
,D/AmoledAdjustTimer( 2390): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2390): waitForAlarm result :8
,E/SPPClientService( 5492): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/AmoledAdjustTimer( 2390): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2390): waitForAlarm result :8
,V/AlarmManager( 2390): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2784): GC_CONCURRENT freed 7168K, 35% free 19102K/29184K, paused 15ms+8ms, total 84ms
,D/AmoledAdjustTimer( 2390): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,I/PowerManagerService( 2390): [PWL] Off : 1625s ago
,E/Watchdog( 2390): !@Sync 57
,D/AmoledAdjustTimer( 2390): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/dalvikvm( 2390): GC_CONCURRENT freed 3736K, 69% free 24798K/79144K, paused 16ms+17ms, total 214ms
,D/AmoledAdjustTimer( 2390): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2390): !@Sync 58
,D/AmoledAdjustTimer( 2390): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2390): waitForAlarm result :8
,V/AlarmManager( 2390): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2390): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2390): !@Sync 59
,D/AmoledAdjustTimer( 2390): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2390): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2390): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2390): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2390): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4019): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4019): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2390): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/TimaService( 2390): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2390): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2390): TimaServiceHandler.handleMessage what =1
,D/BatteryService( 2390): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2390): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2390): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2390): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4019): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/HeadsetStateMachine( 4019): Disconnected process message: 10
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ProcessCpuTracker( 2390): Skipping unknown process pid 10810
,D/AmoledAdjustTimer( 2390): prevTemp = 285, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2390): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel( 2390): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2390): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2390): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2390): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 2390): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2390): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2390): mCoverManager.getCoverState() : true
,D/BatteryService( 2390): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4019): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4019): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2390): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2390): waitForAlarm result :8
,V/AlarmManager( 2390): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2390): Prepared write state in 58ms
,I/ProcessStatsService( 2390): Prepared write state in 33ms
,I/ProcessStatsService( 2390): Pruning old procstats: /data/system/procstats/state-2015-12-07-22-13-51.bin
,D/AmoledAdjustTimer( 2390): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2390): !@Sync 61
,D/AmoledAdjustTimer( 2390): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,I/PowerManagerService( 2390): [PWL] Off : 1755s ago
,D/AmoledAdjustTimer( 2390): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2390): !@Sync 62
,D/AmoledAdjustTimer( 2390): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2390): waitForAlarm result :8
,V/AlarmManager( 2390): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,I/ActivityManager( 2390): Killing 6148:com.google.android.music:main/u0a125 (adj 15): empty for 1815s
,I/ActivityManager( 2390): Killing 6112:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty for 1816s
,I/ActivityManager( 2390): Killing 6274:com.android.providers.calendar/u0a45 (adj 15): empty for 1816s
,I/ActivityManager( 2390): Killing 5939:com.android.calendar/u0a144 (adj 15): empty for 1816s
,I/ActivityManager( 2390): Killing 6292:com.sec.providers.settingsearch/u0a162 (adj 15): empty for 1816s
,I/ActivityManager( 2390): Killing 6230:com.sec.phone/1001 (adj 15): empty for 1816s
,I/ActivityManager( 2390): Killing 5356:com.google.android.talk/u0a109 (adj 15): empty for 1817s
,I/ActivityManager( 2390): Killing 5699:com.sec.android.diagmonagent/1000 (adj 15): empty for 1817s
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/ActivityManager( 2390): Killing 6270:com.sec.android.app.voicenote/1000 (adj 15): empty for 1819s
,I/ActivityManager( 2390): Killing 6251:com.sec.android.app.videoplayer/u0a53 (adj 15): empty for 1819s
,D/AmoledAdjustTimer( 2390): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2390): !@Sync 63
,D/AmoledAdjustTimer( 2390): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2390): !@Sync 64
,D/AmoledAdjustTimer( 2390): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2390): waitForAlarm result :8
,V/AlarmManager( 2390): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2390): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2390): <AppSync3 Whitelist>
,V/AlarmManager( 2390): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
I/ActivityManager( 2390): Killing 6686:com.samsung.helphub/1000 (adj 15): empty for 1818s
,I/ActivityManager( 2390): Killing 6673:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1818s
,I/ActivityManager( 2390): Killing 6660:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty for 1818s
,I/ActivityManager( 2390): Killing 6647:com.sec.android.service.cm/u0a82 (adj 15): empty for 1819s
,I/ActivityManager( 2390): Killing 6313:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1819s
,I/ActivityManager( 2390): Killing 5648:com.android.mms/u0a49 (adj 15): empty for 1819s
,I/ActivityManager( 2390): Killing 5759:com.osp.app.signin/u0a44 (adj 15): empty for 1819s
,I/ActivityManager( 2390): Killing 6621:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty for 1819s
,I/ActivityManager( 2390): Killing 6605:com.policydm/1000 (adj 15): empty for 1819s
,I/ActivityManager( 2390): Killing 5955:com.sec.android.app.shealth/u0a36 (adj 15): empty for 1819s
,I/ActivityManager( 2390): Killing 6591:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty for 1820s
,I/ActivityManager( 2390): Killing 6579:com.sec.pcw.device/1000 (adj 15): empty for 1820s
,I/ActivityManager( 2390): Killing 6565:com.android.musicfx/u0a24 (adj 15): empty for 1820s
,I/ActivityManager( 2390): Killing 6551:com.samsung.groupcast/u0a15 (adj 15): empty for 1820s
,I/ActivityManager( 2390): Killing 6400:com.google.android.partnersetup/u0a14 (adj 15): empty for 1820s
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/ActivityManager( 2390): Killing 6520:com.android.defcontainer/u0a6 (adj 15): empty for 1821s
,I/ActivityManager( 2390): Killing 6468:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty for 1859s
,D/CountryDetector( 2390): No listener is left
,D/AmoledAdjustTimer( 2390): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2390): !@Sync 65
,D/AmoledAdjustTimer( 2390): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,I/PowerManagerService( 2390): [PWL] Off : 1890s ago
,D/AmoledAdjustTimer( 2390): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2390): !@Sync 66
,D/AmoledAdjustTimer( 2390): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2390): waitForAlarm result :8
,V/AlarmManager( 2390): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2390): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2390): !@Sync 67
,D/AmoledAdjustTimer( 2390): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2390): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2390): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2390): stay LED for fully charged
,D/UiModeManager( 2390): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4019): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4019): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2390): !@Sync 68
,D/AmoledAdjustTimer( 2390): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2390): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0,
,V/AlarmManager( 2390): waitForAlarm result :8
,V/AlarmManager( 2390): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2390): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2390): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2390): !@Sync 69
,TIME-OUT KILL (timeout was 1800000ms)
```
