#### Test 568182540458528_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system,
E/Watchdog( 2411): !@Sync 8
--------- beginning of /dev/log/main
D/AndroidRuntime( 7294): 
D/AndroidRuntime( 7294): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7294): CheckJNI is OFF
D/AndroidRuntime( 7294): setted country_code = Poland
D/AndroidRuntime( 7294): setted countryiso_code = PL
D/AndroidRuntime( 7294): setted sales_code = PLS
D/AndroidRuntime( 7294): readGMSProperty: start
D/AndroidRuntime( 7294): readGMSProperty: already setted!!
D/AndroidRuntime( 7294): readGMSProperty: end
D/AndroidRuntime( 7294): addProductProperty: start
D/dalvikvm( 7294): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7294): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7294): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7294): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7294): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7294): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7294): failed to load memtrack module: -2
D/dalvikvm( 7294): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7294): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2411): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2411): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2411  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2411): mDVFSHelper.acquire()
I/SELinux ( 7322): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7322):  
D/PointerIcon( 2411): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2411): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2411): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2411): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7294): Shutting down VM
D/dalvikvm( 7294): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+1ms, total 3ms
I/SELinux ( 7322): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7322):  
I/SELinux ( 7322):  
I/SELinux ( 7322): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7322): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7322): >>>>> Normal User
E/dalvikvm( 7322): >>>>> com.test.thalitest [ userId:0 | appId:10651 ]
E/SELinux ( 7322): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7322): in addTimaSignatureService
D/TimaKeyStoreProvider( 7322): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7322): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4175): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4175): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (-2/10)
D/dalvikvm( 7322): GC_CONCURRENT freed 3014K, 31% free 9557K/13844K, paused 2ms+1ms, total 18ms
D/dalvikvm( 7322): WAIT_FOR_CONCURRENT_GC blocked 16ms
V/WebViewChromium( 7322): Binding Chromium to the background looper Looper (main, tid 1) {422a4468}
I/chromium( 7322): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7322): Initializing chromium process, renderers=0
W/chromium( 7322): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7322): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7322): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7322): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7322): Mali API Version : 401
,I/Mali    ( 7322): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7322): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7322): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
,D/dalvikvm( 7322): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7322): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7322): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7322): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2578): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/StatusBarManagerService( 2411): tr p:7322,o:f
,W/dalvikvm( 7322): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 7322): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7322): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7322): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 7322): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 7322): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7322): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7322): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 7322): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7322): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7322): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 7322): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 7322): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2578): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2411): semi p:7322,o:f
,I/SurfaceFlinger( 1920): id=19 createSurf (1x1),1 flag=404, NainActivit
D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
D/STATUSBAR-StatusBarManagerService( 2411): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2411): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2411): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2411): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2411): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2411): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7322): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7322): Enabling debug mode 0
,W/AwContents( 7322): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 7322): showStatusIcon on inactive InputConnection
,D/CustomFrequencyManagerService( 2411): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2411  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2411): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2411): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2411  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/JsMessageQueue( 7322): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7322): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4229ce18
,D/dalvikvm( 7322): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4229ce18
,D/jxcore_app_log( 7322): JniHelper::setJavaVM(0x4180a220), pthread_self() = 1964181824
,I/chromium( 7322): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/dalvikvm( 7322): GC_CONCURRENT freed 1287K, 19% free 11342K/13900K, paused 2ms+2ms, total 27ms
,D/dalvikvm( 7322): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 7322): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/AmoledAdjustTimer( 2411): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,D/dalvikvm( 7322): GC_CONCURRENT freed 1725K, 17% free 15151K/18168K, paused 1ms+3ms, total 40ms
D/dalvikvm( 7322): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/dalvikvm( 7322): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/CustomFrequencyManagerService( 2411): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2411  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 7322): GC_FOR_ALLOC freed 5720K, 30% free 16721K/23752K, paused 50ms, total 50ms
,D/dalvikvm( 7322): GC_CONCURRENT freed 6781K, 31% free 18101K/26184K, paused 3ms+10ms, total 68ms
,D/dalvikvm( 7322): WAIT_FOR_CONCURRENT_GC blocked 35ms
,D/dalvikvm( 7322): WAIT_FOR_CONCURRENT_GC blocked 33ms
,D/dalvikvm( 7322): GC_FOR_ALLOC freed 1013K, 32% free 17948K/26184K, paused 52ms, total 52ms
,I/dalvikvm-heap( 7322): Grow heap (frag case) to 22.285MB for 3688532-byte allocation
,D/dalvikvm( 7322): GC_FOR_ALLOC freed 2434K, 36% free 19116K/29788K, paused 50ms, total 50ms
,D/dalvikvm( 7322): GC_FOR_ALLOC freed 2164K, 36% free 19150K/29788K, paused 48ms, total 48ms
,W/jxcore-log( 7322): Initializing JXcore engine
,W/jxcore-log( 7322): JXcore engine is ready
,W/jxcore-log( 7322): Starting JXcore engine
,W/jxcore-log( 7322): Platform android
W/jxcore-log( 7322): 
,W/jxcore-log( 7322): Process ARCH arm
W/jxcore-log( 7322): 
,I/jxcore-log( 7322): JXcore Cordova bridge is ready!
I/jxcore-log( 7322): 
,W/jxcore-log( 7322): JXcore engine is started
,E/jxcore  ( 7322): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 7322): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 7322): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/PointerIcon( 2411): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2411): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2411): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2411): setHoveringSpenCustomIcon IconType is same.1
I/ActivityManager( 2411): Killing 6215:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,D/CustomFrequencyManagerService( 2411): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2411  pkgName : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2411): mDVFSHelper.acquire()
I/SurfaceFlinger( 1920): id=19 Removed NainActivit (8/10)
I/SurfaceFlinger( 1920): id=19 Removed NainActivit (-2/10)
,I/DBG_DM  ( 4763): [3.19.140541][Line:408][onResume] 
,I/DBG_DM  ( 4763): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 32
,I/DBG_DM  ( 4763): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/DBG_DM  ( 4763): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4763): [3.19.140541][Line:418][onResume] Postpone Count : 32
I/DBG_DM  ( 4763): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/DBG_DM  ( 4763): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 4763): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2411): sendNotification(2) - 4
,I/DBG_DM  ( 4763): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 32
W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/DBG_DM  ( 4763): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4763): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
I/DBG_DM  ( 4763): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
D/checkbox( 4763): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4763): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4763): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
D/Activity( 4763): setTransGradationMode to true
,D/PhoneStatusBar( 2578): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,I/DBG_DM  ( 4763): [3.19.140541][Line:400][onPause] 
D/StatusBarManagerService( 2411): semi p:4763,o:t
,I/SurfaceFlinger( 1920): id=20 createSurf (720x1280),2 flag=404, YUIInstallC
D/STATUSBAR-StatusBarManagerService( 2411): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2411): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2411): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2411): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2411): setHoveringSpenCustomIcon IconType is same.1
D/STATUSBAR-StatusBarManagerService( 2411): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/IInputConnectionWrapper( 7322): showStatusIcon on inactive InputConnection
,D/CustomFrequencyManagerService( 2411): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2411  tag : ACTIVITY_RESUME_BOOSTER@4
,D/CustomFrequencyManagerService( 2411): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2411  pkgName : ACTIVITY_RESUME_BOOSTER@8
,W/ActivityManager( 2411): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2411): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2411  tag : ACTIVITY_RESUME_BOOSTER@8
,V/AlarmManager( 2411): waitForAlarm result :8,
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/PackageManager( 2411): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2411): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2411): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 2411): !@Sync 9,
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2411): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2411): [PWL] Off : 225s ago,
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.,
D/BatteryService( 2411): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate,
D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4008): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2411): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4,
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2411): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4,
,D/TimaService( 2411): TIMA: TimaService scheduler is intialized. ,
,D/TimaService( 2411): TimaServiceHandler.handleMessage what =1
,D/TimaService( 2411): TIMA: checkEvent, operation: 50000 subject: 10000,
,I/TLC_TIMA_PKM_initialize( 2411): initializing...,
I/TLC_TIMA_PKM_initialize( 2411): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 2411): process = ffffffff00000000000000000000000a, process_strlen = 32,
I/TZ: mc_tlc_communication( 2411): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2411): input max_recvmsg_size = 262196
,I/TZ: mc_tlc_communication( 2411): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2411): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2411): aligned max_sendmsg_size = 262208,
I/TZ: mc_tlc_communication( 2411): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 2411): device_id = 0x0
I/TZ: mc_tlc_communication( 2411): tlc_open() was called,
,I/TZ: mc_tlc_communication( 2411): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2411): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 2411): Opening the session,
,I/TZ: mc_tlc_communication( 2411): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 2411): Trustlet response is completed,
,W/ProcessCpuTracker( 2411): Skipping unknown process pid 7499,
,E/Watchdog( 2411): !@Sync 10,
,I/TLC_TIMA_PKM_measure_kernel( 2411): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2411): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2411): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/TimaService( 2411): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2411): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4,
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2411): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate,
D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4008): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,V/AlarmManager( 2411): waitForAlarm result :8,
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2411): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = -10,
,D/AmoledAdjustTimer( 2411): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4,
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2411): [PWL] Off : 275s ago,
,E/Watchdog( 2411): !@Sync 11,
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2411): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4,
,V/AlarmManager( 2411): waitForAlarm result :4,
,V/AlarmManager( 2411): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 7632): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7632):  
,I/SELinux ( 7632): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7632):  
I/SELinux ( 7632):  
,I/SELinux ( 7632): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7632): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7632): >>>>> Normal User
,E/dalvikvm( 7632): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ],
,E/SELinux ( 7632): [DEBUG] seapp_context_lookup: seinfoCategory = default,
,D/TimaKeyStoreProvider( 7632): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7632): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7632): Added TimaKesytore provider,
,D/dalvikvm( 7632): GC_CONCURRENT freed 3000K, 31% free 9567K/13840K, paused 3ms+2ms, total 28ms,
,D/dalvikvm( 7632): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/ActivityManager( 2411): Killing 6285:com.sec.android.app.music:service/u0a152 (adj 15): empty #43,
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2411): stay LED for fully charged
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4008): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2411): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4,
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2411): stay LED for fully charged
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2411): stay LED for fully charged
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2411): !@Sync 12
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,I/PowerManagerService( 2411): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2411): !@Sync 13
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 290, currTemp = 291, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2411): !@Sync 14
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/PowerManagerService( 2411): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2411): !@Sync 15
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2411): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2411): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2411): !@Sync 16,
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2411): stay LED for fully charged
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
V/AlarmManager( 2411): waitForAlarm result :8
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :4
,V/AlarmManager( 2411): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2411): stay LED for fully charged
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2578): GC_CONCURRENT freed 15753K, 34% free 33852K/50876K, paused 10ms+9ms, total 92ms
,E/SPPClientService( 5572): [b] __PingReply__
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2411): [PWL] Off : 455s ago
,E/Watchdog( 2411): !@Sync 17
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 18
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 2411): GC_CONCURRENT freed 5073K, 75% free 24916K/98244K, paused 20ms+21ms, total 258ms
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2411): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2411): !@Sync 19
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2411): [PWL] Off : 525s ago
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/TimaService( 2411): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2411): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2411): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2411): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2411): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2411): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2411): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2411): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2411): stay LED for fully charged
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2411): !@Sync 21
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2411): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2411): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2411): waitForAlarm result :4
,I/SensorManagerA( 2411): getReportingMode :: sensor.mType = 5
,D/LightsService( 2411): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2411): LightSensor setDelay = 200000000
D/Sensors ( 2411): LightSensor setSensorDelay = 200000000
D/Sensors ( 2411): Light sensor flush: not enabled 0
D/Sensors ( 2411): LightSensor enable = 1
D/Sensors ( 2411): LightSensor enableSensor = 1
D/SensorManager( 2411): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2411): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/EventLogService( 3277): Aggregate from 1453855606442 (log), 1453855606442 (data)
,I/PowerManagerService( 2411): [PWL] Off : 600s ago
I/PowerManagerService( 2411): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2411): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2411): [PWL]       PARTIAL_WAKE_LOCK              'Event Log Service' (uid=10012, pid=3277, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=99)
,D/dalvikvm( 3277): GC_CONCURRENT freed 2129K, 22% free 12546K/15948K, paused 8ms+9ms, total 86ms
,D/LightsService( 2411): [SvcLED]  onSensorChanged::light value = 0
D/Sensors ( 2411): LightSensor enable = 0
D/Sensors ( 2411): LightSensor enableSensor = 0
,D/SensorManager( 2411): unregisterListener ::   
D/LightsService( 2411): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 287, currTemp = 289, prevStep = 4, currStep = 4
,I/GAV2    ( 5674): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5674): Thread[disconnect check,5,main]: Disconnected from service
,E/Watchdog( 2411): !@Sync 22
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2411): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2411): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 2411): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,V/AlarmManager( 2411): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2411): stay LED for fully charged
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2411): stay LED for fully charged
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 23
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2411): stay LED for fully charged
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 24
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2411): [PWL] Off : 680s ago
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 25
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 26
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4061): GC_CONCURRENT freed 2879K, 30% free 9724K/13876K, paused 6ms+2ms, total 63ms
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2411): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 27
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2411): [PWL] Off : 765s ago
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2411): stay LED for fully charged
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2411): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 28
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2411): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2411): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 29
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2411): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/TimaService( 2411): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2411): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2411): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2411): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2411): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2411): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2411): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2411): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2411): [PWL] Off : 855s ago
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2411): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2411): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/dalvikvm( 2411): GC_CONCURRENT freed 3799K, 75% free 24917K/98008K, paused 19ms+19ms, total 225ms
,E/Watchdog( 2411): !@Sync 31
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :4
,V/AlarmManager( 2411): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager( 2411): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 9421): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 9421):  
,I/GoogleURLConnFactory( 2849): Using platform SSLCertificateSocketFactory
,I/SELinux ( 9421): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 9421):  
I/SELinux ( 9421):  
,I/SELinux ( 9421): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 9421): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 9421): >>>>> Normal User
,E/dalvikvm( 9421): >>>>> com.google.android.youtube [ userId:0 | appId:10175 ]
,E/SELinux ( 9421): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 9421): in addTimaSignatureService
,D/TimaKeyStoreProvider( 9421): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 9421): Added TimaKesytore provider
,E/dalvikvm( 2849): Could not find class 'android.net.Network', referenced from method com.google.android.gms.auth.be.k.a
W/dalvikvm( 2849): VFY: unable to resolve check-cast 174 (Landroid/net/Network;) in Lcom/google/android/gms/auth/be/k;
,D/dalvikvm( 2849): VFY: replacing opcode 0x1f at 0x0149
,D/dalvikvm( 9421): GC_CONCURRENT freed 2997K, 31% free 9568K/13844K, paused 8ms+2ms, total 42ms
,D/dalvikvm( 9421): WAIT_FOR_CONCURRENT_GC blocked 28ms
,I/PhenotypeConfigurator( 2734): Scheduling Phenotype for one-off execution 4975 seconds from now (1453857879169)
,D/GetConfigurationSnapshotOperation( 2734): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/ConnectivityService( 2411): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController( 2578): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2578): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2578): updateDataNetType()
,D/STATUSBAR-NetworkController( 2578): NoService, mRoamingIconId = 0
,I/PhenotypeFlagCommitter( 2734): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,E/dalvikvm( 9421): Could not find class 'android.app.Notification$Action$Builder', referenced from method b.a
W/dalvikvm( 9421): VFY: unable to resolve new-instance 406 (Landroid/app/Notification$Action$Builder;) in Lb;
,D/dalvikvm( 9421): VFY: replacing opcode 0x22 at 0x0000
,D/dalvikvm( 2734): GC_EXPLICIT freed 1707K, 21% free 11675K/14724K, paused 17ms+16ms, total 153ms
,D/dalvikvm( 2849): GC_CONCURRENT freed 1825K, 23% free 11084K/14220K, paused 6ms+6ms, total 99ms
,W/dalvikvm( 2734): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2734): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2734): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 9421): Unable to resolve superclass of Lal; (749)
W/dalvikvm( 9421): Link of class 'Lal;' failed
E/dalvikvm( 9421): Could not find class 'al', referenced from method b.a
W/dalvikvm( 9421): VFY: unable to resolve new-instance 304 (Lal;) in Lb;
,D/dalvikvm( 9421): VFY: replacing opcode 0x22 at 0x0006
I/dalvikvm( 2734): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 2734): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
D/dalvikvm( 2734): VFY: replacing opcode 0x6e at 0x00bb
W/dalvikvm( 9421): Unable to resolve superclass of Lan; (749)
W/dalvikvm( 9421): Link of class 'Lan;' failed
E/dalvikvm( 9421): Could not find class 'an', referenced from method b.a
,W/dalvikvm( 9421): VFY: unable to resolve new-instance 358 (Lan;) in Lb;
,D/dalvikvm( 9421): VFY: replacing opcode 0x22 at 0x002a
,I/GoogleURLConnFactory( 2734): Using platform SSLCertificateSocketFactory
,I/dalvikvm( 9421): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method b.a
W/dalvikvm( 9421): VFY: unable to resolve virtual method 5407: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm( 9421): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 9421): Could not find method android.view.View.getTransitionName, referenced from method b.a
W/dalvikvm( 9421): VFY: unable to resolve virtual method 5231: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 9421): VFY: replacing opcode 0x6e at 0x0006
,W/dalvikvm( 9421): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 9421): Could not find class 'android.app.RemoteInput[]', referenced from method b.a
W/dalvikvm( 9421): VFY: unable to resolve new-array 12200 ([Landroid/app/RemoteInput;) in Lb;
,D/dalvikvm( 9421): VFY: replacing opcode 0x23 at 0x0005
,D/LocationManagerService( 2411): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/dalvikvm( 9421): DexOpt: unable to opt direct call 0x090f at 0x0e in Lb;.a
W/dalvikvm( 9421): Unable to resolve superclass of Lal; (749)
W/dalvikvm( 9421): Link of class 'Lal;' failed
D/dalvikvm( 9421): DexOpt: unable to opt direct call 0x068d at 0x08 in Lb;.a
W/dalvikvm( 9421): Unable to resolve superclass of Lan; (749)
W/dalvikvm( 9421): Link of class 'Lan;' failed
D/dalvikvm( 9421): DexOpt: unable to opt direct call 0x0802 at 0x2c in Lb;.a
,D/dalvikvm( 9421): DexOpt: unable to opt direct call 0x0957 at 0x13 in Lb;.a
,I/dalvikvm( 9421): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method dyp.a
,W/dalvikvm( 9421): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 9421): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm( 9421): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 9421): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 9421): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 9421): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 9421): VFY: unable to resolve instance field 36
,D/dalvikvm( 9421): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 9421): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 9421): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 9421): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 9421): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 9421): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 9421): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4236c210
D/dalvikvm( 9421): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4236c210
,D/dalvikvm( 9421): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4236c210, skipping init
,D/dalvikvm( 9421): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4236c210
,D/dalvikvm( 9421): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4236c210
,V/JNIHelp ( 9421): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/System.out( 2734): Thread-124(HTTPLog):isShipBuild true
,I/System.out( 2734): Thread-124(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/dalvikvm( 9421): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 9421): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 9421): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm( 9421): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4236c210
,D/dalvikvm( 9421): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x4236c210
,D/dalvikvm( 9421): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4236c210
,D/dalvikvm( 9421): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4236c210
,I/dalvikvm( 9421): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
,W/dalvikvm( 9421): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 9421): VFY: replacing opcode 0x71 at 0x004e
,D/dalvikvm( 9421): DexOpt: --- BEGIN 'ads-1776657561.jar' (bootstrap=0) ---
,I/ProviderInstaller( 9421): Installed default security provider GmsCore_OpenSSL
,D/dalvikvm( 9459): DexOpt: load 6ms, verify+opt 14ms, 194052 bytes
,D/dalvikvm( 9421): DexOpt: --- END 'ads-1776657561.jar' (success) ---
,D/dalvikvm( 9421): DEX prep '/data/data/com.google.android.youtube/cache/ads-1776657561.jar': unzip in 0ms, rewrite 118ms
,E/YouTube MDX( 9421): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/dalvikvm( 9421): GC_CONCURRENT freed 1957K, 24% free 10684K/13912K, paused 7ms+6ms, total 56ms
,D/dalvikvm( 9421): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 9421): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 9421): WAIT_FOR_CONCURRENT_GC blocked 21ms
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 9421): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,I/dalvikvm( 9421): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm( 9421): VFY: unable to resolve virtual method 2614: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/ComponentName;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 9421): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 9421): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm( 9421): VFY: unable to resolve virtual method 2615: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/Intent;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 9421): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 9421): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm( 9421): VFY: unable to resolve virtual method 2622: Landroid/content/pm/PackageManager;.getApplicationBanner (Landroid/content/pm/ApplicationInfo;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 9421): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 9421): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm( 9421): VFY: unable to resolve virtual method 2623: Landroid/content/pm/PackageManager;.getApplicationBanner (Ljava/lang/String;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 9421): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 9421): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method agv.getLeanbackLaunchIntentForPackage
W/dalvikvm( 9421): VFY: unable to resolve virtual method 2639: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/dalvikvm( 9421): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 9421): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method agv.getPackageInstaller
W/dalvikvm( 9421): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 9421): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 9421): Could not find method android.content.pm.PackageManager.getUserBadgedDrawableForDensity, referenced from method agv.getUserBadgedDrawableForDensity
W/dalvikvm( 9421): VFY: unable to resolve virtual method 2659: Landroid/content/pm/PackageManager;.getUserBadgedDrawableForDensity (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;Landroid/graphics/Rect;I)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 9421): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 9421): Could not find method android.content.pm.PackageManager.getUserBadgedIcon, referenced from method agv.getUserBadgedIcon
W/dalvikvm( 9421): VFY: unable to resolve virtual method 2660: Landroid/content/pm/PackageManager;.getUserBadgedIcon (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 9421): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 9421): Could not find method android.content.pm.PackageManager.getUserBadgedLabel, referenced from method agv.getUserBadgedLabel
W/dalvikvm( 9421): VFY: unable to resolve virtual method 2661: Landroid/content/pm/PackageManager;.getUserBadgedLabel (Ljava/lang/CharSequence;Landroid/os/UserHandle;)Ljava/lang/CharSequence;
,D/dalvikvm( 9421): VFY: replacing opcode 0x6e at 0x0002
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 9421): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 9421): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 9421): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,W/InstanceID/Rpc( 9421): Found 10012
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 9421): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,I/ActivityManager( 2411): Killing 6357:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/System.out( 9421): Thread-695(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 9421): Thread-695(ApacheHTTPLog):isShipBuild true
,I/System.out( 9421): Thread-695(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 9421): Thread-695 calls detatch()
,D/LocationManagerService( 2411): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/dalvikvm( 2734): GC_CONCURRENT freed 1405K, 19% free 12199K/14944K, paused 4ms+10ms, total 57ms
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 32
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2411): stay LED for fully charged
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2411): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 33
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2411): [PWL] Off : 950s ago
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 34
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2411): stay LED for fully charged
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 35
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2411): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 36
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,E/SPPClientService( 5572): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,I/PowerManagerService( 2411): [PWL] Off : 1050s ago
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 285, prevStep = 4, currStep = 4
D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2411): !@Sync 37
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
D/AmoledAdjustTimer( 2411): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2411): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 38
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 39
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/TimaService( 2411): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2411): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2411): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2411): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 2411): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 2411): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2411): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2411): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2411): [PWL] Off : 1155s ago
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 41
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/dalvikvm( 2411): GC_CONCURRENT freed 3859K, 75% free 24810K/98008K, paused 18ms+22ms, total 252ms
,E/Watchdog( 2411): !@Sync 42
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2411): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2411): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,V/AlarmManager( 2411): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2411): !@Sync 43
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
,D/BatteryService( 2411): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,I/PowerManagerService( 2411): [PWL] Off : 1265s ago
,E/Watchdog( 2411): !@Sync 44
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 45
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 46
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :4
,I/SensorManagerA( 2411): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2411): LightSensor setDelay = 200000000
,D/LightsService( 2411): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2411): LightSensor setSensorDelay = 200000000
D/Sensors ( 2411): Light sensor flush: not enabled 0
D/Sensors ( 2411): LightSensor enable = 1
D/Sensors ( 2411): LightSensor enableSensor = 1
D/SensorManager( 2411): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2411): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/LightsService( 2411): [SvcLED]  onSensorChanged::light value = 0
D/Sensors ( 2411): LightSensor enable = 0
D/Sensors ( 2411): LightSensor enableSensor = 0
,D/SensorManager( 2411): unregisterListener ::   
D/LightsService( 2411): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SPPClientService( 5572): [b] __PingReply__
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 47
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,I/PowerManagerService( 2411): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2411): !@Sync 48
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2411): waitForAlarm result :8
,V/AlarmManager( 2411): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2411): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2411): stay LED for fully charged
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,TIME-OUT KILL (timeout was 1200000ms)
```
