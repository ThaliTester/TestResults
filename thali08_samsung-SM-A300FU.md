#### Test 503880190437b9b_thali08_samsung-SM-A300FU Logs


```--------- beginning of system
,11-17 18:01:18.714  1018  1051 I PowerManagerService: [PWL] Off : 15s ago
11-17 18:01:18.804  1018  1058 D PackageManager: [MSG] MCS_UNBIND
11-17 18:01:18.804  1018  1513 I ActivityManager: Killing 3907:com.android.providers.calendar/u0a37 (adj 15): empty #31
11-17 18:01:18.864  1018  1043 W libprocessgroup: failed to open /acct/uid_10037/pid_3907/cgroup.procs: No such file or directory
--------- beginning of main
11-17 18:01:19.004  5061  5061 D AndroidRuntime: 
11-17 18:01:19.004  5061  5061 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
11-17 18:01:19.004  5061  5061 D AndroidRuntime: CheckJNI is OFF
11-17 18:01:19.004  5061  5061 D AndroidRuntime: readGMSProperty: start
11-17 18:01:19.004  5061  5061 D AndroidRuntime: readGMSProperty: already setted!!
11-17 18:01:19.004  5061  5061 D AndroidRuntime: propertySet: couldn't set property (it is from app)
11-17 18:01:19.004  5061  5061 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
11-17 18:01:19.004  5061  5061 D AndroidRuntime: readGMSProperty: end
11-17 18:01:19.004  5061  5061 D AndroidRuntime: addProductProperty: start
11-17 18:01:19.134  5061  5061 E AffinityControl: AffinityControl: registerfunction enter
11-17 18:01:19.164  5061  5061 D AndroidRuntime: Calling main entry com.android.commands.am.Am
11-17 18:01:19.184  1018  1700 E PersonaManagerService: inState():  stateMachine is null !!
11-17 18:01:19.184  1018  1700 I PersonaManagerService: PersonaId don't exist
11-17 18:01:19.184  1018  1700 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
11-17 18:01:19.194  1018  1700 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.example.hello
11-17 18:01:19.204  1018  1700 W ActivityManager: mDVFSHelper.acquire()
11-17 18:01:19.204  1018  1700 D FocusedStackFrame: Set to : 0
11-17 18:01:19.214  1018  1049 D PhoneWindow: *FMB* installDecor mIsFloating : false
11-17 18:01:19.214  1018  1049 D PhoneWindow: *FMB* installDecor flags : 25362712
11-17 18:01:19.214  1018  1700 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:19.214  1018  1700 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:19.214  1018  1700 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:19.214  1018  1700 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:19.234  1018  1700 I ActivityManager: Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5073 uid=10333 gids={50333, 9997, 3003, 3001, 3002} abi=armeabi-v7a
11-17 18:01:19.234  1018  1700 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
11-17 18:01:19.234  1018  1700 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.example.hello
11-17 18:01:19.234  1018  1700 D InputDispatcher: Focused application set to: xxxx
11-17 18:01:19.234  1018  1700 D InputDispatcher: Focus left window: 1477
11-17 18:01:19.234  5073  5073 E Zygote  : MountEmulatedStorage()
11-17 18:01:19.234  5073  5073 I libpersona: KNOX_SDCARD checking this for 10333
11-17 18:01:19.234  5073  5073 E Zygote  : v2
11-17 18:01:19.234  5073  5073 I libpersona: KNOX_SDCARD not a persona
11-17 18:01:19.234  1018  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
11-17 18:01:19.234  1018  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
11-17 18:01:19.234  5073  5073 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
11-17 18:01:19.234   260   260 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, iello
11-17 18:01:19.234  5073  5073 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
11-17 18:01:19.234  5061  5061 D AndroidRuntime: Shutting down VM
11-17 18:01:19.234  5073  5073 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
11-17 18:01:19.244  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
11-17 18:01:19.244  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
11-17 18:01:19.254  5073  5073 D TimaKeyStoreProvider: TimaSignature is unavailable
11-17 18:01:19.254  5073  5073 D ActivityThread: Added TimaKeyStore provider
11-17 18:01:19.254  1018  1281 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
11-17 18:01:19.254  1018  1018 V ActivityManager: Display changed displayId=0
11-17 18:01:19.274  1018  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
11-17 18:01:19.284  1018  1281 D PersonaManager: isKioskContainerExistOnDevice
11-17 18:01:19.294  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
11-17 18:01:19.324   260   450 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
11-17 18:01:19.324   260   448 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
11-17 18:01:19.334  1477  1477 V ActivityThread: updateVisibility : ActivityRecord{2d40d50b token=android.os.BinderProxy@3501177b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
11-17 18:01:19.334  1477  1477 D Launcher: onTrimMemory. Level: 20
11-17 18:01:19.414  5073  5073 I WebViewFactory: Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
11-17 18:01:19.434  5073  5073 I LibraryLoader: Loading: webviewchromium
11-17 18:01:19.444  5061  5061 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,11-17 18:01:19.484  5073  5073 I LibraryLoader: Time to load native libraries: 53 ms (timestamps 6982-7035)
11-17 18:01:19.484  5073  5073 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-17 18:01:19.504  5073  5073 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3df6d87d}
11-17 18:01:19.504  5073  5073 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-17 18:01:19.514  5073  5073 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
11-17 18:01:19.534  5073  5073 I BrowserStartupController: Initializing chromium process, renderers=0
11-17 18:01:19.534  5073  5073 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:01:19.554  5073  5090 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
11-17 18:01:19.564  5073  5073 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
11-17 18:01:19.564  5073  5073 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
11-17 18:01:19.564  5073  5073 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
11-17 18:01:19.584  5073  5094 D BluetoothAdapter: 96367474: getState() :  mService = null. Returning STATE_OFF
11-17 18:01:19.594   298   298 E SMD     : DCD OFF
11-17 18:01:19.604  5073  5073 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
11-17 18:01:19.604  5073  5073 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
11-17 18:01:19.604  5073  5073 I Adreno-EGL: Build Date: 04/06/15 Mon
11-17 18:01:19.604  5073  5073 I Adreno-EGL: Local Branch: 
11-17 18:01:19.604  5073  5073 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
11-17 18:01:19.604  5073  5073 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
11-17 18:01:19.604  5073  5073 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
11-17 18:01:19.714  5073  5100 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
11-17 18:01:19.724  5073  5073 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
11-17 18:01:19.744  5073  5073 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:01:19.754  5073  5073 W AwContents: onDetachedFromWindow called when already detached. Ignoring
11-17 18:01:19.764  5073  5073 D PhoneWindow: *FMB* installDecor mIsFloating : false
11-17 18:01:19.764  5073  5073 D PhoneWindow: *FMB* installDecor flags : 8456448
11-17 18:01:19.764  5073  5073 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
11-17 18:01:19.774  5073  5073 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:01:19.774  5073  5073 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:01:19.784  1018  1044 W ActivityManager: Activity pause timeout for ActivityRecord{16e4830f u0 com.example.hello/.MainActivity t10}
11-17 18:01:19.804  5073  5112 D OpenGLRenderer: Render dirty regions requested: true
11-17 18:01:19.814  1018  1030 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
11-17 18:01:19.814  1018  1030 D KnoxTimeoutHandler: postActiveUserChange for user 0
11-17 18:01:19.814  1018  1030 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
11-17 18:01:19.814  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
11-17 18:01:19.814  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
11-17 18:01:19.814  5073  5073 V ActivityThread: updateVisibility : ActivityRecord{accfd70 token=android.os.BinderProxy@2eb69d22 {com.example.hello/com.example.hello.MainActivity}} show : true
11-17 18:01:19.824  5073  5073 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
11-17 18:01:19.824  5073  5073 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
11-17 18:01:19.874   260   260 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
11-17 18:01:19.884  1018  1212 D InputDispatcher: Focus entered window: 5073
11-17 18:01:19.894  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
11-17 18:01:19.894  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
11-17 18:01:19.894  5073  5073 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
11-17 18:01:19.894  5073  5112 I OpenGLRenderer: Initialized EGL, version 1.4
11-17 18:01:19.904  5073  5112 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
11-17 18:01:19.904  5073  5112 D OpenGLRenderer: Enabling debug mode 0
11-17 18:01:19.924  1018  1514 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
11-17 18:01:19.924  1176  1176 I StatusBar: Icon Only
11-17 18:01:19.934  1176  1176 D PanelView: There is/are notification(s) 
11-17 18:01:19.934  1018  5118 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
11-17 18:01:19.944  5073  5073 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
11-17 18:01:19.944  5073  5073 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2eb69d22 time:67499
11-17 18:01:19.944  1018  1049 I ActivityManager: Displayed Component not be shown by security: +662ms (total +732ms)
11-17 18:01:19.944  1018  1049 W ActivityManager: mDVFSHelper.release()
11-17 18:01:19.954  1755  1755 I SamsungIME: getCurrentCandidateView
11-17 18:01:19.954  1018  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{16e4830f u0 com.example.hello/.MainActivity t10} time:67502
11-17 18:01:19.974   260   448 I SurfaceFlinger: id=11 Removed iello (7/9)
11-17 18:01:19.974   260  4702 I SurfaceFlinger: id=11 Removed iello (-2/9)
11-17 18:01:20.004  1755  1755 D SamsungIME: Dismiss ExpandCandiate
11-17 18:01:20.044  1755  1755 I SamsungIME: getDebugLevel  : 0x4f4c
11-17 18:01:20.104  1755  1755 I SamsungIME: getDebugLevel  : 0x4f4c
11-17 18:01:20.114  5073  5073 I chromium: [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
11-17 18:01:20.114  5073  5120 E AndroidProtocolHandler: Unable to open asset URL: file:///android_asset/www/jxcore.js
11-17 18:01:20.134  1755  1755 I SamsungIME: KeybaordView init() : load resources
11-17 18:01:20.164  1755  1755 I SamsungIME: getCurrentKeyboard
11-17 18:01:20.164  1755  1755 I SamsungIME: getTextKeyboard
11-17 18:01:20.164  5073  5073 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
11-17 18:01:20.174  5073  5073 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
11-17 18:01:20.174  5073  5073 I chromium: 
11-17 18:01:20.184  1755  1755 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,11-17 18:01:20.354  5073  5123 D jxcore_app_log: JniHelper::setJavaVM(0xb8cf0448), pthread_self() = -1188574336
,11-17 18:01:20.354  5073  5123 D JX-Cordova: jxcore cordova android initializing
,11-17 18:01:20.394  5073  5073 W jxcore-log: Initializing JXcore engine
,11-17 18:01:20.394  5073  5073 W jxcore-log: JXcore engine is ready
,11-17 18:01:20.394  5073  5073 W jxcore-log: Starting JXcore engine
,11-17 18:01:20.454  1819  1819 E audit   : type=1400 msg=audit(1447779680.454:203): avc:  denied  { ioctl } for  pid=5073 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,11-17 18:01:20.454  1819  1819 E audit   :  SEPF_SM-A300FU_5.0.2_0027
11-17 18:01:20.454  1819  1819 E audit   : type=1300 msg=audit(1447779680.454:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=bed2ad58 items=0 ppid=318 ppcomm=main pid=5073 auid=4294967295 uid=10333 gid=10333 euid=10333 suid=10333 fsuid=10333 egid=10333 sgid=10333 fsgid=10333 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
11-17 18:01:20.454  1819  1819 E audit   : type=1320 msg=audit(1447779680.454:203): ,
,11-17 18:01:20.574  5073  5073 W jxcore-log: Platform android,
11-17 18:01:20.574  5073  5073 W jxcore-log: 
11-17 18:01:20.574  5073  5073 W jxcore-log: Process ARCH arm
11-17 18:01:20.574  5073  5073 W jxcore-log: 
,11-17 18:01:20.624  5073  5073 I jxcore-log: JXcore Cordova bridge is ready!,
11-17 18:01:20.624  5073  5073 I jxcore-log: 
11-17 18:01:20.624  5073  5073 W jxcore-log: JXcore engine is started
,11-17 18:01:20.624  1018  2552 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,11-17 18:01:20.664  5073  5073 E jxcore-log: >> samsung-SM-A300FU
11-17 18:01:20.664  5073  5073 E jxcore-log: 
,11-17 18:01:20.674  5073  5073 I jxcore-log: Total memory 1451114496,
11-17 18:01:20.674  5073  5073 I jxcore-log: 
11-17 18:01:20.674  5073  5073 I jxcore-log: Free memory 23920640
11-17 18:01:20.674  5073  5073 I jxcore-log: 
11-17 18:01:20.674  5073  5073 I jxcore-log: execPath /data/data/com.example.hello/files/www/jxcore
11-17 18:01:20.674  5073  5073 I jxcore-log: 
11-17 18:01:20.674  5073  5073 I jxcore-log: process.cwd /data/data/com.example.hello/files/www/jxcore
11-17 18:01:20.674  5073  5073 I jxcore-log: ,
,11-17 18:01:20.674  5073  5073 I jxcore-log: userPath [ 'www' ],
11-17 18:01:20.674  5073  5073 I jxcore-log: 
,11-17 18:01:20.684  5073  5073 I jxcore-log: Size 540 960,
11-17 18:01:20.684  5073  5073 I jxcore-log: 
,11-17 18:01:20.684  5073  5073 I jxcore-log: Screen Brightness 255,
11-17 18:01:20.684  5073  5073 I jxcore-log: 
11-17 18:01:20.684  5073  5073 E jxcore-log: Dummy Error Log.
11-17 18:01:20.684  5073  5073 E jxcore-log: 
,11-17 18:01:21.204  5073  5073 I jxcore-log: getBuffer is called!!!!
11-17 18:01:21.204  5073  5073 I jxcore-log: 
,11-17 18:01:22.594   298   298 E SMD     : DCD OFF
,11-17 18:01:23.344  1018  2535 D SSRM:n  : SIOP:: AP = 330
,11-17 18:01:23.654  1018  1044 I ActivityManager: Waited long enough for: ServiceRecord{828918b u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,11-17 18:01:25.594   298   298 E SMD     : DCD OFF,
,11-17 18:01:25.624  1018  2552 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,11-17 18:01:25.694  5073  5073 D BluetoothAdapter: disable()
,11-17 18:01:25.704  1018  1212 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,11-17 18:01:25.724  1018  1513 D SecContentProvider: uri = 18 selection = isWifiEnabled
,11-17 18:01:25.724  1018  1513 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,11-17 18:01:25.724  1018  1513 D SecContentProvider2: mCursor = null
,11-17 18:01:25.724  1018  1513 D WifiService: setWifiEnabled: false pid=5073, uid=10333
,11-17 18:01:25.724  1018  1513 D SettingsProvider: name = wifi_on
,11-17 18:01:25.734  5073  5073 I jxcore-log: ****TEST TOOK:  5066  ms ****
11-17 18:01:25.734  5073  5073 I jxcore-log: 
,11-17 18:01:25.734  5073  5073 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
11-17 18:01:25.734  5073  5073 I jxcore-log: 
,11-17 18:01:26.034  5127  5127 D AndroidRuntime: ,
11-17 18:01:26.034  5127  5127 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,11-17 18:01:26.034  5127  5127 D AndroidRuntime: CheckJNI is OFF,
11-17 18:01:26.034  5127  5127 D AndroidRuntime: readGMSProperty: start
11-17 18:01:26.034  5127  5127 D AndroidRuntime: readGMSProperty: already setted!!
,11-17 18:01:26.034  5127  5127 D AndroidRuntime: propertySet: couldn't set property (it is from app)
11-17 18:01:26.034  5127  5127 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
11-17 18:01:26.034  5127  5127 D AndroidRuntime: readGMSProperty: end
11-17 18:01:26.034  5127  5127 D AndroidRuntime: addProductProperty: start
,11-17 18:01:26.154  5127  5127 E AffinityControl: AffinityControl: registerfunction enter,
,11-17 18:01:26.184  5127  5127 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-17 18:01:26.194  1018  1700 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
11-17 18:01:26.194  1018  1700 D PackageManager: START PACKAGE DELETE: observer{703615489}
11-17 18:01:26.194  1018  1700 D PackageManager: pkg{<packageName>}
11-17 18:01:26.194  1018  1700 D PackageManager: user{0}
11-17 18:01:26.194  1018  1700 D PackageManager: caller{2000}
11-17 18:01:26.194  1018  1700 D PackageManager: flags{3}
11-17 18:01:26.194  1018  1700 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
11-17 18:01:26.194  1018  1058 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
11-17 18:01:26.194  1018  1700 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
11-17 18:01:26.194  1018  1700 D PackageManager: deletePackageAsUser- pkg:com.example.hello, userId:0, flag3,
11-17 18:01:26.194  1018  1700 D PackageManager: deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
11-17 18:01:26.194  1018  1058 D PackageManagerService: deletePackage- pkg:com.example.hello, edmuserId:0
11-17 18:01:26.194  1018  1058 D PackageManagerService: deletePackage- pkg:com.example.hello, edmuserId:-1
11-17 18:01:26.194  1018  1058 D ApplicationPolicy: getApplicationUninstallationEnabled
11-17 18:01:26.194  1018  1058 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,11-17 18:01:26.204  1018  1058 D PackageManager: !@killApplicatoin: 10333, uninstall pkg,
,11-17 18:01:26.224  1018  1044 I ActivityManager: Force stopping com.example.hello appid=10333 user=-1: uninstall pkg
,11-17 18:01:26.224  1018  1044 I ActivityManager: Killing 5073:com.example.hello/u0a333 (adj 0): stop com.example.hello cause uninstall pkg
,11-17 18:01:26.264  1018  1058 W PackageSettings: Skipping PackageSetting{2b984dd8 com.test.thalitest/10326} due to missing metadata
,11-17 18:01:26.284  1018  1044 I ActivityManager:   Force finishing activity ActivityRecord{16e4830f u0 com.example.hello/.MainActivity t10}
,11-17 18:01:26.284  1018  1044 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,11-17 18:01:26.294  1018  1044 D InputDispatcher: Focus left window: 5073
,11-17 18:01:26.294   260   450 I SurfaceFlinger: id=12 Removed NainActivit (6/8)
,11-17 18:01:26.294   260  4702 I SurfaceFlinger: id=12 Removed NainActivit (-2/8)
,11-17 18:01:26.294  1018  1044 D InputDispatcher: Focused application released
,11-17 18:01:26.304  1018  1049 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,11-17 18:01:26.304  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
11-17 18:01:26.304  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,11-17 18:01:26.304  1018  1058 I ActivityManager: Force stopping com.example.hello appid=10333 user=0: pkg removed
,11-17 18:01:26.314  1018  1058 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,11-17 18:01:26.334  3611  3611 I art     : Explicit concurrent mark sweep GC freed 2483(148KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 695us total 29.616ms
,11-17 18:01:26.354  1018  1100 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-17 18:01:26.364  1755  1755 E SamsungIME: mOCRHelper is null
,11-17 18:01:26.384  3365  3365 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Nov 17 18:01:26 GMT+01:00 2015
,11-17 18:01:26.404  3022  3022 I art     : Explicit concurrent mark sweep GC freed 11466(752KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 5MB/7MB, paused 936us total 94.237ms
,11-17 18:01:26.494  1438  1438 D RegisteredServicesCache: empty dynamic service
,11-17 18:01:26.494  1018  1018 I art     : Explicit concurrent mark sweep GC freed 61910(3MB) AllocSpace objects, 15(354KB) LOS objects, 33% free, 22MB/33MB, paused 2.276ms total 177.219ms
11-17 18:01:26.494  1018  1514 I art     : WaitForGcToComplete blocked for 123.746ms for cause Explicit
,11-17 18:01:26.554  1018  1018 D RCPManagerService: PackageReceiver onReceive()
,11-17 18:01:26.554  1018  1018 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,11-17 18:01:26.554  1018  1018 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,11-17 18:01:26.634  1018  1514 I art     : Explicit concurrent mark sweep GC freed 13793(674KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/33MB, paused 2.751ms total 142.415ms
,11-17 18:01:26.634  1018  1058 I art     : WaitForGcToComplete blocked for 255.000ms for cause Explicit
11-17 18:01:26.634  1018  1512 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
11-17 18:01:26.634  1018  1512 D SecContentProvider2: mCursor = null
,11-17 18:01:26.634  1630  1851 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-17 18:01:26.644  1018  1513 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:26.644  1018  1513 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:01:26.644  1018  1513 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,11-17 18:01:26.654  1018  1043 D EnterpriseDeviceManagerService: Package has changed for user 0
11-17 18:01:26.654  1018  1043 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,11-17 18:01:26.654  3365  3365 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,11-17 18:01:26.664  1018  1043 W TextServicesManagerService: no available spell checker services found
,11-17 18:01:26.664  1018  1030 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=30, mBgSplitQueueNum=3 divideNum= 9 r.nextReceiver= 1 receivers.size=39
11-17 18:01:26.664  1018  1030 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,11-17 18:01:26.664  1018  1018 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,11-17 18:01:26.674  1018  1018 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-17 18:01:26.674  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
11-17 18:01:26.674  1018  1018 V EnterpriseBillingPolicy: uID is 10333
11-17 18:01:26.674  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
11-17 18:01:26.674  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
11-17 18:01:26.674  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
11-17 18:01:26.674  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
11-17 18:01:26.674  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
11-17 18:01:26.674  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.example.hello
,11-17 18:01:26.674  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,11-17 18:01:26.674  3365  3365 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,11-17 18:01:26.674  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:26.674  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:26.674  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:26.674  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:26.674  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:01:26.674  3365  3365 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,11-17 18:01:26.684  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:01:26.684  3365  3365 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,11-17 18:01:26.684  5140  5140 E Zygote  : MountEmulatedStorage()
11-17 18:01:26.684  5140  5140 E Zygote  : v2
11-17 18:01:26.684  5140  5140 I libpersona: KNOX_SDCARD checking this for 10090
11-17 18:01:26.684  5140  5140 I libpersona: KNOX_SDCARD not a persona
,11-17 18:01:26.694  5140  5140 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
11-17 18:01:26.694  1018  1030 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5140 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,11-17 18:01:26.694  5140  5140 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
11-17 18:01:26.694  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:01:26.694  5140  5140 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,11-17 18:01:26.694  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:01:26.694  4072  4072 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
,11-17 18:01:26.704  3365  5139 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,11-17 18:01:26.704  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:26.704  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:26.704  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:26.704  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:26.714  3365  5139 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,11-17 18:01:26.724  5155  5155 E Zygote  : MountEmulatedStorage(),
11-17 18:01:26.724  5155  5155 I libpersona: KNOX_SDCARD checking this for 10145
11-17 18:01:26.724  5155  5155 E Zygote  : v2,
11-17 18:01:26.724  5155  5155 I libpersona: KNOX_SDCARD not a persona
11-17 18:01:26.724  5155  5155 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,11-17 18:01:26.724  5155  5155 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
11-17 18:01:26.724  5155  5155 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
11-17 18:01:26.724  1018  1044 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=5155 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
11-17 18:01:26.724  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.example.hello
,11-17 18:01:26.724  3365  5139 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
11-17 18:01:26.724  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
11-17 18:01:26.724  1018  2535 D SSRM:aZ : MSG_TYPE_APP_REMOVED::
11-17 18:01:26.724  1018  1018 V EnterpriseBillingPolicy: uID is 10333
11-17 18:01:26.724  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
11-17 18:01:26.724  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,11-17 18:01:26.734  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
11-17 18:01:26.734  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
11-17 18:01:26.734  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
11-17 18:01:26.734  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.example.hello
,11-17 18:01:26.734  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
11-17 18:01:26.734  1018  1160 D TaskPersister: removeObsoleteFile: deleting file=10_task.xml
,11-17 18:01:26.734  3365  5139 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
,11-17 18:01:26.744  1018  1281 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:26.744  1018  1281 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:01:26.744  1018  1281 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,11-17 18:01:26.744  5140  5140 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:01:26.744  5140  5140 D ActivityThread: Added TimaKeyStore provider
,11-17 18:01:26.764  4929  4929 D FilterInstaller: onReceive:android.intent.action.PACKAGE_REMOVED, package:com.example.hello
11-17 18:01:26.764  4929  4929 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,11-17 18:01:26.774  1018  1512 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:26.774  1018  1512 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:01:26.774  1018  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,11-17 18:01:26.774  5155  5155 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:01:26.774  5155  5155 D ActivityThread: Added TimaKeyStore provider
,11-17 18:01:26.784  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:26.784  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:01:26.784  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,11-17 18:01:26.794  4072  5169 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
11-17 18:01:26.794  4072  5169 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
,11-17 18:01:26.794  1018  1513 I TactileAssist: enable value -1
11-17 18:01:26.794  1018  1513 I TactileAssist: internal enable value -1
11-17 18:01:26.794  1018  1513 I TactileAssist: intensity value -1
11-17 18:01:26.794  1018  1513 I TactileAssist: saveAppList value true
,11-17 18:01:26.804  1018  1513 I TactileAssist: List of disabled apps :
,11-17 18:01:26.814  1018  1058 I art     : Explicit concurrent mark sweep GC freed 7274(423KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 22MB/33MB, paused 3.021ms total 171.495ms
,11-17 18:01:26.814  1018  1474 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:26.824  1018  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:01:26.824  1018  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
11-17 18:01:26.824  4929  4929 I FilterInstaller: FilterPackageService : ACTION_PACKAGE_REMOVED
,11-17 18:01:26.824  4929  5171 I FilterInstaller: FilterPackageService : ACTION_REMOVED
,11-17 18:01:26.824  3365  5139 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
11-17 18:01:26.824  4929  5171 D FilterUnInstaller: before removeFromFS
,11-17 18:01:26.824  1018  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:26.834  1018  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:26.834  1018  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:26.834  1018  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:26.834  1018  1043 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,11-17 18:01:26.844  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:01:26.844  5140  5140 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
11-17 18:01:26.844  5140  5140 D elm:15121: ELMEngine.ELMEngine( context ).
11-17 18:01:26.844  1018  1476 I ActivityManager: Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=5172 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
11-17 18:01:26.844  3365  3365 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,11-17 18:01:26.854  5172  5172 E Zygote  : MountEmulatedStorage()
,11-17 18:01:26.854  5172  5172 E Zygote  : v2
11-17 18:01:26.854  5172  5172 I libpersona: KNOX_SDCARD checking this for 10095
11-17 18:01:26.854  5172  5172 I libpersona: KNOX_SDCARD not a persona
,11-17 18:01:26.854  5172  5172 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,11-17 18:01:26.854  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:01:26.854  5172  5172 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
11-17 18:01:26.854  5172  5172 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
11-17 18:01:26.854  1018  1513 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:26.854  1018  1513 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:01:26.854  1018  1513 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:26.864  5155  5155 D ThemeInfoUtil: getCurrentFestivalName is [null]
11-17 18:01:26.864  5155  5155 D ThemeInfoUtil: isCurrentFestival = false
,11-17 18:01:26.864  1018  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:26.864  1018  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:26.864  1018  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:26.864  1018  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:26.864  5140  5140 D elm:15121: MDMBridge.setEnterpriseBridge()
,11-17 18:01:26.874  1018  1058 D PackageManager: delete codoeFile: 
,11-17 18:01:26.874  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:01:26.874  1018  1058 D AASAuninstall: userId = 0, info.removedAppID = -1, info.uid = 10333, packageName = com.example.hello
,11-17 18:01:26.874  1018  1058 I AASA_removePackage: UID=10333 Target=com.example.hello
,11-17 18:01:26.874  1018  1058 D PackageManager: result of delete: 1{703615489}
,11-17 18:01:26.884  1018  1043 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
11-17 18:01:26.884  1018  1043 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
11-17 18:01:26.884  1018  1043 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,11-17 18:01:26.884  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:01:26.884  5185  5185 E Zygote  : MountEmulatedStorage()
11-17 18:01:26.884  5185  5185 E Zygote  : v2
11-17 18:01:26.884  5185  5185 I libpersona: KNOX_SDCARD checking this for 1000
11-17 18:01:26.884  5185  5185 I libpersona: KNOX_SDCARD not a persona
11-17 18:01:26.884  5185  5185 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
11-17 18:01:26.884  1018  1475 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5185 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,11-17 18:01:26.884  1018  1281 W ActivityManager: userId = 0, bbcId = -10000,
11-17 18:01:26.884  1018  1281 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:01:26.884  1018  1281 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
11-17 18:01:26.884  5127  5127 D AndroidRuntime: Shutting down VM
11-17 18:01:26.894  5185  5185 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
11-17 18:01:26.894  5185  5185 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
11-17 18:01:26.894  5172  5172 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:01:26.894  5140  5140 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
11-17 18:01:26.894  5172  5172 D ActivityThread: Added TimaKeyStore provider
,11-17 18:01:26.904  1018  1474 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:26.904  1018  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:01:26.904  1018  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:26.904  5140  5140 D elm:15121: ElmAgentService : onCreate()
11-17 18:01:26.904  5140  5192 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
11-17 18:01:26.904  5140  5192 D elm:15121: MainReceiver.listeningToPackageRemoved()
11-17 18:01:26.904  5140  5192 D elm:15121: MDMBridge.getInstance()
11-17 18:01:26.904  5140  5192 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,11-17 18:01:26.914  5140  5192 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,11-17 18:01:26.924  1018  1212 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:26.924  1018  1212 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:01:26.924  1018  1212 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:26.924  4819  4819 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
11-17 18:01:26.924  4819  4819 I PCWCLIENTTRACE_PushUtil: sales region : global
11-17 18:01:26.924  4819  4819 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
11-17 18:01:26.924  4819  4819 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,11-17 18:01:26.924  5185  5185 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:01:26.934  5185  5185 D ActivityThread: Added TimaKeyStore provider
,11-17 18:01:26.944  1018  1514 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:26.944  1018  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:01:26.944  1018  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,11-17 18:01:26.944  4899  4899 D Compatibility: onReceive() it will make start service
11-17 18:01:26.944  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:01:26.944  5172  5172 D PreloadFilterInstaller: uses FILTER_DB_VER_1
,11-17 18:01:26.944  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:01:26.944  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:26.944  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,11-17 18:01:26.954  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,11-17 18:01:26.954  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:01:26.954  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,11-17 18:01:26.954  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:01:26.954  5172  5172 E SQLiteLog: (284) automatic index on titles(filter_id)
,11-17 18:01:26.954  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,11-17 18:01:26.954  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,11-17 18:01:26.964  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:01:26.964  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,11-17 18:01:26.964  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
11-17 18:01:26.964  5185  5185 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
11-17 18:01:26.964  4899  5204 D Compatibility: onHandleIntent()
11-17 18:01:26.964  4899  5204 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10333, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,11-17 18:01:26.964  1018  1467 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:26.964  1018  1467 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:01:26.964  1018  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,11-17 18:01:26.974  4899  5204 D Compatibility: found: 2
11-17 18:01:26.974  4899  5204 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
11-17 18:01:26.974  4899  5204 D Compatibility: skipping ResolveInfo{23fc54be com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
11-17 18:01:26.974  4899  5204 D Compatibility: considering ResolveInfo{3d36291f com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
11-17 18:01:26.974  4899  5204 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,11-17 18:01:26.974  1018  1043 D UsbSettingsManager: clearDefaults: com.example.hello
11-17 18:01:26.974  1018  1043 I CrashAnrDetector: onPackageRemoved : com.example.hello
,11-17 18:01:26.974  1018  1512 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:26.974  1018  1512 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:01:26.974  1018  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,11-17 18:01:26.974  4899  5204 D Compatibility: enabling receiver ResolveInfo{3d91246c com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
11-17 18:01:26.974  5140  5140 D elm:15121: ElmAgentService : onDestroy().
,11-17 18:01:26.974  4899  5204 D Compatibility: enabling receiver ResolveInfo{76d9a35 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,11-17 18:01:26.984  5172  5183 E SQLiteLog: (284) automatic index on titles(filter_id)
,11-17 18:01:26.994  4782  4782 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
11-17 18:01:26.994  4782  4782 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,11-17 18:01:26.994  4782  4782 I TapandpayWidget:Utils: Clear T&P info.
11-17 18:01:26.994  4782  4782 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,11-17 18:01:26.994  4899  5204 D Compatibility: enabling receiver ResolveInfo{8a4feca com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,11-17 18:01:27.004  4899  5204 D Compatibility: enabling receiver ResolveInfo{e1e383b com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,11-17 18:01:27.004  1018  1212 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:27.004  1018  1212 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:01:27.004  1018  1212 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,11-17 18:01:27.014  4899  5204 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,11-17 18:01:27.014  1018  1476 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:27.014  1018  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:01:27.014  1018  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,11-17 18:01:27.014  1018  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:27.014  1018  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:27.014  1018  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:27.014  1018  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:27.024  3022  5208 I UpdateIcingCorporaServi: Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,11-17 18:01:27.034  5209  5209 E Zygote  : MountEmulatedStorage(),
11-17 18:01:27.034  5209  5209 I libpersona: KNOX_SDCARD checking this for 1000
11-17 18:01:27.034  5209  5209 E Zygote  : v2
11-17 18:01:27.034  5209  5209 I libpersona: KNOX_SDCARD not a persona
11-17 18:01:27.034  5209  5209 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,11-17 18:01:27.034  5209  5209 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,11-17 18:01:27.034  5209  5209 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,11-17 18:01:27.034  1018  1475 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5209 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,11-17 18:01:27.044  1018  1476 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:27.044  1018  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:01:27.044  1018  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:27.054  1018  1281 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:27.054  1018  1281 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:01:27.054  1018  1281 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:27.054  5209  5209 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:01:27.054  5209  5209 D ActivityThread: Added TimaKeyStore provider
,11-17 18:01:27.054  1018  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:27.064  1018  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:27.064  1018  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:27.064  1018  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:27.074  5224  5224 E Zygote  : MountEmulatedStorage()
11-17 18:01:27.074  5224  5224 E Zygote  : v2
11-17 18:01:27.074  5224  5224 I libpersona: KNOX_SDCARD checking this for 10032
11-17 18:01:27.074  5224  5224 I libpersona: KNOX_SDCARD not a persona
,11-17 18:01:27.074  5224  5224 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,11-17 18:01:27.074  5224  5224 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,11-17 18:01:27.084  1018  1475 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=5224 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,11-17 18:01:27.084  5224  5224 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,11-17 18:01:27.104  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:27.104  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:01:27.104  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,11-17 18:01:27.104  1018  1475 I ActivityManager: Killing 4481:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,11-17 18:01:27.104  5127  5127 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,11-17 18:01:27.124  1018  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:27.124  1018  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:27.124  1018  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:27.124  1018  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:27.124  5224  5224 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:01:27.124  5224  5224 D ActivityThread: Added TimaKeyStore provider
,11-17 18:01:27.134  5239  5239 E Zygote  : MountEmulatedStorage()
11-17 18:01:27.134  5239  5239 E Zygote  : v2
11-17 18:01:27.134  5239  5239 I libpersona: KNOX_SDCARD checking this for 10055
11-17 18:01:27.134  5239  5239 I libpersona: KNOX_SDCARD not a persona
11-17 18:01:27.134  5239  5239 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
11-17 18:01:27.144  5239  5239 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
11-17 18:01:27.144  1018  1475 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=5239 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
11-17 18:01:27.144  5239  5239 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
11-17 18:01:27.144  5209  5245 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_REMOVED
11-17 18:01:27.144  1018  1475 I ActivityManager: Killing 4190:com.sec.android.app.music:service/u0a35 (adj 15): empty #31
11-17 18:01:27.144  5209  5245 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,11-17 18:01:27.154   318   318 I art     : Explicit concurrent mark sweep GC freed 8718(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 598us total 20.253ms
,11-17 18:01:27.164  5239  5239 D TimaKeyStoreProvider: TimaSignature is unavailable
,11-17 18:01:27.164  5239  5239 D ActivityThread: Added TimaKeyStore provider
,11-17 18:01:27.164  1018  1513 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:27.164  1018  1513 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:01:27.164  1018  1513 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,11-17 18:01:27.164  1018  1476 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:27.164  1018  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:01:27.164  1018  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,11-17 18:01:27.164  1018  1514 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:27.164  1018  1514 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:01:27.164  1018  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:27.174  1801  5255 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,11-17 18:01:27.174  1801  5255 D AccountUtils: Clearing selected account for com.example.hello
11-17 18:01:27.174  1018  1467 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:27.174  1018  1467 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:01:27.174  1018  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,11-17 18:01:27.174   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 16.962ms
,11-17 18:01:27.174  1018  1212 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:27.174  1018  1212 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:01:27.174  1018  1212 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
11-17 18:01:27.174  5209  5209 D AcmsService: Enter Oncreate
11-17 18:01:27.174  5209  5209 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
11-17 18:01:27.174  5209  5209 D AcmsService: creating AcmsCore
11-17 18:01:27.174  5209  5209 D AcmsCore: AcmsCore.getAcmsCore() - Enter
11-17 18:01:27.174  5209  5209 D AcmsCore: AcmsCore
,11-17 18:01:27.184  5209  5209 D AcmsCore: init
11-17 18:01:27.184  5209  5209 D AcmsCore: Looper handler is not null
11-17 18:01:27.184  5209  5209 D AcmsCore: Post to AcmsCoreHandler
11-17 18:01:27.184  5209  5209 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
11-17 18:01:27.184  5209  5209 D AcmsServiceMonitor: Incrementing - Counter value: 1
11-17 18:01:27.184  5209  5209 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
11-17 18:01:27.184  5209  5209 D AcmsService: onStartCommand
11-17 18:01:27.184  5209  5209 D AcmsService: Action: android.intent.action.PACKAGE_REMOVED
11-17 18:01:27.184  5209  5209 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
11-17 18:01:27.184  5209  5209 D AcmsServiceMonitor: Incrementing - Counter value: 2
11-17 18:01:27.184  5209  5209 D AcmsService: Incremented Counter Value : onStartCommand
,11-17 18:01:27.184  1018  1476 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:27.184  1018  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:01:27.184  1018  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,11-17 18:01:27.194   318   318 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 18.497ms
,11-17 18:01:27.194  5209  5209 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,11-17 18:01:27.194  5209  5258 D AcmsCertificateMngr: AcmsCertificateMngr
11-17 18:01:27.194  5209  5258 D AcmsRevocationMngr: AcmsRevocationMngr
,11-17 18:01:27.204  1018  1514 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:27.204  1018  1514 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:01:27.204  1018  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
11-17 18:01:27.214  5209  5209 W FileUtils: Failed to chmod(/data/data/com.samsung.android.app.mirrorlink/databases/pkgnamedb): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,11-17 18:01:27.214  3022  5208 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
11-17 18:01:27.214  3022  5208 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,11-17 18:01:27.214  4929  5171 I FilterUnInstaller: FilterUninstaller.java : removeFromDB()
,11-17 18:01:27.214  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:27.214  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:01:27.214  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:27.214  1018  1467 W ActivityManager: userId = 0, bbcId = -10000,
11-17 18:01:27.214  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_4481/cgroup.procs: No such file or directory
11-17 18:01:27.214  1018  1467 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:01:27.214  1018  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,11-17 18:01:27.224  3022  5208 E IcingCorporaProvider: Exception thrown from notifyTableChanged
11-17 18:01:27.224  3022  5208 E IcingCorporaProvider: java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-17 18:01:27.224  3022  5208 E IcingCorporaProvider: 	at beg.a(PG:301)
11-17 18:01:27.224  3022  5208 E IcingCorporaProvider: 	at beg.c(PG:222)
11-17 18:01:27.224  3022  5208 E IcingCorporaProvider: 	at cun.b(PG:660)
11-17 18:01:27.224  3022  5208 E IcingCorporaProvider: 	at cun.a(PG:651)
11-17 18:01:27.224  3022  5208 E IcingCorporaProvider: 	at cun.g(PG:597)
11-17 18:01:27.224  3022  5208 E IcingCorporaProvider: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
11-17 18:01:27.224  3022  5208 E IcingCorporaProvider: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:340)
11-17 18:01:27.224  3022  5208 E IcingCorporaProvider: 	at android.content.ContentResolver.update(ContentResolver.java:1386)
11-17 18:01:27.224  3022  5208 E IcingCorporaProvider: 	at cuw.Tg(PG:368)
11-17 18:01:27.224  3022  5208 E IcingCorporaProvider: 	at cuy.ub(PG:301)
11-17 18:01:27.224  3022  5208 E IcingCorporaProvider: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
11-17 18:01:27.224  3022  5208 E IcingCorporaProvider: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
11-17 18:01:27.224  3022  5208 E IcingCorporaProvider: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
11-17 18:01:27.224  3022  5208 E IcingCorporaProvider: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:01:27.224  3022  5208 E IcingCorporaProvider: 	at android.os.Looper.loop(Looper.java:145)
11-17 18:01:27.224  3022  5208 E IcingCorporaProvider: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-17 18:01:27.224  3022  5208 E IcingCorporaProvider: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-17 18:01:27.224  3022  5208 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
11-17 18:01:27.224  3022  5208 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
11-17 18:01:27.224  3022  5208 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
11-17 18:01:27.224  3022  5208 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
11-17 18:01:27.224  3022  5208 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
11-17 18:01:27.224  3022  5208 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
11-17 18:01:27.224  3022  5208 E IcingCorporaProvider: 	at bea.a(PG:382)
11-17 18:01:27.224  3022  5208 E IcingCorporaProvider: 	at beg.i(PG:325)
11-17 18:01:27.224  3022  5208 E IcingCorporaProvider: 	at beh.call(PG:215)
11-17 18:01:27.224  3022  5208 E IcingCorporaProvider: 	at beg.a(PG:299)
11-17 18:01:27.224  3022  5208 E IcingCorporaProvider: 	... 15 more
11-17 18:01:27.224  3022  5208 W IcingCorporaProvider: notifyTableChanged failed.
11-17 18:01:27.224  3022  5208 W IcingCorporaProvider: Table change notification failed for TableStorageSpec[applications]
11-17 18:01:27.224  3022  5208 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 199 ms] updated apps [took 199 ms] 
,11-17 18:01:27.224  1018  1043 W libprocessgroup: failed to open /acct/uid_10035/pid_4190/cgroup.procs: No such file or directory
,11-17 18:01:27.224  5172  5183 D FilterProvider: delete when PACKAGE_NAME : 2002 
11-17 18:01:27.224  5172  5183 D FilterProvider: packageName : com.example.hello
,11-17 18:01:27.234  1018  1476 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:27.234  1018  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:01:27.234  1018  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:27.244  5209  5209 D AcmsService: Inside handle Intent
11-17 18:01:27.244  5209  5209 D AcmsService: App removed - package name: com.example.hello
11-17 18:01:27.244  5209  5209 D AcmsCore: Post to AcmsCoreHandler
11-17 18:01:27.244  5209  5209 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
11-17 18:01:27.244  5209  5209 D AcmsServiceMonitor: Incrementing - Counter value: 3
11-17 18:01:27.244  5209  5209 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>5
11-17 18:01:27.244  5209  5209 D AcmsService: Decremented Counter Value : handleStartIntent
11-17 18:01:27.244  5209  5209 D AcmsServiceMonitor: Decrementing - Counter value: 2
,11-17 18:01:27.244  1018  1700 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:27.244  1018  1700 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:27.244  1018  1700 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:27.244  1018  1700 E ActivityManager: checkUser: useridlist=null, currentuser=0
,11-17 18:01:27.254  1801  1801 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.gms
,11-17 18:01:27.264  5224  5262 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
11-17 18:01:27.264  5224  5262 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,11-17 18:01:27.264  5239  5239 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,11-17 18:01:27.264  5264  5264 E Zygote  : MountEmulatedStorage(),
11-17 18:01:27.264  5264  5264 E Zygote  : v2
11-17 18:01:27.264  5264  5264 I libpersona: KNOX_SDCARD checking this for 1000
11-17 18:01:27.264  5264  5264 I libpersona: KNOX_SDCARD not a persona
,11-17 18:01:27.264  5264  5264 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,11-17 18:01:27.274  5264  5264 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
11-17 18:01:27.274  1018  1700 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=5264 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
11-17 18:01:27.274  5264  5264 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,11-17 18:01:27.274  4929  5171 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.filterinstaller.FilterUninstaller.uninstallFilters:48 com.samsung.android.app.filterinstaller.FilterPackageService$ServiceHandler.handleMessage:152 android.os.Handler.dispatchMessage:102 
,11-17 18:01:27.274  1018  1476 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:27.274  1018  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:01:27.274  1018  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
11-17 18:01:27.284  5224  5262 D SPPClientService: PushLog.txt file is not deleted.
11-17 18:01:27.284  5224  5262 D SPPClientService: PushLog.txt file is not deleted.
11-17 18:01:27.284  5224  5262 D SPPClientService: ============PushLog. stop!
,11-17 18:01:27.294  4886  4886 I SA      : [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
11-17 18:01:27.294  4886  4886 I SA      : [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10333 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
11-17 18:01:27.294  5224  5224 E SQLiteLog: (28) failed to open "/data/data/com.sec.spp.push/databases/push_noti_db" with flag (131138) and mode_t (0) due to error (30)
,11-17 18:01:27.294  1018  1514 I ActivityManager: Killing 4138:com.google.android.music:main/u0a108 (adj 15): empty #31
11-17 18:01:27.294  5224  5224 E SQLiteDatabase: Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.
11-17 18:01:27.294  5224  5224 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:01:27.294  5224  5224 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:01:27.294  5224  5224 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
11-17 18:01:27.294  5224  5224 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
11-17 18:01:27.294  5224  5224 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
11-17 18:01:27.294  5224  5224 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
11-17 18:01:27.294  5224  5224 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
11-17 18:01:27.294  5224  5224 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
11-17 18:01:27.294  5224  5224 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
11-17 18:01:27.294  5224  5224 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
11-17 18:01:27.294  5224  5224 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
11-17 18:01:27.294  5224  5224 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
11-17 18:01:27.294  5224  5224 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:01:27.294  5224  5224 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:01:27.294  5224  5224 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.a.b.<init>(Unknown Source)
11-17 18:01:27.294  5224  5224 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.a.b.a(Unknown Source)
11-17 18:01:27.294  5224  5224 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.n.b(Unknown Source)
11-17 18:01:27.294  5224  5224 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.n.a(Unknown Source)
11-17 18:01:27.294  5224  5224 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.a(Unknown Source)
11-17 18:01:27.294  5224  5224 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.a(Unknown Source)
11-17 18:01:27.294  5224  5224 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.i.handleMessage(Unknown Source)
11-17 18:01:27.294  5224  5224 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:01:27.294  5224  5224 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
11-17 18:01:27.294  5224  5224 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
11-17 18:01:27.294  5224  5224 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:01:27.294  5224  5224 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:01:27.294  5224  5224 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
11-17 18:01:27.294  5224  5224 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
11-17 18:01:27.294  5224  5224 E LNoti   : [b] open fail. SQLException occured
,11-17 18:01:27.294  1018  1700 I ActivityManager: Killing 4311:com.google.android.talk/u0a102 (adj 15): empty #31
11-17 18:01:27.304  1018  1467 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:27.304  1018  1467 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:01:27.304  1018  1467 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
11-17 18:01:27.314  5264  5264 D TimaKeyStoreProvider: TimaSignature is unavailable
11-17 18:01:27.314  5264  5264 D ActivityThread: Added TimaKeyStore provider
11-17 18:01:27.314  1018  1512 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:27.314  1018  1512 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:01:27.314  1018  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
11-17 18:01:27.314  5239  5239 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
11-17 18:01:27.314  5239  5239 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
11-17 18:01:27.314  5239  5239 D UserAnalysis: Create SecureDbHelper
11-17 18:01:27.314  1617  1617 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
11-17 18:01:27.314  1617  1617 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
11-17 18:01:27.324  1018  1031 I ActivityManager: Killing 4538:com.sec.knox.bridge/1000 (adj 15): empty #31
11-17 18:01:27.324  1801  5261 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/metrics.db" with flag (131138) and mode_t (0) due to error (30)
,11-17 18:01:27.334  1801  5261 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
11-17 18:01:27.334  1801  5261 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:01:27.334  1801  5261 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:01:27.334  1801  5261 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
11-17 18:01:27.334  1801  5261 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
11-17 18:01:27.334  1801  5261 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
11-17 18:01:27.334  1801  5261 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
11-17 18:01:27.334  1801  5261 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
11-17 18:01:27.334  1801  5261 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
11-17 18:01:27.334  1801  5261 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
11-17 18:01:27.334  1801  5261 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
11-17 18:01:27.334  1801  5261 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
11-17 18:01:27.334  1801  5261 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
11-17 18:01:27.334  1801  5261 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:01:27.334  1801  5261 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-17 18:01:27.334  1801  5261 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
11-17 18:01:27.334  1801  5261 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
11-17 18:01:27.334  1801  5261 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
11-17 18:01:27.334  1801  5261 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
11-17 18:01:27.334  1801  5261 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
11-17 18:01:27.334  1801  5261 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:01:27.334  1801  5261 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
11-17 18:01:27.334  1801  5261 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-17 18:01:27.334  4210  4210 I PackagesMonitor: PackagesMonitor onReceive :com.example.hello
,11-17 18:01:27.334  1801  5261 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
11-17 18:01:27.334  1801  5261 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:01:27.334  1801  5261 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:01:27.334  1801  5261 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
11-17 18:01:27.334  1801  5261 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
11-17 18:01:27.334  1801  5261 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
11-17 18:01:27.334  1801  5261 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
11-17 18:01:27.334  1801  5261 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
11-17 18:01:27.334  1801  5261 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
11-17 18:01:27.334  1801  5261 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
11-17 18:01:27.334  1801  5261 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
11-17 18:01:27.334  1801  5261 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
11-17 18:01:27.334  1801  5261 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
11-17 18:01:27.334  1801  5261 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:01:27.334  1801  5261 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-17 18:01:27.334  1801  5261 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
11-17 18:01:27.334  1801  5261 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
11-17 18:01:27.334  1801  5261 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
11-17 18:01:27.334  1801  5261 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
11-17 18:01:27.334  1801  5261 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
11-17 18:01:27.334  1801  5261 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:01:27.334  1801  5261 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
11-17 18:01:27.334  1801  5261 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-17 18:01:27.334  1801  5261 W SQLiteOpenHelper: Opened metrics.db in read-only mode
11-17 18:01:27.334  1801  5261 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,11-17 18:01:27.334  1801  5261 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,11-17 18:01:27.344  1801  5261 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.example.hello"] attempt to write a readonly database
,11-17 18:01:27.344  4210  4210 E SharedPreferencesImpl: Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,11-17 18:01:27.344  1801  5255 I LocationSettingsChecker: Removing dialog suppression flag for package com.example.hello
,11-17 18:01:27.354  1018  1476 W ActivityManager: userId = 0, bbcId = -10000
,11-17 18:01:27.354  1018  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:01:27.354  1018  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:27.364  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:27.364  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:01:27.364  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:27.364  1018  1513 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:27.364  1018  1513 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
11-17 18:01:27.364  1018  1513 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,11-17 18:01:27.374  1801  5255 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/phenotype.db" with flag (131138) and mode_t (0) due to error (30)
,11-17 18:01:27.374  5239  5239 D IntelligenceServiceApplication: onCreate()
,11-17 18:01:27.384  5239  5239 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,11-17 18:01:27.384  5239  5239 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
,11-17 18:01:27.384  5239  5239 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
11-17 18:01:27.384  5239  5239 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:01:27.384  5239  5239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:01:27.384  5239  5239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
11-17 18:01:27.384  5239  5239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
11-17 18:01:27.384  5239  5239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
11-17 18:01:27.384  5239  5239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
11-17 18:01:27.384  5239  5239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
11-17 18:01:27.384  5239  5239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
11-17 18:01:27.384  5239  5239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
11-17 18:01:27.384  5239  5239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
11-17 18:01:27.384  5239  5239 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
11-17 18:01:27.384  5239  5239 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
11-17 18:01:27.384  5239  5239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:01:27.384  5239  5239 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-17 18:01:27.384  5239  5239 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
11-17 18:01:27.384  5239  5239 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
11-17 18:01:27.384  5239  5239 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
11-17 18:01:27.384  5239  5239 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-17 18:01:27.384  5239  5239 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
11-17 18:01:27.384  5239  5239 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
11-17 18:01:27.384  5239  5239 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:01:27.384  5239  5239 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:01:27.384  5239  5239 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
11-17 18:01:27.384  5239  5239 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,11-17 18:01:27.384  5239  5239 E SQLiteOpenHelper: Couldn't open privacy for writing (will try read-only):
11-17 18:01:27.384  5239  5239 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:01:27.384  5239  5239 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:01:27.384  5239  5239 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
11-17 18:01:27.384  5239  5239 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
11-17 18:01:27.384  5239  5239 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
11-17 18:01:27.384  5239  5239 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
11-17 18:01:27.384  5239  5239 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
11-17 18:01:27.384  5239  5239 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
11-17 18:01:27.384  5239  5239 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
11-17 18:01:27.384  5239  5239 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
11-17 18:01:27.384  5239  5239 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
11-17 18:01:27.384  5239  5239 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
11-17 18:01:27.384  5239  5239 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:01:27.384  5239  5239 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-17 18:01:27.384  5239  5239 E SQLiteOpenHelper: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
11-17 18:01:27.384  5239  5239 E SQLiteOpenHelper: 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
11-17 18:01:27.384  5239  5239 E SQLiteOpenHelper: 	at android.os.Handler.handleCallback(Handler.java:739)
11-17 18:01:27.384  5239  5239 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-17 18:01:27.384  5239  5239 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
11-17 18:01:27.384  5239  5239 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
11-17 18:01:27.384  5239  5239 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:01:27.384  5239  5239 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:01:27.384  5239  5239 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
11-17 18:01:27.384  5239  5239 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,11-17 18:01:27.384  5239  5239 W SQLiteOpenHelper: Opened privacy in read-only mode
,11-17 18:01:27.384  5264  5264 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,11-17 18:01:27.384  5239  5239 D IntelligenceServiceApplication: no applications having user consent for prediction
,11-17 18:01:27.394  3560  3560 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,11-17 18:01:27.394  1018  1043 W libprocessgroup: failed to open /acct/uid_10108/pid_4138/cgroup.procs: No such file or directory
11-17 18:01:27.394  1018  1043 W libprocessgroup: failed to open /acct/uid_10102/pid_4311/cgroup.procs: No such file or directory
11-17 18:01:27.394  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_4538/cgroup.procs: No such file or directory
,11-17 18:01:27.394  1018  1474 W ActivityManager: userId = 0, bbcId = -10000
11-17 18:01:27.394  1018  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
11-17 18:01:27.394  1018  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,11-17 18:01:27.394  5239  5239 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,11-17 18:01:27.394  1018  1281 D SecContentProvider2: uri = -1 selection = getSealedState
11-17 18:01:27.394  1018  1281 D SecContentProvider2: mCursor = null
,11-17 18:01:27.394  5264  5264 I PopupuiReceiver_KNOX: getSealedState : true
,11-17 18:01:27.394  1018  1512 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
11-17 18:01:27.394  1018  1512 D SecContentProvider2: mCursor = null
,11-17 18:01:27.404  5264  5264 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
,11-17 18:01:27.404  1018  1476 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
11-17 18:01:27.404  1018  1476 D SecContentProvider2: mCursor = null
11-17 18:01:27.404  5264  5264 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
11-17 18:01:27.404  5264  5264 D PopupuiReceiver: Action package removed
,11-17 18:01:27.404  1801  5261 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
11-17 18:01:27.404  1617  1617 D AndroidRuntime: Shutting down VM
11-17 18:01:27.404  1801  5261 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
11-17 18:01:27.404  1801  5261 E AndroidRuntime: Process: com.google.android.gms, PID: 1801
11-17 18:01:27.404  1801  5261 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
11-17 18:01:27.404  1801  5261 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-17 18:01:27.404  1801  5261 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
11-17 18:01:27.404  1801  5261 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-17 18:01:27.404  1801  5261 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-17 18:01:27.404  1801  5261 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1637)
11-17 18:01:27.404  1801  5261 E AndroidRuntime: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
11-17 18:01:27.404  1801  5261 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
11-17 18:01:27.404  1801  5261 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
11-17 18:01:27.404  1801  5261 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:01:27.404  1801  5261 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
11-17 18:01:27.404  1801  5261 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-17 18:01:27.404  1617  1617 E AndroidRuntime: FATAL EXCEPTION: main
11-17 18:01:27.404  1617  1617 E AndroidRuntime: Process: com.google.process.gapps, PID: 1617
11-17 18:01:27.404  1617  1617 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-17 18:01:27.404  1617  1617 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3132)
11-17 18:01:27.404  1617  1617 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
11-17 18:01:27.404  1617  1617 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
11-17 18:01:27.404  1617  1617 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:01:27.404  1617  1617 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
11-17 18:01:27.404  1617  1617 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
11-17 18:01:27.404  1617  1617 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:01:27.404  1617  1617 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:01:27.404  1617  1617 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
11-17 18:01:27.404  1617  1617 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
11-17 18:01:27.404  1617  1617 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-17 18:01:27.404  1617  1617 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-17 18:01:27.404  1617  1617 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
11-17 18:01:27.404  1617  1617 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-17 18:01:27.404  1617  1617 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-17 18:01:27.404  1617  1617 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1637)
11-17 18:01:27.404  1617  1617 E AndroidRuntime: 	at com.google.android.gms.gcm.bq.a(SourceFile:310)
11-17 18:01:27.404  1617  1617 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
11-17 18:01:27.404  1617  1617 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
11-17 18:01:27.404  1617  1617 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
11-17 18:01:27.404  1617  1617 E AndroidRuntime: 	... 9 more
11-17 18:01:27.404  1018  1700 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:27.404  1018  1700 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:27.404  1018  1700 E ActivityManager: checkUser: useridlist=null, currentuser=0
11-17 18:01:27.404  1018  1700 E ActivityManager: checkUser: useridlist=null, currentuser=0
```
