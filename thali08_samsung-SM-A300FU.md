#### Test 50388019b27d54e_thali08_samsung-SM-A300FU Logs


```--------- beginning of system
11-17 18:20:47.364  1018  1408 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
11-17 18:20:47.364  1018  1408 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
11-17 18:20:47.364  1018  1408 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
11-17 18:20:47.364  1018  1408 D BatteryService: stay LED for fully charged
11-17 18:20:47.364  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
--------- beginning of main
11-17 18:20:47.374  1181  1181 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
11-17 18:20:47.374  1181  1181 D KeyguardUpdateMonitor: handleBatteryUpdate
11-17 18:20:47.374  1018  1018 I MotionRecognitionService: Plugged
11-17 18:20:47.374  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
11-17 18:20:47.374  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
11-17 18:20:47.374  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
11-17 18:20:47.404  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
11-17 18:20:47.404  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
11-17 18:20:47.404  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
11-17 18:20:47.404  1181  1181 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
11-17 18:20:47.404  1181  1181 D SViewCoverView: level :100 plugged : 2
11-17 18:20:47.474  1018  1044 W libprocessgroup: failed to open /acct/uid_10037/pid_3899/cgroup.procs: No such file or directory
,11-17 18:20:47.784  5076  5076 D AndroidRuntime: 
11-17 18:20:47.784  5076  5076 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
11-17 18:20:47.784  5076  5076 D AndroidRuntime: CheckJNI is OFF
11-17 18:20:47.784  5076  5076 D AndroidRuntime: readGMSProperty: start
11-17 18:20:47.784  5076  5076 D AndroidRuntime: readGMSProperty: already setted!!
11-17 18:20:47.784  5076  5076 D AndroidRuntime: propertySet: couldn't set property (it is from app)
11-17 18:20:47.784  5076  5076 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
11-17 18:20:47.784  5076  5076 D AndroidRuntime: readGMSProperty: end
11-17 18:20:47.784  5076  5076 D AndroidRuntime: addProductProperty: start
11-17 18:20:47.924  5076  5076 E AffinityControl: AffinityControl: registerfunction enter
11-17 18:20:47.954  5076  5076 D AndroidRuntime: Calling main entry com.android.commands.am.Am
11-17 18:20:47.974  1018  1408 E PersonaManagerService: inState():  stateMachine is null !!
11-17 18:20:47.974  1018  1408 I PersonaManagerService: PersonaId don't exist
11-17 18:20:47.974  1018  1408 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
11-17 18:20:47.974  1018  1408 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.example.hello
11-17 18:20:47.984  1018  1408 W ActivityManager: mDVFSHelper.acquire()
11-17 18:20:47.994  1018  1408 D FocusedStackFrame: Set to : 0
11-17 18:20:47.994  1018  1408 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:20:47.994  1018  1408 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:20:47.994  1018  1408 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:20:47.994  1018  1408 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:20:48.004  1018  1050 D PhoneWindow: *FMB* installDecor mIsFloating : false
11-17 18:20:48.004  1018  1050 D PhoneWindow: *FMB* installDecor flags : 25362712
11-17 18:20:48.014  5089  5089 E Zygote  : MountEmulatedStorage()
11-17 18:20:48.014  5089  5089 I libpersona: KNOX_SDCARD checking this for 10333
11-17 18:20:48.014  5089  5089 E Zygote  : v2
11-17 18:20:48.014  5089  5089 I libpersona: KNOX_SDCARD not a persona
11-17 18:20:48.014  5089  5089 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
11-17 18:20:48.014  1018  1408 I ActivityManager: Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5089 uid=10333 gids={50333, 9997, 3003, 3001, 3002} abi=armeabi-v7a
11-17 18:20:48.014  1018  1408 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
11-17 18:20:48.014  1018  1408 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.example.hello
11-17 18:20:48.014  1018  1408 D InputDispatcher: Focused application set to: xxxx
11-17 18:20:48.014  1018  1408 D InputDispatcher: Focus left window: 1479
11-17 18:20:48.014  5089  5089 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
11-17 18:20:48.014  5076  5076 D AndroidRuntime: Shutting down VM
11-17 18:20:48.014  5089  5089 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
11-17 18:20:48.024  1018  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
11-17 18:20:48.024  1018  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
11-17 18:20:48.024   259   259 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, iello
11-17 18:20:48.034  1018  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
11-17 18:20:48.034  1018  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
11-17 18:20:48.034  5089  5089 D TimaKeyStoreProvider: TimaSignature is unavailable
11-17 18:20:48.034  5089  5089 D ActivityThread: Added TimaKeyStore provider
11-17 18:20:48.034  1018  1485 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
11-17 18:20:48.044  1018  1018 V ActivityManager: Display changed displayId=0
11-17 18:20:48.044  1018  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
11-17 18:20:48.054  1018  1485 D PersonaManager: isKioskContainerExistOnDevice
11-17 18:20:48.064  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
11-17 18:20:48.094   259   453 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
11-17 18:20:48.094   259  1101 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
11-17 18:20:48.104  1479  1479 V ActivityThread: updateVisibility : ActivityRecord{2f7ae669 token=android.os.BinderProxy@5dde4ff {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
11-17 18:20:48.104  1479  1479 D Launcher: onTrimMemory. Level: 20
11-17 18:20:48.184  5089  5089 I WebViewFactory: Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
11-17 18:20:48.204  5089  5089 I LibraryLoader: Loading: webviewchromium
11-17 18:20:48.224  5076  5076 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,11-17 18:20:48.254  5089  5089 I LibraryLoader: Time to load native libraries: 51 ms (timestamps 6816-6867)
11-17 18:20:48.254  5089  5089 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-17 18:20:48.284  5089  5089 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1113343a}
11-17 18:20:48.284  5089  5089 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-17 18:20:48.294  5089  5089 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
11-17 18:20:48.314  5089  5089 I BrowserStartupController: Initializing chromium process, renderers=0
11-17 18:20:48.314  5089  5089 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:20:48.334  5089  5105 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
11-17 18:20:48.344  5089  5089 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
11-17 18:20:48.344  5089  5089 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
11-17 18:20:48.344  5089  5089 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
11-17 18:20:48.354  5089  5109 D BluetoothAdapter: 1039341803: getState() :  mService = null. Returning STATE_OFF
11-17 18:20:48.374  5089  5089 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
11-17 18:20:48.374  5089  5089 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
11-17 18:20:48.374  5089  5089 I Adreno-EGL: Build Date: 04/06/15 Mon
11-17 18:20:48.374  5089  5089 I Adreno-EGL: Local Branch: 
11-17 18:20:48.374  5089  5089 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
11-17 18:20:48.374  5089  5089 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
11-17 18:20:48.374  5089  5089 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
11-17 18:20:48.474  5089  5115 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
11-17 18:20:48.484  5089  5089 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
11-17 18:20:48.514  5089  5089 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:20:48.514  5089  5089 W AwContents: onDetachedFromWindow called when already detached. Ignoring
11-17 18:20:48.524  5089  5089 D PhoneWindow: *FMB* installDecor mIsFloating : false
11-17 18:20:48.524  5089  5089 D PhoneWindow: *FMB* installDecor flags : 8456448
11-17 18:20:48.534  5089  5089 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
11-17 18:20:48.534  5089  5089 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:20:48.534  5089  5089 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:20:48.564  1018  1045 W ActivityManager: Activity pause timeout for ActivityRecord{21486548 u0 com.example.hello/.MainActivity t10}
11-17 18:20:48.574   291   291 E SMD     : DCD OFF
11-17 18:20:48.574  5089  5127 D OpenGLRenderer: Render dirty regions requested: true
11-17 18:20:48.584  1018  1031 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
11-17 18:20:48.584  1018  1031 D KnoxTimeoutHandler: postActiveUserChange for user 0
11-17 18:20:48.584  1018  1031 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
11-17 18:20:48.584  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
11-17 18:20:48.584  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
11-17 18:20:48.584  5089  5089 V ActivityThread: updateVisibility : ActivityRecord{3f419051 token=android.os.BinderProxy@11f012db {com.example.hello/com.example.hello.MainActivity}} show : true
11-17 18:20:48.594  5089  5089 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
11-17 18:20:48.594  5089  5089 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
11-17 18:20:48.634   259   259 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
11-17 18:20:48.644  1018  1520 D InputDispatcher: Focus entered window: 5089
11-17 18:20:48.644  1018  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
11-17 18:20:48.654  1018  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
11-17 18:20:48.654  5089  5089 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
11-17 18:20:48.654  5089  5127 I OpenGLRenderer: Initialized EGL, version 1.4
11-17 18:20:48.654  5089  5127 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
11-17 18:20:48.654  5089  5127 D OpenGLRenderer: Enabling debug mode 0
11-17 18:20:48.674  1018  1486 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
11-17 18:20:48.684  1181  1181 I StatusBar: Icon Only
11-17 18:20:48.684  1181  1181 D PanelView: There is/are notification(s) 
11-17 18:20:48.684  1018  5133 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
11-17 18:20:48.704  1018  1050 I ActivityManager: Displayed Component not be shown by security: +637ms (total +704ms)
11-17 18:20:48.704  1018  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{21486548 u0 com.example.hello/.MainActivity t10} time:67311
11-17 18:20:48.704  1018  1050 W ActivityManager: mDVFSHelper.release()
11-17 18:20:48.704  5089  5089 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
11-17 18:20:48.704  5089  5089 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@11f012db time:67318
11-17 18:20:48.714  1018  5136 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
11-17 18:20:48.754   259  1041 I SurfaceFlinger: id=11 Removed iello (7/9)
11-17 18:20:48.754   259   453 I SurfaceFlinger: id=11 Removed iello (-2/9)
11-17 18:20:48.754  1765  1765 I SamsungIME: getCurrentCandidateView
11-17 18:20:48.814  1765  1765 D SamsungIME: Dismiss ExpandCandiate
11-17 18:20:48.854  1765  1765 I SamsungIME: getDebugLevel  : 0x4f4c
11-17 18:20:48.864  5089  5089 I chromium: [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
11-17 18:20:48.874  5089  5121 E AndroidProtocolHandler: Unable to open asset URL: file:///android_asset/www/jxcore.js
11-17 18:20:48.894  1765  1765 I SamsungIME: getDebugLevel  : 0x4f4c
11-17 18:20:48.914  1765  1765 I SamsungIME: KeybaordView init() : load resources
11-17 18:20:48.934  1765  1765 I SamsungIME: getCurrentKeyboard
11-17 18:20:48.934  1765  1765 I SamsungIME: getTextKeyboard
11-17 18:20:48.944  5089  5089 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
11-17 18:20:48.944  1765  1765 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
11-17 18:20:49.004  1018  2549 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,11-17 18:20:49.124  5089  5140 D jxcore_app_log: JniHelper::setJavaVM(0xb8294448), pthread_self() = -1199209704
,11-17 18:20:49.124  5089  5140 D JX-Cordova: jxcore cordova android initializing
,11-17 18:20:49.164  5089  5089 W jxcore-log: Initializing JXcore engine
11-17 18:20:49.164  5089  5089 W jxcore-log: JXcore engine is ready
,11-17 18:20:49.174  5089  5089 W jxcore-log: Starting JXcore engine
,11-17 18:20:49.234  1789  1789 E audit   : type=1400 msg=audit(1447780849.234:203): avc:  denied  { ioctl } for  pid=5089 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
11-17 18:20:49.234  1789  1789 E audit   :  SEPF_SM-A300FU_5.0.2_0027
,11-17 18:20:49.234  1789  1789 E audit   : type=1300 msg=audit(1447780849.234:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=beb7bd58 items=0 ppid=309 ppcomm=main pid=5089 auid=4294967295 uid=10333 gid=10333 euid=10333 suid=10333 fsuid=10333 egid=10333 sgid=10333 fsgid=10333 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
11-17 18:20:49.234  1789  1789 E audit   : type=1320 msg=audit(1447780849.234:203): 
,11-17 18:20:49.354  5089  5089 W jxcore-log: Platform android,
11-17 18:20:49.354  5089  5089 W jxcore-log: 
11-17 18:20:49.354  5089  5089 W jxcore-log: Process ARCH arm
11-17 18:20:49.354  5089  5089 W jxcore-log: 
,11-17 18:20:49.394  5089  5089 I jxcore-log: JXcore Cordova bridge is ready!,
11-17 18:20:49.394  5089  5089 I jxcore-log: 
11-17 18:20:49.394  5089  5089 W jxcore-log: JXcore engine is started
11-17 18:20:49.394  5089  5089 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
11-17 18:20:49.394  5089  5089 I chromium: 
,11-17 18:20:49.444  5089  5089 E jxcore-log: >> samsung-SM-A300FU
11-17 18:20:49.444  5089  5089 E jxcore-log: 
,11-17 18:20:49.444  5089  5089 I jxcore-log: Total memory 1451114496
11-17 18:20:49.444  5089  5089 I jxcore-log: 
,11-17 18:20:49.444  5089  5089 I jxcore-log: Free memory 22745088
11-17 18:20:49.444  5089  5089 I jxcore-log: 
11-17 18:20:49.444  5089  5089 I jxcore-log: execPath /data/data/com.example.hello/files/www/jxcore
11-17 18:20:49.444  5089  5089 I jxcore-log: 
11-17 18:20:49.444  5089  5089 I jxcore-log: process.cwd /data/data/com.example.hello/files/www/jxcore
11-17 18:20:49.444  5089  5089 I jxcore-log: 
,11-17 18:20:49.454  5089  5089 I jxcore-log: userPath [ 'www' ]
11-17 18:20:49.454  5089  5089 I jxcore-log: 
,11-17 18:20:49.454  5089  5089 I jxcore-log: Size 540 960
11-17 18:20:49.454  5089  5089 I jxcore-log: 
,11-17 18:20:49.454  5089  5089 I jxcore-log: Screen Brightness 255
11-17 18:20:49.454  5089  5089 I jxcore-log: 
,11-17 18:20:49.454  5089  5089 E jxcore-log: Dummy Error Log.
11-17 18:20:49.454  5089  5089 E jxcore-log: 
,11-17 18:20:49.934  1018  1217 I ActivityManager: Killing 4488:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,11-17 18:20:49.974  5089  5089 I jxcore-log: getBuffer is called!!!!
11-17 18:20:49.974  5089  5089 I jxcore-log: 
,11-17 18:20:50.044  1018  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_4488/cgroup.procs: No such file or directory
,11-17 18:20:51.574   291   291 E SMD     : DCD OFF
,11-17 18:20:51.904  1018  2537 D SSRM:n  : SIOP:: AP = 340
,11-17 18:20:52.164  1018  1045 I ActivityManager: Waited long enough for: ServiceRecord{2dc82972 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,11-17 18:20:54.014  1018  2549 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,11-17 18:20:54.464  5089  5089 D BluetoothAdapter: disable()
,11-17 18:20:54.484  1018  1030 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,11-17 18:20:54.504  1018  1031 D SecContentProvider: uri = 18 selection = isWifiEnabled
,11-17 18:20:54.504  1018  1031 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,11-17 18:20:54.504  1018  1031 D SecContentProvider2: mCursor = null
,11-17 18:20:54.504  1018  1031 D WifiService: setWifiEnabled: false pid=5089, uid=10333
,11-17 18:20:54.504  1018  1031 D SettingsProvider: name = wifi_on
,11-17 18:20:54.514  5089  5089 I jxcore-log: ****TEST TOOK:  5071  ms ****
11-17 18:20:54.514  5089  5089 I jxcore-log: 
,11-17 18:20:54.514  5089  5089 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
11-17 18:20:54.514  5089  5089 I jxcore-log: 
,11-17 18:20:54.574   291   291 E SMD     : DCD OFF,
,11-17 18:20:54.814  5144  5144 D AndroidRuntime: 
11-17 18:20:54.814  5144  5144 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,11-17 18:20:54.814  5144  5144 D AndroidRuntime: CheckJNI is OFF,
11-17 18:20:54.824  5144  5144 D AndroidRuntime: readGMSProperty: start
11-17 18:20:54.824  5144  5144 D AndroidRuntime: readGMSProperty: already setted!!
11-17 18:20:54.824  5144  5144 D AndroidRuntime: propertySet: couldn't set property (it is from app),
11-17 18:20:54.824  5144  5144 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
11-17 18:20:54.824  5144  5144 D AndroidRuntime: readGMSProperty: end
11-17 18:20:54.824  5144  5144 D AndroidRuntime: addProductProperty: start
,11-17 18:20:54.984  5144  5144 E AffinityControl: AffinityControl: registerfunction enter
,11-17 18:20:55.014  5144  5144 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-17 18:20:55.024  1018  1516 D PackageManager: START PACKAGE DELETE: observer{346015474}
11-17 18:20:55.024  1018  1516 D PackageManager: pkg{<packageName>}
11-17 18:20:55.024  1018  1516 D PackageManager: user{0}
11-17 18:20:55.024  1018  1516 D PackageManager: caller{2000}
11-17 18:20:55.024  1018  1516 D PackageManager: flags{3}
,11-17 18:20:55.024  1018  1516 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
11-17 18:20:55.024  1018  1516 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
11-17 18:20:55.024  1018  1516 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
11-17 18:20:55.024  1018  1516 D PackageManager: deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,11-17 18:20:55.024  1018  1516 D PackageManager: deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,11-17 18:20:55.024  1018  1059 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
11-17 18:20:55.024  1018  1059 D PackageManagerService: deletePackage- pkg:com.example.hello, edmuserId:0
11-17 18:20:55.024  1018  1059 D PackageManagerService: deletePackage- pkg:com.example.hello, edmuserId:-1
,11-17 18:20:55.024  1018  1059 D ApplicationPolicy: getApplicationUninstallationEnabled
11-17 18:20:55.024  1018  1059 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,11-17 18:20:55.024  1018  1059 D PackageManager: !@killApplicatoin: 10333, uninstall pkg
,11-17 18:20:55.024  1018  1045 I ActivityManager: Force stopping com.example.hello appid=10333 user=-1: uninstall pkg
,11-17 18:20:55.024  1018  1045 I ActivityManager: Killing 5089:com.example.hello/u0a333 (adj 0): stop com.example.hello cause uninstall pkg
,11-17 18:20:55.094  1018  1059 W PackageSettings: Skipping PackageSetting{3f7acd61 com.test.thalitest/10326} due to missing metadata
,11-17 18:20:55.114  1018  1486 I WindowState: WIN DEATH: Window{26c7fe9a u0 com.example.hello/com.example.hello.MainActivity}
,11-17 18:20:55.114   259  1101 I SurfaceFlinger: id=12 Removed NainActivit (6/8)
,11-17 18:20:55.124   259  1100 I SurfaceFlinger: id=12 Removed NainActivit (-2/8)
,11-17 18:20:55.124  1018  1486 D InputDispatcher: Focus left window: 5089
,11-17 18:20:55.134  1018  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
11-17 18:20:55.134  1018  1050 D PointerIcon: setMouseCustomIcon IconType is same.101,
,11-17 18:20:55.144  1018  1045 I ActivityManager:   Force finishing activity ActivityRecord{21486548 u0 com.example.hello/.MainActivity t10},
11-17 18:20:55.144  1018  1030 W ActivityManager: Spurious death for ProcessRecord{7d1a143 5089:com.example.hello/u0a333}, curProc for 5089: null
11-17 18:20:55.144  1018  1059 I ActivityManager: Force stopping com.example.hello appid=10333 user=0: pkg removed
,11-17 18:20:55.144  1018  1059 I ActivityManager:   Force finishing activity ActivityRecord{21486548 u0 com.example.hello/.MainActivity t10 f}
11-17 18:20:55.144  1018  1059 W ActivityManager: Duplicate finish request for ActivityRecord{21486548 u0 com.example.hello/.MainActivity t10 f}
,11-17 18:20:55.164  1018  1059 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,11-17 18:20:55.184  3579  3579 I art     : Explicit concurrent mark sweep GC freed 2483(148KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 975us total 30.040ms
,11-17 18:20:55.184  1018  1045 D InputDispatcher: Focused application released
,11-17 18:20:55.194  3000  3000 I art     : Explicit concurrent mark sweep GC freed 23670(1440KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 5MB/7MB, paused 1.262ms total 46.097ms
,11-17 18:20:55.214  1018  1103 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-17 18:20:55.214  1765  1765 E SamsungIME: mOCRHelper is null
,11-17 18:20:55.244  3373  3373 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Nov 17 18:20:55 GMT+01:00 2015
,11-17 18:20:55.344  1441  1441 D RegisteredServicesCache: empty dynamic service
,11-17 18:20:55.344  1018  1018 I art     : Explicit concurrent mark sweep GC freed 64270(3MB) AllocSpace objects, 15(354KB) LOS objects, 33% free, 22MB/33MB, paused 2.213ms total 180.381ms
,11-17 18:20:55.344  1018  1408 I art     : WaitForGcToComplete blocked for 126.747ms for cause Explicit
,11-17 18:20:55.384  1018  1018 D RCPManagerService: PackageReceiver onReceive()
,11-17 18:20:55.394  1018  1018 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,11-17 18:20:55.394  1018  1018 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,11-17 18:20:55.494  1018  1018 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,11-17 18:20:55.494  1018  1018 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
11-17 18:20:55.494  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
11-17 18:20:55.494  1018  1018 V EnterpriseBillingPolicy: uID is 10333
11-17 18:20:55.494  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
11-17 18:20:55.494  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,11-17 18:20:55.494  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
11-17 18:20:55.494  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
11-17 18:20:55.494  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
11-17 18:20:55.494  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.example.hello
,11-17 18:20:55.494  1018  1408 I art     : Explicit concurrent mark sweep GC freed 13970(703KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/33MB, paused 2.802ms total 150.262ms
11-17 18:20:55.494  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,11-17 18:20:55.494  1018  1485 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
11-17 18:20:55.494  1018  1485 D SecContentProvider2: mCursor = null
11-17 18:20:55.494  1018  1059 I art     : WaitForGcToComplete blocked for 260.179ms for cause Explicit
,11-17 18:20:55.504  1018  1519 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:20:55.504  1018  1519 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:20:55.504  1018  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,11-17 18:20:55.514  1619  1922 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-17 18:20:55.514  1018  1044 D EnterpriseDeviceManagerService: Package has changed for user 0
11-17 18:20:55.514  1018  1044 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,11-17 18:20:55.514  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:20:55.514  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:20:55.514  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,11-17 18:20:55.524  3373  3373 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,11-17 18:20:55.524  1018  1044 W TextServicesManagerService: no available spell checker services found
,11-17 18:20:55.534  1018  1517 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=30, mBgSplitQueueNum=3 divideNum= 9 r.nextReceiver= 1 receivers.size=39
,11-17 18:20:55.534  3373  3373 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,11-17 18:20:55.534  1018  1517 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,11-17 18:20:55.534  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.example.hello
,11-17 18:20:55.534  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
,11-17 18:20:55.534  1018  2537 D SSRM:aZ : MSG_TYPE_APP_REMOVED::
,11-17 18:20:55.534  1018  1018 V EnterpriseBillingPolicy: uID is 10333
,11-17 18:20:55.534  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
11-17 18:20:55.534  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,11-17 18:20:55.544  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
11-17 18:20:55.544  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
11-17 18:20:55.544  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
11-17 18:20:55.544  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.example.hello
,11-17 18:20:55.544  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,11-17 18:20:55.544  1018  1217 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:20:55.544  1018  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:20:55.544  1018  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:20:55.544  3373  3373 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,11-17 18:20:55.554  3373  3373 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,11-17 18:20:55.554  4085  4085 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
,11-17 18:20:55.564  1018  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:20:55.564  3373  5156 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,11-17 18:20:55.574  1018  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:20:55.574  1018  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:20:55.574  1018  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:20:55.574  1018  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:20:55.574  1018  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:20:55.574  3373  5156 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,11-17 18:20:55.584  3373  5156 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START,
11-17 18:20:55.584  3373  5156 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
,11-17 18:20:55.584  5157  5157 E Zygote  : MountEmulatedStorage()
11-17 18:20:55.584  5157  5157 E Zygote  : v2
11-17 18:20:55.584  5157  5157 I libpersona: KNOX_SDCARD checking this for 10145
11-17 18:20:55.584  5157  5157 I libpersona: KNOX_SDCARD not a persona,
,11-17 18:20:55.584  5157  5157 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,11-17 18:20:55.594  1018  1045 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=5157 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
11-17 18:20:55.594  1018  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:20:55.594  1018  1517 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:20:55.594  1018  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:20:55.594  1018  1517 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:20:55.594  1018  1517 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:20:55.594  1018  1517 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:20:55.594  5157  5157 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,11-17 18:20:55.604  5157  5157 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,11-17 18:20:55.614  5165  5165 E Zygote  : MountEmulatedStorage(),
11-17 18:20:55.614  5165  5165 E Zygote  : v2
11-17 18:20:55.614  5165  5165 I libpersona: KNOX_SDCARD checking this for 10090
11-17 18:20:55.614  5165  5165 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
11-17 18:20:55.614  5165  5165 I libpersona: KNOX_SDCARD not a persona
11-17 18:20:55.614  5165  5165 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
11-17 18:20:55.614  5165  5165 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,11-17 18:20:55.624  1018  1517 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5165 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,11-17 18:20:55.624  1018  1519 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:20:55.624  1018  1519 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:20:55.624  1018  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:20:55.634  1018  1163 D TaskPersister: removeObsoleteFile: deleting file=10_task.xml
,11-17 18:20:55.634  1018  1476 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:20:55.634  1018  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:20:55.634  1018  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,11-17 18:20:55.654  5157  5157 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:20:55.654  5157  5157 D ActivityThread: Added TimaKeyStore provider
,11-17 18:20:55.654  5165  5165 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:20:55.654  5165  5165 D ActivityThread: Added TimaKeyStore provider
,11-17 18:20:55.654  4944  4944 D FilterInstaller: onReceive:android.intent.action.PACKAGE_REMOVED, package:com.example.hello
,11-17 18:20:55.654  4944  4944 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,11-17 18:20:55.664  1018  1517 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:20:55.664  1018  1517 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:20:55.664  1018  1517 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,11-17 18:20:55.674  1018  1517 I TactileAssist: enable value -1
11-17 18:20:55.674  1018  1517 I TactileAssist: internal enable value -1
11-17 18:20:55.674  1018  1517 I TactileAssist: intensity value -1
11-17 18:20:55.674  1018  1517 I TactileAssist: saveAppList value true
,11-17 18:20:55.674  4085  5182 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
11-17 18:20:55.674  4085  5182 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
,11-17 18:20:55.674  4944  4944 I FilterInstaller: FilterPackageService : ACTION_PACKAGE_REMOVED
,11-17 18:20:55.684  1018  1517 I TactileAssist: List of disabled apps :
,11-17 18:20:55.684  1018  1217 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:20:55.684  1018  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,11-17 18:20:55.684  1018  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:20:55.684  3373  5156 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,11-17 18:20:55.684  4944  5188 I FilterInstaller: FilterPackageService : ACTION_REMOVED
11-17 18:20:55.684  4944  5188 D FilterUnInstaller: before removeFromFS
,11-17 18:20:55.694  1018  1059 I art     : Explicit concurrent mark sweep GC freed 7717(508KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 22MB/33MB, paused 6.661ms total 191.540ms
,11-17 18:20:55.704  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:20:55.704  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:20:55.704  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:20:55.704  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:20:55.704  3373  3373 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,11-17 18:20:55.714  5189  5189 E Zygote  : MountEmulatedStorage()
11-17 18:20:55.714  5189  5189 E Zygote  : v2
11-17 18:20:55.714  1018  1044 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,11-17 18:20:55.714  5189  5189 I libpersona: KNOX_SDCARD checking this for 10095
11-17 18:20:55.714  5189  5189 I libpersona: KNOX_SDCARD not a persona
,11-17 18:20:55.724  5189  5189 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,11-17 18:20:55.724  1018  1030 I ActivityManager: Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=5189 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a,
11-17 18:20:55.724  5189  5189 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,11-17 18:20:55.724  5189  5189 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,11-17 18:20:55.734  1018  1516 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:20:55.734  1018  1516 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:20:55.734  1018  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:20:55.734  1018  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:20:55.734  1018  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:20:55.764  5189  5189 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:20:55.764  1018  1059 D PackageManager: delete codoeFile: 
11-17 18:20:55.764  5189  5189 D ActivityThread: Added TimaKeyStore provider
,11-17 18:20:55.764  1018  1059 D AASAuninstall: userId = 0, info.removedAppID = -1, info.uid = 10333, packageName = com.example.hello
11-17 18:20:55.764  1018  1059 I AASA_removePackage: UID=10333 Target=com.example.hello
,11-17 18:20:55.764  1018  1059 D PackageManager: result of delete: 1{346015474}
,11-17 18:20:55.764  1018  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:20:55.764  5165  5165 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,11-17 18:20:55.764  5165  5165 D elm:15121: ELMEngine.ELMEngine( context ).
,11-17 18:20:55.774  5165  5165 D elm:15121: MDMBridge.setEnterpriseBridge()
,11-17 18:20:55.774  5157  5157 D ThemeInfoUtil: getCurrentFestivalName is [null]
11-17 18:20:55.774  5157  5157 D ThemeInfoUtil: isCurrentFestival = false
,11-17 18:20:55.774  5144  5144 D AndroidRuntime: Shutting down VM
,11-17 18:20:55.774  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:20:55.774  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:20:55.774  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:20:55.774  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:20:55.774  1018  1044 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
11-17 18:20:55.774  1018  1044 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
11-17 18:20:55.774  1018  1044 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,11-17 18:20:55.774  1018  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:20:55.794  5204  5204 E Zygote  : MountEmulatedStorage()
11-17 18:20:55.794  5204  5204 E Zygote  : v2
11-17 18:20:55.794  5204  5204 I libpersona: KNOX_SDCARD checking this for 1000
11-17 18:20:55.794  5204  5204 I libpersona: KNOX_SDCARD not a persona
,11-17 18:20:55.794  5204  5204 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,11-17 18:20:55.794  1018  1031 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5204 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,11-17 18:20:55.794  5204  5204 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,11-17 18:20:55.794  5204  5204 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,11-17 18:20:55.794  1018  1517 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:20:55.804  1018  1517 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:20:55.804  1018  1517 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,11-17 18:20:55.804  5165  5165 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,11-17 18:20:55.804  1018  1217 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:20:55.804  1018  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:20:55.814  1018  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,11-17 18:20:55.814  1018  1485 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:20:55.814  1018  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:20:55.814  1018  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,11-17 18:20:55.824  4872  4872 D Compatibility: onReceive() it will make start service
,11-17 18:20:55.824  5165  5165 D elm:15121: ElmAgentService : onCreate()
,11-17 18:20:55.824  5165  5216 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,11-17 18:20:55.824  5165  5216 D elm:15121: MainReceiver.listeningToPackageRemoved()
,11-17 18:20:55.824  5165  5216 D elm:15121: MDMBridge.getInstance()
,11-17 18:20:55.824  5165  5216 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,11-17 18:20:55.834  5204  5204 D TimaKeyStoreProvider: TimaSignature is unavailable
11-17 18:20:55.834  5165  5216 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,11-17 18:20:55.834  1018  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:20:55.834  5204  5204 D ActivityThread: Added TimaKeyStore provider
,11-17 18:20:55.834  4831  4831 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
11-17 18:20:55.834  4831  4831 I PCWCLIENTTRACE_PushUtil: sales region : global
11-17 18:20:55.834  4831  4831 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
11-17 18:20:55.834  4831  4831 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,11-17 18:20:55.844  1018  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:20:55.844  4798  4798 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
,11-17 18:20:55.844  4798  4798 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,11-17 18:20:55.854  1018  1517 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:20:55.854  1018  1517 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:20:55.854  1018  1517 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,11-17 18:20:55.854  4798  4798 I TapandpayWidget:Utils: Clear T&P info.
,11-17 18:20:55.854  1018  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:20:55.854  1018  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,11-17 18:20:55.854  4798  4798 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,11-17 18:20:55.854  1018  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:20:55.854  1018  1253 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:20:55.854  1018  1253 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:20:55.854  1018  1253 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
11-17 18:20:55.854  1018  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:20:55.864  1018  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,11-17 18:20:55.864  1018  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:20:55.864  1018  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,11-17 18:20:55.864  5165  5165 D elm:15121: ElmAgentService : onDestroy().
,11-17 18:20:55.864  1018  1486 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:20:55.864  1018  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:20:55.864  1018  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,11-17 18:20:55.864  1018  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:20:55.874  1018  1044 D UsbSettingsManager: clearDefaults: com.example.hello
11-17 18:20:55.874  1018  1044 I CrashAnrDetector: onPackageRemoved : com.example.hello
,11-17 18:20:55.874  5189  5189 D PreloadFilterInstaller: uses FILTER_DB_VER_1
,11-17 18:20:55.884  4872  5223 D Compatibility: onHandleIntent()
,11-17 18:20:55.884  4872  5223 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10333, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,11-17 18:20:55.884  1018  1486 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:20:55.884  1018  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:20:55.884  1018  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,11-17 18:20:55.884  5204  5204 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
11-17 18:20:55.884  5189  5189 E SQLiteLog: (284) automatic index on titles(filter_id)
,11-17 18:20:55.884  1018  1516 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:20:55.884  4872  5223 D Compatibility: found: 2
11-17 18:20:55.884  1018  1516 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:20:55.894  1018  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,11-17 18:20:55.894  4872  5223 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
11-17 18:20:55.894  4872  5223 D Compatibility: skipping ResolveInfo{1c6858c7 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
11-17 18:20:55.894  4872  5223 D Compatibility: considering ResolveInfo{14649ef4 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
11-17 18:20:55.894  4872  5223 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,11-17 18:20:55.894  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:20:55.894  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:20:55.894  4872  5223 D Compatibility: enabling receiver ResolveInfo{3bfe361d com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
11-17 18:20:55.894  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:20:55.894  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:20:55.904  3000  5224 I UpdateIcingCorporaServi: Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,11-17 18:20:55.904  5189  5201 E SQLiteLog: (284) automatic index on titles(filter_id)
,11-17 18:20:55.904  4872  5223 D Compatibility: enabling receiver ResolveInfo{37281092 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,11-17 18:20:55.914  5226  5226 E Zygote  : MountEmulatedStorage()
11-17 18:20:55.914  5226  5226 E Zygote  : v2
11-17 18:20:55.914  5226  5226 I libpersona: KNOX_SDCARD checking this for 10032
11-17 18:20:55.914  5226  5226 I libpersona: KNOX_SDCARD not a persona
,11-17 18:20:55.914  5226  5226 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,11-17 18:20:55.914  5226  5226 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
11-17 18:20:55.914  1018  1031 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=5226 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
11-17 18:20:55.914  5226  5226 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
11-17 18:20:55.914  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:20:55.914  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:20:55.914  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:20:55.924  4872  5223 D Compatibility: enabling receiver ResolveInfo{1407ba63 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,11-17 18:20:55.934  4872  5223 D Compatibility: enabling receiver ResolveInfo{2da6b660 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,11-17 18:20:55.934  4872  5223 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,11-17 18:20:55.934  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:20:55.934  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:20:55.934  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:20:55.934  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:20:55.954  5241  5241 E Zygote  : MountEmulatedStorage(),
11-17 18:20:55.954  5241  5241 I libpersona: KNOX_SDCARD checking this for 1000
11-17 18:20:55.954  5241  5241 E Zygote  : v2
11-17 18:20:55.954  5241  5241 I libpersona: KNOX_SDCARD not a persona
11-17 18:20:55.954  5226  5226 D TimaKeyStoreProvider: TimaSignature is unavailable
11-17 18:20:55.954  5241  5241 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
11-17 18:20:55.954  5226  5226 D ActivityThread: Added TimaKeyStore provider
,11-17 18:20:55.954  5241  5241 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
11-17 18:20:55.954  5241  5241 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
11-17 18:20:55.964  1018  1031 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5241 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,11-17 18:20:55.964  1018  1253 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:20:55.964  1018  1253 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:20:55.964  1018  1253 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,11-17 18:20:55.964  1018  1408 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:20:55.964  1018  1408 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:20:55.964  1018  1408 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
11-17 18:20:55.974  1806  5249 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
11-17 18:20:55.974  1806  5249 D AccountUtils: Clearing selected account for com.example.hello
,11-17 18:20:55.984   309   309 I art     : Explicit concurrent mark sweep GC freed 8733(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 755us total 25.819ms
,11-17 18:20:55.984  5144  5144 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,11-17 18:20:55.984  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:20:55.984  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:20:55.984  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:20:55.984  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:20:55.994  5241  5241 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:20:55.994  5241  5241 D ActivityThread: Added TimaKeyStore provider
,11-17 18:20:56.004   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 596us total 18.956ms
,11-17 18:20:56.024   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 599us total 16.874ms
,11-17 18:20:56.034  5258  5258 E Zygote  : MountEmulatedStorage()
,11-17 18:20:56.034  5258  5258 E Zygote  : v2
11-17 18:20:56.034  5258  5258 I libpersona: KNOX_SDCARD checking this for 10055
11-17 18:20:56.034  5258  5258 I libpersona: KNOX_SDCARD not a persona
,11-17 18:20:56.034  5258  5258 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,11-17 18:20:56.034  5258  5258 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,11-17 18:20:56.034  5258  5258 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,11-17 18:20:56.044  1018  1031 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5258 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,11-17 18:20:56.054  1018  1520 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:20:56.054  1018  1520 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:20:56.054  1018  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
11-17 18:20:56.054  1018  1517 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:20:56.054  1018  1517 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:20:56.054  1018  1517 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:20:56.054  1018  1516 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:20:56.054  1018  1516 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:20:56.054  1018  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,11-17 18:20:56.064  1018  1408 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:20:56.064  1018  1408 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:20:56.064  1018  1408 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,11-17 18:20:56.064  5258  5258 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:20:56.064  5258  5258 D ActivityThread: Added TimaKeyStore provider
,11-17 18:20:56.074  5226  5275 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
11-17 18:20:56.074  1018  1408 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:20:56.074  1018  1408 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:20:56.074  1018  1408 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
11-17 18:20:56.074  5226  5275 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,11-17 18:20:56.084  1018  1031 I ActivityManager: Killing 4202:com.sec.android.app.music:service/u0a35 (adj 15): empty #31
,11-17 18:20:56.094  1018  1519 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:20:56.094  1018  1519 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:20:56.094  1018  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,11-17 18:20:56.094  1018  1516 I ActivityManager: Killing 4150:com.google.android.music:main/u0a108 (adj 15): empty #31
,11-17 18:20:56.094  3000  5224 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 196 ms] updated apps [took 196 ms] 
,11-17 18:20:56.104  1806  1806 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.gms
,11-17 18:20:56.104  5226  5275 D SPPClientService: PushLog.txt file is not deleted.
,11-17 18:20:56.104  4918  4918 I SA      : [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
11-17 18:20:56.104  4918  4918 I SA      : [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10333 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,11-17 18:20:56.104  5226  5275 D SPPClientService: PushLog.txt file is not deleted.
11-17 18:20:56.104  5226  5275 D SPPClientService: ============PushLog. stop!
,11-17 18:20:56.114  1018  1253 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:20:56.114  1018  1253 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:20:56.114  1018  1253 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,11-17 18:20:56.124  5241  5279 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_REMOVED
,11-17 18:20:56.134  5241  5279 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,11-17 18:20:56.134  4944  5188 I FilterUnInstaller: FilterUninstaller.java : removeFromDB()
,11-17 18:20:56.134  4222  4222 I PackagesMonitor: PackagesMonitor onReceive :com.example.hello
,11-17 18:20:56.134  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:20:56.134  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:20:56.134  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,11-17 18:20:56.144  5189  5201 D FilterProvider: delete when PACKAGE_NAME : 2002 
11-17 18:20:56.144  5189  5201 D FilterProvider: packageName : com.example.hello
,11-17 18:20:56.144  5241  5241 D AcmsService: Enter Oncreate
11-17 18:20:56.144  5241  5241 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
11-17 18:20:56.144  5241  5241 D AcmsService: creating AcmsCore
11-17 18:20:56.144  5241  5241 D AcmsCore: AcmsCore.getAcmsCore() - Enter
11-17 18:20:56.144  5241  5241 D AcmsCore: AcmsCore
,11-17 18:20:56.144  5241  5241 D AcmsCore: init
11-17 18:20:56.144  5241  5241 D AcmsCore: Looper handler is not null
11-17 18:20:56.144  5241  5241 D AcmsCore: Post to AcmsCoreHandler
11-17 18:20:56.144  5241  5241 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
11-17 18:20:56.144  5241  5241 D AcmsServiceMonitor: Incrementing - Counter value: 1
11-17 18:20:56.144  5241  5241 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
11-17 18:20:56.144  5241  5241 D AcmsService: onStartCommand
11-17 18:20:56.144  5241  5241 D AcmsService: Action: android.intent.action.PACKAGE_REMOVED
11-17 18:20:56.144  5241  5241 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
11-17 18:20:56.144  5241  5241 D AcmsServiceMonitor: Incrementing - Counter value: 2
11-17 18:20:56.144  5241  5241 D AcmsService: Incremented Counter Value : onStartCommand
,11-17 18:20:56.144  4944  5188 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.filterinstaller.FilterUninstaller.uninstallFilters:48 com.samsung.android.app.filterinstaller.FilterPackageService$ServiceHandler.handleMessage:152 android.os.Handler.dispatchMessage:102 
,11-17 18:20:56.154  5241  5280 D AcmsCertificateMngr: AcmsCertificateMngr
,11-17 18:20:56.154  5241  5280 D AcmsRevocationMngr: AcmsRevocationMngr
11-17 18:20:56.154  5258  5258 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,11-17 18:20:56.154  1018  1519 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:20:56.154  1018  1519 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:20:56.154  1018  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,11-17 18:20:56.164  5241  5241 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,11-17 18:20:56.164  1806  5249 I LocationSettingsChecker: Removing dialog suppression flag for package com.example.hello
,11-17 18:20:56.164  1609  1609 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-17 18:20:56.174  1609  1609 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-17 18:20:56.184  1018  1516 I ActivityManager: Killing 4321:com.google.android.talk/u0a102 (adj 15): empty #31
,11-17 18:20:56.194  1806  5277 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
11-17 18:20:56.194  1806  5277 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,11-17 18:20:56.194  1806  5277 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.example.hello.
11-17 18:20:56.194  1806  5277 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,11-17 18:20:56.194  1018  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:20:56.194  1018  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:20:56.194  1018  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:20:56.194  1018  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:20:56.214  1806  5277 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1,
11-17 18:20:56.214  1806  5277 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
11-17 18:20:56.214  1806  5277 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
11-17 18:20:56.214  1806  5277 E SQLiteLog: (3850) statement aborts at 21: [DELETE FROM help_responses WHERE app_package_name="com.example.hello"] disk I/O error
,11-17 18:20:56.214  5283  5283 E Zygote  : MountEmulatedStorage()
,11-17 18:20:56.214  5283  5283 E Zygote  : v2
11-17 18:20:56.214  5283  5283 I libpersona: KNOX_SDCARD checking this for 1000
,11-17 18:20:56.224  5283  5283 I libpersona: KNOX_SDCARD not a persona
11-17 18:20:56.224  1806  5277 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,11-17 18:20:56.224  5258  5258 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
11-17 18:20:56.224  5258  5258 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
11-17 18:20:56.224  5258  5258 D UserAnalysis: Create SecureDbHelper
,11-17 18:20:56.224  5241  5241 D AcmsService: Inside handle Intent
,11-17 18:20:56.224  5241  5241 D AcmsService: App removed - package name: com.example.hello
11-17 18:20:56.224  5241  5241 D AcmsCore: Post to AcmsCoreHandler
11-17 18:20:56.224  5241  5241 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
11-17 18:20:56.224  5241  5241 D AcmsServiceMonitor: Incrementing - Counter value: 3
11-17 18:20:56.224  5241  5241 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>5
11-17 18:20:56.224  5241  5241 D AcmsService: Decremented Counter Value : handleStartIntent
11-17 18:20:56.224  5241  5241 D AcmsServiceMonitor: Decrementing - Counter value: 2
,11-17 18:20:56.234  1018  1516 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=5283 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,11-17 18:20:56.234  1806  5277 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
11-17 18:20:56.234  1806  5277 E AndroidRuntime: Process: com.google.android.gms, PID: 1806
11-17 18:20:56.234  1806  5277 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-17 18:20:56.234  1806  5277 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-17 18:20:56.234  1806  5277 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
11-17 18:20:56.234  1806  5277 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-17 18:20:56.234  1806  5277 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-17 18:20:56.234  1806  5277 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1637)
11-17 18:20:56.234  1806  5277 E AndroidRuntime: 	at com.google.android.gms.googlehelp.c.b.d(SourceFile:535)
11-17 18:20:56.234  1806  5277 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:52)
11-17 18:20:56.234  1806  5277 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
11-17 18:20:56.234  1806  5277 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:20:56.234  1806  5277 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
11-17 18:20:56.234  1806  5277 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-17 18:20:56.234  5258  5258 D IntelligenceServiceApplication: onCreate()
11-17 18:20:56.234  1018  1520 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:20:56.234  1018  1520 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:20:56.234  1018  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:20:56.234  5258  5258 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,11-17 18:20:56.244  5258  5258 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
,11-17 18:20:56.244  1018  1516 I ActivityManager: Killing 4552:com.sec.knox.bridge/1000 (adj 15): empty #31
11-17 18:20:56.244  1018  1476 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,11-17 18:20:56.254  5258  5258 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
11-17 18:20:56.254  5258  5258 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:20:56.254  5258  5258 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:20:56.254  5258  5258 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
11-17 18:20:56.254  5258  5258 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
11-17 18:20:56.254  5258  5258 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
11-17 18:20:56.254  5258  5258 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
11-17 18:20:56.254  5258  5258 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
11-17 18:20:56.254  5258  5258 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
11-17 18:20:56.254  5258  5258 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
11-17 18:20:56.254  5258  5258 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
11-17 18:20:56.254  5258  5258 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
11-17 18:20:56.254  5258  5258 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
11-17 18:20:56.254  5258  5258 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:20:56.254  5258  5258 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-17 18:20:56.254  5258  5258 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
11-17 18:20:56.254  5258  5258 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
11-17 18:20:56.254  5258  5258 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
11-17 18:20:56.254  5258  5258 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-17 18:20:56.254  5258  5258 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
11-17 18:20:56.254  5258  5258 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
11-17 18:20:56.254  5258  5258 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:20:56.254  5258  5258 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:20:56.254  5258  5258 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
11-17 18:20:56.254  5258  5258 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
11-17 18:20:56.254  3550  3550 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
11-17 18:20:56.254  5258  5258 E SQLiteOpenHelper: Couldn't open privacy for writing (will try read-only):
11-17 18:20:56.254  5258  5258 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:20:56.254  5258  5258 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:20:56.254  5258  5258 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectio,n.open(SQLiteConnection.java:318)
11-17 18:20:56.254  5258  5258 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
11-17 18:20:56.254  5258  5258 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
11-17 18:20:56.254  5258  5258 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
11-17 18:20:56.254  5258  5258 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
11-17 18:20:56.254  5258  5258 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
11-17 18:20:56.254  5258  5258 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
11-17 18:20:56.254  5258  5258 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
11-17 18:20:56.254  5258  5258 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
11-17 18:20:56.254  5258  5258 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
11-17 18:20:56.254  5258  5258 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:20:56.254  5258  5258 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-17 18:20:56.254  5258  5258 E SQLiteOpenHelper: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
11-17 18:20:56.254  5258  5258 E SQLiteOpenHelper: 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
11-17 18:20:56.254  5258  5258 E SQLiteOpenHelper: 	at android.os.Handler.handleCallback(Handler.java:739)
11-17 18:20:56.254  5258  5258 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-17 18:20:56.254  5258  5258 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
11-17 18:20:56.254  5258  5258 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
11-17 18:20:56.254  5258  5258 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:20:56.254  5258  5258 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:20:56.254  5258  5258 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
11-17 18:20:56.254  5258  5258 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
11-17 18:20:56.254  5258  5258 W SQLiteOpenHelper: Opened privacy in read-only mode
11-17 18:20:56.254  5258  5258 D IntelligenceServiceApplication: no applications having user consent for prediction
11-17 18:20:56.254  1018  1217 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:20:56.254  1018  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:20:56.254  1018  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
11-17 18:20:56.264  1018  1517 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:20:56.264  1018  1517 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:20:56.264  1018  1517 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
11-17 18:20:56.264  1018  1253 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:20:56.264  1018  1253 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:20:56.264  1018  1253 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
11-17 18:20:56.264  5258  5258 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
11-17 18:20:56.274  1018  1044 W libprocessgroup: failed to open /acct/uid_10035/pid_4202/cgroup.procs: No such file or directory
11-17 18:20:56.274  1018  1044 W libprocessgroup: failed to open /acct/uid_10108/pid_4150/cgroup.procs: No such file or directory
11-17 18:20:56.274  1018  1031 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
11-17 18:20:56.284  5258  5258 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
11-17 18:20:56.284  5258  5258 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
11-17 18:20:56.284  5283  5283 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
11-17 18:20:56.284  5258  5258 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
11-17 18:20:56.284  5258  5258 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:20:56.284  5258  5258 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:20:56.284  5258  5258 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
11-17 18:20:56.284  5258  5258 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
11-17 18:20:56.284  5258  5258 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
11-17 18:20:56.284  5258  5258 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
11-17 18:20:56.284  5258  5258 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
11-17 18:20:56.284  5258  5258 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
11-17 18:20:56.284  5258  5258 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
11-17 18:20:56.284  5258  5258 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
11-17 18:20:56.284  5258  5258 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
11-17 18:20:56.284  5258  5258 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
11-17 18:20:56.284  5258  5258 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:20:56.284  5258  5258 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:20:56.284  5258  5258 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
11-17 18:20:56.284  5258  5258 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
11-17 18:20:56.284  5258  5258 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
11-17 18:20:56.284  5258  5258 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-17 18:20:56.284  5258  5258 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
11-17 18:20:56.284  5258  5258 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
11-17 18:20:56.284  5258  5258 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:20:56.284  5258  5258 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:20:56.284  5258  5258 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
11-17 18:20:56.284  5258  5258 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
11-17 18:20:56.284  5258  5258 D AndroidRuntime: Shutting down VM
11-17 18:20:56.284  5258  5258 E AndroidRuntime: FATAL EXCEPTION: main
11-17 18:20:56.284  5258  5258 E AndroidRuntime: Process: com.samsung.android.intelligenceservice, PID: 5258
11-17 18:20:56.284  5258  5258 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:20:56.284  5258  5258 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:20:56.284  5258  5258 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
11-17 18:20:56.284  5258  5258 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
11-17 18:20:56.284  5258  5258 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
11-17 18:20:56.284  5258  5258 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
11-17 18:20:56.284  5258  5258 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
11-17 18:20:56.284  5258  5258 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
11-17 18:20:56.284  5258  5258 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
11-17 18:20:56.284  5258  5258 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
11-17 18:20:56.284  5258  5258 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
11-17 18:20:56.284  5258  5258 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
11-17 18:20:56.284  5258  5258 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:20:56.284  5258  5258 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:20:56.284  5258  5258 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
11-17 18:20:56.284  5258  5258 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
11-17 18:20:56.284  5258  5258 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-17 18:20:56.284  5258  5258 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-17 18:20:56.284  5258  5258 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
11-17 18:20:56.284  5258  5258 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
11-17 18:20:56.284  5258  5258 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:20:56.284  5258  5258 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:20:56.284  5258  5258 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
11-17 18:20:56.284  5258  5258 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
11-17 18:20:56.284  5283  5283 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
11-17 18:20:56.284  5283  5283 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
11-17 18:20:56.294  1806  5249 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/phenotype.db" with flag (131138) and mode_t (0) due to error (30)
11-17 18:20:56.294  3550  5291 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
11-17 18:20:56.294  3550  5291 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
11-17 18:20:56.294  3550  5291 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:20:56.294  3550  5291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:20:56.294  3550  5291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
11-17 18:20:56.294  3550  5291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
11-17 18:20:56.294  3550  5291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
11-17 18:20:56.294  3550  5291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
11-17 18:20:56.294  3550  5291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
11-17 18:20:56.294  3550  5291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
11-17 18:20:56.294  3550  5291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
,11-17 18:20:56.294  3550  5291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
11-17 18:20:56.294  3550  5291 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
11-17 18:20:56.294  3550  5291 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
11-17 18:20:56.294  3550  5291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:20:56.294  3550  5291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:20:56.294  3550  5291 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
11-17 18:20:56.294  3550  5291 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
11-17 18:20:56.294  3550  5291 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
11-17 18:20:56.294  3550  5291 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:20:56.294  3550  5291 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
11-17 18:20:56.294  3550  5291 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-17 18:20:56.294  3550  5291 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:20:56.294  3550  5291 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:20:56.294  3550  5291 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
11-17 18:20:56.304  1018  5290 E DropBoxManagerService: Can't write: system_app_crash
11-17 18:20:56.304  1018  5290 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop159.tmp: open failed: EROFS (Read-only file system)
11-17 18:20:56.304  1018  5290 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
11-17 18:20:56.304  1018  5290 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-17 18:20:56.304  1018  5290 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-17 18:20:56.304  1018  5290 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-17 18:20:56.304  1018  5290 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
11-17 18:20:56.304  1018  5290 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:15884)
11-17 18:20:56.304  1018  5290 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-17 18:20:56.304  1018  5290 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-17 18:20:56.304  1018  5290 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-17 18:20:56.304  1018  5290 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
11-17 18:20:56.304  1018  5290 E DropBoxManagerService: 	... 5 more
11-17 18:20:56.294  3550  5291 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
11-17 18:20:56.294  3550  5291 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
11-17 18:20:56.294  3550  5291 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
11-17 18:20:56.294  3550  5291 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
11-17 18:20:56.294  3550  5291 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
11-17 18:20:56.294  3550  5291 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
11-17 18:20:56.304  1018  1031 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.sec.knox.bridge/com.sec.knox.bridge.PersonaShortcutReceiver}
11-17 18:20:56.304  1018  1031 W BroadcastQueue: android.os.TransactionTooLargeException
11-17 18:20:56.304  1018  1031 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
11-17 18:20:56.304  1018  1031 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:511)
11-17 18:20:56.304  1018  1031 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
11-17 18:20:56.304  1018  1031 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:309)
11-17 18:20:56.304  1018  1031 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1236)
11-17 18:20:56.304  1018  1031 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20387)
11-17 18:20:56.304  1018  1031 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
11-17 18:20:56.304  1018  1031 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3368)
11-17 18:20:56.304  1018  1031 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:461)
11-17 18:20:56.294  3550  5291 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
11-17 18:20:56.294  3550  5291 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
11-17 18:20:56.304  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:20:56.294  3550  5291 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
11-17 18:20:56.304  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:20:56.294  3550  5291 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:20:56.304  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:20:56.294  3550  5291 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:20:56.304  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:20:56.294  3550  5291 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
11-17 18:20:56.294  3550  5291 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
11-17 18:20:56.294  3550  5291 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
11-17 18:20:56.294  3550  5291 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:20:56.294  3550  5291 W System.err: 	at android.os.Looper.loop(Looper.java:145)
11-17 18:20:56.294  3550  5291 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-17 18:20:56.304  1806  5249 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
11-17 18:20:56.304  1806  5249 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:20:56.304  1806  5249 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:20:56.304  1806  5249 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
11-17 18:20:56.304  1806  5249 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
11-17 18:20:56.304  1806  5249 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
11-17 18:20:56.304  1806  5249 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
11-17 18:20:56.304  1806  5249 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
11-17 18:20:56.304  1806  5249 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
11-17 18:20:56.304  1806  5249 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
11-17 18:20:56.304  1806  5249 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
11-17 18:20:56.304  1806  5249 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
11-17 18:20:56.304  1806  5249 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
11-17 18:20:56.304  1806  5249 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
11-17 18:20:56.304  1806  5249 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:20:56.304  1806  5249 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-17 18:20:56.304  1806  5249 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:68)
11-17 18:20:56.304  1806  5249 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
11-17 18:20:56.304  1806  5249 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:20:56.304  1806  5249 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
11-17 18:20:56.304  1806  5249 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-17 18:20:56.304  5283  5283 D TimaKeyStoreProvider: TimaSignature is unavailable
11-17 18:20:56.304  5283  5283 D ActivityThread: Added TimaKeyStore provider
11-17 18:20:56.314  1806  5249 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
11-17 18:20:56.314  1806  5249 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:20:56.314  1806  5249 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:20:56.314  1806  5249 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
11-17 18:20:56.314  1806  5249 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
11-17 18:20:56.314  1806  5249 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
11-17 18:20:56.314  1806  5249 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
11-17 18:20:56.314  1806  5249 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
11-17 18:20:56.314  1806  5249 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
11-17 18:20:56.314  1806  5249 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
11-17 18:20:56.314  1806  5249 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
11-17 18:20:56.314  1806  5249 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
11-17 18:20:56.314  1806  5249 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
11-17 18:20:56.314  1806  5249 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
11-17 18:20:56.314  1806  5249 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:20:56.314  1806  5249 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-17 18:20:56.314  1806  5249 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:68)
11-17 18:20:56.314  1806  5249 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
11-17 18:20:56.314  1806  5249 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:20:56.314  1806  5249 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
11-17 18:20:56.314  1806  5249 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-17 18:20:56.324  1806  5249 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
11-17 18:20:56.324  5304  5304 E Zygote  : MountEmulatedStorage()
11-17 18:20:56.324  1018  1044 W libprocessgroup: failed to open /acct/uid_10102/pid_4321/cgroup.procs: No such file or directory
11-17 18:20:56.324  5304  5304 E Zygote  : v2
11-17 18:20:56.324  5304  5304 I libpersona: KNOX_SDCARD checking this for 1000
11-17 18:20:56.324  5304  5304 I libpersona: KNOX_SDCARD not a persona
11-17 18:20:56.324  1018  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_4552/cgroup.procs: No such file or directory
```
