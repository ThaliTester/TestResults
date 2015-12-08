#### Test 50650278b1aec71_thali05_samsung-SM-N9005 Logs


```
--------- beginning of system
I/PowerManagerService(  759): [PWL] Off : 50s ago
D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
--------- beginning of main
D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  759): Plugged
I/MotionRecognitionService(  759): setPowerConnected  = true
D/BatteryService(  759): stay LED for fully charged
D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SSRM:n  (  759): SIOP:: AP = 310, PST = 339, CUR = 450
,D/AndroidRuntime( 6146): 
D/AndroidRuntime( 6146): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6146): CheckJNI is OFF
D/AndroidRuntime( 6146): readGMSProperty: start
D/AndroidRuntime( 6146): readGMSProperty: already setted!!
D/AndroidRuntime( 6146): readGMSProperty: end
D/AndroidRuntime( 6146): addProductProperty: start
E/AffinityControl( 6146): AffinityControl: registerfunction enter
D/AndroidRuntime( 6146): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  759): inState():  stateMachine is null !!
I/PersonaManagerService(  759): PersonaId don't exist
I/ActivityManager(  759): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  759): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  759): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  759): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  759): mDVFSHelper.acquire()
D/FocusedStackFrame(  759): Set to : 0
E/ActivityManager(  759): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  759): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  759): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  759): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  759): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6161 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6146): Shutting down VM
E/Zygote  ( 6161): MountEmulatedStorage()
E/Zygote  ( 6161): v2
I/libpersona( 6161): KNOX_SDCARD checking this for 10270
I/libpersona( 6161): KNOX_SDCARD not a persona
I/SELinux ( 6161): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6161): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6161): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon(  759): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  759): setMouseCustomIcon IconType is same.101
D/PointerIcon(  759): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  759): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider( 6161): TimaSignature is unavailable
D/ActivityThread( 6161): Added TimaKeyStore provider
V/WindowOrientationListener(  759): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  759): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  759): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  759): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  759): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  759): Display changed displayId=0
D/SurfaceWidgetView( 1448): destroyHardwareResources():782984955
D/ConnectivityService(  759): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 6161): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger(  254): id=6 Removed Mauncher (6/8)
I/SurfaceFlinger(  254): id=6 Removed Mauncher (-2/8)
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1774): [237392/8] Surface widget visibility changed visibility = false on instance = 1
V/ActivityThread( 1448): updateVisibility : ActivityRecord{195b4d80 token=android.os.BinderProxy@3dfe873b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1448): onTrimMemory. Level: 20
,I/WebViewFactory( 6161): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 6161): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 6161): Loading: webviewchromium
,I/LibraryLoader( 6161): Time to load native libraries: 6 ms (timestamps 8011-8017)
,I/LibraryLoader( 6161): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6161): Binding Chromium to main looper Looper (main, tid 1) {3a827f94}
,I/LibraryLoader( 6161): Expected native library version number "",actual native library version number ""
,I/chromium( 6161): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6161): Initializing chromium process, renderers=0
,W/art     ( 6161): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6161): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium( 6161): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6161): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
I/chromium( 6161): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
,D/BluetoothAdapter( 6161): 753375805: getState() :  mService = null. Returning STATE_OFF
,I/Adreno-EGL( 6161): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6161): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6161): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6161): Local Branch: mybranch5813579
I/Adreno-EGL( 6161): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6161): Local Patches: NONE
I/Adreno-EGL( 6161): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,E/SMD     (  293): DCD ON
,W/chromium( 6161): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6161): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/ActivityManager(  759): Activity pause timeout for ActivityRecord{18f2856d u0 com.test.thalitest/.MainActivity t3}
,W/art     ( 6161): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6161): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6161): CordovaWebView is running on device made by: samsung
,W/art     ( 6161): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6161): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity( 6161): performCreate Call secproduct feature valuefalse
,D/Activity( 6161): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer( 6161): Render dirty regions requested: true
,D/Atlas   ( 6161): Validating map...
,D/ActivityManager(  759): post active user change for 0
,D/KnoxTimeoutHandler(  759): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  759): handleActiveUserChange for user 0
,V/ActivityThread( 6161): updateVisibility : ActivityRecord{27decbe2 token=android.os.BinderProxy@ef5c4 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/SurfaceFlinger(  254): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService(  759): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  759): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon(  759): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  759): setMouseCustomIcon IconType is same.101
D/PointerIcon(  759): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  759): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer( 6161): Initialized EGL, version 1.4
,I/OpenGLRenderer( 6161): HWUI protection enabled for context ,  &this =0xa1653060 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 6161): Enabling debug mode 0
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/InputMethodManagerService(  759): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager(  759): mDVFSHelper.release()
,I/Timeline(  759): Timeline: Activity_windows_visible id: ActivityRecord{18f2856d u0 com.test.thalitest/.MainActivity t3} time:158563
,I/SamsungIME( 1731): getCurrentCandidateView
,W/IInputConnectionWrapper( 6161): showStatusIcon on inactive InputConnection
,I/Timeline( 6161): Timeline: Activity_idle id: android.os.BinderProxy@ef5c4 time:158572
,D/SamsungIME( 1731): Dismiss ExpandCandiate
,D/JsMessageQueue( 6161): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 6161): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6161): 
,I/SamsungIME( 1731): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1731): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1731): KeybaordView init() : load resources
,D/jxcore_app_log( 6161): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258379264
,D/JX-Cordova( 6161): jxcore cordova android initializing
,I/SamsungIME( 1731): getCurrentKeyboard
,I/SamsungIME( 1731): getTextKeyboard
,D/SamsungIME( 1731): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/SamsungIME( 1731): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,W/jxcore-log( 6161): Initializing JXcore engine
,W/jxcore-log( 6161): JXcore engine is ready
,W/jxcore-log( 6161): Starting JXcore engine
,E/auditd  ( 1830): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  759): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,E/ActivityManager(  759): checkUser: useridlist=null, currentuser=0
D/SecurityLogAgent:SEDenialService(  759): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
E/ActivityManager(  759): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  759): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  759): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6244): MountEmulatedStorage()
E/Zygote  ( 6244): v2
I/libpersona( 6244): KNOX_SDCARD checking this for 1000
I/libpersona( 6244): KNOX_SDCARD not a persona
,I/SELinux ( 6244): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6244): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6244): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  759): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6244 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/art     (  326): Explicit concurrent mark sweep GC freed 8764(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 343us total 24.708ms
,I/art     (  326): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 263us total 10.092ms
,D/TimaKeyStoreProvider( 6244): TimaSignature is unavailable
,D/ActivityThread( 6244): Added TimaKeyStore provider
,I/art     (  326): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 263us total 12.215ms
,W/jxcore-log( 6161): Platform android
W/jxcore-log( 6161): 
,W/jxcore-log( 6161): Process ARCH arm
W/jxcore-log( 6161): 
,D/ResourcesManager( 6244): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 6244):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 6244):  SeDenialReceiver : File path = null
,I/ActivityManager(  759): Killing 4339:com.android.providers.calendar/u0a51 (adj 15): bgCount ##41
,E/SMD     (  293): DCD ON
,I/jxcore-log( 6161): JXcore Cordova bridge is ready!
I/jxcore-log( 6161): 
,W/jxcore-log( 6161): JXcore engine is started
,E/jxcore  ( 6161): Error!: missing ) after argument list
E/jxcore  ( 6161): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 6161): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,D/FocusedStackFrame(  759): Set to : 0
,D/PointerIcon(  759): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  759): setMouseCustomIcon IconType is same.101
D/PointerIcon(  759): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  759): setHoveringSpenCustomIcon IconType is same.1
,I/ActivityManager(  759): Killing 5068:com.google.android.talk/u0a131 (adj 15): bgCount ##41
,E/lowmemorykiller(  251): Error writing /proc/5068/oom_score_adj; errno=22
,D/ConnectivityService(  759): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ScreenOrientationListener( 6161): Removing an inexistent observer!
,I/SurfaceFlinger(  254): id=13 Removed NainActivit (6/8)
,I/SurfaceFlinger(  254): id=13 Removed NainActivit (-2/8)
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 5
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  759): SIOP:: AP = 320, PST = 335, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  759): SIOP:: AP = 310, PST = 327, CUR = 450
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 75s ago
,E/SMD     (  293): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  759): SIOP:: AP = 310, PST = 321, CUR = 450
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 6
,I/ClearcutLoggerApiImpl( 1480): disconnect managed GoogleApiClient
,D/SSRM:n  (  759): SIOP:: AP = 310, PST = 318, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,V/AlarmManager(  759): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1191): handleTimeUpdate
,D/KeyguardEffectViewController( 1191): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1191): *** don't update sliding image ***
,D/NtpTrustedTime(  759): forceRefresh() from cache miss
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/NtpTrustedTime(  759): forceRefresh Fail.
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  293): DCD ON,
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 310, PST = 315, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  759): waitForAlarm result :8
,I/PowerManagerService(  759): [PWL] Off : 105s ago
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,I/Atfwd_Sendcmd(  336): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  336): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 300, PST = 312, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  759): stay LED for fully charged
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/Watchdog(  759): !@Sync 7
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/SSRM:n  (  759): SIOP:: AP = 300, PST = 310, CUR = 450
,E/SMD     (  293): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  293): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  759): Plugged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  759): stay LED for fully charged
,E/SMD     (  293): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/SSRM:n  (  759): SIOP:: AP = 300, PST = 308, CUR = 450
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 140s ago
,D/SSRM:n  (  759): SIOP:: AP = 300, PST = 307, CUR = 450
,E/SMD     (  293): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  759): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 8
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 300, PST = 306, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  759): Plugged
I/MotionRecognitionService(  759): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  759): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 300, PST = 304, CUR = 450
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true,
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 300, PST = 303, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  759): Plugged
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 9
,I/PowerManagerService(  759): [PWL] Off : 180s ago
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 300, PST = 302, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/SSRM:n  (  759): SIOP:: AP = 300, PST = 301, CUR = 450
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 300, PST = 300, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/TimaService(  759): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  759): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  759): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  759): initializing...
,I/TLC_TIMA_PKM_initialize(  759): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  759): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  759): root = /firmware/image, root_len = 15,
I/TZ: qc_tlc_communication(  759): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  759): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  759): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  759): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  759): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  759): App is not loaded in QSEE
,D/QSEECOMAPI: (  759): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  759): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  759): Trustlet response is completed
,E/SMD     (  293): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  759): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  759): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  759): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  759): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  759): !@Sync 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 300, PST = 300, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/Atfwd_Sendcmd(  336): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  336): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 300, PST = 300, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  759): [PWL] Off : 225s ago
,V/AlarmManager(  759): waitForAlarm result :4
,E/ActivityManager(  759): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  759): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  759): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  759): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): stay LED for fully charged
,E/Zygote  ( 6302): MountEmulatedStorage()
,E/Zygote  ( 6302): v2
,I/libpersona( 6302): KNOX_SDCARD checking this for 10096
I/libpersona( 6302): KNOX_SDCARD not a persona
,I/ActivityManager(  759): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=6302 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1191): handleTimeUpdate
,I/SELinux ( 6302): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6302): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6302): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/KeyguardEffectViewController( 1191): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1191): *** don't update sliding image ***
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  759): Plugged
I/MotionRecognitionService(  759): setPowerConnected  = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/TimaKeyStoreProvider( 6302): TimaSignature is unavailable
,D/ActivityThread( 6302): Added TimaKeyStore provider
,D/SurfaceWidgetView( 1448): destroyHardwareResources():782984955
,V/WindowOrientationListener(  759): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  759): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  759): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  759): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  759): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/ResourcesManager( 6302): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,D/Launcher( 1448): onRestart, Launcher: 597196670
,D/Launcher( 1448): onStart, Launcher: 597196670
D/Launcher.HomeView( 1448): onStart
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1774): [237392/8] Surface widget visibility changed visibility = true on instance = 1
V/ActivityThread( 1448): updateVisibility : ActivityRecord{195b4d80 token=android.os.BinderProxy@3dfe873b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,D/SurfaceWidget.Renderer( 1774): [237392/8] SurfaceWidget drawing first frame
D/accuweather( 1774): [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
,I/SurfaceFlinger(  254): id=14 createSurf (1080x1920),1 flag=4, Mauncher
,D/StatusBarManagerService(  759): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  759): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon(  759): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  759): setMouseCustomIcon IconType is same.101
D/PointerIcon(  759): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  759): setHoveringSpenCustomIcon IconType is same.1
,D/InputMethodManagerService(  759): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 6161): showStatusIcon on inactive InputConnection
,I/ActivityManager(  759): Killing 5324:com.samsung.android.app.FileShareServer/u0a88 (adj 15): bgCount ##41
,I/Timeline(  759): Timeline: Activity_windows_visible id: ActivityRecord{36c94d8a u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:331993
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 300, PST = 300, CUR = 450
,E/SMD     (  293): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON,
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  759): stay LED for fully charged
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 11
,I/art     (  759): Explicit concurrent mark sweep GC freed 260174(18MB) AllocSpace objects, 88(5MB) LOS objects, 17% free, 37MB/45MB, paused 1.504ms total 181.493ms
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5443): (HTTPLog)-Static: isSBSettingEnabled false
,E/SMD     (  293): DCD ON,
,E/SQLiteLog( 1573): (10) POSIX Error : 11 SQLite Error : 3850
,D/SSRM:n  (  759): SIOP:: AP = 300, PST = 300, CUR = 450
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 290, PST = 299, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): stay LED for fully charged
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/SSRM:n  (  759): SIOP:: AP = 290, PST = 298, CUR = 450
,E/SMD     (  293): DCD ON
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 12
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 290, PST = 297, CUR = 450
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 275s ago
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/SSRM:n  (  759): SIOP:: AP = 290, PST = 296, CUR = 450
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  293): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  759): waitForAlarm result :8
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 290, PST = 295, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 13
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 290, PST = 294, CUR = 450
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  759): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 290, PST = 293, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  759): Plugged
I/MotionRecognitionService(  759): setPowerConnected  = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  759): stay LED for fully charged
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 290, PST = 292, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  759): Plugged
I/MotionRecognitionService(  759): setPowerConnected  = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  759): stay LED for fully charged
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 14
,I/PowerManagerService(  759): [PWL] Off : 330s ago
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 290, PST = 291, CUR = 450
,I/Atfwd_Sendcmd(  336): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  336): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  759): stay LED for fully charged
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  759): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 15
,I/ClearcutLoggerApiImpl( 1573): disconnect managed GoogleApiClient
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  759): stay LED for fully charged
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  759): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/bootchecker(  330): bootchecker wake up!!
,E/SMD     (  293): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 290, PST = 290, CUR = 450
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 16
,I/PowerManagerService(  759): [PWL] Off : 390s ago
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/SSRM:n  (  759): SIOP:: AP = 290, PST = 290, CUR = 450
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  293): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  759): stay LED for fully charged
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 17
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,I/ServiceManager(  336): Waiting for service AtCmdFwd...
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  759): Plugged
I/MotionRecognitionService(  759): setPowerConnected  = true
,D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,W/Atfwd_Sendcmd(  336): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 290, PST = 290, CUR = 450
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  759): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 18
,E/SMD     (  293): DCD ON
,I/Atfwd_Sendcmd(  336): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  336): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  (  759): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 455s ago
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  759): waitForAlarm result :8
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  759): stay LED for fully charged
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  759): Plugged
I/MotionRecognitionService(  759): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  759): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/Atfwd_Daemon(  336): Stop the daemon....
,E/SMD     (  293): DCD ON,
,E/Watchdog(  759): !@Sync 19
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  759): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 290, PST = 290, CUR = 450
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/TimaService(  759): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  759): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  759): TimaServiceHandler.handleMessage what =1
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  759): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  759): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  759): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  759): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  759): !@Sync 20
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  759): [PWL] Off : 525s ago
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  759): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 21
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5443): (HTTPLog)-Static: isSBSettingEnabled false
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  759): Plugged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  759): setPowerConnected  = true
,D/BatteryService(  759): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  759): Plugged
I/MotionRecognitionService(  759): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  759): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 22
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 289, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 23
,I/PowerManagerService(  759): [PWL] Off : 600s ago
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 288, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 287, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  759): Plugged
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 286, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 24
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 285, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 284, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  759): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 283, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  759): !@Sync 25
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 680s ago
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  759): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  759): !@Sync 26
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  759): Plugged
I/MotionRecognitionService(  759): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  759): stay LED for fully charged
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  759): !@Sync 27
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  759): Plugged
I/MotionRecognitionService(  759): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  759): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  759): stay LED for fully charged
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  759): stay LED for fully charged
,E/Watchdog(  759): !@Sync 28
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  759): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,I/PowerManagerService(  759): [PWL] Off : 765s ago
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  759): Plugged
I/MotionRecognitionService(  759): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  759): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
D/BatteryService(  759): stay LED for fully charged
,E/Watchdog(  759): !@Sync 29
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
D/BatteryService(  759): stay LED for fully charged
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  759): Plugged
I/MotionRecognitionService(  759): setPowerConnected  = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  759): stay LED for fully charged
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/TimaService(  759): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  759): TimaServiceHandler.handleMessage what =1
,D/TimaService(  759): TIMA: checkEvent, operation: 50000 subject: 10000
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/TLC_TIMA_PKM_measure_kernel(  759): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  759): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  759): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  759): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  759): !@Sync 30
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 290, PST = 281, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  759): stay LED for fully charged
D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  759): !@Sync 31
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5443): (HTTPLog)-Static: isSBSettingEnabled false
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  759): Plugged
I/MotionRecognitionService(  759): setPowerConnected  = true
,D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 281, CUR = 450
,I/PowerManagerService(  759): [PWL] Off : 855s ago
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  759): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  759): !@Sync 32
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  759): stay LED for fully charged
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  759): !@Sync 33
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  759): stay LED for fully charged
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 34
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  759): stay LED for fully charged
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  759): Plugged
I/MotionRecognitionService(  759): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  759): stay LED for fully charged
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  759): Plugged
I/MotionRecognitionService(  759): setPowerConnected  = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  759): stay LED for fully charged
,I/PowerManagerService(  759): [PWL] Off : 950s ago
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 35
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  759): Plugged
I/MotionRecognitionService(  759): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  759): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  759): Plugged
I/MotionRecognitionService(  759): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  759): stay LED for fully charged
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  759): Plugged
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  759): setPowerConnected  = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  759): stay LED for fully charged
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 36
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  759): stay LED for fully charged
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  759): Plugged
I/MotionRecognitionService(  759): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  759): stay LED for fully charged
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  759): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 37
,E/SMD     (  293): DCD ON
,V/AlarmManager(  759): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1191): handleTimeUpdate
,D/KeyguardEffectViewController( 1191): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1191): *** don't update sliding image ***
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  759): stay LED for fully charged
,D/LightsService(  759): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  759): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  759): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/MotionRecognitionService(  759): Plugged
I/MotionRecognitionService(  759): setPowerConnected  = true
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 1754): Aggregate from 1449594856992 (log), 1449594856992 (data)
,D/LightsService(  759): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  759): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  759): unregisterListener ::   
,D/LightsService(  759): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  759): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 38
,I/PowerManagerService(  759): [PWL] Off : 1050s ago
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  759): stay LED for fully charged
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  759): Plugged
I/MotionRecognitionService(  759): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
D/BatteryService(  759): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 39
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  759): Plugged
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  759): stay LED for fully charged
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  759): stay LED for fully charged
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,D/TimaService(  759): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  759): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  759): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  759): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  759): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  759): Updating Usage Statistics in DB @ 1449596742672
,I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
,W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
,W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
,W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
,W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
,W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
,W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
,W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
,W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
,W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
,W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
,W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
,W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
,W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
,W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
,W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
,W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
,W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
,W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
,W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
,W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  759): ::getAppControlDB: Exception to create DB
W/System.err(  759): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  759): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  759): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsage(  759): Done Updating Usage Statistics in DB @ 1449596742863
,E/SMD     (  293): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  759): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  759): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  759): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  759): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  759): !@Sync 40
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 41
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5443): (HTTPLog)-Static: isSBSettingEnabled false
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  759): Plugged
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 1155s ago
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  759): Plugged
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 42
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  759): stay LED for fully charged
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  759): setPowerConnected  = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  759): stay LED for fully charged
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  759): stay LED for fully charged
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 43
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  759): Plugged
I/MotionRecognitionService(  759): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  759): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 44
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  759): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 45
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  759): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 1265s ago
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  759): Plugged
I/MotionRecognitionService(  759): setPowerConnected  = true
,D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  759): Plugged
,D/BatteryService(  759): stay LED for fully charged
I/MotionRecognitionService(  759): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 46
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  759): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 47
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  759): Plugged
I/MotionRecognitionService(  759): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  759): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 48
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  759): stay LED for fully charged
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 49
,I/PowerManagerService(  759): [PWL] Off : 1380s ago
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  759): Plugged
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/TimaService(  759): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  759): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  759): TimaServiceHandler.handleMessage what =1
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  759): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  759): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  759): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  759): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  759): !@Sync 50
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 51
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5443): (HTTPLog)-Static: isSBSettingEnabled false
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  759): stay LED for fully charged
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 52
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 53
,I/PowerManagerService(  759): [PWL] Off : 1500s ago
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  759): stay LED for fully charged
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  759): Plugged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  759): stay LED for fully charged
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  759): Plugged
I/MotionRecognitionService(  759): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  759): stay LED for fully charged
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 54
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  759): Plugged
I/MotionRecognitionService(  759): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  759): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 55
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  759): stay LED for fully charged
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  759): !@Sync 56
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  759): !@Sync 57
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 1625s ago
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  759): stay LED for fully charged
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  759): Plugged
I/MotionRecognitionService(  759): setPowerConnected  = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  759): stay LED for fully charged
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  759): !@Sync 58
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  759): Plugged
I/MotionRecognitionService(  759): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  759): stay LED for fully charged
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  759): stay LED for fully charged
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  759): stay LED for fully charged
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  759): !@Sync 59
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  759): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,I/MotionRecognitionService(  759): Plugged
I/MotionRecognitionService(  759): setPowerConnected  = true
,D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService(  759): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  759): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  759): TimaServiceHandler.handleMessage what =1
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,I/TLC_TIMA_PKM_measure_kernel(  759): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  759): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  759): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  759): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  759): !@Sync 60
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1191): handleTimeUpdate
,D/KeyguardEffectViewController( 1191): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1191): *** don't update sliding image ***
,D/LightsService(  759): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,I/ProcessStatsService(  759): Prepared write state in 14ms
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/LightSensor(  759): Light old sensor_state 0, new sensor_state : 512 en : 1
,I/ProcessStatsService(  759): Prepared write state in 11ms
,D/SensorManager(  759): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/NtpTrustedTime(  759): forceRefresh() from cache miss
,D/NtpTrustedTime(  759): forceRefresh Fail.
,V/NetworkStats(  759): performPollLocked(flags=0x3)
,D/NetworkStatsFactory(  759): UpdateStatsForKnox
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  759): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  759): performPollLocked() took 8ms
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/NtpTrustedTime(  759): forceRefresh() from cache miss
,D/NtpTrustedTime(  759): forceRefresh Fail.
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  759): Pruning old procstats: /data/system/procstats/state-2015-12-07-19-13-03.bin
,I/System.out( 1573): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1573): (HTTPLog)-Static: isShipBuild true
I/System.out( 1573): (HTTPLog)-Thread-111-650544655: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1573): (HTTPLog)-Static: isSBSettingEnabled false
,D/LightsService(  759): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  759): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  759): unregisterListener ::   
D/LightsService(  759): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SQLiteLog( 1573): (10) POSIX Error : 11 SQLite Error : 3850
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  759): !@Sync 61
,I/ActivityManager(  759): Killing 5517:flipboard.app/u0a125 (adj 13): empty for 1800s
,I/ActivityManager(  759): Killing 4997:com.google.android.gm/u0a128 (adj 13): empty for 1800s
,I/ActivityManager(  759): Killing 4915:com.sec.android.app.myfiles/u0a56 (adj 13): empty for 1800s
,I/ActivityManager(  759): Killing 4844:com.sec.android.app.music:service/u0a49 (adj 15): empty for 1800s
,I/ActivityManager(  759): Killing 5404:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty for 1801s
,I/ActivityManager(  759): Killing 5352:com.sec.knox.bridge/1000 (adj 15): empty for 1801s
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/libprocessgroup(  759): failed to open /acct/uid_10125/pid_5517/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10128/pid_4997/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10056/pid_4915/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10049/pid_4844/cgroup.procs: No such file or directory
,E/SMD     (  293): DCD ON
,W/libprocessgroup(  759): failed to open /acct/uid_1000/pid_5404/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_1000/pid_5352/cgroup.procs: No such file or directory
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5443): (HTTPLog)-Static: isSBSettingEnabled false
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON,
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  759): Plugged
I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  759): stay LED for fully charged
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  759): [PWL] Off : 1755s ago
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  759): !@Sync 62
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,V/AlarmManager(  759): waitForAlarm result :4
,I/ActivityManager(  759): Killing 6037:com.sec.kidsplat.installer/u0a189 (adj 11): empty for 1805s
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  759): stay LED for fully charged
D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/ActivityManager(  759): Killing 5421:com.google.android.apps.plus/u0a155 (adj 11): empty for 1805s
,I/ActivityManager(  759): Killing 5389:com.sec.android.app.controlpanel/u0a134 (adj 11): empty for 1805s
,I/ActivityManager(  759): Killing 6019:com.samsung.helphub/1000 (adj 11): empty for 1805s
,I/ActivityManager(  759): Killing 6004:com.samsung.android.app.watchmanagerstub/u0a126 (adj 11): empty for 1805s
,I/ActivityManager(  759): Killing 5984:com.samsung.android.app.filterinstaller/1000 (adj 11): empty for 1805s
,I/ActivityManager(  759): Killing 5965:com.google.android.apps.docs/u0a112 (adj 11): empty for 1805s
,I/ActivityManager(  759): Killing 5370:com.sec.chaton/u0a102 (adj 11): empty for 1807s
,I/ActivityManager(  759): Killing 5053:com.samsung.android.app.assistantmenu/1000 (adj 11): empty for 1807s
,I/ActivityManager(  759): Killing 5945:com.sec.android.app.soundalive/u0a64 (adj 11): empty for 1807s
,I/ActivityManager(  759): Killing 5924:com.osp.app.signin/u0a50 (adj 13): empty for 1807s
,I/ActivityManager(  759): Killing 5899:com.samsung.android.sdk.samsunglink/u0a48 (adj 13): empty for 1807s
,I/ActivityManager(  759): Killing 4625:com.sec.spp.push/u0a43 (adj 13): empty for 1808s
,I/ActivityManager(  759): Killing 5878:com.policydm/1000 (adj 13): empty for 1808s
,I/ActivityManager(  759): Killing 4121:com.sec.android.app.shealth/u0a40 (adj 13): empty for 1808s
,I/ActivityManager(  759): Killing 5303:com.samsung.android.app.galaxyfinder/u0a39 (adj 13): empty for 1808s
,I/ActivityManager(  759): Killing 5845:com.sec.pcw.device/1000 (adj 13): empty for 1808s
,I/ActivityManager(  759): Killing 5264:sstream.app/u0a25 (adj 13): empty for 1808s
,I/ActivityManager(  759): Killing 5829:com.samsung.groupcast/u0a20 (adj 13): empty for 1808s
,I/ActivityManager(  759): Killing 5811:com.google.android.partnersetup/u0a19 (adj 13): empty for 1808s
,I/ActivityManager(  759): Killing 5684:com.android.defcontainer/u0a7 (adj 15): empty for 1809s
,I/ActivityManager(  759): Killing 5761:com.google.android.gms:car/u0a15 (adj 15): empty for 1810s
,D/Finsky  ( 5443): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/libprocessgroup(  759): failed to open /acct/uid_10189/pid_6037/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10155/pid_5421/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10134/pid_5389/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_1000/pid_6019/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10126/pid_6004/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_1000/pid_5984/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10112/pid_5965/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10102/pid_5370/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_1000/pid_5053/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10064/pid_5945/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10050/pid_5924/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10048/pid_5899/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10043/pid_4625/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_1000/pid_5878/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10040/pid_4121/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10039/pid_5303/cgroup.procs: No such file or directory
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,W/libprocessgroup(  759): failed to open /acct/uid_10025/pid_5264/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10007/pid_5684/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10015/pid_5761/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10019/pid_5811/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10020/pid_5829/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_1000/pid_5845/cgroup.procs: No such file or directory
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5443): Thread-887 calls detatch()
,W/Finsky  ( 5443): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5443): Thread-888 calls detatch()
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5443): Thread-887 calls detatch()
,W/Finsky  ( 5443): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,E/SMD     (  293): DCD ON
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5443): Thread-888 calls detatch()
,W/Finsky  ( 5443): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 5443): [1] WearSupportService.startHygiene: disabled
D/Finsky  ( 5443): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  759): waitForAlarm result :4
,D/Finsky  ( 5443): [1] DailyHygiene.reschedule: Scheduling new run in 89 minutes (failures=3)
,D/DeviceConnectionService( 1480): client connected with version: 8296000
,D/Finsky  ( 5443): [919] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5443): (HTTPLog)-Static: isSBSettingEnabled false
,I/ActivityManager(  759): Killing 6058:com.sec.android.app.samsungapps/u0a45 (adj 15): empty for 1807s
,W/libprocessgroup(  759): failed to open /acct/uid_10045/pid_6058/cgroup.procs: No such file or directory
,V/AlarmManager(  759): waitForAlarm result :8
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,V/AlarmManager(  759): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1191): handleTimeUpdate
,D/KeyguardEffectViewController( 1191): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1191): *** don't update sliding image ***
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  293): DCD ON
,D/Finsky  ( 5443): [900] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5443): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  759): !@Sync 63
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): stay LED for fully charged
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  759): !@Sync 64
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,V/AlarmManager(  759): waitForAlarm result :8
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  759): !@Sync 65
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  759): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  759): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  759): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  759): Plugged
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  759): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
,D/BatteryService(  759): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  759): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  759): SIOP:: AP = 280, PST = 280, CUR = 450
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 6593): 
D/AndroidRuntime( 6593): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6593): CheckJNI is OFF
D/AndroidRuntime( 6593): readGMSProperty: start
D/AndroidRuntime( 6593): readGMSProperty: already setted!!
D/AndroidRuntime( 6593): readGMSProperty: end
D/AndroidRuntime( 6593): addProductProperty: start
E/AffinityControl( 6593): AffinityControl: registerfunction enter
D/AndroidRuntime( 6593): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService(  759): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager(  759): START PACKAGE DELETE: observer{423245527}
D/PackageManager(  759): pkg{<packageName>}
D/PackageManager(  759): user{0}
D/PackageManager(  759): caller{2000}
D/PackageManager(  759): flags{3}
D/PersonaManagerService(  759): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  759): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  759): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  759): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  759): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  759): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  759): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  759): getApplicationUninstallationEnabled
D/ApplicationPolicy(  759): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  759): !@killApplicatoin: 10270, uninstall pkg
I/ActivityManager(  759): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  759): Killing 6161:com.test.thalitest/u0a270 (adj 11): stop com.test.thalitest
W/PackageSettings(  759): Skipping PackageSetting{21f1449e com.example.hello/10268} due to missing metadata
W/ActivityManager(  759): Spurious death for ProcessRecord{3bc90bc4 6161:com.test.thalitest/u0a270}, curProc for 6161: null
I/ActivityManager(  759): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/art     ( 1622): Explicit concurrent mark sweep GC freed 4813(313KB) AllocSpace objects, 2(689KB) LOS objects, 39% free, 18MB/31MB, paused 559us total 53.727ms
I/art     ( 4262): Explicit concurrent mark sweep GC freed 8077(483KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 16MB/21MB, paused 476us total 41.783ms
D/ResourcesManager(  759): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/InputReader(  759): Reconfiguring input devices.  changes=0x00000010
E/ActivityManager(  759): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  759): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  759): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  759): checkUser: useridlist=null, currentuser=0
W/GeofencerStateMachine( 1480): Ignoring removeGeofence because network location is disabled.
I/art     ( 4038): Explicit concurrent mark sweep GC freed 38528(2MB) AllocSpace objects, 9(144KB) LOS objects, 39% free, 15MB/26MB, paused 662us total 70.139ms
E/SamsungIME( 1731): mOCRHelper is null
E/Zygote  ( 6619): MountEmulatedStorage()
E/Zygote  ( 6619): v2
I/libpersona( 6619): KNOX_SDCARD checking this for 10023
I/libpersona( 6619): KNOX_SDCARD not a persona
I/ActivityManager(  759): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6619 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 6619): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6619): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6619): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6619): TimaSignature is unavailable
D/ActivityThread( 6619): Added TimaKeyStore provider
D/ResourcesManager( 6619): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
I/art     (  759): Explicit concurrent mark sweep GC freed 43802(3MB) AllocSpace objects, 87(1531KB) LOS objects, 17% free, 36MB/44MB, paused 6.562ms total 198.149ms
D/ResourcesManager(  759): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
I/art     (  759): WaitForGcToComplete blocked for 107.267ms for cause Explicit
D/ResourcesManager(  759): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager(  759): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/ResourcesManager(  759): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager(  759): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  759): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
D/ResourcesManager(  759): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  759): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  759): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
I/KLMS-2.4.511: ( 6619): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.511: ( 6619): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1449597516077
I/KLMS-2.4.511: ( 6619): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.511: ( 6619): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(  759): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/SecContentProvider2(  759): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  759): mCursor = null
D/ResourcesManager(  759): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
D/ResourcesManager(  759): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/ResourcesManager(  759): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
D/ResourcesManager(  759): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/RegisteredServicesCache( 1415): empty dynamic service
D/ResourcesManager(  759): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  759): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  759): creating new AssetManager and set to /system/app/Books/Books.apk
E/ActivityManager(  759): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  759): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  759): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  759): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  759): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  759): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  759): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  759): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  759): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  759): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
E/Zygote  ( 6637): MountEmulatedStorage()
E/Zygote  ( 6637): v2
I/libpersona( 6637): KNOX_SDCARD checking this for 10116
I/libpersona( 6637): KNOX_SDCARD not a persona
D/ResourcesManager(  759): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(  759): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
I/ActivityManager(  759): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6637 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
D/ResourcesManager(  759): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  759): creating new AssetManager and set to /system/app/Videos/Videos.apk
I/SELinux ( 6637): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6637): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6637): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/RCPManagerService(  759): PackageReceiver onReceive()
I/HarmonyEASService(  759): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy(  759): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  759): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  759): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  759): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/TimaKeyStoreProvider( 6637): TimaSignature is unavailable
V/EnterpriseBillingPolicy(  759): uID is 10270
D/ActivityThread( 6637): Added TimaKeyStore provider
V/EnterpriseBillingPolicy(  759): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  759): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  759): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  759): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  759): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  759): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  759): getBillingProfileForVpnEngine - end - null
D/ResourcesManager( 6637): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/TaskPersister(  759): removeObsoleteFile: deleting file=3_task.xml
I/art     (  759): Explicit concurrent mark sweep GC freed 15944(880KB) AllocSpace objects, 1(16KB) LOS objects, 17% free, 36MB/44MB, paused 3.309ms total 265.961ms
D/elm:14491( 6637): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491( 6637): ELMEngine.ELMEngine( context ).
D/elm:14491( 6637): MDMBridge.setEnterpriseBridge()
D/elm:14491( 6637): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
E/ActivityManager(  759): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  759): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  759): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  759): checkUser: useridlist=null, currentuser=0
D/elm:14491( 6637): ElmAgentService : onCreate()
D/elm:14491( 6637): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491( 6637): MainReceiver.listeningToPackageRemoved()
D/elm:14491( 6637): MDMBridge.getInstance()
D/elm:14491( 6637): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14491( 6637): MDMBridge.getAllLicenseInfoFromSDK()
E/Zygote  ( 6655): MountEmulatedStorage()
E/Zygote  ( 6655): v2
I/libpersona( 6655): KNOX_SDCARD checking this for 10021
I/libpersona( 6655): KNOX_SDCARD not a persona
I/ActivityManager(  759): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=6655 uid=10021 gids={50021, 9997} abi=armeabi-v7a
D/ResourcesManager(  759): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
I/SELinux ( 6655): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/ActivityManager(  759): Killing 4859:com.sec.android.gallery3d/u0a53 (adj 15): empty for 1883s
D/elm:14491( 6637): ElmAgentService : onDestroy().
D/ResourcesManager(  759): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
I/SELinux ( 6655): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6655): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/PackageManager(  759): delete codoeFile: 
D/ResourcesManager(  759): creating new AssetManager and set to /system/app/talkback/talkback.apk
I/AASAUninstall(  759):  com.test.thalitest not target!
D/PackageManager(  759): result of delete: 1{423245527}
D/AndroidRuntime( 6593): Shutting down VM
D/EnterpriseDeviceManagerService(  759): Package has changed for user 0
D/EnterpriseDeviceManagerService(  759): Admin package name: com.google.android.gms
D/TimaKeyStoreProvider( 6655): TimaSignature is unavailable
D/ActivityThread( 6655): Added TimaKeyStore provider
D/ResourcesManager(  759): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
D/ResourcesManager(  759): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  759): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  759): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  759): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  759): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  759): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager(  759): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/ResourcesManager(  759): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
W/libprocessgroup(  759): failed to open /acct/uid_10053/pid_4859/cgroup.procs: No such file or directory
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  759): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
D/ResourcesManager( 6655): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  759): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  759): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  759): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6655): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 6655): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6655): onReceive() : package name is not s health. Return !!!
D/ResourcesManager(  759): creating new AssetManager and set to /system/app/Drive/Drive.apk
E/ActivityManager(  759): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  759): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  759): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  759): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  759): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  759): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  759): creating new AssetManager and set to /system/app/Maps/Maps.apk
D/ResourcesManager(  759): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  759): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
D/ResourcesManager(  759): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  759): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
I/ActivityManager(  759): Start proc sstream.app for broadcast sstream.app/.receiver.ApplicationCompatibleReceiver: pid=6671 uid=10025 gids={50025, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager(  759): Killing 4781:com.android.mms/u0a55 (adj 15): empty for 1883s
W/ResourcesManager(  759): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  759): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  759): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  759): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
D/ResourcesManager(  759): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
E/Zygote  ( 6671): MountEmulatedStorage()
E/Zygote  ( 6671): v2
I/libpersona( 6671): KNOX_SDCARD checking this for 10025
I/libpersona( 6671): KNOX_SDCARD not a persona
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  759): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  759): creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  759): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  759): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  759): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/Resources(  759): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 6671): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6671): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6671): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/CountryDetector(  759): No listener is left
D/TimaKeyStoreProvider( 6671): TimaSignature is unavailable
D/ActivityThread( 6671): Added TimaKeyStore provider
D/UsbSettingsManager(  759): clearDefaults: com.test.thalitest
W/libprocessgroup(  759): failed to open /acct/uid_10055/pid_4781/cgroup.procs: No such file or directory
I/CrashAnrDetector(  759): onPackageRemoved : com.test.thalitest
D/ResourcesManager( 6671): creating new AssetManager and set to /system/priv-app/MagazineHome/MagazineHome.apk
W/ResourcesManager( 6671): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/linker  ( 6671): libdmcAlwaysFD.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
D/MVFD_interface( 6671): <<<  caMVFace_FaceInit
E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/sstream.app/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6671): Failed to ensure directory: /storage/extSdCard/Android/data/sstream.app/cache
E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/sstream.app/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6671): Failed to ensure directory: /storage/extSdCard/Android/data/sstream.app/cache
D/HockeyApp( 6671): Current handler class = sstream.app.util.Log$1
I/EventHub(  759): Removing device '/dev/input/event6' due to inotify event
I/EventHub(  759): Removing device '/dev/input/event7' due to inotify event
D/ResourcesManager( 6671): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/ResourcesManager( 6671): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/SQLiteLog( 6671): (28) failed to open "/data/data/sstream.app/databases/sstream.db" with flag (131138) and mode_t (0) due to error (2)
E/SQLiteLog( 6671): (28) failed to open "/data/data/sstream.app/databases/sstream.db" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 6671): (14) cannot open file at line 32503 of [9491ba7d73]
E/SQLiteLog( 6671): (14) os_unix.c:32503: (2) open(/data/data/sstream.app/databases/sstream.db) - 
E/SQLiteDatabase( 6671): Failed to open database '/data/data/sstream.app/databases/sstream.db'.
E/SQLiteDatabase( 6671): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 6671): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6671): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6671): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6671): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6671): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6671): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6671): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6671): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6671): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6671): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 6671): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6671): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6671): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6671): 	at sstream.app.provider.StoryProvider.query(StoryProvider.java:386)
E/SQLiteDatabase( 6671): 	at android.content.ContentProvider.query(ContentProvider.java:980)
E/SQLiteDatabase( 6671): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/SQLiteDatabase( 6671): 	at android.content.ContentResolver.query(ContentResolver.java:484)
E/SQLiteDatabase( 6671): 	at android.content.ContentResolver.query(ContentResolver.java:428)
E/SQLiteDatabase( 6671): 	at sstream.app.provider.DatabaseUtil.queryConfigSetting(DatabaseUtil.java:685)
E/SQLiteDatabase( 6671): 	at sstream.app.receiver.ApplicationCompatibleReceiver.addCompatibleAppsToDB(ApplicationCompatibleReceiver.java:418)
E/SQLiteDatabase( 6671): 	at sstream.app.receiver.ApplicationCompatibleReceiver.getCompatibleApps(ApplicationCompatibleReceiver.java:155)
E/SQLiteDatabase( 6671): 	at sstream.app.StreamManager$1.run(StreamManager.java:177)
E/SQLiteLog( 6671): (28) failed to open "/data/data/sstream.app/databases/sstream.db" with flag (131138) and mode_t (0) due to error (2)
E/SQLiteLog( 6671): (28) failed to open "/data/data/sstream.app/databases/sstream.db" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 6671): (14) cannot open file at line 32503 of [9491ba7d73]
E/SQLiteLog( 6671): (14) os_unix.c:32503: (2) open(/data/data/sstream.app/databases/sstream.db) - 
E/SQLiteDatabase( 6671): Failed to open database '/data/data/sstream.app/databases/sstream.db'.
E/SQLiteDatabase( 6671): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 6671): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6671): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6671): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6671): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6671): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6671): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6671): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 6671): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 6671): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6671): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 6671): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6671): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6671): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6671): 	at sstream.app.provider.StoryProvider.delete(StoryProvider.java:90)
E/SQLiteDatabase( 6671): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:314)
E/SQLiteDatabase( 6671): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
E/SQLiteDatabase( 6671): 	at sstream.app.provider.DatabaseUtil.deleteConfigSettingForApp(DatabaseUtil.java:985)
E/SQLiteDatabase( 6671): 	at sstream.app.receiver.ApplicationCompatibleReceiver.onReceive(ApplicationCompatibleReceiver.java:216)
E/SQLiteDatabase( 6671): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2991)
E/SQLiteDatabase( 6671): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
E/SQLiteDatabase( 6671): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
E/SQLiteDatabase( 6671): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6671): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6671): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/SQLiteDatabase( 6671): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6671): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6671): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/SQLiteDatabase( 6671): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
E/ActivityManager(  759): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  759): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  759): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  759): checkUser: useridlist=null, currentuser=0
D/AndroidRuntime( 6671): Shutting down VM
I/EventHub(  759): Removing device '/dev/input/event8' due to inotify event
E/Zygote  ( 6709): MountEmulatedStorage()
E/Zygote  ( 6709): v2
I/libpersona( 6709): KNOX_SDCARD checking this for 1000
I/libpersona( 6709): KNOX_SDCARD not a persona
I/EventHub(  759): Removing device '/dev/input/event9' due to inotify event
I/ActivityManager(  759): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6709 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  759): Killing 5727:com.sec.android.widgetapp.digitalclock/u0a109 (adj 15): empty for 1883s
D/HockeyApp( 6671): Writing unhandled exception to: /data/data/sstream.app/files/ca60f14c-28f2-4307-a5f8-1d02f56af443.stacktrace
E/HockeyApp( 6671): Error saving exception stacktrace!
E/HockeyApp( 6671): 
E/HockeyApp( 6671): java.io.FileNotFoundException: /data/data/sstream.app/files/ca60f14c-28f2-4307-a5f8-1d02f56af443.stacktrace: open failed: EROFS (Read-only file system)
E/HockeyApp( 6671): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/HockeyApp( 6671): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/HockeyApp( 6671): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/HockeyApp( 6671): 	at java.io.FileWriter.<init>(FileWriter.java:80)
E/HockeyApp( 6671): 	at net.hockeyapp.android.internal.ExceptionHandler.saveException(ExceptionHandler.java:83)
E/HockeyApp( 6671): 	at net.hockeyapp.android.internal.ExceptionHandler.uncaughtException(ExceptionHandler.java:108)
E/HockeyApp( 6671): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/HockeyApp( 6671): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
E/HockeyApp( 6671): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/HockeyApp( 6671): 	at libcore.io.Posix.open(Native Method)
E/HockeyApp( 6671): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/HockeyApp( 6671): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/HockeyApp( 6671): 	... 7 more
D/HockeyApp( 6671): Writing unhandled exception to: /data/data/sstream.app/files/562c558e-5077-492d-a385-b48819ea5636.stacktrace
E/HockeyApp( 6671): Error saving exception stacktrace!
E/HockeyApp( 6671): 
E/HockeyApp( 6671): java.io.FileNotFoundException: /data/data/sstream.app/files/562c558e-5077-492d-a385-b48819ea5636.stacktrace: open failed: EROFS (Read-only file system)
E/HockeyApp( 6671): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/HockeyApp( 6671): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/HockeyApp( 6671): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/HockeyApp( 6671): 	at java.io.FileWriter.<init>(FileWriter.java:80)
E/HockeyApp( 6671): 	at net.hockeyapp.android.internal.ExceptionHandler.saveException(ExceptionHandler.java:83)
E/HockeyApp( 6671): 	at net.hockeyapp.android.internal.ExceptionHandler.uncaughtException(ExceptionHandler.java:108)
E/HockeyApp( 6671): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/HockeyApp( 6671): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
E/HockeyApp( 6671): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/HockeyApp( 6671): 	at libcore.io.Posix.open(Native Method)
E/HockeyApp( 6671): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/HockeyApp( 6671): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/HockeyApp( 6671): 	... 7 more
I/SELinux ( 6709): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0_0002
I/EventHub(  759): Removing device '/dev/input/event10' due to inotify event
E/SELinux ( 6709): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/EventHub(  759): Removing device '/dev/input/event11' due to inotify event
D/TimaKeyStoreProvider( 6709): TimaSignature is unavailable
D/ActivityThread( 6709): Added TimaKeyStore provider
W/libprocessgroup(  759): failed to open /acct/uid_10109/pid_5727/cgroup.procs: No such file or directory
D/ResourcesManager( 6709): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
W/ContextImpl( 6709): Unable to create files subdir /data/data/com.sec.pcw.device/cache
E/ActivityThread( 6709): Unable to setupGraphicsSupport due to missing cache directory
D/AndroidRuntime( 6709): Shutting down VM
I/EventHub(  759): Removing device '/dev/input/event12' due to inotify event
E/AndroidRuntime( 6709): FATAL EXCEPTION: main
E/AndroidRuntime( 6709): Process: com.sec.pcw.device, PID: 6709
E/AndroidRuntime( 6709): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: java.lang.ClassNotFoundException: Didn't find class "com.sec.pcw.device.contentprovider.DMProvider" on path: DexPathList[[zip file "/system/priv-app/PCWClientS18/PCWClientS18.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 6709): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5560)
E/AndroidRuntime( 6709): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5152)
E/AndroidRuntime( 6709): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5092)
E/AndroidRuntime( 6709): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
E/AndroidRuntime( 6709): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
E/AndroidRuntime( 6709): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6709): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6709): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/AndroidRuntime( 6709): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6709): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6709): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/AndroidRuntime( 6709): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
E/AndroidRuntime( 6709): Caused by: java.lang.ClassNotFoundException: Didn't find class "com.sec.pcw.device.contentprovider.DMProvider" on path: DexPathList[[zip file "/system/priv-app/PCWClientS18/PCWClientS18.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 6709): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/AndroidRuntime( 6709): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/AndroidRuntime( 6709): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/AndroidRuntime( 6709): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5545)
E/AndroidRuntime( 6709): 	... 11 more
E/AndroidRuntime( 6709): 	Suppressed: java.io.IOException: Zip archive '/system/priv-app/PCWClientS18/PCWClientS18.apk' doesn't contain classes.dex (error msg: Entry not found)
E/AndroidRuntime( 6709): 		at dalvik.system.DexFile.openDexFileNative(Native Method)
E/AndroidRuntime( 6709): 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
E/AndroidRuntime( 6709): 		at dalvik.system.DexFile.<init>(DexFile.java:80)
E/AndroidRuntime( 6709): 		at dalvik.system.DexFile.<init>(DexFile.java:59)
E/AndroidRuntime( 6709): 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
E/AndroidRuntime( 6709): 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
E/AndroidRuntime( 6709): 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
E/AndroidRuntime( 6709): 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
E/AndroidRuntime( 6709): 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
E/AndroidRuntime( 6709): 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:74)
E/AndroidRuntime( 6709): 		at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6709): 		at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6709): 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:63)
E/AndroidRuntime( 6709): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:119)
E/AndroidRuntime( 6709): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:46)
E/AndroidRuntime( 6709): 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
E/AndroidRuntime( 6709): 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
E/AndroidRuntime( 6709): 		at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5084)
E/AndroidRuntime( 6709): 		... 9 more
E/AndroidRuntime( 6709): 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/priv-app/PCWClientS18/PCWClientS18.apk'
E/AndroidRuntime( 6709): 		... 27 more
E/AndroidRuntime( 6709): 	Caused by: java.io.IOException: Failed to open oat file from /system/priv-app/PCWClientS18/arm/PCWClientS18.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
E/AndroidRuntime( 6709): 		... 27 more
E/AndroidRuntime( 6709): 	Caused by: java.io.IOException: 
E/AndroidRuntime( 6709): 		... 27 more
E/AndroidRuntime( 6709): 	Suppressed: java.lang.ClassNotFoundException: com.sec.pcw.device.contentprovider.DMProvider
E/AndroidRuntime( 6709): 		at java.lang.Class.classForName(Native Method)
E/AndroidRuntime( 6709): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/AndroidRuntime( 6709): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/AndroidRuntime( 6709): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/AndroidRuntime( 6709): 		... 13 more
E/AndroidRuntime( 6709): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
V/ApplicationPolicy(  759): isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device
E/AndroidRuntime(  759): *** FATAL EXCEPTION IN SYSTEM PROCESS: Error dump: system_app_crash
E/AndroidRuntime(  759): java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
E/AndroidRuntime(  759): 	at android.os.StatFs.doStat(StatFs.java:46)
E/AndroidRuntime(  759): 	at android.os.StatFs.restat(StatFs.java:56)
E/AndroidRuntime(  759): 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
E/AndroidRuntime(  759): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
E/AndroidRuntime(  759): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/AndroidRuntime(  759): 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:14833)
E/AndroidRuntime(  759): Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
E/AndroidRuntime(  759): 	at libcore.io.Posix.statvfs(Native Method)
E/AndroidRuntime(  759): 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
E/AndroidRuntime(  759): 	at android.system.Os.statvfs(Os.java:473)
E/AndroidRuntime(  759): 	at android.os.StatFs.doStat(StatFs.java:44)
E/AndroidRuntime(  759): 	... 5 more
E/ActivityManager(  759): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  759): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  759): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  759): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  759): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6731 uid=10039 gids={50039, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/Process ( 6709): Sending signal. PID: 6709 SIG: 9
E/Zygote  ( 6731): MountEmulatedStorage()
E/Zygote  ( 6731): v2
I/libpersona( 6731): KNOX_SDCARD checking this for 10039
I/libpersona( 6731): KNOX_SDCARD not a persona
I/EventHub(  759): Removing device '/dev/input/event13' due to inotify event
I/SELinux ( 6731): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0_0002
E/SELinux ( 6731): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/EventHub(  759): Removing device '/dev/input/event14' due to inotify event
D/TimaKeyStoreProvider( 6731): TimaSignature is unavailable
D/ActivityThread( 6731): Added TimaKeyStore provider
I/ActivityManager(  759): Process com.sec.pcw.device (pid 6709)(adj 0) has died(646,1360)
D/ResourcesManager( 6731): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/ContextImpl( 6731): Unable to create files subdir /data/data/com.samsung.android.app.galaxyfinder/cache
E/ActivityThread( 6731): Unable to setupGraphicsSupport due to missing cache directory
I/FeatureConfig( 6731): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
D/ResourcesManager( 6731): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
W/ResourcesManager( 6731): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6731): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ResourcesManager( 6731): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/ResourcesManager( 6731): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6731): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6731): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6731): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6731): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6731): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/ResourcesManager( 6731): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk

```
