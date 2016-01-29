#### Test 56818254e6f5c3b_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system,
W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
--------- beginning of /dev/log/main
D/AndroidRuntime( 6882): 
D/AndroidRuntime( 6882): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6882): CheckJNI is OFF
D/AndroidRuntime( 6882): setted country_code = Poland
D/AndroidRuntime( 6882): setted countryiso_code = PL
D/AndroidRuntime( 6882): setted sales_code = PLS
D/AndroidRuntime( 6882): readGMSProperty: start
D/AndroidRuntime( 6882): readGMSProperty: already setted!!
D/AndroidRuntime( 6882): readGMSProperty: end
D/AndroidRuntime( 6882): addProductProperty: start
D/dalvikvm( 6882): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6882): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6882): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6882): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6882): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 6882): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6882): failed to load memtrack module: -2
D/dalvikvm( 6882): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 6882): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2397): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2397): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2397  pkgName : ACTIVITY_RESUME_BOOSTER@4
I/SurfaceFlinger( 1922): id=19 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger( 1922): id=20 createSurf (16x16),-1 flag=20004, EimLayer
W/ActivityManager( 2397): mDVFSHelper.acquire()
I/SELinux ( 6909): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6909):  
D/PointerIcon( 2397): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2397): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2397): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2397): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 6882): Shutting down VM
D/dalvikvm( 6882): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+0ms, total 4ms
I/SELinux ( 6909): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6909):  
I/SELinux ( 6909):  
I/SELinux ( 6909): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6909): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6909): >>>>> Normal User
E/dalvikvm( 6909): >>>>> com.test.thalitest [ userId:0 | appId:10188 ]
E/SELinux ( 6909): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 6909): in addTimaSignatureService
D/TimaKeyStoreProvider( 6909): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6909): Added TimaKesytore provider
V/WindowManager( 2397): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
I/SQLiteSecureOpenHelper( 3561): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3561): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1922): id=9 Removed Mauncher (8/10)
I/SurfaceFlinger( 1922): id=9 Removed Mauncher (-2/10)
D/Launcher( 2781): onTrimMemory. Level: 20
D/dalvikvm( 6909): GC_CONCURRENT freed 3006K, 30% free 9565K/13636K, paused 2ms+1ms, total 18ms
D/dalvikvm( 6909): WAIT_FOR_CONCURRENT_GC blocked 15ms
V/WebViewChromium( 6909): Binding Chromium to the background looper Looper (main, tid 1) {42320238}
I/chromium( 6909): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 6909): Initializing chromium process, renderers=0
W/chromium( 6909): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 6909): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 6909): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 6909): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 6909): Mali API Version : 401
,I/Mali    ( 6909): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 ,
,I/dalvikvm( 6909): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>,
W/dalvikvm( 6909): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 6909): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 6909): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 6909): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 6909): VFY: replacing opcode 0x6e at 0x0008,
,D/PhoneStatusBar( 2582): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/StatusBarManagerService( 2397): tr p:6909,o:f
W/dalvikvm( 6909): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 6909): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 6909): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 6909): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 6909): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 6909): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 6909): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 6909): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 6909): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 6909): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 6909): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 6909): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 6909): CordovaWebView is running on device made by: samsung
,D/StatusBarManagerService( 2397): semi p:6909,o:f
D/PhoneStatusBar( 2582): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,I/SurfaceFlinger( 1922): id=21 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2397): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2397): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2397): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2397): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2397): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 6909): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 6909): Enabling debug mode 0
,D/STATUSBAR-StatusBarManagerService( 2397): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
W/AwContents( 6909): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 6909): showStatusIcon on inactive InputConnection
,D/CustomFrequencyManagerService( 2397): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2397  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2397): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2397): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2397  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/JsMessageQueue( 6909): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 6909): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4230e8e8
,D/dalvikvm( 6909): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4230e8e8
,D/jxcore_app_log( 6909): JniHelper::setJavaVM(0x418bc220), pthread_self() = 2026716528
,I/chromium( 6909): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/dalvikvm( 6909): GC_CONCURRENT freed 1289K, 18% free 11349K/13700K, paused 2ms+2ms, total 24ms
,D/dalvikvm( 6909): WAIT_FOR_CONCURRENT_GC blocked 7ms
,D/dalvikvm( 6909): GC_FOR_ALLOC freed 2337K, 20% free 14340K/17752K, paused 33ms, total 33ms
,D/CustomFrequencyManagerService( 2397): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2397  tag : ACTIVITY_RESUME_BOOSTER@8
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 6909): GC_CONCURRENT freed 6472K, 33% free 16029K/23596K, paused 1ms+9ms, total 57ms
D/dalvikvm( 6909): WAIT_FOR_CONCURRENT_GC blocked 35ms
,D/dalvikvm( 6909): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 6909): GC_FOR_ALLOC freed 5332K, 29% free 16852K/23596K, paused 55ms, total 55ms
,W/jxcore-log( 6909): Initializing JXcore engine
,W/jxcore-log( 6909): JXcore engine is ready
,W/jxcore-log( 6909): Starting JXcore engine
,W/jxcore-log( 6909): Platform android
W/jxcore-log( 6909): 
,W/jxcore-log( 6909): Process ARCH arm
W/jxcore-log( 6909): 
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 330, Delta = 10
,I/jxcore-log( 6909): JXcore Cordova bridge is ready!
I/jxcore-log( 6909): 
,W/jxcore-log( 6909): JXcore engine is started
,E/jxcore  ( 6909): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6909): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6909): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/PointerIcon( 2397): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2397): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2397): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2397): setHoveringSpenCustomIcon IconType is same.1
,I/ActivityManager( 2397): Killing 5317:com.sec.android.diagmonagent/1000 (adj 15): empty #43
W/PluginManager( 6909): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 18ms. Plugin should use CordovaInterface.getThreadPool().
,I/SurfaceFlinger( 1922): id=21 Removed NainActivit (8/10)
,I/SurfaceFlinger( 1922): id=21 Removed NainActivit (-2/10)
,I/SurfaceFlinger( 1922): id=20 Removed EimLayer (6/9)
,I/SurfaceFlinger( 1922): id=20 Removed EimLayer (-2/9)
I/SurfaceFlinger( 1922): id=19 Removed EimLayer (5/8)
,I/SurfaceFlinger( 1922): id=19 Removed EimLayer (-2/8)
,V/WindowManager( 2397): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
,D/Launcher( 2781): onRestart, Launcher: 1110799144
D/Launcher( 2781): onStart, Launcher: 1110799144
,D/Launcher.HomeView( 2781): onStart
,I/SurfaceFlinger( 1922): id=22 createSurf (720x1280),1 flag=4, Mauncher
D/STATUSBAR-StatusBarManagerService( 2397): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/STATUSBAR-StatusBarManagerService( 2397): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2397): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2397): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2397): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2397): setHoveringSpenCustomIcon IconType is same.1
,D/PhoneStatusBar( 2582): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/PhoneStatusBar( 2582): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2397): tr p:2781,o:f
D/StatusBarManagerService( 2397): semi p:2781,o:f
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 6909): showStatusIcon on inactive InputConnection
,D/AmoledAdjustTimer( 2397): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4,
,D/PackageManager( 2397): [MSG] WRITE_PACKAGE_RESTRICTIONS,
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2397): stay LED for fully charged,
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3394): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = -10,
,D/AmoledAdjustTimer( 2397): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4,
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2397): [PWL] Off : 140s ago,
,E/Watchdog( 2397): !@Sync 8,
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2397): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4,
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2397): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED,
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2397): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4,
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2397): waitForAlarm result :8
V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2397): stay LED for fully charged,
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3394): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2397): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/BatteryService( 2397): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2397): !@Sync 9,
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2397): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2397): [PWL] Off : 180s ago,
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2397): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2397): stay LED for fully charged,
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3394): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2397): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4,
,D/TimaService( 2397): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 2397): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2397): TimaServiceHandler.handleMessage what =1,
,I/TLC_TIMA_PKM_initialize( 2397): initializing...,
I/TLC_TIMA_PKM_initialize( 2397): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2397): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2397): input max_sendmsg_size = 262196
,I/TZ: mc_tlc_communication( 2397): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 2397): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2397): process = ffffffff00000000000000000000000a, process_strlen = 32,
I/TZ: mc_tlc_communication( 2397): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2397): aligned max_recvmsg_size = 262208
,I/TZ: mc_tlc_communication( 2397): device_id = 0x0
I/TZ: mc_tlc_communication( 2397): tlc_open() was called
,I/TZ: mc_tlc_communication( 2397): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2397): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 2397): Opening the session
,I/TZ: mc_tlc_communication( 2397): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 2397): Trustlet response is completed,
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2397): stay LED for fully charged
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
D/UiModeManager( 2397): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2397): !@Sync 10,
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0,
,I/TLC_TIMA_PKM_measure_kernel( 2397): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2397): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2397): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/TimaService( 2397): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/AmoledAdjustTimer( 2397): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2397): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4,
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2397): waitForAlarm result :8,
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2397): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED,
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3394): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = -10,
,D/AmoledAdjustTimer( 2397): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2397): [PWL] Off : 225s ago,
,V/AlarmManager( 2397): waitForAlarm result :4,
,V/AlarmManager( 2397): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 7373): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7373):  
,I/SELinux ( 7373): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7373):  
I/SELinux ( 7373):  
I/SELinux ( 7373): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7373): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7373): >>>>> Normal User
,E/dalvikvm( 7373): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
,E/SELinux ( 7373): [DEBUG] seapp_context_lookup: seinfoCategory = default,
,D/TimaKeyStoreProvider( 7373): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7373): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7373): Added TimaKesytore provider,
,D/dalvikvm( 7373): GC_CONCURRENT freed 3009K, 30% free 9557K/13632K, paused 3ms+2ms, total 28ms,
,D/dalvikvm( 7373): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/ActivityManager( 2397): Killing 4927:com.google.android.talk/u0a109 (adj 15): empty #43,
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/BatteryService( 2397): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2397): !@Sync 11,
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2397): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4,
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2397): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2397): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4,
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.,
D/BatteryService( 2397): stay LED for fully charged
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3394): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2397): !@Sync 12,
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2397): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4,
,V/AlarmManager( 2397): waitForAlarm result :4,
,V/AlarmManager( 2397): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 7539): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7539):  
,I/SELinux ( 7539): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7539):  
I/SELinux ( 7539):  
I/SELinux ( 7539): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7539): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 7539): >>>>> Normal User
,E/dalvikvm( 7539): >>>>> com.sec.spp.push:RemoteDlcProcess [ userId:0 | appId:10039 ],
,E/SELinux ( 7539): [DEBUG] seapp_context_lookup: seinfoCategory = samsung,
,D/TimaKeyStoreProvider( 7539): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7539): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7539): Added TimaKesytore provider,
,D/dalvikvm( 7539): GC_CONCURRENT freed 2995K, 30% free 9569K/13632K, paused 3ms+2ms, total 28ms,
,D/dalvikvm( 7539): WAIT_FOR_CONCURRENT_GC blocked 24ms,
,E/SPPClientService( 7539): ============PushLog. commonIsShipBuild. stop!,
,E/SPPClientService( 7539): [PushClientApplication] Push log off : This is Ship build version,
,D/SPPClientService( 7539): PushLog.txt file is not deleted.
D/SPPClientService( 7539): PushLog.txt file is not deleted.,
,D/SPPClientService( 7539): ============PushLog. stop!
,I/ActivityManager( 2397): Killing 5876:com.sec.phone/1001 (adj 15): empty #43,
,E/SPPClientService( 5085): [b] __PingReply__,
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2397): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4,
,D/dalvikvm( 2397): GC_CONCURRENT freed 4219K, 53% free 24799K/52288K, paused 21ms+20ms, total 268ms,
,I/PowerManagerService( 2397): [PWL] Off : 275s ago,
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2397): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2397): !@Sync 13
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2397): !@Sync 14
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,I/PowerManagerService( 2397): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2397): !@Sync 15
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2397): !@Sync 16
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/BatteryService( 2397): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2397): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2397): !@Sync 17
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/BatteryService( 2397): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 2582): GC_CONCURRENT freed 15745K, 34% free 33839K/50644K, paused 20ms+9ms, total 107ms
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2397): !@Sync 18
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2397): [PWL] Off : 455s ago
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2397): !@Sync 19
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/TimaService( 2397): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2397): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2397): TimaServiceHandler.handleMessage what =1
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2397): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2397): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2397): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2397): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2397): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3394): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2397): [PWL] Off : 525s ago
,E/Watchdog( 2397): !@Sync 21
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/GAV2    ( 5200): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5200): Thread[disconnect check,5,main]: Disconnected from service
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2397): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2397): !@Sync 22
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2397): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2397): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2397): <AppSync3 Whitelist>
,V/AlarmManager( 2397): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2397): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2397): !@Sync 23
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2397): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2397): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2397): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2397): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2397): !@Sync 24
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 3752): GC_CONCURRENT freed 2885K, 29% free 9725K/13672K, paused 13ms+3ms, total 82ms
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2397): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2397): !@Sync 25
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2397): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): stay LED for fully charged
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3394): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2397): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/dalvikvm( 2397): GC_CONCURRENT freed 3894K, 52% free 24635K/51208K, paused 18ms+16ms, total 236ms
,I/PowerManagerService( 2397): [PWL] Off : 680s ago
,E/Watchdog( 2397): !@Sync 26
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2397): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2397): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2397): !@Sync 27
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2397): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2397): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2397): !@Sync 28
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2397): mCoverManager.getCoverState() : true
D/BatteryService( 2397): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2397): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2397): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2397): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2397): mCoverManager.getCoverState() : true
D/BatteryService( 2397): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2397): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2397): [PWL] Off : 765s ago
,E/Watchdog( 2397): !@Sync 29
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2397): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2397): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): stay LED for fully charged
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2397): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/TimaService( 2397): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2397): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2397): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2397): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2397): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2397): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2397): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2397): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2397): stay LED for fully charged
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2397): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2397): !@Sync 31
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2397): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2397): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2397): waitForAlarm result :4
,I/SensorManagerA( 2397): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2397): LightSensor setDelay = 200000000
,D/Sensors ( 2397): LightSensor setSensorDelay = 200000000
,D/LightsService( 2397): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2397): Light sensor flush: not enabled 0
D/Sensors ( 2397): LightSensor enable = 1
D/Sensors ( 2397): LightSensor enableSensor = 1
D/SensorManager( 2397): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2397): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Sensors ( 2397): LightSensor enable = 0
,D/Sensors ( 2397): LightSensor enableSensor = 0
D/LightsService( 2397): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 2397): unregisterListener ::   
D/LightsService( 2397): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/ConnectivityService( 2397): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController( 2582): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/STATUSBAR-NetworkController( 2582): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2582): updateDataNetType()
,D/STATUSBAR-NetworkController( 2582): NoService, mRoamingIconId = 0
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2397): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2397): prevTemp = 284, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2397): [PWL] Off : 855s ago
,E/Watchdog( 2397): !@Sync 32
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/BatteryService( 2397): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2397): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2397): waitForAlarm result :8
,E/SPPClientService( 5085): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2397): !@Sync 33
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): stay LED for fully charged
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2397): prevTemp = 284, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2397): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2397): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2397): !@Sync 34
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/BatteryService( 2397): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2397): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/BatteryService( 2397): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2397): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,I/PowerManagerService( 2397): [PWL] Off : 950s ago
,E/Watchdog( 2397): !@Sync 35
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2397): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2397): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/BatteryService( 2397): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2397): prevTemp = 284, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2397): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2397): !@Sync 36
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2397): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2397): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2397): !@Sync 37
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2397): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 284, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2397): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3394): Disconnected process message: 10,
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2397): !@Sync 38
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2397): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2397): GC_CONCURRENT freed 3755K, 52% free 24661K/51208K, paused 8ms+17ms, total 204ms
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2397): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2397): !@Sync 39
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 284, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/BatteryService( 2397): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): stay LED for fully charged
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/TimaService( 2397): TIMA: TimaService scheduler is intialized. 
D/TimaService( 2397): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2397): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2397): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 2397): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2397): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2397): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2397): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/BatteryService( 2397): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 284, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/BatteryService( 2397): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2397): !@Sync 41
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,I/PowerManagerService( 2397): [PWL] Off : 1155s ago
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): stay LED for fully charged
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2397): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2397): !@Sync 42
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 284, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2397): waitForAlarm result :4
,V/AlarmManager( 2397): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): stay LED for fully charged
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SPPClientService( 5085): [b] __PingReply__
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2397): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2397): <AppSync3 Whitelist>
,V/AlarmManager( 2397): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2397): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2397): !@Sync 43
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2397): !@Sync 44
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2397): !@Sync 45
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,I/PowerManagerService( 2397): [PWL] Off : 1265s ago
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/BatteryService( 2397): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2397): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2397): !@Sync 46
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 283, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/BatteryService( 2397): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): stay LED for fully charged
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3394): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2397): !@Sync 47
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/BatteryService( 2397): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 283, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2397): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2397): !@Sync 48
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 3752): GC_CONCURRENT freed 2048K, 29% free 9724K/13672K, paused 4ms+3ms, total 48ms
,D/dalvikvm( 3752): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,V/HeadsetService( 3394): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3394): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime(10291): 
D/AndroidRuntime(10291): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(10291): CheckJNI is OFF
D/AndroidRuntime(10291): setted country_code = Poland
D/AndroidRuntime(10291): setted countryiso_code = PL
D/AndroidRuntime(10291): setted sales_code = PLS
D/AndroidRuntime(10291): readGMSProperty: start
D/AndroidRuntime(10291): readGMSProperty: already setted!!
D/AndroidRuntime(10291): readGMSProperty: end
D/AndroidRuntime(10291): addProductProperty: start
D/dalvikvm(10291): Trying to load lib libjavacore.so 0x0
D/dalvikvm(10291): Added shared lib libjavacore.so 0x0
D/dalvikvm(10291): Trying to load lib libnativehelper.so 0x0
D/dalvikvm(10291): Added shared lib libnativehelper.so 0x0
D/dalvikvm(10291): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/Watchdog( 2397): !@Sync 49
E/memtrack(10291): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug(10291): failed to load memtrack module: -2
D/dalvikvm(10291): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime(10291): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 2397): START PACKAGE DELETE: observer{1124390424}
D/PackageManager( 2397): pkg{<packageName>}
D/PackageManager( 2397): user{0}
D/PackageManager( 2397): deletePackageAsUser : uid = 2000 userId = 0
D/ApplicationPolicy( 2397): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2397): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService( 2397): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2397): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 2397): !@killApplicatoin: 10188, uninstall pkg
I/ActivityManager( 2397): Killing 6909:com.test.thalitest/u0a188 (adj 9): stop com.test.thalitest
W/PackageSettings( 2397): Skipping PackageSetting{42cab090 com.example.hello/10614} due to missing metadata
D/PackageManager( 2397): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10188, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/dalvikvm( 6395): GC_EXPLICIT freed 197K, 29% free 9957K/13848K, paused 5ms+6ms, total 82ms
D/dalvikvm( 6011): GC_EXPLICIT freed 564K, 28% free 9980K/13716K, paused 5ms+25ms, total 94ms
D/dalvikvm( 3269): GC_EXPLICIT freed 352K, 19% free 12231K/15080K, paused 9ms+9ms, total 155ms
D/dalvikvm( 2957): GC_EXPLICIT freed 1437K, 27% free 10020K/13632K, paused 10ms+6ms, total 108ms
D/dalvikvm( 2397): GC_CONCURRENT freed 3731K, 52% free 24745K/51208K, paused 9ms+21ms, total 252ms
D/dalvikvm( 2397): WAIT_FOR_CONCURRENT_GC blocked 123ms
D/dalvikvm( 2397): GC_EXPLICIT freed 116K, 52% free 24629K/51208K, paused 11ms+15ms, total 185ms
D/dalvikvm( 2397): WAIT_FOR_CONCURRENT_GC blocked 298ms
D/PackageManager( 2397): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10188, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/FPMS_FingerprintManagerService( 2603): onReceive: android.intent.action.PACKAGE_REMOVED
I/InputReader( 2397): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 2988): mOCRHelper is null
W/GeofencerStateMachine( 2738): Ignoring removeGeofence because network location is disabled.
D/QuickConnect[1.1][2] ( 4674): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
D/RCPManagerService( 2397): PackageReceiver onReceive()
I/PackageManager( 2397):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2397):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2397):   Scheme: "sms"
I/SELinux (10320): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (10320):  
I/PackageManager( 2397): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/HarmonyEASService( 2397): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/SELinux (10320): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (10320):  
I/SELinux (10320):  
I/SELinux (10320): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (10320): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(10320): >>>>> Normal User
E/dalvikvm(10320): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
E/SELinux (10320): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager( 2397):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2397):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2397):   Scheme: "smsto"
I/PackageManager( 2397): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider(10320): in addTimaSignatureService
D/dalvikvm( 2781): GC_CONCURRENT freed 7668K, 31% free 19461K/28188K, paused 11ms+6ms, total 95ms
D/dalvikvm( 2781): WAIT_FOR_CONCURRENT_GC blocked 62ms
I/PackageManager( 2397):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2397):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2397):   Scheme: "mms"
I/PackageManager( 2397): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider(10320): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(10320): Added TimaKesytore provider
D/RegisteredServicesCache( 2762): empty dynamic service
I/PackageManager( 2397):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2397):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2397):   Scheme: "mmsto"
I/PackageManager( 2397): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2397):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2397):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2397):   Scheme: "sms"
D/EnterpriseDeviceManagerService( 2397): Package has changed for user 0
I/PackageManager( 2397): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm(10320): GC_CONCURRENT freed 2999K, 30% free 9568K/13632K, paused 2ms+8ms, total 26ms
D/dalvikvm(10320): WAIT_FOR_CONCURRENT_GC blocked 23ms
D/dalvikvm( 2397): GC_EXPLICIT freed 707K, 52% free 24764K/51208K, paused 7ms+26ms, total 332ms
I/PackageManager( 2397):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2397): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2397):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2397):   Scheme: "smsto"
D/elm:14132(10320): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132(10320): ELMEngine.ELMEngine( context ).
I/PackageManager( 2397):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2397):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2397):   Scheme: "mms"
D/elm:14132(10320): MDMBridge.setEnterpriseBridge()
I/PackageManager( 2397): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2397):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2397):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2397):   Scheme: "mmsto"
I/PackageManager( 2397): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132(10320): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132(10320): ElmAgentService : onCreate()
D/elm:14132(10320): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132(10320): MainReceiver.listeningToPackageRemoved()
D/elm:14132(10320): MDMBridge.getInstance()
D/elm:14132(10320): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132(10320): MDMBridge.getAllLicenseInfoFromSDK()
W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager( 2397): delete sourFile : 
I/SELinux (10333): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (10333):  
D/elm:14132(10320): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/BackupManagerService( 2397): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 2397): removePackageParticipantsLocked: uid=10188 #1
I/SELinux (10333): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (10333):  
I/SELinux (10333):  
I/SELinux (10333): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (10333): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(10333): >>>>> Normal User
E/dalvikvm(10333): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux (10333): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14132(10320): ElmAgentService : onDestroy().
D/PackageManager( 2397): delete native library directory: 
D/TimaKeyStoreProvider(10333): in addTimaSignatureService
D/AndroidRuntime(10291): Shutting down VM
D/PackageManager( 2397): return delete result to caller: 1124390424
D/PackageManager( 2397): returnCode: 1
D/dalvikvm(10291): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 1ms+1ms, total 4ms
D/TimaKeyStoreProvider(10333): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(10333): Added TimaKesytore provider
W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2397):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2397):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2397):   Scheme: "sms"
I/PackageManager( 2397): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2397):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2397):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2397):   Scheme: "smsto"
I/PackageManager( 2397): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2397):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2397):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2397):   Scheme: "mms"
I/PackageManager( 2397): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2397):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2397):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2397):   Scheme: "mmsto"
I/PackageManager( 2397): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm(10333): GC_CONCURRENT freed 2997K, 30% free 9567K/13632K, paused 3ms+2ms, total 31ms
D/dalvikvm(10333): WAIT_FOR_CONCURRENT_GC blocked 27ms
W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux (10348): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (10348):  
I/ActivityManager( 2397): Killing 5894:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
I/SELinux (10348): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (10348):  
I/SELinux (10348):  
I/SELinux (10348): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (10348): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(10348): >>>>> Normal User
E/dalvikvm(10348): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SELinux (10348): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/TimaKeyStoreProvider(10348): in addTimaSignatureService
W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider(10348): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(10348): Added TimaKesytore provider
W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector( 2397): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 2397): clearDefaults: com.test.thalitest
W/AtomicFile( 2397): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl( 2397): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
D/dalvikvm(10348): GC_CONCURRENT freed 2993K, 30% free 9574K/13636K, paused 2ms+2ms, total 22ms
D/dalvikvm(10348): WAIT_FOR_CONCURRENT_GC blocked 19ms
E/SQLiteDatabase(10348): Failed to open database '/data/data/com.sec.android.app.mss/databases/user.db'.
E/SQLiteDatabase(10348): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10348): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10348): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(10348): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(10348): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10348): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10348): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10348): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(10348): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(10348): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(10348): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(10348): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(10348): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(10348): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase(10348): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase(10348): 	at com.sec.android.app.mss.b.h.b(Unknown Source)
E/SQLiteDatabase(10348): 	at com.sec.android.app.mss.receiver.VerificationReceiver.onReceive(Unknown Source)
E/SQLiteDatabase(10348): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase(10348): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase(10348): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase(10348): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(10348): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(10348): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(10348): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(10348): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(10348): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(10348): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(10348): 	at dalvik.system.NativeStart.main(Native Method)
W/ApplicationsProvider( 2957): Could not fetch usage stats
W/ApplicationsProvider( 2957): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2957): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2957): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2957): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2957): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2957): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2957): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2957): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2957): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2957): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2957): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2957): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/AndroidRuntime(10348): Shutting down VM
W/dalvikvm(10348): threadid=1: thread exiting with uncaught exception (group=0x418cfc08)
E/AndroidRuntime(10348): FATAL EXCEPTION: main
E/AndroidRuntime(10348): Process: com.sec.android.app.mss, PID: 10348
E/AndroidRuntime(10348): java.lang.RuntimeException: Unable to start receiver com.sec.android.app.mss.receiver.VerificationReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10348): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime(10348): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime(10348): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime(10348): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(10348): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(10348): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(10348): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(10348): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(10348): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(10348): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(10348): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(10348): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10348): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(10348): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(10348): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(10348): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(10348): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(10348): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(10348): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(10348): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(10348): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(10348): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(10348): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(10348): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(10348): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime(10348): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime(10348): 	at com.sec.android.app.mss.b.h.b(Unknown Source)
E/AndroidRuntime(10348): 	at com.sec.android.app.mss.receiver.VerificationReceiver.onReceive(Unknown Source)
E/AndroidRuntime(10348): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime(10348): 	... 10 more
I/PCWCLIENTTRACE_PushUtil( 6235): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6235): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6235): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6235): [onReceive] - android.intent.action.PACKAGE_REMOVED
I/Process (10348): Sending signal. PID: 10348 SIG: 9
E/DropBoxManagerService( 2397): Can't write: system_app_crash
E/DropBoxManagerService( 2397): java.io.FileNotFoundException: /data/system/dropbox/drop225.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2397): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2397): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2397): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2397): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2397): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2397): 	... 5 more
I/ActivityManager( 2397): Process com.sec.android.app.mss (pid 10348) (adj 9) has died.
I/SA      ( 5387): [SUR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
I/SA      ( 5387): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package ]
E/SQLiteLog( 5579): (3850) statement aborts at 35: [DELETE FROM app_registry WHERE package_name=? AND plugin_id=? AND sync_status != 170004 AND sync_status = 170002] disk I/O error
W/dalvikvm( 5579): threadid=13: thread exiting with uncaught exception (group=0x418cfc08)
E/AndroidRuntime( 5579): FATAL EXCEPTION: IntentService[HandleAppDataService]
E/AndroidRuntime( 5579): Process: com.sec.android.app.shealth, PID: 5579
E/AndroidRuntime( 5579): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 5579): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 5579): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/AndroidRuntime( 5579): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 5579): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 5579): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/AndroidRuntime( 5579): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericDelete(BaseContentProvider.java:486)
E/AndroidRuntime( 5579): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.delete(BaseContentProvider.java:441)
E/AndroidRuntime( 5579): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 5579): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 5579): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.deleteAppRegistryData(AppRegistryDbManagerWithProvider.java:459)
E/AndroidRuntime( 5579): 	at com.sec.android.app.shealth.service.HandleAppDataService.onHandleIntent(HandleAppDataService.java:56)
E/AndroidRuntime( 5579): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5579): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5579): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 5579): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SharedPreferencesImpl( 3766): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
E/DropBoxManagerService( 2397): Can't write: system_app_crash
E/DropBoxManagerService( 2397): java.io.FileNotFoundException: /data/system/dropbox/drop226.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2397): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2397): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2397): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2397): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2397): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2397): 	... 5 more
I/Process ( 5579): Sending signal. PID: 5579 SIG: 9
I/Icing.InternalIcingCorporaProvider( 6011): Updating corpora: A: com.test.thalitest, C: MAYBE
I/ActivityManager( 2397): Process com.sec.android.app.shealth (pid 5579) (adj 5) has died.
E/SQLiteLog( 6011): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 6011): threadid=10: thread exiting with uncaught exception (group=0x418cfc08)
E/AndroidRuntime( 6011): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 6011): Process: com.google.android.googlequicksearchbox:search, PID: 6011
E/AndroidRuntime( 6011): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6011): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6011): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 6011): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6011): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6011): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 6011): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/AndroidRuntime( 6011): 	at com.google.android.search.core.summons.icing.ApplicationsHelper.updateApplicationsList(ApplicationsHelper.java:171)
E/AndroidRuntime( 6011): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$DatabaseHelper.updateApplications(InternalIcingCorporaProvider.java:511)
E/AndroidRuntime( 6011): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:288)
E/AndroidRuntime( 6011): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AndroidRuntime( 6011): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/AndroidRuntime( 6011): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/AndroidRuntime( 6011): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/AndroidRuntime( 6011): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/AndroidRuntime( 6011): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/AndroidRuntime( 6011): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/AndroidRuntime( 6011): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6011): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6011): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6011): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/SELinux (10372): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (10372):  
I/Process ( 6011): Sending signal. PID: 6011 SIG: 9
E/DropBoxManagerService( 2397): Can't write: system_app_crash
E/DropBoxManagerService( 2397): java.io.FileNotFoundException: /data/system/dropbox/drop227.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2397): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2397): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2397): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2397): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2397): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2397): 	... 5 more
I/ActivityManager( 2397): Process com.google.android.googlequicksearchbox:search (pid 6011) (adj 5) has died.
D/dalvikvm( 1924): GC_EXPLICIT freed 43K, 11% free 9502K/10612K, paused 4ms+4ms, total 38ms
I/SELinux (10372): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (10372):  
I/SELinux (10372):  
I/SELinux (10372): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (10372): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(10372): >>>>> Normal User
E/dalvikvm(10372): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
E/SELinux (10372): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 1924): GC_EXPLICIT freed <1K, 11% free 9502K/10612K, paused 3ms+4ms, total 30ms
D/TimaKeyStoreProvider(10372): in addTimaSignatureService
D/TimaKeyStoreProvider(10372): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(10372): Added TimaKesytore provider
D/dalvikvm( 1924): GC_EXPLICIT freed <1K, 11% free 9502K/10612K, paused 2ms+3ms, total 28ms
D/dalvikvm(10372): GC_CONCURRENT freed 3004K, 30% free 9569K/13636K, paused 2ms+1ms, total 25ms
D/dalvikvm(10372): WAIT_FOR_CONCURRENT_GC blocked 20ms
D/UserAnalysis.PlaceProvider(10372): Create SecureDbHelper
D/UserAnalysis.UserAnalysisBroadcastReceiver(10372): Create SecureDbHelper
E/SQLiteDatabase(10372): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase(10372): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10372): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10372): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(10372): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(10372): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10372): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10372): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10372): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(10372): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(10372): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(10372): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(10372): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(10372): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(10372): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase(10372): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase(10372): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase(10372): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteDatabase(10372): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase(10372): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase(10372): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase(10372): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase(10372): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(10372): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(10372): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(10372): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(10372): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(10372): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(10372): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(10372): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper(10372): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper(10372): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(10372): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(10372): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper(10372): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper(10372): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(10372): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(10372): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(10372): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper(10372): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper(10372): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper(10372): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper(10372): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper(10372): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper(10372): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper(10372): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper(10372): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper(10372): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteOpenHelper(10372): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper(10372): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper(10372): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper(10372): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper(10372): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(10372): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper(10372): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper(10372): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper(10372): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper(10372): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper(10372): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper(10372): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper(10372): Opened privacy in read-only mode
E/SQLiteDatabase(10372): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase(10372): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10372): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10372): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(10372): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(10372): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10372): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10372): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10372): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(10372): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(10372): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(10372): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(10372): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(10372): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(10372): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase(10372): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase(10372): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase(10372): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteDatabase(10372): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase(10372): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase(10372): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase(10372): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase(10372): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(10372): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(10372): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(10372): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(10372): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(10372): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(10372): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(10372): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper(10372): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper(10372): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(10372): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(10372): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper(10372): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper(10372): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(10372): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(10372): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(10372): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper(10372): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper(10372): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper(10372): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper(10372): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper(10372): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper(10372): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper(10372): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper(10372): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper(10372): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteOpenHelper(10372): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper(10372): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper(10372): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper(10372): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper(10372): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper(10372): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper(10372): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper(10372): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper(10372): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper(10372): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper(10372): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper(10372): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper(10372): Opened privacy in read-only mode
E/SQLiteDatabase(10372): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase(10372): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10372): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10372): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(10372): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(10372): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10372): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10372): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10372): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(10372): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(10372): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(10372): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(10372): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(10372): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(10372): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase(10372): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase(10372): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
E/SQLiteDatabase(10372): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase(10372): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase(10372): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase(10372): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase(10372): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(10372): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(10372): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(10372): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(10372): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(10372): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(10372): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(10372): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err(10372): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err(10372): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err(10372): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err(10372): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err(10372): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err(10372): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err(10372): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err(10372): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err(10372): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err(10372): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
W/System.err(10372): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err(10372): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err(10372): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err(10372): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err(10372): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err(10372): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
W/System.err(10372): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
W/System.err(10372): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
W/System.err(10372): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err(10372): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
W/System.err(10372): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(10372): 	at android.os.Looper.loop(Looper.java:146)
W/System.err(10372): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err(10372): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err(10372): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err(10372): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err(10372): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err(10372): 	at dalvik.system.NativeStart.main(Native Method)
W/ContextImpl( 5937): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:165 android.app.ActivityThread.handleReceiver:2698 
D/RCPManager( 6025):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 2397):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 2397): queryAllProviders():  providerCallBack is not register for 0
D/CapabilityManagerService New( 6305): Receiver Broadcast:android.intent.action.PACKAGE_REMOVED
D/CapabilityManagerService New( 6305): The package(com.test.thalitest) removed
W/System.err( 2397): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/System.err( 2397): 	at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
W/System.err( 2397): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
W/System.err( 2397): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
W/System.err( 2397): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
W/System.err( 2397): 	at android.os.Binder.execTransact(Binder.java:404)
W/System.err( 2397): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 2397): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 2397): 	at libcore.io.Posix.open(Native Method)
W/System.err( 2397): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 2397): 	... 8 more
E/SQLiteDatabase( 5937): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 5937): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5937): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5937): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5937): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5937): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5937): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5937): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5937): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5937): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5937): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5937): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5937): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5937): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5937): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5937): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 5937): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
E/SQLiteDatabase( 5937): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5937): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5937): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5937): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 2397): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/System.err( 2397): 	at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
W/System.err( 2397): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
W/System.err( 2397): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
W/System.err( 2397): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
W/System.err( 2397): 	at android.os.Binder.execTransact(Binder.java:404)

```
