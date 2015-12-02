#### Test 52383621d5a0cb8_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system,
D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/BatteryService( 2403): stay LED for fully charged
--------- beginning of /dev/log/main
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4011): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime( 7072): 
D/AndroidRuntime( 7072): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7072): CheckJNI is OFF
D/AndroidRuntime( 7072): setted country_code = Poland
D/AndroidRuntime( 7072): setted countryiso_code = PL
D/AndroidRuntime( 7072): setted sales_code = PLS
D/AndroidRuntime( 7072): readGMSProperty: start
D/AndroidRuntime( 7072): readGMSProperty: already setted!!
D/AndroidRuntime( 7072): readGMSProperty: end
D/AndroidRuntime( 7072): addProductProperty: start
D/dalvikvm( 7072): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7072): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7072): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7072): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7072): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7072): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7072): failed to load memtrack module: -2
D/dalvikvm( 7072): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7072): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2403): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2403): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2403): mDVFSHelper.acquire()
I/SELinux ( 7098): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7098):  
D/PointerIcon( 2403): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2403): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2403): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2403): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7072): Shutting down VM
D/dalvikvm( 7072): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+0ms, total 3ms
I/SELinux ( 7098): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7098):  
I/SELinux ( 7098):  
I/SELinux ( 7098): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7098): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7098): >>>>> Normal User
E/dalvikvm( 7098): >>>>> com.test.thalitest [ userId:0 | appId:10491 ]
E/SELinux ( 7098): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7098): in addTimaSignatureService
D/TimaKeyStoreProvider( 7098): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7098): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4171): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4171): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (-2/10)
D/dalvikvm( 7098): GC_CONCURRENT freed 3006K, 30% free 9564K/13564K, paused 2ms+1ms, total 18ms
D/dalvikvm( 7098): WAIT_FOR_CONCURRENT_GC blocked 15ms
V/WebViewChromium( 7098): Binding Chromium to the background looper Looper (main, tid 1) {4224a250}
I/chromium( 7098): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7098): Initializing chromium process, renderers=0
W/chromium( 7098): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7098): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7098): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7098): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7098): Mali API Version : 401
,I/Mali    ( 7098): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7098): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7098): VFY: unable to resolve virtual method 217: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7098): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7098): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7098): VFY: unable to resolve virtual method 212: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7098): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2579): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,D/StatusBarManagerService( 2403): tr p:7098,o:f
W/dalvikvm( 7098): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7098): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7098): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7098): VFY: unable to resolve virtual method 270: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 7098): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 7098): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7098): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7098): VFY: unable to resolve virtual method 228: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 7098): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7098): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7098): VFY: unable to resolve virtual method 233: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 7098): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 7098): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2579): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2403): semi p:7098,o:f
,I/SurfaceFlinger( 1920): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2403): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2403): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2403): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2403): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2403): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2403): setHoveringSpenCustomIcon IconType is same.1
I/HWUI    ( 7098): EGLImpl-HWUI Protected EGL context created
D/OpenGLRenderer( 7098): Enabling debug mode 0
W/AwContents( 7098): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 7098): showStatusIcon on inactive InputConnection
,D/CustomFrequencyManagerService( 2403): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2403): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2403): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/JsMessageQueue( 7098): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7098): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4223b508
,D/dalvikvm( 7098): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4223b508
D/jxcore_app_log( 7098): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2030843544
,D/JX-Cordova( 7098): jxcore cordova android initializing
,I/dalvikvm( 7098): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.BtConnectorHelper.isBLEAdvertisingSupported
W/dalvikvm( 7098): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 7098): VFY: replacing opcode 0x6e at 0x0045
,D/dalvikvm( 7098): GC_CONCURRENT freed 1288K, 17% free 11347K/13624K, paused 1ms+2ms, total 22ms
,D/dalvikvm( 7098): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/dalvikvm( 7098): GC_CONCURRENT freed 1927K, 17% free 14908K/17844K, paused 2ms+2ms, total 39ms
,D/dalvikvm( 7098): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/CustomFrequencyManagerService( 2403): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  tag : ACTIVITY_RESUME_BOOSTER@8
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 330, Delta = 10
,D/dalvikvm( 7098): GC_FOR_ALLOC freed 5408K, 29% free 16212K/22828K, paused 41ms, total 42ms
,D/AmoledAdjustTimer( 2403): prevTemp = 301, currTemp = 300, prevStep = 4, currStep = 4
,D/dalvikvm( 7098): GC_CONCURRENT freed 6638K, 31% free 17685K/25392K, paused 2ms+10ms, total 62ms
,D/dalvikvm( 7098): WAIT_FOR_CONCURRENT_GC blocked 53ms
,D/dalvikvm( 7098): GC_FOR_ALLOC freed 1391K, 31% free 17582K/25392K, paused 51ms, total 51ms
,I/dalvikvm-heap( 7098): Grow heap (frag case) to 21.726MB for 3767174-byte allocation
,D/dalvikvm( 7098): GC_FOR_ALLOC freed 2522K, 36% free 18738K/29072K, paused 42ms, total 42ms
,W/jxcore-log( 7098): Initializing JXcore engine
,W/jxcore-log( 7098): JXcore engine is ready
,W/jxcore-log( 7098): Starting JXcore engine
,W/jxcore-log( 7098): Platform android
W/jxcore-log( 7098): 
,W/jxcore-log( 7098): Process ARCH arm
W/jxcore-log( 7098): 
,I/jxcore-log( 7098): JXcore Cordova bridge is ready!
I/jxcore-log( 7098): 
,W/jxcore-log( 7098): JXcore engine is started
,I/chromium( 7098): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 7098): Error!: Cannot find module '../server-address.js',
E/jxcore  ( 7098): Stack: [{"_fileName":"module.js","_functionName":"Module._oldRes","_lineNumber":"776","_columnNumber":"15","_msg":"    at Module._oldRes@module.js:776:15"},{"_fileName":"module.js","_functionName":"Module._resolveFilename","_lineNumber":"1608","_columnNumber":"1","_msg":"    at Module._resolveFilename@module.js:1608:1"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"337","_columnNumber":"18","_msg":"    at Module._load@module.js:337:18"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"11","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:11:21"},{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"597","_columnNumber":"10","_msg":"    at Module.prototype._compile@module.js:597:10"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"}]
,I/chromium( 7098): [INFO:CONSOLE(37)] "App.js file failed to load : "Cannot find module '../server-address.js'\nError: Cannot find module '../server-address.js'\n    at Module._oldRes@module.js:776:15\n    at Module._resolveFilename@module.js:1608:1\n    at Module._load@module.js:337:18\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:11:21\n    at Module.prototype._compile@module.js:597:10\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7"", source: file:///android_asset/www/js/thali_main.js (37),
,D/PointerIcon( 2403): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
D/PointerIcon( 2403): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2403): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2403): setHoveringSpenCustomIcon IconType is same.1,
I/ActivityManager( 2403): Killing 6174:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,I/SurfaceFlinger( 1920): id=19 Removed NainActivit (8/10),
,I/SurfaceFlinger( 1920): id=19 Removed NainActivit (-2/10)
D/CustomFrequencyManagerService( 2403): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  pkgName : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2403): mDVFSHelper.acquire()
,I/DBG_DM  ( 4714): [3.19.140541][Line:408][onResume] ,
,I/DBG_DM  ( 4714): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 22,
,I/DBG_DM  ( 4714): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0,
,I/DBG_DM  ( 4714): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0,
,I/DBG_DM  ( 4714): [3.19.140541][Line:418][onResume] Postpone Count : 22
,I/DBG_DM  ( 4714): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0,
,I/DBG_DM  ( 4714): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 4714): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 ,
,D/STATUSBAR-StatusBarManagerService( 2403): sendNotification(2) - 4,
,I/DBG_DM  ( 4714): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 22,
,I/DBG_DM  ( 4714): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0,
,I/DBG_DM  ( 4714): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
I/DBG_DM  ( 4714): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
D/checkbox( 4714): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
I/DBG_DM  ( 4714): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
I/DBG_DM  ( 4714): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
D/Activity( 4714): setTransGradationMode to true
D/PhoneStatusBar( 2579): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,D/StatusBarManagerService( 2403): semi p:4714,o:t
I/DBG_DM  ( 4714): [3.19.140541][Line:400][onPause] 
,I/SurfaceFlinger( 1920): id=20 createSurf (720x1280),2 flag=404, YUIInstallC
D/STATUSBAR-StatusBarManagerService( 2403): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2403): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2403): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2403): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2403): setHoveringSpenCustomIcon IconType is same.1
D/STATUSBAR-StatusBarManagerService( 2403): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,W/IInputConnectionWrapper( 7098): showStatusIcon on inactive InputConnection
W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/CustomFrequencyManagerService( 2403): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2403): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2403): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/CustomFrequencyManagerService( 2403): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  tag : ACTIVITY_RESUME_BOOSTER@8
,D/PackageManager( 2403): [MSG] WRITE_PACKAGE_RESTRICTIONS,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 2403): !@Sync 9,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = -10,
,D/AmoledAdjustTimer( 2403): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4,
,V/AlarmManager( 2403): waitForAlarm result :8
V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
I/PowerManagerService( 2403): [PWL] Off : 225s ago
I/PowerManagerService( 2403): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2403): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 2403): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=2403, ws=WorkSource{1000}) (elapsedTime=10)
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2403): stay LED for fully charged,
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4011): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): stay LED for fully charged
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4,
,D/TimaService( 2403): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 2403): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2403): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 2403): initializing...,
I/TLC_TIMA_PKM_initialize( 2403): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2403): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2403): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2403): input max_recvmsg_size = 262196,
I/TZ: mc_tlc_communication( 2403): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2403): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 2403): aligned max_sendmsg_size = 262208
,I/TZ: mc_tlc_communication( 2403): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 2403): device_id = 0x0
,I/TZ: mc_tlc_communication( 2403): tlc_open() was called
,I/TZ: mc_tlc_communication( 2403): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2403): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 2403): Opening the session
,I/TZ: mc_tlc_communication( 2403): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 2403): Trustlet response is completed,
,E/Watchdog( 2403): !@Sync 10,
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/TimaService( 2403): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4011): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2403): [PWL] Off : 275s ago,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate,
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10,
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,E/Watchdog( 2403): !@Sync 11,
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 299, currTemp = 300, prevStep = 4, currStep = 4,
,V/AlarmManager( 2403): waitForAlarm result :4,
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 7435): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7435):  
,I/SELinux ( 7435): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7435):  
I/SELinux ( 7435):  
,I/SELinux ( 7435): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
,E/SELinux ( 7435): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7435): >>>>> Normal User
,E/dalvikvm( 7435): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ],
,E/SELinux ( 7435): [DEBUG] seapp_context_lookup: seinfoCategory = default,
,D/TimaKeyStoreProvider( 7435): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7435): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7435): Added TimaKesytore provider,
,V/AlarmManager( 2403): waitForAlarm result :8,
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK,
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/dalvikvm( 2403): GC_EXPLICIT freed 28427K, 72% free 25270K/87648K, paused 10ms+31ms, total 380ms,
,D/dalvikvm( 7435): GC_CONCURRENT freed 3009K, 30% free 9570K/13568K, paused 3ms+2ms, total 30ms,
,D/dalvikvm( 7435): WAIT_FOR_CONCURRENT_GC blocked 26ms
,I/ActivityManager( 2403): Killing 6243:com.sec.android.app.music:service/u0a152 (adj 15): empty #43,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true,
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED,
,D/BatteryService( 2403): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4011): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2403): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4,
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4011): Disconnected process message: 10
D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 299, currTemp = 300, prevStep = 4, currStep = 4
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/BatteryService( 2403): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2403): !@Sync 12
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2403): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2403): !@Sync 13
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 14
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2403): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2403): !@Sync 15
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2403): !@Sync 16
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2403): [PWL] Off : 455s ago
,E/Watchdog( 2403): !@Sync 17
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 18
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2403): !@Sync 19
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2403): [PWL] Off : 525s ago
,I/PowerManagerService( 2403): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2403): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2403): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=2403, ws=WorkSource{1000}) (elapsedTime=50)
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/TimaService( 2403): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2403): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2403): TimaServiceHandler.handleMessage what =1
,W/ProcessCpuTracker( 2403): Skipping unknown process pid 8131
,W/ProcessCpuTracker( 2403): Skipping unknown process pid 8133
,W/ProcessCpuTracker( 2403): Skipping unknown process pid 8134
,W/ProcessCpuTracker( 2403): Skipping unknown process pid 8136
,W/ProcessCpuTracker( 2403): Skipping unknown process pid 8138
,W/ProcessCpuTracker( 2403): Skipping unknown process pid 8139
,W/ProcessCpuTracker( 2403): Skipping unknown process pid 8141
,W/ProcessCpuTracker( 2403): Skipping unknown process pid 8143
,W/ProcessCpuTracker( 2403): Skipping unknown process pid 8144
,W/ProcessCpuTracker( 2403): Skipping unknown process pid 8145
,E/Watchdog( 2403): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2403): !@Sync 21
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 600s ago
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,I/GAV2    ( 5624): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5624): Thread[disconnect check,5,main]: Disconnected from service
,E/Watchdog( 2403): !@Sync 22
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 23
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2403): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2403): <AppSync3 Whitelist>
,V/AlarmManager( 2403): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 24
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 680s ago
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 25
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4082): GC_CONCURRENT freed 2883K, 29% free 9730K/13604K, paused 6ms+2ms, total 69ms
,D/dalvikvm( 2403): GC_CONCURRENT freed 4468K, 72% free 24679K/87648K, paused 10ms+16ms, total 223ms
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 26
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,I/SensorManagerA( 2403): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2403): LightSensor setDelay = 200000000
,D/LightsService( 2403): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2403): LightSensor setSensorDelay = 200000000
D/Sensors ( 2403): Light sensor flush: not enabled 0
D/Sensors ( 2403): LightSensor enable = 1
D/Sensors ( 2403): LightSensor enableSensor = 1
D/SensorManager( 2403): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,E/SPPClientService( 5521): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/LightsService( 2403): [SvcLED]  onSensorChanged::light value = 8
D/Sensors ( 2403): LightSensor enable = 0
D/Sensors ( 2403): LightSensor enableSensor = 0
,D/SensorManager( 2403): unregisterListener ::   
D/LightsService( 2403): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 27
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2403): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2403): [PWL] Off : 765s ago
,I/PowerManagerService( 2403): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService( 2403): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2403): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=2403, ws=WorkSource{1000}) (elapsedTime=92)
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 28
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 29
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,D/TimaService( 2403): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2403): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2403): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,E/Watchdog( 2403): !@Sync 30
,D/TimaService( 2403): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 320, Delta = 10
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 855s ago
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 31
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 32
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 33
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2403): [PWL] Off : 950s ago
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 34
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 35
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 36
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :4
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5521): [b] __PingReply__
V/AlarmManager( 2403): waitForAlarm result :4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/UdcCache:FPQuery( 3424): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 2849): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2849): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GetConfigurationSnapshotOperation( 2849): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 2849): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 2849): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 2849): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/ConnectivityService( 2403): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController( 2579): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/STATUSBAR-NetworkController( 2579): getUpdateDataNetType() - mDataNetType:0
,D/STATUSBAR-NetworkController( 2579): updateDataNetType()
,D/STATUSBAR-NetworkController( 2579): NoService, mRoamingIconId = 0
,D/dalvikvm( 2849): GC_CONCURRENT freed 1709K, 20% free 11399K/14168K, paused 8ms+7ms, total 74ms
,W/Uploader( 2849):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 2849): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 2849): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 2849): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 2849): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/PowerManagerService( 2403): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 37
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 38
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/dalvikvm( 2403): GC_CONCURRENT freed 3678K, 72% free 24714K/87640K, paused 21ms+18ms, total 230ms
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 39
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/TimaService( 2403): TIMA: TimaService scheduler is intialized. 
D/TimaService( 2403): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2403): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,E/Watchdog( 2403): !@Sync 40
,D/TimaService( 2403): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 1155s ago
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 41
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 42
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 43
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2403): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2403): <AppSync3 Whitelist>
,V/AlarmManager( 2403): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 1265s ago
,E/Watchdog( 2403): !@Sync 44
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 45
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4,
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2403): !@Sync 46
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :4
,I/SensorManagerA( 2403): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2403): LightSensor setDelay = 200000000
,D/LightsService( 2403): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2403): LightSensor setSensorDelay = 200000000
D/Sensors ( 2403): Light sensor flush: not enabled 0
D/Sensors ( 2403): LightSensor enable = 1
D/Sensors ( 2403): LightSensor enableSensor = 1
D/SensorManager( 2403): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/EventLogService( 3424): Aggregate from 1449055911721 (log), 1449055911721 (data)
,D/Sensors ( 2403): LightSensor enable = 0
,D/Sensors ( 2403): LightSensor enableSensor = 0
D/SensorManager( 2403): unregisterListener ::   
D/LightsService( 2403): [SvcLED]  onSensorChanged::light value = 11
,D/LightsService( 2403): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 47
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 48
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 49
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4082): GC_CONCURRENT freed 2050K, 29% free 9727K/13604K, paused 2ms+2ms, total 28ms
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/TimaService( 2403): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2403): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2403): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,E/Watchdog( 2403): !@Sync 50
,D/TimaService( 2403): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 5521): GC_CONCURRENT freed 1902K, 24% free 10429K/13556K, paused 6ms+4ms, total 63ms
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2403): !@Sync 51
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2403): !@Sync 52
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 288, prevStep = 4, currStep = 4
,D/dalvikvm( 2403): GC_CONCURRENT freed 3744K, 72% free 24709K/87640K, paused 23ms+18ms, total 246ms
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2403): !@Sync 53
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2403): !@Sync 54
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 55
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 1625s ago
,E/Watchdog( 2403): !@Sync 56
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,E/SPPClientService( 5521): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 57
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2403): !@Sync 58
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 59
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/TimaService( 2403): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2403): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2403): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2403): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2403): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2403): !@Sync 60
,I/PowerManagerService( 2403): [PWL] Off : 1755s ago
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 61
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2403): Prepared write state in 54ms
,I/ProcessStatsService( 2403): Pruning old procstats: /data/system/procstats/state-2015-12-01-15-16-43.bin
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 62
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 63
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2403): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2403): <AppSync3 Whitelist>
,V/AlarmManager( 2403): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,I/ActivityManager( 2403): Killing 6196:com.google.android.music:main/u0a125 (adj 15): empty for 1824s
,I/ActivityManager( 2403): Killing 6160:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty for 1825s
,I/ActivityManager( 2403): Killing 6262:com.android.providers.calendar/u0a45 (adj 15): empty for 1825s
,I/ActivityManager( 2403): Killing 5990:com.android.calendar/u0a144 (adj 15): empty for 1825s
,I/ActivityManager( 2403): Killing 6323:com.sec.providers.settingsearch/u0a162 (adj 15): empty for 1825s
,I/ActivityManager( 2403): Killing 5383:com.google.android.talk/u0a109 (adj 15): empty for 1825s
,I/ActivityManager( 2403): Killing 6294:com.sec.phone/1001 (adj 15): empty for 1825s
,I/ActivityManager( 2403): Killing 5745:com.sec.android.diagmonagent/1000 (adj 15): empty for 1826s
,I/ActivityManager( 2403): Killing 5570:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty for 1826s
,I/ActivityManager( 2403): Killing 6340:com.sec.android.app.voicenote/1000 (adj 15): empty for 1828s
,I/ActivityManager( 2403): Killing 6313:com.sec.android.app.videoplayer/u0a53 (adj 15): empty for 1828s
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 64
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2403): [PWL] Off : 1890s ago
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 65
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,I/ActivityManager( 2403): Killing 6700:com.samsung.helphub/1000 (adj 15): empty for 1832s
,I/ActivityManager( 2403): Killing 6687:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1832s
,I/ActivityManager( 2403): Killing 6674:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty for 1832s
,I/ActivityManager( 2403): Killing 6661:com.sec.android.service.cm/u0a82 (adj 15): empty for 1832s
I/ActivityManager( 2403): Killing 6360:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1833s
,I/ActivityManager( 2403): Killing 5696:com.android.mms/u0a49 (adj 15): empty for 1833s
,I/ActivityManager( 2403): Killing 5803:com.osp.app.signin/u0a44 (adj 15): empty for 1833s
,I/ActivityManager( 2403): Killing 6635:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty for 1833s
,I/ActivityManager( 2403): Killing 6619:com.policydm/1000 (adj 15): empty for 1833s
,I/ActivityManager( 2403): Killing 6004:com.sec.android.app.shealth/u0a36 (adj 15): empty for 1833s
,I/ActivityManager( 2403): Killing 6603:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty for 1834s
,I/ActivityManager( 2403): Killing 6590:com.sec.pcw.device/1000 (adj 15): empty for 1834s
I/ActivityManager( 2403): Killing 6577:com.android.musicfx/u0a24 (adj 15): empty for 1834s
I/ActivityManager( 2403): Killing 6564:com.samsung.groupcast/u0a15 (adj 15): empty for 1834s
,I/ActivityManager( 2403): Killing 6441:com.google.android.partnersetup/u0a14 (adj 15): empty for 1834s
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,I/ActivityManager( 2403): Killing 6534:com.android.defcontainer/u0a6 (adj 15): empty for 1835s
,D/CountryDetector( 2403): No listener is left
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/dalvikvm( 2403): GC_CONCURRENT freed 3828K, 72% free 24598K/87640K, paused 10ms+12ms, total 169ms
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/BatteryService( 2403): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2403): !@Sync 66
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 67
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2403): waitForAlarm result :8
,D/NtpTrustedTime( 2403): currentTimeMillis() cache hit
V/NetworkStats( 2403): performPollLocked(flags=0x3)
,V/AlarmManager( 2403): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager( 2403): waitForAlarm result :12
,D/NtpTrustedTime( 2403): currentTimeMillis() cache hit
,V/NetworkStats( 2403): performPollLocked() took 62ms
D/NtpTrustedTime( 2403): currentTimeMillis() cache hit
D/NtpTrustedTime( 2403): currentTimeMillis() cache hit
,I/SELinux (11753): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (11753):  
,I/SELinux (11757): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (11757):  
,I/SELinux (11753): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (11753):  
I/SELinux (11753):  
,I/SELinux (11753): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux (11753): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm(11753): >>>>> Normal User
,E/dalvikvm(11753): >>>>> com.n7mobile.muzodajnia:main [ userId:0 | appId:10184 ]
,E/SELinux (11753): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider(11753): in addTimaSignatureService
I/SELinux (11757): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (11757):  
I/SELinux (11757):  
,I/SELinux (11757): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux (11757): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm(11757): >>>>> Normal User
,E/dalvikvm(11757): >>>>> com.google.android.youtube [ userId:0 | appId:10175 ]
,E/SELinux (11757): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider(11753): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(11753): Added TimaKesytore provider
,D/TimaKeyStoreProvider(11757): in addTimaSignatureService
,D/TimaKeyStoreProvider(11757): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(11757): Added TimaKesytore provider
,D/dalvikvm(11753): GC_CONCURRENT freed 3006K, 30% free 9571K/13568K, paused 4ms+2ms, total 30ms
,D/dalvikvm(11753): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/dalvikvm(11757): GC_CONCURRENT freed 3003K, 30% free 9565K/13560K, paused 3ms+3ms, total 37ms
,D/dalvikvm(11757): WAIT_FOR_CONCURRENT_GC blocked 32ms
,D/@ WidgetProvider(11753): onReceive = android.appwidget.action.APPWIDGET_UPDATE
,D/@ WidgetProvider(11753): onUpdate called for widgetId : 0
,D/@ WidgetProvider(11753): Widget random data : 7
,D/@ WidgetProvider(11753): onUpdate called for widgetId : 5
,D/@ WidgetProvider(11753): Widget random data : 4
,I/ActivityManager( 2403): Killing 6713:com.sec.kidsplat.installer/u0a160 (adj 15): empty for 1907s
,I/SensorManagerA( 2403): getReportingMode :: sensor.mType = 5
D/Sensors ( 2403): LightSensor setDelay = 200000000
E/dalvikvm(11753): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJson
W/dalvikvm(11753): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(11753): VFY: replacing opcode 0x22 at 0x0038
D/Sensors ( 2403): LightSensor setSensorDelay = 200000000
D/Sensors ( 2403): Light sensor flush: not enabled 0
E/dalvikvm(11753): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(11753): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(11753): VFY: replacing opcode 0x22 at 0x0038
,D/LightsService( 2403): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2403): LightSensor enable = 1
D/Sensors ( 2403): LightSensor enableSensor = 1
D/SensorManager( 2403): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
E/dalvikvm(11753): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(11753): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(11753): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(11753): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPUT
W/dalvikvm(11753): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(11753): VFY: replacing opcode 0x22 at 0x0038
,D/dalvikvm(11753): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJson
,D/dalvikvm(11753): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
D/dalvikvm(11753): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(11753): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPUT
,V/GLSActivity( 2849): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2849): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService( 2403): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController( 2579): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2579): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2579): updateDataNetType()
,D/STATUSBAR-NetworkController( 2579): NoService, mRoamingIconId = 0
,I/System.out(11753): Thread-627(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/Sensors ( 2403): LightSensor enable = 0
,D/LightsService( 2403): [SvcLED]  onSensorChanged::light value = 8
D/Sensors ( 2403): LightSensor enableSensor = 0
D/SensorManager( 2403): unregisterListener ::   
,I/System.out(11753): Thread-627(ApacheHTTPLog):isShipBuild true
,I/System.out(11753): Thread-627(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/LightsService( 2403): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/dalvikvm(11757): Could not find class 'android.app.Notification$Action$Builder', referenced from method b.a
W/dalvikvm(11757): VFY: unable to resolve new-instance 406 (Landroid/app/Notification$Action$Builder;) in Lb;
,D/dalvikvm(11757): VFY: replacing opcode 0x22 at 0x0000
,W/dalvikvm(11757): Unable to resolve superclass of Lal; (749)
W/dalvikvm(11757): Link of class 'Lal;' failed
E/dalvikvm(11757): Could not find class 'al', referenced from method b.a
W/dalvikvm(11757): VFY: unable to resolve new-instance 304 (Lal;) in Lb;
,D/dalvikvm(11757): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm(11757): Unable to resolve superclass of Lan; (749)
W/dalvikvm(11757): Link of class 'Lan;' failed
E/dalvikvm(11757): Could not find class 'an', referenced from method b.a
W/dalvikvm(11757): VFY: unable to resolve new-instance 358 (Lan;) in Lb;
,D/dalvikvm(11757): VFY: replacing opcode 0x22 at 0x002a
I/dalvikvm(11757): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method b.a
W/dalvikvm(11757): VFY: unable to resolve virtual method 5407: Landroid/view/ViewGroup;.isTransitionGroup ()Z
,D/dalvikvm(11757): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm(11757): Could not find method android.view.View.getTransitionName, referenced from method b.a
W/dalvikvm(11757): VFY: unable to resolve virtual method 5231: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm(11757): VFY: replacing opcode 0x6e at 0x0006
,W/dalvikvm(11757): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
,E/dalvikvm(11757): Could not find class 'android.app.RemoteInput[]', referenced from method b.a
W/dalvikvm(11757): VFY: unable to resolve new-array 12200 ([Landroid/app/RemoteInput;) in Lb;
,D/dalvikvm(11757): VFY: replacing opcode 0x23 at 0x0005
,D/dalvikvm(11757): DexOpt: unable to opt direct call 0x090f at 0x0e in Lb;.a
,W/dalvikvm(11757): Unable to resolve superclass of Lal; (749)
W/dalvikvm(11757): Link of class 'Lal;' failed
D/dalvikvm(11757): DexOpt: unable to opt direct call 0x068d at 0x08 in Lb;.a
W/dalvikvm(11757): Unable to resolve superclass of Lan; (749)
,W/dalvikvm(11757): Link of class 'Lan;' failed
,D/dalvikvm(11757): DexOpt: unable to opt direct call 0x0802 at 0x2c in Lb;.a
,D/dalvikvm(11757): DexOpt: unable to opt direct call 0x0957 at 0x13 in Lb;.a
,I/dalvikvm(11757): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method dyp.a
W/dalvikvm(11757): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm(11757): VFY: replacing opcode 0x6e at 0x000d
,I/System.out(11753): AsyncNetworking-1-thread-1 calls detatch()
,D/dalvikvm(11757): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm(11757): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm(11757): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm(11757): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm(11757): VFY: unable to resolve instance field 46
,D/dalvikvm(11757): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm(11757): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm(11757): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm(11757): VFY: replacing opcode 0x62 at 0x0047
,I/System.out(11753): AsyncNetworking-1-thread-1 calls detatch()
D/dalvikvm(11757): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm(11757): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
,D/dalvikvm(11757): Trying to load lib /data/app-lib/com.google.android.gms-4/libgmscore.so 0x422f8900
D/dalvikvm(11757): Added shared lib /data/app-lib/com.google.android.gms-4/libgmscore.so 0x422f8900
,D/dalvikvm(11757): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-4/libgmscore.so 0x422f8900, skipping init
,D/dalvikvm(11757): Trying to load lib /data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so 0x422f8900
D/dalvikvm(11757): Added shared lib /data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so 0x422f8900
,V/JNIHelp (11757): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,V/ImageManager(11753): Max ALLOWED memory (MB): 128
V/ImageManager(11753): Max SHOULD USE memory (MB): 128
,V/ImageManager(11753): Max Image Cache memory (MB): 32
,D/dalvikvm(11757): Trying to load lib /data/app-lib/com.google.android.gms-4/libgmscore.so 0x422f8900
,D/dalvikvm(11757): Shared lib '/data/app-lib/com.google.android.gms-4/libgmscore.so' already loaded in same CL 0x422f8900
D/dalvikvm(11757): Trying to load lib /data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so 0x422f8900
,D/dalvikvm(11757): Shared lib '/data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so' already loaded in same CL 0x422f8900
,D/skia    (11753): getTotalSize : Do not get file length
,D/@ WidgetProvider(11753): Building widget : 5
,I/dalvikvm(11757): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
W/dalvikvm(11757): VFY: unable to resolve static method 1165: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm(11757): VFY: replacing opcode 0x71 at 0x0046
,I/dalvikvm(11757): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.ma.a
W/dalvikvm(11757): VFY: unable to resolve virtual method 484: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm(11757): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm(11757): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.ma.b
W/dalvikvm(11757): VFY: unable to resolve virtual method 148: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm(11757): VFY: replacing opcode 0x6e at 0x0220
,D/dalvikvm(11757): DexOpt: --- BEGIN 'ads-2094907933.jar' (bootstrap=0) ---
,D/dalvikvm( 2775): GC_CONCURRENT freed 9004K, 40% free 18185K/30004K, paused 7ms+11ms, total 111ms
,D/dalvikvm( 2775): WAIT_FOR_CONCURRENT_GC blocked 84ms
,I/ProviderInstaller(11757): Installed default security provider GmsCore_OpenSSL
,E/YouTube MDX(11757): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/dalvikvm(11801): DexOpt: load 9ms, verify+opt 19ms, 194052 bytes
,D/dalvikvm(11757): DexOpt: --- END 'ads-2094907933.jar' (success) ---
,D/dalvikvm(11757): DEX prep '/data/data/com.google.android.youtube/cache/ads-2094907933.jar': unzip in 1ms, rewrite 145ms
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,W/ContextImpl(11757): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,D/dalvikvm(11757): GC_CONCURRENT freed 1979K, 22% free 10656K/13624K, paused 7ms+5ms, total 50ms
,D/dalvikvm(11757): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm(11757): WAIT_FOR_CONCURRENT_GC blocked 21ms
,I/dalvikvm(11757): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm(11757): VFY: unable to resolve virtual method 2614: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/ComponentName;)Landroid/graphics/drawable/Drawable;
D/dalvikvm(11757): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(11757): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm(11757): VFY: unable to resolve virtual method 2615: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/Intent;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm(11757): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(11757): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm(11757): VFY: unable to resolve virtual method 2622: Landroid/content/pm/PackageManager;.getApplicationBanner (Landroid/content/pm/ApplicationInfo;)Landroid/graphics/drawable/Drawable;
D/dalvikvm(11757): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(11757): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm(11757): VFY: unable to resolve virtual method 2623: Landroid/content/pm/PackageManager;.getApplicationBanner (Ljava/lang/String;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm(11757): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(11757): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method agv.getLeanbackLaunchIntentForPackage
W/dalvikvm(11757): VFY: unable to resolve virtual method 2639: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm(11757): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(11757): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method agv.getPackageInstaller
W/dalvikvm(11757): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm(11757): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(11757): Could not find method android.content.pm.PackageManager.getUserBadgedDrawableForDensity, referenced from method agv.getUserBadgedDrawableForDensity
W/dalvikvm(11757): VFY: unable to resolve virtual method 2659: Landroid/content/pm/PackageManager;.getUserBadgedDrawableForDensity (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;Landroid/graphics/Rect;I)Landroid/graphics/drawable/Drawable;
,D/dalvikvm(11757): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(11757): Could not find method android.content.pm.PackageManager.getUserBadgedIcon, referenced from method agv.getUserBadgedIcon
W/dalvikvm(11757): VFY: unable to resolve virtual method 2660: Landroid/content/pm/PackageManager;.getUserBadgedIcon (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm(11757): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(11757): Could not find method android.content.pm.PackageManager.getUserBadgedLabel, referenced from method agv.getUserBadgedLabel
W/dalvikvm(11757): VFY: unable to resolve virtual method 2661: Landroid/content/pm/PackageManager;.getUserBadgedLabel (Ljava/lang/CharSequence;Landroid/os/UserHandle;)Ljava/lang/CharSequence;
,D/dalvikvm(11757): VFY: replacing opcode 0x6e at 0x0002
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl(11757): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl(11757): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl(11757): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,W/InstanceID/Rpc(11757): Found 10012
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl(11757): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,I/ActivityManager( 2403): Killing 6725:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty for 1909s
,I/System.out(11757): Thread-692(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(11757): Thread-692(ApacheHTTPLog):isShipBuild true
,I/System.out(11757): Thread-692(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm(11757): GC_FOR_ALLOC freed 684K, 19% free 11108K/13624K, paused 38ms, total 38ms
,I/System.out(11757): Thread-692 calls detatch()
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2403): !@Sync 68
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 287, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2403): !@Sync 69
,V/AlarmManager( 2403): waitForAlarm result :8
,V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2579): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
,D/BatteryService( 2403): stay LED for fully charged
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4011): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4011): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2403): [PWL] Off : 2030s ago
,TIME-OUT KILL (timeout was 1800000ms),D/SSRMv2:SIOP( 2403): SIOP:: AP = 310, Delta = 0
D/AmoledAdjustTimer( 2403): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
D/AndroidRuntime(12068): 
D/AndroidRuntime(12068): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(12068): CheckJNI is OFF
D/AndroidRuntime(12068): setted country_code = Poland
D/AndroidRuntime(12068): setted countryiso_code = PL
D/AndroidRuntime(12068): setted sales_code = PLS
D/AndroidRuntime(12068): readGMSProperty: start
D/AndroidRuntime(12068): readGMSProperty: already setted!!
D/AndroidRuntime(12068): readGMSProperty: end
D/AndroidRuntime(12068): addProductProperty: start
D/dalvikvm(12068): Trying to load lib libjavacore.so 0x0
D/dalvikvm(12068): Added shared lib libjavacore.so 0x0
D/dalvikvm(12068): Trying to load lib libnativehelper.so 0x0
D/dalvikvm(12068): Added shared lib libnativehelper.so 0x0
D/dalvikvm(12068): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack(12068): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug(12068): failed to load memtrack module: -2
D/dalvikvm(12068): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime(12068): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 2403): START PACKAGE DELETE: observer{1153807488}
D/PackageManager( 2403): pkg{<packageName>}
D/PackageManager( 2403): user{0}
D/PackageManager( 2403): deletePackageAsUser : uid = 2000 userId = 0
D/ApplicationPolicy( 2403): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2403): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService( 2403): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2403): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 2403): !@killApplicatoin: 10491, uninstall pkg
I/ActivityManager( 2403): Killing 7098:com.test.thalitest/u0a491 (adj 11): stop com.test.thalitest
W/PackageSettings( 2403): Skipping PackageSetting{4232abd8 com.example.hello/10485} due to missing metadata
D/PackageManager( 2403): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10491, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/dalvikvm( 6751): GC_EXPLICIT freed 160K, 28% free 9962K/13784K, paused 5ms+12ms, total 62ms
D/dalvikvm( 6419): GC_EXPLICIT freed 2507K, 28% free 9888K/13564K, paused 5ms+17ms, total 77ms
D/PackageManager( 2403): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10491, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/dalvikvm( 2960): GC_EXPLICIT freed 1447K, 27% free 10032K/13564K, paused 10ms+8ms, total 111ms
I/FPMS_FingerprintManagerService( 2599): onReceive: android.intent.action.PACKAGE_REMOVED
E/SamsungIME( 2986): mOCRHelper is null
D/QuickConnect[1.1][2] ( 5129): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2403):   Scheme: "sms"
I/SELinux (12097): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12097):  
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/GeofencerStateMachine( 2734): Ignoring removeGeofence because network location is disabled.
I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2403):   Scheme: "smsto"
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux (12097): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12097):  
I/SELinux (12097):  
I/SELinux (12097): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12097): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(12097): >>>>> Normal User
E/dalvikvm(12097): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
E/SELinux (12097): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2403):   Scheme: "mms"
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/InputReader( 2403): Reconfiguring input devices.  changes=0x00000010
D/TimaKeyStoreProvider(12097): in addTimaSignatureService
I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2403):   Scheme: "mmsto"
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider(12097): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12097): Added TimaKesytore provider
D/RegisteredServicesCache( 2756): empty dynamic service
I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2403):   Scheme: "sms"
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm( 2403): GC_EXPLICIT freed 3185K, 72% free 24767K/87640K, paused 14ms+17ms, total 310ms
D/dalvikvm( 2403): WAIT_FOR_CONCURRENT_GC blocked 85ms
I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2403):   Scheme: "smsto"
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2403):   Scheme: "mms"
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2403):   Scheme: "mmsto"
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/RCPManagerService( 2403): PackageReceiver onReceive()
I/HarmonyEASService( 2403): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/dalvikvm(12097): GC_CONCURRENT freed 2989K, 30% free 9577K/13560K, paused 4ms+4ms, total 56ms
D/dalvikvm(12097): WAIT_FOR_CONCURRENT_GC blocked 42ms
D/elm:14132(12097): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132(12097): ELMEngine.ELMEngine( context ).
D/elm:14132(12097): MDMBridge.setEnterpriseBridge()
D/elm:14132(12097): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132(12097): ElmAgentService : onCreate()
D/elm:14132(12097): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132(12097): MainReceiver.listeningToPackageRemoved()
D/elm:14132(12097): MDMBridge.getInstance()
D/elm:14132(12097): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132(12097): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux (12110): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12110):  
D/elm:14132(12097): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/elm:14132(12097): ElmAgentService : onDestroy().
I/SELinux (12110): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12110):  
I/SELinux (12110):  
I/SELinux (12110): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12110): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(12110): >>>>> Normal User
E/dalvikvm(12110): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux (12110): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider(12110): in addTimaSignatureService
D/TimaKeyStoreProvider(12110): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12110): Added TimaKesytore provider
D/EnterpriseDeviceManagerService( 2403): Package has changed for user 0
W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm(12110): GC_CONCURRENT freed 2993K, 30% free 9580K/13564K, paused 6ms+5ms, total 45ms
D/dalvikvm(12110): WAIT_FOR_CONCURRENT_GC blocked 22ms
W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BackupManagerService( 2403): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 2403): removePackageParticipantsLocked: uid=10491 #1
W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux (12126): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12126):  
I/ActivityManager( 2403): Killing 6737:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty for 1968s
D/dalvikvm( 1921): GC_EXPLICIT freed 42K, 10% free 9507K/10544K, paused 3ms+4ms, total 40ms
I/SELinux (12126): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12126):  
I/SELinux (12126):  
I/SELinux (12126): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12126): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(12126): >>>>> Normal User
E/dalvikvm(12126): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
D/dalvikvm( 2403): GC_EXPLICIT freed 1015K, 72% free 24954K/87640K, paused 6ms+33ms, total 595ms
E/SELinux (12126): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 10% free 9507K/10544K, paused 3ms+4ms, total 33ms
D/TimaKeyStoreProvider(12126): in addTimaSignatureService
W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider(12126): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12126): Added TimaKesytore provider
D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 10% free 9507K/10544K, paused 3ms+5ms, total 33ms
W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager( 2403): delete sourFile : 
W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm(12126): GC_CONCURRENT freed 2997K, 30% free 9579K/13568K, paused 4ms+2ms, total 24ms
D/dalvikvm(12126): WAIT_FOR_CONCURRENT_GC blocked 12ms
D/PackageManager( 2403): delete native library directory: 
D/PackageManager( 2403): return delete result to caller: 1153807488
D/AndroidRuntime(12068): Shutting down VM
D/PackageManager( 2403): returnCode: 1
D/dalvikvm(12068): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 0ms+1ms, total 4ms
I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2403):   Scheme: "sms"
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2403):   Scheme: "smsto"
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux (12139): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12139):  
I/ActivityManager( 2403): Killing 6751:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty for 1967s
W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2403):   Scheme: "mms"
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ApplicationsProvider( 2960): Could not fetch usage stats
W/ApplicationsProvider( 2960): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2960): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2960): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2960): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2960): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2960): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2960): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2960): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2960): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2960): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2960): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2960): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2403):   Scheme: "mmsto"
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux (12139): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12139):  
I/SELinux (12139):  
I/SELinux (12139): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12139): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(12139): >>>>> Normal User
E/dalvikvm(12139): >>>>> com.android.musicfx [ userId:0 | appId:10024 ]
E/SELinux (12139): [DEBUG] seapp_context_lookup: seinfoCategory = release
W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/TimaKeyStoreProvider(12139): in addTimaSignatureService
D/TimaKeyStoreProvider(12139): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12139): Added TimaKesytore provider
W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector( 2403): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 2403): clearDefaults: com.test.thalitest
D/dalvikvm(12139): GC_CONCURRENT freed 3014K, 30% free 9564K/13568K, paused 4ms+2ms, total 32ms
D/dalvikvm(12139): WAIT_FOR_CONCURRENT_GC blocked 26ms
I/SELinux (12155): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12155):  
I/SELinux (12155): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12155):  
I/SELinux (12155):  
I/SELinux (12155): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12155): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(12155): >>>>> Normal User
E/dalvikvm(12155): >>>>> com.sec.pcw.device [ userId:0 | appId:1000 ]
E/SELinux (12155): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/dalvikvm(12155): Enabling JNI app bug workarounds for target SDK version 8...
I/ActivityManager( 2403): Killing 5972:com.sec.android.app.samsungapps/u0a41 (adj 15): empty for 1967s
D/TimaKeyStoreProvider(12155): in addTimaSignatureService
D/TimaKeyStoreProvider(12155): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12155): Added TimaKesytore provider
D/dalvikvm(12155): GC_CONCURRENT freed 2992K, 30% free 9579K/13564K, paused 3ms+2ms, total 25ms
D/dalvikvm(12155): WAIT_FOR_CONCURRENT_GC blocked 22ms
E/SQLiteDatabase(12155): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase(12155): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12155): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12155): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(12155): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(12155): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12155): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12155): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12155): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(12155): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(12155): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(12155): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(12155): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(12155): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase(12155): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase(12155): 	at com.sec.pcw.device.contentprovider.URLProvider.onCreate(URLProvider.java:30)
E/SQLiteDatabase(12155): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase(12155): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase(12155): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase(12155): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase(12155): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase(12155): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(12155): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(12155): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12155): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(12155): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(12155): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(12155): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(12155): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(12155): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(12155): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(12155): Shutting down VM
W/dalvikvm(12155): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime(12155): FATAL EXCEPTION: main
E/AndroidRuntime(12155): Process: com.sec.pcw.device, PID: 12155
E/AndroidRuntime(12155): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.URLProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12155): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime(12155): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime(12155): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime(12155): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime(12155): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime(12155): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12155): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(12155): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(12155): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(12155): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(12155): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(12155): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(12155): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(12155): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12155): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12155): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(12155): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(12155): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12155): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12155): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12155): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(12155): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(12155): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(12155): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(12155): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(12155): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime(12155): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime(12155): 	at com.sec.pcw.device.contentprovider.URLProvider.onCreate(URLProvider.java:30)
E/AndroidRuntime(12155): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime(12155): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime(12155): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime(12155): 	... 12 more
E/DropBoxManagerService( 2403): Can't write: system_app_crash
E/DropBoxManagerService( 2403): java.io.FileNotFoundException: /data/system/dropbox/drop232.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2403): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2403): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2403): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2403): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2403): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2403): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2403): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2403): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2403): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2403): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2403): 	... 5 more
I/SELinux (12168): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12168):  
I/Process (12155): Sending signal. PID: 12155 SIG: 9
I/ActivityManager( 2403): Process com.sec.pcw.device (pid 12155) (adj 0) has died.
I/SELinux (12168): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12168):  
I/SELinux (12168):  
I/SELinux (12168): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12168): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(12168): >>>>> Normal User
E/dalvikvm(12168): >>>>> com.samsung.android.app.galaxyfinder [ userId:0 | appId:10035 ]
E/SELinux (12168): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider(12168): in addTimaSignatureService
D/TimaKeyStoreProvider(12168): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12168): Added TimaKesytore provider
D/dalvikvm(12168): GC_CONCURRENT freed 2998K, 30% free 9574K/13568K, paused 4ms+2ms, total 27ms
D/dalvikvm(12168): WAIT_FOR_CONCURRENT_GC blocked 21ms
W/System.err(12168): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory)
W/System.err(12168): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err(12168): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err(12168): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err(12168): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err(12168): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
W/System.err(12168): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err(12168): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err(12168): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
W/System.err(12168): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:104)
W/System.err(12168): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:88)
W/System.err(12168): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err(12168): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err(12168): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err(12168): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err(12168): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(12168): 	at android.os.Looper.loop(Looper.java:146)
W/System.err(12168): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err(12168): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err(12168): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err(12168): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err(12168): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err(12168): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err(12168): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err(12168): 	at libcore.io.Posix.open(Native Method)
W/System.err(12168): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err(12168): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err(12168): 	... 21 more
D/GalaxyFinderApplication(12168): [Slink platform] Version = 29011
D/GalaxyFinderApplication(12168): [Slink platform] use state of slink location service is [false] to [true]
I/SELinux (12182): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12182):  
I/ActivityManager( 2403): Killing 6400:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty for 1968s
I/SELinux (12182): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12182):  
I/SELinux (12182):  
I/SELinux (12182): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12182): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(12182): >>>>> Normal User
E/dalvikvm(12182): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10036 ]
E/SELinux (12182): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider(12182): in addTimaSignatureService
D/TimaKeyStoreProvider(12182): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12182): Added TimaKesytore provider
D/dalvikvm(12182): GC_CONCURRENT freed 2995K, 30% free 9580K/13568K, paused 2ms+2ms, total 23ms
D/dalvikvm(12182): WAIT_FOR_CONCURRENT_GC blocked 21ms
W/ContextImpl(12182): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
E/Device Type Shared Preferences(12182): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences(12182): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication(12182): ContentProvider is not null
W/ResourceType(12182): No package identifier when getting value for resource number 0x00000000
I/System.out(12182): resource Id::2131361807
E/SQLiteDatabase(12182): Failed to open database '/data/data/com.sec.android.app.shealth/databases/base.db'.
E/SQLiteDatabase(12182): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12182): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12182): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(12182): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(12182): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12182): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12182): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12182): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(12182): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(12182): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(12182): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(12182): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(12182): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/SQLiteDatabase(12182): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/SQLiteDatabase(12182): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:121)
E/SQLiteDatabase(12182): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericQuery(BaseContentProvider.java:296)
E/SQLiteDatabase(12182): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.query(BaseContentProvider.java:231)
E/SQLiteDatabase(12182): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/SQLiteDatabase(12182): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/SQLiteDatabase(12182): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/SQLiteDatabase(12182): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/SQLiteDatabase(12182): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.getPluginRegistryData(AppRegistryDbManagerWithProvider.java:197)
E/SQLiteDatabase(12182): 	at com.sec.android.app.shealth.SHealthApplication.getPreloadedAppRegistryData(SHealthApplication.java:363)
E/SQLiteDatabase(12182): 	at com.sec.android.app.shealth.SHealthApplication.loadPreInstalledPLuginsData(SHealthApplication.java:597)
E/SQLiteDatabase(12182): 	at com.sec.android.app.shealth.SHealthApplication.loadAppRegistryData(SHealthApplication.java:443)
E/SQLiteDatabase(12182): 	at com.sec.android.app.shealth.SHealthApplication.onCreate(SHealthApplication.java:186)
E/SQLiteDatabase(12182): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
E/SQLiteDatabase(12182): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
E/SQLiteDatabase(12182): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(12182): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(12182): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12182): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(12182): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(12182): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(12182): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(12182): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(12182): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(12182): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(12182): Shutting down VM
W/dalvikvm(12182): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime(12182): FATAL EXCEPTION: main
E/AndroidRuntime(12182): Process: com.sec.android.app.shealth, PID: 12182
E/AndroidRuntime(12182): java.lang.RuntimeException: Unable to create application com.sec.android.app.shealth.SHealthApplication: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12182): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4793)
E/AndroidRuntime(12182): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime(12182): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime(12182): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12182): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(12182): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(12182): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(12182): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(12182): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(12182): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(12182): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(12182): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12182): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12182): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(12182): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(12182): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12182): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12182): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12182): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(12182): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(12182): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(12182): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(12182): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(12182): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/AndroidRuntime(12182): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/AndroidRuntime(12182): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:121)
E/AndroidRuntime(12182): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericQuery(BaseContentProvider.java:296)
E/AndroidRuntime(12182): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.query(BaseContentProvider.java:231)
E/AndroidRuntime(12182): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/AndroidRuntime(12182): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/AndroidRuntime(12182): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/AndroidRuntime(12182): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/AndroidRuntime(12182): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.getPluginRegistryData(AppRegistryDbManagerWithProvider.java:197)
E/AndroidRuntime(12182): 	at com.sec.android.app.shealth.SHealthApplication.getPreloadedAppRegistryData(SHealthApplication.java:363)
E/AndroidRuntime(12182): 	at com.sec.android.app.shealth.SHealthApplication.loadPreInstalledPLuginsData(SHealthApplication.java:597)
E/AndroidRuntime(12182): 	at com.sec.android.app.shealth.SHealthApplication.loadAppRegistryData(SHealthApplication.java:443)
E/AndroidRuntime(12182): 	at com.sec.android.app.shealth.SHealthApplication.onCreate(SHealthApplication.java:186)
E/AndroidRuntime(12182): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
E/AndroidRuntime(12182): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
E/AndroidRuntime(12182): 	... 10 more
E/DropBoxManagerService( 2403): Can't write: system_app_crash
E/DropBoxManagerService( 2403): java.io.FileNotFoundException: /data/system/dropbox/drop233.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2403): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2403): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2403): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2403): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2403): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2403): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2403): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2403): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2403): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2403): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2403): 	... 5 more
I/SELinux (12202): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12202):  
I/Process (12182): Sending signal. PID: 12182 SIG: 9
I/ActivityManager( 2403): Process com.sec.android.app.shealth (pid 12182) (adj 0) has died.
D/HeadlinesChannelApplication( 5869): HeadlinesChannelApplication.onTrimMemory(). level : 40
I/EsApplication( 5934): Trimming memory (onTrimMemory 40)
V/SamsungIME( 2986): onTrimMeomory Level = 5
I/SELinux (12202): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12202):  
I/SELinux (12202):  
I/SELinux (12202): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12202): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm(12202): >>>>> Normal User
E/dalvikvm(12202): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10043 ]
E/SELinux (12202): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/rsC++   ( 2775): RS Message thread exiting.
E/OpenGLRenderer( 2775): SFEffectCache:clear(), mSize = 0
D/Launcher( 2775): onTrimMemory. Level: 80
W/ManagedEGLContext( 2775): doTerminate failed: EGL count is 2 but managed count is 1
W/GeoLookout( 3086): at (DisasterAlertApplication.java:67) [onTrimMemory()]

```
