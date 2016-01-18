#### Test 563583788793eb6_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system
D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2411): stay LED for fully charged
,--------- beginning of /dev/log/main
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2411): mCoverManager.getCoverState() : true
V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4003): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime( 7148): 
D/AndroidRuntime( 7148): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7148): CheckJNI is OFF
D/AndroidRuntime( 7148): setted country_code = Poland
D/AndroidRuntime( 7148): setted countryiso_code = PL
D/AndroidRuntime( 7148): setted sales_code = PLS
D/AndroidRuntime( 7148): readGMSProperty: start
D/AndroidRuntime( 7148): readGMSProperty: already setted!!
D/AndroidRuntime( 7148): readGMSProperty: end
D/AndroidRuntime( 7148): addProductProperty: start
D/dalvikvm( 7148): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7148): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7148): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7148): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7148): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7148): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7148): failed to load memtrack module: -2
D/dalvikvm( 7148): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7148): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2411): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2411): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2411  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2411): mDVFSHelper.acquire()
I/SELinux ( 7160): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7160):  
D/PointerIcon( 2411): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2411): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2411): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2411): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7148): Shutting down VM
D/dalvikvm( 7148): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+0ms, total 4ms
I/SELinux ( 7160): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7160):  
I/SELinux ( 7160):  
I/SELinux ( 7160): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7160): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7160): >>>>> Normal User
E/dalvikvm( 7160): >>>>> com.test.thalitest [ userId:0 | appId:10636 ]
E/SELinux ( 7160): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7160): in addTimaSignatureService
D/TimaKeyStoreProvider( 7160): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7160): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4177): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4177): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (-2/10)
D/dalvikvm( 7160): GC_CONCURRENT freed 3006K, 31% free 9565K/13852K, paused 2ms+1ms, total 19ms
D/dalvikvm( 7160): WAIT_FOR_CONCURRENT_GC blocked 16ms
V/WebViewChromium( 7160): Binding Chromium to the background looper Looper (main, tid 1) {42291260}
I/chromium( 7160): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7160): Initializing chromium process, renderers=0
W/chromium( 7160): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 7160): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7160): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7160): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7160): Mali API Version : 401
,I/Mali    ( 7160): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7160): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7160): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
,D/dalvikvm( 7160): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7160): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7160): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7160): VFY: replacing opcode 0x6e at 0x0008
,D/StatusBarManagerService( 2411): tr p:7160,o:f
D/PhoneStatusBar( 2581): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,W/dalvikvm( 7160): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 7160): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7160): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7160): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 7160): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 7160): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7160): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7160): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 7160): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7160): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7160): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 7160): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 7160): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2581): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2411): semi p:7160,o:f
,I/SurfaceFlinger( 1921): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2411): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2411): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2411): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2411): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2411): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2411): setHoveringSpenCustomIcon IconType is same.1
I/HWUI    ( 7160): EGLImpl-HWUI Protected EGL context created
D/OpenGLRenderer( 7160): Enabling debug mode 0
W/AwContents( 7160): nativeOnDraw failed; clearing to background color.
W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
D/CustomFrequencyManagerService( 2411): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2411  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2411): mDVFSHelper.release()
D/CustomFrequencyManagerService( 2411): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2411  pkgName : ACTIVITY_RESUME_BOOSTER@8
W/AwContents( 7160): nativeOnDraw failed; clearing to background color.
W/IInputConnectionWrapper( 7160): showStatusIcon on inactive InputConnection
D/JsMessageQueue( 7160): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 7160): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422891c0
D/dalvikvm( 7160): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422891c0
D/jxcore_app_log( 7160): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2028046160
I/chromium( 7160): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/dalvikvm( 7160): GC_CONCURRENT freed 1290K, 19% free 11348K/13916K, paused 2ms+2ms, total 24ms
D/dalvikvm( 7160): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/dalvikvm( 7160): GC_CONCURRENT freed 1730K, 17% free 15163K/18196K, paused 2ms+3ms, total 39ms
D/dalvikvm( 7160): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/dalvikvm( 7160): WAIT_FOR_CONCURRENT_GC blocked 28ms
,W/PluginManager( 7160): THREAD WARNING: exec() call to JXcore.isReady blocked the main thread for 38ms. Plugin should use CordovaInterface.getThreadPool().
,D/CustomFrequencyManagerService( 2411): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2411  tag : ACTIVITY_RESUME_BOOSTER@8
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 303, currTemp = 302, prevStep = 4, currStep = 4
,D/dalvikvm( 7160): GC_FOR_ALLOC freed 5739K, 30% free 16767K/23820K, paused 47ms, total 47ms
,D/dalvikvm( 7160): GC_CONCURRENT freed 6774K, 31% free 18148K/26236K, paused 3ms+9ms, total 58ms
,D/dalvikvm( 7160): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/dalvikvm( 7160): WAIT_FOR_CONCURRENT_GC blocked 36ms
,D/dalvikvm( 7160): GC_FOR_ALLOC freed 1062K, 32% free 17961K/26236K, paused 61ms, total 61ms
,I/dalvikvm-heap( 7160): Grow heap (frag case) to 22.304MB for 3688532-byte allocation
,D/dalvikvm( 7160): GC_FOR_ALLOC freed 2404K, 36% free 19158K/29840K, paused 62ms, total 62ms
,D/dalvikvm( 7160): GC_FOR_ALLOC freed 2242K, 36% free 19203K/29840K, paused 52ms, total 52ms
,W/jxcore-log( 7160): Initializing JXcore engine
,W/jxcore-log( 7160): JXcore engine is ready
,W/jxcore-log( 7160): Starting JXcore engine
,W/jxcore-log( 7160): Platform android
W/jxcore-log( 7160): 
,W/jxcore-log( 7160): Process ARCH arm
W/jxcore-log( 7160): 
,I/jxcore-log( 7160): JXcore Cordova bridge is ready!
I/jxcore-log( 7160): 
,W/jxcore-log( 7160): JXcore engine is started
,E/jxcore  ( 7160): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 7160): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 7160): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/PointerIcon( 2411): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2411): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2411): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2411): setHoveringSpenCustomIcon IconType is same.1
,I/ActivityManager( 2411): Killing 6153:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
W/PluginManager( 7160): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 19ms. Plugin should use CordovaInterface.getThreadPool().
,D/CustomFrequencyManagerService( 2411): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2411  pkgName : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2411): mDVFSHelper.acquire()
I/SurfaceFlinger( 1921): id=19 Removed NainActivit (8/10)
I/SurfaceFlinger( 1921): id=19 Removed NainActivit (-2/10)
,I/DBG_DM  ( 4732): [3.19.140541][Line:408][onResume] 
,I/DBG_DM  ( 4732): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 30
,I/DBG_DM  ( 4732): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/DBG_DM  ( 4732): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4732): [3.19.140541][Line:418][onResume] Postpone Count : 30
,I/DBG_DM  ( 4732): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/DBG_DM  ( 4732): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 4732): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,I/DBG_DM  ( 4732): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 30
D/STATUSBAR-StatusBarManagerService( 2411): sendNotification(2) - 4
,I/DBG_DM  ( 4732): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4732): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4732): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
D/checkbox( 4732): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4732): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4732): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
D/Activity( 4732): setTransGradationMode to true
,D/PhoneStatusBar( 2581): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,I/DBG_DM  ( 4732): [3.19.140541][Line:400][onPause] 
,D/StatusBarManagerService( 2411): semi p:4732,o:t
,I/SurfaceFlinger( 1921): id=20 createSurf (720x1280),2 flag=404, YUIInstallC
D/STATUSBAR-StatusBarManagerService( 2411): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/STATUSBAR-StatusBarManagerService( 2411): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2411): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2411): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2411): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2411): setHoveringSpenCustomIcon IconType is same.1
,W/IInputConnectionWrapper( 7160): showStatusIcon on inactive InputConnection
W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/CustomFrequencyManagerService( 2411): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2411  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2411): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2411): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2411  pkgName : ACTIVITY_RESUME_BOOSTER@8
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/CustomFrequencyManagerService( 2411): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2411  tag : ACTIVITY_RESUME_BOOSTER@8
,D/PackageManager( 2411): [MSG] WRITE_PACKAGE_RESTRICTIONS,
,E/Watchdog( 2411): !@Sync 9,
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2411): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2411): [PWL] Off : 225s ago,
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2411): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10,
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2411): prevTemp = 302, currTemp = 301, prevStep = 4, currStep = 4,
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2411): waitForAlarm result :8,
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2411): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4,
,D/TimaService( 2411): TIMA: TimaService scheduler is intialized. ,
,D/TimaService( 2411): TimaServiceHandler.handleMessage what =1
,D/TimaService( 2411): TIMA: checkEvent, operation: 50000 subject: 10000,
,I/TLC_TIMA_PKM_initialize( 2411): initializing...,
I/TLC_TIMA_PKM_initialize( 2411): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2411): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2411): input max_sendmsg_size = 262196
,I/TZ: mc_tlc_communication( 2411): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 2411): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2411): process = ffffffff00000000000000000000000a, process_strlen = 32,
I/TZ: mc_tlc_communication( 2411): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2411): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 2411): device_id = 0x0,
I/TZ: mc_tlc_communication( 2411): tlc_open() was called
,I/TZ: mc_tlc_communication( 2411): Opening MobiCore device
,I/TZ: mc_tlc_communication( 2411): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 2411): Opening the session,
,I/TZ: mc_tlc_communication( 2411): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 2411): Trustlet response is completed,
,E/Watchdog( 2411): !@Sync 10,
,I/TLC_TIMA_PKM_measure_kernel( 2411): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2411): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2411): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/TimaService( 2411): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2411): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4,
,D/dalvikvm( 2411): GC_CONCURRENT freed 4703K, 73% free 25016K/89832K, paused 19ms+21ms, total 272ms
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = -10,
,D/AmoledAdjustTimer( 2411): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2411): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4,
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2411): [PWL] Off : 275s ago,
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2411): !@Sync 11,
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2411): prevTemp = 301, currTemp = 300, prevStep = 4, currStep = 4,
,V/AlarmManager( 2411): waitForAlarm result :4,
,V/AlarmManager( 2411): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 7468): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7468):  
,V/AlarmManager( 2411): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 7468): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7468):  
I/SELinux ( 7468):  
I/SELinux ( 7468): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7468): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7468): >>>>> Normal User
,E/dalvikvm( 7468): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ],
,E/SELinux ( 7468): [DEBUG] seapp_context_lookup: seinfoCategory = default,
,D/TimaKeyStoreProvider( 7468): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7468): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7468): Added TimaKesytore provider,
,D/dalvikvm( 7468): GC_CONCURRENT freed 3009K, 31% free 9565K/13852K, paused 3ms+2ms, total 28ms,
,D/dalvikvm( 7468): WAIT_FOR_CONCURRENT_GC blocked 24ms,
,I/ActivityManager( 2411): Killing 6223:com.sec.android.app.music:service/u0a152 (adj 15): empty #43,
,I/EventLogService( 3434): Aggregate from 1453132596158 (log), 1453132596158 (data),
,D/dalvikvm( 3434): GC_CONCURRENT freed 1751K, 20% free 12669K/15704K, paused 6ms+8ms, total 89ms,
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2411): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4,
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2411): waitForAlarm result :8,
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2411): stay LED for fully charged
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2411): !@Sync 12
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :4
,V/AlarmManager( 2411): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5517): [b] __PingReply__
,I/PowerManagerService( 2411): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2411): !@Sync 13
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2411): !@Sync 14
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,I/PowerManagerService( 2411): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2411): !@Sync 15
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 16
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2411): [PWL] Off : 455s ago
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
E/Watchdog( 2411): !@Sync 17
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 18
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 2581): GC_CONCURRENT freed 15709K, 34% free 33860K/50844K, paused 18ms+9ms, total 107ms
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2411): !@Sync 19
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,I/PowerManagerService( 2411): [PWL] Off : 525s ago
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/TimaService( 2411): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2411): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2411): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2411): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2411): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2411): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2411): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2411): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2411): !@Sync 21
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2411): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,I/GAV2    ( 5612): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5612): Thread[disconnect check,5,main]: Disconnected from service
,E/Watchdog( 2411): !@Sync 22
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 23
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2411): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2411): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,V/AlarmManager( 2411): (AppSync) ### 0 added ###,
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2411): GC_CONCURRENT freed 3985K, 73% free 24844K/89744K, paused 12ms+18ms, total 240ms
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 24
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2411): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :4
,I/SensorManagerA( 2411): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2411): LightSensor setDelay = 200000000
,D/LightsService( 2411): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2411): LightSensor setSensorDelay = 200000000
D/Sensors ( 2411): Light sensor flush: not enabled 0
D/Sensors ( 2411): LightSensor enable = 1
D/Sensors ( 2411): LightSensor enableSensor = 1
,D/SensorManager( 2411): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2411): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Sensors ( 2411): LightSensor enable = 0
,D/Sensors ( 2411): LightSensor enableSensor = 0
,D/SensorManager( 2411): unregisterListener ::   
D/LightsService( 2411): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2411): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/PowerManagerService( 2411): [PWL] Off : 680s ago
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 25
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :4
,V/AlarmManager( 2411): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4077): GC_CONCURRENT freed 2892K, 31% free 9725K/13896K, paused 22ms+2ms, total 98ms
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 26
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 27
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2411): stay LED for fully charged
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,I/PowerManagerService( 2411): [PWL] Off : 765s ago
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 28
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 29
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/TimaService( 2411): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2411): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2411): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2411): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2411): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2411): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2411): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2411): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,I/PowerManagerService( 2411): [PWL] Off : 855s ago
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2411): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 31
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2411): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :4
,V/AlarmManager( 2411): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/ConnectivityService( 2411): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
,D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 10
,D/AmoledAdjustTimer( 2411): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 32
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2411): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,E/SPPClientService( 5517): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 33
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,I/PowerManagerService( 2411): [PWL] Off : 950s ago
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 34
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 35
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 36
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/PowerManagerService( 2411): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/dalvikvm( 2411): GC_CONCURRENT freed 3830K, 73% free 24784K/89744K, paused 21ms+19ms, total 251ms
,E/Watchdog( 2411): !@Sync 37
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 38
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 39
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/TimaService( 2411): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2411): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2411): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ProcessCpuTracker( 2411): Skipping unknown process pid 9358
,E/Watchdog( 2411): !@Sync 40
I/TLC_TIMA_PKM_measure_kernel( 2411): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 2411): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2411): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2411): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/PowerManagerService( 2411): [PWL] Off : 1155s ago
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 41
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 42
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :4
,V/AlarmManager( 2411): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5517): [b] __PingReply__
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2411): stay LED for fully charged
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2411): !@Sync 43
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2411): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2411): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,V/AlarmManager( 2411): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2411): [PWL] Off : 1265s ago
,E/Watchdog( 2411): !@Sync 44
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,I/SensorManagerA( 2411): getReportingMode :: sensor.mType = 5
,D/LightsService( 2411): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2411): LightSensor setDelay = 200000000
D/Sensors ( 2411): LightSensor setSensorDelay = 200000000
D/Sensors ( 2411): Light sensor flush: not enabled 0
D/Sensors ( 2411): LightSensor enable = 1
D/Sensors ( 2411): LightSensor enableSensor = 1
D/SensorManager( 2411): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors ( 2411): LightSensor enable = 0
,D/Sensors ( 2411): LightSensor enableSensor = 0
,D/LightsService( 2411): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 2411): unregisterListener ::   
D/LightsService( 2411): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 45
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 46
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 47
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2411): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2411): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2411): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 288, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 48
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 49
,TIME-OUT KILL (timeout was 1200000ms)
```
