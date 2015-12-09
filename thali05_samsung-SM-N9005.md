#### Test 5065027873d6a28_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
E/SMD     (  286): DCD ON
,D/AndroidRuntime( 6214): 
D/AndroidRuntime( 6214): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6214): CheckJNI is OFF
D/AndroidRuntime( 6214): readGMSProperty: start
D/AndroidRuntime( 6214): readGMSProperty: already setted!!
D/AndroidRuntime( 6214): readGMSProperty: end
D/AndroidRuntime( 6214): addProductProperty: start
E/AffinityControl( 6214): AffinityControl: registerfunction enter
D/AndroidRuntime( 6214): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  891): inState():  stateMachine is null !!
I/PersonaManagerService(  891): PersonaId don't exist
I/ActivityManager(  891): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
I/ActivityManager(  891): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  891): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  891): mDVFSHelper.acquire()
D/FocusedStackFrame(  891): Set to : 0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  891): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6231 uid=10271 gids={50271, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 6231): MountEmulatedStorage()
E/Zygote  ( 6231): v2
I/libpersona( 6231): KNOX_SDCARD checking this for 10271
I/libpersona( 6231): KNOX_SDCARD not a persona
D/PointerIcon(  891): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  891): setMouseCustomIcon IconType is same.101
D/PointerIcon(  891): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  891): setHoveringSpenCustomIcon IconType is same.1
I/art     (  327): Explicit concurrent mark sweep GC freed 8753(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 8.491ms total 41.265ms
I/SELinux ( 6231): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/AndroidRuntime( 6214): Shutting down VM
I/SELinux ( 6231): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6231): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 355us total 12.925ms
I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 314us total 16.691ms
D/TimaKeyStoreProvider( 6231): TimaSignature is unavailable
D/ActivityThread( 6231): Added TimaKeyStore provider
V/WindowOrientationListener(  891): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  891): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  891): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  891): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  891): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/SurfaceWidgetView( 1435): destroyHardwareResources():981099247
I/SurfaceFlinger(  254): id=5 Removed Mauncher (6/8)
I/SurfaceFlinger(  254): id=5 Removed Mauncher (-2/8)
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
V/ActivityThread( 1435): updateVisibility : ActivityRecord{3fcf0be4 token=android.os.BinderProxy@156a0c10 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1435): onTrimMemory. Level: 20
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1779): [237392/8] Surface widget visibility changed visibility = false on instance = 1
D/ResourcesManager( 6231): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,I/WebViewFactory( 6231): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 6231): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 6231): Loading: webviewchromium
,I/LibraryLoader( 6231): Time to load native libraries: 6 ms (timestamps 6130-6136)
I/LibraryLoader( 6231): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6231): Binding Chromium to main looper Looper (main, tid 1) {1dc9c7b8}
,I/LibraryLoader( 6231): Expected native library version number "",actual native library version number ""
,I/chromium( 6231): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6231): Initializing chromium process, renderers=0
,W/art     ( 6231): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6231): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium( 6231): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6231): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
I/chromium( 6231): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
,D/BluetoothAdapter( 6231): 437537169: getState() :  mService = null. Returning STATE_OFF
,I/Adreno-EGL( 6231): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6231): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6231): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6231): Local Branch: mybranch5813579
I/Adreno-EGL( 6231): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6231): Local Patches: NONE
I/Adreno-EGL( 6231): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,W/chromium( 6231): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6231): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 6231): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6231): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6231): CordovaWebView is running on device made by: samsung
,W/art     ( 6231): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6231): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager(  891): Activity pause timeout for ActivityRecord{17a71b6a u0 com.test.thalitest/.MainActivity t3}
,D/Activity( 6231): performCreate Call secproduct feature valuefalse
D/Activity( 6231): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer( 6231): Render dirty regions requested: true
,D/Atlas   ( 6231): Validating map...
D/ActivityManager(  891): post active user change for 0
D/KnoxTimeoutHandler(  891): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  891): handleActiveUserChange for user 0
V/ActivityThread( 6231): updateVisibility : ActivityRecord{2b8843a6 token=android.os.BinderProxy@341a8ee8 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/SurfaceFlinger(  254): id=12 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService(  891): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  891): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon(  891): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon(  891): setMouseCustomIcon IconType is same.101
D/PointerIcon(  891): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  891): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer( 6231): Initialized EGL, version 1.4
,I/OpenGLRenderer( 6231): HWUI protection enabled for context ,  &this =0xb3a68ab0 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 6231): Enabling debug mode 0
,D/InputMethodManagerService(  891): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager(  891): mDVFSHelper.release()
,I/Timeline(  891): Timeline: Activity_windows_visible id: ActivityRecord{17a71b6a u0 com.test.thalitest/.MainActivity t3} time:156582
,W/IInputConnectionWrapper( 6231): showStatusIcon on inactive InputConnection
,I/Timeline( 6231): Timeline: Activity_idle id: android.os.BinderProxy@341a8ee8 time:156590
,I/SamsungIME( 1725): getCurrentCandidateView
,D/SamsungIME( 1725): Dismiss ExpandCandiate
,D/JsMessageQueue( 6231): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 6231): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6231): 
,D/jxcore_app_log( 6231): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1665856896
,D/JX-Cordova( 6231): jxcore cordova android initializing
,I/SamsungIME( 1725): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1725): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1725): KeybaordView init() : load resources
,I/SamsungIME( 1725): getCurrentKeyboard
,I/SamsungIME( 1725): getTextKeyboard
,D/SamsungIME( 1725): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/SamsungIME( 1725): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/ClearcutLoggerApiImpl( 1479): disconnect managed GoogleApiClient
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 320, PST = 322, CUR = 450
,W/jxcore-log( 6231): Initializing JXcore engine
,W/jxcore-log( 6231): JXcore engine is ready
,W/jxcore-log( 6231): Starting JXcore engine
,E/auditd  ( 1861): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  891): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/SecurityLogAgent:SEDenialService(  891): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,E/Zygote  ( 6304): MountEmulatedStorage()
I/ActivityManager(  891): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6304 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 6304): v2
I/libpersona( 6304): KNOX_SDCARD checking this for 1000
I/libpersona( 6304): KNOX_SDCARD not a persona
,I/SELinux ( 6304): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6304): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6304): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/jxcore-log( 6231): Platform android
W/jxcore-log( 6231): 
,W/jxcore-log( 6231): Process ARCH arm
W/jxcore-log( 6231): 
,D/TimaKeyStoreProvider( 6304): TimaSignature is unavailable
,D/ActivityThread( 6304): Added TimaKeyStore provider
,D/ResourcesManager( 6304): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 6304):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 6304):  SeDenialReceiver : File path = null
,I/ActivityManager(  891): Killing 5264:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/jxcore-log( 6231): JXcore Cordova bridge is ready!
I/jxcore-log( 6231): 
,W/jxcore-log( 6231): JXcore engine is started
,E/jxcore  ( 6231): Error!: missing ) after argument list
E/jxcore  ( 6231): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 6231): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  891): Killing 5069:com.sec.providers.settingsearch/u0a191 (adj 15): bgCount ##41
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/lowmemorykiller(  251): Error writing /proc/5069/oom_score_adj; errno=22
,W/ScreenOrientationListener( 6231): Removing an inexistent observer!
,I/SurfaceFlinger(  254): id=12 Removed NainActivit (6/8)
,I/SurfaceFlinger(  254): id=12 Removed NainActivit (-2/8)
,D/PointerIcon(  891): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon(  891): setMouseCustomIcon IconType is same.101
D/PointerIcon(  891): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  891): setHoveringSpenCustomIcon IconType is same.1
D/FocusedStackFrame(  891): Set to : 0
,E/ViewRootImpl( 6231): sendUserActionEvent() mView == null
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,V/AlarmManager(  891): waitForAlarm result :4
,D/NtpTrustedTime(  891): forceRefresh() from cache miss
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/NtpTrustedTime(  891): forceRefresh Fail.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/PowerManagerService(  891): [PWL] Off : 105s ago
,W/Atfwd_Sendcmd(  344): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  286): DCD ON
,D/PackageManager(  891): [MSG] WRITE_PACKAGE_RESTRICTIONS
,E/Watchdog(  891): !@Sync 5
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 300, PST = 318, CUR = 450
,E/SMD     (  286): DCD ON
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): stay LED for fully charged
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 309, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 304, CUR = 450
,W/Atfwd_Sendcmd(  344): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  286): DCD ON
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/Watchdog(  891): !@Sync 6
,I/ClearcutLoggerApiImpl( 1571): disconnect managed GoogleApiClient
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 140s ago
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 301, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,V/AlarmManager(  891): waitForAlarm result :8
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 299, CUR = 450
,E/SMD     (  286): DCD ON
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,I/Atfwd_Sendcmd(  344): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  344): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 297, CUR = 450
,E/SMD     (  286): DCD ON
,V/AlarmManager(  891): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/NtpTrustedTime(  891): forceRefresh() from cache miss
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/NtpTrustedTime(  891): forceRefresh Fail.
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/Watchdog(  891): !@Sync 7
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  344): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 296, CUR = 450
,E/SMD     (  286): DCD ON
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/PowerManagerService(  891): [PWL] Off : 180s ago
,W/Atfwd_Sendcmd(  344): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 295, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 294, CUR = 450
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  344): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  286): DCD ON
,E/Watchdog(  891): !@Sync 8
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,V/AlarmManager(  891): waitForAlarm result :8
,E/SMD     (  286): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  286): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  344): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/PowerManagerService(  891): [PWL] Off : 225s ago
,E/SMD     (  286): DCD ON
,E/Watchdog(  891): !@Sync 9
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  286): DCD ON
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  344): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 289, CUR = 450
,E/SMD     (  286): DCD ON
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,D/TimaService(  891): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  891): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  891): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  891): initializing...
,I/TLC_TIMA_PKM_initialize(  891): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  891): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  891): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  891): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  891): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  891): aligned max_recvmsg_size = 262208 = 0x40040,
,I/TZ: qc_tlc_communication(  891): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  891): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  891): App is not loaded in QSEE
,D/QSEECOMAPI: (  891): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  891): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  891): Trustlet response is completed
,E/SMD     (  286): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  891): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  891): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  891): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  891): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  891): !@Sync 10
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 289, CUR = 450,
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/Atfwd_Sendcmd(  344): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  344): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 289, CUR = 450
,E/SMD     (  286): DCD ON
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  891): waitForAlarm result :4
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/Zygote  ( 6346): MountEmulatedStorage()
,E/Zygote  ( 6346): v2
I/libpersona( 6346): KNOX_SDCARD checking this for 10096
I/libpersona( 6346): KNOX_SDCARD not a persona
,I/ActivityManager(  891): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=6346 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6346): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,I/SELinux ( 6346): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6346): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/TimaKeyStoreProvider( 6346): TimaSignature is unavailable
,D/ActivityThread( 6346): Added TimaKeyStore provider
,D/SurfaceWidgetView( 1435): destroyHardwareResources():981099247
,V/WindowOrientationListener(  891): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  891): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  891): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  891): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  891): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/Launcher( 1435): onRestart, Launcher: 698543565
D/Launcher( 1435): onStart, Launcher: 698543565
D/Launcher.HomeView( 1435): onStart
,D/ResourcesManager( 6346): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 1779): [237392/8] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 1779): [237392/8] SurfaceWidget drawing first frame
D/accuweather( 1779): [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
,V/ActivityThread( 1435): updateVisibility : ActivityRecord{3fcf0be4 token=android.os.BinderProxy@156a0c10 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,I/SurfaceFlinger(  254): id=13 createSurf (1080x1920),1 flag=4, Mauncher
,D/StatusBarManagerService(  891): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  891): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon(  891): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  891): setMouseCustomIcon IconType is same.101
D/PointerIcon(  891): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  891): setHoveringSpenCustomIcon IconType is same.1
,E/SMD     (  286): DCD ON
,D/InputMethodManagerService(  891): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 6231): showStatusIcon on inactive InputConnection
,I/ActivityManager(  891): Killing 4405:com.android.providers.calendar/u0a51 (adj 15): bgCount ##41
,I/Timeline(  891): Timeline: Activity_windows_visible id: ActivityRecord{16f005cd u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:332249
,I/PowerManagerService(  891): [PWL] Off : 275s ago
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,D/SSRM:n  (  891): SIOP:: AP = 290, PST = 289, CUR = 450
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  344): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  286): DCD ON
,E/Watchdog(  891): !@Sync 11
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5471): (HTTPLog)-Static: isSBSettingEnabled false
,E/SMD     (  286): DCD ON
,E/SQLiteLog( 1571): (10) POSIX Error : 11 SQLite Error : 3850
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 288, CUR = 450
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  344): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 287, CUR = 450
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  344): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 286, CUR = 450
,E/SMD     (  286): DCD ON
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,E/SMD     (  286): DCD ON
,E/Watchdog(  891): !@Sync 12
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 285, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,V/AlarmManager(  891): waitForAlarm result :8
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/PowerManagerService(  891): [PWL] Off : 330s ago
,W/Atfwd_Sendcmd(  344): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 284, CUR = 450
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 283, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/Watchdog(  891): !@Sync 13
,E/SMD     (  286): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 283, CUR = 450
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  344): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  286): DCD ON
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/Watchdog(  891): !@Sync 14
,E/SMD     (  286): DCD ON
,I/Atfwd_Sendcmd(  344): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  344): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 390s ago
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  344): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  286): DCD ON
,E/Watchdog(  891): !@Sync 15
,I/ClearcutLoggerApiImpl( 1571): disconnect managed GoogleApiClient
,E/SMD     (  286): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  344): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/bootchecker(  340): bootchecker wake up!!
,E/SMD     (  286): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  344): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/Watchdog(  891): !@Sync 16
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  344): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 455s ago
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/Watchdog(  891): !@Sync 17
,E/SMD     (  286): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,I/ServiceManager(  344): Waiting for service AtCmdFwd...
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,W/Atfwd_Sendcmd(  344): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/Watchdog(  891): !@Sync 18
,E/SMD     (  286): DCD ON
,I/Atfwd_Sendcmd(  344): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  344): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 525s ago
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,I/Atfwd_Daemon(  344): Stop the daemon....
,E/SMD     (  286): DCD ON
,E/Watchdog(  891): !@Sync 19
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450,
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  891): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  891): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  891): TimaServiceHandler.handleMessage what =1
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  891): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  891): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  891): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  891): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  891): !@Sync 20
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON,
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  891): stay LED for fully charged
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,W/ContextImpl(  891): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,I/ActivityManager(  891): Killing 5106:com.google.android.talk/u0a131 (adj 15): bgCount ##41
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/Watchdog(  891): !@Sync 21
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5471): (HTTPLog)-Static: isSBSettingEnabled false
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 600s ago
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/Watchdog(  891): !@Sync 22
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/Watchdog(  891): !@Sync 23
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  891): !@Sync 24
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 680s ago
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  891): !@Sync 25
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  891): !@Sync 26
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,I/PowerManagerService(  891): [PWL] Off : 765s ago
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,E/Watchdog(  891): !@Sync 27
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,E/Watchdog(  891): !@Sync 28
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  891): !@Sync 29
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,V/AlarmManager(  891): waitForAlarm result :4
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/Finsky  ( 5471): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/LightsService(  891): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  891): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SensorManager(  891): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1751): Aggregate from 1449625595247 (log), 1449625595247 (data)
,I/System.out( 5471): Thread-892 calls detatch()
,W/Finsky  ( 5471): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5471): Thread-893 calls detatch()
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5471): Thread-892 calls detatch()
,W/Finsky  ( 5471): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/LightsService(  891): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  891): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  891): unregisterListener ::   
,D/LightsService(  891): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 1571): (10) POSIX Error : 11 SQLite Error : 3850
,I/System.out( 5471): Thread-893 calls detatch()
,W/Finsky  ( 5471): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 5471): [1] WearSupportService.startHygiene: disabled
D/Finsky  ( 5471): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  891): waitForAlarm result :4
,D/Finsky  ( 5471): [1] DailyHygiene.reschedule: Scheduling new run in 27 minutes (failures=2)
,D/DeviceConnectionService( 1479): client connected with version: 8296000
,D/Finsky  ( 5471): [919] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5471): (HTTPLog)-Static: isSBSettingEnabled false
,E/SQLiteLog( 1571): (10) POSIX Error : 11 SQLite Error : 3850
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,I/PowerManagerService(  891): [PWL] Off : 855s ago
,D/TimaService(  891): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  891): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  891): TimaServiceHandler.handleMessage what =1
,E/SMD     (  286): DCD ON
,V/AlarmManager(  891): waitForAlarm result :4
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/Finsky  ( 5471): [905] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5471): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/TLC_TIMA_PKM_measure_kernel(  891): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  891): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  891): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  891): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  891): !@Sync 30
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,V/AlarmManager(  891): waitForAlarm result :8
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0,
D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  891): !@Sync 31
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5471): (HTTPLog)-Static: isSBSettingEnabled false
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): stay LED for fully charged
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  891): !@Sync 32
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  891): !@Sync 33
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 950s ago
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/ClearcutLoggerApiImpl( 1571): disconnect managed GoogleApiClient
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,E/Watchdog(  891): !@Sync 34
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,E/Watchdog(  891): !@Sync 35
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,E/Watchdog(  891): !@Sync 36
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 1050s ago
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,E/Watchdog(  891): !@Sync 37
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,E/Watchdog(  891): !@Sync 38
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,E/Watchdog(  891): !@Sync 39
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 1155s ago
,D/TimaService(  891): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  891): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  891): TimaServiceHandler.handleMessage what =1
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,I/UsageStatsService(  891): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  891): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  891): Updating Usage Statistics in DB @ 1449627709566
,I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
,W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
,W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
,W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
,W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
,W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
,W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
,W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
,W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  891): ::getAppControlDB: Exception to create DB
W/System.err(  891): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  891): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  891): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  891): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  891): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  891): Done Updating Usage Statistics in DB @ 1449627709757
,E/SMD     (  286): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  891): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  891): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  891): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  891): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  891): !@Sync 40
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,E/Watchdog(  891): !@Sync 41
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5471): (HTTPLog)-Static: isSBSettingEnabled false
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,E/Watchdog(  891): !@Sync 42
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,E/Watchdog(  891): !@Sync 43
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 1265s ago
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,E/Watchdog(  891): !@Sync 44
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,E/Watchdog(  891): !@Sync 45
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,E/Watchdog(  891): !@Sync 46
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  891): !@Sync 47
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 1380s ago
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  891): !@Sync 48
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  891): stay LED for fully charged
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  891): !@Sync 49
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  891): stay LED for fully charged
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 270, PST = 279, CUR = 450
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,D/TimaService(  891): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  891): TimaServiceHandler.handleMessage what =1
,D/TimaService(  891): TIMA: checkEvent, operation: 50000 subject: 10000
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 279, CUR = 450
,I/TLC_TIMA_PKM_measure_kernel(  891): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  891): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  891): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  891): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  891): !@Sync 50
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 279, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  891): setPowerConnected  = true
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 279, CUR = 450
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 279, CUR = 450
,E/Watchdog(  891): !@Sync 51
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5471): (HTTPLog)-Static: isSBSettingEnabled false
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 279, CUR = 450
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 1500s ago
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 279, CUR = 450
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 279, CUR = 450
,E/Watchdog(  891): !@Sync 52
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 279, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 270, PST = 278, CUR = 450
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 270, PST = 278, CUR = 450
,E/Watchdog(  891): !@Sync 53
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 270, PST = 277, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 270, PST = 276, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): stay LED for fully charged
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 270, PST = 275, CUR = 450
,E/Watchdog(  891): !@Sync 54
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 270, PST = 274, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 270, PST = 273, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 270, PST = 272, CUR = 450
,E/Watchdog(  891): !@Sync 55
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 270, PST = 271, CUR = 450
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  891): stay LED for fully charged
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 1625s ago
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 270, PST = 270, CUR = 450
,E/Watchdog(  891): !@Sync 56
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/Watchdog(  891): !@Sync 57
,D/SSRM:n  (  891): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/Watchdog(  891): !@Sync 58
,D/SSRM:n  (  891): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/Watchdog(  891): !@Sync 59
,D/SSRM:n  (  891): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  891): stay LED for fully charged
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 270, PST = 270, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,I/PowerManagerService(  891): [PWL] Off : 1755s ago
,D/TimaService(  891): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  891): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  891): TimaServiceHandler.handleMessage what =1
,E/SMD     (  286): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  891): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  891): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  891): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  891): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  891): !@Sync 60
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 271, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 272, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,V/AlarmManager(  891): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1182): handleTimeUpdate
,D/KeyguardEffectViewController( 1182): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1182): *** don't update sliding image ***
,D/LightsService(  891): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,I/ProcessStatsService(  891): Prepared write state in 8ms
,E/LightSensor(  891): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  891): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,I/ProcessStatsService(  891): Prepared write state in 9ms
,D/NtpTrustedTime(  891): forceRefresh() from cache miss
,D/NtpTrustedTime(  891): forceRefresh Fail.
,V/NetworkStats(  891): performPollLocked(flags=0x3)
,D/NetworkStatsFactory(  891): UpdateStatsForKnox
D/ConnectivityService(  891): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  891): performPollLocked() took 6ms
,D/NtpTrustedTime(  891): forceRefresh() from cache miss
,D/NtpTrustedTime(  891): forceRefresh Fail.
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1182): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 1571): (HTTPLog)-Static: isSBSettingEnabled false
,I/ProcessStatsService(  891): Pruning old procstats: /data/system/procstats/state-2015-12-08-10-13-39.bin
,D/LightsService(  891): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  891): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  891): unregisterListener ::   
D/LightsService(  891): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SQLiteLog( 1571): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 273, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/Watchdog(  891): !@Sync 61
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 274, CUR = 450
,I/ActivityManager(  891): Killing 5552:flipboard.app/u0a125 (adj 13): empty for 1800s
,E/SMD     (  286): DCD ON
,I/ActivityManager(  891): Killing 5035:com.google.android.gm/u0a128 (adj 13): empty for 1800s
,I/ActivityManager(  891): Killing 4952:com.sec.android.app.myfiles/u0a56 (adj 13): empty for 1800s
,I/ActivityManager(  891): Killing 4881:com.sec.android.app.music:service/u0a49 (adj 15): empty for 1800s
,I/ActivityManager(  891): Killing 5432:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty for 1801s
,I/ActivityManager(  891): Killing 5381:com.sec.knox.bridge/1000 (adj 15): empty for 1801s
,I/ActivityManager(  891): Killing 5354:com.samsung.android.app.FileShareServer/u0a88 (adj 15): empty for 1801s
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/libprocessgroup(  891): failed to open /acct/uid_10125/pid_5552/cgroup.procs: No such file or directory
,W/libprocessgroup(  891): failed to open /acct/uid_10128/pid_5035/cgroup.procs: No such file or directory
,W/libprocessgroup(  891): failed to open /acct/uid_10056/pid_4952/cgroup.procs: No such file or directory
,W/libprocessgroup(  891): failed to open /acct/uid_10049/pid_4881/cgroup.procs: No such file or directory
,W/libprocessgroup(  891): failed to open /acct/uid_1000/pid_5432/cgroup.procs: No such file or directory
,W/libprocessgroup(  891): failed to open /acct/uid_1000/pid_5381/cgroup.procs: No such file or directory
,W/libprocessgroup(  891): failed to open /acct/uid_10088/pid_5354/cgroup.procs: No such file or directory
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5471): (HTTPLog)-Static: isSBSettingEnabled false
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 275, CUR = 450
,E/SMD     (  286): DCD ON,
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 280, PST = 276, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/Watchdog(  891): !@Sync 62
,D/SSRM:n  (  891): SIOP:: AP = 270, PST = 276, CUR = 450
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD ON
,V/AlarmManager(  891): waitForAlarm result :8
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 270, PST = 276, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 270, PST = 276, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/BatteryService(  891): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/Watchdog(  891): !@Sync 63
,D/SSRM:n  (  891): SIOP:: AP = 270, PST = 276, CUR = 450
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 270, PST = 275, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  891): stay LED for fully charged
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 270, PST = 274, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/BatteryService(  891): stay LED for fully charged
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/Watchdog(  891): !@Sync 64
,D/SSRM:n  (  891): SIOP:: AP = 270, PST = 273, CUR = 450
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 270, PST = 272, CUR = 450
,I/PowerManagerService(  891): [PWL] Off : 1890s ago
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  891): stay LED for fully charged
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,I/MotionRecognitionService(  891): Plugged
I/MotionRecognitionService(  891): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,D/SSRM:n  (  891): SIOP:: AP = 270, PST = 271, CUR = 450
,E/SMD     (  286): DCD ON
,D/BatteryService(  891): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  891): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  891): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  891): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  891): Plugged
,I/MotionRecognitionService(  891): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1182): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1182): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1182):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  891): stay LED for fully charged
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1182): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD ON
,E/SMD     (  286): DCD ON
,E/Watchdog(  891): !@Sync 65
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 6588): 
D/AndroidRuntime( 6588): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6588): CheckJNI is OFF
D/AndroidRuntime( 6588): readGMSProperty: start
D/AndroidRuntime( 6588): readGMSProperty: already setted!!
D/AndroidRuntime( 6588): readGMSProperty: end
D/AndroidRuntime( 6588): addProductProperty: start
E/AffinityControl( 6588): AffinityControl: registerfunction enter
D/AndroidRuntime( 6588): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  891): START PACKAGE DELETE: observer{722110264}
D/PackageManager(  891): pkg{<packageName>}
D/PackageManager(  891): user{0}
D/PackageManager(  891): caller{2000}
D/PackageManager(  891): flags{3}
D/PersonaManagerService(  891): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  891): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  891): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  891): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  891): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  891): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  891): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  891): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  891): getApplicationUninstallationEnabled
D/ApplicationPolicy(  891): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  891): !@killApplicatoin: 10271, uninstall pkg
I/ActivityManager(  891): Force stopping com.test.thalitest appid=10271 user=-1: uninstall pkg
I/ActivityManager(  891): Killing 6231:com.test.thalitest/u0a271 (adj 9): stop com.test.thalitest
W/PackageSettings(  891): Skipping PackageSetting{25f1d3d8 com.example.hello/10268} due to missing metadata
I/ActivityManager(  891): Killing 6043:com.samsung.android.app.watchmanagerstub/u0a126 (adj 11): empty for 1885s
I/ActivityManager(  891): Killing 6022:com.samsung.android.app.filterinstaller/1000 (adj 11): empty for 1885s
I/ActivityManager(  891): Killing 5994:com.google.android.apps.docs/u0a112 (adj 11): empty for 1885s
I/ActivityManager(  891): Killing 5398:com.sec.chaton/u0a102 (adj 11): empty for 1886s
I/ActivityManager(  891): Killing 5091:com.samsung.android.app.assistantmenu/1000 (adj 11): empty for 1886s
I/ActivityManager(  891): Killing 5974:com.sec.android.app.soundalive/u0a64 (adj 11): empty for 1886s
I/ActivityManager(  891): Killing 4819:com.android.mms/u0a55 (adj 11): empty for 1887s
D/CountryDetector(  891): No listener is left
D/SSRM:n  (  891): SIOP:: AP = 280, PST = 271, CUR = 450
I/ActivityManager(  891): Killing 4897:com.sec.android.gallery3d/u0a53 (adj 11): empty for 1887s
I/ActivityManager(  891): Killing 5953:com.osp.app.signin/u0a50 (adj 13): empty for 1887s
I/ActivityManager(  891): Killing 5928:com.samsung.android.sdk.samsunglink/u0a48 (adj 13): empty for 1887s
E/SMD     (  286): DCD ON
I/ActivityManager(  891): Killing 4632:com.sec.spp.push/u0a43 (adj 13): empty for 1887s
I/ActivityManager(  891): Killing 5908:com.policydm/1000 (adj 13): empty for 1887s
I/ActivityManager(  891): Killing 4143:com.sec.android.app.shealth/u0a40 (adj 13): empty for 1887s
I/ActivityManager(  891): Killing 5331:com.samsung.android.app.galaxyfinder/u0a39 (adj 13): empty for 1887s
I/ActivityManager(  891): Killing 5877:com.sec.pcw.device/1000 (adj 13): empty for 1887s
I/ActivityManager(  891): Killing 5298:sstream.app/u0a25 (adj 13): empty for 1888s
I/ActivityManager(  891): Killing 5859:com.samsung.groupcast/u0a20 (adj 13): empty for 1888s
I/ActivityManager(  891): Killing 5841:com.google.android.partnersetup/u0a19 (adj 15): empty for 1888s
I/ActivityManager(  891): Killing 5743:com.android.defcontainer/u0a7 (adj 15): empty for 1888s
I/ActivityManager(  891): Killing 5793:com.google.android.gms:car/u0a15 (adj 15): empty for 1889s
I/ActivityManager(  891): Killing 5695:com.sec.android.widgetapp.activeapplicationwidget/u0a182 (adj 15): empty for 1909s
W/ActivityManager(  891): Spurious death for ProcessRecord{15fed311 6231:com.test.thalitest/u0a271}, curProc for 6231: null
W/libprocessgroup(  891): failed to open /acct/uid_10025/pid_5298/cgroup.procs: No such file or directory
W/libprocessgroup(  891): failed to open /acct/uid_10126/pid_6043/cgroup.procs: No such file or directory
W/libprocessgroup(  891): failed to open /acct/uid_1000/pid_6022/cgroup.procs: No such file or directory
W/libprocessgroup(  891): failed to open /acct/uid_10112/pid_5994/cgroup.procs: No such file or directory
W/libprocessgroup(  891): failed to open /acct/uid_10102/pid_5398/cgroup.procs: No such file or directory
W/libprocessgroup(  891): failed to open /acct/uid_1000/pid_5091/cgroup.procs: No such file or directory
W/libprocessgroup(  891): failed to open /acct/uid_10064/pid_5974/cgroup.procs: No such file or directory
W/libprocessgroup(  891): failed to open /acct/uid_10055/pid_4819/cgroup.procs: No such file or directory
W/libprocessgroup(  891): failed to open /acct/uid_10053/pid_4897/cgroup.procs: No such file or directory
W/libprocessgroup(  891): failed to open /acct/uid_10050/pid_5953/cgroup.procs: No such file or directory
W/libprocessgroup(  891): failed to open /acct/uid_10048/pid_5928/cgroup.procs: No such file or directory
W/libprocessgroup(  891): failed to open /acct/uid_10043/pid_4632/cgroup.procs: No such file or directory
W/libprocessgroup(  891): failed to open /acct/uid_1000/pid_5908/cgroup.procs: No such file or directory
W/libprocessgroup(  891): failed to open /acct/uid_10040/pid_4143/cgroup.procs: No such file or directory
W/libprocessgroup(  891): failed to open /acct/uid_10039/pid_5331/cgroup.procs: No such file or directory
W/libprocessgroup(  891): failed to open /acct/uid_1000/pid_5877/cgroup.procs: No such file or directory
W/libprocessgroup(  891): failed to open /acct/uid_10020/pid_5859/cgroup.procs: No such file or directory
W/libprocessgroup(  891): failed to open /acct/uid_10019/pid_5841/cgroup.procs: No such file or directory
W/libprocessgroup(  891): failed to open /acct/uid_10007/pid_5743/cgroup.procs: No such file or directory
W/libprocessgroup(  891): failed to open /acct/uid_10015/pid_5793/cgroup.procs: No such file or directory
W/libprocessgroup(  891): failed to open /acct/uid_10182/pid_5695/cgroup.procs: No such file or directory
I/ActivityManager(  891): Force stopping com.test.thalitest appid=10271 user=0: pkg removed
I/art     ( 1624): Explicit concurrent mark sweep GC freed 13181(851KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 18MB/31MB, paused 455us total 41.092ms
I/art     ( 6075): Explicit concurrent mark sweep GC freed 9036(518KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 16MB/21MB, paused 352us total 34.403ms
I/art     ( 4043): Explicit concurrent mark sweep GC freed 37735(2046KB) AllocSpace objects, 9(144KB) LOS objects, 39% free, 15MB/26MB, paused 365us total 23.580ms
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/InputReader(  891): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1479): Ignoring removeGeofence because network location is disabled.
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/SamsungIME( 1725): mOCRHelper is null
I/ActivityManager(  891): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6624 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
E/Zygote  ( 6624): MountEmulatedStorage()
E/Zygote  ( 6624): v2
I/libpersona( 6624): KNOX_SDCARD checking this for 10023
I/libpersona( 6624): KNOX_SDCARD not a persona
I/SELinux ( 6624): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6624): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6624): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     (  891): Explicit concurrent mark sweep GC freed 40122(3MB) AllocSpace objects, 70(1263KB) LOS objects, 17% free, 36MB/44MB, paused 2.389ms total 174.782ms
D/ResourcesManager(  891): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
D/TimaKeyStoreProvider( 6624): TimaSignature is unavailable
I/art     (  891): WaitForGcToComplete blocked for 76.832ms for cause Explicit
D/ActivityThread( 6624): Added TimaKeyStore provider
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager( 6624): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/SecContentProvider2(  891): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  891): mCursor = null
D/RegisteredServicesCache( 1409): empty dynamic service
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
I/KLMS-2.4.511: ( 6624): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
I/KLMS-2.4.511: ( 6624): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1449628464515
I/KLMS-2.4.511: ( 6624): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.511: ( 6624): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Videos/Videos.apk
E/Zygote  ( 6642): MountEmulatedStorage()
I/libpersona( 6642): KNOX_SDCARD checking this for 10116
E/Zygote  ( 6642): v2
I/libpersona( 6642): KNOX_SDCARD not a persona
I/ActivityManager(  891): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6642 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  891): Killing 6058:com.samsung.helphub/1000 (adj 15): empty for 1887s
D/RCPManagerService(  891): PackageReceiver onReceive()
I/HarmonyEASService(  891): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy(  891): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  891): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  891): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  891): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  891): uID is 10271
V/EnterpriseBillingPolicy(  891): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  891): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  891): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  891): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  891): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  891): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  891): getBillingProfileForVpnEngine - end - null
I/SELinux ( 6642): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6642): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6642): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6642): TimaSignature is unavailable
D/ActivityThread( 6642): Added TimaKeyStore provider
I/art     (  891): Explicit concurrent mark sweep GC freed 15112(804KB) AllocSpace objects, 0(0B) LOS objects, 17% free, 36MB/44MB, paused 2.470ms total 270.651ms
W/libprocessgroup(  891): failed to open /acct/uid_1000/pid_6058/cgroup.procs: No such file or directory
D/PackageManager(  891): delete codoeFile: 
D/TaskPersister(  891): removeObsoleteFile: deleting file=3_task.xml
I/AASAUninstall(  891):  com.test.thalitest not target!
D/PackageManager(  891): result of delete: 1{722110264}
D/AndroidRuntime( 6588): Shutting down VM
D/ResourcesManager( 6642): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/elm:14491( 6642): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491( 6642): ELMEngine.ELMEngine( context ).
D/elm:14491( 6642): MDMBridge.setEnterpriseBridge()
D/elm:14491( 6642): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
D/elm:14491( 6642): ElmAgentService : onCreate()
D/elm:14491( 6642): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491( 6642): MainReceiver.listeningToPackageRemoved()
D/elm:14491( 6642): MDMBridge.getInstance()
D/elm:14491( 6642): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14491( 6642): MDMBridge.getAllLicenseInfoFromSDK()
E/Zygote  ( 6659): MountEmulatedStorage()
E/Zygote  ( 6659): v2
I/libpersona( 6659): KNOX_SDCARD checking this for 10021
I/libpersona( 6659): KNOX_SDCARD not a persona
I/ActivityManager(  891): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=6659 uid=10021 gids={50021, 9997} abi=armeabi-v7a
D/elm:14491( 6642): ElmAgentService : onDestroy().
I/SELinux ( 6659): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/ActivityManager(  891): Killing 5417:com.sec.android.app.controlpanel/u0a134 (adj 15): empty for 1887s
I/SELinux ( 6659): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6659): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup(  891): failed to open /acct/uid_10134/pid_5417/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 6659): TimaSignature is unavailable
D/ActivityThread( 6659): Added TimaKeyStore provider
D/ResourcesManager( 6659): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6659): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 6659): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 6659): onReceive() : package name is not s health. Return !!!
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6674): MountEmulatedStorage()
E/Zygote  ( 6674): v2
I/libpersona( 6674): KNOX_SDCARD checking this for 10025
I/libpersona( 6674): KNOX_SDCARD not a persona
I/ActivityManager(  891): Start proc sstream.app for broadcast sstream.app/.receiver.ApplicationCompatibleReceiver: pid=6674 uid=10025 gids={50025, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux ( 6674): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/ActivityManager(  891): Killing 5447:com.google.android.apps.plus/u0a155 (adj 15): empty for 1887s
I/SELinux ( 6674): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6674): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6674): TimaSignature is unavailable
D/ActivityThread( 6674): Added TimaKeyStore provider
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
W/libprocessgroup(  891): failed to open /acct/uid_10155/pid_5447/cgroup.procs: No such file or directory
D/ResourcesManager( 6674): creating new AssetManager and set to /system/priv-app/MagazineHome/MagazineHome.apk
I/EventHub(  891): Removing device '/dev/input/event6' due to inotify event
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
W/ResourcesManager( 6674): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ContextImpl( 6674): Unable to create files subdir /data/data/sstream.app/cache
E/ActivityThread( 6674): Unable to setupGraphicsSupport due to missing cache directory
W/        ( 6674): Zip: inflate read failed (8070 vs 32768)
D/AndroidRuntime( 6674): Shutting down VM
E/AndroidRuntime( 6674): FATAL EXCEPTION: main
E/AndroidRuntime( 6674): Process: sstream.app, PID: 6674
E/AndroidRuntime( 6674): java.lang.RuntimeException: Unable to instantiate application sstream.app.StreamApplication: java.lang.ClassNotFoundException: Didn't find class "sstream.app.StreamApplication" on path: DexPathList[[zip file "/system/framework/twframework.jar", zip file "/system/priv-app/MagazineHome/MagazineHome.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 6674): 	at android.app.LoadedApk.makeApplication(LoadedApk.java:625)
E/AndroidRuntime( 6674): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5084)
E/AndroidRuntime( 6674): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
E/AndroidRuntime( 6674): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
E/AndroidRuntime( 6674): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6674): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6674): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/AndroidRuntime( 6674): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6674): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6674): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/AndroidRuntime( 6674): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
E/AndroidRuntime( 6674): Caused by: java.lang.ClassNotFoundException: Didn't find class "sstream.app.StreamApplication" on path: DexPathList[[zip file "/system/framework/twframework.jar", zip file "/system/priv-app/MagazineHome/MagazineHome.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 6674): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/AndroidRuntime( 6674): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/AndroidRuntime( 6674): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/AndroidRuntime( 6674): 	at android.app.Instrumentation.newApplication(Instrumentation.java:988)
E/AndroidRuntime( 6674): 	at android.app.LoadedApk.makeApplication(LoadedApk.java:620)
E/AndroidRuntime( 6674): 	... 10 more
E/AndroidRuntime( 6674): 	Suppressed: java.io.IOException: Failed to extract 'classes.dex' from '/system/priv-app/MagazineHome/MagazineHome.apk': I/O Error
E/AndroidRuntime( 6674): 		at dalvik.system.DexFile.openDexFileNative(Native Method)
E/AndroidRuntime( 6674): 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
E/AndroidRuntime( 6674): 		at dalvik.system.DexFile.<init>(DexFile.java:80)
E/AndroidRuntime( 6674): 		at dalvik.system.DexFile.<init>(DexFile.java:59)
E/AndroidRuntime( 6674): 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
E/AndroidRuntime( 6674): 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
E/AndroidRuntime( 6674): 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
E/AndroidRuntime( 6674): 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
E/AndroidRuntime( 6674): 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
E/AndroidRuntime( 6674): 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:74)
E/AndroidRuntime( 6674): 		at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6674): 		at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6674): 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:63)
E/AndroidRuntime( 6674): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:119)
E/AndroidRuntime( 6674): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:46)
E/AndroidRuntime( 6674): 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
E/AndroidRuntime( 6674): 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
E/AndroidRuntime( 6674): 		... 10 more
E/AndroidRuntime( 6674): 	Caused by: java.io.IOException: Failed to open file '/data/dalvik-cache/arm/system@priv-app@MagazineHome@MagazineHome.apk@classes.dex': Read-only file system
E/AndroidRuntime( 6674): 		... 27 more
E/AndroidRuntime( 6674): 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/priv-app/MagazineHome/MagazineHome.apk'
E/AndroidRuntime( 6674): 		... 27 more
E/AndroidRuntime( 6674): 	Caused by: java.io.IOException: Failed to open oat file from /system/priv-app/MagazineHome/arm/MagazineHome.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
E/AndroidRuntime( 6674): 		... 27 more
E/AndroidRuntime( 6674): 	Caused by: java.io.IOException: 
E/AndroidRuntime( 6674): 		... 27 more
E/AndroidRuntime( 6674): 	Suppressed: java.lang.ClassNotFoundException: sstream.app.StreamApplication
E/AndroidRuntime( 6674): 		at java.lang.Class.classForName(Native Method)
E/AndroidRuntime( 6674): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/AndroidRuntime( 6674): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/AndroidRuntime( 6674): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/AndroidRuntime( 6674): 		... 13 more
E/AndroidRuntime( 6674): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/talkback/talkback.apk
V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname sstream.app
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/AndroidRuntime(  891): *** FATAL EXCEPTION IN SYSTEM PROCESS: Error dump: system_app_crash
E/AndroidRuntime(  891): java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
E/AndroidRuntime(  891): 	at android.os.StatFs.doStat(StatFs.java:46)
E/AndroidRuntime(  891): 	at android.os.StatFs.restat(StatFs.java:56)
E/AndroidRuntime(  891): 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
E/AndroidRuntime(  891): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
E/AndroidRuntime(  891): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/AndroidRuntime(  891): 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:14833)
E/AndroidRuntime(  891): Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
E/AndroidRuntime(  891): 	at libcore.io.Posix.statvfs(Native Method)
E/AndroidRuntime(  891): 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
E/AndroidRuntime(  891): 	at android.system.Os.statvfs(Os.java:473)
E/AndroidRuntime(  891): 	at android.os.StatFs.doStat(StatFs.java:44)
E/AndroidRuntime(  891): 	... 5 more
I/EventHub(  891): Removing device '/dev/input/event7' due to inotify event
E/Zygote  ( 6700): MountEmulatedStorage()
E/Zygote  ( 6700): v2
I/libpersona( 6700): KNOX_SDCARD checking this for 1000
I/libpersona( 6700): KNOX_SDCARD not a persona
I/ActivityManager(  891): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6700 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/Process ( 6674): Sending signal. PID: 6674 SIG: 9
I/EventHub(  891): Removing device '/dev/input/event8' due to inotify event
I/EventHub(  891): Removing device '/dev/input/event9' due to inotify event
I/SELinux ( 6700): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0_0002
D/EnterpriseDeviceManagerService(  891): Package has changed for user 0
D/EnterpriseDeviceManagerService(  891): Admin package name: com.google.android.gms
E/SELinux ( 6700): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
I/EventHub(  891): Removing device '/dev/input/event10' due to inotify event
I/ActivityManager(  891): Process sstream.app (pid 6674)(adj 0) has died(580,1419)
W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  891): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/TimaKeyStoreProvider( 6700): TimaSignature is unavailable
D/ActivityThread( 6700): Added TimaKeyStore provider
D/ResourcesManager( 6700): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
I/EventHub(  891): Removing device '/dev/input/event11' due to inotify event
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/ContextImpl( 6700): Unable to create files subdir /data/data/com.sec.pcw.device/cache
E/ActivityThread( 6700): Unable to setupGraphicsSupport due to missing cache directory
W/Resources(  891): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  891): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/AndroidRuntime( 6700): Shutting down VM
E/AndroidRuntime( 6700): FATAL EXCEPTION: main
E/AndroidRuntime( 6700): Process: com.sec.pcw.device, PID: 6700
E/AndroidRuntime( 6700): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: java.lang.ClassNotFoundException: Didn't find class "com.sec.pcw.device.contentprovider.DMProvider" on path: DexPathList[[zip file "/system/priv-app/PCWClientS18/PCWClientS18.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 6700): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5560)
E/AndroidRuntime( 6700): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5152)
E/AndroidRuntime( 6700): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5092)
E/AndroidRuntime( 6700): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
E/AndroidRuntime( 6700): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
E/AndroidRuntime( 6700): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6700): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6700): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/AndroidRuntime( 6700): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6700): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6700): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/AndroidRuntime( 6700): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
E/AndroidRuntime( 6700): Caused by: java.lang.ClassNotFoundException: Didn't find class "com.sec.pcw.device.contentprovider.DMProvider" on path: DexPathList[[zip file "/system/priv-app/PCWClientS18/PCWClientS18.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 6700): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/AndroidRuntime( 6700): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/AndroidRuntime( 6700): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/AndroidRuntime( 6700): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5545)
E/AndroidRuntime( 6700): 	... 11 more
E/AndroidRuntime( 6700): 	Suppressed: java.io.IOException: Zip archive '/system/priv-app/PCWClientS18/PCWClientS18.apk' doesn't contain classes.dex (error msg: Entry not found)
E/AndroidRuntime( 6700): 		at dalvik.system.DexFile.openDexFileNative(Native Method)
E/AndroidRuntime( 6700): 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
E/AndroidRuntime( 6700): 		at dalvik.system.DexFile.<init>(DexFile.java:80)
E/AndroidRuntime( 6700): 		at dalvik.system.DexFile.<init>(DexFile.java:59)
E/AndroidRuntime( 6700): 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
E/AndroidRuntime( 6700): 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
E/AndroidRuntime( 6700): 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
E/AndroidRuntime( 6700): 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
E/AndroidRuntime( 6700): 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
E/AndroidRuntime( 6700): 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:74)
E/AndroidRuntime( 6700): 		at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6700): 		at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6700): 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:63)
E/AndroidRuntime( 6700): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:119)
E/AndroidRuntime( 6700): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:46)
E/AndroidRuntime( 6700): 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
E/AndroidRuntime( 6700): 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
E/AndroidRuntime( 6700): 		at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5084)
E/AndroidRuntime( 6700): 		... 9 more
E/AndroidRuntime( 6700): 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/priv-app/PCWClientS18/PCWClientS18.apk'
E/AndroidRuntime( 6700): 		... 27 more
E/AndroidRuntime( 6700): 	Caused by: java.io.IOException: Failed to open oat file from /system/priv-app/PCWClientS18/arm/PCWClientS18.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
E/AndroidRuntime( 6700): 		... 27 more
E/AndroidRuntime( 6700): 	Caused by: java.io.IOException: 
E/AndroidRuntime( 6700): 		... 27 more
E/AndroidRuntime( 6700): 	Suppressed: java.lang.ClassNotFoundException: com.sec.pcw.device.contentprovider.DMProvider
E/AndroidRuntime( 6700): 		at java.lang.Class.classForName(Native Method)
E/AndroidRuntime( 6700): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/AndroidRuntime( 6700): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/AndroidRuntime( 6700): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/AndroidRuntime( 6700): 		... 13 more
E/AndroidRuntime( 6700): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
V/ApplicationPolicy(  891): isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  891): checkUser: useridlist=null, currentuser=0
I/Process (  891): Sending signal. PID: 891 SIG: 9
E/Zygote  ( 6717): MountEmulatedStorage()
I/libpersona( 6717): KNOX_SDCARD checking this for 10039
E/Zygote  ( 6717): v2
I/libpersona( 6717): KNOX_SDCARD not a persona
I/SELinux ( 6717): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0_0002
E/SELinux ( 6717): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/installd(  300): eof
E/installd(  300): failed to read size
I/installd(  300): closing connection
I/ServiceManager(  252): service 'input_method' died
I/ServiceManager(  252): service 'accessibility' died
I/ServiceManager(  252): service 'mount' died
I/ServiceManager(  252): service 'lock_settings' died
I/ServiceManager(  252): service 'device_policy' died
I/ServiceManager(  252): service 'harmony_eas_service' died
I/ServiceManager(  252): service 'sdp' died
I/ServiceManager(  252): service 'log_manager_service' died
I/ServiceManager(  252): service 'application_policy' died
I/ServiceManager(  252): service 'wifi_policy' died
I/ServiceManager(  252): service 'phone_restriction_policy' died
I/ServiceManager(  252): service 'remoteinjection' died
I/ServiceManager(  252): service 'mum_container_policy' died
I/ServiceManager(  252): service 'enterprise_billing_policy' died
I/ServiceManager(  252): service 'knox_timakeystore_policy' died
I/SurfaceFlinger(  254): restart the boot-animation @ binderDied
I/ServiceManager(  252): service 'rcp' died
I/ServiceManager(  252): service 'wifi' died
I/ServiceManager(  252): service 'msapwifi' died
I/ServiceManager(  252): service 'wifiscanner' died
I/ServiceManager(  252): service 'rttmanager' died
I/ServiceManager(  252): service 'enterprise_policy' died
I/ServiceManager(  252): service 'statusbar' died
I/ServiceManager(  252): service 'clipboard' died
I/ServiceManager(  252): service 'clipboardEx' died
I/ServiceManager(  252): service 'network_management' died
I/ServiceManager(  252): service 'ABTPersistenceService' died
I/ServiceManager(  252): service 'textservices' died
I/ServiceManager(  252): service 'network_score' died
I/ServiceManager(  252): service 'netstats' died
I/ServiceManager(  252): service 'netpolicy' died
I/ServiceManager(  252): service 'sec_analytics' died
I/ServiceManager(  252): service 'wifip2p' died
I/ServiceManager(  252): service 'backup' died
I/ServiceManager(  252): service 'appwidget' died
I/ServiceManager(  252): service 'voiceinteraction' died
I/ServiceManager(  252): service 'SecExternalDisplayService' died
I/ServiceManager(  252): service 'diskstats' died
I/ServiceManager(  252): service 'mDNIe' died
I/ServiceManager(  252): service 'spengestureservice' died
I/ServiceManager(  252): service 'quickconnect' died
I/ServiceManager(  252): service 'samplingprofiler' died
I/ServiceManager(  252): service 'commontime_management' died

```
