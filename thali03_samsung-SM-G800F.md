#### Test 564496604206eac_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system,
D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2397): stay LED for fully charged
D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager( 2397): mCoverManager.getCoverState() : true
--------- beginning of /dev/log/main
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4006): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime( 7200): 
D/AndroidRuntime( 7200): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7200): CheckJNI is OFF
D/AndroidRuntime( 7200): setted country_code = Poland
D/AndroidRuntime( 7200): setted countryiso_code = PL
D/AndroidRuntime( 7200): setted sales_code = PLS
D/AndroidRuntime( 7200): readGMSProperty: start
D/AndroidRuntime( 7200): readGMSProperty: already setted!!
D/AndroidRuntime( 7200): readGMSProperty: end
D/AndroidRuntime( 7200): addProductProperty: start
D/dalvikvm( 7200): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7200): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7200): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7200): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7200): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7200): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7200): failed to load memtrack module: -2
D/dalvikvm( 7200): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7200): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2397): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2397): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2397  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2397): mDVFSHelper.acquire()
I/SELinux ( 7211): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7211):  
D/PointerIcon( 2397): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2397): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2397): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2397): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7200): Shutting down VM
D/dalvikvm( 7200): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+1ms, total 3ms
I/SELinux ( 7211): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7211):  
I/SELinux ( 7211):  
I/SELinux ( 7211): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7211): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7211): >>>>> Normal User
E/dalvikvm( 7211): >>>>> com.test.thalitest [ userId:0 | appId:10653 ]
E/SELinux ( 7211): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7211): in addTimaSignatureService
D/TimaKeyStoreProvider( 7211): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7211): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4162): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4162): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (-2/10)
D/dalvikvm( 7211): GC_CONCURRENT freed 3010K, 32% free 9557K/14004K, paused 2ms+2ms, total 19ms
D/dalvikvm( 7211): WAIT_FOR_CONCURRENT_GC blocked 16ms
V/WebViewChromium( 7211): Binding Chromium to the background looper Looper (main, tid 1) {42a9b330}
I/chromium( 7211): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7211): Initializing chromium process, renderers=0
W/chromium( 7211): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 7211): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7211): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7211): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7211): Mali API Version : 401
,I/Mali    ( 7211): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7211): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7211): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
,D/dalvikvm( 7211): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7211): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7211): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7211): VFY: replacing opcode 0x6e at 0x0008
,D/StatusBarManagerService( 2397): tr p:7211,o:f
D/PhoneStatusBar( 2582): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
W/dalvikvm( 7211): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7211): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7211): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7211): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 7211): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 7211): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7211): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7211): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 7211): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7211): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7211): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 7211): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 7211): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2582): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2397): semi p:7211,o:f
,I/SurfaceFlinger( 1921): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2397): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2397): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2397): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2397): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2397): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2397): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7211): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7211): Enabling debug mode 0
,W/AwContents( 7211): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 7211): showStatusIcon on inactive InputConnection
,D/CustomFrequencyManagerService( 2397): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2397  tag : ACTIVITY_RESUME_BOOSTER@4
,D/CustomFrequencyManagerService( 2397): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2397  pkgName : ACTIVITY_RESUME_BOOSTER@8
,W/ActivityManager( 2397): mDVFSHelper.release()
,D/JsMessageQueue( 7211): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7211): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42a97ad8
,D/dalvikvm( 7211): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42a97ad8
,D/jxcore_app_log( 7211): JniHelper::setJavaVM(0x41fda220), pthread_self() = 1952074680
,I/chromium( 7211): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/dalvikvm( 7211): GC_CONCURRENT freed 1287K, 20% free 11342K/14060K, paused 1ms+2ms, total 24ms
,D/dalvikvm( 7211): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/dalvikvm( 7211): WAIT_FOR_CONCURRENT_GC blocked 10ms
,I/PowerManagerService( 2397): [PWL] Off : 180s ago
,D/dalvikvm( 7211): GC_CONCURRENT freed 1724K, 18% free 15148K/18328K, paused 1ms+3ms, total 41ms
D/dalvikvm( 7211): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 7211): WAIT_FOR_CONCURRENT_GC blocked 32ms
,D/CustomFrequencyManagerService( 2397): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2397  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 7211): GC_FOR_ALLOC freed 5717K, 31% free 16720K/23908K, paused 44ms, total 44ms
,D/dalvikvm( 7211): GC_CONCURRENT freed 6780K, 32% free 18096K/26344K, paused 2ms+11ms, total 76ms
D/dalvikvm( 7211): WAIT_FOR_CONCURRENT_GC blocked 38ms
,D/dalvikvm( 7211): WAIT_FOR_CONCURRENT_GC blocked 50ms
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 330, Delta = 10
,D/AmoledAdjustTimer( 2397): prevTemp = 302, currTemp = 301, prevStep = 4, currStep = 4
,D/dalvikvm( 7211): GC_FOR_ALLOC freed 1153K, 33% free 17812K/26344K, paused 59ms, total 61ms
,I/dalvikvm-heap( 7211): Grow heap (frag case) to 22.307MB for 3688532-byte allocation
,D/dalvikvm( 7211): GC_FOR_ALLOC freed 19K, 29% free 21394K/29948K, paused 57ms, total 57ms
,W/jxcore-log( 7211): Initializing JXcore engine
,W/jxcore-log( 7211): JXcore engine is ready
,W/jxcore-log( 7211): Starting JXcore engine
,W/jxcore-log( 7211): Platform android
W/jxcore-log( 7211): 
,W/jxcore-log( 7211): Process ARCH arm
W/jxcore-log( 7211): 
,I/jxcore-log( 7211): JXcore Cordova bridge is ready!
I/jxcore-log( 7211): 
,W/jxcore-log( 7211): JXcore engine is started
,E/jxcore  ( 7211): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 7211): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 7211): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/PointerIcon( 2397): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2397): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2397): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2397): setHoveringSpenCustomIcon IconType is same.1
I/ActivityManager( 2397): Killing 6202:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,W/PluginManager( 7211): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 23ms. Plugin should use CordovaInterface.getThreadPool().
,D/CustomFrequencyManagerService( 2397): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2397  pkgName : ACTIVITY_RESUME_BOOSTER@4
,I/SurfaceFlinger( 1921): id=19 Removed NainActivit (8/10)
,I/SurfaceFlinger( 1921): id=19 Removed NainActivit (-2/10)
W/ActivityManager( 2397): mDVFSHelper.acquire()
,I/DBG_DM  ( 4750): [3.19.140541][Line:408][onResume] 
,I/DBG_DM  ( 4750): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 32
,I/DBG_DM  ( 4750): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/DBG_DM  ( 4750): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4750): [3.19.140541][Line:418][onResume] Postpone Count : 32
,I/DBG_DM  ( 4750): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/DBG_DM  ( 4750): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 4750): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2397): sendNotification(2) - 4
,I/DBG_DM  ( 4750): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 32
,I/DBG_DM  ( 4750): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4750): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4750): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
D/checkbox( 4750): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4750): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4750): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,D/Activity( 4750): setTransGradationMode to true
D/PhoneStatusBar( 2582): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,I/DBG_DM  ( 4750): [3.19.140541][Line:400][onPause] 
,D/StatusBarManagerService( 2397): semi p:4750,o:t
,I/SurfaceFlinger( 1921): id=20 createSurf (720x1280),2 flag=404, YUIInstallC
D/PointerIcon( 2397): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2397): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2397): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2397): setHoveringSpenCustomIcon IconType is same.1
D/STATUSBAR-StatusBarManagerService( 2397): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2397): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/IInputConnectionWrapper( 7211): showStatusIcon on inactive InputConnection
,D/CustomFrequencyManagerService( 2397): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2397  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2397): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2397): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2397  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/CustomFrequencyManagerService( 2397): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2397  tag : ACTIVITY_RESUME_BOOSTER@8
,D/PackageManager( 2397): [MSG] WRITE_PACKAGE_RESTRICTIONS,
,E/Watchdog( 2397): !@Sync 8,
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2397): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = -10,
,D/AmoledAdjustTimer( 2397): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4,
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2397): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4006): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2397): prevTemp = 301, currTemp = 300, prevStep = 4, currStep = 4,
,V/AlarmManager( 2397): waitForAlarm result :8
V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2397): stay LED for fully charged,
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4006): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2397): !@Sync 9,
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2397): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2397): [PWL] Off : 225s ago,
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2397): stay LED for fully charged
D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4006): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2397): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2397): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,D/TimaService( 2397): TIMA: TimaService scheduler is intialized. ,
,D/TimaService( 2397): TimaServiceHandler.handleMessage what =1
,D/TimaService( 2397): TIMA: checkEvent, operation: 50000 subject: 10000,
,I/TLC_TIMA_PKM_initialize( 2397): initializing...,
I/TLC_TIMA_PKM_initialize( 2397): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 2397): process = ffffffff00000000000000000000000a, process_strlen = 32,
I/TZ: mc_tlc_communication( 2397): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2397): input max_recvmsg_size = 262196
,I/TZ: mc_tlc_communication( 2397): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2397): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2397): aligned max_sendmsg_size = 262208,
I/TZ: mc_tlc_communication( 2397): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 2397): device_id = 0x0,
I/TZ: mc_tlc_communication( 2397): tlc_open() was called
,I/TZ: mc_tlc_communication( 2397): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2397): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 2397): Opening the session,
,I/TZ: mc_tlc_communication( 2397): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 2397): Trustlet response is completed,
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): stay LED for fully charged
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4006): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2397): !@Sync 10,
,I/TLC_TIMA_PKM_measure_kernel( 2397): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2397): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2397): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/TimaService( 2397): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2397): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2397): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4006): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2397): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED,
,D/BatteryService( 2397): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4006): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2397): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4,
,V/AlarmManager( 2397): waitForAlarm result :8,
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2397): [PWL] Off : 275s ago,
,E/Watchdog( 2397): !@Sync 11,
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2397): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,V/AlarmManager( 2397): waitForAlarm result :4,
,V/AlarmManager( 2397): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 7594): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7594):  
,I/SELinux ( 7594): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7594):  
I/SELinux ( 7594):  
I/SELinux ( 7594): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7594): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7594): >>>>> Normal User,
,E/dalvikvm( 7594): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
E/SELinux ( 7594): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 7594): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7594): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7594): Added TimaKesytore provider
,D/dalvikvm( 7594): GC_CONCURRENT freed 3013K, 32% free 9557K/14004K, paused 3ms+3ms, total 28ms
,D/dalvikvm( 7594): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/ActivityManager( 2397): Killing 6271:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2397): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2397): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/BatteryService( 2397): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4006): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2397): !@Sync 12
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,V/AlarmManager( 2397): waitForAlarm result :4
,V/AlarmManager( 2397): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5565): [b] __PingReply__
,I/PowerManagerService( 2397): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2397): !@Sync 13
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/BatteryService( 2397): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4006): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,E/Watchdog( 2397): !@Sync 14
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,I/PowerManagerService( 2397): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/dalvikvm( 2397): GC_CONCURRENT freed 4970K, 73% free 24985K/90092K, paused 25ms+21ms, total 273ms
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4006): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2397): !@Sync 15
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,E/Watchdog( 2397): !@Sync 16
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4006): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2397): stay LED for fully charged
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4006): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2397): [PWL] Off : 455s ago
,E/Watchdog( 2397): !@Sync 17
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4006): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,E/Watchdog( 2397): !@Sync 18
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2397): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4006): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2397): !@Sync 19
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,I/PowerManagerService( 2397): [PWL] Off : 525s ago
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/TimaService( 2397): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2397): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2397): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2397): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2397): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2397): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2397): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2397): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4006): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2397): !@Sync 21
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2397): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,I/PowerManagerService( 2397): [PWL] Off : 600s ago
,V/AlarmManager( 2397): waitForAlarm result :8
,I/SensorManagerA( 2397): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2397): LightSensor setDelay = 200000000
,D/LightsService( 2397): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2397): LightSensor setSensorDelay = 200000000
D/Sensors ( 2397): Light sensor flush: not enabled 0
D/Sensors ( 2397): LightSensor enable = 1
D/Sensors ( 2397): LightSensor enableSensor = 1
D/SensorManager( 2397): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/LightsService( 2397): [SvcLED]  onSensorChanged::light value = 2
D/Sensors ( 2397): LightSensor enable = 0
D/Sensors ( 2397): LightSensor enableSensor = 0
,D/SensorManager( 2397): unregisterListener ::   
D/LightsService( 2397): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,I/GAV2    ( 5657): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5657): Thread[disconnect check,5,main]: Disconnected from service
,E/Watchdog( 2397): !@Sync 22
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2397): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2397): <AppSync3 Whitelist>
,V/AlarmManager( 2397): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4084): GC_CONCURRENT freed 2820K, 31% free 9723K/13976K, paused 13ms+3ms, total 60ms
,E/Watchdog( 2397): !@Sync 23
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/BatteryService( 2397): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4006): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 292, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/BatteryService( 2397): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4006): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,E/Watchdog( 2397): !@Sync 24
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,I/PowerManagerService( 2397): [PWL] Off : 680s ago
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4006): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2397): !@Sync 25
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2397): !@Sync 26
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2397): !@Sync 27
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,I/PowerManagerService( 2397): [PWL] Off : 765s ago
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2397): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4006): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2397): !@Sync 28
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/dalvikvm( 2397): GC_CONCURRENT freed 3909K, 73% free 24852K/90080K, paused 20ms+16ms, total 244ms
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2397): !@Sync 29
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2397): stay LED for fully charged
D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4006): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 2397): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2397): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2397): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2397): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2397): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2397): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2397): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2397): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/BatteryService( 2397): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4006): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/PowerManagerService( 2397): [PWL] Off : 855s ago
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2397): !@Sync 31
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/BatteryService( 2397): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4006): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2397): waitForAlarm result :4
,V/AlarmManager( 2397): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/ConnectivityService( 2397): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController( 2582): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/STATUSBAR-NetworkController( 2582): getUpdateDataNetType() - mDataNetType:0
,D/STATUSBAR-NetworkController( 2582): updateDataNetType()
,D/STATUSBAR-NetworkController( 2582): NoService, mRoamingIconId = 0
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2397): !@Sync 32
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/BatteryService( 2397): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4006): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2397): waitForAlarm result :8
,E/SPPClientService( 5565): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/BatteryService( 2397): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4006): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2397): !@Sync 33
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2397): [PWL] Off : 950s ago
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4006): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2397): !@Sync 34
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2397): stay LED for fully charged
D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4006): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2397): !@Sync 35
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4006): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/BatteryService( 2397): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4006): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2397): !@Sync 36
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2397): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2397): !@Sync 37
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4006): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2397): !@Sync 38
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4006): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2397): !@Sync 39
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/TimaService( 2397): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2397): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2397): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2397): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 2397): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2397): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2397): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2397): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4006): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2397): [PWL] Off : 1155s ago
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/BatteryService( 2397): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4006): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4006): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2397): !@Sync 41
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2397): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4006): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2397): !@Sync 42
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/dalvikvm( 2397): GC_CONCURRENT freed 3751K, 73% free 24877K/90080K, paused 24ms+20ms, total 251ms
,V/AlarmManager( 2397): waitForAlarm result :4
,I/SensorManagerA( 2397): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2397): LightSensor setDelay = 200000000
,D/LightsService( 2397): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2397): LightSensor setSensorDelay = 200000000
D/Sensors ( 2397): Light sensor flush: not enabled 0
D/Sensors ( 2397): LightSensor enable = 1
D/Sensors ( 2397): LightSensor enableSensor = 1
D/SensorManager( 2397): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2397): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Sensors ( 2397): LightSensor enable = 0
,D/Sensors ( 2397): LightSensor enableSensor = 0
,D/SensorManager( 2397): unregisterListener ::   
D/LightsService( 2397): [SvcLED]  onSensorChanged::light value = 7
D/LightsService( 2397): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SPPClientService( 5565): [b] __PingReply__
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2397): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2397): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,V/AlarmManager( 2397): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2397): !@Sync 43
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4006): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/BatteryService( 2397): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4006): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2397): [PWL] Off : 1265s ago
,E/Watchdog( 2397): !@Sync 44
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4006): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 288, currTemp = 290, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4006): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2397): !@Sync 45
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2397): !@Sync 46
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4006): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2397): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4006): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/dalvikvm( 4084): GC_CONCURRENT freed 2050K, 31% free 9721K/13976K, paused 7ms+2ms, total 73ms
,E/Watchdog( 2397): !@Sync 47
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/BatteryService( 2397): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4006): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/BatteryService( 2397): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4006): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2397): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2397): !@Sync 48
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/BatteryService( 2397): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4006): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,D/BatteryService( 2397): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4006): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 287, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2397): waitForAlarm result :8
,V/AlarmManager( 2397): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2397): !@Sync 49
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2397): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1200000ms)
```
