#### Test 56449660bb41d23_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system,
D/BatteryService( 2393): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2393): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2393): stay LED for fully charged
--------- beginning of /dev/log/main
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2393): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4002): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime( 7184): 
D/AndroidRuntime( 7184): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7184): CheckJNI is OFF
D/AndroidRuntime( 7184): setted country_code = Poland
D/AndroidRuntime( 7184): setted countryiso_code = PL
D/AndroidRuntime( 7184): setted sales_code = PLS
D/AndroidRuntime( 7184): readGMSProperty: start
D/AndroidRuntime( 7184): readGMSProperty: already setted!!
D/AndroidRuntime( 7184): readGMSProperty: end
D/AndroidRuntime( 7184): addProductProperty: start
D/dalvikvm( 7184): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7184): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7184): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7184): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7184): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7184): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7184): failed to load memtrack module: -2
D/dalvikvm( 7184): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7184): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2393): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2393): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2393  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2393): mDVFSHelper.acquire()
I/SELinux ( 7211): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7211):  
D/PointerIcon( 2393): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2393): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2393): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2393): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7184): Shutting down VM
D/dalvikvm( 7184): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+0ms, total 4ms
I/SELinux ( 7211): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7211):  
I/SELinux ( 7211):  
I/SELinux ( 7211): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7211): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7211): >>>>> Normal User
E/dalvikvm( 7211): >>>>> com.test.thalitest [ userId:0 | appId:10644 ]
E/SELinux ( 7211): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7211): in addTimaSignatureService
D/TimaKeyStoreProvider( 7211): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7211): Added TimaKesytore provider
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (-2/10)
I/SQLiteSecureOpenHelper( 4161): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4161): getDatabaseLocked(b,b,pwd)...
D/dalvikvm( 7211): GC_CONCURRENT freed 3005K, 32% free 9561K/13892K, paused 2ms+1ms, total 18ms
D/dalvikvm( 7211): WAIT_FOR_CONCURRENT_GC blocked 17ms
V/WebViewChromium( 7211): Binding Chromium to the background looper Looper (main, tid 1) {4229c110}
I/chromium( 7211): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7211): Initializing chromium process, renderers=0
W/chromium( 7211): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 7211): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7211): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7211): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7211): Mali API Version : 401
,I/Mali    ( 7211): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7211): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7211): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7211): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7211): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7211): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7211): VFY: replacing opcode 0x6e at 0x0008
,D/StatusBarManagerService( 2393): tr p:7211,o:f
D/PhoneStatusBar( 2583): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,W/dalvikvm( 7211): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7211): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7211): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7211): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 7211): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 7211): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7211): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7211): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 7211): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7211): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7211): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 7211): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 7211): CordovaWebView is running on device made by: samsung
,D/StatusBarManagerService( 2393): semi p:7211,o:f
D/PhoneStatusBar( 2583): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,I/SurfaceFlinger( 1920): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2393): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2393): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2393): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2393): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2393): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2393): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7211): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7211): Enabling debug mode 0
,W/AwContents( 7211): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2393): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/CustomFrequencyManagerService( 2393): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2393  tag : ACTIVITY_RESUME_BOOSTER@4
,W/AwContents( 7211): nativeOnDraw failed; clearing to background color.
W/ActivityManager( 2393): mDVFSHelper.release()
D/CustomFrequencyManagerService( 2393): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2393  pkgName : ACTIVITY_RESUME_BOOSTER@8
,W/IInputConnectionWrapper( 7211): showStatusIcon on inactive InputConnection
,E/Watchdog( 2393): !@Sync 8
,D/JsMessageQueue( 7211): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7211): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42294680
,D/dalvikvm( 7211): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42294680
D/jxcore_app_log( 7211): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2028038008
I/chromium( 7211): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/dalvikvm( 7211): GC_CONCURRENT freed 1288K, 19% free 11345K/13952K, paused 1ms+2ms, total 23ms
D/dalvikvm( 7211): WAIT_FOR_CONCURRENT_GC blocked 12ms
D/dalvikvm( 7211): WAIT_FOR_CONCURRENT_GC blocked 6ms
D/dalvikvm( 7211): GC_CONCURRENT freed 1723K, 17% free 15151K/18220K, paused 1ms+4ms, total 40ms
D/dalvikvm( 7211): WAIT_FOR_CONCURRENT_GC blocked 19ms
D/dalvikvm( 7211): WAIT_FOR_CONCURRENT_GC blocked 31ms
D/CustomFrequencyManagerService( 2393): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2393  tag : ACTIVITY_RESUME_BOOSTER@8
D/SSRMv2:SIOP( 2393): SIOP:: AP = 320, Delta = 0
,D/dalvikvm( 7211): GC_FOR_ALLOC freed 5737K, 30% free 16765K/23856K, paused 53ms, total 55ms
,D/AmoledAdjustTimer( 2393): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,D/dalvikvm( 7211): GC_CONCURRENT freed 6775K, 31% free 18145K/26276K, paused 3ms+14ms, total 89ms
,D/dalvikvm( 7211): WAIT_FOR_CONCURRENT_GC blocked 67ms
,D/dalvikvm( 7211): WAIT_FOR_CONCURRENT_GC blocked 54ms
,D/dalvikvm( 7211): GC_FOR_ALLOC freed 1045K, 32% free 17969K/26276K, paused 53ms, total 53ms
,I/dalvikvm-heap( 7211): Grow heap (frag case) to 22.352MB for 3688532-byte allocation
,D/dalvikvm( 7211): GC_FOR_ALLOC freed 41K, 28% free 21530K/29880K, paused 52ms, total 52ms
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
,D/PointerIcon( 2393): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2393): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2393): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2393): setHoveringSpenCustomIcon IconType is same.1
,I/ActivityManager( 2393): Killing 6170:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,W/PluginManager( 7211): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 26ms. Plugin should use CordovaInterface.getThreadPool().
,D/CustomFrequencyManagerService( 2393): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2393  pkgName : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2393): mDVFSHelper.acquire()
,I/SurfaceFlinger( 1920): id=19 Removed NainActivit (8/10)
,I/SurfaceFlinger( 1920): id=19 Removed NainActivit (-2/10)
,I/DBG_DM  ( 4735): [3.19.140541][Line:408][onResume] 
,I/DBG_DM  ( 4735): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 30
,I/DBG_DM  ( 4735): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/DBG_DM  ( 4735): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4735): [3.19.140541][Line:418][onResume] Postpone Count : 30
,I/DBG_DM  ( 4735): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/DBG_DM  ( 4735): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 4735): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2393): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2393): sendNotification(2) - 4
,I/DBG_DM  ( 4735): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 30
,I/DBG_DM  ( 4735): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4735): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4735): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
,D/checkbox( 4735): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4735): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4735): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,D/Activity( 4735): setTransGradationMode to true
,D/PhoneStatusBar( 2583): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,I/DBG_DM  ( 4735): [3.19.140541][Line:400][onPause] 
,D/StatusBarManagerService( 2393): semi p:4735,o:t
,I/SurfaceFlinger( 1920): id=20 createSurf (720x1280),2 flag=404, YUIInstallC
D/STATUSBAR-StatusBarManagerService( 2393): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2393): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2393): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2393): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2393): setHoveringSpenCustomIcon IconType is same.1
D/STATUSBAR-StatusBarManagerService( 2393): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,W/IInputConnectionWrapper( 7211): showStatusIcon on inactive InputConnection
W/ContextImpl( 2393): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/CustomFrequencyManagerService( 2393): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2393  tag : ACTIVITY_RESUME_BOOSTER@4
,D/CustomFrequencyManagerService( 2393): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2393  pkgName : ACTIVITY_RESUME_BOOSTER@8
,W/ActivityManager( 2393): mDVFSHelper.release()
,W/ContextImpl( 2393): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/CustomFrequencyManagerService( 2393): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2393  tag : ACTIVITY_RESUME_BOOSTER@8
,D/PackageManager( 2393): [MSG] WRITE_PACKAGE_RESTRICTIONS,
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2393): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4,
,D/BatteryService( 2393): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2393): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2393): stay LED for fully charged
,D/UiModeManager( 2393): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2393): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4,
,W/ContextImpl( 2393): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 2393): !@Sync 9,
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2393): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2393): [PWL] Off : 225s ago,
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2393): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,V/AlarmManager( 2393): waitForAlarm result :8,
,V/AlarmManager( 2393): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,W/ContextImpl( 2393): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2393): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,D/TimaService( 2393): TIMA: TimaService scheduler is intialized. ,
,D/TimaService( 2393): TimaServiceHandler.handleMessage what =1,
,D/TimaService( 2393): TIMA: checkEvent, operation: 50000 subject: 10000,
,I/TLC_TIMA_PKM_initialize( 2393): initializing...,
I/TLC_TIMA_PKM_initialize( 2393): root = 0, root_strlen = 1,
,I/TLC_TIMA_PKM_initialize( 2393): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 2393): input max_sendmsg_size = 262196
,I/TZ: mc_tlc_communication( 2393): input max_recvmsg_size = 262196
,I/TZ: mc_tlc_communication( 2393): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2393): process = ffffffff00000000000000000000000a, process_strlen = 32,
I/TZ: mc_tlc_communication( 2393): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2393): aligned max_recvmsg_size = 262208
,I/TZ: mc_tlc_communication( 2393): device_id = 0x0
I/TZ: mc_tlc_communication( 2393): tlc_open() was called,
,I/TZ: mc_tlc_communication( 2393): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2393): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 2393): Opening the session
,I/TZ: mc_tlc_communication( 2393): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 2393): Trustlet response is completed
,E/Watchdog( 2393): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel( 2393): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2393): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2393): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2393): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2393): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,D/dalvikvm( 2393): GC_CONCURRENT freed 4728K, 75% free 25086K/98208K, paused 19ms+24ms, total 272ms
,W/ContextImpl( 2393): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2393): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2393): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2393): stay LED for fully charged
,D/UiModeManager( 2393): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2393): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2393): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4,
,W/ContextImpl( 2393): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2393): [PWL] Off : 275s ago,
,E/Watchdog( 2393): !@Sync 11,
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2393): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4,
,V/AlarmManager( 2393): waitForAlarm result :4,
,V/AlarmManager( 2393): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 7619): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7619):  
,I/SELinux ( 7619): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7619):  
I/SELinux ( 7619):  
,I/SELinux ( 7619): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7619): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7619): >>>>> Normal User
,E/dalvikvm( 7619): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
,E/SELinux ( 7619): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 7619): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7619): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7619): Added TimaKesytore provider
,D/dalvikvm( 7619): GC_CONCURRENT freed 3009K, 32% free 9560K/13892K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 7619): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/ActivityManager( 2393): Killing 6242:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,D/BatteryService( 2393): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2393): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2393): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate,
D/UiModeManager( 2393): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2393): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4,
,V/AlarmManager( 2393): waitForAlarm result :8,
,V/AlarmManager( 2393): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,W/ContextImpl( 2393): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,E/Watchdog( 2393): !@Sync 12
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2393): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2393): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,V/AlarmManager( 2393): waitForAlarm result :4
,V/AlarmManager( 2393): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5535): [b] __PingReply__
,I/PowerManagerService( 2393): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2393): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2393): !@Sync 13
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/BatteryService( 2393): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2393): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2393): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2393): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2393): waitForAlarm result :8
,V/AlarmManager( 2393): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2393): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2393): !@Sync 14
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2393): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,I/PowerManagerService( 2393): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2393): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2393): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2393): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2393): mCoverManager.getCoverState() : true
,D/BatteryService( 2393): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2393): !@Sync 15
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2393): waitForAlarm result :8
,V/AlarmManager( 2393): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2393): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2393): !@Sync 16
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2393): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2393): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2393): [PWL] Off : 455s ago
,E/Watchdog( 2393): !@Sync 17
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2393): waitForAlarm result :8
,V/AlarmManager( 2393): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2393): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2393): !@Sync 18
,D/BatteryService( 2393): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2393): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2393): mCoverManager.getCoverState() : true
D/BatteryService( 2393): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2393): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2393): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2393): !@Sync 19
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2393): [PWL] Off : 525s ago
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2393): waitForAlarm result :8
,V/AlarmManager( 2393): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2393): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/TimaService( 2393): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2393): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2393): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2393): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2393): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2393): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2393): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2393): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2393): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2393): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2393): !@Sync 21
,D/BatteryService( 2393): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2393): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2393): stay LED for fully charged
,D/UiModeManager( 2393): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2393): waitForAlarm result :8
,V/AlarmManager( 2393): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2393): [PWL] Off : 600s ago,
,V/AlarmManager( 2393): waitForAlarm result :8
,I/SensorManagerA( 2393): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2393): LightSensor setDelay = 200000000
,D/LightsService( 2393): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2393): LightSensor setSensorDelay = 200000000
D/Sensors ( 2393): Light sensor flush: not enabled 0
D/Sensors ( 2393): LightSensor enable = 1
D/Sensors ( 2393): LightSensor enableSensor = 1
D/SensorManager( 2393): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors ( 2393): LightSensor enable = 0
D/Sensors ( 2393): LightSensor enableSensor = 0
,D/SensorManager( 2393): unregisterListener ::   
D/LightsService( 2393): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2393): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/GAV2    ( 5626): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5626): Thread[disconnect check,5,main]: Disconnected from service
,E/Watchdog( 2393): !@Sync 22
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2393): !@Sync 23
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2393): waitForAlarm result :8
,V/AlarmManager( 2393): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2393): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2393): <AppSync3 Whitelist>
,V/AlarmManager( 2393): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2583): GC_CONCURRENT freed 15744K, 34% free 33861K/50924K, paused 29ms+8ms, total 172ms
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2393): !@Sync 24
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/dalvikvm( 2393): GC_CONCURRENT freed 4160K, 75% free 24763K/97912K, paused 20ms+16ms, total 249ms
,I/PowerManagerService( 2393): [PWL] Off : 680s ago
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2393): !@Sync 25
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2393): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2393): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2393): mCoverManager.getCoverState() : true
,D/BatteryService( 2393): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2393): waitForAlarm result :8
,V/AlarmManager( 2393): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4078): GC_CONCURRENT freed 2882K, 31% free 9727K/13932K, paused 21ms+3ms, total 89ms
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2393): !@Sync 26
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2393): !@Sync 27
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2393): [PWL] Off : 765s ago
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2393): waitForAlarm result :8
,V/AlarmManager( 2393): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2393): !@Sync 28
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2393): !@Sync 29
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2393): waitForAlarm result :8
,V/AlarmManager( 2393): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/TimaService( 2393): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2393): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2393): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2393): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2393): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2393): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2393): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2393): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 2393): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2393): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2393): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2393): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2393): [PWL] Off : 855s ago
,D/BatteryService( 2393): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2393): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2393): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService( 2393): stay LED for fully charged
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2393): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2393): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2393): stay LED for fully charged
,D/UiModeManager( 2393): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2393): !@Sync 31
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2393): waitForAlarm result :8
,V/AlarmManager( 2393): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2393): waitForAlarm result :4
,V/AlarmManager( 2393): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/ConnectivityService( 2393): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController( 2583): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/STATUSBAR-NetworkController( 2583): getUpdateDataNetType() - mDataNetType:0
,D/STATUSBAR-NetworkController( 2583): updateDataNetType()
,D/STATUSBAR-NetworkController( 2583): NoService, mRoamingIconId = 0
,D/BatteryService( 2393): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2393): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2393): mCoverManager.getCoverState() : true
,D/BatteryService( 2393): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2393): !@Sync 32
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2393): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2393): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2393): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2393): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2393): waitForAlarm result :8
,E/SPPClientService( 5535): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/BatteryService( 2393): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2393): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2393): mCoverManager.getCoverState() : true
,D/BatteryService( 2393): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2393): !@Sync 33
,D/BatteryService( 2393): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2393): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2393): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2393): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2393): [PWL] Off : 950s ago
,V/AlarmManager( 2393): waitForAlarm result :8
,V/AlarmManager( 2393): ClockReceiver onReceive() ACTION_TIME_TICK
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/AmoledAdjustTimer( 2393): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2393): !@Sync 34
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2393): !@Sync 35
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2393): waitForAlarm result :8
,V/AlarmManager( 2393): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2393): !@Sync 36
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2393): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2393): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2393): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2393): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/BatteryService( 2393): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2393): !@Sync 37
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2393): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2393): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2393): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2393): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2393): waitForAlarm result :8
,V/AlarmManager( 2393): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2393): !@Sync 38
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/dalvikvm( 2393): GC_CONCURRENT freed 3733K, 75% free 24757K/97912K, paused 21ms+18ms, total 259ms
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2393): !@Sync 39
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2393): waitForAlarm result :8
,V/AlarmManager( 2393): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/TimaService( 2393): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2393): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2393): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2393): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 2393): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2393): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2393): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2393): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2393): [PWL] Off : 1155s ago
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2393): !@Sync 41
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2393): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2393): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2393): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/BatteryService( 2393): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2393): waitForAlarm result :8
,V/AlarmManager( 2393): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2393): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2393): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2393): mCoverManager.getCoverState() : true
,D/BatteryService( 2393): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 285, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2393): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2393): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2393): stay LED for fully charged
,D/UiModeManager( 2393): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2393): !@Sync 42
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2393): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2393): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2393): stay LED for fully charged
,D/UiModeManager( 2393): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2393): waitForAlarm result :4
,D/LightsService( 2393): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2393): getReportingMode :: sensor.mType = 5
D/Sensors ( 2393): LightSensor setDelay = 200000000
D/Sensors ( 2393): LightSensor setSensorDelay = 200000000
D/Sensors ( 2393): Light sensor flush: not enabled 0
D/Sensors ( 2393): LightSensor enable = 1
D/Sensors ( 2393): LightSensor enableSensor = 1
,D/SensorManager( 2393): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
V/AlarmManager( 2393): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Sensors ( 2393): LightSensor enable = 0
,D/Sensors ( 2393): LightSensor enableSensor = 0
,D/SensorManager( 2393): unregisterListener ::   
D/LightsService( 2393): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2393): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SPPClientService( 5535): [b] __PingReply__
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2393): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2393): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2393): mCoverManager.getCoverState() : true
,D/BatteryService( 2393): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2393): !@Sync 43
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2393): waitForAlarm result :8
,V/AlarmManager( 2393): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2393): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2393): <AppSync3 Whitelist>
,V/AlarmManager( 2393): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2393): [PWL] Off : 1265s ago
,E/Watchdog( 2393): !@Sync 44
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2393): !@Sync 45
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2393): waitForAlarm result :8
,V/AlarmManager( 2393): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2393): !@Sync 46
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2393): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2393): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2393): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2393): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2393): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2393): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2393): mCoverManager.getCoverState() : true
,D/BatteryService( 2393): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2393): !@Sync 47
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2393): waitForAlarm result :8
,V/AlarmManager( 2393): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2393): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2393): !@Sync 48
,D/SSRMv2:SIOP( 2393): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2393): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1200000ms)
```
