#### Test 568182548138a64_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system,
D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2421): stay LED for fully charged
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
--------- beginning of /dev/log/main
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4008): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime( 7309): 
D/AndroidRuntime( 7309): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7309): CheckJNI is OFF
D/AndroidRuntime( 7309): setted country_code = Poland
D/AndroidRuntime( 7309): setted countryiso_code = PL
D/AndroidRuntime( 7309): setted sales_code = PLS
D/AndroidRuntime( 7309): readGMSProperty: start
D/AndroidRuntime( 7309): readGMSProperty: already setted!!
D/AndroidRuntime( 7309): readGMSProperty: end
D/AndroidRuntime( 7309): addProductProperty: start
D/dalvikvm( 7309): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7309): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7309): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7309): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7309): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7309): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7309): failed to load memtrack module: -2
D/dalvikvm( 7309): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7309): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2421): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2421): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2421): mDVFSHelper.acquire()
I/SELinux ( 7322): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7322):  
D/PointerIcon( 2421): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2421): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2421): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2421): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7309): Shutting down VM
D/dalvikvm( 7309): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+1ms, total 3ms
I/SELinux ( 7322): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7322):  
I/SELinux ( 7322):  
I/SELinux ( 7322): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7322): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7322): >>>>> Normal User
E/dalvikvm( 7322): >>>>> com.test.thalitest [ userId:0 | appId:10647 ]
E/SELinux ( 7322): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7322): in addTimaSignatureService
D/TimaKeyStoreProvider( 7322): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7322): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4166): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4166): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1921): id=17 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1921): id=17 Removed YUIInstallC (-2/10)
D/dalvikvm( 7322): GC_CONCURRENT freed 2993K, 31% free 9573K/13848K, paused 3ms+1ms, total 19ms
D/dalvikvm( 7322): WAIT_FOR_CONCURRENT_GC blocked 16ms
V/WebViewChromium( 7322): Binding Chromium to the background looper Looper (main, tid 1) {42294298}
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
D/dalvikvm( 7322): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7322): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7322): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7322): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2580): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,D/StatusBarManagerService( 2421): tr p:7322,o:f
W/dalvikvm( 7322): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7322): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7322): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7322): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 7322): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 7322): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7322): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7322): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 7322): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7322): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7322): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 7322): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 7322): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2580): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2421): semi p:7322,o:f
,I/SurfaceFlinger( 1921): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2421): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2421): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2421): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2421): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2421): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2421): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7322): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7322): Enabling debug mode 0
,W/AwContents( 7322): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 7322): showStatusIcon on inactive InputConnection
D/CustomFrequencyManagerService( 2421): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2421): mDVFSHelper.release()
D/CustomFrequencyManagerService( 2421): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/JsMessageQueue( 7322): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7322): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42295020
,D/dalvikvm( 7322): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42295020
,D/jxcore_app_log( 7322): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2028088616
,I/chromium( 7322): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/dalvikvm( 7322): GC_CONCURRENT freed 1310K, 19% free 11335K/13924K, paused 1ms+2ms, total 23ms
,D/dalvikvm( 7322): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/dalvikvm( 7322): GC_CONCURRENT freed 1718K, 17% free 15128K/18152K, paused 2ms+3ms, total 40ms
D/dalvikvm( 7322): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/dalvikvm( 7322): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/CustomFrequencyManagerService( 2421): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  tag : ACTIVITY_RESUME_BOOSTER@8
,D/AmoledAdjustTimer( 2421): prevTemp = 305, currTemp = 305, prevStep = 4, currStep = 4
,D/dalvikvm( 7322): GC_FOR_ALLOC freed 5747K, 30% free 16763K/23828K, paused 49ms, total 49ms
,D/dalvikvm( 7322): GC_CONCURRENT freed 6776K, 31% free 18144K/26236K, paused 3ms+10ms, total 76ms
D/dalvikvm( 7322): WAIT_FOR_CONCURRENT_GC blocked 36ms
,D/dalvikvm( 7322): WAIT_FOR_CONCURRENT_GC blocked 47ms
,D/dalvikvm( 7322): GC_FOR_ALLOC freed 1161K, 32% free 17858K/26236K, paused 59ms, total 59ms
,I/dalvikvm-heap( 7322): Grow heap (frag case) to 22.206MB for 3688532-byte allocation
,D/dalvikvm( 7322): GC_FOR_ALLOC freed 12K, 29% free 21448K/29840K, paused 58ms, total 58ms
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
,D/PointerIcon( 2421): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2421): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2421): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2421): setHoveringSpenCustomIcon IconType is same.1
I/ActivityManager( 2421): Killing 6250:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,W/PluginManager( 7322): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 20ms. Plugin should use CordovaInterface.getThreadPool().
,I/SurfaceFlinger( 1921): id=19 Removed NainActivit (8/10)
,I/SurfaceFlinger( 1921): id=19 Removed NainActivit (-2/10)
D/CustomFrequencyManagerService( 2421): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2421): mDVFSHelper.acquire()
,I/DBG_DM  ( 4795): [3.19.140541][Line:408][onResume] 
,I/DBG_DM  ( 4795): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 31
,I/DBG_DM  ( 4795): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/DBG_DM  ( 4795): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4795): [3.19.140541][Line:418][onResume] Postpone Count : 31
,I/DBG_DM  ( 4795): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/DBG_DM  ( 4795): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 4795): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2421): sendNotification(2) - 4
,I/DBG_DM  ( 4795): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 31
,I/DBG_DM  ( 4795): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4795): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4795): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
D/checkbox( 4795): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4795): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4795): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,D/Activity( 4795): setTransGradationMode to true
,D/PhoneStatusBar( 2580): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,I/DBG_DM  ( 4795): [3.19.140541][Line:400][onPause] 
,D/StatusBarManagerService( 2421): semi p:4795,o:t
,I/SurfaceFlinger( 1921): id=20 createSurf (720x1280),2 flag=404, YUIInstallC
,D/PointerIcon( 2421): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/STATUSBAR-StatusBarManagerService( 2421): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/STATUSBAR-StatusBarManagerService( 2421): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2421): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2421): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2421): setHoveringSpenCustomIcon IconType is same.1
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/IInputConnectionWrapper( 7322): showStatusIcon on inactive InputConnection
,D/CustomFrequencyManagerService( 2421): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2421): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2421): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/CustomFrequencyManagerService( 2421): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  tag : ACTIVITY_RESUME_BOOSTER@8
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 340, Delta = 10,
,D/PackageManager( 2421): [MSG] WRITE_PACKAGE_RESTRICTIONS,
,D/AmoledAdjustTimer( 2421): prevTemp = 305, currTemp = 305, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2421): [PWL] Off : 180s ago,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 330, Delta = -10,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2421): stay LED for fully charged
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4008): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2421): !@Sync 9,
,D/AmoledAdjustTimer( 2421): prevTemp = 305, currTemp = 305, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 330, Delta = 0,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2421): stay LED for fully charged,
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 305, currTemp = 304, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 330, Delta = 0,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2421): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate,
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4008): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/AmoledAdjustTimer( 2421): prevTemp = 304, currTemp = 304, prevStep = 4, currStep = 4,
,D/TimaService( 2421): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 2421): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2421): TimaServiceHandler.handleMessage what =1,
,I/TLC_TIMA_PKM_initialize( 2421): initializing...,
I/TLC_TIMA_PKM_initialize( 2421): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2421): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 2421): input max_sendmsg_size = 262196
,I/TZ: mc_tlc_communication( 2421): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 2421): root = 0, root_len = 1
,I/TZ: mc_tlc_communication( 2421): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2421): aligned max_sendmsg_size = 262208,
I/TZ: mc_tlc_communication( 2421): aligned max_recvmsg_size = 262208
,I/TZ: mc_tlc_communication( 2421): device_id = 0x0
I/TZ: mc_tlc_communication( 2421): tlc_open() was called
,I/TZ: mc_tlc_communication( 2421): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2421): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 2421): Opening the session
,I/TZ: mc_tlc_communication( 2421): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 2421): Trustlet response is completed,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 330, Delta = 0,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/TimaService( 2421): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,E/Watchdog( 2421): !@Sync 10,
,D/AmoledAdjustTimer( 2421): prevTemp = 304, currTemp = 305, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 330, Delta = 0,
,I/PowerManagerService( 2421): [PWL] Off : 225s ago,
,D/AmoledAdjustTimer( 2421): prevTemp = 305, currTemp = 305, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 330, Delta = 0,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED,
,D/BatteryService( 2421): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4008): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 305, currTemp = 305, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 330, Delta = 0,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
D/BatteryService( 2421): stay LED for fully charged,
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2421): !@Sync 11
,D/AmoledAdjustTimer( 2421): prevTemp = 305, currTemp = 305, prevStep = 4, currStep = 4,
,V/AlarmManager( 2421): waitForAlarm result :4,
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 7687): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7687):  
,I/SELinux ( 7687): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7687):  
I/SELinux ( 7687):  
,I/SELinux ( 7687): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7687): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 7687): >>>>> Normal User
,E/dalvikvm( 7687): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ],
,E/SELinux ( 7687): [DEBUG] seapp_context_lookup: seinfoCategory = default,
,D/TimaKeyStoreProvider( 7687): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7687): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7687): Added TimaKesytore provider,
,D/dalvikvm( 7687): GC_CONCURRENT freed 2997K, 31% free 9562K/13844K, paused 2ms+3ms, total 29ms,
,D/dalvikvm( 7687): WAIT_FOR_CONCURRENT_GC blocked 26ms
,I/ActivityManager( 2421): Killing 6320:com.sec.android.app.music:service/u0a152 (adj 15): empty #43,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 305, currTemp = 305, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 330, Delta = 0,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4372, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate,
D/BatteryService( 2421): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4008): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,V/AlarmManager( 2421): waitForAlarm result :8,
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/AmoledAdjustTimer( 2421): prevTemp = 305, currTemp = 304, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 330, Delta = 0,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate,
D/BatteryService( 2421): stay LED for fully charged
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4008): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2421): !@Sync 12,
,I/PowerManagerService( 2421): [PWL] Off : 275s ago,
,D/AmoledAdjustTimer( 2421): prevTemp = 304, currTemp = 304, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 304, currTemp = 304, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :4
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5616): [b] __PingReply__
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 330, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2421): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 304, currTemp = 304, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 330, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4372, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 2580): GC_CONCURRENT freed 15718K, 34% free 33868K/50864K, paused 25ms+9ms, total 104ms
,E/Watchdog( 2421): !@Sync 13
,D/AmoledAdjustTimer( 2421): prevTemp = 304, currTemp = 304, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 330, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 304, currTemp = 304, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 330, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 304, currTemp = 303, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = -10
,E/Watchdog( 2421): !@Sync 14
,D/AmoledAdjustTimer( 2421): prevTemp = 303, currTemp = 303, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 303, currTemp = 302, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2421): !@Sync 15
,D/AmoledAdjustTimer( 2421): prevTemp = 302, currTemp = 301, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 301, currTemp = 300, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2421): !@Sync 16
,D/AmoledAdjustTimer( 2421): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2421): !@Sync 17
,D/AmoledAdjustTimer( 2421): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2421): !@Sync 18
,I/PowerManagerService( 2421): [PWL] Off : 455s ago
,D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/dalvikvm( 2421): GC_CONCURRENT freed 5121K, 73% free 24881K/90800K, paused 18ms+18ms, total 253ms
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2421): !@Sync 19
,D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/TimaService( 2421): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2421): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2421): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2421): !@Sync 20
,D/AmoledAdjustTimer( 2421): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,I/PowerManagerService( 2421): [PWL] Off : 525s ago
,D/AmoledAdjustTimer( 2421): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2421): !@Sync 21
,D/AmoledAdjustTimer( 2421): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2421): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,I/GAV2    ( 5710): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5710): Thread[disconnect check,5,main]: Disconnected from service
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2421): !@Sync 22
,D/AmoledAdjustTimer( 2421): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged,
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 600s ago
,V/AlarmManager( 2421): waitForAlarm result :8
,D/LightsService( 2421): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2421): getReportingMode :: sensor.mType = 5
D/Sensors ( 2421): LightSensor setDelay = 200000000
D/Sensors ( 2421): LightSensor setSensorDelay = 200000000
D/Sensors ( 2421): Light sensor flush: not enabled 0
D/Sensors ( 2421): LightSensor enable = 1
D/Sensors ( 2421): LightSensor enableSensor = 1
D/SensorManager( 2421): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors ( 2421): LightSensor enable = 0
,D/Sensors ( 2421): LightSensor enableSensor = 0
,D/SensorManager( 2421): unregisterListener ::   
D/LightsService( 2421): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2421): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2421): !@Sync 23
,D/AmoledAdjustTimer( 2421): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2421): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2421): <AppSync3 Whitelist>
,V/AlarmManager( 2421): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2421): !@Sync 24
,D/AmoledAdjustTimer( 2421): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2421): !@Sync 25
,D/AmoledAdjustTimer( 2421): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 680s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4083): GC_CONCURRENT freed 2890K, 31% free 9723K/13896K, paused 25ms+3ms, total 97ms
,D/AmoledAdjustTimer( 2421): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2421): !@Sync 26
,D/AmoledAdjustTimer( 2421): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2421): !@Sync 27
,D/AmoledAdjustTimer( 2421): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2421): !@Sync 28
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,I/PowerManagerService( 2421): [PWL] Off : 765s ago
,D/AmoledAdjustTimer( 2421): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 293, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2421): !@Sync 29
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/TimaService( 2421): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2421): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2421): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2421): !@Sync 30
,D/TimaService( 2421): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/AmoledAdjustTimer( 2421): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2421): !@Sync 31
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,I/PowerManagerService( 2421): [PWL] Off : 855s ago
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :4
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/PhenotypeConfigurator( 2735): Scheduling Phenotype for one-off execution 3637 seconds from now (1453416899036)
,D/GetConfigurationSnapshotOperation( 2735): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 2735): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 2735): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2735): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2735): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 2735): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 2735): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 2735): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 2735): Using platform SSLCertificateSocketFactory
,D/dalvikvm( 2735): GC_CONCURRENT freed 1819K, 22% free 11679K/14848K, paused 8ms+7ms, total 85ms
,D/LocationManagerService( 2421): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 2735): Thread-124(HTTPLog):isShipBuild true
,I/System.out( 2735): Thread-124(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/ConnectivityService( 2421): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
,D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/LocationManagerService( 2421): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/dalvikvm( 2853): GC_CONCURRENT freed 1888K, 23% free 10883K/14124K, paused 6ms+6ms, total 63ms
,D/dalvikvm( 2421): GC_CONCURRENT freed 3882K, 73% free 24861K/90444K, paused 11ms+19ms, total 223ms
,D/LocationManagerService( 2421): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/dalvikvm( 2735): GC_CONCURRENT freed 1446K, 19% free 12236K/15032K, paused 9ms+18ms, total 107ms
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2421): !@Sync 32
,D/AmoledAdjustTimer( 2421): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
D/AmoledAdjustTimer( 2421): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/SPPClientService( 5616): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false,
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2421): !@Sync 33
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2421): !@Sync 34
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 950s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2421): !@Sync 35
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2421): !@Sync 36
,D/AmoledAdjustTimer( 2421): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2421): !@Sync 37
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2421): !@Sync 38
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2421): !@Sync 39
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/TimaService( 2421): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2421): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2421): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 10
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2421): !@Sync 40
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2421): !@Sync 41
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,I/PowerManagerService( 2421): [PWL] Off : 1155s ago
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :12
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2788): GC_CONCURRENT freed 7222K, 40% free 18920K/31124K, paused 10ms+7ms, total 96ms
,D/AmoledAdjustTimer( 2421): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2421): !@Sync 42
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :4
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/SPPClientService( 5616): [b] __PingReply__
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2421): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,I/SensorManagerA( 2421): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2421): LightSensor setDelay = 200000000
,D/Sensors ( 2421): LightSensor setSensorDelay = 200000000
,D/LightsService( 2421): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2421): Light sensor flush: not enabled 0
D/Sensors ( 2421): LightSensor enable = 1
D/Sensors ( 2421): LightSensor enableSensor = 1
,D/SensorManager( 2421): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors ( 2421): LightSensor enable = 0
,D/Sensors ( 2421): LightSensor enableSensor = 0
,D/LightsService( 2421): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 2421): unregisterListener ::   
D/LightsService( 2421): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2421): !@Sync 43
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2421): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2421): <AppSync3 Whitelist>
,V/AlarmManager( 2421): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2421): !@Sync 44
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2421): !@Sync 45
,I/PowerManagerService( 2421): [PWL] Off : 1265s ago
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2421): GC_FOR_ALLOC freed 3735K, 73% free 24992K/90444K, paused 206ms, total 206ms
,D/dalvikvm( 2421): GC_CONCURRENT freed 256K, 73% free 24742K/90444K, paused 11ms+16ms, total 212ms
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2421): !@Sync 46
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2421): !@Sync 47
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2421): !@Sync 48
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 290, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4008): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4008): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2421): !@Sync 49
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,TIME-OUT KILL (timeout was 1200000ms)
```
