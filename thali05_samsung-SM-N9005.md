#### Test 50650278eab32a5_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
E/SMD     (  289): DCD ON
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
D/AndroidRuntime( 6168): 
D/AndroidRuntime( 6168): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6168): CheckJNI is OFF
D/AndroidRuntime( 6168): readGMSProperty: start
D/AndroidRuntime( 6168): readGMSProperty: already setted!!
D/AndroidRuntime( 6168): readGMSProperty: end
D/AndroidRuntime( 6168): addProductProperty: start
E/AffinityControl( 6168): AffinityControl: registerfunction enter
D/AndroidRuntime( 6168): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  896): inState():  stateMachine is null !!
I/PersonaManagerService(  896): PersonaId don't exist
I/ActivityManager(  896): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
I/ActivityManager(  896): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  896): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  896): mDVFSHelper.acquire()
D/FocusedStackFrame(  896): Set to : 0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6184): MountEmulatedStorage()
E/Zygote  ( 6184): v2
I/libpersona( 6184): KNOX_SDCARD checking this for 10272
I/libpersona( 6184): KNOX_SDCARD not a persona
I/ActivityManager(  896): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6184 uid=10272 gids={50272, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6184): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6184): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
D/PointerIcon(  896): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  896): setMouseCustomIcon IconType is same.101
D/PointerIcon(  896): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  896): setHoveringSpenCustomIcon IconType is same.1
E/SELinux ( 6184): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 6168): Shutting down VM
D/TimaKeyStoreProvider( 6184): TimaSignature is unavailable
D/ActivityThread( 6184): Added TimaKeyStore provider
V/WindowOrientationListener(  896): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  896): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  896): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  896): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  896): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/SurfaceWidgetView( 1435): destroyHardwareResources():251750094
D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 6184): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger(  254): id=6 Removed Mauncher (6/8)
I/SurfaceFlinger(  254): id=6 Removed Mauncher (-2/8)
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1807): [237392/8] Surface widget visibility changed visibility = false on instance = 1
V/ActivityThread( 1435): updateVisibility : ActivityRecord{3fe11a77 token=android.os.BinderProxy@267fffd3 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1435): onTrimMemory. Level: 20
,I/WebViewFactory( 6184): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 6184): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 6184): Loading: webviewchromium
,I/LibraryLoader( 6184): Time to load native libraries: 6 ms (timestamps 9022-9028)
I/LibraryLoader( 6184): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6184): Binding Chromium to main looper Looper (main, tid 1) {3d452891}
,I/LibraryLoader( 6184): Expected native library version number "",actual native library version number ""
,I/chromium( 6184): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6184): Initializing chromium process, renderers=0
,W/art     ( 6184): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6184): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium( 6184): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6184): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=36 off=46780 len=2953
I/chromium( 6184): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:35 off:229536 len:643667
D/BluetoothAdapter( 6184): 435463158: getState() :  mService = null. Returning STATE_OFF
,I/Adreno-EGL( 6184): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6184): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6184): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6184): Local Branch: mybranch5813579
I/Adreno-EGL( 6184): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6184): Local Patches: NONE
I/Adreno-EGL( 6184): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,W/chromium( 6184): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/ActivityManager(  896): Activity pause timeout for ActivityRecord{3aacd30c u0 com.test.thalitest/.MainActivity t3}
,W/chromium( 6184): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 6184): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6184): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6184): CordovaWebView is running on device made by: samsung
,W/art     ( 6184): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6184): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity( 6184): performCreate Call secproduct feature valuefalse
D/Activity( 6184): performCreate Call debug elastic valuetrue
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,D/OpenGLRenderer( 6184): Render dirty regions requested: true
,D/Atlas   ( 6184): Validating map...
,D/ActivityManager(  896): post active user change for 0
,D/KnoxTimeoutHandler(  896): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  896): handleActiveUserChange for user 0
,V/ActivityThread( 6184): updateVisibility : ActivityRecord{1002c8e7 token=android.os.BinderProxy@2f05801 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/SurfaceFlinger(  254): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService(  896): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  896): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon(  896): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  896): setMouseCustomIcon IconType is same.101
D/PointerIcon(  896): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  896): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer( 6184): Initialized EGL, version 1.4
,I/OpenGLRenderer( 6184): HWUI protection enabled for context ,  &this =0xb3a64ab0 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 6184): Enabling debug mode 0
,D/InputMethodManagerService(  896): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  896): SIOP:: AP = 300, PST = 321, CUR = 450
,W/ActivityManager(  896): mDVFSHelper.release()
I/Timeline(  896): Timeline: Activity_windows_visible id: ActivityRecord{3aacd30c u0 com.test.thalitest/.MainActivity t3} time:159636
,I/art     (  896): Explicit concurrent mark sweep GC freed 240742(16MB) AllocSpace objects, 32(4MB) LOS objects, 17% free, 37MB/45MB, paused 1.629ms total 151.816ms
,W/IInputConnectionWrapper( 6184): showStatusIcon on inactive InputConnection
,I/Timeline( 6184): Timeline: Activity_idle id: android.os.BinderProxy@2f05801 time:159802
,I/SamsungIME( 1742): getCurrentCandidateView
,D/SamsungIME( 1742): Dismiss ExpandCandiate
,D/JsMessageQueue( 6184): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 6184): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6184): 
,I/SamsungIME( 1742): getDebugLevel  : 0x4f4c
,D/jxcore_app_log( 6184): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1661601152
D/JX-Cordova( 6184): jxcore cordova android initializing
,I/SamsungIME( 1742): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1742): KeybaordView init() : load resources
,I/SamsungIME( 1742): getCurrentKeyboard
,I/SamsungIME( 1742): getTextKeyboard
,D/SamsungIME( 1742): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/SamsungIME( 1742): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,W/jxcore-log( 6184): Initializing JXcore engine
,W/jxcore-log( 6184): JXcore engine is ready
,W/jxcore-log( 6184): Starting JXcore engine
,E/auditd  ( 1857): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  896): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,D/SecurityLogAgent:SEDenialService(  896): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,E/Zygote  ( 6257): MountEmulatedStorage()
I/libpersona( 6257): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6257): v2
I/libpersona( 6257): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6257 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/art     (  340): Explicit concurrent mark sweep GC freed 8772(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 299us total 23.652ms
,I/art     (  340): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 264us total 9.703ms
,I/SELinux ( 6257): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/art     (  340): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 260us total 10.014ms
,I/SELinux ( 6257): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6257): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6257): TimaSignature is unavailable
,D/ActivityThread( 6257): Added TimaKeyStore provider
,D/ResourcesManager( 6257): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,W/jxcore-log( 6184): Platform android
W/jxcore-log( 6184): 
,W/jxcore-log( 6184): Process ARCH arm
W/jxcore-log( 6184): 
,D/SecurityLogAgent( 6257):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 6257):  SeDenialReceiver : File path = null
,I/ActivityManager(  896): Killing 5302:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
,I/jxcore-log( 6184): JXcore Cordova bridge is ready!
I/jxcore-log( 6184): 
,W/jxcore-log( 6184): JXcore engine is started
,E/jxcore  ( 6184): Error!: missing ) after argument list
E/jxcore  ( 6184): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 6184): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 6184): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  896): Killing 5098:com.sec.providers.settingsearch/u0a191 (adj 15): bgCount ##41
,W/PluginManager( 6184): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 21ms. Plugin should use CordovaInterface.getThreadPool().
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ScreenOrientationListener( 6184): Removing an inexistent observer!
,I/SurfaceFlinger(  254): id=13 Removed NainActivit (6/8)
,I/SurfaceFlinger(  254): id=13 Removed NainActivit (-2/8)
,D/PointerIcon(  896): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  896): setMouseCustomIcon IconType is same.101
D/PointerIcon(  896): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  896): setHoveringSpenCustomIcon IconType is same.1
,D/FocusedStackFrame(  896): Set to : 0
,E/ViewRootImpl( 6184): sendUserActionEvent() mView == null
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  353): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD ON
,E/Watchdog(  896): !@Sync 5
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/PackageManager(  896): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/SSRM:n  (  896): SIOP:: AP = 300, PST = 316, CUR = 450
,E/SMD     (  289): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  896): waitForAlarm result :8
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 75s ago
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 300, PST = 308, CUR = 450
,E/SMD     (  289): DCD ON
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  353): AtCmdFwd service not published, waiting... retryCnt : 5
,I/ClearcutLoggerApiImpl( 1477): disconnect managed GoogleApiClient
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 303, CUR = 450
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  896): !@Sync 6
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 300, CUR = 450
,E/SMD     (  289): DCD ON
,V/AlarmManager(  896): waitForAlarm result :4
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1183): handleTimeUpdate
,D/KeyguardEffectViewController( 1183): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1183): *** don't update sliding image ***
,D/NtpTrustedTime(  896): forceRefresh() from cache miss
,D/NtpTrustedTime(  896): forceRefresh Fail.
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 105s ago
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 298, CUR = 450
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/Atfwd_Sendcmd(  353): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  353): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 296, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,E/Watchdog(  896): !@Sync 7
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  353): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 295, CUR = 450
,E/SMD     (  289): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  896): waitForAlarm result :8
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  353): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 140s ago
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 294, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 293, CUR = 450
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  353): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  289): DCD ON
,E/Watchdog(  896): !@Sync 8
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 292, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 291, CUR = 450
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  353): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 180s ago
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): stay LED for fully charged
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/Watchdog(  896): !@Sync 9
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 290, CUR = 450
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): stay LED for fully charged
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,E/SMD     (  289): DCD ON
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  353): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 289, CUR = 450
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService(  896): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  896): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  896): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  896): initializing...
,I/TLC_TIMA_PKM_initialize(  896): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  896): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  896): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  896): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  896): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  896): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  896): max_message_size = 524416 = 0x80080,
D/QSEECOMAPI: (  896): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: (  896): App is not loaded in QSEE
,D/QSEECOMAPI: (  896): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  896): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  896): Trustlet response is completed
,E/SMD     (  289): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  896): !@Sync 10
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 289, CUR = 450
,E/SMD     (  289): DCD ON
,I/Atfwd_Sendcmd(  353): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  353): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  896): [PWL] Off : 225s ago
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,V/GLSActivity( 1568): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1568): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1568): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 3349): (HTTPLog)-Static: isSBSettingEnabled false
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 289, CUR = 450
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  896): waitForAlarm result :4
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): stay LED for fully charged
,E/Zygote  ( 6316): MountEmulatedStorage()
,E/Zygote  ( 6316): v2
I/libpersona( 6316): KNOX_SDCARD checking this for 10096
I/libpersona( 6316): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=6316 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1183): handleTimeUpdate
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardEffectViewController( 1183): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1183): *** don't update sliding image ***
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
I/SELinux ( 6316): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6316): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6316): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/TimaKeyStoreProvider( 6316): TimaSignature is unavailable
,D/ActivityThread( 6316): Added TimaKeyStore provider
,D/ResourcesManager( 6316): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,D/SurfaceWidgetView( 1435): destroyHardwareResources():251750094
,V/WindowOrientationListener(  896): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
,V/WindowOrientationListener(  896): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  896): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  896): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  896): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,E/SMD     (  289): DCD ON
,D/Launcher( 1435): onRestart, Launcher: 952043906
,D/Launcher( 1435): onStart, Launcher: 952043906
D/Launcher.HomeView( 1435): onStart
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1807): [237392/8] Surface widget visibility changed visibility = true on instance = 1
V/ActivityThread( 1435): updateVisibility : ActivityRecord{3fe11a77 token=android.os.BinderProxy@267fffd3 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,D/SurfaceWidget.Renderer( 1807): [237392/8] SurfaceWidget drawing first frame
,D/accuweather( 1807): [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
,I/SurfaceFlinger(  254): id=14 createSurf (1080x1920),1 flag=4, Mauncher
,D/StatusBarManagerService(  896): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  896): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon(  896): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon(  896): setMouseCustomIcon IconType is same.101
D/PointerIcon(  896): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  896): setHoveringSpenCustomIcon IconType is same.1
,D/InputMethodManagerService(  896): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 6184): showStatusIcon on inactive InputConnection
,I/ActivityManager(  896): Killing 4401:com.android.providers.calendar/u0a51 (adj 15): bgCount ##41
,E/lowmemorykiller(  251): Error writing /proc/4401/oom_score_adj; errno=22
,I/Timeline(  896): Timeline: Activity_windows_visible id: ActivityRecord{1a8e3fd2 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:332351
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 289, CUR = 450
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): stay LED for fully charged
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  353): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  289): DCD ON
,E/Watchdog(  896): !@Sync 11
,E/SMD     (  289): DCD ON
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 288, CUR = 450
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  896): waitForAlarm result :8
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  353): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 287, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  353): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 286, CUR = 450
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 275s ago
,E/Watchdog(  896): !@Sync 12
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 285, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  353): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 284, CUR = 450
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 283, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/Watchdog(  896): !@Sync 13
,E/SMD     (  289): DCD ON
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 283, CUR = 450
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  353): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 330s ago
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 281, CUR = 450
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  896): setPowerConnected  = true
D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/Watchdog(  896): !@Sync 14
,E/SMD     (  289): DCD ON
,I/Atfwd_Sendcmd(  353): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  353): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  353): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  289): DCD ON
,E/Watchdog(  896): !@Sync 15
,E/SMD     (  289): DCD ON
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  353): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,I/bootchecker(  347): bootchecker wake up!!
,E/SMD     (  289): DCD ON
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,W/Atfwd_Sendcmd(  353): AtCmdFwd service not published, waiting... retryCnt : 3
,I/PowerManagerService(  896): [PWL] Off : 390s ago
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,E/SMD     (  289): DCD ON
,E/Watchdog(  896): !@Sync 16
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  353): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/Watchdog(  896): !@Sync 17
,E/SMD     (  289): DCD ON
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  896): waitForAlarm result :8
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,I/ServiceManager(  353): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  353): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 455s ago
,E/Watchdog(  896): !@Sync 18
,E/SMD     (  289): DCD ON
,I/Atfwd_Sendcmd(  353): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  353): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,I/Atfwd_Daemon(  353): Stop the daemon....
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/Watchdog(  896): !@Sync 19
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/TimaService(  896): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  896): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  896): TimaServiceHandler.handleMessage what =1
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  896): !@Sync 20
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): stay LED for fully charged
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  896): [PWL] Off : 525s ago
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,V/GLSActivity( 1568): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1568): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1568): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 3349): (HTTPLog)-Static: isSBSettingEnabled false
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,I/ActivityManager(  896): Killing 5133:com.google.android.talk/u0a131 (adj 15): bgCount ##41
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/Watchdog(  896): !@Sync 21
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/Watchdog(  896): !@Sync 22
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 600s ago
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  896): !@Sync 23
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  896): !@Sync 24
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  896): !@Sync 25
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 680s ago
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  896): !@Sync 26
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): stay LED for fully charged
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  896): !@Sync 27
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): stay LED for fully charged
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  896): !@Sync 28
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 765s ago
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
D/BatteryService(  896): stay LED for fully charged
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  896): !@Sync 29
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
D/BatteryService(  896): stay LED for fully charged
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/TimaService(  896): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  896): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  896): TimaServiceHandler.handleMessage what =1
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,E/Watchdog(  896): !@Sync 30
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,V/GLSActivity( 1568): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1568): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1568): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 3349): (HTTPLog)-Static: isSBSettingEnabled false
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/Watchdog(  896): !@Sync 31
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,I/PowerManagerService(  896): [PWL] Off : 855s ago
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/Watchdog(  896): !@Sync 32
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/Watchdog(  896): !@Sync 33
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/Watchdog(  896): !@Sync 34
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 950s ago
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/Watchdog(  896): !@Sync 35
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/Watchdog(  896): !@Sync 36
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,E/Watchdog(  896): !@Sync 37
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 1050s ago
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  896): !@Sync 38
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 279, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 278, CUR = 450
,E/Watchdog(  896): !@Sync 39
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 277, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 276, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/TimaService(  896): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  896): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  896): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  896): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  896): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  896): Updating Usage Statistics in DB @ 1449669802413
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  896): Done Updating Usage Statistics in DB @ 1449669802597
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 276, CUR = 450
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  896): !@Sync 40
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 276, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,V/GLSActivity( 1568): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1568): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1568): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 3349): (HTTPLog)-Static: isSBSettingEnabled false
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 276, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 276, CUR = 450
,E/Watchdog(  896): !@Sync 41
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 1155s ago
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 276, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 276, CUR = 450
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 276, CUR = 450
,E/Watchdog(  896): !@Sync 42
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,V/AlarmManager(  896): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1183): handleTimeUpdate
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardEffectViewController( 1183): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1183): *** don't update sliding image ***
,D/LightsService(  896): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  896): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  896): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 1726): Aggregate from 1449668071657 (log), 1449668071657 (data)
,D/LightsService(  896): [SvcLED]  onSensorChanged::light value = 1
,E/LightSensor(  896): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  896): unregisterListener ::   
D/LightsService(  896): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 277, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 278, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 278, CUR = 450
,E/Watchdog(  896): !@Sync 43
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,V/AlarmManager(  896): waitForAlarm result :8
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): stay LED for fully charged
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 277, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 276, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 275, CUR = 450
,E/Watchdog(  896): !@Sync 44
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 274, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 273, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService(  896): [PWL] Off : 1265s ago
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 272, CUR = 450
,E/Watchdog(  896): !@Sync 45
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 272, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): stay LED for fully charged
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 271, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/Watchdog(  896): !@Sync 46
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,E/Watchdog(  896): !@Sync 47
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/Watchdog(  896): !@Sync 48
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 1380s ago
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,E/Watchdog(  896): !@Sync 49
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/TimaService(  896): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  896): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  896): TimaServiceHandler.handleMessage what =1
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  896): !@Sync 50
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 271, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 272, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,V/GLSActivity( 1568): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1568): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1568): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 3349): (HTTPLog)-Static: isSBSettingEnabled false
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 273, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  896): !@Sync 51
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 273, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 273, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 273, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  896): !@Sync 52
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 273, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 273, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 273, CUR = 450
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 1500s ago
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  896): !@Sync 53
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 273, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 272, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 271, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  896): !@Sync 54
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  896): !@Sync 55
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  896): !@Sync 56
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 1625s ago
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  896): !@Sync 57
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  896): stay LED for fully charged
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  896): !@Sync 58
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  896): !@Sync 59
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 270, CUR = 450,
,E/SMD     (  289): DCD ON,
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/TimaService(  896): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  896): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  896): TimaServiceHandler.handleMessage what =1
,E/SMD     (  289): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  896): !@Sync 60
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 271, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
D/BatteryService(  896): stay LED for fully charged
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 271, CUR = 450
,E/SMD     (  289): DCD ON
,V/GLSActivity( 1568): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  896): Prepared write state in 10ms
,V/GLSActivity( 1568): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1568): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 3349): (HTTPLog)-Static: isSBSettingEnabled false
,I/ProcessStatsService(  896): Pruning old procstats: /data/system/procstats/state-2015-12-08-19-11-04.bin
,E/SMD     (  289): DCD ON
,V/AlarmManager(  896): waitForAlarm result :8
,D/NtpTrustedTime(  896): forceRefresh() from cache miss
,D/NtpTrustedTime(  896): forceRefresh Fail.
,V/NetworkStats(  896): performPollLocked(flags=0x3)
,D/NetworkStatsFactory(  896): UpdateStatsForKnox,
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1183): handleTimeUpdate
,D/KeyguardEffectViewController( 1183): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1183): *** don't update sliding image ***
,V/NetworkStats(  896): performPollLocked() took 44ms
,D/NtpTrustedTime(  896): forceRefresh() from cache miss
,D/NtpTrustedTime(  896): forceRefresh Fail.
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/System.out( 1568): (HTTPLog)-Static: isSBSettingEnabled false
,E/SQLiteLog( 1568): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 272, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  896): !@Sync 61
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 272, CUR = 450
,E/SMD     (  289): DCD ON
,V/AlarmManager(  896): waitForAlarm result :8
,E/SMD     (  289): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 1755s ago
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 272, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 272, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  896): !@Sync 62
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 272, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 272, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 272, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  896): !@Sync 63
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 272, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 271, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 271, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  896): !@Sync 64
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/Watchdog(  896): !@Sync 65
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  896): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  289): DCD ON
,E/SMD     (  289): DCD ON
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 6513): 
D/AndroidRuntime( 6513): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6513): CheckJNI is OFF
D/AndroidRuntime( 6513): readGMSProperty: start
D/AndroidRuntime( 6513): readGMSProperty: already setted!!
D/AndroidRuntime( 6513): readGMSProperty: end
D/AndroidRuntime( 6513): addProductProperty: start
E/AffinityControl( 6513): AffinityControl: registerfunction enter
D/AndroidRuntime( 6513): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService(  896): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager(  896): START PACKAGE DELETE: observer{232703116}
D/PackageManager(  896): pkg{<packageName>}
D/PackageManager(  896): user{0}
D/PackageManager(  896): caller{2000}
D/PackageManager(  896): flags{3}
D/PersonaManagerService(  896): isFromApprovedUnInstaller: isApproved : true
D/PackageManager(  896): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService(  896): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  896): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  896): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService(  896): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManager(  896): !@killApplicatoin: 10272, uninstall pkg
D/PackageManagerService(  896): deletePackage- pkg:com.test.thalitest, edmuserId:-1
I/ActivityManager(  896): Force stopping com.test.thalitest appid=10272 user=-1: uninstall pkg
D/ApplicationPolicy(  896): getApplicationUninstallationEnabled
I/ActivityManager(  896): Killing 6184:com.test.thalitest/u0a272 (adj 9): stop com.test.thalitest
D/ApplicationPolicy(  896): getApplicationUninstallationEnabled :  enabled true
W/PackageSettings(  896): Skipping PackageSetting{428e29a com.example.hello/10268} due to missing metadata
I/ActivityManager(  896): Killing 6005:com.samsung.android.app.watchmanagerstub/u0a126 (adj 9): empty for 1903s
I/ActivityManager(  896): Killing 5985:com.samsung.android.app.filterinstaller/1000 (adj 11): empty for 1903s
E/SMD     (  289): DCD ON
I/ActivityManager(  896): Killing 5965:com.google.android.apps.docs/u0a112 (adj 11): empty for 1903s
I/ActivityManager(  896): Killing 5444:com.sec.chaton/u0a102 (adj 11): empty for 1905s
I/ActivityManager(  896): Killing 5118:com.samsung.android.app.assistantmenu/1000 (adj 11): empty for 1905s
I/ActivityManager(  896): Killing 5945:com.sec.android.app.soundalive/u0a64 (adj 11): empty for 1905s
I/ActivityManager(  896): Killing 4957:com.android.mms/u0a55 (adj 11): empty for 1905s
D/CountryDetector(  896): No listener is left
I/ActivityManager(  896): Killing 4886:com.sec.android.gallery3d/u0a53 (adj 11): empty for 1905s
I/ActivityManager(  896): Killing 5924:com.osp.app.signin/u0a50 (adj 11): empty for 1905s
I/ActivityManager(  896): Killing 5898:com.samsung.android.sdk.samsunglink/u0a48 (adj 11): empty for 1905s
I/ActivityManager(  896): Killing 4676:com.sec.spp.push/u0a43 (adj 11): empty for 1906s
I/ActivityManager(  896): Killing 5878:com.policydm/1000 (adj 13): empty for 1906s
I/ActivityManager(  896): Killing 4182:com.sec.android.app.shealth/u0a40 (adj 13): empty for 1906s
I/ActivityManager(  896): Killing 5376:com.samsung.android.app.galaxyfinder/u0a39 (adj 13): empty for 1906s
I/ActivityManager(  896): Killing 5845:com.sec.pcw.device/1000 (adj 13): empty for 1906s
I/ActivityManager(  896): Killing 5338:sstream.app/u0a25 (adj 13): empty for 1906s
I/ActivityManager(  896): Killing 5829:com.samsung.groupcast/u0a20 (adj 13): empty for 1906s
I/ActivityManager(  896): Killing 5811:com.google.android.partnersetup/u0a19 (adj 13): empty for 1906s
I/ActivityManager(  896): Killing 5715:com.android.defcontainer/u0a7 (adj 13): empty for 1907s
I/ActivityManager(  896): Killing 5773:com.sec.android.widgetapp.dualclockdigital/u0a115 (adj 13): empty for 1916s
I/ActivityManager(  896): Killing 5757:com.sec.android.widgetapp.digitalclock/u0a109 (adj 13): empty for 1916s
I/ActivityManager(  896): Killing 5552:flipboard.app/u0a125 (adj 15): empty for 1938s
I/ActivityManager(  896): Killing 5064:com.google.android.gm/u0a128 (adj 15): empty for 1938s
I/ActivityManager(  896): Killing 4939:com.sec.android.app.myfiles/u0a56 (adj 15): empty for 1938s
I/ActivityManager(  896): Killing 4869:com.sec.android.app.music:service/u0a49 (adj 15): empty for 1938s
I/ActivityManager(  896): Killing 5479:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty for 1939s
I/ActivityManager(  896): Killing 5422:com.sec.knox.bridge/1000 (adj 15): empty for 1939s
I/ActivityManager(  896): Killing 5401:com.samsung.android.app.FileShareServer/u0a88 (adj 15): empty for 1939s
W/ActivityManager(  896): Spurious death for ProcessRecord{180487d5 6184:com.test.thalitest/u0a272}, curProc for 6184: null
W/libprocessgroup(  896): failed to open /acct/uid_10025/pid_5338/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10020/pid_5829/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10126/pid_6005/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_1000/pid_5985/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10112/pid_5965/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10102/pid_5444/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_1000/pid_5118/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10064/pid_5945/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10055/pid_4957/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10053/pid_4886/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10050/pid_5924/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10048/pid_5898/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10043/pid_4676/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_1000/pid_5878/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10040/pid_4182/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10039/pid_5376/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_1000/pid_5845/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10128/pid_5064/cgroup.procs: No such file or directory
D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  896): stay LED for fully charged
I/ActivityManager(  896): Force stopping com.test.thalitest appid=10272 user=0: pkg removed
I/art     ( 1610): Explicit concurrent mark sweep GC freed 17779(1167KB) AllocSpace objects, 2(689KB) LOS objects, 39% free, 18MB/31MB, paused 584us total 37.840ms
I/art     ( 4305): Explicit concurrent mark sweep GC freed 8038(481KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 16MB/21MB, paused 371us total 27.882ms
I/art     ( 4085): Explicit concurrent mark sweep GC freed 39325(2MB) AllocSpace objects, 9(144KB) LOS objects, 39% free, 15MB/26MB, paused 361us total 23.801ms
W/libprocessgroup(  896): failed to open /acct/uid_10019/pid_5811/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10007/pid_5715/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10115/pid_5773/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10109/pid_5757/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10125/pid_5552/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10056/pid_4939/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10049/pid_4869/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_1000/pid_5479/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_1000/pid_5422/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10088/pid_5401/cgroup.procs: No such file or directory
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/InputReader(  896): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1742): mOCRHelper is null
W/GeofencerStateMachine( 1477): Ignoring removeGeofence because network location is disabled.
D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6549): MountEmulatedStorage()
E/Zygote  ( 6549): v2
I/libpersona( 6549): KNOX_SDCARD checking this for 10023
I/libpersona( 6549): KNOX_SDCARD not a persona
I/ActivityManager(  896): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6549 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 6549): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6549): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6549): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6549): TimaSignature is unavailable
D/ActivityThread( 6549): Added TimaKeyStore provider
I/art     (  896): Explicit concurrent mark sweep GC freed 47067(4MB) AllocSpace objects, 161(2MB) LOS objects, 17% free, 36MB/44MB, paused 1.373ms total 182.813ms
I/art     (  896): WaitForGcToComplete blocked for 72.683ms for cause Explicit
D/ResourcesManager(  896): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/ResourcesManager( 6549): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/SecContentProvider2(  896): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  896): mCursor = null
I/KLMS-2.4.511: ( 6549): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
I/KLMS-2.4.511: ( 6549): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1449670576825
I/KLMS-2.4.511: ( 6549): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.511: ( 6549): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
D/RegisteredServicesCache( 1412): empty dynamic service
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Videos/Videos.apk
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  896): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
D/RCPManagerService(  896): PackageReceiver onReceive()
I/HarmonyEASService(  896): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy(  896): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  896): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  896): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  896): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  896): uID is 10272
V/EnterpriseBillingPolicy(  896): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  896): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  896): getProfileForApplication - exit null
I/ActivityManager(  896): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6568 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
V/EnterpriseBillingPolicy(  896): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  896): packageModificationReceiver - onreceive - might be a vpn vendor package 
E/Zygote  ( 6568): MountEmulatedStorage()
E/Zygote  ( 6568): v2
I/libpersona( 6568): KNOX_SDCARD checking this for 10116
I/libpersona( 6568): KNOX_SDCARD not a persona
V/EnterpriseBillingPolicyStorage(  896): getBillingProfileForVpnEngine - start - com.test.thalitest
I/ActivityManager(  896): Killing 6020:com.samsung.helphub/1000 (adj 15): empty for 1905s
V/EnterpriseBillingPolicyStorage(  896): getBillingProfileForVpnEngine - end - null
I/art     (  896): Explicit concurrent mark sweep GC freed 12143(662KB) AllocSpace objects, 0(0B) LOS objects, 17% free, 36MB/44MB, paused 2.010ms total 210.552ms
I/SELinux ( 6568): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6568): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6568): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6568): TimaSignature is unavailable
D/ActivityThread( 6568): Added TimaKeyStore provider
I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
W/libprocessgroup(  896): failed to open /acct/uid_1000/pid_6020/cgroup.procs: No such file or directory
D/TaskPersister(  896): removeObsoleteFile: deleting file=3_task.xml
D/ResourcesManager( 6568): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/PackageManager(  896): delete codoeFile: 
I/AASAUninstall(  896):  com.test.thalitest not target!
D/PackageManager(  896): result of delete: 1{232703116}
D/AndroidRuntime( 6513): Shutting down VM
D/elm:14491( 6568): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491( 6568): ELMEngine.ELMEngine( context ).
D/elm:14491( 6568): MDMBridge.setEnterpriseBridge()
D/elm:14491( 6568): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
D/elm:14491( 6568): ElmAgentService : onCreate()
D/elm:14491( 6568): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491( 6568): MainReceiver.listeningToPackageRemoved()
D/elm:14491( 6568): MDMBridge.getInstance()
D/elm:14491( 6568): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14491( 6568): MDMBridge.getAllLicenseInfoFromSDK()
E/Zygote  ( 6585): MountEmulatedStorage()
E/Zygote  ( 6585): v2
I/libpersona( 6585): KNOX_SDCARD checking this for 10021
I/libpersona( 6585): KNOX_SDCARD not a persona
I/ActivityManager(  896): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=6585 uid=10021 gids={50021, 9997} abi=armeabi-v7a
I/SELinux ( 6585): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/elm:14491( 6568): ElmAgentService : onDestroy().
I/ActivityManager(  896): Killing 5464:com.sec.android.app.controlpanel/u0a134 (adj 15): empty for 1906s
E/lowmemorykiller(  251): Error writing /proc/5464/oom_score_adj; errno=22
I/SELinux ( 6585): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6585): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6585): TimaSignature is unavailable
D/ActivityThread( 6585): Added TimaKeyStore provider
W/libprocessgroup(  896): failed to open /acct/uid_10134/pid_5464/cgroup.procs: No such file or directory
D/ResourcesManager( 6585): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6585): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 6585): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6585): onReceive() : package name is not s health. Return !!!
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6600): MountEmulatedStorage()
I/libpersona( 6600): KNOX_SDCARD checking this for 10025
E/Zygote  ( 6600): v2
I/libpersona( 6600): KNOX_SDCARD not a persona
I/ActivityManager(  896): Start proc sstream.app for broadcast sstream.app/.receiver.ApplicationCompatibleReceiver: pid=6600 uid=10025 gids={50025, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager(  896): Killing 5495:com.google.android.apps.plus/u0a155 (adj 15): empty for 1906s
E/lowmemorykiller(  251): Error writing /proc/5495/oom_score_adj; errno=22
I/SELinux ( 6600): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6600): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6600): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6600): TimaSignature is unavailable
D/ActivityThread( 6600): Added TimaKeyStore provider
W/libprocessgroup(  896): failed to open /acct/uid_10155/pid_5495/cgroup.procs: No such file or directory
D/ResourcesManager( 6600): creating new AssetManager and set to /system/priv-app/MagazineHome/MagazineHome.apk
W/ResourcesManager( 6600): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
W/linker  ( 6600): libdmcAlwaysFD.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
D/MVFD_interface( 6600): <<<  caMVFace_FaceInit
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/talkback/talkback.apk
D/EnterpriseDeviceManagerService(  896): Package has changed for user 0
D/EnterpriseDeviceManagerService(  896): Admin package name: com.google.android.gms
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/sstream.app/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6600): Failed to ensure directory: /storage/extSdCard/Android/data/sstream.app/cache
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/sstream.app/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6600): Failed to ensure directory: /storage/extSdCard/Android/data/sstream.app/cache
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Drive/Drive.apk
E/SharedPreferencesImpl( 6600): Couldn't rename file /data/data/sstream.app/shared_prefs/shared_prefs.xml to backup file /data/data/sstream.app/shared_prefs/shared_prefs.xml.bak
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Maps/Maps.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/HockeyApp( 6600): Current handler class = sstream.app.util.Log$1
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
W/ResourcesManager(  896): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  896): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  896): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk

```
